registry-haproxy
================

registry for docker images


Install haproxy proxy in registry, only for docker pulling for internet user,

docker push only for private network.


### Run registry

80 for pull from internet, 5000 for push from private ip

```docker run -d -p 80:8088 -p 127.0.0.1:5000:5000 nicescale/registry-haproxy```


