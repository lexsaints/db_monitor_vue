## 项目介绍

> 基于 iview-admin 2.5.0

安装nodejs 
下载node安装包 wget https://nodejs.org/dist/v10.16.0/node-v10.16.0-linux-x64.tar.xz
下载解压，将node的bin加入到环境变量即可

使用npm安装yarn
npm install -g yarn

配置yarn淘宝镜像源
yarn config set registry https://registry.npm.taobao.org

## 运行

```bush
1. 下载项目源码
git clone https://github.com/gumengkai/db_monitor_vue

2. 修改后端API连接地址
src/config/index.js
baseUrl:
    dev: 测试
    pro: 线上
示例API地址：47.100.119.84:43278

3. 安装依赖包
yarn install

4. 开发环境运行
yarn run dev
```

## DEMO

> http://122.51.204.250:8080/

> 账户 admin 密码 111111


![demo1](src/demo/demo1.jpg)
![demo2](src/demo/demo2.jpg)

## 编译

> dist

```bush
yarn build
```

将dist文件夹部署到nginx即可
