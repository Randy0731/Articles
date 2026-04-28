# 市場解碼 #6：AMD / Meta 6GW 訂單到 EPS Model 分析師流程

- **KOL**：宋分 / 美股送分題
- **來源**：Substack Note
- **類型**：Substack Note / 個股分析師流程 / **AMD** Meta 6GW 訂單到 EPS model
- **發文時間**：2026-02-25 11:14 UTC（台北 19:14；Substack preloads JSON）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://substack.com/@openbookandeasypoint/note/c-219464147；https://ir.amd.com/news-events/press-releases/detail/1279/amd-and-meta-announce-expanded-strategic-partnership-to-deploy-6-gigawatts-of-amd-gpus
- **source_id**：宋分-20260225-amd-meta-6gw-eps-model-process-f913e9c3
- **raw 路徑 / URL**：`KOL/宋分/raw/20260225_宋分_amd_meta_6gw_eps_model_process_宋分-20260225-amd-meta-6gw-eps-model-process-f913e9c3.pdf`；Substack URL；AMD official IR URL
- **OCR 狀態**：部分（Substack preloads JSON 正文可讀；使用者提供之 PDF 為 image-only 截圖 raw 備份）
- **相關 ticker**：**AMD**, **META**；**NVDA**, **AMZN**, **GOOG**, **GOOGL** 僅為競爭 / AI capex 背景語境
- **主題 tags**：#AI基建, #ReRating, #財報, #估值風險, #投資與投機

## 主旨

宋分這篇「市場解碼 #6」把 AMD / Meta 6GW 合作新聞拆成分析師更新模型的流程：先把合作新聞轉成 revenue recognition schedule，再推 net income、diluted EPS，最後才判斷市場願意給多少 PE。核心不是直接喊目標價，而是示範「新聞 -> 營收 -> 淨利 -> EPS -> multiple」如何一步一步變成估值輸入。

這篇對 **AMD** 是 L3 候選追蹤：文章直接討論 Meta 6GW 合作、MI450 / inference、OpenAI + Meta warrants、營收認列、EPS revision 與 PE multiple。由於本專案尚未建立 `Stocks/AMD/`，本次更新 ticker / theme / framework / catalyst / watchlist，不建立正式個股專案。**META** 是具名客戶與 AI capex counterparty，但本文沒有形成 Meta 自身營收、EPS 或估值 thesis，因此只記 L1-L2 customer / capex context。

AMD official IR 用於校準外部事實：AMD / Meta announced up to 6GW AMD Instinct GPU deployment；first 1GW shipments expected to begin in 2H 2026；first deployment uses a custom AMD Instinct GPU based on MI450 architecture；AMD issued Meta a performance-based warrant for up to 160 million AMD common shares. 宋分文中的 `$17.5B/GW`、`$105B`、2026 / 2027 EPS 與 23.5% net margin 都是 KOL model assumptions，不是 AMD official guidance，也不是本專案買賣建議。

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **AMD** | 主角；Meta 6GW 合作、MI450 / inference、warrant dilution、EPS revision | L3 候選追蹤 | ticker index + theme index + framework index + catalyst index + watchlist；不建立 `Stocks/AMD/` | 整篇核心是 **AMD** 的訂單如何被放進 revenue / net income / diluted EPS / multiple model |
| **META** | 具名客戶與 AI capex counterparty | L1-L2 | ticker index；不進 watchlist | 官方合作對 **AMD** 是直接 thesis input；對 **META** 只是 AI infrastructure procurement / compute diversification 背景，本文未做 Meta 財務模型 |
| **NVDA**, **AMZN**, **GOOG**, **GOOGL** | 競爭與 hyperscaler / Anthropic cap table 背景 | L1 | 不另建單股 thesis | 原文用 NVDA / Anthropic / Amazon / Google 說明 early customer lock-in 與推理市場競爭，不是這些公司的新估值觀點 |

## 個股觀點

| 股票代號 | 立場 | re-rating 階段 | 確定性來源 | 下一個催化劑 | 關鍵訊號 / 風險 |
|---|---|---|---|---|---|
| **AMD** | 明確偏多增量；宋分認為 Meta 6GW 合作會迫使 analyst model 更新，但仍需認列、margin 與 dilution 驗證 | 從新聞事件走向 EPS revision，再決定 PE multiple | Meta 6GW partnership、MI450 custom inference GPU、OpenAI + Meta customer lock-in、official warrant milestone structure | 2026H2 first 1GW shipment / revenue recognition、2027-2030 ramp、EPS consensus revision、warrant vesting | order 不等於當年 revenue；revenue / margin / share dilution 皆為假設；growth 由 89% 降到 49% 時 PE 可能壓縮；NVDA competition 與 execution risk |

## 宋分 Model Assumptions

| 步驟 | 宋分假設 / 計算 | 整理者備註 |
|---|---|---|
| Revenue schedule | `1GW = $17.5B` revenue；`6GW = $105B`；五年約；2026 貢獻 `$10.5B`；2027-2030 每年約 `$23.6B` | 這是 KOL conservative assumption；official AMD 未披露總合約金額或 revenue recognition |
| 2026 revenue | Bloomberg consensus `$46.2B` + Meta `$10.5B` = `$56.7B` | consensus 與 add-back 為 KOL model input |
| 2026 net income | net margin `23.5%`，net income 約 `$13.3B` | KOL 假設 Meta custom inference chip 不需大幅調整 margin；需用 AMD gross margin / opex / guidance 驗證 |
| Dilution | AMD 給 OpenAI + Meta `3.2億` warrants；假設 2026 兩方各 deploy 1GW，合計稀釋 53.32M shares；diluted shares 約 1.68B | official AMD Meta warrant 為 up to 160M shares；OpenAI 部分為 KOL 口徑 / 其他背景，需另行校準 |
| 2026 EPS | `$13.3B / 1.68B = $7.9`；原 Bloomberg consensus `$6.65` | 宋分稱這就是 Meta order incremental EPS effect；不是公司 guidance |
| 2027 model | consensus revenue `$64.6B` + Meta `$23.6B` = `$88.2B`；net income `$20.7B`；shares 約 1.76B；EPS `$11.76` vs original consensus `$10.4` | 建立 2027 EPS revision baseline；需追 deployment pace、dilution、margin、customer acceptance |
| Growth / PE | 2025 -> 2026 EPS `4.17 -> 7.9`，YoY +89%；2026 -> 2027 `7.9 -> 11.76`，YoY +49%；growth slows, PE multiple naturally falls | 宋分把 PE multiple 寫成 growth rate 的函數；target price 是最後一步，不是新聞當下直接輸出 |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker |
|---|---|---|---|---|
| 新聞到 EPS model / 訂單認列框架 | 合作新聞要先轉成可認列 revenue schedule，再推 net income、diluted EPS，最後才判斷 PE multiple | AI GPU / accelerator 多年合作、capacity deal、customer warrant、sell-side EPS revision | GW -> revenue conversion、recognition timing、consensus revenue、net margin、warrant dilution、share count、EPS revision、growth rate、target multiple | **AMD**, **META** |
| Warrants as customer lock-in | 對挑戰者而言，performance-based warrants 可提高 customer commitment 與長期合作 certainty，而不只是「缺乏信心」的訊號 | GPU / inference 市場、AI hardware challenger、hyperscaler / AI lab strategic partnership、cap table / compute commitment | deployment milestones、vesting conditions、share dilution、customer adoption、technical milestones、commercial milestones、order certainty | **AMD**, **META**；OpenAI 背景 |
| PE multiple follows growth | EPS model 更新後，multiple 不是固定常數，而會隨 growth rate、market confidence 與競爭風險調整 | 高成長 EPS revision 後的 target price 推導、growth deceleration、re-rating / de-rating | EPS growth, growth duration, PEG, forward PE, consensus revision, margin, competition | **AMD** |

## 宋分框架拆解

### 新聞到 EPS model / 訂單認列框架

**核心邏輯**：宋分把一則合作新聞拆成四層：先決定訂單可否與何時認列為 revenue，再用 margin 推 net income，接著處理 warrant / share count dilution，最後得到 EPS revision。目標價和 PE multiple 是模型完成後的最後一步。

**宋分原話**：
> 宋分（2026-02-25, 《市場解碼 #6》）：「訂單不等於當年營收」

**整理者判斷**：這篇把前面 DCF / PE / PEG / 分析師流程系列落到具名公司 **AMD**。它不是在說「好消息直接等於股價上漲」，而是示範 analyst 如何把好消息變成模型輸入。

### Warrants 作為 customer lock-in

**核心邏輯**：宋分反駁「AMD 發 warrants 代表沒信心」的看法。他用 NVDA / Anthropic / Amazon / Google 的背景說明，早期 AI customer 若被別人用資本與供應鏈綁住，hardware provider 可能錯失長期合作。AMD 在 inference 市場追趕，不該在客戶 lock-in 上太慢；performance-based warrants 更像用股權 upside 換訂單確定性與 roadmap alignment。

**適用情境**：硬體挑戰者需要用 warrant、投資、joint roadmap 或 long-term agreement 綁定 hyperscaler / AI lab，讓未來 deployment 更像可追蹤 milestones，而不是一次性採購新聞。

### PE multiple follows growth

**核心邏輯**：宋分在模型最後提醒，EPS growth 從 2026 的 +89% 放緩到 2027 的 +49% 時，市場自然會下修 PE multiple。也就是 target price 不能只把 EPS 上調後乘上固定倍數；要同時判斷 growth duration 與市場願意給的 multiple。

**觀察指標**：EPS revision、YoY EPS growth、PEG、forward PE、gross / net margin、competition、2027-2030 deployment schedule、customer concentration。

## 關鍵證據

| 證據 | 來源 | 整理者判斷 |
|---|---|---|
| 宋分說市場看到 AMD 拿到 Meta 6GW 合作訂單，而 analyst 會想到 model 要改 | Substack Note / preloads JSON | 明確將新聞事件轉入財務模型，而非只做 headline 解讀 |
| 原文假設 1GW 對 AMD 貢獻 `$17.5B` revenue，6GW 等於 `$105B`，且 2026 只認列 `$10.5B` | Substack Note / preloads JSON | 本文核心是 revenue recognition timing |
| 原文用 23.5% net margin、warrant dilution 與 diluted shares 推 2026 EPS `$7.9` | Substack Note / preloads JSON | 把 order effect 轉成 EPS revision，需與 official data / consensus 後續校準 |
| 原文 2027 model 推 EPS `$11.76` vs Bloomberg consensus `$10.4` | Substack Note / preloads JSON | 形成 2027 follow-up baseline |
| AMD official 確認 Meta partnership up to 6GW、first 1GW shipments expected in 2H26、MI450-based custom GPU、Meta warrant up to 160M shares | AMD official IR, 2026-02-24 | official calibration 支撐事件存在與 milestone structure，但不支撐 KOL revenue / EPS assumptions |
| Substack attachment 指向 2026-02-24 DCF / PE target note | Substack preloads JSON | 該前文已入庫；本文視為估值流程的具名公司應用，不重複整理附件全文 |

## 風險與反例

| 風險 | 相關 ticker | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 訂單不等於當年營收 | **AMD** | 高 | 6GW headline 被市場提前全額資本化，但 shipment / acceptance / revenue recognition 較慢 | official guidance, data center revenue, deferred revenue / backlog commentary, shipment timing | Substack Note；AMD official |
| KOL revenue / EPS 假設不等於 official guidance | **AMD** | 高 | `$17.5B/GW`、23.5% margin、share dilution 或 timing 與實際不符 | AMD filings, earnings call, segment gross margin, opex, diluted shares | 整理者判斷 |
| Warrant dilution 壓縮 EPS | **AMD** | 中高 | Meta / OpenAI milestones 達成但 incremental earnings 不足以抵消 share count 上升 | diluted shares, warrant vesting, EPS bridge, customer deployment pace | Substack Note；AMD official |
| MI450 custom inference execution risk | **AMD**, **META** | 高 | custom MI450-based GPU / Helios / ROCm integration 延後或 performance / supply 不達標 | shipment, technical milestones, ROCm adoption, customer commentary, yield / packaging constraints | AMD official；整理者判斷 |
| PE compression | **AMD** | 中高 | EPS 上修但 growth rate 放緩、market multiple 下修或 competition 加劇 | forward PE, PEG, 2027/2028 EPS growth, NVDA / ASIC competition | Substack Note |
| Customer concentration / strategic lock-in risk | **AMD**, **META** | 中 | 單一 hyperscaler deployment 影響過大，或 warrants 使 upside / dilution highly path dependent | customer mix, deployment milestones, purchase commitments, stock-price thresholds | AMD official；整理者判斷 |

## 延伸追蹤

| 日期 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 2026H2 | Meta first 1GW AMD deployment shipments expected to begin | **AMD**, **META** | 正面若 shipment / revenue recognition 按期，且 margin / dilution bridge 支持 EPS revision | MI450-based custom GPU shipment、Helios rack-scale architecture、data center revenue、gross / net margin、warrant first tranche vesting | AMD official；本篇整理 |
| 2027-2030 | Meta 6GW remaining deployment ramp | **AMD**, **META** | 正面若每年 revenue contribution 接近或高於 KOL model，且 EPS consensus 上修 | annual deployment pace、customer acceptance、revenue recognition、EPS consensus、diluted shares、gross margin | Substack Note；AMD official |
| 每季 | AMD consensus EPS 是否按宋分模型方向上修 | **AMD** | 正面若 2026 / 2027 EPS estimates move toward `$7.9` / `$11.76` with credible margin | Bloomberg / sell-side consensus、AMD guide、warrant dilution、data center revenue | Substack Note |
| 未定 | OpenAI + Meta warrants / customer lock-in 是否提高 inference market certainty | **AMD**, **META** | 正面若 strategic partnership 轉成 multi-year deployment / roadmap alignment；負面若 warrants 只造成 dilution | warrant milestones、customer purchases、technical milestones、ROCm ecosystem、NVDA competitive response | Substack Note；AMD official |

## 整理者延伸

這篇把宋分 2026-02-05 的 **AMD** 估值溫度計往前推了一步：前文重點是財報後估值變便宜、MI450 / data center 節點等待驗證；這篇則把 Meta 6GW 合作放進具體 EPS model，回答「如果 thesis 真的兌現，model 會怎麼改」。後續查 **AMD** 時，應把 2/5 看作估值區間 / 溫度計，把 2/25 看作 revenue recognition + EPS revision 檢查表。

查詢 **META** 時不可把本文寫成宋分對 Meta 的單股 thesis；Meta 在此只是 AMD customer、AI infrastructure demand 與 compute diversification counterparty。

---
