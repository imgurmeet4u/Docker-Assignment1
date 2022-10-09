# 15 basic Docker commands

## Commands----

1) docker version<br>
•	This command is used to get the currently installed version of docker.<br>
• Ex- <b>docker --version</b><br>
![](images/docker_version.JPG)<br>

###############################################################################################################################################################

2) docker pull<br>
•	This command is used to pull images from the docker.<br>
• Ex- <b>docker pull (image name)</b> (from the git hub repository)<br>
![](images/docker_pull.JPG)<br>

###############################################################################################################################################################

3)	docker run<br>
•	This command is used to create a container from an image.<br>
•	Ex- <b>docker run -d (image name)</b><br>
![](images/docker_run.JPG)<br>

###############################################################################################################################################################

4) docker ps<br>
•	This command is used to list the running containers.<br>
•	Ex- <b>docker ps </b> <br>
![](images/docker_ps.JPG)<br>

###############################################################################################################################################################

5)	docker ps -a <br>
•	This command is used to show all the running and exited containers.<br>
  •	Ex- <b>docker ps -a</b> <br>
![](images/docker_ps_a.JPG)<br>

###############################################################################################################################################################

6)	docker exec<br>
•	This command is used to access the running container.<br>
•	Ex- <b>docker exec -it (container id) bash</b> <br>
![](images/docker_exec.JPG)<br>

###############################################################################################################################################################

7)	docker stop<br>
•	This command stops a running container.<br>
• Ex- <b>docker stop (container id)</b><br>
![](images/docker_stop.JPG)<br>

###############################################################################################################################################################

8)	docker kill<br>
•	This command kills the container by stopping its execution immediately.. <br>
•	The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too       much time for getting the container to stop, one can opt to kill it. <br>
•	Ex- <b>docker kill (container id)</b><br>
![](images/docker_kill.JPG)<br>

###############################################################################################################################################################

9)	docker login<br>
•	This command is used to login to the docker hub repository.<br>
•	Ex- <b>docker login</b><br>
![](images/docker_login.JPG)<br>

###############################################################################################################################################################

10)	docker commit<br>
•	This command creates a new image of an edited container on the local system.<br>
•	Ex- <b>docker commit (container id) (username/imagename)</b><br>
![](images/docker_commit.JPG)<br>

###############################################################################################################################################################

11)	docker images<br>
•	This command lists all the locally stored docker images. <br>
•	Ex- <b>docker images</b><br>
![](images/docker_images.JPG)<br>

###############################################################################################################################################################

12)	docker push<br>
•	This command is used to push an image to the docker hub repository.<br>
•	Ex- <b>docker push (username/image name):tag </b><br>
![](images/docker_push.JPG)<br>

###############################################################################################################################################################

13)	docker rm<br>
•	This command is used to delete a stopped container.<br>
•	Ex- <b>docker rm (container id)</b><br>
![](images/docker_rm.JPG)<br>

###############################################################################################################################################################

14)	docker rmi<br>
•	This command is used to delete an image from local storage.<br>
•	Ex- <b>docker rmi (image-id)</b> <br>
![](images/docker_rmi.JPG)<br>

###############################################################################################################################################################

15)	docker build<br>
• This command is used to build an image from a specified docker file.<br>
• Ex- <b>docker build (path to docker file)</b><br>
![](images/docker_build.JPG)<br>

###############################################################################################################################################################
