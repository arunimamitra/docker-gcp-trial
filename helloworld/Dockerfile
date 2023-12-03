# Using pytorch's base image (latest version by default)
FROM python:latest

# Copying the application files to container
COPY . /app

# Setting working directory
WORKDIR /app

# Root privileges granted
USER root

# Command to run once container starts - arguments passed
# no-cuda - to disable cuda training,
# no-mps - to disable MacOS gpu training
# epochs and batchsize
CMD ["python", "firstprog_auro.py"]