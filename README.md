# 台灣機器人社群網站

這是一個 Hugo 靜態網站，推送到 `main` 後由 GitHub Pages 自動部署。

## 更新下一場與活動紀錄

所有活動資料集中在 `data/events.yaml`：

- `upcoming`：首頁與活動頁的下一場資訊。
- `events`：由新到舊排列的歷史活動時間軸。

網站只保存活動名稱、日期、地點、簡介與外部連結。相簿、影片、簡報與報名資料請留在 Luma、ACCUPASS、YouTube、Google Drive 或原本的平台。

本機預覽：

```sh
hugo server
```

正式檢查：

```sh
hugo --gc --minify
```

## 字型

標題使用自架的「霞鶩文楷 TC」，來源為 [lxgw/LxgwWenkaiTC](https://github.com/lxgw/LxgwWenkaiTC)，採 SIL Open Font License 1.1。網站使用的 WOFF2 檔已依目前文案縮減字集；新增未使用過的中文字時，需重新產生字型子集。
