# ASP.NET MVC QQ Connect

#### 介绍
ASP.NET MVC QQ互联接入Demo。

#### 项目说明
因为个人博客要接入QQ互联，也是第一次玩，不熟悉，所以就先写了这个Demo。
支持登录返回登录前的Url。
后台回调方法获取数据，可以写入数据库自己发挥。
只用了一个第三方的库：Newtonsoft.Json

#### 使用说明

1. 修改QQLoginHelper 里的appId appKey redirect_uri 为你自己的。
![输入图片说明](https://images.gitee.com/uploads/images/2019/0725/122551_5d90d5a6_1130037.jpeg "_1.jpg")
2. 发布到本地文件夹
3. IIS发布这个项目 内网ip加80端口
4. 添加一条本地域名映射记录 C:\Windows\System32\drivers\etc\hosts 你的内网ip 你的域名
5. 浏览器用域名打开IIS发布的网站，查看cookie
![输入图片说明](https://images.gitee.com/uploads/images/2019/0725/123034_921b8e66_1130037.jpeg "cookie.jpg")


#### 项目截图
![输入图片说明](https://images.gitee.com/uploads/images/2019/0725/123504_3acd2bdf_1130037.jpeg "e.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0725/123524_c8097b27_1130037.jpeg "e1.jpg")