# KOL 投資文章追蹤系統

這個專案用來整理、入庫、查詢與交叉比對不同投資 KOL 的文章、短 Note、PDF、截圖與聊天室紀錄。核心目標不是逐字翻譯，而是建立可查詢、可追蹤、可驗證的研究筆記。

## 快速使用

常見指令範例：

- `這批文章幫我入庫`
- `這是新的 Bytc 文章，照規則整理`
- `幫我查大叔最近對 MU 的觀點變化`
- `幫我看宋分哪幾篇講過 CCC`
- `幫我比較同一個 KOL 前後對 ONDS 的看法`

預設行為：

- 上傳新文章、PDF、截圖或聊天紀錄時，先判斷 KOL，再整理入庫。
- 查詢觀點變化時，預設只在同一個 KOL 的資料內交叉比對。
- 不提供買賣建議，只整理觀點、訊號、風險、催化劑與證據。

## 重要檔案

- [PROJECT_RULES.md](PROJECT_RULES.md)：全域規則與鐵律
- [kol_config.yaml](kol_config.yaml)：KOL 對應資料夾與機器可讀設定
- [docs/KOL_PROFILES.md](docs/KOL_PROFILES.md)：各 KOL 專屬規則
- [docs/STOCK_PROFILES.md](docs/STOCK_PROFILES.md)：個股專案規則與 KOL×個股交會規則
- [docs/FORMAT_SPEC.md](docs/FORMAT_SPEC.md)：寫作格式硬規格
- [docs/TAG_TAXONOMY.md](docs/TAG_TAXONOMY.md)：通用 tags、事件 tags、風險 tags 與個股母題字典
- [docs/INGEST_WORKFLOW.md](docs/INGEST_WORKFLOW.md)：新文章入庫流程
- [docs/QUERY_WORKFLOW.md](docs/QUERY_WORKFLOW.md)：查詢與交叉比對流程
- [docs/TEMPLATES.md](docs/TEMPLATES.md)：筆記與索引模板

## 資料夾結構

```text
article-record/
├── KOL/
│   ├── Bytc/
│   ├── 大叔美股筆記/
│   │   ├── raw/
│   │   ├── notes/
│   │   └── articles/
│   ├── 宋分/
│   ├── KP_FOMOSoc/
│   ├── 美股老司機/
│   └── 其他KOL/
├── Stocks/
│   ├── ONDS/
│   │   ├── raw/
│   │   ├── notes/
│   │   ├── quarterly/
│   │   ├── milestones/
│   │   ├── longform/
│   │   ├── ONDS_儀表板.md
│   │   └── ONDS_index.md
│   └── 其他個股/
├── Research/
│   ├── raw/
│   ├── notes/
│   ├── industry/
│   ├── macro/
│   └── comparisons/
├── indexes/
│   ├── ticker_index.md
│   ├── theme_index.md
│   ├── framework_index.md
│   ├── catalyst_index.md
│   ├── watchlist_index.md
│   └── source_index.md
├── docs/
├── inbox/
└── logs/
```

## 工作原則

- 先判斷任務類型，再決定是否入庫、查詢或比對。
- 每篇文章都要保留來源、日期、KOL、ticker、主題 tag。
- 每篇入庫資料都要有 `source_id`；原始實體檔保留 raw 複本或原始路徑，並標示 OCR 狀態。
- 所有明確引文都要能追回來源。
- 嚴格區分 KOL 觀點、群友喊價、分析師目標價、玩笑與轉述。
- KOL 是來源，Stocks 是研究對象；同一篇 KOL 原文只做一份主整理，個股資料夾只放投資論述萃取與儀表板更新。
- 新 ticker 預設只進 `ticker_index.md`；達到升級條件才建立 `Stocks/<Ticker>/`，不因首次提及就自動開專案。
- 非 KOL、非單一個股的產業 / 宏觀 / 橫向比較資料放 `Research/`。
- 框架庫只放可複用的方法論，不放一次性新聞摘要。
- tag 優先使用 [docs/TAG_TAXONOMY.md](docs/TAG_TAXONOMY.md)，避免同義詞分裂。
