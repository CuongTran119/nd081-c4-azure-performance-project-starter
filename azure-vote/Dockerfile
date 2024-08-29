# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.9
# Copy the content of the current directory to the /app of the container
ADD . /app
# Install depndencies 
RUN pip install -r /app/requirements.txt
