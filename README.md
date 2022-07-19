# V2Board-theme-LuFly(首页)

## 部署方法

进入v2Board的运行目录：

```shell
cd /usr/share/nginx/html/v2board/public/
```
> 宝塔：cd /www/wwwroot/网站目录/public/

下拉首页文件：

```shell
git clone https://github.com/1kst/v2board-theme-LuFly.git
mv v2board-theme-LuFly/* .
```

修改Nginx运行的index优先级：

```shell
index index.html index.htm index.php;
```

> 若是宝塔搭建的，自行修改配置文件，将index.html放在第一，其他往后移。宝塔修改可参考：https://jingyan.baidu.com/article/7e440953f70e516ec0e2efc0.html

