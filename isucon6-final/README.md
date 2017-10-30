# 初期設定

## image01

* isucon6f.tar.gz コピーして、解凍
  * 以下を配置
   * /home/isucon/webapp
   * /etc/systemd/system/isu.service

~~~
# user, group を root に変更 (or docker group に isucon 追加)
vi /etc/systemd/system/isu.service
systemctl start isu.service
systemctl enable isu.service
systemctl status isu.service
~~~

## bench

* bench.tar.gz コピーして、解凍
  * /home/isucon 以下に配置

* bench やり方

~~~
cd /home/isucon/bench
# target ip を変更
vi Dockerfile
docker build . -t bench
docker run bench
~~~
