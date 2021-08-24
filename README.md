# Ubuntu-SSH winth NVM, Node.js and GIT
# Arquivo docker-composer

Set up:
```bash
git clone https://github.com/franciscodara/docker-composer_sample.git
cd docker-composer_sample
docker-compose up -d
```
Show ports:
```bash
docker container port <container>
```

Connectition ssh:
```bash
ssh root@localhost -p <port>