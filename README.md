# Docker Wordpress
Run a wordpress store locally.

# How to Run
- Be sure to have docker installed
- Run  `yarn compose`
- Open the website on `http://localhost:8000` and configure your store

# Useful Links
- [Adding and Managing Products](https://docs.woocommerce.com/document/managing-products/)
- [Docker Commands](https://gist.github.com/daniloab/dbea32701e323975bf2d4d51a48f33b5)
- [Quickstart: Compose and WordPress](https://docs.docker.com/samples/wordpress/)

---
## Docker 
### Purge all
```
sudo docker stop $(sudo docker ps -aq)
sudo docker rm $(sudo docker ps -aq)
sudo docker rmi $(sudo docker images -aq)
```
```
sudo docker stop $(sudo docker ps -aq) && sudo docker rm $(sudo docker ps -aq) && sudo docker rmi $(sudo docker images -aq)
```

### Run Docker image
```
sudo docker-compose up -d
```