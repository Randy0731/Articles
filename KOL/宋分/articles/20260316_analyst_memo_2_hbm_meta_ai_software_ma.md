# 宋分分析師備忘錄 #2：HBM 雙結構、META AI 廣告框架與軟體併購校準

- **KOL**：宋分 / 美股送分題
- **來源**：Substack 文章
- **類型**：Substack 文章 / 分析師備忘錄 / HBM re-rating / **META** AI 廣告變現 / 軟體 SaaS 估值校準
- **發文時間**：2026-03-16 00:30 UTC（台北 08:30；Substack preloads JSON）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://substack.com/home/post/p-190995636
- **source_id**：宋分-20260316-analyst-memo-2-hbm-meta-ai-software-ma-9947773b
- **raw 路徑 / URL**：`KOL/宋分/raw/20260316_宋分_analyst_memo_2_hbm_meta_ai_software_ma_home_宋分-20260316-analyst-memo-2-hbm-meta-ai-software-ma-9947773b.pdf`；`KOL/宋分/raw/20260316_宋分_analyst_memo_2_hbm_meta_ai_software_ma_note_宋分-20260316-analyst-memo-2-hbm-meta-ai-software-ma-9947773b.pdf`
- **OCR 狀態**：部分（Substack preloads 正文完整可讀；使用者提供 4 頁 / 2 頁 Substack 截圖 PDF 為 image-only raw 備份，未 OCR）
- **相關 ticker**：**META** 為本篇主要單股框架；**MU** 為 2026-03-12 記憶體框架的既有 proxy，本篇未直接具名 **MU**；**IBM** 為軟體併購買方語境 L1；**TSM**、**AAPL**、**QCOM**、**2454.TW** 為台積電 iPhone 週期歷史類比；**GOOG** / **GOOGL** 為 Gemini benchmark 對照；**AMZN** 為物流系統類比
- **主題 tags**：#AI基建, #Memory, #ReRating, #軟體SaaS, #估值風險

## 主旨

這篇是《宋分分析師備忘錄 #2》，延續備忘錄系列的讀法：市場很少因為單一新聞改變方向，更多時候是因為開始問不同問題。這次三個新問題分別是：HBM 是否會成為記憶體產業的 iPhone moment / 台積電化轉折、市場是否用錯框架評估 **META** 的 AI 策略、軟體股估值是否可能由私募 / 公開市場併購倍數重新校準。

本篇對 **META** 是明確 L2+ 有效觀點：宋分認為 Meta AI 的核心不是模型 benchmark 競賽，而是廣告推薦、素材生成與投放優化能否提高 ROAS、ARPU 與利潤率。對記憶體則是 2026-03-12 PB / cycle 框架的補充：HBM 可能形成高階子市場，但不等於整個 DRAM / NAND cycle 消失。

## Ticker 分流

| Ticker / 類別 | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **META** | 第二節主角；AI 策略、廣告變現、Avocado 延後與自研模型必要性 | L2+ 有效觀點 / watchlist candidate | 更新 ticker / theme / catalyst / watchlist；不建立 `Stocks/META/` | 宋分明確說市場用錯框架評估 Meta；Meta 的 AI 目標是強化廣告生態、提高 ROAS / ARPU，模型只需夠強、夠便宜、能服務平台，並避免長期被外部模型收「AI 過路費」 |
| **MU** / memory makers | 既有記憶體框架 proxy；本篇未直接具名 **MU** | L2 framework continuation | 更新 theme / framework / catalyst / watchlist；不建立 `Stocks/MU/` | 本篇延伸 2026-03-12 記憶體 PB / Cycle 框架，討論 HBM / eSSD 是否成為高階子市場，以及 HBM PE、傳統 DRAM / NAND PB 的雙結構可能 |
| **IBM** | 軟體併購買方語境 | L1 | ticker index；不更新 `Stocks/IBM/` | 原文只提到 IBM 軟體負責人在 Morgan Stanley 論壇引用市場先生概念，暗示下跌可成為併購機會；沒有形成 **IBM** 新財務 thesis |
| **TSM**, **AAPL**, **QCOM**, **2454.TW** | 台積電 2014-2015 iPhone / Apple A 系列與客戶訂單類比 | L1 | ticker index | 用來類比週期股如何因穩定大客戶與製程領先，從 PB 轉向 PE / structural growth valuation；不是當下單股觀點 |
| **GOOG**, **GOOGL** | Gemini 3.0 / Google 模型作為 Meta Avocado benchmark 對照 | L1 | ticker index | 只是 Meta AI 模型能力的外部 benchmark，未建立 Alphabet 新 thesis |
| **AMZN** | 物流系統類比 | L1 | ticker index | 宋分用 Amazon 物流系統說明 Meta 不必擁有最強模型，但必須掌握可支撐平台的內部 AI 系統；不是 **AMZN** 新觀點 |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker |
|---|---|---|---|---|
| HBM 雙結構 / 記憶體再定價框架 | HBM / eSSD 可能更貼近 CSP CAPEX cycle，消費 DRAM / NAND 仍跟 PC / 手機 cycle；記憶體可能出現高階用 PE、成熟用 PB 的混合估值 | AI memory、HBM、DRAM / NAND、AI server demand、CSP capex | HBM bit shipment share、HBM revenue share、yield、CSP deployment peak、consumer demand、DRAM / NAND pricing、capacity backflow | **MU** proxy；memory makers |
| META AI 廣告飛輪 / 模型自主框架 | 對廣告平台而言，AI 不一定要贏 benchmark；重點是推薦、素材與投放優化能否提升 ROAS、ARPU、margin，且避免依賴外部模型 | 廣告平台、社群平台、自研模型 vs 外部模型、AI capex monetization | ROAS、ARPU、ad load / conversion、engagement、model cost、Avocado / Llama roadmap、外部模型依賴度 | **META** |
| 軟體併購倍數校準框架 | 公開市場 SaaS 缺乏 AI 洗牌後的估值基準時，若私有化 / 收購案仍以高倍數成交，可能成為 public software multiple 的重新校準訊號 | SaaS / software 估值下修、AI 替代疑慮、private equity M&A、strategic M&A | transaction multiple、take-private premium、public SaaS EV/Sales / EV/FCF、buyer commentary、deal financing | software / SaaS；**IBM** 為 acquirer context |

## HBM：高階子市場，還是整個記憶體台積電化

宋分先回應讀者對前一篇記憶體深度文的補充：台積電在 2015 以前曾長期以 PB / 週期股方式定價，轉折來自 2014 年 iPhone 6 與 Apple A 系列處理器大規模轉向台積電，使台積電產能利用率與 FCF / 獲利穩定度改變，市場才逐步從設備價值改看 earnings power。

他把這個歷史問題轉到 HBM：HBM 會不會成為記憶體產業的重新定價轉折點？答案尚未確定，因為 2026 年 HBM 位元出貨量即使翻倍，可能也只佔整體 DRAM 約 20%，但因單價較高，營收可能突破 40%。這表示 HBM 重要，但還不足以直接讓整個記憶體產業去週期化。

本篇新增的判讀是「雙結構」：高階 HBM / eSSD / hybrid bonding HBM 可能跟 CSP CAPEX cycle 走，週期變長、變平滑；成熟 DRAM / NAND 仍跟 PC、手機與消費電子 cycle 走。如果 HBM 因良率提升、CSP 第一階段部署見頂或重複下單被消化，原本被擠壓的產能可能倒灌回傳統 DRAM，壓低價格。

整理者判斷：這段補強 `記憶體 PB / Cycle 三階段框架`，不是推翻。新的問題是：記憶體是否會從單一 PB cycle，變成 HBM 子市場用 PE、傳統 DRAM / NAND 用 PB 的混合估值。

## META：市場可能用錯 AI 框架

宋分認為市場看到 Avocado 延後與 Gemini 3.0 benchmark 落後後，第一反應會是 Meta 又在模型競賽落後；但他和外資機構討論後的結論是：市場正在用錯框架評估 **META**。Meta AI 的商業模式不是賣模型，而是強化廣告生態。

他把 Meta AI 拆成三件事：

| AI 用途 | 對廣告業務的作用 | 財務 read-through |
|---|---|---|
| AI 推薦內容 | 提升用戶停留時間 | 提高可變現 attention |
| AI 生成素材 | 降低廣告製作門檻 | 讓更多廣告主投放 |
| AI 優化投放 | 提升廣告轉換率 | 提升 ROAS 與 ARPU |

原文提到 Meta 自稱 AI 優化可讓 ROAS 提升約 22%。宋分的重點不是這個數字本身，而是如果廣告更容易製作、效果更好，企業自然會投放更多預算，ARPU、利潤率與估值空間才是應該被追蹤的主線。

因此 Avocado 的任務不是成為全球最強模型，而是證明 Meta 有能力維持平台內部 AI 技術競爭力。只要模型夠好、夠便宜、能服務 IG / Facebook / 廣告 / 演算法，Meta 不必在每個 benchmark 贏過 Google 或 OpenAI；但它必須避免長期依賴外部模型，否則未來會被收取 AI 過路費。

## 軟體：私募併購可能重新校準 public multiple

第三段延續 2026-03-09 備忘錄 #1 的軟體股問題：軟體反彈後又轉弱，代表機構對軟體仍沒有完全恢復信心。這次新增的觀點來自私募市場：私募軟體公司的交易倍數仍維持高位，沒有像公開市場那樣劇烈下修。

宋分認為公開市場現在缺乏 AI 洗牌後 SaaS 應給多少倍數的基準。如果私有化交易或收購案持續以高倍數成交，這會成為軟體產業的重新校準訊號，證明部分軟體業務在公開市場可能被低估。

他提到 IBM 軟體負責人在 Morgan Stanley 論壇引用「市場先生」概念，暗示股價波動或下跌可能給 IBM 進行併購的機會。整理者判斷：這只構成 **IBM** L1 acquirer context，不是新的 **IBM** 單股 thesis；真正要追的是整體 software M&A transaction multiple 是否替 public SaaS 建立新的估值錨。

## 關鍵證據

| 證據 | 來源 | 整理者判斷 |
|---|---|---|
| 讀者把台積電從 PB 轉 PE 的歷史與 HBM 類比 | Substack 正文 | 用於提出 HBM 是否是 memory iPhone moment 的問題，不是定論 |
| 2026 HBM bit shipment 可能約佔 DRAM 20%，但 revenue 可能突破 40% | Substack 正文 | 支持高階子市場重要性上升，也提醒整體 DRAM / NAND 尚未完全 HBM 化 |
| HBM 生產消耗更多 DRAM 產能，推升傳統 DRAM 價格 | Substack 正文 | 這可能是全面復甦，也可能只是產能推擠；需追 yield / capacity backflow |
| Meta AI 主要服務推薦、素材生成、投放優化 | Substack 正文 | 支持 **META** AI 應用應用廣告變現而不是模型榜單 |
| AI 優化可讓 ROAS 約 +22% | Substack 正文 | 是 Meta AI 廣告飛輪的重要觀察點，但需用公司 filings / call 後續校準 |
| 私募軟體交易倍數仍高 | Substack 正文 | 可能成為 public software multiple 校準基準，但需看實際 deal frequency、premium 與 financing |

## 風險與反例

| 風險 | 相關 ticker / 類別 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 把 HBM 高階子市場誤讀成整體記憶體去週期化 | **MU** proxy / memory makers | 高 | HBM 強，但 PC / 手機 DRAM / NAND 需求下滑抵消高階需求 | DRAM / NAND pricing、PC / phone demand、HBM revenue mix、inventory | 本文；整理者判斷 |
| HBM yield 改善或 CSP 部署見頂造成產能倒灌 | memory makers | 高 | 生產同樣 HBM 需要較少晶圓，或 CSP 重複下單被消化 | HBM yield、capacity、CSP capex、customer inventory | 本文 |
| Meta 模型能力不足影響產品體驗 | **META** | 高 | Avocado / Llama 明顯落後，使 IG / FB / ads / algorithm 體驗受損 | engagement、ad conversion、model benchmark、user retention | 本文 |
| 外部模型依賴形成 AI 過路費 | **META** | 中高 | Meta 長期使用 Google / OpenAI / Anthropic 等外部模型支撐核心功能 | model opex、API / licensing cost、internal model adoption | 本文；整理者判斷 |
| ROAS / ARPU 提升不足以覆蓋 AI capex | **META** | 高 | AI 造成 compute cost 上升，但廣告轉換與收入未同步改善 | ROAS、ARPU、capex、depreciation、margin | 本文；整理者判斷 |
| 私募高倍數併購無法代表公開市場 | software / SaaS | 中高 | Deal 樣本太少、買方 synergies 特殊、融資條件惡化 | transaction multiple、take-private premium、deal volume、credit spread | 本文；整理者判斷 |

## 延伸追蹤

| 日期 / 項目 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 每季 | HBM 是否真的形成高階子市場，且與傳統 DRAM / NAND 分流 | **MU** proxy / memory makers | 正面若 HBM revenue / margin 持續上升且傳統市場不拖累；負面若產能倒灌壓價 | HBM bit / revenue share、yield、pricing、capacity、consumer DRAM / NAND demand | 本文 |
| 每季 / 財報 | Meta AI 是否轉成廣告 ROAS、ARPU 與 margin 改善 | **META** | 正面若 AI tools 提高 ad conversion 並支撐 ARPU；負面若 capex / depreciation 壓 margin | ROAS、ARPU、ad impressions、conversion、AI capex、operating margin | 本文 |
| 未定 | Avocado / Llama 是否足以維持 Meta 內部模型自主 | **META** | 正面若模型夠用且成本可控；負面若需長期依賴外部模型 | model quality、deployment、external model cost、product integration | 本文 |
| 重大交易後 | 軟體私有化 / 併購倍數是否為 public SaaS 提供新錨 | software / SaaS；**IBM** acquirer context | 正面若高品質 software take-private premium 維持高位；負面若交易倍數同步下修 | EV/Sales、EV/FCF、take-private premium、strategic buyer commentary、financing cost | 本文 |

## 整理者延伸

這篇應放在 2026-03-09 備忘錄 #1 與 2026-03-12 記憶體深度文後面讀。備忘錄 #1 問的是 CSP FCF、軟體信心、AI CAPEX 見頂與 AI 通縮；本篇則把問題推進為 HBM 是否改變 memory valuation map、**META** 是否被錯放進模型競賽框架，以及軟體 multiple 是否可能靠併購交易重新找錨。

查詢 **META** 時，這篇是宋分第一篇較完整的 Meta 單股框架：不是 supplier / customer 背景，而是對 Meta AI monetization 的判讀。查詢 **MU** 或 memory 時，這篇不能寫成宋分對 **MU** 的新目標價或操作觀點，只能寫成 3/12 記憶體 PB / cycle 框架的延伸：HBM 可能讓 cycle 變長、變雙結構，但供給、庫存與傳統需求仍是核心風險。

---
