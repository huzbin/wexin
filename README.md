<h2 align="center">

<h4 align="center">
    企业微信群机器人管理工具
</h4>
<p align="center">
    非常方便的发布群即时消息和定时消息，解放双手，提升沟通效率
</p>

## 部署教程
这个是在nginx上部署此工程的使用参考教程：[从0到1，Nginx部署Nodejs+React教程](https://www.jianshu.com/p/5af19b772948)

## 更新日志


## 快速启动

```shell
# 本地开发环境
# 启动前端
cd insight-front-end 
npm install
npm start   

# 启动后端
cd insight-back-end
npm install
npm run dev     

```

访问http://localhost:3000 即可启动。

前后端使用的是React+Nodejs，数据库默认为Mysql测试库，您可以进入`insight-back-end/config`文件夹下，修改为自己的Mysql配置。

## QBot Manager是什么？

QBot Manager是一个**可以管理企业微信群机器人的小工具，在这里添加一个机器人webhook地址，然后发布即时消息和定时消息，消息就会发送到企业微信中机器人所在的群里**。


## 产品特色

1. 一键发布消息，支持@所有人、指定人，方便快捷。
2. 强大的定时功能，可以每天执行并且智能跳过节假日，彻底解放双手。
3. 简约的排版，科幻的风格，3分钟内轻松上手。
4. 贴心的自定义套件，拓展代码实现自定义文本内容。
5. 完备的权限控制，保证机器人运行安全无忧。
6. 支持移动端布局，支持集成到企业微信控制台。
7. 消息支持自定义Cron表达式。

## 技术栈

我们使用的技术尽量是通用简单，即使是一个前端工程师也可以很快掌握前后端代码，下面是前后端项目用到的技术栈，和使用到的组件库。

| 业务   | 技术   |  教程 |
| ------ | -------- | ------ |
| 前端 | React+ Create React App + Mobx + Ant Design | 
| 后端 | Nodejs+ Egg + Typeorm + Typescript + Mysql | +Typescript模版，数据库操作使用的是ORM
