# SCA-Cloud-School-Application
## This is my SCA Cloud School Application Repo

Step 1:I created an Index.html and Dockerfile as attached in the repository

Step 2:To Build the Docker image for the HTML server i used the command below: docker build -t sca-cloud-html-image .

Step 3: To confirm the i used the command " docker images" to list and the output shows as below:

Step 4:To run the docker container i used the 

command docker run -d -p 80:80 sca-cloud-html-image

![image](https://user-images.githubusercontent.com/56696638/125689591-2d916ecc-074d-46ff-b35f-4e7c86a76053.png)

Once done, run the container and test the application. Kindly Describe your test process and provide output
The result is as follows: docker run -d -p 80:80 sca-cloud-html-image
![image](https://user-images.githubusercontent.com/56696638/125690015-df08349a-8f01-4418-8a5a-f1161d9f23cc.png)

Step 5:I viewed it in the browser using localhost:80
![image](https://user-images.githubusercontent.com/56696638/125690342-b200d94b-3d9e-449c-b2cb-ffdfa8868f7a.png)
