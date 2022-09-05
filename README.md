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
## Resources
 - https://docs.docker.com/get-started/
 - https://labs.play-with-docker.com/#
