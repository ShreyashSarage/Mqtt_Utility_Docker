<<<<<<< HEAD
# Use the official Python image as the base image
FROM python:3.10-slim   

# Set the working directory in the container
WORKDIR /app

# Copy the Python script into the container
COPY ./sender_influx/influx_sender.py .
COPY ./sender_influx/config.py .

# Install any dependencies required by the subscriber script
RUN pip install paho-mqtt influxdb-client

# Command to run the subscriber script
CMD ["python", "influx_sender.py"]
=======
# Use the official Python image as the base image
FROM python:3.10-slim   

# Set the working directory in the container
WORKDIR /app

# Copy the Python script into the container
COPY ./sender_influx/influx_sender.py .
COPY ./sender_influx/config.py .

# Install any dependencies required by the subscriber script
RUN pip install paho-mqtt influxdb-client

# Command to run the subscriber script
CMD ["python", "influx_sender.py"]
>>>>>>> 30f65f0b13604b300aea5de2e93116e9a56e06cb
