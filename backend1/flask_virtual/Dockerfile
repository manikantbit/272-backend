# FROM python:3.4-alpine
# Build an image starting with the Python 3.6 image.
FROM python:3.6

# Add the current directory . into the path /code in the image.
ADD . /code

# Set the working directory to /code.
WORKDIR /code

# Install the Python dependencies.
RUN pip3 install -r requirements.txt

# Expose Port
EXPOSE 5000

# Set the default command for the container to python app.py.
CMD ["python3", "flaskApp.py"]



