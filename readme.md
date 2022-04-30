1- run the Docker app on mac
2- open a command line and navigate to this folder
3- Build the image using this command
docker build -t streamlitapp:latest .
4- Then run the image file with the following command
docker run -d -p 8501:8501 streamlitapp
5- Go to the Docker tool and open the app


Note: the 8501:8501 has to match what was exposed in the Dockerfile
Note: You can check all the running containers with: docker ps -a
