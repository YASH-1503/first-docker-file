Firstly install the docker and start the Docker daemon and grant acess to the user.
Then apply following Instructions.

1. Clone the repository:
       -> https://github.com/YASH-1503/first-docker-file.git
       -> cd first-docker-file
2. Build the Docker image:
        docker build -t image-name .
3. Run the Docker container:
       docker run -d -p 8000:8000 your-image-name
