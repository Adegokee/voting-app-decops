# Use official Python 3.12.5 image
FROM python:3.12.5

# Set working directory
WORKDIR /app

# Copy project files to the container
COPY . /app/

# Install dependencies (note the corrected file name: requirements.txt)
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 8080
EXPOSE 8080

# Correct CMD syntax and Django runserver command
CMD ["python", "manage.py", "runserver", "0.0.0.0:8080"]
