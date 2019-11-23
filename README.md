# DockerLearn
learning docker


To navigate into the root directory, use "cd /"
To navigate to your home directory, use "cd" or "cd ~"
To navigate up one directory level, use "cd .."
To navigate to the previous directory (or back), use "cd -"




installing docker
https://docs.docker.com/install/linux/docker-ce/ubuntu/
sudo apt-get install  curl apt-transport-https ca-certificates software-properties-common
 curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt update
sudo apt install docker-ce

6. Check Docker Status
Once the installation is complete, it is a good idea to check the status of the service.

sudo systemctl status docker

sudo docker run hello-world

https://docs.docker.com/compose/install/#install-compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
