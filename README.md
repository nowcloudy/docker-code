# Create the Docker image
docker build -t flask-app .

# Create and start a container from the image
docker run -p 5000:5000 flask-app
