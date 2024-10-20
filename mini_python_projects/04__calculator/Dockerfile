# Base image
FROM python:3.7

# Set the working directory
WORKDIR /app

# Copy the application code into the container
COPY . .

# Install necessary packages
RUN apt-get update && \
    apt-get install -y xvfb python3-tk && \
    rm -rf /var/lib/apt/lists/*

# Upgrade pip and install Python dependencies (if there are any)
RUN pip install --upgrade pip

# Set up the virtual display and run the application
CMD Xvfb :99 -ac & export DISPLAY=:99 && python3 calculator.py 0.0.0.0:8000

