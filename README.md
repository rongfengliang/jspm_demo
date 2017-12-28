# jspm_demo web app

> 简单的模块添加，以及构建 使用了jquery  以及一个 npm 模块 shortid ,jspm 可以帮助进行构建类似browserify

## 环境准备
``` shell
 yarn global add jspm  (package manager)
 yarn global add live-server(http server)
```
## 项目启动
* jspm 依赖安装
```
jspm install
```
* 构建
```
jspm bundle lib/main  --inject
```
## 项目查看
```
live-server
```
 

