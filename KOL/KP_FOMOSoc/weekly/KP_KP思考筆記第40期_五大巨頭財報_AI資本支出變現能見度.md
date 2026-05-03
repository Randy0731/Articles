# KP 思考筆記第40期：五大巨頭財報、AI 資本支出與變現能見度

- **來源 KOL**：KP / FOMOSoc
- **原始來源**：https://www.fomosoc.com/p/5-kp40；推廣 Note：https://substack.com/@fomosoc/note/c-252923956
- **source_id**：KP_FOMOSoc-20260502-kp-thinking-note-40-big-tech-earnings-ai-capex-2f19bb36
- **推廣 Note source_id**：KP_FOMOSoc-20260503-kp-thinking-note-40-big-tech-earnings-promo-30ec5489
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown 完整可讀）
- **OCR 狀態**：不適用
- **類型**：Substack 公開電子報 / KP 思考筆記 / 週報 / 五大巨頭財報 / AI capex / hyperscaler
- **發文時間**：主文 2026-05-02 03:06 UTC（台北 11:06）；推廣 Note 2026-05-03 06:20 UTC（台北 14:20）
- **整理日期**：2026-05-03
- **文章完整性檢查**：Jina Reader Markdown 共 782 行；正文開頭明確自稱第 40 期，列出 Meta、Amazon、Microsoft、Google、四大巨頭分歧與 Apple 六個主題，六個主題均完整展開，結尾有宣傳段落與 KP 署名，未偵測核心正文截斷。
- **主題 / 母題標籤**：#財報 #AI基建 #雲端基建 #ReRating #估值風險 #執行風險 #能源電力 #Memory

## 一句話結論

KP 將本輪 big-tech 財報解讀為 AI capex 從「願景敘事」進入「變現能見度比較」階段：市場不再同等獎勵所有 AI 投資，而是用 backlog / RPO、外部 revenue line、cloud growth、AI product paid usage、margin 與 FCF 來區分 Google、Amazon、Microsoft、Meta 與 Apple 的資本支出品質。

## 相關 ticker 與交會等級

| Ticker | 交會等級 | 本文判定 | 同步位置 |
|---|---:|---|---|
| **GOOG**, **GOOGL** | L3 | KP 將 Google 寫成最能回答「AI capex 是否有回收路徑」的 hyperscaler：Cloud +63%、企業 AI、Search engagement、TPU 外售 / 客戶機房部署與大額 backlog 形成較高變現能見度。 | `Stocks/GOOGL/quarterly/GOOGL_筆記_2026Q2.md`；`Stocks/GOOGL/GOOGL_index.md`；`Stocks/GOOGL/GOOGL_儀表板.md` |
| **AMZN** | L3 | AWS +28%、RPO / backlog 擴張、Trainium / Graviton / Nitro、OpenAI / Anthropic / Meta workload 與 2027-2028 capacity path，延續 KP 對 AWS AI capex receipt 的 tracked-stock thesis。 | `Stocks/AMZN/quarterly/AMZN_筆記_2026Q2.md`；`Stocks/AMZN/AMZN_index.md`；`Stocks/AMZN/AMZN_儀表板.md` |
| **MSFT** | L3 watchlist | KP 將 Microsoft 寫成從 OpenAI proxy 轉向 enterprise AI platform / Copilot / usage-pricing 的公司；方向清楚，但 margin、FCF 與增量 monetization 還在驗證期。 | `indexes/ticker_index.md`；`indexes/watchlist_index.md` |
| **META** | L3 watchlist | Meta ad engine / Lattice / GEM / Reels / AI ad conversion 數字強，但 2026 capex `$125B-$145B` 與 AI 產品變現不透明，成為「內部最佳化 vs 外部 revenue」的反例。 | `indexes/ticker_index.md`；`indexes/watchlist_index.md` |
| **AAPL** | L3 watchlist | Apple Q1 / March-quarter 數字強、Services 與 China 支撐，但 memory / component cost、AI 策略、WWDC 與 Tim Cook 交棒成為下一階段驗證點。 | `indexes/ticker_index.md`；`indexes/watchlist_index.md`；`indexes/catalyst_index.md` |
| **NVDA** | L1-L2 | 本文只作 TPU / Trainium / custom silicon competition context；不得寫成 KP 對 **NVDA** 的新獨立 thesis break。 | `indexes/ticker_index.md` |

## 核心框架：AI 資本支出變現能見度

KP 的橫向比較不是「誰 capex 最大」，而是「誰能把 capex 變成外部可觀測的收入、使用量、backlog 或 margin」。同樣是幾千億美元級 AI buildout，市場給 Google 較高分，是因為 Cloud growth、TPU 直接銷售、企業客戶、Search usage 與 backlog 指向更明確的回收路徑；Meta 被懲罰，是因為 AI capex 多數仍在內部 ad ranking / personalization / assistant 中運作，缺少獨立收入線。

| 公司 | KP 的本文定位 | 市場正在追問 |
|---|---|---|
| Google | full-stack AI platform / TPU + Gemini + Cloud + Search | Cloud +63%、TPU 外部化與 backlog 能否抵銷 2026-2027 capex / depreciation |
| Amazon | AI infrastructure supplier / AWS + Trainium + Graviton + Bedrock | `$364B` backlog、OpenAI / Anthropic / Meta workload 是否轉成 AWS revenue / margin / FCF |
| Microsoft | enterprise AI platform / Copilot + Azure + GitHub + agents | Copilot paid seats、usage pricing 與 AI run-rate 是否足以覆蓋 capex / compute cost |
| Meta | AI-enhanced ads engine / social commerce brain | Lattice / GEM / adaptive ranking 是否能產生可歸因的增量 revenue，而不只是信任 Zuckerberg vision |
| Apple | installed-base + Services cash machine with AI catch-up | AI strategy、memory cost、gross margin 與新 CEO 交棒後 capital allocation 如何展開 |

## Google / Alphabet：AI capex 回收路徑最清楚

KP 對 **GOOGL** 的語氣偏正面。Google Cloud revenue `$20B`、+63%，企業 AI 產品首次成為 cloud growth 的主要驅動；Gemini Enterprise paid MAU +40% q/q，超過 2,800 家企業與 8M paid seats，330 個 cloud customers 過去 12 個月處理超過 1T tokens，35 個客戶達 10T tokens 里程碑。

KP 也把 Search 寫成「AI 沒有殺死搜尋」的延續：Search & other revenue `$60.4B`、+19%，query volume 創高；AI Mode / AI Overviews 被視為增加場景與使用頻率，而不是立即 cannibalize paid clicks。

本文增量在 TPU 外部化。KP 認為 Google 已將最新 TPU 8t / 8i 從內部雲端優勢推向外部客戶與客戶機房部署，讓 TPU 從 cost advantage 變成可能的 independent hardware revenue line，2027 後可能有更明顯收入貢獻。Cloud margin 由 17.8% 升至 32.9%，加上 KP 口徑 backlog 約 `$462B`，使市場更願意接受 2026 capex `$180B-$190B` 與 2027 更高 capex。

**同步判定**：**GOOGL** L3 tracked-stock follow-up。重點不是單季財報 beat，而是 Google 是否用 Search cash flow、Cloud AI revenue、TPU 外部化、backlog 與能源 / memory / interconnect stack，把 AI capex 轉成可衡量的平台經濟。

## Amazon：AWS 重新加速與 Trainium / Graviton 飛輪

KP 將 **AMZN** 寫成「cloud leader 轉向 AI infrastructure supplier」的候選。AWS Q1 revenue `$37.6B`、+28%，創 15 個季度最佳增速，annualized run-rate 約 `$150B`；operating profit `$14.2B`，margin 37.7%。KP 的重點是 AI workload 不是只消耗 GPU，而是帶動 S3、database、networking、security、compute architecture 等 AWS core services，形成 stickiness。

自研晶片段落延續第37期 Jassy shareholder letter thesis：Graviton / Trainium / Nitro 內部晶片業務年化 >`$20B`，q/q +40%，若外部化可能接近 `$50B` run-rate 的假想規模。KP 口徑稱 OpenAI 2027 起在 AWS 啟用約 2GW Trainium capacity，Anthropic current / future Trainium 最高 5GW 並有超過 `$100B` 十年 AWS spend，Meta 也承諾大量 Graviton cores 用於 agent AI CPU workload。此類合約與 workload 細節按 KP 口徑入庫，未外部校準。

KP 口徑 AWS backlog / RPO 從前季 `$244B` 升至 `$364B`，且不含近期 Anthropic >`$100B` deal；他將 2026 約 `$200B` capex 解讀為 2027-2028 revenue assets。核心驗證不是「Amazon 花很多錢」，而是 Trainium performance、RPO conversion、AWS margin、FCF 與自研晶片能否外部化。

**同步判定**：**AMZN** L3 tracked-stock follow-up。這篇強化「capex 有收據」而非純資本黑洞，但風險仍在 customer concentration、contract quality、depreciation、power / supply chain 與 Trainium 是否只是 Nvidia 議價籌碼。

## Microsoft：從 OpenAI 代理到企業 AI 平台

KP 將 **MSFT** 的敘事轉折寫成「不再只是 OpenAI 最大受益人，而是要自己成為 enterprise AI platform」。管理層語言從 software margin 轉向 gigawatts、capacity constraint、GPU deployment time reduced 20% 等物理世界 capacity language。

OpenAI / Microsoft 關係段落需按 KP 口徑處理：KP 稱 2026-04-27 雙方關係調整後，Microsoft 不再支付 revenue share 給 OpenAI，OpenAI 仍向 Microsoft 支付約 20% revenue share 但 capped and decoupled from AGI progress；Microsoft 保有到 2032 的 non-exclusive IP / model rights，而 OpenAI 可把 workload 放到 AWS / Google Cloud。本文不能改寫成官方結論；後續需用正式 filings / announcements 校準。

Copilot 是 KP 給 Microsoft 的主要驗證線：paid seats >20M，q/q +33%；weekly engagement 接近 Outlook；>50,000-seat Copilot customers up 4x；AI annualized revenue run-rate `$37B`、+123%。但 KP 也提醒，Microsoft 必須從 per-seat software 走向 seat + usage / metered pricing，才有機會吸收 AI compute cost。

**同步判定**：**MSFT** L3 watchlist 補強，不建立 `Stocks/MSFT/`。後續追 Copilot paid seats、usage pricing、Azure AI revenue、RPO ex-OpenAI、gross margin、FCF、Maia / internal model deployment 與 OpenAI agreement official terms。

## Meta：廣告引擎很強，但 capex 回收仍像黑箱

KP 對 **META** 的財報解讀是「business performance strong, capex visibility weak」。Meta Q1 revenue growth 33%，ad growth fastest since 2021，ad price +12%，IG Reels watch time +10%、FB video watch time +8%，Meta AI after Muse / Spark 每人 conversations double-digit growth，WhatsApp / Messenger business AI weekly conversations >10M，年初以來 10x。

KP 承認 Meta AI 已在廣告系統內產生效果：Lattice 統一 feed / Reels / Stories 模型，GEM 作為 ad foundation model，adaptive ranking model 只在高轉換機會使用昂貴模型。KP 引用 conversion lift：Lattice / GEM landing-page-view conversion >6%，adaptive ranking 對 FB / IG main placement conversion +1.6%。

問題是 2026 capex guide 升到 `$125B-$145B`，且 memory / compute / data center cost 上行。Meta AI capex 目前主要仍服務 ad optimization、feed / Reels personalization、shopping、assistant 與 internal AI；沒有像 Cloud backlog、TPU external sales、Copilot seats 這樣可直接觀察的獨立收入線。KP 將 Manus 交易被中國政府阻擋 / 逆轉的段落寫成 geopolitical and execution risk，也提醒 Meta AI agent execution layer 可能受外部環境牽制。

**同步判定**：**META** L3 watchlist 補強，不建立 `Stocks/META/`。後續追 AI ad conversion attribution、incremental revenue disclosure、Meta AI / agent paid product、Reality Labs loss、capex / depreciation、memory cost、FCF 與 AI 產品能否走出 ads black box。

## Apple：最好季度之一，但成本與 AI 策略成為大考

KP 將 **AAPL** 財報寫成「數字漂亮，但下一階段問題更硬」。Revenue `$111.2B`、+17%，March-quarter iPhone revenue record，iPhone revenue `$57B`、+22%；Services >`$31B`，gross margin 76.7%；installed base >2.5B active devices；Greater China +28%；EPS +22%；OCF >`$28B`，並宣布 `$100B` buyback、dividend +4%。

本文的 Apple 增量不是單純 beat，而是資本配置與成本壓力。KP 認為 Apple 放棄「net cash neutral」目標，改為獨立評估 cash / debt，代表新 CEO 或下一階段 AI / R&D / acquisition 可以有更大彈性；但同時 memory cost 在 March quarter 已上升，June quarter and beyond 顯著更高，gross margin guide 47.5%-48.5% 低於當前 49.3%，product GM q/q -200 bps。

KP 也記錄 Tim Cook 將於 9 月交棒、John Ternus 接任，並將 WWDC early June 視為 Apple AI strategy 大考。供應限制從 March quarter iPhone / Mac，轉向 Mac mini、Mac Studio、MacBook Neo 等產品，KP 將部分 Mac 設備視為 AI / agent platform 的 early signal。

**同步判定**：**AAPL** L3 watchlist 補強，不建立 `Stocks/AAPL/`。後續追 WWDC AI roadmap、enhanced Siri / Apple Intelligence、gross margin / memory cost、Services growth、China demand、新 CEO capital allocation 與 Mac / device AI upgrade cycle。

## 對已追蹤個股的同步判定

| 已追蹤個股 | 是否同步 | 理由 |
|---|---|---|
| **AMZN** | 是 | 本文直接延續 AWS AI capex / Trainium / Graviton / backlog thesis，屬 L3 tracked-stock follow-up。 |
| **GOOGL** | 是 | 本文直接補強 Cloud AI demand、TPU externalization、Search AI engagement 與 capex / backlog 變現能見度，屬 L3 tracked-stock follow-up。 |
| **SNDK** | 否 | 文中 Apple / Meta / Google 都提到 memory cost / AI memory pressure，但沒有 SanDisk / HBF / NAND 單股 thesis。 |

## 後續追蹤清單

| 主題 | 觀察指標 |
|---|---|
| AI capex prove-it stage | Cloud revenue growth、RPO / backlog conversion、AI revenue run-rate、paid seats、external TPU / Trainium sales、capex、depreciation、FCF、energy / memory cost |
| Google | Google Cloud revenue / margin、TPU 8 external adoption、TPU direct-sale revenue、Search AI Mode monetization、backlog conversion、2027 capex |
| Amazon | AWS +28% 是否延續、RPO / backlog conversion、Trainium utilization、Graviton / Trainium / Nitro revenue、OpenAI / Anthropic workload quality、AWS margin |
| Microsoft | Copilot paid seats、usage-based AI pricing、Azure AI revenue, RPO ex-OpenAI, Maia / internal model deployment, OpenAI agreement official terms |
| Meta | AI ad conversion attribution、incremental ad revenue, Meta AI / agent monetization, Reality Labs loss, memory / compute cost, FCF |
| Apple | WWDC AI roadmap, enhanced Siri, gross margin and memory cost, Services durability, China demand, Tim Cook / John Ternus transition |

## 資料品質與限制

- 本文以 KP / FOMOSoc Substack 主文為 source of truth；推廣 Note 只作補充版 / duplicate_of 主文。
- 文中對 OpenAI / Microsoft / Amazon / Anthropic / Meta 等合約、capacity 與模型細節多屬 KP 口徑，本次未逐項外部校準；後續若進入 `Stocks/` 儀表板，需標「KP 口徑」或等待 official filing / transcript。
- 本文不是買賣建議；所有價位、capex、backlog 與 revenue 數字均作 KOL 觀點整理與後續驗證清單。
