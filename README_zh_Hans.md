# You Lu 学术主页

这个目录是 You Lu 的学术主页源码，基于 Minimal Light Jekyll 主题整理。

## 主要文件

- `_config.yml`: 站点元信息、个人链接、头像和主题配置。
- `index.md`: 首页简介、研究方向、论文和获奖信息入口。
- `_data/publications.yml`: 首页渲染用的 10 篇论文数据。
- `_includes/publications.md`: 论文列表渲染模板。
- `_includes/awards.md`: 获奖信息。
- `assets/img/ly.jpg`: 从 `Leason-ly.github.io/images/ly.jpg` 复制来的头像。

## 本地预览

安装 Ruby 依赖后运行：

```bash
bundle install
bundle exec jekyll serve
```

然后打开 `http://localhost:4000`。
