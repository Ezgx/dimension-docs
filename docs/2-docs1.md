# 安装主题

## 方法一

从`github`克隆

```bash
git clone https://github.com/Ezgx/hexo-theme-dimension /theme/dimension
```

## 方法二

`npm包`安装

```bash
npm i hexo-theme-dimension --save

# 或

cnpm i hexo-theme-dimension --save
```

## 必要插件

```bash
npm un hexo-renderer-marked
```

```bash
npm i hexo-wordcount hexo-renderer-pug hexo-renderer-stylus hexo-renderer-kramed hexo-generator-search --save
```

## 文件操作

1. 将下载的主题中的`_config.dimension.yml`放到博客根目录下
2. 解压`source.7z`，所有内容放到`$blogroot/source`下，提示替换时请备份你的文件。

## 启用主题

在`$blogroot/_config.yml`中，把`theme`项改为：
```yml
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: dimension
```