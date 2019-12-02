chown -R 1100:1100 /srv/docker/graylog

* 修改讓 elasticsearch 的 folder 有權限寫入
chown -R 1000:1000 /srv/docker/graylog/elasticsearch



Reference:
https://github.com/Graylog2/graylog2-server/issues/2155
https://www.zhihu.com/question/280307001


