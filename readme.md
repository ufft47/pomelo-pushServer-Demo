#基于Pomelo 的推送演示demo#

##在线演示##
[http://goo.gl/R4kKL](http://goo.gl/R4kKL)

##说明文章##
[http://blog.gfdsa.net/2013/06/17/pomelo_study_appserver/](http://blog.gfdsa.net/2013/06/17/pomelo_study_appserver/)

##测试用账号##
用户名: demo

密码: demo

客户端连接使用 apiKey

<s>**注意!!! 忽然发现了一个异地多客户端登陆导致 账号用户列表的问题.....最终导致用户都为null....所以,暂时如果demo 账号不能用请自己注册一个...过会修复它**</s>

**界面就不要吐槽了..ps: 直接点击apikey 可以跳转到web client 看推送效果**

android 客户端在
`/androidApp/Pomelo-push-demo` 支持gradle 构建

`gradle build` 在`build/apk` 目录就可以直接使用apk 安装到手机

**需要注意**

如果,编译过程出现,编码错误,需要手动设置jdk的编码环境,在环境变量里面加上

name: `JAVA_TOOL_OPTIONS`

value: `-Dfile.encoding=UTF-8`


##服务端##
windows 环境你需要安装:

* vs 2010 express
* node x86(注意千万不能使用x64)
* python 2.x

运行步骤:

1. 运行npm-install,安装运行需要的module
2. 进入game-server 目录运行 `pomelo start`
3. 进入web-server 目录运行 `node app`

如果在安装 pomelo 过程中出现各种错误,请自行google.


##支持本项目##
如果你愿意支持一下本项目,没有什么比捐点线实在了...

[![](pay_encourage.png)](http://me.alipay.com/youxilua)