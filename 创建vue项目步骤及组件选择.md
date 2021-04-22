# 单页面中title设置
    npm install vue-wechat-title --save
    页面标签上添加： <div v-wechat-title="this.t || $route.meta.title">//页面有单独设置t使用t的内容为页面title，如没有t则使用路由设置中mate.title座位页面title
    data(){
        return{
            t:'页面title',//设置页面title
        }
    }

# 依赖包 #
+ 移动端页面兼容
    npm install postcss-pxtorem
+ css扩展语言 sass
    npm install sass-loader sass webpack --save-dev
+ 