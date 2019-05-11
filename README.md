# Docker演習 Nginx編

```bash
# コマンドラインでの実行
$ git clone https://github.com/MasanoriIwakura/docker-nginx.git
$ docker run --name nginx-study -d -p 80:80 \
-v ${PWD}/docker-nginx/html:/usr/share/nginx/html nginx
```