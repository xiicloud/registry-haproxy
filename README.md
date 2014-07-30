registry-haproxy
================

Registry only support pulling images from internet.


Install haproxy in registry, only support docker images pulling from internet,

You can only push to registry from private network.


### Run registry

Port 80 for pulling from internet, 5000 for pushing from private ip

```docker run -d -p 80:8088 -p 127.0.0.1:5000:5000 nicescale/registry-haproxy```


