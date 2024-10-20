# Use a Python base image
FROM python:latest

# Set the working directory
WORKDIR /app

# Copy your application code
COPY . .

# Install dependencies
RUN pip install --upgrade pip
RUN python -m venv .venv
RUN .venv/bin/pip install -r requirements.txt

# Run the application
CMD ["python", "Jarvis/jarvis.py"]

