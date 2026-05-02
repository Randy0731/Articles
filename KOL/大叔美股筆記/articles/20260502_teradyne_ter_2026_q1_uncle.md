# Teradyne **TER** 2026 Q1 財報分析

- **KOL**：大叔美股筆記
- **來源**：[大叔美股筆記 Substack](https://unclestocknotes.substack.com/p/teradyne-ter-2026-q1)；[Teradyne official Q1 2026 results](https://investors.teradyne.com/news-events/press-releases/detail/440/teradyne-reports-first-quarter-2026-results)
- **類型**：Substack 文章 / 財報分析 / 半導體測試設備 / HBM / AI chip test / Robotics
- **發文時間**：2026-05-02（Substack 頁面 / PDF 顯示 May 02, 2026；時區未確認）
- **整理日期**：2026-05-02
- **原始檔案 / URL**：https://unclestocknotes.substack.com/p/teradyne-ter-2026-q1；本機原始路徑見 `private/raw_manifest.local.yaml`（未同步）
- **source_id**：大叔美股筆記-20260502-teradyne-ter-2026-q1-ai-test-structural-profit-leverage-57131493
- **raw 路徑 / URL**：`KOL/大叔美股筆記/raw/20260502_大叔美股筆記_teradyne_ter_2026_q1_大叔美股筆記-20260502-teradyne-ter-2026-q1-ai-test-structural-profit-leverage-57131493.pdf`
- **OCR 狀態**：部分（9 頁 image-only Substack 截圖 PDF；p.1-p.6 為標題、核心正文、links 與免責聲明起始，p.7-p.9 為 discussion / 推薦文章 / footer。頁面影像清楚，核心財報數字以 Teradyne official Q1 2026 results 校準）
- **相關 ticker**：**TER**, **NVDA**, **AMD**, **MU**, **000660.KS**, **AAPL**
- **主題 tags**：#財報 #AI基建 #半導體設備 #先進封裝 #Memory #ReRating #估值風險 #執行風險 #競爭風險

## 主旨

大叔把 **TER** 2026Q1 財報解讀為半導體測試設備從消費電子週期股轉向 AI 算力測試基礎設施的拐點。過去 Teradyne 常被市場用手機、PC 與 Apple 換機週期定價，因此估值容易被壓在傳統測試設備循環股區間；這篇的核心改變是，AI GPU / ASIC、HBM、chiplet、SLT 與 data center 零容錯需求，讓測試設備變成高價 AI 算力的可靠性保險。

這篇是 **TER** L3 主題個股文，並將 **TER** 建立為正式追蹤個股。大叔立場是結構上偏正面：Q1 revenue `$1.282B`、non-GAAP EPS `$2.56`、non-GAAP gross margin `60.9%`，加上約 70% revenue 與 AI demand 相關，使 TER 不再只是消費電子測試週期。風險在於 Q2 guide 低於 Q1、半導體設備訂單波浪式採購、AI capex 是否過熱、HBM 供給可能反轉，以及估值已反映不少樂觀情境。本專案只記錄 KOL 觀點，不提供買賣建議。

## Ticker 分流

| Ticker / 實體 | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **TER** | 主角 / Teradyne 2026Q1 財報、半導體測試、HBM / chiplet / SLT、Robotics 與估值情境 | L3 | KOL 長文獨立整理；建立 `Stocks/TER/` 專案、季度筆記、儀表板與 index | 整篇圍繞 **TER** Q1 revenue / EPS / margin、AI revenue mix、Semiconductor Test、System Test、Robotics、DCF 情境與風險 |
| **NVDA**, **AMD** | AI GPU / next-gen AI chips / hyperscaler compute demand 背景 | L1 | ticker / theme context | 大叔用 NVIDIA / AMD next-gen AI chip build cycle 解釋 tester demand wave，不形成這些 ticker 的新 thesis |
| **MU**, **000660.KS** | HBM / DRAM testing demand 背景 | L1 | ticker / theme context | 大叔用 Micron / SK Hynix 類 HBM 供應商說明 KGD、Magnum 與 test time 增加，不形成單獨記憶體股觀點 |
| **AAPL** | Teradyne 歷史 consumer electronics cycle 背景 | L1 | ticker context | 大叔用 Apple / phone / PC replacement cycle 對比過去估值框架，並非新 **AAPL** thesis |
| Universal Robots / MiR | TER robotics segment、AI inference into robots | L2 context | 收入與風險收進 **TER** 筆記 | 兩者是 Teradyne 旗下業務，不是獨立上市 ticker |

## 官方校準

| 項目 | 大叔文章 / PDF 口徑 | Teradyne official 校準 | 整理者處理 |
|---|---|---|---|
| Q1 revenue | `$1.282B`，year-on-year +`87%`，quarter-on-quarter +`18%` | Q1 2026 revenue `$1,282M` | 一致，作為財報基準 |
| Q1 EPS | non-GAAP EPS `$2.56`，year-on-year +`241%` | GAAP EPS `$2.19`；non-GAAP EPS `$2.56` | 一致；文章重點採 non-GAAP EPS |
| Gross margin | non-GAAP gross margin `60.9%` | GAAP gross margin `60.7%`；non-GAAP gross margin `60.9%` | 一致，支撐 operating leverage |
| Semiconductor Test | `$1.111B` / 約 `86.6%` of revenue | Semiconductor Test sales `$1,110.9M` | 一致；主要由 AI computing chips、HBM 與 high-speed networking processors 帶動 |
| Robotics | 約 `$91M` | Robotics sales `$91.2M` | 一致；涵蓋 Universal Robots / MiR |
| System Test | 約 `$80M` | System Test sales `$80.3M` | 一致；SLT / storage / aerospace and defense 等需求 |
| Q2 guidance | revenue `$1.15B-$1.25B`；non-GAAP EPS 約 `$1.78-$2.07` | Revenue `$1,150M-$1,250M`；GAAP diluted EPS `$1.54-$1.83`；non-GAAP diluted EPS `$1.78-$2.07` | 一致；低於 Q1 但大叔解讀為 batch purchase / build phase 波動 |
| Mid-term model | revenue `$6B`、EPS `$9.50-$11.00` / `$11` | 文章引用 management mid-term target；official Q1 PR 本頁未完整展開該模型 | 保留為 KOL / management model 口徑，與 official quarterly results 分開 |

## 結構化分析

| 面向 | 大叔整理的重點 | 對 **TER** thesis 的含義 | 追蹤重點 |
|---|---|---|---|
| 需求重心轉移 | 約 70% revenue 與 AI demand 相關，從手機 / PC 測試週期轉向 AI compute cycle | 若 AI chip value 上升且容錯率下降，測試設備不再只是 cyclical capex，而是 reliability insurance | AI-related revenue mix、Compute / Memory / Networking demand、tester backlog |
| Q1 財報 | Revenue `$1.282B`、non-GAAP EPS `$2.56`、non-GAAP GM `60.9%` | 高毛利與 modest opex growth 讓 revenue 增量大幅轉成 operating profit | Revenue growth、GM、opex as % revenue、operating margin、EPS |
| Semiconductor Test | `$1.111B`，約 `86.6%` of revenue；UltraFLEX / Magnum demand tight | TER 的核心價值在 SoC / memory test，尤其 AI GPU / ASIC、HBM、networking processors | UltraFLEXplus supply, Magnum demand, customer capex, foundry / OSAT tester purchases |
| HBM test time | HBM 8 / 12 / 16-high stack 需 KGD 與 TSV 測試；test time and complexity 遠高於 DDR5 | HBM capacity growth 會同時放大 tester unit demand 與 test intensity | HBM shipments, SK Hynix / Micron capex, test time per die, memory tester ASP |
| Wafer-to-Data Center | 測試從 wafer sort、final test 延伸到 SLT / data center reliability | AI training / inference systems 對 failure tolerance 極低，SLT 可能成為下一個增長引擎 | SLT revenue, System Test growth, CoWoS / chiplet package complexity, hyperscaler qualification |
| Robotics | Universal Robots / MiR Q1 sales `$91.2M`；AI inference 可能讓協作機器人從程式化工具升級 | 提供非半導體週期的 optionality，但目前仍不是主要獲利來源 | Robotics revenue growth, AI-enabled product launches, industrial demand, margin |
| 資本配置 | 2015 至 2026Q1 cumulative FCF `$5.6B`，大叔圖表口徑約 97% FCF returned to shareholders | TER 有長期 buyback / dividend discipline，但未必能抵消半導體設備周期與估值壓縮 | Buyback pace, share count, FCF, dividend, acquisition discipline |

## 價位與催化劑

| Ticker | 價位 / 數字 | 價位性質 | 來源 / 說話者 | 時間 | 備註 |
|---|---|---|---|---|---|
| **TER** | `$343` | 大叔估值演算使用的文章當下股價 / anchor price | 大叔文章 | 2026-05-02 | 非買點或目標價 |
| **TER** | 2026 EPS potential `$9.00-$10.00` | 大叔全年 EPS 假設 | 大叔文章 | 2026-05-02 | 前提是 H2 AI chip shipments rise |
| **TER** | Mid-term EPS `$9.50-$11.00` / `$11` | management mid-term model / 大叔引用 | 大叔文章 | 2026-05-02 | 不是當季 guidance |
| **TER** | 約 `36x` / `31x` | 以 `$343` 對 2026 EPS `$9.5` / target EPS `$11` 的 P/E 粗估 | 大叔文章 | 2026-05-02 | 大叔認為不便宜，但相對先前 45x+ 已壓縮 |
| **TER** | `$240-$270` | DCF bear case | 大叔文章 | 2026-05-02 | North America AI capex peaks in 2027、HBM capacity oversupply |
| **TER** | `$310-$350` | DCF base case | 大叔文章 | 2026-05-02 | AI test demand steadily realized、GM >60%、robotics mild recovery |
| **TER** | `$420+` | DCF bull case | 大叔文章 | 2026-05-02 | AI chips broadly shift to complex chiplet architectures，test demand multi-year expansion |

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 2026Q2 | Q2 guidance and demand-lumpiness check | **TER** | 正面若 lower guide 被證實只是 batch purchase timing；負面若代表需求 peak | Revenue `$1.15B-$1.25B`、non-GAAP EPS `$1.78-$2.07`、bookings、semi test demand commentary | Teradyne official / 大叔文章 |
| 2026H2 | NVIDIA / AMD next-gen AI chip build phase | **TER**, **NVDA**, **AMD** | 正面若 tester waves 延續到 H2 ramp | Tester shipments, foundry / OSAT purchases, customer qualification, HBM / chiplet volumes | 大叔文章 |
| 每季 | HBM / chiplet / SLT test intensity check | **TER**, **MU**, **000660.KS** | 正面若 test time and ASP increase；負面若 HBM capacity overbuild or pricing pressure | Magnum, UltraFLEXplus, test time, tester ASP, SLT revenue, HBM supply / demand | 大叔文章 |
| 每季 | Robotics AI inference optionality check | **TER** | 正面若 robotics recovery plus AI-enabled products create non-semi growth | Universal Robots / MiR revenue, orders, AI inference product roadmap, margin | 大叔文章 |

## 核心框架 / 心法

- **Wafer-to-Data Center / AI 測試保險框架**：AI chip、HBM、chiplet 與 high-speed networking 的價值越高、系統越複雜，客戶越不能接受 failure，測試設備就從生產線成本轉成算力可靠性的保險費。
- **測試時間倍增 / 結構性利潤槓桿框架**：HBM 與 chiplet 讓每顆高價晶片需要更長、更複雜的測試；若 tester ASP / utilization 上升且 opex 增幅有限，增量 revenue 可能以高比例流入 operating profit。
- **設備股波浪式採購框架**：tester demand 不一定按季度平滑釋放，可能在 foundry / OSAT 為 H2 AI chip ramp 一次性採購時形成波峰；單季 guide 需搭配 build phase 和 backlog 解讀。

## 關鍵證據

| 證據 | 出處 | 解讀 |
|---|---|---|
| Q1 2026 revenue `$1.282B`，non-GAAP EPS `$2.56`，non-GAAP GM `60.9%` | Teradyne official results；大叔文章 p.1-p.2 | 財報 beat 支撐 AI test demand 與 operating leverage |
| Semiconductor Test sales `$1.1109B`，佔總 revenue 約 `86.6%` | Teradyne official results；大叔文章 p.2-p.3 | TER 的主 thesis 仍在半導體測試，而非 robotics |
| Q2 revenue guide `$1.15B-$1.25B`、non-GAAP EPS `$1.78-$2.07` | Teradyne official results；大叔文章 Q&A 段 | Q2 低於 Q1 是近期主要爭議點；大叔解讀為 batch purchase / build phase |
| 大叔圖表口徑：2015-Q1 2026 cumulative FCF `$5.6B`，約 97% FCF returned | 大叔文章 p.5 | 支撐 management capital return discipline，但不消除 cyclicality |
| CEO Q&A 提到 R&D 投入處於 "target-rich environment" | 大叔文章 p.5-p.6 | 大叔將其解讀為 AI testing roadmap 仍有大量投資機會 |

## 風險與反例

| 風險 | 相關 ticker | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| Q2 guide 被市場解讀為 demand peak | **TER** | 高 | Q2 revenue / EPS 下滑後，H2 tester demand 未回升 | Q2 actual, Q3 guide, bookings, management commentary | 大叔文章 / Teradyne official |
| AI capex cycle peak | **TER**, **NVDA**, **AMD** | 高 | North America AI capex 2027 前後見頂，customer tester purchases 放緩 | Hyperscaler capex, GPU / ASIC shipment plan, foundry / OSAT order cadence | 大叔 DCF bear case |
| HBM capacity oversupply | **TER**, **MU**, **000660.KS** | 中高 | HBM capacity 快速擴張但 demand 不及預期，memory tester demand 放慢 | HBM pricing, memory capex, tester utilization, Magnum demand | 大叔 DCF bear case |
| Tester ASP / utilization 無法維持 | **TER** | 高 | test time 增加未轉成定價權，或供給跟上壓低設備 ASP | Equipment ASP, GM, semi test backlog, competition | 整理者判斷 / 大叔框架 |
| Robotics recovery 低於預期 | **TER** | 中 | Manufacturing destocking 後需求恢復短暫，AI inference product 化慢 | Robotics revenue, orders, margins, product launches | 大叔文章 |
| 估值壓縮 | **TER** | 高 | `$343` anchor 對 2026 EPS / mid-term EPS 已反映樂觀，若 EPS revision 下修則 multiple 壓縮 | Forward P/E, EPS revisions, GM, FCF, stock reaction | 大叔 valuation 段 |

## 延伸追蹤

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 2026Q2 | Q2 guidance 兌現 | **TER** | 未定 | Revenue、non-GAAP EPS、semi test demand commentary、orders / backlog | Teradyne official / 大叔文章 |
| 2026H2 | AI chip build wave 是否延續 | **TER**, **NVDA**, **AMD** | 正面若 H2 tester wave 明確 | Foundry / OSAT tester purchases, HBM / chiplet capacity, networking processors | 大叔文章 |
| 2026-2027 | Mid-term model validation | **TER** | 正面若 `$6B` revenue / `$9.50-$11.00` EPS 路徑清楚 | Segment revenue, GM >60%, opex discipline, operating margin, FCF | 大叔文章 |
| 每季 | Robotics AI inference roadmap | **TER** | 正面若 robotics orders and AI-enabled functions accelerate | UR / MiR revenue, margins, order intake, product announcements | 大叔文章 |

## 整理者延伸

歷史回查 `TER|Teradyne|泰瑞達|Universal Robots|MiR` 只找到 Bytc 2026-03-17 GTC 2026 文中把 **TER** / Universal Robots 作為 Physical AI / robotics 上市母公司 proxy 的 L1 背景。該筆不是大叔觀點，也沒有形成 **TER** 單股 thesis，因此不回填到 `Stocks/TER/`；本篇是首次把 **TER** 升級成正式追蹤個股。

這篇和大叔先前 **AMKR**、**LRCX**、CPO / 矽光子文章形成同一條 AI hardware chain：**LRCX** 處理前段 process intensity，**AMKR** 處理先進封裝與產能承接，**TER** 則處理 AI chip / HBM / SLT 在 wafer-to-data-center 路徑上的可靠性測試與利潤槓桿。
