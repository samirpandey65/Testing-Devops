#OS
FROM python:3.7

#Dir
WORKDIR /app

#Copy
COPY . /app

#Li
RUN pip install -r requirments.txt

#RUN
RUN python cool_counters/manage.py migrate


#CMD
CMD ["python", "cool_counters/manage.py", "runserver", "0.0.0.0:8000"]
