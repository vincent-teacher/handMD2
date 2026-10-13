# 高中地理第四章：地形系統 (Geomorphological Systems)

[![HackMD Book Mode](https://img.shields.io/badge/HackMD-Book%20Mode-blue?logo=markdown&logoColor=white)](book.md)
[![Curriculum](https://img.shields.io/badge/教育部-108課綱普通高中-green)](https://www.k12ea.gov.tw/)
[![Interactive Site](https://img.shields.io/badge/GitHub%20Pages-Interactive%20Site-emerald?logo=github)](index.html)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

> 依據教育部 108 課綱高級中等學校地理科教學規範編撰。完整解構內外營力、流水喀斯特冰河風浪地貌、人地互動反饋機制，並結合 1904 臺灣堡圖進行鄉土拓墾地名探究。

---

## 📖 專案特色與亮點

- **🧩 完美適配 HackMD 書本模式 (Book Mode)**：內建 `book.md` 索引導航，全面採用標準 Markdown 語法及 HackMD 特色擴充（包含提示區塊 `:::info`、`:::warning`、點擊展開解析 `:::spoiler`）。
- **📊 動態 Mermaid.js 地貌架構圖**：包含地函熱對流、褶曲斷層構造、冰河拔蝕磨蝕、喀斯特溶蝕序列、曲流牛軛湖、突堤效應等 20+ 幅精美視覺化流程圖。
- **🔬 完整收錄 3 大課本深度探究案例**：
  - **探究 4-1**：新北萬里野柳女王頭脖圍演變與蕈狀岩地質思辨（人為固化 vs 自然演育）。
  - **探究 4-2**：屏東平原潮州斷層階地、1938年隘寮溪長堤改道與東港溪口海岸線後退之系統反饋。
  - **探究 4-3**：桃園西北海岸侵蝕加劇、國軍海防碉堡淪為「海中孤島」之影像實證。
- **🗺️ 跨時空地理實作（活動 GO）**：詳解 1904 年日治《臺灣堡圖》圖例，深度剖析「澳底、四鯤鯓、三層、灣仔、沙崙」五大地名密碼與 Web GIS 探究工具。
- **🌐 現代化響應式 GitHub 互動首頁 (`index.html`)**：具備深淺模式切換、章節即時全文過濾、學習進度追蹤 (LocalStorage)、Markdown 動態閱覽與概念快篩測驗。

---

## 🗂️ 檔案結構與教材導航

```text
├── book.md                 # 📚 HackMD 書本模式主目錄 (Master Table of Contents)
├── full_book.md            # 📜 單篇完整彙整版教材 (方便一鍵整本複製或列印匯出 PDF)
├── index.html              # 🌐 GitHub Pages 互動首頁與即時閱讀器
├── README.md               # 📌 專案說明與部署指南
└── docs/                   # 📁 各模組分章內容
    ├── 00-introduction.md          # 00. 章首導讀：台江滄海至七股桑田與人地互動
    ├── 01-geomorphic-systems.md    # 01. 地形系統的概念、運作架構與空間尺度
    ├── 02-endogenic-processes.md   # 02. 內營力：褶曲、斷層、火山與危害資源
    ├── 03-exogenic-processes.md    # 03. 外營力：風化、四大崩壞、差異侵蝕、八卦台地
    ├── 04-case-study-yehliu.md     # 04. 探究 4-1：野柳女王頭的歲月痕跡與蕈狀岩
    ├── 05-fluvial-landforms.md     # 05. 河流地形：上中下游侵蝕堆積、曲流牛軛湖、大溪河階
    ├── 06-karst-landforms.md       # 06. 岩溶作用：喀斯特地表演育、洞穴滴石、泰國睡美人洞
    ├── 07-glacial-landforms.md     # 07. 冰河作用：磨蝕拔蝕、角峰U型谷峽灣、歐洲黃土帶譜
    ├── 08-case-study-pingtung.md   # 08. 探究 4-2：屏東平原隘寮溪長堤與出海口後退
    ├── 09-aeolian-landforms.md     # 09. 風力作用：風蝕礫漠岩漠、三大沙丘類型、黃土高原
    ├── 10-coastal-landforms.md     # 10. 海水作用：海岸分區、海蝕海積地貌、離水海階與沉水
    ├── 11-case-study-taoyuan.md    # 11. 探究 4-3：桃園海岸線後退與海防碉堡變遷
    ├── 12-human-environment.md     # 12. 人地關係：聖山文化、突堤效應、知本溪倒塌與永續
    ├── 13-activity-taiwan-toponyms.md # 13. 活動GO：1904臺灣堡圖與地名中的地形密碼
    └── 14-appendix-glossary-quiz.md   # 14. 附錄：名詞精要表、全章思維導圖、實戰評量
```

---

## 🚀 如何在 HackMD 中開啟「書本模式 (Book Mode)」？

本教材專為 HackMD 書本模式量身打造，共有兩種便捷的使用方式：

### 方式一：多筆記書本模式（正規標準）
1. 登入 [HackMD](https://hackmd.io/)，建立一篇新筆記。
2. 開啟本專案的 [`book.md`](book.md)，將內容複製貼上至該筆記中。
3. 將標題設定為 `# 第四章 地形系統 (Landform Systems)`。
4. 在該筆記右上角點擊選單，將檢視模式切換為 **「書本模式 (Book Mode)」**。
5. 點擊分享或發布連結，即可獲得如書籍般帶有左側目錄樹、右側章節閱讀的完整數位書本！

### 方式二：單篇全書模式（適合個人離線閱讀與筆記）
1. 若想一次性閱覽全部章節，直接開啟 [`full_book.md`](full_book.md)。
2. 將全部內容貼至單篇 HackMD 筆記中。
3. 文首已預設 `[TOC]`，HackMD 會自動在左側或頂部生成可折疊式的全文章節導航目錄。

---

## 🌐 如何部署至 GitHub Pages？

若欲將本教材發布為公開線上網站，操作步驟極其簡易：

1. 將本專案所有檔案（包含 `index.html`、`book.md`、`full_book.md`、`docs/` 資料夾）推送到您的 GitHub 倉庫主分支（`main`）。
2. 進入該 GitHub 倉庫的 **Settings**（設定）分頁。
3. 點選左側選單的 **Pages**。
4. 在 **Build and deployment** $\rightarrow$ **Source** 選擇 `Deploy from a branch`。
5. 分支（Branch）選擇 `main`，路徑維持預設 `/ (root)`，點擊 **Save**。
6. 等候約 1~2 分鐘，即可透過專屬網址造訪具有高質感動畫、章節閱讀器與素養測驗的線上教材首頁！

---

## 🎯 學習目標與課綱對應指標

依據 108 課綱地理核心素養，本章學習目標對應如下：

| 學習核心素養 | 具體教材實踐單元 |
| :--- | :--- |
| **地-U-A1 系統思維** | 01單元地形系統的投入、過程、產出與反饋架構；08單元屏東平原水利改道引發的海岸後退連鎖反應。 |
| **地-U-B1 符號判讀與空間分析** | 05單元曲流等高線判讀；10單元海階與谷灣地形等高線特徵；13單元1904年《臺灣堡圖》圖例與地勢套疊。 |
| **地-U-B2 資訊科技與 Web GIS** | 13單元結合「中研院百年歷史地圖」、「地名資訊服務網」、「NCDR災害潛勢地圖」進行跨時空鄉土考察。 |
| **地-U-C2 人地環境互動與倫理** | 04單元野柳女王頭保育思辨；12單元海岸突堤效應、知本溪曲流凹岸建築坍塌與沿海超抽地下水地層下陷反思。 |

---

## 📜 授權條款 (License)

本教材文本內容依據教育部開放教育資源與創用 CC **姓名標示-非商業性-相同方式分享 4.0 國際 (CC BY-NC-SA 4.0)** 授權釋出。歡迎廣大地理科教師、學生及自學者教學與研讀使用。
