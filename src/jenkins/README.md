# jenkins

실행
* docker run --name jenkins --privileged -d -p 32769:8080 -v /jenkins:/var/jenkins_home -v $(which docker):/usr/bin/docker -v /var/run/docker.sock:/var/run/docker.sock -u root jobjava00/jenkins:latest 
