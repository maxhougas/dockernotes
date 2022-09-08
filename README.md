# Docker Notes
## Install Docker
 - apt install docker.io
## Install Docker Engine
 - https://docs.docker.com/engine/install/debian/ is pretty good
 - You may need to change https://unix.stackexchange.com/questions/630643/how-to-install-docker-ce-in-kali-linux
```
  echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
 - to
```
  echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian \
  buster stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
 
## Commands
 - docker build -t [tag] .
 - docker exec -it [mycontainer] [shell] https://stackoverflow.com/questions/30172605/how-do-i-get-into-a-docker-containers-shell
 - docker run -dp [external]:[internal] [tag]
 - docker rename [old name] [new name] https://www.tecmint.com/name-docker-containers/
 - docker run -d --name [name] [image]

## Resources
 - https://docs.docker.com/get-started/
 - https://labs.play-with-docker.com/#
 - https://www.geeksforgeeks.org/docker-docker-container-for-node-js/
 - https://stackoverflow.com/questions/30172605/how-do-i-get-into-a-docker-containers-shell
 - https://jpetazzo.github.io/2020/02/01/quest-minimal-docker-images-part-1/
