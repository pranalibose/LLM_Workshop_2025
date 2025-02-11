FROM python:3.9-slim-buster

WORKDIR /workdir

COPY requirements.txt .
RUN pip install -r requirements.txt

# Copy your project files (optional, but good practice)
COPY . /workdir

# Set the working directory inside the container
WORKDIR /workdir

# You can add other configurations here if needed