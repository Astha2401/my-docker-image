# Use an existing base image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the .py file to the container
COPY helloworld.py .

# Install dependencies
RUN pip install requests

# Specify the command to run when the container starts
CMD ["python", "helloworld.py"]
