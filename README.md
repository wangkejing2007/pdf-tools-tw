<div align="center">

# 雲卷雲舒 · PDF 全能匠心

### 化繁為簡凝雲墨，拆骨離魂鑄新篇

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://pdf-tools-tw.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/ChatGPT3a01/pdf-tools-tw?style=social)](https://github.com/ChatGPT3a01/pdf-tools-tw)

<img src="assets/splash.png" alt="PDF 工具箱" width="600">

**免費、開源、無廣告的線上 PDF 處理工具**

[立即使用](https://pdf-tools-tw.streamlit.app) · [回報問題](https://github.com/ChatGPT3a01/pdf-tools-tw/issues) · [功能建議](https://github.com/ChatGPT3a01/pdf-tools-tw/issues)

</div>

---

## ✨ 功能特色

<table>
<tr>
<td width="33%" align="center">

### 📦 PDF 壓縮

**智慧壓縮技術**

- 三種壓縮程度可選
- 高壓縮目標 **4MB 以下**
- 完美適合上傳作業
- 即時顯示壓縮比例

</td>
<td width="33%" align="center">

### ✂️ PDF 拆分

**靈活拆分選項**

- 每頁拆分成獨立檔案
- 自訂頁數範圍
- 支援格式：`1-3, 5, 7-10`
- 一鍵打包下載 ZIP

</td>
<td width="33%" align="center">

### 🔗 PDF 合併

**輕鬆合併文件**

- 多檔案同時上傳
- 依序合併成單一 PDF
- 拖放調整順序
- 快速匯出下載

</td>
</tr>
</table>

---

## 🎯 為什麼選擇我們？

| 特點 | 說明 |
|:---:|:---|
| 🔒 **隱私安全** | 檔案處理完成後立即刪除，絕不保存 |
| 🌐 **免安裝** | 純網頁操作，無需下載任何軟體 |
| 🆓 **完全免費** | 開源專案，無廣告、無付費牆 |
| 🇹🇼 **繁體中文** | 專為台灣使用者打造的介面 |
| 📱 **跨平台** | 電腦、平板、手機皆可使用 |
| ⚡ **快速處理** | 採用高效能壓縮演算法 |

---

## 🖥️ 畫面預覽

<div align="center">

| 壓縮功能 | 拆分功能 | 合併功能 |
|:---:|:---:|:---:|
| ![壓縮](https://via.placeholder.com/250x150/E3F2FD/1976D2?text=壓縮+PDF) | ![拆分](https://via.placeholder.com/250x150/E8F5E9/388E3C?text=拆分+PDF) | ![合併](https://via.placeholder.com/250x150/FFF3E0/F57C00?text=合併+PDF) |

</div>

---

## 🚀 快速開始

### 線上使用（推薦）

直接點擊下方按鈕，無需安裝：

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://pdf-tools-tw.streamlit.app)

### 本地安裝

```bash
# 1. 複製專案
git clone https://github.com/ChatGPT3a01/pdf-tools-tw.git
cd pdf-tools-tw

# 2. 安裝依賴
pip install -r requirements.txt

# 3. 啟動應用
streamlit run app.py
```

開啟瀏覽器訪問 `http://localhost:8501` 即可使用！

---

## 📋 壓縮程度說明

| 等級 | 圖片品質 | 適用情境 | 預期壓縮率 |
|:---:|:---:|:---|:---:|
| 🟢 低度 | 85% | 需要保持高品質的文件 | 10-30% |
| 🟡 中度 | 60% | 一般用途，平衡品質與大小 | 30-50% |
| 🔴 高度 | 30% | 上傳作業、Email 附件（目標 4MB 以下） | 50-80% |

> ⚠️ **注意**：實際壓縮效果取決於原始 PDF 的內容。純文字 PDF 壓縮空間有限，包含大量圖片的 PDF 壓縮效果較佳。

---

## 🛠️ 技術架構

```
pdf-tools-tw/
├── 📄 app.py              # 主程式（Streamlit 應用）
├── 📄 requirements.txt    # Python 依賴套件
├── 📄 README.md           # 專案說明
├── 📄 LICENSE             # MIT 授權條款
├── 📁 assets/             # 靜態資源
│   └── 🖼️ splash.png      # 啟動畫面圖片
└── 📁 .streamlit/         # Streamlit 設定
    └── ⚙️ config.toml     # 主題與伺服器設定
```

### 使用技術

- **[Streamlit](https://streamlit.io/)** - 網頁應用框架
- **[pikepdf](https://github.com/pikepdf/pikepdf)** - PDF 處理與壓縮
- **[pypdf](https://github.com/py-pdf/pypdf)** - PDF 讀寫操作
- **[Pillow](https://python-pillow.org/)** - 圖片壓縮處理

---

## 🤝 貢獻指南

歡迎各種形式的貢獻！

1. 🍴 Fork 這個專案
2. 🌿 建立功能分支 (`git checkout -b feature/AmazingFeature`)
3. 💾 提交變更 (`git commit -m 'Add some AmazingFeature'`)
4. 📤 推送分支 (`git push origin feature/AmazingFeature`)
5. 🔃 開啟 Pull Request

---

## 📜 授權條款

本專案採用 **MIT License** 授權 - 詳見 [LICENSE](LICENSE) 檔案

---

## 💖 支持專案

如果這個工具對你有幫助，歡迎：

- ⭐ 給專案一顆星星
- 🐛 回報問題或建議
- 📢 分享給需要的朋友

---

## 👨‍🏫 作者資訊

<div align="center">

<img src="assets/作者資訊.png" alt="作者資訊" width="600">

### 阿亮老師

<table>
<tr>
<td align="center" width="50%">

**🎓 現職**

新北市安溪國中 資訊科技教師

</td>
<td align="center" width="50%">

**🏆 獲獎紀錄**

112 年教育部數位學習績優教師<br>
113 年教育部數位學習績優教師

</td>
</tr>
</table>

[![YouTube](https://img.shields.io/badge/YouTube-阿亮老師-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Liang-yt02)
[![Facebook](https://img.shields.io/badge/Facebook-3A科技研究社-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/groups/2754139931432955)
[![Email](https://img.shields.io/badge/Email-3a01chatgpt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:3a01chatgpt@gmail.com)

</div>

---

## ⚖️ 授權聲明

<div align="center">

### © 2026 阿亮老師 版權所有

**本專案僅供「阿亮老師課程學員」學習使用**

</div>

| ⚠️ 禁止事項 |
|:---|
| 🚫 禁止修改本專案內容 |
| 🚫 禁止轉傳或散布 |
| 🚫 禁止商業使用 |
| 🚫 禁止未經授權之任何形式使用 |

> 如有任何授權需求，請聯繫作者。

---

<div align="center">

## ⭐ 喜歡這個專案嗎？

**給個 Star 支持一下吧！**

[![GitHub stars](https://img.shields.io/github/stars/ChatGPT3a01/pdf-tools-tw?style=for-the-badge)](https://github.com/ChatGPT3a01/pdf-tools-tw/stargazers)

---

**用心製作 with ❤️ in Taiwan**

[⬆ 回到頂端](#雲卷雲舒--pdf-全能匠心)

</div>
