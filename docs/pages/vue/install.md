##  Vue 引入方式及脚手架构建
1、直接用 script 引入 
```js
// 开发版本 包含完整的警告和调试模式
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>

// 生产版本 删除了警告，33.30KB min+gzip
 <script src="https://cdn.jsdelivr.net/npm/vue@2.6.0"></script>
 ```
 2、脚手架搭建
 脚手架的基础都是需要nodejs, 地址：<http://nodejs.cn/>

 vue-cli2.x
 ```js
// vue-cli2.x
//  全局安装vue-cli
npm install --global vue-cli

// 创建一个基于webpack模板的新项目
vue init webpack 'vue-demo' // 基于webpack模板创建的一个叫vue-demo的项目
cd 'vue-demo' // 进入vue-demo文件夹
npm install // 安装依赖包
npm run dev // 启动项目
 ```
 vue-cli3.x
```js
 // vue-cli3.x
//  全局安装vue-cli3
npm install -g @vue/cli
# OR
yarn global add @vue/cli
// 创建项目
vue create hello-world
// 启动
vue server
 ```