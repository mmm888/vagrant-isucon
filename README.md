# vagrant-isucon

## REGULATION

* isucon4q
  * https://gist.github.com/mirakui/e394ed543415852d34a6
  * bench
   * cd /home/isucon/
   * ./benchmarker bench --host 192.168.39.154 --workload 2

* isucon5q
  * https://gist.github.com/tagomoris/1a2df5ab0999f5e64cff
  * bench
   * cd /home/isucon/
   + ./bench.sh (bench.sh 内の TARGET_IP を変更)

* isucon6q
  * https://github.com/isucon/isucon6-qualify/blob/master/Regulation.md
  * https://gist.github.com/fujiwara/cb69b456c4556ddbe24f65ec86419959
  * bench
   * cd /home/isucon/isucon6q/
   * ./isucon6q-bench -target http://192.168.39.156

* isucon6f
  * https://github.com/isucon/isucon6-final/blob/master/regulation.md
  * bench
   * docker build . -t bench
   * docker run bench

* pixiv isucon
  * https://github.com/catatsuy/private-isu/blob/master/public_manual.md
  * bench
   * /opt/go/bin/benchmarker -t http://192.168.39.176/ -u /opt/go/src/github.com/catatsuy/private-isu/benchmarker/userdata

## TODO

* isucon3q
  * vagrant up が failed する

* isucon4q (centos)
  * vagrant up が failed する

* isucon5f
  * vagrant up が failed する

* yisucon
  * public network の IP が設定されない

## License

MIT
