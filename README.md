# Pet Clinic
The .github/workflows folder contains a Github Actions workflow which resolves depdencies, builds and tests the image, which is then uploaded to Docker hub, at https://hub.docker.com/repository/docker/jeffabbott/testing/general.  The image can be easily deployed using the following command:

sudo docker run --name my_container -p 8080:80 -d jeffabbott/testing:latest
