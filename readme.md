# 双语项目前端环境使用

## 项目初始化命令

在项目根目录下执行 `npm i`

如果遇到 `node-sass` 模块安装失败的情况，请使用淘宝源国内镜像安装，命令如下： 

``` js
npm install -g cnpm --registry=https://registry.npm.taobao.org

// 接下来再执行

npm i

```
### 文件
#### 1.assets       主要存放静态文件  比如icon 和图片
#### 1.axios        数据交互基础库，请求的函数库，
#### 1.components   各个组件的源码存放地方
#### 1.config       配置项存放处
#### 1.pages        页面源码存放
#### 1.reducer      主要存放redux 通用函数
#### 1.routes       主要存放router 相关函数
#### 1.styles       通用样式 相关换肤
#### 1.utils        主要存放通用函数

