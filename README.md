# grpc_plugins
Grpc compiled plugins


Chek releases

```
# Download plugins compiled
RUN wget https://github.com/pablodz/grpc_plugins/releases/download/v1.0.0/grpc_plugins.zip -O /grpc_plugins.zip ;\
    unzip  /grpc_plugins.zip -d /grpc_plugins ;\
    cp /grpc_plugins/* /usr/local/bin/
```
