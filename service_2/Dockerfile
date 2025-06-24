# Use official Python 3.13 image (currently in beta/rc at the time of writing)
FROM python:3.13-rc-slim

# Set working directory
WORKDIR /app

# Copy source code
COPY . .

# Install specific Flask version
RUN pip install --no-cache-dir flask==3.1.1

# Expose port
EXPOSE 8002

# Run the app
CMD ["python", "app.py"]

