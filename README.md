# Template-GitBook 

空的模版项目

```
sed -i '' 's/Template-GitBook/_NewProject_/g' `grep Template-GitBook --include=\*.{md,html,xml} -rl .`

git config user.email ykb553@163.com
git config -l | grep user
```



> gitbook install ./GitBook  
>
> gitbook build ./GitBook ./docs  
>
> gitbook serve ./GitBook ./docs  



# 帮助文档

> npm：https://www.npmjs.com/package/gitbook
>
> 教程：http://gitbook.zhangjikai.com/bookjson.html



## 快速开始

```bash
# 安装
$ sudo npm install gitbook-cli -g

# 初始化一个项目
$ gitbook init

# 默认是生成到 _book 文件夹，这里生成到 docs 文件夹）
$ gitbook build . docs

# 本地发布
$ gitbook serve . docs

# 帮助
$ gitbook help

```



## 插件

> 在 npm 仓库搜索：https://www.npmjs.com/search?q=gitbook-plugin
>
> 插件推荐：http://gitbook.zhangjikai.com/plugins.html



```bash
# 配置插件后，通过以下命令安装
$ gitbook install
```



