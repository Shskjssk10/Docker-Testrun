# Docker-Testrun
Testing out Docker

## Step 1: 
Build the image. (username)/(imageName):(version) .
docker build -t cadentoh10/dockertestrun:1.1 .

## Step 2:
Find the created image ID
docker images 

## Step 3: 
Run the image in a contianer
docker run (imageID)