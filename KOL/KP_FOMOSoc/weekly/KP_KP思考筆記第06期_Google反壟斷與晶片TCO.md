# Google的反壟斷案還未結束？為何晶片不能堆數量？- KP思考筆記（第6期）

- **來源**：KP / FOMOSoc Substack
- **原始連結**：https://www.fomosoc.com/p/google200-kp6
- **發文時間**：2025-09-06 03:55 UTC（台北 11:55）
- **整理日期**：2026-04-29
- **原檔名**：不適用（Substack 公開網頁）
- **source_id**：KP_FOMOSoc-20250906-kp-thinking-note-6-google-adtech-chip-tco-195a48ee
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用（Substack API `body_html` 完整可讀）
- **文章類型**：週報 / KP 思考筆記
- **相關 ticker**：**GOOG**, **GOOGL**, **AAPL**, **MSFT**, **NVDA**, **ASML**, **TSM**, **005930.KS**, **INTC**, **0981.HK**, **BABA**, **AMZN**；華為未單獨建 ticker
- **主題 tags**：#監管審批 #競爭風險 #AI基建 #半導體設備 #地緣政治 #估值風險 #ReRating

## 資料完整性

- 來源透過 Substack API post id `172767355` 與 canonical URL 讀取，`audience=everyone`，正文 HTML 可完整解析。
- 正文有開頭、Google 反壟斷主題、美中晶片大戰三個補充段落、結尾與 KP 署名，沒有付費牆截斷或缺頁訊號。
- API 的 `wordcount` 明顯低於正文實際長度，本次以 `body_html` 轉文字後逐段檢查，不以 `wordcount` 判定完整度。

## 主旨

KP 本期延續第 4 期 Google / Chrome 反壟斷與上一週美中晶片長文。第一段把 **GOOG** / **GOOGL** 的搜尋預設合約與 Ad Tech 壟斷案拆開：市場若只慶祝 Search case 暫時過關，會低估 Ad Manager / AdX / DV360 這條廣告技術鏈的監管風險。第二段則把晶片戰從「能不能做出 7nm / 5nm」拉到 TCO：先進製程的核心不是名義節點，而是良率、每瓦效能、資料中心空間、互連延遲與 CUDA / 生態黏性。

## 本期主題索引

| # | 主題 | 核心論點 | 涉及個股 / 資產 |
|---|---|---|---|
| 1 | Google 司法大戰延續 | Safari 預設搜尋揭示 Google Search 現金流強度，但 Ad Tech monopoly case 仍可能打到更深的廣告基礎設施 | **GOOG**, **GOOGL**, **AAPL**, **MSFT** |
| 2 | 先進製程不是單純節點 | 中國可用 DUV 多重曝光逼近先進節點，但低良率、高成本、耗電與互連延遲讓「堆數量」難以取代先進製程 | **ASML**, **TSM**, **005930.KS**, **INTC**, **0981.HK**, **NVDA** |
| 3 | AI 雙戰場與地緣生態圈 | Nvidia / CUDA 仍主導能力之巔，中國更可能在效率平原用成本、場景與應用普及切入；未來科技估值要看生態圈在地緣市場的主導力 | **NVDA**, **BABA**, **AMZN**, **AAPL**, **GOOG**, **GOOGL** |

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **GOOG**, **GOOGL** | Google Search / Ad Tech 反壟斷主角 | L3 已追蹤個股 | 更新 ticker index、theme/catalyst/framework indexes、`Stocks/GOOGL/` | KP 將 Safari 預設搜尋收入與 Ad Tech monopoly case 串成 Alphabet 現金流與監管風險雙面，Ad Manager forced sale 是明確 L3 風險 |
| **AAPL** | Safari 預設搜尋 revenue-share 對手方 | L2 context | 更新 ticker index；不建立 watchlist | KP 用 Google 對 Apple 支付約 `$20B`、36% revenue share 反推 Safari search economics；對 Apple 是服務收入與 default-search remedy 風險脈絡 |
| **NVDA** | 中國收入、CUDA 生態與能力之巔主角 | L2 context | 更新 ticker index；既有 watchlist 不升級 | KP 指出 Nvidia 超過 15% 收入來自中國，並將 CUDA 寫成頂級 AI 訓練賽道的作業系統級 moat |
| **ASML** | EUV 設備瓶頸 | L2 context | 更新 ticker index；不建立 watchlist | KP 將 EUV 視為先進製程商業可行性的關鍵工具，限制中國取得 EUV 是美國封鎖核心 |
| **TSM**, **005930.KS**, **INTC**, **0981.HK** | 先進製程 / 中國 DUV 多重曝光比較 | L1-L2 context | 更新 ticker index；**INTC** 不同步 `Stocks/INTC/` | 台積電、三星、Intel 是先進製程三家，SMIC 是中國 7nm / 5nm 嘗試者；本文主軸是製程 TCO，不是各公司完整 thesis |
| **BABA**, **AMZN**, **AAPL**, **GOOG**, **GOOGL** | 垂直整合動機比較 | L1-L2 context | 更新 ticker index；**AMZN** 不同步 `Stocks/AMZN/` | Google / Apple / Amazon 是主動優化自研晶片，中國巨頭如華為 / 阿里是被動生存策略；這是科技地緣框架，不是單股估值文 |
| **MSFT** | Search 預設合約下被封鎖的競爭者 | L1 context | 更新 ticker index | Microsoft 只作 Google / Apple default search agreement 的競爭背景 |

## 各主題展開

### 主題 1：Google Search 過關，不代表司法戰結束

**核心論點**：

KP 認為司法部搜尋反壟斷案的價值，不只在於 Google 暫時保住搜尋分發，而是它公開了 Google Search 現金流與 Apple distribution 的巨大經濟價值。法院文件揭露 Google 對 Apple 的 Safari 預設搜尋安排接近 revenue-share 結構，KP 用約 36% 分潤與約 `$20B` 支付反推 Safari search ad revenue 約 `$55.6B`，扣除渠道費後仍有約 `$35.6B`，約占 Google Search revenue 近三成。

**KP 觀點**：

這說明 Google 願意為 iPhone / Safari 預設位置支付天價，不是因為渠道費便宜，而是因為 Apple user base 的廣告價值高、且 default position 有戰略封鎖作用。它讓 Microsoft 等競爭者更難接近高價值 mobile search traffic。

### 主題 1 延伸：Ad Tech monopoly case 才是下一個戰場

**核心論點**：

KP 將 Ad Tech case 拆成三層：

| 角色 | Google 相關工具 | KP 解讀 |
|---|---|---|
| 內容網站 / publisher | Google Ad Manager | 幫網站管理與出售廣告位，KP 引述市場上高比例網站使用 Google 工具 |
| 廣告商 / buyer | DV360 等購買平台 | 幫品牌尋找並競標廣告 inventory |
| 交易所 / exchange | Google AdX | 連接買賣雙方，KP 稱其為交易量超過 50% 的最大廣告交易平台 |

這形成 Google 同時代表賣方、買方又經營交易所的利益衝突。KP 認為這不是單一產品問題，而是 Google 網路廣告利潤核心。2025-04-17 美國地方法院法官 Leonie Brinkema 已判定 Google 相關行為構成非法壟斷；2025-09-22 法庭進入 remedy / penalty hearing，司法部嚴厲版本是要求 Google 出售 Google Ad Manager。

**KP 觀點**：

市場若只把焦點放在 Search / Chrome remedy，會低估 Ad Tech case 對 Alphabet monetization stack 的威脅。Ad Manager / AdX / DV360 是 publisher inventory、advertiser demand 與 auction mechanism 的交會點，若被拆分或行為受限，Google 的 take rate、廣告資料優勢、publisher relationship 與 display ad economics 都可能被重估。

### 主題 2：晶片不能只靠堆數量

**核心論點**：

KP 反駁「算力不夠就用成熟製程堆晶片」的直覺。中國的 **0981.HK** / SMIC 能用 DUV 多重曝光為華為等客戶做出 7nm、甚至接近 5nm 的晶片，但這條路會遇到低良率、高單位成本與複雜工序。EUV 的價值不是名義節點，而是讓先進節點具備高良率與商業量產可行性。

KP 把成熟製程堆算力的 TCO 拆成兩堵牆：

- **能源效率**：AI data center 的電費是生存成本。先進製程的每瓦效能更高，成熟製程即使用更多晶片補算力，也可能被電力與散熱成本拖垮。
- **空間與互連延遲**：AI 訓練需要大量晶片像單一叢集協作。晶片越分散，機架、資料中心面積與通訊距離越大，延遲與同步成本吃掉有效算力。

**KP 觀點**：

成熟製程可以支撐部分中國內需的「內循環」算力基礎，但難以成為全球頂級 AI 算力競爭的門票。這對 **ASML** 的 EUV chokepoint、**TSM** / Samsung / **INTC** 的先進製程地位、以及 **NVDA** 高階 GPU / networking / CUDA 平台 moat 都是正向背景。

### 主題 3：中國 AI 更可能走效率平原，不是硬爬算力高峰

**核心論點**：

KP 把 AI 競爭分成兩個戰場：

- **能力之巔**：追求最強模型與最大訓練叢集，玩家對成本不敏感，重視搶先完成訓練。這是 **NVDA** / CUDA 最強的地方，CUDA 像 AI 開發的作業系統，轉換成本極高。
- **效率平原**：絕大多數企業與消費應用只需要夠用、便宜、好用的 AI。中國的優勢在大市場、場景落地、供應鏈整合與成本控制。

**KP 觀點**：

中國未來更可能像電動車產業一樣，把外部已證明方向做成 1 到 N 的極致普及，而不是在最高端 foundation model / frontier training 正面擊敗 Nvidia 生态。這對投資研究的提示是：中國 AI 機會可能不在「最強算力」，而在高性價比應用與垂直場景落地。

### 主題 4：垂直整合的動機分裂

**核心論點**：

KP 認為美中科技巨頭都在走垂直整合，但動機不同：

| 陣營 | 代表 | 動機 | 性質 |
|---|---|---|---|
| 西方巨頭 | Google, Apple, Amazon | 讓搜尋、雲端、作業系統更高效，降低成本、提升體驗 | 主動優化 |
| 中國巨頭 | 華為, 阿里 | 在無法取得最先進晶片時保住供應與生態自主 | 被動求生 |

短期看，技術分岔會造成重複投資、互不兼容標準與全球創新效率下降。但從投資角度，KP 認為未來十年評估科技公司不能只問「誰技術最好」，而要問「誰的生態圈在什麼地緣市場具有主導權」。

## 框架沉澱

### Ad Tech 垂直整合 / 平台稅壟斷框架

- **一句話定義**：當平台同時控制 publisher ad server、advertiser buying tool 與 exchange，收入優化可能不再服務買方或賣方，而是服務平台自身 take rate 與資料優勢。
- **適用情境**：Google Ad Manager / AdX / DV360、digital advertising exchange、publisher monetization、ad tech antitrust。
- **觀察指標**：Ad Manager remedy、AdX auction rule、DV360 routing、publisher take rate、TAC、Search & Network revenue、DOJ remedy order、appeals timeline、advertiser ROI、publisher revenue share。

### 先進製程 TCO / 算力堆數量失效框架

- **一句話定義**：AI 算力不能只用晶片數量衡量，真正成本要同時計入良率、單位成本、每瓦效能、資料中心空間、散熱、互連延遲與叢集利用率。
- **適用情境**：中國 DUV 多重曝光、SMIC 7nm / 5nm、EUV export controls、AI data center TCO、mature-node AI chips。
- **觀察指標**：yield rate、cost per die、performance per watt、cluster utilization、interconnect latency、rack density、power availability、cooling cost、EUV access、HBM / advanced packaging availability。

### AI 雙戰場 / 峰頂算力與效率平原框架

- **一句話定義**：AI 競爭可分成 frontier training 的能力之巔與 mass-market deployment 的效率平原；前者重視極限性能與軟體生態，後者重視成本、場景、整合與普及速度。
- **適用情境**：Nvidia CUDA moat、中國 AI 應用公司、enterprise AI deployment、低成本模型、developing-market AI solutions。
- **觀察指標**：frontier model training cost、CUDA / software ecosystem switching cost、inference cost、enterprise adoption、application revenue、model performance per dollar、local hardware compatibility、global expansion。

### 科技地緣生態圈 / 垂直整合動機框架

- **一句話定義**：地緣分裂下，自研晶片與垂直整合不一定代表效率最大化；要區分主動優化與被動求生，並評估每個生態圈在各自地緣市場的主導力。
- **適用情境**：Google TPU、Apple M-series、Amazon Trainium / Inferentia、Huawei Ascend、Alibaba AI chips、中美 tech decoupling。
- **觀察指標**：ecosystem lock-in、chip availability、domestic substitution rate、software compatibility、cloud / device integration、customer retention、capex intensity、export-control changes、regional market share。

## 風險與備註

- Google / Apple revenue share、Safari search revenue、Ad Manager / AdX 市占、法院判決與 hearing 日期均為 KP 口徑或其引用資訊；本次按原文入庫，未逐項用官方 docket / filings 校準。
- **GOOG** / **GOOGL** 判定為 L3 已追蹤個股，補入 `Stocks/GOOGL/`；這是歷史風險增量，不直接改寫 2026 最新 Alphabet thesis。
- **AAPL**, **MSFT**, **NVDA**, **ASML**, **TSM**, **005930.KS**, **INTC**, **0981.HK**, **BABA**, **AMZN** 均為分發、競爭、供應鏈或地緣生態脈絡；除既有 `Stocks/GOOGL/` 外，本篇不新增 `Stocks/`。
- 本文不是買賣建議。
