FROM python:3.10-slim

WORKDIR /app

COPY requirements.txt *.py .

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# start the app.py file when the container starts
CMD ["python", "app.py"]
