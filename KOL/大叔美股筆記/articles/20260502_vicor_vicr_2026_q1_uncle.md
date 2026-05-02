# Vicor **VICR** 2026 Q1 財報分享

- **KOL**：大叔美股筆記
- **來源**：[大叔美股筆記 Substack](https://unclestocknotes.substack.com/p/vicor-vicr-2026-q1)；[Vicor official Q1 2026 results](https://vicorcorporation.gcs-web.com/news-releases/news-release-details/vicor-corporation-reports-results-first-quarter-ended-march-13)；[Vicor 2026Q1 10-Q](https://www.sec.gov/Archives/edgar/data/751978/000119312526194947/vicr-20260331.htm)
- **類型**：Substack 文章 / 財報分析 / AI power delivery / vertical power / Factorized Power Architecture / aerospace and defense / valuation scenarios
- **發文時間**：2026-05-02（Substack 頁面 / PDF 顯示 May 02, 2026；時區未確認）
- **整理日期**：2026-05-02
- **原始檔案 / URL**：https://unclestocknotes.substack.com/p/vicor-vicr-2026-q1；本機原始路徑見 `private/raw_manifest.local.yaml`（未同步）
- **source_id**：大叔美股筆記-20260502-vicor-vicr-2026-q1-ai-power-base-3e39b7e6
- **raw 路徑 / URL**：`KOL/大叔美股筆記/raw/20260502_大叔美股筆記_vicor_vicr_2026_q1_大叔美股筆記-20260502-vicor-vicr-2026-q1-ai-power-base-3e39b7e6.pdf`
- **OCR 狀態**：部分（10 頁 image-only Substack 截圖 PDF；p.1-p.7 為標題、核心正文、valuation / DCF、備忘錄與 links，p.8-p.10 為 disclaimer / comments / 推薦文章 / footer；核心內容可可靠判讀，財報數字以 Vicor official Q1 2026 results / SEC 10-Q 校準）
- **相關 ticker**：**VICR**, **NVDA**, **AMD**, **TXN**, **MPWR**
- **主題 tags**：#財報 #AI基建 #功率半導體 #能源電力 #先進封裝 #ReRating #估值風險 #執行風險 #競爭風險 #供應鏈風險

## 主旨

大叔把 **VICR** 重新定位成 AI 算力硬體的 power base，而不是一般電源零組件公司。核心論點是：當 GPU / ASIC 功耗往 1000W、2000W 與更高密度 rack 推進，真正瓶頸不只在晶片本身，而在高電流、低電壓、低損耗、低熱量的供電架構。Vicor 的 vertical power delivery、FPA 與高密度模組，若能進入 advanced package / GPU 周邊設計，就可能從零組件供應商 re-rate 成 AI infrastructure supplier。

文章語氣偏多，但大叔也把估值風險講得很明確：若以 full-capacity EPS `$8-$10`、中位 `$9.00` 估算，文章事件價位約對應 forward P/E `29.7x`，不便宜。後續要用 backlog conversion、book-to-bill、gross margin、capacity ramp、hyperscaler / OEM design-in 與競爭者是否突破 `1.5mm` 封裝限制來驗證。

## Ticker 分流

| 股票代號 | 關聯等級 | 立場 / 角色 | 本次處理 |
|---|---|---|---|
| **VICR** | L3 | 大叔主文個股；AI power delivery / vertical power / FPA / defense power module 受益者 | 正式建立 `Stocks/VICR/` |
| **NVDA** | L1-L2 | 高功耗 GPU / Rubin / AI rack power 背景 | 僅進 index；不建立新 **NVDA** thesis |
| **AMD** | L1 | 高功耗 AI accelerator 背景 | 僅作 supply-chain context |
| **TXN**, **MPWR** | L1-L2 | power management peers；大叔提到同業財報也強 | 僅作功率半導體同業脈絡 |

## 官方校準

| 項目 | 數字 / 內容 | 來源 | 備註 |
|---|---|---|---|
| Q1 2026 revenue | `$113.0M`，y/y +20.2%，q/q +5.3% | Vicor official Q1 results | 與大叔文一致 |
| Gross margin | `$62.4M` / `55.2%`，去年同期 `47.2%` | Vicor official Q1 results | 大叔用來支撐 pricing power / product mix thesis |
| Net income / EPS | Net income `$20.7M`，diluted EPS `$0.44` | Vicor official Q1 results | 大叔文稱 EPS beat expected `$0.40` |
| Backlog | `$300.6M`，q/q +70%，y/y +75% | Vicor official Q1 results | 大叔將 book-to-bill >2 和 backlog 視為需求爆發證據 |
| Cash / liquidity | Cash and equivalents `$404.2M`；current assets `$599.469M`；total assets `$804.881M` | Vicor official / SEC 10-Q | 支撐 capacity expansion cushion |
| Operating cash flow | `-$3.947M`，包含 litigation payment `$28.557M` | SEC 10-Q | 大叔稱扣除 one-time litigation payment 後 core OCF 約 `$24.7M` |
| Capex | `$12.4M` Q1；planned commitments `$25.309M` | Vicor official / SEC 10-Q | 對應 capacity ramp / second fab |

## 結構化分析

| 面向 | 大叔觀點 | 驗證方式 |
|---|---|---|
| AI power bottleneck | AI server / GPU power delivery 從配角變成限制條件；高功耗 GPU 若供電不好，算力無法穩定釋放 | rack power、GPU TDP、power loss / thermal data、customer design-in |
| 技術護城河 | Vicor 的 FPA / vertical power 把 regulation 與 transformation / current multiplication 拆開，讓 tiny current multiplier 更接近 GPU / package | 2nd Gen VPD module adoption、module thickness、customer qualification、competitor specs |
| 1.5mm packaging moat | 文章把 `1.5mm` 視為 advanced packaging / CoWoS 周邊供電門檻；若 Vicor 能做得更薄，設計替換難度上升 | package-level power delivery roadmap、CoWoS / advanced packaging qualification、OEM dual-source language |
| 財報爆發 | Revenue `$113M`、GM `55.2%`、book-to-bill >2、backlog `$300.6M` 顯示 demand > shipment | 每季 revenue conversion、backlog、book-to-bill、gross margin |
| 軍工底盤 | 大叔稱 Vicor 在 aerospace / defense DC-DC converter market 具高市占，服務大型 military-industrial customers；SwaP 是長期優勢 | Defense revenue mix、program wins、product life cycle、margin / qualification |
| 產能路徑 | Federal Street 周邊擴建與 second factory / second fab 目標支撐 `$1.5B` annual revenue capacity | Capex、capacity commentary、second fab timeline、yield / utilization |

## 價位與催化劑

| 類型 | 內容 | 日期 / 價位 | 來源 | 備註 |
|---|---|---|---|---|
| 事件市值 | 大叔文使用 market cap | 約 `$12.183B` | 大叔文章 | 事件估值錨點 |
| 產能目標 | 滿產 revenue capacity | `$1.5B` annual revenue | 大叔文章 / management capacity path | 需用擴產進度驗證 |
| Earnings power | full-capacity EPS range | `$8.00-$10.00`，中位 `$9.00` | 大叔文章 | KOL 模型，不是 company guidance |
| 隱含倍數 | `$268 / $9.00` | 約 `29.7x` | 大叔文章 | 大叔稱不便宜，但若 AI power bottleneck 成真仍可合理 |
| DCF bear | AI capex 2027 見頂、競爭者突破 `1.5mm` | `$140-$170` | 大叔文章 | KOL 情境，不是建議 |
| DCF base | 消化 `$300M` backlog、順利達 `$1.5B` revenue、GM 55% | `$250-$280` | 大叔文章 | KOL 情境，不是建議 |
| DCF bull | vertical power 成為 AI server / autonomous driving / supercomputer standard，GM >60% | `$350+` | 大叔文章 | KOL 情境，不是建議 |
| 每季催化 | backlog、book-to-bill、gross margin、capacity conversion | 2026 起每季 | 大叔文章 / official results | 主要驗證項 |

## 核心框架 / 心法

- **AI 電力底座 / 垂直供電 re-rating**：AI rack power 從 40kW 到 100kW、500kW+ 時，供電效率、電流密度與熱管理會從成本項變成算力可用率的限制條件。
- **封裝內供電 / 1.5mm design-in 護城河**：若 power module 被放進或貼近 advanced package，替換供應商不再只是 BOM 替換，而會牽涉封裝、散熱、layout 與 qualification。
- **SwaP 軍工底盤**：Size、Weight、Power 對 UAV、radar、electronic warfare 等軍工系統是硬限制；長產品週期與高 qualification 門檻可提供 counter-cyclical base。

## 關鍵證據

| 證據 | 解讀 |
|---|---|
| Q1 revenue `$113.0M`、GM `55.2%` | 需求與 mix 支持大叔對 pricing power / high-density module 的看法 |
| Backlog `$300.6M`、book-to-bill >2 | demand 明顯高於 shipments；後續若轉成 revenue，會支撐 2026 剩餘季度 |
| OCF `-$3.947M` net of litigation payment `$28.557M` | 表面 cash flow 為負，但大叔認為 litigation payment 是 one-time overhang 清除 |
| Current assets `$599.469M`、cash `$404.245M` | 產能擴張有資產負債表緩衝 |
| CEO official language 提到 high performance compute、ATE、industrial、aerospace and defense demand strong | 官方需求敘述不只 AI，也包含其他 industrial / defense demand；需要拆 mix |

## 風險與反例

| 風險 | 相關 ticker | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 估值已反映 `$1.5B` capacity / full-capacity EPS | **VICR** | 高 | 產能 ramp 延遲或 demand conversion 不及預期 | Forward P/E、EPS revisions、backlog conversion、capacity utilization | 大叔 valuation 段 |
| AI capex cycle peak | **VICR**, **NVDA**, **AMD** | 高 | AI capex 2027 前後放緩，高功耗 server demand 低於預期 | Hyperscaler capex、GPU / ASIC shipments、rack power roadmap | 大叔 bear case |
| 競爭者突破封裝厚度 / current density | **VICR**, **TXN**, **MPWR** | 高 | 競爭者達到類似 `1.5mm` 或更薄 package-level power solution | Product specs、customer wins、dual-source language | 大叔 bear case |
| Capacity execution | **VICR** | 中高 | Federal Street / second fab 進度、yield 或 capex 不順 | Capex、facility timeline、utilization、gross margin | Official results / SEC 10-Q |
| Customer concentration / design-in 未落地 | **VICR** | 中高 | 高 performance compute 客戶未轉成 durable production orders | Backlog quality、10-Q customer concentration、hyperscaler / OEM disclosures | 整理者判斷 |
| Litigation / IP overhang 未完全消失 | **VICR** | 中 | 已付款項不代表未來完全沒有 legal / IP friction | 10-Q legal proceedings、future accruals | SEC 10-Q |

## 延伸追蹤

| 日期 / 節奏 | 事件 | 相關 ticker | 追蹤重點 | 出處 |
|---|---|---|---|---|
| 每季 | **VICR** backlog / book-to-bill / GM check | **VICR** | `>2` book-to-bill 是否維持、`$300.6M` backlog 轉 revenue、GM 是否守住 55%+ | 大叔文章 / Vicor official |
| 2026-2028 | `$1.5B` annual revenue capacity path | **VICR** | Federal Street expansion、second factory / fab、capex、yield、capacity utilization | 大叔文章 / Vicor official |
| 每季 | VPD / FPA hyperscaler and OEM design-in | **VICR**, **NVDA**, **AMD** | 2nd Gen VPD、package-level power、OEM redundancy / alternate-source commentary | 大叔文章 / Vicor official |
| 每季 | Defense / aerospace SwaP base | **VICR** | Defense program commentary、qualification、long-cycle revenue stability | 大叔文章 |

## 整理者延伸

歷史回查 `VICR|Vicor|vicor` 未發現既有入庫資料，因此本篇是 **VICR** 第一篇正式單股 thesis。它可與既有 AI infrastructure map 串接：**TER** 是 AI compute reliability / test insurance，**SNDK** 是 memory / storage capacity layer，**GLW** 是 optical interconnect / photonics materials，**VICR** 則補上 power delivery / vertical power base。

本文沒有本專案買賣建議；大叔文中的 fair value / DCF / P/E 均記為 KOL 情境估值。
