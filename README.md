# 大五人格高端養老評估 PWA

Big Five Personality Senior Living Assessment - Progressive Web App

## 📱 功能特色

- **大五人格 BFI-10 問卷**：國際標準10題量表
- **個人資料錄入**：姓名、性別、生日、婚姻狀況
- **自動評分**：五個維度（開放性、盡責性、外向性、宜人性、情緒穩定性）
- **養老需求分析**：基於人格特征匹配養老核心需求
- **消費行為畫像**：高端養老消費偏好與行為特征
- **會員適配評級**：A/B/C/D 四級客群分類
- **PWA 支持**：可安裝到 iPhone/Android 主螢幕，離線可用

## 🚀 GitHub Pages 部署步驟

1. 上傳以下文件到 `https://github.com/jp169zx-GH/big5`：
   - `index.html`（主應用）
   - `manifest.json`（PWA 清單）
   - `sw.js`（Service Worker）
   - `icon-192.png`（應用圖標）
   - `icon-512.png`（應用圖標）

2. 在 GitHub repository Settings → Pages 中：
   - Source: Deploy from a branch
   - Branch: main / (root)
   - 保存後等待 1-2 分鐘

3. 訪問：`https://jp169zx-gh.github.io/big5/`

## 📲 iPhone 安裝步驟

1. 在 iPhone 的 Safari 瀏覽器打開應用網址
2. 點擊底部分享按鈕（方形箭頭圖標）
3. 選擇「加入主螢幕（Add to Home Screen）」
4. 點擊「加入」即完成安裝

## 🎯 評估內容

基於文件資料，問卷結果涵蓋：

| 維度 | 高分特征 | 低分特征 |
|------|---------|---------|
| 開放性 | 體驗付費型 | 傳統穩健型 |
| 盡責性 | 健康規劃型 | 隨性休閒型 |
| 外向性 | 社交活動型 | 隱私內向型 |
| 宜人性 | 家庭情感型 | 理性自主型 |
| 情緒穩定性 | 安全保障型 | 佛系樂觀型 |

## 人格類型

- 🥇 A級：尊崇自信成就型、盡責穩健型
- 🥈 B級：社交活力型、理性自主型、開放探索型  
- 🥉 C級：溫和宜人型、情緒敏感型
- ⚠️ D級：務實節儉型

## 技術架構

- 純 HTML/CSS/JavaScript（無框架依賴）
- PWA Service Worker 離線緩存
- Web Share API 分享功能
- Google Fonts（Noto Serif SC、Ma Shan Zheng）
