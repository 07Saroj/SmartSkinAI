# Use official Python image
FROM python:3.10-slim

WORKDIR /app

# Copy dependency file first
COPY requirements.txt .

# Install all Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy all backend files
COPY . .

# Expose Flask port
EXPOSE 5000

# Run the Flask app
CMD ["python", "app3.py"]
