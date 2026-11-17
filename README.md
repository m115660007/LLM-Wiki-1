[README.md]
# 🐾 貓咖新手教學與互動指南知識庫 (Cat Cafe Beginner & Interaction Wiki)

> 依據 **Andrej Karpathy LLM Wiki** 模式構建，融合 **國際貓科獸醫組織 (AAFP / ISFM) 友善環境指引**、台灣 **《動物展演管理辦法》（113年最新修正）**、農業部官方指引以及知名貓咖（MOCHA、紅玥緬因貓）實務經驗打造的現代化貓咪互動知識庫。

---

## 🌟 核心理念與亮點

- **動物福祉與科學優先**：破除「自嗨嚕貓」迷思，回歸貓咪自主權（Pillar 4：由貓發起、由貓選擇、由貓控制）。
- **完整知識網絡（Graph-ready）**：以 Obsidian 雙向鏈結全面交織，零孤島節點。
- **雙模互動投影片**：內建全域拓撲圖譜 (Graph View) 與 16:9 簡報投影視圖，支援完全離線播放。

---

## 📂 專案目錄結構

```text
├── assets/                  # 賓士店長貓視覺貼紙素材 (PNG)
├── raw/                     # [Layer 1] 原始來源區（純只讀真理來源）
│   ├── vet-guidelines/      # 國際獸醫指引 (AAFP / iCatCare 五大支柱)
│   ├── regulations/         # 農業部動保指南、動物展演管理辦法及 6 份官方稽查表單
│   └── web-clippings/       # 知名貓咖 (MOCHA、紅玥) 店規與訂位須知
├── wiki/                    # [Layer 2] 知識網絡區（LLM 維護 Obsidian 筆記）
│   ├── index.md             # 總索引導覽
│   ├── log.md               # 審計與異動歷史日誌
│   ├── etiquette/           # 貓咖法規、五大支柱、訪客守則、換鞋衛生
│   ├── body-language/       # 警戒三級量表、飛機耳瞳孔、呼嚕雙重含意
│   ├── interactions/        # 同意權破冰、逗貓獵物三部曲、肉泥安全、拍照禮節
│   ├── scenarios/           # 桌面防護、抓咬傷急救、兒童同行教育、多貓衝突
│   └── personalities/       # 摺耳貓軟骨痛點、曼赤肯短腿、緬因溫柔巨人
├── slides/                  # [Layer 3] 衍生產物：Graph 雙模互動簡報
│   └── index.html           # 互動投影片主程式（支援鍵盤 G 鍵開啟圖譜）
└── agent.md                 # Agent 大腦守則與維護規範
```

---

## 🖥️ 線上互動簡報 (Slides Preview)

本專案附帶互動式簡報：
- **開啟全域圖譜**：播放時按 <kbd>G</kbd> 鍵可展開 Canvas 物理動態星系圖。
- **全螢幕播放**：按 <kbd>F</kbd> 鍵切換。
- **翻頁導航**：使用 <kbd>→</kbd> / <kbd>←</kbd> 或點選推薦關聯節點按鈕。

---

## 📖 如何在本地閱讀 (Obsidian)

1. 下載並安裝 [Obsidian](https://obsidian.md/)。
2. 點選 **「開啟資料夾作為儲存庫 (Open folder as vault)」**。
3. 選擇本專案目錄，即可在 **Graph View（關聯圖譜）** 中看到所有知識節點完美互聯！
