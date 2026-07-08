# You Lu 學術主頁

這個目錄是 You Lu 的學術主頁源碼，基於 Minimal Light Jekyll 主題整理。

## 主要文件

- `_config.yml`: 站點元信息、個人連結、頭像和主題配置。
- `index.md`: 首頁簡介、研究方向、論文和獲獎信息入口。
- `_data/publications.yml`: 首頁渲染用的 10 篇論文資料。
- `_includes/publications.md`: 論文列表渲染模板。
- `_includes/awards.md`: 獲獎信息。
- `assets/img/ly.jpg`: 從 `Leason-ly.github.io/images/ly.jpg` 複製來的頭像。

## 本地預覽

安裝 Ruby 依賴後運行：

```bash
bundle install
bundle exec jekyll serve
```

然後打開 `http://localhost:4000`。
