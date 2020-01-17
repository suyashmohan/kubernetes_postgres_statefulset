This repo shows how to setup postgres on kubernetes using statefulsets

```
sudo microk8s.kubectl run psql -it --rm=true --image=postgres:12 --command -- psql -h 10.152.183.15 -U amazinguser awesomedb
```
