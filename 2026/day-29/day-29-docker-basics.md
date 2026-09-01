# Task 3
## 1. Nginx
docker run -d --name my-nginx -p 8080:80 nginx

## 2. Check running containers
docker ps

## 3. Open http://localhost:8080 in your browser

## 4. Start Ubuntu interactively
docker run -it --name my-ubuntu ubuntu

### Inside Ubuntu:
```
cat /etc/os-release
pwd
ls
whoami
exit
```

## 5. List ALL containers
docker ps -a

## 6. Stop Nginx
docker stop my-nginx

## 7. Remove Nginx
docker rm my-nginx

## 8. Check everything
docker ps -a

# Task 4