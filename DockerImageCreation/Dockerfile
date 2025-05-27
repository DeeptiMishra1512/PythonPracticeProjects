#This is a basic DockerFile to understand how the process of creating Docker Images work
# Use a lightweight Python base image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /main

# Copy your Python script into the container
COPY main.py .

# Run the script when the container starts
CMD ["python", "main.py"]

LABEL authors="Deepti Mishra"