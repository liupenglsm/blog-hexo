# blog-hexo
### 1.安装git
### 2.安装Node.js
[Node.js安装及环境配置之Windows篇](https://www.jianshu.com/p/03a76b2e7e00 )
### 3.安装hexo
- 拉取项目  
```git clone https://github.com/liupenglsm/blog-hexo.git```
- 执行命令  
```npm install hexo -save```
- 检查环境  
```hexo -v```
- 安装所需要的主键  
```npm install```  
- 快速部署插件  
```npm install hexo-deployer-git --save```  
- CNAME永久驻留  
```npm install hexo-generator-cname --save```  
```
在_config.yml中添加（可选）：
Plugins:
- hexo-generator-cname
```
- 本地搜索  
```npm install hexo-generator-search --save```
```
在_config.yml中添加（可选）：
search:
  path: search.xml
  field: post
```
- hexo博客安装RSS插件
```npm install hexo-generator-feed```
```
# Extensions
## Plugins: http://hexo.io/plugins/
#RSS订阅
plugin:
- hexo-generator-feed
#Feed Atom
feed:
type: atom
path: atom.xml
limit: 20
```
### 配置SSH
- 我的百度云下载ssh压缩文件
- 覆盖C:\Users\Administrator\.ssh文件
