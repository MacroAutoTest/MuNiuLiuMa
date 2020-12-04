# MuNiuLiuM
docker+robot framework+selenium+selenium hub 高性能,水平扩展自动化测试平台。

```shell script
docker pull qiangzhou/autotest_platform:v1.0
docker run -dit --name autotest_platform --net host qiangzhou/autotest_platform:v1.0 bash -c "cd /opt/AutotestPlatform/web/ && uwsgi -i uwsgi.ini"

# browser http://ip:8080
# login passwd: admin/123
```
