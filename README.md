# 仙台・河口湖旅遊小工具

這是一個手機優先的靜態 PWA 旅遊 App，已內建：
- 每日行程
- 預訂資料
- 地圖導航按鈕
- 離線記帳
- 緊急聯絡頁

## 本機預覽

最簡單方式：

```bash
python3 -m http.server 8000
```

然後打開：
`http://localhost:8000`

## 部署

- GitHub Pages
- Netlify
- Vercel
- Kinsta 靜態網站

## 目前限制

- 天氣是示意資料，未串即時 API
- 記帳是 localStorage 離線版，未接 Firebase
