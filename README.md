# hexo

## 博客地址

- [github](https://fruitsdrink.github.io)
- [vercel](https://fruitsdrink-blog.vercel.app)

编译静态文件

```bash
hexo g
```

本地预览

```bash
hexo s
```

## 发布到 github

修改`_config.yml`

```yaml
deploy:
  type:git
  repo: https://github.com/fruitsdrink/fruitsdrink.github.io.git,main
```

```bash
npm i hexo-deployer-git
```

```bash
hexo clean && hexo g && hexo de
```
