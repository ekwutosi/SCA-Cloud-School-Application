# SCA-Cloud-School-Application
## This is my SCA Cloud School Application Repo

Step 1:I created an Index.html and Dockerfile as attached in the repository

Step 2:To Build the Docker image for the HTML server i used the command below: docker build -t sca-cloud-html-image .

Step 3: To confirm the i used the command " docker images" to list and the output shows as below:

Step 4:To run the docker container i used the command docker run -d -p 80:80 sca-cloud-html-image

