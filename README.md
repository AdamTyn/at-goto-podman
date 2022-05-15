### at-goto-podman

```toml
# 可以 quick-use.registries.conf 文件后直接替换 /etc/containers/registries.conf 文件
# 这个 docker.mirrors.ustc.edu.cn 可以修改为其他镜像源

unqualified-search-registries = ["docker.io", "docker.mirrors.ustc.edu.cn"]

[[registry]]
prefix="docker.io"
location="docker.mirrors.ustc.edu.cn"

[aliases]
"python"="docker.mirrors.ustc.edu.cn/library/python"
"php"="docker.mirrors.ustc.edu.cn/library/php"
"nginx"="docker.mirrors.ustc.edu.cn/library/nginx"
"openresty"="docker.mirrors.ustc.edu.cn/openresty/openresty"
"openresty/openresty"="docker.mirrors.ustc.edu.cn/openresty/openresty"
"postgres"="docker.mirrors.ustc.edu.cn/library/postgres"
"pgadmin"="docker.mirrors.ustc.edu.cn/dpage/pgadmin4"
"pgadmin4"="docker.mirrors.ustc.edu.cn/dpage/pgadmin4"
"dpage/pgadmin4"="docker.mirrors.ustc.edu.cn/dpage/pgadmin4"
"node"="docker.mirrors.ustc.edu.cn/library/node"
"mysql"="docker.mirrors.ustc.edu.cn/library/mysql"
"mariadb"="docker.mirrors.ustc.edu.cn/library/mariadb"
"phpmyadmin"="docker.mirrors.ustc.edu.cn/library/phpmyadmin"
"redis"="docker.mirrors.ustc.edu.cn/library/redis"
"elasticsearch"="docker.mirrors.ustc.edu.cn/library/elasticsearch"
"kibana"="docker.mirrors.ustc.edu.cn/library/kibana"
"mongo"="docker.mirrors.ustc.edu.cn/library/mongo"
"busybox"="docker.mirrors.ustc.edu.cn/library/busybox"
"debian"="docker.mirrors.ustc.edu.cn/library/debian"
"ubuntu"="docker.mirrors.ustc.edu.cn/library/ubuntu"
"archlinux"="docker.mirrors.ustc.edu.cn/library/archlinux"
"alpine"="docker.mirrors.ustc.edu.cn/library/alpine"
# 未完待续......
```

