# 一個AI夢的破滅，另一個AI夢的燃料 - KP思考筆記（第3期）

- **來源**：KP / FOMOSoc Substack
- **原始連結**：https://www.fomosoc.com/p/aiai-kp3
- **發文時間**：2025-08-16 03:55 UTC（台北 11:55）
- **整理日期**：2026-04-29
- **原檔名**：不適用（Substack 公開網頁）
- **source_id**：KP_FOMOSoc-20250816-kp-thinking-note-3-ai-dojo-nuclear-b73bfa8d
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用（Substack API `body_html` 完整可讀）
- **文章類型**：週報 / KP 思考筆記
- **相關 ticker**：**TSLA**, **NVDA**, **CEG**, **OKLO**；**AMD**, **TSM**, **MSFT**, **GOOG**, **GOOGL** 為夥伴 / 客戶 / 供應鏈脈絡
- **主題 tags**：#AI基建 #核能 #能源電力 #競爭風險 #執行風險 #ReRating

## 資料完整性

- 來源透過 Substack API post id `170973678` 與 canonical URL 讀取，`audience=everyone`，正文 HTML 可完整解析。
- 正文有開頭、Dojo 主段、核能公司成長主段、結論與 KP 署名，沒有付費牆截斷或缺頁訊號。
- API 的 `wordcount` 明顯低於正文實際長度，本次以 `body_html` 轉文字後逐段檢查，不以 `wordcount` 判定完整度。

## 主旨

KP 本期把兩個看似不同的事件放在同一條 AI 基建鏈上：一邊是 **TSLA** 自研 AI 訓練晶片 Dojo 從明星專案走向戰略重組，顯示自研硬體與全垂直整合很容易被技術、生態、人才與資本成本反噬；另一邊是核能公司因 AI data center 對 24/7 零碳電力的需求，被重新拉進成長敘事。前者提醒 AI 算力供應鏈仍由成熟平台與分工生態主導，後者則把 AI 夢的燃料從 GPU 擴展到基載電力與長約 PPA。

## 本期主題索引

| # | 主題 | 核心論點 | 涉及個股 |
|---|---|---|---|
| 1 | Dojo 的戰略重組 | **TSLA** 自研訓練晶片不是公開市場 GPU 競爭，而是服務 FSD / Optimus 的內部算力豪賭；重組反映自研硬體的現實難度 | **TSLA**, **NVDA** |
| 2 | 自研 AI 晶片的四重壓力 | 記憶體 / 散熱 / 軟體生態、核心人才流失、資本投入與供應鏈依賴、垂直整合複雜度共同壓縮 Dojo 成功率 | **TSLA**, **NVDA**, **AMD**, **TSM** |
| 3 | 核能公司的三條成長路徑 | 核能成長不是像軟體一樣快速複製，而是靠現有電廠增容、長約高價賣電、新建或新型反應爐 | **CEG**, **OKLO** |
| 4 | AI PPA 與核能再定價 | AI 巨頭需要穩定、全天候、零碳電力，可能讓核能電力從 commodity 轉成高可靠電力服務 | **CEG**, **MSFT**, **GOOG**, **GOOGL** |

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **TSLA** | Dojo 主角 / 自研 AI 訓練晶片戰略轉向 | L2 | 更新 ticker index、watchlist；不建立 `Stocks/TSLA/` | Dojo 是主題一核心，KP 將其視為自研 AI 訓練硬體的昂貴試錯與戰略糾偏，但未給 TSLA 財務模型或估值目標 |
| **NVDA** | AI 訓練平台與 CUDA 生態受益者 | L2 | 更新 ticker index；既有 watchlist 不新增專案 | Dojo 重組被 KP 解讀為 **NVDA** 訓練 GPU / CUDA 生態護城河再確認，但仍是 read-through，不是完整 NVDA 單股估值文 |
| **CEG** | 傳統核電巨頭 / 核能馬拉松式成長案例 | L3 | 更新 ticker index、watchlist；不建立 `Stocks/CEG/` | KP 用 Constellation Energy 說明既有核電資產如何靠增容、PTC、營運效率與 AI PPA 讓 EPS 增長快於營收 |
| **OKLO** | 新創核能 / 工廠製造微型反應爐案例 | L2-L3 | 更新 ticker index、watchlist；不建立 `Stocks/OKLO/` | KP 用 Oklo 作「核能電池」與工廠製造模式代表，重點是技術驗證與模式顛覆的高風險 optionality |
| **AMD**, **TSM** | Dojo 轉向後的外部夥伴 / 供應鏈脈絡 | L1 | 更新 ticker index context | AMD 被提為 GPU 供應合作方向，台積電為先進製程依賴；本文未形成 AMD / TSM 單股 thesis |
| **MSFT**, **GOOG**, **GOOGL** | AI 巨頭電力需求 / PPA 客戶脈絡 | L1 | 更新 ticker index context | Microsoft / Google 作 AI 企業長期購電需求背景；本文主角是核能供電方，不是 hyperscaler 單股分析 |

## 各主題展開

### 主題 1：Dojo 的黃粱一夢

**核心論點**：

KP 認為，Dojo 從來不是為了與 **NVDA** 或 **AMD** 在公開 GPU 市場競爭，而是 **TSLA** 為 FSD 訓練與 Optimus 機器人打算自建的內部算力引擎。這是典型的「手術刀」邏輯：放棄通用 GPU 的冗餘，針對海量影片資料與特定神經網路訓練做極致優化，同時追求成本、效能、軟硬體同源與戰略獨立。

但 KP 的判斷是，這場垂直整合豪賭遇上四座大山：

- **技術瓶頸**：Dojo 的 SRAM 架構雖有高內部頻寬，但容量不足；散熱與功耗讓訓練瓦片落地困難；自研軟體堆疊難以追上 CUDA 生態。
- **人才與管理連續性**：Jim Keller、Ganesh Venkataramanan、Peter Bannon 等核心人物先後離開，使技術路線與管理穩定性承壓。
- **經濟現實**：Exaflop 等級超算需要數十億美元研發與 capex，且仍依賴台積電先進製程，無法真正完全擺脫外部供應鏈。
- **戰略複雜度**：一家車企同時自研晶片、軟體、資料中心與製造閉環，對工程組織能力要求極高。

**KP 觀點**：

Dojo 的重組不是單純失敗，而是昂貴試錯後的戰略糾偏。它說明在 AI 訓練領域，成熟 GPU 平台、軟體生態、供應鏈節奏與開發者工具的價值，往往比單一硬體規格更重要。KP 將 **TSLA** 的後續方向理解為更混合的模式：訓練側重新擁抱 **NVDA** GPU，同時保留自研推論晶片與外部夥伴合作的可能。

### 主題 2：Nvidia 訓練霸權與專業分工

**核心論點**：

Dojo 的轉向使 KP 再次確認 AI 訓練市場的高進入壁壘。這個戰場不只是晶片設計，而是資本、IP、軟體、生態、客戶遷移成本與供應鏈節奏的總和。當 Dojo 還在爬坡時，**NVDA** 的 H100 / Blackwell 等平台已持續迭代，使 Dojo 原本期待的成本效能優勢更難兌現。

**KP 觀點**：

垂直整合並非永遠錯，但公司必須先問清楚：自己的核心優勢究竟是自建硬體，還是用市場上最強平台把自家資料、軟體與產品做出差異化？在 AI 訓練中，KP 更傾向認為成熟生態系統的價值遠高於單一硬體參數。

### 主題 3：核能公司的成長密碼

**核心論點**：

KP 把核能公司的成長拆成三條路：

| 路徑 | KP 描述 | 投資含義 |
|---|---|---|
| 榨出更多價值 | 透過 power uprates 讓既有電廠安全提升 2%-20% 發電量，或把運營許可從 60 年延至 80 年 | 傳統核電巨頭可用較低 capex 延長現金流壽命 |
| 鎖定更高利潤 | 與 AI 巨頭簽長期 PPA，用高於市場的價格出售 24/7 零碳電力 | 核能電力從 commodity 轉向高可靠能源服務 |
| 開疆拓土 | 傳統巨頭新建大型反應爐，新創公司推模組化 / 微型反應爐 | 傳統公司靠資產與政策，新創公司靠技術驗證與模式顛覆 |

**KP 觀點**：

核能公司不是以軟體式速度成長，而是用資產壽命、政策補貼、營運效率、長約價格與新建項目堆出成長曲線。對 AI data center 來說，電力的價值不只在便宜，而在穩定、低碳、可承諾與可擴展。

### 主題 4：CEG 的馬拉松與 OKLO 的衝刺

**核心論點**：

KP 以 **CEG** 作傳統核電巨頭案例。表面上，公司預期營收年增約 `3%-4%`，但其目標是到 2030 年 base EPS CAGR 超過 `13%`。這背後不是單靠收入增長，而是營運槓桿、政策 PTC、燃料與 O&M 成本下降、容量因數提升，以及與 AI 巨頭簽高價長約共同推動。

KP 引用 / 轉述的重點包括：

- 核電固定成本占比高，增加發電量可攤薄每度電成本。
- 美國核能 PTC 可作為成本抵銷，KP 口徑稱 Constellation 每年可獲超過 `$100M`，到 2028 年可能帶來約 `$500M` 增量效益。
- 行業核燃料成本自 2012 年以來下降約 `43.7%`，核電營運成本下降約 `33%`。
- Constellation 容量因數約 `94.4%`，高於行業平均。
- 與 Microsoft 的 PPA 估計價格約 `$110-$115/MWh`，使收入品質提升。

新創公司則是另一條曲線。KP 以 **OKLO** 為例，指出其首座 Aurora 微型反應爐僅約 `1.5 MWe`，目標是先在偏遠資料中心或工業設施等利基市場驗證「核能電池」模式；若工廠製造與 2-3 年建設週期能兌現，才有複製擴張的想像。

**KP 觀點**：

傳統巨頭與新創公司不是純零和競爭，而可能是同一個核能生態的兩種角色。傳統公司有營運經驗、政策影響力與客戶關係；新創公司提供技術邊界與部署彈性。真正要問的是，誰能把 AI 企業對全天候零碳電力的需求，轉成可簽約、可建設、可收款的商業模式。

## 框架沉澱

### AI 自研晶片 / 垂直整合陷阱框架

- **一句話定義**：自研晶片只有在硬體性能、軟體生態、供應鏈節奏、人才連續性與資本投入同時過關時才可能創造差異化；否則垂直整合會從護城河變成資本與組織能力的壓力測試。
- **適用情境**：Tesla Dojo、hyperscaler ASIC、AI accelerator challenger、自研 training / inference chip、make-or-buy decision。
- **觀察指標**：HBM / SRAM memory architecture、thermal / power envelope、compiler / software stack maturity、developer ecosystem、talent retention、capex, TCO, time-to-market, external GPU roadmap, customer workload fit。

### 核能成長三路徑 / AI PPA 高價值電力框架

- **一句話定義**：核能公司的成長可拆成既有資產增容與延壽、長期高價 PPA 鎖利潤、新建或模組化反應爐擴張；AI data center 需求讓全天候零碳電力具備重新定價可能。
- **適用情境**：核電營運商、SMR / advanced nuclear、新建核電、AI data center power procurement、energy infrastructure re-rating。
- **觀察指標**：power uprates、license extensions、capacity factor、PTC / policy support、PPA price / duration、AI customer commitments、fuel cost、O&M cost、EPS CAGR vs revenue growth、NRC approvals、construction cost / schedule、factory manufacturing proof。

## 風險與備註

- Dojo 相關細節、人物異動、成本與技術判斷為 KP 口徑或其引用資訊，本次未逐項用 Tesla / Nvidia / AMD / TSM 官方文件校準。
- CEG 的 EPS CAGR、PTC、PPA 價格、燃料與 O&M 成本下降等數字為 KP 口徑或其引用資料，入庫時保留為 KOL 觀點，不寫成 official guidance。
- **TSLA**, **CEG**, **OKLO**, **NVDA** 目前皆不因本篇自動建立正式 `Stocks/` 專案；後續若更多 KOL L3/L4 或使用者指定追蹤，再升級。
- 本文不是買賣建議。
