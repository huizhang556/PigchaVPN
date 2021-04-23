## [点我到官网](http://pigcha.com)


## 简介
PigchaVPN是一款用于多平台系统的科学上网，翻墙，上网加速，VPN工具，上网代理，浏览器代理，Git代理，控制台代理的客户端。如果本项目对您有用，请不要吝啬你的star~  
[youtube视频地址](https://youtu.be/fjTCqtGDW0w)
## 平台支持
- windows
- mac
- ubuntu
- ios 开发中
- android

## 注意事项
- 请关闭其它同类软件
- 关闭浏览器相关代理插件
- 请关闭杀毒相关软件，承诺本软件无任何病毒

## 使用介绍
### 第一步：注册登录
用户第一次仅需输入邮箱和密码，点击注册|登录按钮即可

![img](https://cdn.processon.com/601a15be1e08535a7bccf8a6)

### 第二步：选择节点加速
选择界面中的加速节点,并点击加速

![img](https://cdn.processon.com/5ffd43dbf346fb55c5ba3d7b)

### 第三步：去开浏览器试试~
下针对加速成功后，使用不了的，可以尝试如下解决方案
- 考虑chrome是否有什么谷歌上网助手等等，请卸载之
- 加速成功后理论上修改系统代理为127.0.0.1:61422，检查系统代理设置成功与否
- 尝试退出同类型的应用
- 尝试退出杀毒软件
- windows用户可尝试使用edge浏览器测试



## 高级代理说明（本功能为内地开发者之福音）
![img](https://cdn.processon.com/5ffd440d1e0853437c3e1ad1)
- **本地默认http/https代理地址**：**127.0.0.1:15732**，欢迎各位大佬连接
- **本地默认socks5代理地址，不支持UDP**：**127.0.0.1:15733**，欢迎各位大佬连接
- **全局代理**：在客户端的左下角，所有域名都走代理通道，**如若不勾选**，默认如百度等常用的网站走本地，上网体验更佳！！
- **git代理**：在托盘菜单勾选，加速git客户端的clone push pull等操作，前提是仓库地址要使用**https**的哦！！
- **控制台代理**：在托盘菜单点出，仅该控制台生效，比如你使用python的pip命令,golang的go get命令,前端的npm等等等，在该控制台的调用的命令，都会进行http/https代理加速！！需要特别说明的是，linux下，存在权限问题，如果你调的命令是sudo开头的，需要将控制台切换到sudo，请手动输入该2条命令  export http_proxy=http://127.0.0.1:15732  export https_proxy=http://127.0.0.1:15732
然后再调用你的命令即可代理，参考图片
![img](https://cdn.processon.com/6020cc58e401fd48f2938109)


