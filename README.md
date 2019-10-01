# 短网址
### 功能
1.生成短网址
2.删除短网址
3.使用Ecache缓存

### 代解决的问题
1. 使用缓存，1s内缓存内容不变，导致访问数量也不变 

## 部署方式
1. 导入数据库 `shorturl.sql` 
2. `gradle bootRun`运行运行，后台登录`/login`，密码为admin


### 图

![](https://raw.githubusercontent.com/Ljqiii/url_JaiqiLiang_20190918/master/pic/addurl.png)
![](https://raw.githubusercontent.com/Ljqiii/url_JaiqiLiang_20190918/master/pic/adminpage.png)
![](https://raw.githubusercontent.com/Ljqiii/url_JaiqiLiang_20190918/master/pic/redirect.png)

