## npm
> this is a package

## 学习文档
- [w3cschool](https://www.w3cschool.cn/npmjs/npmjs-2rjm3knk.html)
- [npmjs](https://www.npmjs.cn/cli/dedupe/)
- [前端工程化（5）：你所需要的npm知识储备都在这了](https://juejin.cn/post/6844903870578032647)

## agenda

### 关于npm你需要知道的基础知识（标题-待定）
### npm i 和 npm publish 你需要知道什么（标题-待定）

#### 开始之前
- 安装npm
  - 方式一：通过安装nodejs LTS，自动安装上npm
  - 方式二：通过nvm

#### npm i <packageName>
- 全局安装 -g 或 --global
- 依赖包安装错综复在，了解npm i是如何安装包及处理包之间的依赖关系，有助于我们在安装遇到问题时更好的定位问题
  - npm2.x 嵌套安装
  - npm3.x 扁平安装
  - npm5.x 生成package-lock.json
    - package-lock.json 描述了node_modules下所有包的依赖树状结构

#### npm publish
- 创建需要发布的包的文件夹
  - npm init 为npm包的进行初始化
    - package.name 
      - 必须全小写
      - 可以使用连字符、下划线
      - 不可以出现空格
  - npm init --yes 或 npm init -y 使用默认信息作为package.json的内容
  - npm login
  - npm publish

#### 一些你可能会用到的npm命令
- npm init 初始化一个npm包
- npm run 
- npm run env
- npm list 或 npm ls
- npm ll <packageName>


#### demo info
  - [tracyA](https://www.npmjs.com/package/tracya)
    - 1.0.0
    - 2.0.0
  - [tracyB](https://www.npmjs.com/package/tracyb)
    - 1.0.0
    - 1.1.0
  - [tracyC](https://www.npmjs.com/package/tracyc)
    - 1.0.0
    - 1.0.1
  - project

