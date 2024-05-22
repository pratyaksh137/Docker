# BASE Image
FROM ubuntu:latest

# Define the work directory {Work directory is within the generated image}
WORKDIR /app

#copy the content of your host directory to workdir
COPY . /app

# Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

#Set ENV variables
ENV NAME World

#Run command to start the application 
CMD ["python3", "app.py"]

#for base image you can even add the pyhton-buster image to bypass the loading of ubuntu image
