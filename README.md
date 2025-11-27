# 项目概述 python581

本项目是一款基于Python语言的Web渗透测试工具，使用Django框架进行功能模块的搭建，并以MySQL作为数据存储。它主要包含Web漏洞扫描和端口漏洞扫描两个核心功能模块，同时支持用户注册与登录。

# 技术栈

## 后端

- 开发语言：Python 3.7.7
- 框架：Django
- 数据库：MySQL 5.7+
- 数据库工具：Navicat 11+

## 前端

- Node.js
- Vue.js
- HTML

# 功能模块

## 用户登录界面

用户输入网址后，首先到达登录页面，需输入用户权限完成认证。未注册用户可通过“去注册”按钮进行注册。

## 渗透测试工具首页

登录后，首页展示了高、中、低风险漏洞的数量，并以环形图展示。同时设有首页、Web漏洞扫描、端口扫描三个菜单。

### WEB漏洞测试

用户输入检测的URL地址，可自动进行全扫描、XSS扫描和SQL注入扫描。扫描结果以图表形式展示，不同颜色代表不同风险。

### 端口扫描测试

用户输入端口字符串，点击扫描，系统对端口进行漏洞扫描，并以图表形式展示扫描结果。

# 系统角色

- 普通用户：可注册、登录，并使用渗透测试工具。
- 管理员：负责系统维护和用户权限管理。

# 运行环境

- 后端：Python 3.7.7，Django，MySQL 5.7+
- 前端：Node.js，Vue.js，HTML

# 部署步骤

1. 环境准备：安装Python、Django、MySQL、Navicat、Node.js、Vue.js等。
2. 数据库配置：创建数据库及表结构。
3. 后端部署：根据配置文件启动Django服务。
4. 前端部署：编译Vue.js项目并运行。

# 目录结构

```
 project/
 ├── backend/               # 后端代码目录
 │   ├── app/               # Django应用目录
 │   ├── settings.py        # 配置文件
 │   └── ...
 ├── frontend/              # 前端代码目录
 │   ├── src/               # Vue.js源码目录
 │   ├── public/            # 公共文件目录
 │   └── ...
 └── ...
```

# 核心亮点

- 面向对象的开发方式，便于维护与扩展。
- 提供Web漏洞扫描与端口漏洞扫描，功能全面。
- 界面友好，漏洞展示清晰，易于操作。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/341422/32/7172/19191/68d4e45bF55bdee1b/1377939627bd73e5.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/325586/20/23973/11202/68d4e45bFe1f5982f/ed8acfcfffcf6822.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/294123/39/11498/20961/68d4e45cFd8aaaadd/c9387655c187ae68.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/240644/21/30364/23025/68d4e45cF31e173c2/722201211de3a6b6.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/350009/28/7132/40306/68d4e45cF66c322d4/3150e7398adafbb3.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/346350/22/7156/17665/68d4e45dFddc50285/2418f784274bf884.jpg)
