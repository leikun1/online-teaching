## online-teaching
### 基于Vue开发的在线学习前台页面
### 感谢 [yucccc](https://github.com/yucccc) 的开源 [vue-mall](https://github.com/yucccc/vue-mall) 项目提供前端页面及框架支持

    
### 所用技术

- Vue 2.x
- Vuex
- Vue Router
- [Element UI](http://element.eleme.io/#/zh-CN)
- ES6
- webpack
- axios
- Node.js
- 第三方SDK
    - ~~[极验Test-button人机验证码](http://www.geetest.com/Test-button.html)~~ 因其收费详见[极验验证码移除文档](https://github.com/Exrick/xmall/wiki/%E6%9E%81%E9%AA%8C%E7%A7%BB%E9%99%A4%E6%96%87%E6%A1%A3)
- 第三方插件
    - [hotjar](https://github.com/Exrick/xmall/blob/master/study/hotjar.md)：一体化分析和反馈
    - ~~[搜狐畅言评论插件](http://changyan.kuaizhan.com/)~~ 垃圾广告评论插件 现已更换 [Gitment](https://github.com/imsun/gitment)

### 本地开发运行
- 在项目根文件夹下先后执行命令 `npm install` 、 `npm run dev`
- 默认端口9999 http://localhost:9999
## 部署
- 先后执行命令 `npm install` 、 `npm run build` 将打包生成的 `dist` 静态文件放置服务器中，若使用Nginx等涉及跨域请配置路由代理
