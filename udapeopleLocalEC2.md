### install Node.js
`apt install build-essential nodejs npm`

### Clone repo

Run `npm i` for backend and frontend

### Docker and Docker compose:

`curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -`

```
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
```

`sudo apt update && sudo apt upgrade`

`sudo apt install docker-ce docker-ce-cli containerd.io`

`sudo docker run hello-world`

`sudo curl -L "https://github.com/docker/compose/releases/download/1.26.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`

`sudo chmod +x /usr/local/bin/docker-compose`

`docker-compose --version`

```
cd util
sudo docker-compose up -d
```

```
sudo docker-compose ps
sudo docker-compose logs
sudo docker-compose pause
sudo docker-compose unpause
sudo docker-compose stop
```

### Modify compose file to include pgAdmin
