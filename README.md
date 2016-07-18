# vue-elema

> 这是一个vue项目，仿饿了么招聘页面

## 开始

``` bash
# clone project
git clone https://github.com/jiayisheji/vue-elema.git

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

## 介绍

1. 使用vue-cli构建项目
2. 使用eslint代码检测
3. 使用webpack打包
4. 使用es2015编写
5. 使用vue-router页面切换
6. 使用vue-resource数据加载
7. 使用vuex数据管理
8. 未使用任何css预处理器（本机编译有问题）


## 资料
1. vue中文网        http://cn.vuejs.org/
2. vue社区          http://www.vue-js.com/
3. vue-router文档   http://router.vuejs.org/zh-cn/index.html
4. vuex文档         http://vuex.vuejs.org/zh-cn/intro.html

## 迭代
### 1.0.1 项目搭建
> 开始不熟悉eslint遇到很多坑（吐槽一下，看到控制台报错，一脸懵逼）


#### 目前进度：

1. 增加一个欢迎页面
2. 首页已经完成
3. 正在做招聘列表页面

### 1.0.2 页面搭建
> 整好了eslint现在写代码顺手多了



#### 目前进度：

1. fix 路由bug 不能回退
2. 招聘列表页面已经完成（数据来自饿了么）
3. 招聘详情页面也底部分享未做
4. 公司介绍页面基本完成，细节未完善
5. 做了一个登陆页面，模拟一下登陆。考虑运用vue验证插件。
6. 路由基本配置完成

### 1.0.3 页面基本搭建完成
> 捣鼓路由钩子配置，弄了好久才明白，一开始把route写成router死活不起作用



#### 目前进度：

1. fix about页面banner图和文字可以随下面tab切换
2. 整合了数据（数据来自饿了么）
3. 新写了几个过滤器
4. 最近在看vuex文档，还没有整明白
