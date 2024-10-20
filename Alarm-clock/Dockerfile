##OS
FROM python:3.7

##DIR
WORKDIR /app

##COPY
COPY . .

##LIB
RUN pip install .

##RUN
RUN python Alarm_clock.py migrate

##CMD
CMD ["python", "Alarm_clock.py"]
