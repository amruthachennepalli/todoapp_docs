# Redis :

Update and Install redis server

```
# apt update
# apt install redis-server
# sed -i -e 's/127.0.0.1/0.0.0.0/' /etc/redis/redis.conf
```    

Finally start the service once to effect the changes by the below cammand.

```	
# systemctl restart redis
```	
