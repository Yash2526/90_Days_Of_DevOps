# Day 16 Answers: Docker for DevOps Engineers

### Docker

Docker is a software platform that allows you to build, test, and deploy applications quickly. Docker packages software into standardized units called containers that have everything the software needs to run, including libraries, system tools, code, and runtime. Using Docker, you can quickly deploy and scale applications into any environment and know your code will run.

## Tasks with Answers

As you have already installed Docker in previous tasks, now is the time to run Docker commands.

### 1. Use the `docker run` command to start a new container and interact with it through the command line. [Hint: `docker run hello-world`]

**Answer**
   - This command runs the `hello-world` image, which prints a message confirming that Docker is working correctly.
![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%201.png)

### 2. Use the `docker inspect` command to view detailed information about a container or image.

**Answer**
   - View Detailed Information About a Container or Image:

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%202.png)

### 3. Use the `docker port` command to list the port mappings for a container.

**Answer**
   - This command maps port 8181 on the host to port 82 in the container and lists the port mappings.

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%203.png)

### 4. Use the `docker stats` command to view resource usage statistics for one or more containers.

**Answer**
   - This command provides a live stream of resource usage statistics for all running containers.

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%204.png)

### 5. Use the `docker top` command to view the processes running inside a container.

**Answer**
   - This command lists the processes running inside the `my_container2` container.

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%205.png)

### 6. Use the `docker save` command to save an image to a tar archive.

**Answer**
   - This command saves the `nginx` image to a tar archive named `my_image.tar`.

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%206.png)

### 7. Use the `docker load` command to load an image from a tar archive.

**Answer**
   - This command loads the image from the `my_image.tar` archive into Docker.

![image](https://github.com/Yash2526/90_Days_Of_DevOps/blob/master/2024/day16/Task_images/Task%207.png)

These tasks involve simple operations that can be used to manage images and containers.

For reference, you can watch this video: [Docker Tutorial on AWS EC2 as DevOps Engineer // DevOps Project Bootcamp Day 2](https://youtu.be/Tevxhn6Odc8).

** KEEP LEARNING & KEEP EXPLORING **
