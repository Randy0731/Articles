# KOL 專屬規則

本文件只放 KOL 專屬語境與特殊處理。通用規則見 [PROJECT_RULES.md](PROJECT_RULES.md)，tag 標準化見 [docs/TAG_TAXONOMY.md](docs/TAG_TAXONOMY.md)。

## Bytc / BTYC

### 適用來源

- Bytc
- BTYC
- Btyc Substack
- 檔名含 `#BTYC`、`#BYTC`、`Bytc`

### 資料夾

```text
KOL/Bytc/raw/
KOL/Bytc/notes/
KOL/Bytc/articles/
```

### 整理重點

Bytc 常見內容類型：

- 宏觀數據週報
- 地緣政治與國防產業
- AI 基建、算力、資料中心、能源
- 暗池、CTA、流動性、散戶情緒
- 個股短評與 Substack Notes

### 寫法規則

- 短文整理後 <= 150 行：合併到 `KOL/Bytc/notes/bytc筆記.md`
- 長文整理後 > 150 行：獨立成文，放 `KOL/Bytc/articles/`
- 文章若是宏觀或產業長文，可加入 `### 結構化分析`
- 個股立場要區分「明確看多 / 看空」與「正面敘事 / 資訊分享」
- Bytc 常使用數據框架，需保留關鍵數字、時間點與風險條件

### 特別注意

- 不要把 Bytc 對題材的敘事樂觀直接寫成重倉建議。
- 若同一 ticker 同時有看多敘事與風險提醒，要寫出這個張力。
- 宏觀判斷要標出資料依據，例如 CTA、VIX、暗池點位、歷史回測。

## 大叔美股筆記 / Uncle Stock Notes

### 適用來源

- 大叔美股筆記
- Uncle Stock Notes
- Substack 文章
- Substack Note
- 社群短評
- 研究文章

### 資料夾

```text
KOL/大叔美股筆記/raw/
KOL/大叔美股筆記/notes/
KOL/大叔美股筆記/articles/
```

### 本專案預設

本專案中的「大叔美股筆記」預設處理 **文章與 Note**，不是聊天室逐字稿或每日對話分析。

只有在使用者明確提供聊天室 PDF / 逐字稿，且要求整理聊天室時，才啟用聊天室流程。否則不要主動建立每日對話分析，也不要把 Lawrence 或群友發言納入大叔文章筆記的核心來源。

### 寫法規則

- 短文整理後 <= 150 行：合併到 `KOL/大叔美股筆記/notes/大叔美股筆記.md`
- 長文整理後 > 150 行：獨立成文，放 `KOL/大叔美股筆記/articles/`
- 若是併購、產業地圖、財報、研報或個股長文，優先獨立成文
- 若文章只是轉貼新聞加短評，要區分「大叔觀點」與「新聞 / 分析師原文」
- 若文章提到價位，要標明價位性質：目標價、成本價、希望價、分析師目標價、事件價位

### 引文規則

格式：

```text
大叔（2026-04-22, 《文章標題》）：「...」
```

若來源是 PDF 且有頁碼，可加頁碼：

```text
大叔（2026-04-22, 《文章標題》, p.3）：「...」
```

不可跨日拼湊引文。不可把新聞原文、分析師目標價、社群留言或圖片價位寫成大叔明確觀點。

### 訊號判讀

必須區分：

- 明確 conviction：例如「一定贏」「我看好」「我成本」
- 觀察 / 中立：例如「我在觀察」「再看看」
- 玩笑 / 反諷：含表情符號、戲謔、群聊梗
- 轉述 / 猜測：他人說法、新聞轉貼、群友推測

### 價位判讀

必須區分：

- 目標價
- 希望價
- 成本價
- 期權履約價
- warrant / 增發事件價
- 分析師目標價
- 群友喊價

### 大叔文章 / Note 建議結構

```text
## [文章標題]

- **KOL**：大叔美股筆記
- **來源**：
- **類型**：Substack 文章 / Substack Note / 社群短評 / 研究文章
- **發文時間**：
- **整理日期**：
- **相關 ticker**：
- **主題 tags**：

### 主旨
### 個股觀點
### 核心概念
### 關鍵證據
### 風險與反例
### 延伸追蹤
```

## 宋分 / 美股送分題

### 適用來源

- 宋分
- 美股送分題
- 安分分析師
- 市場解碼
- 分析師備忘錄
- 投資紀律

### 資料夾

```text
KOL/宋分/raw/
KOL/宋分/articles/
KOL/宋分/frameworks/
```

### 整理重點

宋分文章的重點是框架，不只是單篇摘要。常見框架包括：

- re-rate
- CCC
- ROIC x Organic Growth
- Type A / Type B 確定性
- PB 到 PE 估值切換
- 機構定價階段
- 停損、加碼、出場節奏

### PDF 處理

不要預設所有 PDF 都是同一格式。先用 `file` 判斷：

- 若是真 PDF：嘗試文字抽取；文字不足再 OCR。
- 若是 ZIP 偽裝 PDF：解壓圖片後依頁序 OCR。
- 若是截圖型 PDF：依頁面做 OCR，並保留頁碼。

### 輸出規則

- 每篇原則上獨立成 `.md`，放 `KOL/宋分/articles/`
- 每篇整理後更新 `KOL/宋分/frameworks/宋分框架庫索引.md`
- 框架庫要合併同義框架，不要重複建立近似名稱
- 若是純個股文，可寫「套用框架」而非硬湊新框架

### 框架條目格式

```text
## [框架名稱]

- 來源：
- 一句話定義：
- 適用情境：
- 觀察指標：
- 相關文章：
- 可套用 ticker / 產業：
```

## KP / FOMOSoc

### 適用來源

滿足以下任一項，即視為 KP / FOMOSoc：

- Substack 來源為 `fomosoc.substack.com`
- 標題含「KP 思考筆記」「週末思考筆記」「深度分析第 N 期」
- 作者署名 KP / KP@FOMOSoc / FOMO 研究院
- 文章結尾含 `linktr.ee/fomo_soc`
- PDF 檔名含 `fomosoc-substack`

若同時出現「美股送分題」但來源、作者或檔名明確指向 KP / FOMOSoc，歸入 KP / FOMOSoc。若只出現模糊名稱，先依來源 URL 與作者判斷，不確定則問使用者。

### 資料夾

```text
KOL/KP_FOMOSoc/raw/
KOL/KP_FOMOSoc/notes/
KOL/KP_FOMOSoc/articles/
KOL/KP_FOMOSoc/weekly/
KOL/KP_FOMOSoc/deep_dive/
KOL/KP_FOMOSoc/frameworks/
```

### 觸發規則

KP / FOMOSoc 與其他 KOL 一樣：收到新文章、PDF、截圖或連結時，先偵測 KOL、文章類型與檔案格式，然後預設整理入庫。

偵測不是確認流程。只有在來源不明、疑似重複、檔案不可讀、使用者明確說不要整理，或使用者正在討論規則 / 概念問題時，才先問使用者。

### PDF 處理

第一步必做格式偵測：

```bash
file <path>
head -c 4 <path> | od -c
```

兩類格式：

- A 類真 PDF（`%PDF-`）：通常是頁面影像，`pdftotext` 可能回空；必要時 rasterize / OCR
- B 類 ZIP 偽裝 PDF（`PK`）：先 unzip，再依序讀 `1.jpeg`, `2.jpeg`, ...

禁止未偵測格式就反覆嘗試 PDF / unzip 流程。

### 檔名規則

- 週報型：`KP_KP思考筆記第NN期_[一句話摘要].md`，放 `weekly/`
- 深度分析型：`KP_深度分析第NN期_[主題].md`，放 `deep_dive/`
- 純框架 / 個股分析：`KP_[框架或主題].md`，放 `articles/`

### 整理重點

- 週報型要建立「本期主題索引」與「各主題展開」
- 深度分析 / 純框架文要建立「KP 框架拆解」
- 個股文要建立「個股觀點表」
- 框架要更新 `KOL/KP_FOMOSoc/frameworks/KP框架庫索引.md`
- 若只是引用既有框架，不新增同義框架；在既有框架補「也出現於」

### 個股交會規則

若 KP 文章對已追蹤個股達到 L2 以上重要性，除了 KP 主整理，也要依 [docs/STOCK_PROFILES.md](docs/STOCK_PROFILES.md) 更新對應 `Stocks/<Ticker>/` 的個股筆記或儀表板。不要把整篇 KP 文章複製到個股資料夾，只萃取與該股投資論述有關的內容。

## 美股老司機 3.0

### 適用來源

- 美股老司機
- 美股老司機 3.0
- 社群貼文、留言截圖、連結

### 資料夾

```text
KOL/美股老司機/raw/
KOL/美股老司機/notes/
```

### 核心框架

- 上駟：十年 1000% 類型
- 上等中駟
- 中駟：漲 50-100% 分批賣
- 投機：低價小賭
- 投資 vs 投機界線
- 圍地論
- 科技成長股五大考驗

### 寫法規則

- 新文章依序追加到 `KOL/美股老司機/notes/美股老司機投資筆記.md`
- 每篇用 `文章N` 編號
- 留言區有價值才整理
- 明確信念訊號優先，例如「一股未賣」「今天全加了」「依舊看好」
- 不要把投機標的寫成長期上駟

## Lawrence / 大師兄

### 適用來源

- Lawrence
- 大師兄
- 大師兄 Lawrence
- 投資社群截圖、聊天室技術圖、社群短評

### 資料夾

```text
KOL/Lawrence/raw/
KOL/Lawrence/notes/
KOL/Lawrence/articles/
```

### 整理重點

Lawrence 目前在本專案中主要作為技術面與投機框架來源，常見內容是 K 線圖、支撐壓力、反彈路徑、低位買點與高波動小型股觀察。

### 寫法規則

- 短圖表 / 短評整理後 <= 150 行：合併到 `KOL/Lawrence/notes/Lawrence筆記.md`
- 若單篇技術分析很長或包含完整基本面論述，再獨立成文放 `KOL/Lawrence/articles/`
- 圖上價位要區分「支撐」「壓力」「希望價」「高階技術投射」，不可直接寫成目標價或買賣建議
- 聊天室截圖若沒有日期、頁碼或原始檔，需標「推估」與 OCR / raw 限制
- Lawrence 不是大叔美股筆記來源；不得歸入大叔主筆記

## 其他 KOL

### 適用來源

無法歸入既有 KOL，但內容屬於投資文章、研究報告、財報分析、交易心法或市場觀察。

### 資料夾

```text
KOL/其他KOL/raw/
KOL/其他KOL/notes/
```

### 新 KOL 建檔規則

若同一新 KOL 出現第二篇以上，建立獨立資料夾：

```text
KOL/<新KOL名稱>/raw/
KOL/<新KOL名稱>/notes/
KOL/<新KOL名稱>/articles/
```

並更新：

- [kol_config.yaml](kol_config.yaml)
- 本文件的 KOL 專屬規則
- `indexes/source_index.md`
