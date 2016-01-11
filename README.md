# Meteor训练营

## 第0周周六
* 安装 meteor/robomongo/chrome/Sublime/Atom
* 运行 examples，create hello
* 学会通过 chrome/console.log 调试并查看前后台调试信息
* 了解 .meteor 目录下的文件及数据库
* 掌握基本的部署命令 meteor deploy，完成部署自己的第一个应用

## 第1周周一
* mongodb 基本命令 insert/remove/update/find
* autopublish/insecure 订阅pub/sub机制/权限管理
* Meteor.call/method 后台方法实现
* seed 种子数据

## 第1周周二
* Accounts 账户管理
* loginButtons 登陆注册
* Meteor.users 数据库 schema

## 第1周周三 
* Router 路由

## 第1周周四
* Packages 包管理和使用
* autoform 自动化表单构建
* hooker 钩子函数

## 第1周周五

## 第1周周六


## 第2周周一


## 第2周周二


## 第2周周三 


## 第2周周四


## 第2周周五


## 第2周周日


# Learn Meteor Step by Step 
* 毛豆网《Meteor企业委培生》内部培训教材大纲

## 1 预备知识
* Install Tools
  - Meteor
  - Chrome
  - Robomongo
  - Sublime Text/WebStorm
  - Git and Github
* Commands
  - meteor create/run/add/mongo/deploy/log
  - git init/add/commit/push/pull/log
* Basics
  - HTML5
  - CSS/LESS
  - JavaScript/CoffeeScript

```
* 项目代码分析： hello
```

## 2 Meteor基础
* Meteor 7 Principles
  - Data on the Wire
  - Latency Compensation
  - Full Stack Reactivity
* Basic Concept
  - Template/Event/Helper
  - Session/Reactive
  - Blaze/Handlebar
* Meteor Deploy
  - meteor deploy/settings
  - meteor up/mup/mup.json
  - how to deploy to aliyun/amazon EC2
* Meteor app structure
  - client/server/lib/public/packages/tests
  - publications/subscriptions/methods/collections/routes/seeds

```
* 项目代码分析： todos
```

## 3 Mongo基础
* NoSQL vs SQL
* Collections
  - Schema
* Database Operations
  - Insert/Remove/Update/Find
* Shell Methods
  - find()/findOne()/insert()/remove()/update()
* Robomongo
  - Documents/Edit/View/Insert/Delete/Copy

```
* 项目代码分析： leaderboard
```

## 4 Meteor进阶
* Publish and Subscription
  - Minimongo
  - DDP
  - cursor/record set
  - Multiple Subscriptions 
  - Publish with userFields
* Allow and Deny
  - insert/update/remove

```
* 项目代码分析： localmarket
```

## 5 常用package
* Iron router
  - Router.map()
  - this.render()
* ionic framework/UI 
  - meteoric:ionic
  - meteoric:autoform-ionic
* simple-schema
  - aldeed:autoform
* underscore
  - each/map/reduce/find/filter/where
* some other packages 
  - reywood:publish-composite
  - anti:fake
  - momentjs:moment
  - bengott:avatar

```
* 项目代码分析： welog
```

## 6 User用户登录
* Packages inside
  - accounts-password
  - accounts-ui
* Other Login Packages
  - weibo/qq
  - linkedin/github
* Meteor.users
  - onCreateUser()
  - ServiceConfiguration

```
* 项目代码分析： meteor-bbs
```

## 7 项目1 基于Meteor的微信app应用开发
* 典型项目案例分析-活动行
  - 微信公众号
  - 微信SDK
  - 微信用户信息获取
  - 表单设计

## 8 项目2 基于Meteor的社交电商应用开发
* 典型项目案例分析-购物商城
  - Code Analysis 代码分析
  - Data Design 数据设计
  - Work Flow 运转流程
  - Template Appliance 模版应用

## 9 项目3 基于Meteor的iOS/Android app应用开发
* 典型项目案例分析-松果生活
  - iOS App 打包
  - Android App 打包

