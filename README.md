# Capacity
```
du --block-size=MiB --max-depth=1 | sort -rn
```

# Docker
```
docker save <image> | bzip2 | ssh user@host docker load

sudo docker build -t test:test .
docker run -it  --entrypoint=bash test:test
```
# Bash
```
set +o history

echo 'set +o history' >> ~/.bashrc
. ~/.bashrc

echo 'set +o history' >> /etc/profile
```
