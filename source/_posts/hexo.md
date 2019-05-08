---
title: hexo
date: 2019-05-08 23:10:49
tags: hexo
---

## 安装Hexo命令到系统
```
$ npm install hexo-cli -g
```

## 初始化
```
$ hexo init
```

## 安装modules
```
$ npm install
```

## 创建文章
```
hexo new name
```

## 创建页面名
```
hexo new page name
```

## 生成页面
```
$ hexo g # hexo generate
```

## 启动本地服务
```
$ hexo s # hexo server
```

## 浏览器查看
```
$ open http://localhost:4000
```

## 修改主题
```
$ git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia
```
获取到主题后，修改_config.yml文件中theme的属性设置为yilia即可
运行命令重新生成页面
```
$ hexo g
```

# deploy
## 安装hexo部署到github辅助工具
```
npm install hexo-deployer-git --save
```

## 修改根目录下的_config.yml文件
```
deploy:
  type: git
  repo: https://github.com/qioixiy/qioixiy.github.io.git
  branch: master
```
