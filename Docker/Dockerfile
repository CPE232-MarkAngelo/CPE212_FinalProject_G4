# Base image
FROM python:3.9-slim

# Working directory
WORKDIR /app

# Copy application files
COPY Group4.py .
COPY templates/ /app/templates/
COPY static/ /app/static/
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Application port
EXPOSE 5000

# Run the application 
CMD ["python", "Group4.py"]

