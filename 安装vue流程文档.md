# 首先全局安装node
    https://nodejs.org/en/ 下载对应系统版本 （建议安装稳定版，无需安装最新版）

# 安装完之后命令提示符工具运行
    node -v 查看是否安装成功
    npm -v 查看npm是否成功
# 以上node npm工具安装成功后 开始全局安装vue
    命令提示符工具 运行 npm install vue

# 安装vue-cli 3.0脚手架
    npm install -g @vue/cli

# vue创建项目
    vue create project-name

*** 所有项目建议使用英文目录 ***

+ # 如果是已有项目
    - 以上安装好之后，进入项目文件夹开始安装依赖
        - npm istall 或者 npm i 
    + 依赖安装好之后可以运行项目
        - npm run serve
+ # 新项目clone方案
    + npm clone 项目地址
    + 项目clone完成后，按照已有项目步骤进行即可
    
``` bash
# 项目主体结构
├── index.html                      入口页面
    ├── package.json                    npm包配置文件，里面定义了项目的npm脚本，依赖包等信息
    ├── vue.config.js                   配置本地开发接口地址
    ├── mock                            mock数据目录
    │   └── hello.js
    ├── src                             项目源码目录    
    │   ├── main.js                         入口js文件
    │   ├── app.vue                         根组件
    │   ├── common                      公共方法
    │   │   └── api.js                      页面api配置
    │   ├── components                  公共组件目录
    │   │   └── botNav.vue                  底部导航
    │   │   └── header.vue                  头部
    │   │   └── search.vue                  检索
    │   │   └── RelateLaw                   相关法规组件
    │   │       └── index.vue               
    │   ├── assets                          资源目录，这里的资源会被wabpack构建
    │   │   └── images
    │   │       └── logo.png
    │   ├── routes                          前端路由
    │   │   └── index.js
    │   ├── store                           应用级数据（state）
    │   │   └── index.js
    │   └── sass                            页面样式sass
    │   └── views                           页面目录
    │       ├── index.vue                   首页
    │       └── login.vue                   登录
    │       └── register.vue                注册
    └── test                            测试文件目录（unit&e2e）
        └── unit                            单元测试
            ├── index.js                        入口脚本
            ├── karma.conf.js                   karma配置文件
            └── specs                           单测case目录
                └── Hello.spec.js
```


