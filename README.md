# blog

#### 使用步骤

- 安装 hexo
```sh
# 全局安装 hexo
npm install -g hexo-cli
# 初始化项目
hexo init dwyo@github.io
```

- 安装插件

```sh
 npm install hexo-renderer-pug hexo-renderer-stylus --save
 # git 部署插件
 npm install hexo-deployer-git --save

- 创作新文章
```sh
hexo new 文章名称
# 生成静态文件
hexo generate
# 本地服务预览
hexo server
# 发布草稿
hexo publish
# 发布到 GitHub
hexo deploy
```
