# 个人博客

>  使用[Hexo](https://github.com/hexojs/hexo)搭建的个人博客。目前使用[Ayer](https://github.com/Shen-Yu/hexo-theme-ayer)模板。

## 目录

- [安装](#安装)
- [使用](#使用)
- [配置项](#配置项)
- [项目结构](#项目结构)
- [历史](#历史)
- [维护者](#维护者)
- [开发者](#开发者)
- [License](#license)

## 安装

```javascript
yarn install
yarn install hexo-deployer-git
```

## 使用

```javascript
git add .
git commit -m "..."
git push origin hexo
hexo g -d
```

## 配置项

- 发布：配置`_config.yml`文件中`deploy`的`repo`字段，目前博客所生成的静态资源发布在阿里云服务器所搭建的私有git仓库(git@114.215.148.109:/home/git/repos/blog.git)中。
- 评论管理：[leancloud](https://www.leancloud.cn)

## 项目结构

```javascript
├── public                  // hexo发布后文件
├── scaffolds               // 脚手架
├── source                  // 文件目录(主要)
│   ├── _posts              // 发布文章目录
│   ├── about               // 关于
│   ├── categories          // 分类
│   ├── photos              // 图片目录
│   ├── tags                // 标签
├── themes                  // 主题
│   ├── ayer                // ayer主题
├── _config.yml             // 博客配置文件
```

## 历史

- sometime：创建博客
- 20200423：修改仓库目录及分支

## 维护者

[@Leayh](https://github.com/xiaxiangyun)

## 开发者

[@Leayh](https://github.com/xiaxiangyun)

## License

MIT © 2020