# SCA-Cloud-School-Application
## This is my SCA Cloud School Application Repo

Step 1:I created an Index.html and Dockerfile as attached in the repository

Step 2:To Build the Docker image for the HTML server i used the command below: docker build -t sca-cloud-html-image .

Step 3: To confirm, i used the command " docker images" to list and the output shows as below

Step 4:To run the docker container i used the command 

docker run -d -p 80:80 sca-cloud-html-image

![image](https://user-images.githubusercontent.com/56696638/125689591-2d916ecc-074d-46ff-b35f-4e7c86a76053.png)

Once done, I run the container and test the application. 

docker run -d -p 80:80 sca-cloud-html-image

![image](https://user-images.githubusercontent.com/56696638/125690015-df08349a-8f01-4418-8a5a-f1161d9f23cc.png)

Step 5:I viewed it in the browser using localhost:80


![image](https://user-images.githubusercontent.com/56696638/125690342-b200d94b-3d9e-449c-b2cb-ffdfa8868f7a.png)

Step 6: Created a branch named Start and a folder named docker

![image](https://user-images.githubusercontent.com/56696638/125690945-18db353d-c1a8-46aa-a915-f3d91e0f8d62.png)


6: I Commit my Dockerfile and other files used in the docker folder

![image](https://user-images.githubusercontent.com/56696638/125691188-e9a854e9-61de-45ca-840e-1e88157c719a.png)



![image](https://user-images.githubusercontent.com/56696638/125691288-5c6b40fb-fcdc-4b8a-9de3-e51a1008c134.png)


I updated the Dockerfile so the webpage displays Welcome to SCA Cloud School Application , this is my first assessment

![image](https://user-images.githubusercontent.com/56696638/125691541-72955d17-4d73-4900-8d20-5ed890d487f0.png)

![image](https://user-images.githubusercontent.com/56696638/125691699-5d8b1ba5-bec5-4a24-abc6-d45bb4adee1a.png)


![image](https://user-images.githubusercontent.com/56696638/125691785-3746ee7d-95ff-4168-b906-ad5da45a8403.png)


![image](https://user-images.githubusercontent.com/56696638/125691875-2f104bbd-d277-4a34-8ced-a1c9212d3ab1.png)


![image](https://user-images.githubusercontent.com/56696638/125692113-df3cf340-84ae-4147-8909-df7364eff480.png)

I Commit these changes to the repo into a branch called feature and Merged feature branch to the start branch ( do not delete the feature branch)

![image](https://user-images.githubusercontent.com/56696638/125693469-0ef9e14b-818d-4535-a877-59dffab3664b.png)

![image](https://user-images.githubusercontent.com/56696638/125693781-00180aaf-8f99-495d-9496-978d4c7bc954.png)


I pushed my final docker image to dockerhub (https://hub.docker.com/)


![image](https://user-images.githubusercontent.com/56696638/125692254-081446fe-6ca4-4abc-bdc0-3def3d6c6a72.png)


