## network
#### 查看端口
```
netstat -ntpl
```

## systom
#### 查看系统版本信息
```
lsb_release -a
uname -a
cat /proc/version
```

#### 设置locale
```
localedef -c -i zh_CN -f UTF-8 zh_CN.UTF-8
export LANG=zh_CN.utf8
locale
```

## docker
```
docker ps
docker ps -a
docker rm
docker rmi
docker build --force-rm -t wuzimei/img_laoximen_web:1.0 ./
docker run -d {image_id} {command}
docker exec -it {image_id} /bin/bash
```

## file
#### 
```
```
