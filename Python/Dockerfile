# Use the Python 3.8 image as base image
FROM python:3.8

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install Flask
RUN pip install Flask

# Expose port 8080
EXPOSE 8080

# Run the application
CMD ["python", "app.py"]
