# AI是泡沫？Google Chrome的重要性，國家隊的牌局 - KP思考筆記（第4期）

- **來源**：KP / FOMOSoc Substack
- **原始連結**：https://www.fomosoc.com/p/aigoogle-chrome-kp4
- **發文時間**：2025-08-23 04:05 UTC（台北 12:05）
- **整理日期**：2026-04-29
- **原檔名**：不適用（Substack 公開網頁）
- **source_id**：KP_FOMOSoc-20250823-kp-thinking-note-4-ai-pltr-chrome-intc-81b5dc3d
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用（Substack API `body_html` 完整可讀）
- **文章類型**：週報 / KP 思考筆記
- **相關 ticker**：**PLTR**, **GOOG**, **GOOGL**, **INTC**；**AAPL**, **005930.KS**, **NVDA**, **AMD**, **AVGO**, **TSM** 為客戶 / 競爭 / 供應鏈脈絡
- **主題 tags**：#AI基建 #軟體SaaS #監管審批 #政策風險 #稀釋風險 #ReRating #競爭風險

## 資料完整性

- 來源透過 Substack API post id `171540665` 與 canonical URL 讀取，`audience=everyone`，正文 HTML 可完整解析。
- 正文有開頭、MIT GenAI Divide 主段、Chrome / Google antitrust 主段、Intel 國家隊主段、結尾與 KP 署名，沒有付費牆截斷或缺頁訊號。
- API 的 `wordcount` 明顯低於正文實際長度，本次以 `body_html` 轉文字後逐段檢查，不以 `wordcount` 判定完整度。

## 主旨

KP 本期用三個事件拆同一條 AI / 科技基建主線：MIT 報告說 95% 企業 GenAI 試點未產生可量化財務回報，並不是宣告 AI 無用，而是把市場從「功能展示」逼回「能否嵌入核心流程」；Perplexity 高調喊話收購 Chrome，則凸顯 AI 搜尋時代瀏覽器入口控制權的價值；Intel 則因美國政府可能入股，從一般公司轉為國家戰略資產，但國家隊只買來時間，不買來成功。

## 本期主題索引

| # | 主題 | 核心論點 | 涉及個股 |
|---|---|---|---|
| 1 | MIT GenAI Divide 與 PLTR 反向受益 | 95% AI 試點失敗是市場過濾器，反而凸顯能把模型嵌入業務流程、資料本體與決策系統的公司價值 | **PLTR** |
| 2 | Chrome 入口與 Google 圍城 | Chrome 是 Google 搜尋帝國的入口與護城河；AI 搜尋公司若掌握 browser distribution，可能改寫資訊互動方式 | **GOOG**, **GOOGL** |
| 3 | Intel 國家隊與 Trump Put | 政府入股 / 補助轉股可能降低 Intel 存續風險，但 upside 仍取決於 foundry、18A、外部客戶與管理層執行 | **INTC** |

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **PLTR** | MIT 報告的反向受益者 / 企業 AI 落地平台案例 | L3 watchlist | 更新 ticker index、watchlist；不建立 `Stocks/PLTR/` | KP 將 Palantir 明確寫成能解決 AI 玩具化、場景缺乏與資源錯配的實力玩家，但同時提醒估值即使再跌三成仍不便宜 |
| **GOOG**, **GOOGL** | Chrome / 搜尋入口 / 反壟斷主角 | L3 已追蹤個股 | 更新 ticker index、`Stocks/GOOGL/quarterly/GOOGL_筆記_2025Q3.md`、GOOGL index 與儀表板 | KP 用 Chrome 出售風險、預設搜尋合約與 AI browser distribution，補強 Alphabet antitrust / AI search entry-point risk |
| **INTC** | 美國政府入股 / foundry 國策資產主角 | L3 已追蹤個股 | 更新 ticker index、`Stocks/INTC/quarterly/INTC_筆記_2025Q3.md`、INTC index 與儀表板 | KP 將 Intel 寫成下檔被國策安全網支撐、上檔取決於商業執行的二元公司，對既有 Intel thesis 有明確增量 |
| **AAPL**, **005930.KS** | Google 預設搜尋合約對手方 / 通路背景 | L1 | 更新 ticker index context | 只作 Google antitrust 背景，本文沒有形成 Apple 或 Samsung 單股 thesis |
| **NVDA**, **AMD**, **AVGO**, **TSM** | Intel 設計競爭與製程比較脈絡 | L1 | 更新 ticker index context | KP 只用它們說明 Intel 若分拆設計 / 製造後面臨的競爭與製程壓力，非這些公司的獨立觀點 |

## 各主題展開

### 主題 1：MIT 報告不是 AI 利空，而是企業 AI 落地過濾器

**核心論點**：

KP 引用 MIT `The GenAI Divide` 報告，重點是企業界投入大量資金後，高達 95% 生成式 AI 試點未能產生可量化財務回報。KP 認為市場把它讀成「AI 泡沫」或「AI 無用論」太粗糙，真正問題是企業將通用模型當成玩具，而沒有把 AI 接進核心業務流程。

KP 將失敗原因拆成三類：

- **錯把玩具當工具**：通用聊天模型提升了電郵、簡報等個人效率，但沒有觸及收入、成本、供應鏈、營運效率等能進財報的流程。
- **缺乏業務場景**：通用模型不懂公司內部資料、訂單、客戶、付款、庫存與營運語言，工作流程因此脆弱。
- **資源錯配**：AI 預算過度投向銷售 / 行銷，但報告指出高回報更可能出現在營運效率與供應鏈等後勤自動化。

**KP 觀點**：

這份報告反而凸顯 **PLTR** 的定位。Palantir 不與 OpenAI、Google 或開源模型比模型本身，而是把模型變成能對接企業資料、本體論與業務行動的指揮中心。KP 特別將 Palantir 的 Ontology、AIP、Airbus Skywise 與 Tampa General Hospital 案例作為 AI 能進入營運流程、節省成本或改善結果的例子。

KP 的立場是偏正面但有估值紀律：MIT 報告不是 AI 利空，而是市場過濾器；**PLTR** 可能是能從 AI 浪潮獲益的實力玩家，但估值不便宜，不能寫成無腦買入。

### 主題 2：Chrome 是 Google 搜尋帝國的入口控制權

**核心論點**：

KP 認為 Perplexity 高調喊話收購 Chrome 雖然像公關操作，但它精準戳中 **GOOG** / **GOOGL** 的脆弱點：如果反壟斷程序真的迫使 Google 出售 Chrome，Google 會失去搜尋與資訊入口的重要門戶。

KP 的拆解重點：

- 美國司法部要求出售 Chrome，是因 Google 透過每年高額預設搜尋合約維持搜尋入口優勢。
- KP 口徑稱 Google 控制全球近 90% 線上搜尋，且每年支付高達 `$26B` 以確保預設地位。
- Chrome 不只是瀏覽器，而是搜尋帝國的護城河與入口；KP 稱全球超過六成電腦用戶透過 Chrome 進入網路世界。
- 在 AI 搜尋時代，瀏覽器是將 AI 服務直接推送給數十億用戶的 distribution channel。

**KP 觀點**：

Perplexity 的喊話揭示的是網路入口控制權正在從傳統搜尋結果頁，轉向 AI answer / agent / browser layer。傳統搜尋給連結，AI 搜尋直接給答案；如果 OpenAI、Perplexity 或其他 AI 公司控制 Chrome 類入口，威脅的不只是 Google 搜尋市占，而是下一代人與資訊互動方式的定義權。

KP 也提醒法律戰不會很快結束：Google 會上訴，整體程序可能延續 18-24 個月，最壞甚至拖到 2027 年或更晚。

### 主題 3：Intel 的國家隊 Put 與商業執行問題

**核心論點**：

KP 將 **INTC** 寫成二元公司：未來不是巨大成功，就是極度沉淪。美國政府商討入股後，市場先漲後跌，因投資人擔心補助轉股會稀釋既有股東，未來公司也可能需要增發更多股本來支應資金需求。KP 認為這些擔憂合理，但也反問：是否有更好的選擇？

KP 反對單純分拆 Intel foundry：

- Foundry 才是 Intel 對美國最有戰略價值的部份。
- 若分拆，晶圓廠會失去 Intel 自身這個最穩定的錨定客戶，外部資本更難支撐龐大建廠計畫。
- 設計部門也會失去與自家製造工藝協同的優勢，只能與 **NVDA**, **AMD**, **AVGO** 等設計公司競爭。
- Intel 設計與製造必須互為支撐，而不是簡單切開。

**KP 觀點**：

政府從補貼者轉為股東，等於給 Intel 一張「Trump Put」。KP 認為這降低了 Intel 在未來幾年破產的機率，因為它被重新定義為國家戰略資產。補助轉股也符合交易邏輯：政府不是無償施捨，而是用納稅人的錢支持，並拿到未來 upside 的股權。

但這只鎖住下檔，不保證上檔。政府資金買來的是時間和機會，不是成功。真正 upside 仍取決於 Intel 能否在技術上追上 **TSM**、能否贏得 **NVDA** 等外部大客戶，以及陳立武團隊的執行力。

## 框架沉澱

### 企業 AI 落地 / 場景整合過濾器框架

- **一句話定義**：AI 是否創造投資價值，不看 demo 或模型本身，而看它能否嵌入企業資料、本體論、營運流程與可量化財務結果。
- **適用情境**：enterprise AI software、AI app layer、PLTR / data platform / workflow automation、AI ROI 辯論。
- **觀察指標**：core workflow adoption、ontology / data integration、revenue impact、cost savings、supply-chain automation、gross margin / operating margin、customer expansion、AIP use cases。

### AI 入口控制權 / Browser Distribution Moat 框架

- **一句話定義**：在 AI 搜尋與 agent 時代，瀏覽器不只是網頁工具，而是模型 / 搜尋 / agent 服務的分發入口；誰控制入口，誰就更接近定義資訊互動方式。
- **適用情境**：Google Search antitrust、Chrome remedy、AI browser、Perplexity / OpenAI distribution、default search agreements。
- **觀察指標**：default search agreement terms、Chrome remedy、browser share、AI answer / agent adoption、search query share、TAC、paid clicks、ad load、regulatory timeline。

### 國家隊 Put / 戰略資產下檔鎖定框架

- **一句話定義**：當公司被政府視為國家戰略資產時，政策入股 / 補助可能降低存續與融資風險，但股東 upside 仍取決於商業執行、稀釋成本與資本回報。
- **適用情境**：Intel / domestic semiconductor manufacturing、defense industrial base、critical infrastructure、補助轉股、政府 rescue / stake。
- **觀察指標**：government equity terms、dilution、cash burn、capex funding gap、external customer wins、technology roadmap、gross margin、FCF、policy conditions。

## 風險與備註

- MIT 報告、Google antitrust 進度、Chrome market share、default search payment、Intel 政府入股與補助轉股等細節均為 KP 口徑或其引用資訊，本次未逐項用官方文件校準。
- **PLTR** 判定為 KP 單篇 L3 watchlist，但 KP 明確提醒估值不便宜；不可寫成買點或無腦買入。
- **GOOG** / **GOOGL** 與 **INTC** 因已是正式 `Stocks/` 專案，已做個股萃取；KOL 主整理仍以本檔為 source of truth。
- 本文不是買賣建議。
