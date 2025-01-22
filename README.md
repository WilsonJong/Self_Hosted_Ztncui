# Self_Hosted_Ztncui

### 1. Build the docker container.
```
docker run --name ztncui -dp 3443:3443 keynetworks/ztncui
```

### 2. Execute to docker to find the default password.
```
docker exec -it docker_id bash

cat /var/log/docker-ztncui.log
```

### 3. Log in to the website.
```
https://localhost:3443
```

### 4. Change the default password.
