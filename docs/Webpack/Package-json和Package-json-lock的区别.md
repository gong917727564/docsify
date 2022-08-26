# Package-json和Package-json-lock的区别

>模块化开发在前端越来越流行，使用 node 和 npm 可以很方便的下载管理项目所需的依赖模块。package.json 用来描述项目及项目所依赖的模块信息。


那 package-lock.json 和 package.json 有啥关系和联系呢？

### 1 package.json

`package.json 用来描述项目及项目所依赖的模块信息。`,就是帮我们管理项目中的依赖包的，让我们远离了依赖地狱。
通过 npm 管理，使用一些简单的命令，自动生成package.json, 安装包依赖关系都由package.json来管理，我们几乎不必考虑它们。
