# Day 17 Answers: Docker Project for DevOps Engineers

### You people are doing just amazing in **#90daysofdevops**. Today's challenge is so special because you are going to do a DevOps project with Docker. Are you excited? 😍

# Dockerfile

Docker is a tool that makes it easy to run applications in containers. Containers are like small packages that hold everything an application needs to run. To create these containers, developers use something called a Dockerfile.

A Dockerfile is like a set of instructions for making a container. It tells Docker what base image to use, what commands to run, and what files to include. For example, if you were making a container for a website, the Dockerfile might tell Docker to use an official web server image, copy the files for your website into the container, and start the web server when the container starts.

For more about Dockerfile, visit [here](https://rushikesh-mashidkar.hashnode.dev/dockerfile-docker-compose-swarm-and-volumes).

## Tasks with Answers

**1. Create a Dockerfile for a simple web application (e.g. a Node.js or Python app)**
   - **1. Create a Simple nodejs Application**

      **Answer**

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Task1-Created%20Docker%20file%20for%20a%20nodejs%20web%20app.png)


**2. Build the image using the Dockerfile and run the container**
   - To build the Docker image, run the following command:
   docker container run -d -p 3000:3000 yash2526/hey-nodejs:0.0.1.RELEASE 

      **Answer**

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Task%202.2.png)

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Task%202.3.png)

**3. Verify that the application is working as expected by accessing it in a web browser**
   - Open your web browser and navigate to `http://localhost:3000`. You should see the message "hey-nodejs".

      **Answer**

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Task%202.1.png)

**4. Push the image to a public or private repository (e.g. Docker Hub)**
   - To push the image to Docker Hub, you need to tag it with your Docker Hub username and repository name, then push it.
   - **1. Tag the Image**

      **Answer**

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Task3-Push%20the%20image%20to%20the%20Docker-hub.png)

   - **2. Push the Image**

      **Answer**

      ![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day17/Task_images/Screenshot%202024-10-30%20145038.png)

For a reference project, visit [here](https://youtu.be/Tevxhn6Odc8).

If you want to dive further, watch this [bootcamp](https://youtube.com/playlist?list=PLlfy9GnSVerRqYJgVYO0UiExj5byjrW8u).

You can share your learning with everyone over LinkedIn and tag us along. 😃

Happy Learning :)

[Code for Reference](https://raw.githubusercontent.com/Bhavin213/90DaysOfDevOps/master/2024/day17/code.txt)

