Download and install 
https://github.com/docker/toolbox/releases/

File name : DockerToolbox-19.03.1.exe

Then check docker ps on cmd

STEP 1:
docker pull cloudera/quickstart:latest

Step 2:
docker run --hostname=quickstart.cloudera --privileged=true -t -i -v /home/mariam/project:/src -p 8888:8888 -p 80:80 -p 7180:7180 cloudera/quickstart /usr/bin/docker-quickstart

STEP 3:
browse hue localhost:8888
