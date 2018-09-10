# blog-hexo
### 1.安装git
### 2.安装Node.js
[Node.js安装及环境配置之Windows篇](https://www.jianshu.com/p/03a76b2e7e00 )
### 3.安装hexo
- 创建文件夹  
```blog-hexo```
- 执行命令  
```npm install hexo -g```
- 检查环境  
```hexo -v```
- 初始化该文件夹  
```hexo init```
- 安装所需要的主键  
```npm install```  
- 快速部署插件  
```npm install hexo-deployer-git --save```  
- CNAME永久驻留  
```npm install hexo-generator-cname --save```  
```
在_config.yml中添加：
Plugins:
- hexo-generator-cname
```
- 本地搜索  
```npm install hexo-generator-search --save```
```
在_config.yml中添加：
search:
  path: search.xml
  field: post
```
