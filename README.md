
### redis-trib  
    * redis-trib:  

    ```shell
    ../redis-6.0.6/src/redis-trib.rb \
    create \
    --replicas 1 \
    127.0.0.1:30001 \
    127.0.0.1:30002 \
    127.0.0.1:30003 \
    127.0.0.1:30004 \
    127.0.0.1:30005 \
    127.0.0.1:30006
    ```
    * redis-cli  
    ```shell
    ../redis-6.0.6/src/redis-cli --cluster \
    create \
    127.0.0.1:30001 \
    127.0.0.1:30002 \
    127.0.0.1:30003 \
    127.0.0.1:30004 \
    127.0.0.1:30005 \
    127.0.0.1:30006 \
    --cluster-replicas 1
    ```
