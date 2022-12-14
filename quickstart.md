## Node.js 安装配置

略

## docsify-cli工具安装

> 推荐全局安装 `docsify-cli` 工具，可以方便地创建及在本地预览生成的文档。

``` bash
npm i docsify-cli -g
```

## 项目初始化

> 直接通过 `init` 初始化项目，这里我在当前目录下的 docsify-demo 目录下进行项目初始化。

``` bash
docsify init ./docsify-demo
```

初始化成功后，可以看到 `./docsify-demo` 目录下创建的几个文件

- `index.html` 入口文件
- `README.md` 会做为主页内容渲染
- `.nojekyll` 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 `docsify-demo/README.md` 就能更新文档内容，当然也可以[添加更多页面](https://docsify.js.org/#/zh-cn/more-pages)。



## 本地预览

> 通过运行 `docsify serve ` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 [http://localhost:3000](http://localhost:3000/) 。

``` bash
docsify serve docsify-demo
```


