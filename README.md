# bbws_terminal

## 介绍

本程序使用Express框架开发，使用的数据库为mongo DB，用于保贝卫士机具接入。

## 使用

输入以下命令可直接运行程序

`npm start`

若需要在后台挂起运行可将package.js的

`"scripts": { "start": "pm2 startOrGracefulReload ./pm2.json --no-daemon"}`

修改为

`"scripts": { "start": "pm2 ./pm2.json"}`
# bbws_terminal
