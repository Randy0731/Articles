# Dark Pool 暗池

- **KOL**：大叔美股筆記
- **來源**：[大叔美股筆記 Substack](https://unclestocknotes.substack.com/p/dark-pool)
- **類型**：Substack 文章 / 暗池 / 大盤情緒 / 交易輔助工具
- **發文時間**：2026-02-08（Substack 公開頁與 PDF 顯示 Feb 08, 2026）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://unclestocknotes.substack.com/p/dark-pool；https://squeezemetrics.com/monitor/dix；https://www.stockgrid.io；本機原始路徑見 `private/raw_manifest.local.yaml`（未同步）
- **source_id**：大叔美股筆記-20260208-dark-pool-tools-5b8f3802
- **raw 路徑 / URL**：`KOL/大叔美股筆記/raw/20260208_大叔美股筆記_dark_pool_tools_大叔美股筆記-20260208-dark-pool-tools-5b8f3802.pdf`
- **OCR 狀態**：部分（3 頁網頁截圖 PDF；公開頁全文可讀，PDF p.1-p.2 為正文，p.3 為 discussion / footer；頁面影像清楚）
- **相關 ticker**：**TSLA**, **NVDA**, **AMD**（均為教學例子）
- **主題 tags**：#金融流動性 #投資與投機 #機構洗盤

## 主旨

大叔把暗池解釋為機構大單避開公開市場衝擊價格的私密成交場域，並提醒散戶雖然看不到即時意圖，但可以從成交後留下的 DIX、dark pool levels、option flow / prints 與券商 Time & Sales 觀察籌碼痕跡。

這篇是工具與交易框架文，不是單一 ticker thesis。大叔的結論是：不要把暗池當水晶球；價格 / K 線決定進出場，暗池數據只用來增加信心。

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **TSLA**, **NVDA** | Stockgrid 個股暗池支撐 / 壓力教學例子 | L1 | ticker index | 大叔用作「想買某檔股票時可查暗池淨部位」的例子，未形成當下個股觀點 |
| **AMD** | 即時 dark pool prints 確認趨勢的教學例子 | L1 | ticker index | 大叔用「若看好 AMD，盤中出現多筆上方成交的大單」說明信心確認；不是 AMD 新 thesis |

## 工具與用法

| 工具 / 方法 | 成本 | 大叔用法 | 判讀方式 | 風險 |
|---|---|---|---|---|
| SqueezeMetrics DIX | 免費 | 每天收盤後看大盤情緒 | DIX > `45%`：可能代表主力暗池接盤；DIX < `35%`：警戒訊號 | DIX 是大盤情緒，不是個股買賣點 |
| Stockgrid.io | 可免費試用 | 看個股暗池淨部位、Net Short Volume、Dark Pool Position 與 Dark Pool Levels | 股價下跌但暗池線上升，可能代表吸籌；巨量成交價可能成為支撐 / 壓力 | 暗池成交有延遲且不代表後續一定防守 |
| Unusual Whales / Cheddar Flow / BlackBoxStocks | 付費 / 專業 | 整合 option flow 與 dark pool prints，用於確認趨勢 | 若多筆大額成交在現價上方，可能顯示買方急迫 | 費用高、資訊噪音多；大叔建議新手先用前兩個免費工具 |
| 券商 T&S / Time & Sales | 既有券商軟體 | 過濾 `>10,000` 股或 `>5,000` 股大單，觀察 ADF / TRF 場外成交 | 一整排同樣股數、同樣價格的大單可視為「鯨魚」經過；成交價可記為防守線 | 盤中資料需與 K 線和支撐壓力一起判讀 |

## 核心框架 / 心法

- **DIX 大盤體檢框架**：大盤下跌但 DIX 高於 `45%`，大叔會視為潛在背離，代表主力可能在暗池接盤；DIX 低於 `35%` 則偏警戒。
- **Dark Pool Levels 支撐 / 壓力框架**：暗池巨量成交價容易成為後續市場記憶點；若股價跌破後又站回，可能是主力防守線。
- **價格決定、暗池確認**：大叔明確把 K 線 / 價格放在第一順位，暗池只用於增加交易信心，不用來單獨下判斷。

## 關鍵證據 / 原文訊號

| 訊號 | 出處 | 解讀 |
|---|---|---|
| 約 `40%-50%` 美股交易量發生在 dark pools | 大叔文章 p.1 / Substack 公開頁 | 暗池是市場結構的重要部分，不是小眾異常資料 |
| DIX > `45%` | 大叔文章 p.1 | 可能代表主力暗池接盤，大盤短期底部機率上升 |
| DIX < `35%` | 大叔文章 p.1 | 可能代表主力不想接，需提高回調警覺 |
| T&S 過濾 `>10,000` 股或 `>5,000` 股 | 大叔文章 p.2 | 用券商軟體做簡化版暗池 / 大單觀察 |
| ADF / TRF | 大叔文章 p.2 | 場外交易 / 暗池成交標記，可作大單痕跡 |

> 大叔（2026-02-08, 《Dark Pool 暗池》, Substack 公開頁）：「暗池數據很迷人，但不要把它當水晶球。」

> 大叔（2026-02-08）：「用 K 線（價格） 決定進出場，用暗池（DIX/大單） 來增加你的信心。」

## 風險與反例

| 風險 | 相關 ticker / 資產 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 暗池資料延遲 | 全市場 | 高 | 有些暗池成交可延後回報，看到時機已非即時 | Print timestamp、成交回報規則 | 大叔文章 |
| 把工具當水晶球 | 全市場 | 高 | 只看 DIX / prints 就下單，忽略價格結構 | K 線、支撐壓力、成交量、風險控管 | 大叔文章 |
| 大單不等於方向 | **TSLA**, **NVDA**, **AMD** 等高成交個股 | 中 | 大單可能是避險、換手、block trade 或已完成的交易 | Option flow、價格反應、後續是否守住 level | 整理者延伸 |
| 付費工具噪音 | 全市場 | 中 | 新手用昂貴工具追盤中訊號，過度交易 | win rate、交易紀律、成本 | 大叔文章 |

## 延伸追蹤

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 每日收盤後 | DIX 大盤情緒檢查 | 全市場 / SPX | DIX 高且大盤跌，偏背離；DIX 低，偏警戒 | DIX > `45%`、DIX < `35%`、SPX / QQQ K 線位置 | 大叔文章 |
| 個股進場前 | Stockgrid / T&S 暗池 level 檢查 | **TSLA**, **NVDA**, **AMD** 等 | 作為信心確認，不作單獨買賣依據 | Dark Pool Position、Net Short Volume、ADF / TRF prints | 大叔文章 |

## 整理者延伸

本篇應放在「交易工具 / 市場結構」框架庫裡，後續如果大叔或 Bytc 提到 DIX、dark pool prints、TRF / ADF 或 large block trades，可回到本篇作判讀方法基準。

本文中的 **TSLA**、**NVDA**、**AMD** 都是教學例子，不更新 `Stocks/`，也不寫成大叔對這些股票的當下買賣觀點。
