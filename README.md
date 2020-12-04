# MuNiuLiuM
docker+robot framework+selenium 可扩展水平扩展的测试框架.

```shell script
docker pull qiangzhou/autotest_platform:v1.0
docker run -dit --name autotest_platform --net host qiangzhou/autotest_platform:v1.0 bash -c "cd /opt/AutotestPlatform/web/ && uwsgi -i uwsgi.ini"

# browser http://ip:8080
# login passwd: admin/123
```
