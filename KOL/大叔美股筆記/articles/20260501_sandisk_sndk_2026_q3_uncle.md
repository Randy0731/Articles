# SanDisk **SNDK** 2026 Q3 財報分析：NBM 與 AI storage 估值重構

- **KOL / 來源**：大叔美股筆記 / Uncle Stock Notes
- **原文標題**：SanDisk #SNDK 2026 Q3 財報分析：78.4% 毛利率的硬體奇蹟與 NBM 帶來的估值重構
- **原文 URL**：https://unclestocknotes.substack.com/p/sandisk-sndk-2026-q3
- **官方校準**：SanDisk 2026-04-30 fiscal Q3 2026 financial results；SEC 8-K 2026-04-30
- **發文時間**：2026-05-01（Substack / 使用者提供 PDF 顯示 May 01, 2026；時區未確認）
- **整理日期**：2026-05-01
- **source_id**：大叔美股筆記-20260501-sandisk-sndk-2026-q3-ai-storage-nbm-cash-machine-f0cd3935
- **raw 路徑**：`KOL/大叔美股筆記/raw/20260501_大叔美股筆記_sandisk_sndk_2026_q3_大叔美股筆記-20260501-sandisk-sndk-2026-q3-ai-storage-nbm-cash-machine-f0cd3935.pdf`
- **OCR 狀態**：部分（使用者提供 10 頁 image-only Substack 截圖 PDF；p.1-p.7 為標題、核心正文、links 與免責聲明起始，p.8-p.10 為 disclaimer / comments / footer；核心內容已人工檢視完整，未偵測截斷）
- **相關 ticker**：**SNDK**, **WDC**, **MU**, **005930.KS**, **000660.KS**, **NVDA**, **MSFT**, **META**, **AMZN**
- **主題 tags**：#財報 #Memory #AI基建 #ReRating #估值風險 #執行風險 #競爭風險 #供應鏈風險

## 一句話摘要

大叔把 **SNDK** 2026 fiscal Q3 寫成 SanDisk 從「NAND / storage cycle stock」轉向「AI infrastructure storage capacity supplier」的拐點：datacenter revenue 暴增、NBM 長約把記憶體週期的一部分轉成可預測現金流，零負債與 buyback 提高資本配置彈性；但 `78%+` gross margin、AI KV cache / enterprise SSD 架構需求、NBM contract enforceability 與競爭者供給反應都需要逐季驗證。

整理者判定：本文是 **SNDK** 單股 L3 長文，具公司財報、商業模式、估值、風險與催化劑，正式建立 `Stocks/SNDK/`。先前 KP HBF、Melius memory re-rating 與 Samsung supply-risk 三筆 SNDK L2+ 線索同步回填為 SNDK 前史；本文不是買賣建議。

## Ticker 分流

| Ticker | 分流等級 | 本文角色 | 同步處理 |
|---|---|---|---|
| **SNDK** | L3 | 單股財報與估值重構主角；NBM、enterprise SSD、TLC / QLC、zero debt、buyback 與 AI storage demand 是核心 thesis | 新建 `Stocks/SNDK/`、季度筆記、儀表板、index、相關索引 |
| **WDC** | L1 | 2025-02-21 spin-off 背景；SanDisk 從 Western Digital 拆出後解除 conglomerate discount | 不同步 `Stocks/WDC/` |
| **MU**, **005930.KS**, **000660.KS** | L1-L2 | memory / NAND / HBM / HBF 競爭與供給反應脈絡 | 更新 ticker / theme / catalyst 語境；不建立新 `Stocks/` |
| **NVDA** | L1 | GPU idling / data starvation / memory hierarchy 的需求背景 | 不同步 `Stocks/NVDA/` |
| **MSFT**, **META**, **AMZN** | L1 | hyperscaler customer / capex / NBM demand 例子 | 不同步 `Stocks/` |

## 官方財報校準

| 項目 | 大叔 / 文章重點 | SanDisk official / 8-K 校準 | 整理者備註 |
|---|---|---|---|
| Revenue | 約 `$5.95B` / 接近 `$6B`，q/q +97%、y/y +251% | Revenue `$5.950B`，q/q +97%、y/y +251% | 與 official 一致。 |
| Gross margin | Non-GAAP gross margin `78.4%` | GAAP gross margin `78.4%`，non-GAAP gross margin `78.4%` | `78%+` 是本文 re-rating 核心。 |
| EPS | 文章圖文重點使用 `$23.41` | GAAP diluted EPS `$23.03`；non-GAAP diluted EPS `$23.41` | `$23.41` 必須標為 non-GAAP diluted EPS。 |
| Net income | GAAP net income `$3.615B` | GAAP net income `$3.615B`；non-GAAP net income `$3.675B` | official non-GAAP net income為 `$3.675B`。 |
| Datacenter | revenue +233% | Datacenter revenue `$1.467B`，q/q +233%、y/y +645% | AI storage demand 最直接證據。 |
| Edge / Consumer | consumer 約 `$0.82B` | Edge `$3.663B`，q/q +118%；Consumer `$820M`，y/y +44% | Consumer 仍成長，但本文重點已轉到 datacenter / edge。 |
| Adjusted FCF | `$2.955B` | Adjusted free cash flow `$2.955B` | SanDisk 已從 loss / cycle story 轉向現金流機器敘事。 |
| FQ4 guide | Revenue `$7.75B-$8.25B`、gross margin `79%-81%`、non-GAAP EPS `$30-$33` | official guidance 同口徑；diluted shares約 `158M` | 2026FQ4 是下一個高強度驗證點。 |
| Debt / buyback | 零負債、董事會授權 buyback | official balance sheet long-term debt `$0`；SEC 8-K 披露 board approved `$6B` share repurchase program | Buyback 不代表一定全額執行，8-K 明確保留暫停 / 終止彈性。 |

## 大叔核心 thesis

大叔的 framing 是：SanDisk 已經不是單純賣 NAND 的景氣循環公司，而是在 AI infrastructure 裡賣「低延遲、高耐用、高容量的 storage capacity」。AI inference 的瓶頸不只在 GPU，也在模型權重、長 context、KV cache 與資料搬運；當昂貴 GPU 不能因 I/O 等待而閒置，enterprise SSD / high-end TLC NAND 的戰略價值會提高。

本文最重要的拐點是 NBM（New Business Model）。SanDisk official 表示 FQ3 結束時已有 3 份 signed NBM agreements，FQ4 又簽 2 份。大叔將其解讀為 hyperscalers 用長約、committed supply 與 firm financial commitments 鎖定 capacity，SanDisk 則把傳統 memory supply / demand volatility 的一部分轉成可預測收入與現金流。

## 三個可複用框架

| 框架 | 定義 | 觀察指標 |
|---|---|---|
| NBM 長約 / AI 儲存現金流可預測框架 | Memory 公司若能用 multiyear customer engagements、take-or-pay / firm financial commitments 鎖定供需，就有機會從 commodity cycle multiple 轉向 infrastructure supplier multiple | NBM agreements 數量、contract liabilities、customer prepayments、revenue visibility、ASP、gross margin、FCF、customer concentration |
| Data Starvation / KV cache TLC 定價權框架 | AI inference 的 data movement / KV cache / local NVMe bottleneck 讓高 IOPS、高耐用 TLC enterprise SSD 具備定價權 | Datacenter revenue、enterprise SSD mix、TLC / QLC mix、gross margin、AI server storage attach、GPU utilization、CXL / DRAM alternatives |
| Zero-debt + buyback / Capital return re-rating 框架 | 當 cycle company 轉成強 FCF、零負債並啟動 buyback，市場可能重新估算 EPS durability 與股東回報 | cash、debt、buyback execution、share count、FCF conversion、gross margin durability、capex intensity |

## NBM、產品組合與資產負債表

| 母題 | 大叔觀點 | 後續要驗證 |
|---|---|---|
| NBM | hyperscalers 不只買貨，而是用 committed supply / committed financials 鎖定 SanDisk 產能，使 memory cycle 具備更高可預測性 | 合約條款是否接近 take-or-pay、是否有 renegotiation risk、contract liabilities / customer advances 是否上升 |
| TLC / QLC | 目前 portfolio 約 two-thirds TLC、one-third QLC；AI inference / KV cache 場景需要 TLC 的 IOPS / endurance / latency | Datacenter SSD mix、TLC ASP、QLC penetration、AI workload 是否維持 TLC-heavy |
| Flash Ventures / Kioxia | SanDisk 透過 49.9% Flash Ventures / Kioxia JV 與 BiCS8 / CBA 技術共享，降低單邊 capex 壓力 | JV capex、technology transition、Kioxia relationship、NAND supply discipline |
| Balance sheet | Long-term debt 從 `$1.829B` 降至 `$0`；strong cash generation 讓 buyback 有空間 | cash / FCF、buyback pace、cycle downturn 時是否重新加槓桿 |
| Institutional ownership | 大叔引用 Schedule 13G / Vanguard Capital Management 持股作機構背書 | 13G 原始檔、後續 13F / 13G 變化；不得把被動持股寫成主動看多 thesis |

## 大叔估值情境

以下全部是 KOL 模型 / 情境估值，僅作觀點追蹤，不是本專案買賣建議。

| 模型 / 錨點 | 大叔口徑 | 備註 |
|---|---|---|
| NTM EPS baseline | `$126.00` | 以 FQ4 non-GAAP EPS guide midpoint `$31.50` 年化推估，屬高度外推。 |
| Price / P-E anchor | 約 `$1,024 / 126 = 8.1x` | 文章把低 forward P/E 當成 re-rating 空間。 |
| Conservative P/E | 8.6x => `$1,083.60` | 仍接近 cycle / skeptical multiple。 |
| Base P/E | 10.0x => `$1,260.00` | 假設 NBM / gross margin 有一定 durability。 |
| Optimistic P/E | 12.0x => `$1,512.00` | 需要 market 把 SanDisk 重新視為 AI infrastructure supplier。 |
| DCF bear | `$850-$950` | 對 margin / growth / multiple 較保守。 |
| DCF base | `$1,400-$1,600` | 需要 NBM 與 datacenter demand 延續。 |
| Probability-weighted intrinsic value | `$1,207.50-$1,372.50` | 大叔模型結果；不得視為 target 或本專案建議。 |

## 風險與反例

| 風險 | 等級 | 反例 / 壓力測試 |
|---|---|---|
| NBM 長約壓力測試 | 高 | 如果 2026H2 / 2027 hyperscaler AI monetization 不如預期，Microsoft / Meta / AWS 類客戶削減 capex，NBM / take-or-pay 可能面臨 renegotiation。 |
| Gross margin gravity | 高 | NAND / SSD 是硬體製造，不是純軟體；若競爭者在 12-18 個月內轉進 high-end TLC enterprise SSD，gross margin 從 `80%` 回落到 `65%`，估值模型會明顯下修。 |
| AI 架構變化 | 中高 | 若 future attention / Mamba 類架構降低 KV cache reliance，或 CXL / memory expansion 讓更快 DRAM / pooled memory 取代部分 SSD demand，TLC SSD 定價權會受壓。 |
| 高基期 / 完美 pricing | 高 | FQ4 guide 的 `$30-$33` non-GAAP EPS 與 datacenter revenue +233% 形成極高基期；未來 growth 若從 200% 降至 50%，multiple 可能壓縮。 |
| Macro / liquidity ATM | 中高 | 股價大幅上漲後，若利率、通膨、地緣或市場風險偏好逆轉，SNDK 可能成為高流動性獲利了結標的。 |
| 口徑混淆 | 中 | `$23.41` 是 non-GAAP EPS；大叔估值年化 EPS 高度依賴 FQ4 guide 延續，不能與 GAAP earnings power 混用。 |

## 後續追蹤

| 日期 / 區間 | 事件 | 追蹤重點 |
|---|---|---|
| 2026FQ4 | SanDisk FQ4 guide check | Revenue `$7.75B-$8.25B`、non-GAAP gross margin `79%-81%`、non-GAAP EPS `$30-$33`、diluted shares `158M` |
| 每季 | NBM execution | signed agreements、contract liabilities、customer commitments、customer concentration、renegotiation language、revenue visibility |
| 每季 | Datacenter / enterprise SSD mix | Datacenter revenue、TLC / QLC mix、enterprise SSD ASP、AI server storage attach、gross margin |
| 每季 | Margin durability / supply response | NAND / SSD pricing、competitor capacity、Samsung / Micron / SK Hynix roadmap、inventory、capex |
| 每季 | Capital return | `$6B` buyback execution、share count、cash、FCF、debt |
| 2026-2027 | AI architecture and memory hierarchy | KV cache spillover、CXL / memory expansion、HBF / HBM / SSD hierarchy、Nvidia / OCP ecosystem |

## 歷史回查

正式建立 `Stocks/SNDK/` 前回查 `SNDK|SanDisk|Sandisk|WDC`。需補入 **SNDK** 前史的 L2+ 線索如下：

| 日期 | KOL / 來源 | source_id / 檔案 | 原判定 | 本次處理 |
|---|---|---|---|---|
| 2026-02-28 | KP / FOMOSoc | `KP_FOMOSoc-20260228-kp-thinking-note-31-amd-meta-ibm-google-tpu-salesforce-hbf-nvidia-netflix-openai-aws-5e901705` | **SNDK** HBF / AI memory hierarchy L2-L3 watchlist 補強 | 補入 `Stocks/SNDK/quarterly/SNDK_筆記_2026Q1.md` 作產品 / 架構前史 |
| 2026-04-28 | 大叔美股筆記 / Melius Research | `大叔美股筆記-20260428-melius-mu-sndk-memory-rerate-09b1527b` | **SNDK** L2 候選；AI data / NAND / sell-side target | 補入 `Stocks/SNDK/quarterly/SNDK_筆記_2026Q2.md` 作 re-rating 前史 |
| 2026-04-30 | 大叔美股筆記 / SemiAnalysis | `大叔美股筆記-20260430-samsung-union-memory-supply-risk-sndk-mu-wdc-3b46d028` | **SNDK** L2 supply-tightness read-through | 補入 `Stocks/SNDK/quarterly/SNDK_筆記_2026Q2.md` 作 supply-risk 前史 |
| 2026-04-18 | 宋分 / 讀者提問脈絡 | `宋分-20260418-investment-discipline-12-rebound-rhythm-position-sizing-174d6111` | 讀者問題 L1 大盤節奏脈絡 | 不補入 `Stocks/SNDK/` |
| 2026-04-28 | 大叔美股筆記 / BofA WDC | `大叔美股筆記-20260428-wdc-bofa-495-ai-storage-6824a163` | **WDC** 主線；SNDK 只作 storage-chain 邊界 | 不補入 `Stocks/SNDK/`，避免混寫 WDC / SNDK 公司範圍 |

## 整理者邊界

大叔本文語氣偏多，但本專案只記錄 KOL 觀點、公司數據、估值假設與風險，不提供買賣建議。所有 price / DCF / P-E scenario 都保留為 KOL 模型；正式追蹤 **SNDK** 的核心任務是後續驗證 NBM 是否真的降低 cyclicality、`78%+` gross margin 是否 durable，以及 AI storage demand 是否能從單季爆發變成多年現金流。
