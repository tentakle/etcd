# etcd
```
sudo docker-compose up -d && sudo docker exec etcd /bin/sh -c "export ETCDCTL_API=3 && etcdctl member list"
sudo docker-compose up -d && sudo docker exec etcd /bin/sh -c "etcdctl cluster-health"
```
