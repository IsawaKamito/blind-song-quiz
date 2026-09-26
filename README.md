[README.md](https://github.com/user-attachments/files/32688642/README.md)
# 盲播猜歌

純靜態 HTML 版本，可部署到 GitHub Pages 或 Cloudflare Pages。

## 使用

每行一首 YouTube：

`https://www.youtube.com/watch?v=xxxxx`

也可以：

`https://www.youtube.com/watch?v=xxxxx | 歌名 | 歌手`

## GitHub Pages

把 `index.html` 放在 repository 根目錄，啟用 GitHub Pages。此專案不需要 build command。

## Cloudflare Pages

連接 GitHub repository，Framework preset 選 None；Build command 留空；輸出目錄使用 repository 根目錄（若平台要求目錄，可使用 `.`）。
