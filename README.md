# Aesthisia-Assesment

# Download Docker installation Package 
ref: get.docker.com
then run downloaded script

# StartDocker
systemctl start Docker

When the Docker is up and running, use this above Dockerfile to build a Docker image

# Build Docker image
cmd: docker build -t <user-name>/<****> .
  
# Create Docker Container
cmd: docker container run -dt --name <**> -p 3000:80 <image id>
  
Now we can the use the application in an container application format on the port 3000.
we can check by <localhost:3000> or <ipaddress:3000>
