# AI 記憶體熱潮下，為什麼機構還是只看 PB？

- **KOL**：宋分 / 美股送分題
- **來源**：Substack 文章 + Substack 主文留言補充
- **類型**：Substack 文章 / 市場解碼深度 / AI 記憶體 / PB valuation / cycle framework
- **發文時間**：2026-03-12 05:56 UTC（台北 13:56；Substack preloads JSON）；留言補充 2026-03-12 至 2026-03-15
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://substack.com/home/post/p-190696035；https://openbookandeasypoint.substack.com/p/ai-pb/comment/226683343；https://openbookandeasypoint.substack.com/p/ai-pb/comment/227123438；https://openbookandeasypoint.substack.com/p/ai-pb/comment/227227907；https://openbookandeasypoint.substack.com/p/ai-pb/comment/227587240；https://openbookandeasypoint.substack.com/p/ai-pb/comment/228031717
- **source_id**：宋分-20260312-memory-ai-pb-cycle-framework-861aa7e5；宋分-20260312-memory-cycle-exit-hbm-pe-pb-comments-e13c48d1
- **raw 路徑 / URL**：`KOL/宋分/raw/20260312_宋分_memory_ai_pb_cycle_framework_home_宋分-20260312-memory-ai-pb-cycle-framework-861aa7e5.pdf`；`KOL/宋分/raw/20260312_宋分_memory_ai_pb_cycle_framework_note_宋分-20260312-memory-ai-pb-cycle-framework-861aa7e5.pdf`
- **OCR 狀態**：部分（Substack preloads 正文完整可讀；使用者提供兩份 PDF 為 image-only raw 備份，未 OCR）
- **相關 ticker**：**MU** 為主要框架案例與 watchlist candidate；**005930.KS**、**000660.KS** 為記憶體三大廠 / 供給結構例子；**TSM**、**TXN** 為 PE valuation 對照例子
- **主題 tags**：#AI基建, #Memory, #ReRating, #估值風險, #供應鏈風險

## 主旨

這篇回答一個很容易在 AI 記憶體熱潮中被問錯的問題：如果 HBM、DRAM、NAND 都被 AI 基建拉長需求，記憶體股是不是應該從傳統 PB valuation 變成 PE valuation。

宋分的核心答案是：AI 可能拉長記憶體 cycle，但還沒有證明 cycle 消失。機構仍看 PB，不是因為看不懂 AI，而是因為記憶體是重資本、強週期產業，EPS 在景氣高點會暴衝、在谷底會崩塌，用 PE 反而會在高點看起來便宜、在低點看起來很貴。PB 更直接問的是：市場現在願意為這些晶圓廠、設備與產能支付多少 book value multiple。

本篇將記憶體定價拆成三段：估值擴張、基本面追上估值、估值壓縮。AI / HBM / 長約與預付款可以讓第一段與第二段拉長，但若產能擴張、客戶庫存升高、bit supply 追上 demand，記憶體仍可能回到第三段。宋分明確說本篇不是預測記憶體 cycle 快結束，而是建立週期產業的判讀框架。

## Ticker 分流

| Ticker / 類別 | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **MU** | MU 12M forward PB 20 年圖與三次記憶體 super cycle 案例；目前 AI memory cycle 的主要觀察標的 | L2 framework / watchlist candidate | ticker index + theme index + framework / catalyst / watchlist 更新；不建立 `Stocks/MU/` | 文章用 **MU** 歷史 PB 走勢拆解 PC DRAM、data center DRAM 與 AI memory 三次 cycle，重點是 cycle stage 與 PB multiple，不是買賣建議 |
| **005930.KS**, **000660.KS** | Samsung / SK Hynix 作為 DRAM 三大廠與供給結構例子 | L1 | ticker index | 原文用 Samsung、SK Hynix 與 Micron 說明 2013-2014 後 DRAM 從混亂競爭轉向三大廠 oligopoly；沒有個別財務或估值 thesis |
| **TSM**, **TXN** | 穩定現金流 / 成熟科技與類比半導體可用 PE valuation 的對照例子 | L1 | ticker index | 原文只是用台積電、Texas Instruments 類型公司對照記憶體 earnings volatility；沒有形成個股觀點 |
| 記憶體 / HBM / DRAM / NAND | 產業與框架主體 | 產業框架 | theme / framework / catalyst | 文章核心是 AI memory cycle 判讀，而不是單一公司模型 |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker |
|---|---|---|---|---|
| 記憶體 PB / Cycle 三階段框架 | 記憶體 EPS 太週期，PE 容易在高點看起來便宜、低點看起來貴；PB 更能觀察市場願意為產能與資產付多少倍 | AI memory、HBM、DRAM / NAND、其他資本密集週期產業 | PB、book value、capacity、capex、DRAM / NAND 報價、bit supply、inventory、HBM capacity、AI server demand、股價是否早於需求惡化先反應供給 | **MU**, **005930.KS**, **000660.KS** |
| HBM / 消費記憶體雙結構 re-rating 框架 | HBM 可能因 CSP CAPEX、技術門檻與供給瓶頸取得較長估值週期，但消費 DRAM / NAND 仍受 PC / mobile cycle 牽動；整家公司能否 PE 化取決於 HBM 占比與現金流穩定性 | 投資人想判斷 memory 是否「台積電化」、HBM 是否足以讓整體記憶體廠從 cycle stock 轉成 structural growth 時 | HBM revenue / profit mix、consumer memory capacity shift、CSP CAPEX、PC / mobile demand、capacity allocation、PB range 是否上移 | **MU**, **005930.KS**, **000660.KS** |
| LTA / 預付款不是 cycle 消失框架 | 長約與預付款多半代表下游客戶要保障供應，不代表價格永久上漲；在資本密集產業，需求被確認後常引發供給擴張 | HBM 長約、CSP 鎖單、預付款、capacity reservation | volume commitment、capacity reservation、pricing reset、floor / ceiling、prepayment、supplier capex | **MU** / memory makers |
| 定價三階段的記憶體應用 | 估值先因敘事擴張，基本面再追上估值，最後若供給追上需求則 PB 壓縮 | 判斷 AI memory 是第一段、第二段還是第三段 | long-term assumptions、quotes、EPS revision、PB expansion, customer inventory, good-news reaction | **MU** |

## 為什麼記憶體仍看 PB

宋分先把 PB 定義為股價除以每股淨值，本質上是在問市場願意為公司資產負債表上的資產付多少倍。對記憶體公司來說，這個問題比 PE 更穩，因為生意本身非常重資本：晶圓廠、設備、製程投資、折舊與產能都直接決定供給。

PE 在記憶體上容易失真。景氣高點時，DRAM / NAND 價格上漲，EPS 可能突然暴衝，使 PE 看起來很低；但那常是 cycle peak，而不是便宜。景氣谷底時，EPS 可能歸零或虧損，使 PE 看起來很高或無法計算，但那反而可能接近 cycle bottom。PB 雖然也會波動，但它問的是「市場現在願意為這些產能與資產付多少錢」，更貼近週期產業的定價方式。

宋分用 valuation method 的選擇補強這點：穩定成長、現金流可預測的公司較適合 PE；重資本、盈利劇烈波動、供需一變就出現 EPS 大幅擺動的產業，市場更常看 PB。台積電、德州儀器一類公司可用 PE 對照，但記憶體更像航運、面板、鋼鐵等供給可以擴張的週期產業。

## 三次記憶體 super cycle

| Cycle | 第一段：估值擴張 | 第二段：基本面追上估值 | 第三段：估值壓縮 | 宋分判斷 |
|---|---|---|---|---|
| 2006-2008 PC DRAM | 2005-2006 市場先定價 PC DRAM demand，PB 從約 1x 拉到 1.5-2x | 2006-2007 DRAM 價格與 EPS 上升，但 PB 不再大幅擴張，股價震盪 | 2007-2008 新產能開出、PC demand 放慢、DRAM 價格下跌，PB 回到約 1x 或以下 | 結束原因不是需求完全消失，而是 overexpansion 與需求放慢同時出現 |
| 2017 data center DRAM | 2016 從低谷反彈，cloud server narrative 使 PB 從約 1x 拉到 1.5x 以上 | 2017 DRAM 報價與 earnings 創高，市場進入 earnings catch-up | 2018 cloud customer inventory 升高、bit supply 增加、價格反轉，股價早於 EPS 崩落下跌 | 記憶體股票常在 earnings 最亮時先反應供給壓力 |
| 目前 AI memory cycle | HBM、advanced packaging、CSP 長約與 AI 基建敘事讓市場開始願意付更高 PB | AI server demand、HBM shortage、LTA / 預付款確認需求並推動 earnings | 若 HBM 產能擴張、AI server demand normalizes、客戶庫存累積或軟硬體優化降低 memory intensity，PB 可能壓縮 | AI 可能把 2-3 年 cycle 拉長到 5-7 年，但不代表 cycle 消失 |

宋分也補充 2009 與 2013-2014 的 PB 反彈不是單純 demand cycle。2009 更像 Qimonda 破產、Elpida 重整後的 supply structure cleanup；2013-2014 則是 Micron 收購 Elpida 後，市場重新定價 DRAM 變成 Micron、Samsung、SK Hynix 三大廠的 oligopoly。但即使供給結構改善，2014-2015 仍顯示技術進步與 bit growth 過快會讓 cycle 回來。

## 目前 AI 記憶體有什麼不同

宋分承認這一輪 AI memory cycle 有幾個重要差異：

| 差異 | 為什麼重要 | 為什麼仍不是 PE 化保證 |
|---|---|---|
| HBM 技術門檻更高 | 良率、堆疊、advanced packaging 和客戶認證提高供給難度 | 技術門檻會延長供給反應時間，但高價格仍會刺激資本投入 |
| Advanced packaging capacity constrained | HBM 不只看 wafer，也看封裝與產能分配 | 瓶頸若被投資解開，供給仍可能追上 |
| Cloud companies 簽 long-term agreements | CSP 願意用長約或預付款保障供應，支持 demand visibility | LTA 多半鎖 volume / capacity / pricing mechanism，不等於固定價格或永久高毛利 |
| AI infrastructure cycle 較長 | AI server 建置、模型迭代與 inference deployment 可能延長 memory demand | 若 GPU / compute capex 放慢，memory demand 也難永遠指數成長 |

因此，宋分的結論不是「AI 記憶體不重要」，而是「AI 記憶體可能變成長週期循環股」。市場真正要問的是：目前產業在 cycle 哪一段，以及市場已經為這些產能付了多少 PB。

## LTA 與預付款怎麼讀

宋分特別拆解長約和預付款。下游客戶願意提前鎖供應，通常代表它們害怕拿不到貨，這確實是需求強的訊號。但長約不等於價格永遠上漲，也不等於 cycle 被消滅。

他把 LTA 拆成三個元件：

| 元件 | 代表意思 | 需要避免的誤讀 |
|---|---|---|
| Volume commitment | 客戶承諾一定採購量 | 不是所有量都等於同一價格或同一毛利 |
| Capacity reservation | 供應商為客戶保留產能 | 供應保障不等於股東報酬保證 |
| Pricing mechanism | 可能季度重設、連動指數、設 floor / ceiling | LTA 不等於 fixed price |

預付款與 LTA 常出現在 cycle 中段，而不是一開始。第一段時市場還在懷疑 demand，企業通常不敢過度擴產；等需求爆發、HBM 供應緊張後，客戶才會開始預付、鎖產能、簽長約。這能確認 demand，但在資本密集產業裡，confirmed demand 也會誘發供給擴張，所以它同時是正面訊號與未來供給風險的起點。

## 機構怎麼判斷現在在哪一段

宋分把機構檢查 current cycle stage 的重點拆成三類：

| 檢查項目 | 偏早段 / 中段訊號 | 偏晚段訊號 |
|---|---|---|
| Pricing / 報價 | 記憶體價格連續上漲、報價仍緊 | 漲價持續數季後，市場開始問還能漲多久 |
| Inventory / 庫存 | 下游客戶庫存低，供應緊張 | PC / mobile / CSP 庫存回升，或 CSP pull-in 開始放慢 |
| Capex / 產能 | 廠商仍保守擴產，供給反應慢 | memory makers 大規模 capex、新產能與 bit supply 可能追上 demand |

文章最重要的提醒是：cycle turn often happens before earnings collapse。股價不一定等需求消失才跌，很多時候是市場開始預期供給會增加，PB 就先壓縮。

## 留言補充：cycle 轉折、台積電化與 HBM / 消費記憶體分流

宋分在主文留言區把本篇的應用條件再補清楚：記憶體 cycle 退出訊號不只看當下 demand，而要同時看 price trend、下游客戶庫存與 memory makers CAPEX。股價常在需求尚未消失前先轉弱，因為市場會先反映供給可能增加、庫存可能累積與未來報價可能反轉。

| 留言 | 補充重點 | 對主文的增量 |
|---|---|---|
| `c-226683343` | 判斷 cycle 階段要同看價格趨勢、下游庫存與 memory makers CAPEX；股票常早於需求消失先反應供給 | 補強「第三段估值壓縮」的早期訊號，不把 earnings 還亮眼誤認為 cycle 仍安全 |
| `c-227123438` | 台積電過去也偏 PB，但因護城河與獲利穩定度提高，後來較常被市場用 PE 看；HBM 是否能有類似變化要看貢獻度是否足夠 | 將「記憶體能否 PE 化」改成條件問題，不是直接否定 HBM re-rating |
| `c-227227907` | HBM 與消費記憶體需分開看：HBM 跟 CSP CAPEX，消費 DRAM / NAND 跟 PC / mobile cycle；若消費電子需求弱，仍可能拖累公司整體 | 新增「雙結構」檢查，避免把 HBM tightness 外推成整體記憶體永久成長 |
| `c-227587240` | 半導體整體都有 cycle，但上游如台積電 / 設備因技術與集中度，cycle 更長、獲利更穩 | 將 memory 與半導體上游區分，支撐估值方法差異 |
| `c-228031717` | 上游集中、產品受限時，漲價可推動 revenue / profit expansion；第一輪主角後才思考供應鏈其他受益者 | 補強先看核心瓶頸，再看外溢供應鏈的順序 |

## 關鍵證據

| 證據 | 來源 | 整理者判斷 |
|---|---|---|
| Substack preloads 提供完整正文，兩份使用者 PDF 為 image-only raw 備份 | Substack / 使用者 PDF | 來源內容完整可整理；PDF 未 OCR，但正文已由網頁 preloads 取得 |
| 留言 `c-226683343`、`c-227123438`、`c-227227907`、`c-227587240`、`c-228031717` 均可由公開 comment permalink 追溯 | Substack 主文留言 | 可作本文補充版；內容是框架補強，不是新增 **MU** 買賣觀點 |
| 文章附圖為 `MU PB 20Y.jpg`，以 MU 12M forward PB 作歷史 cycle 案例 | Substack 圖片 / 正文 | **MU** 是本篇主要 ticker 框架案例 |
| 宋分比較 PE 與 PB，說記憶體盈利太週期，PE 容易誤導 | 正文 | 新增「記憶體 PB / Cycle 三階段框架」 |
| 文章整理 2006-2008、2017 與目前 AI memory cycle | 正文 | 本篇是定價三階段框架在記憶體產業的延伸應用 |
| LTA / 預付款被拆成供應保障與 pricing mechanism，不等於固定價格 | 正文 | 補強 2026-03-09 AI CAPEX / memory prepayment 討論，避免把鎖單直接寫成永久需求 |
| 原文明確說不是預測記憶體 cycle 快結束 | 正文 | 入庫時需標為框架文，不可寫成宋分看空 MU 或看空 AI memory |

## 風險與反例

| 風險 | 相關 ticker / 類別 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 把 PB 框架誤讀成看空 AI memory | **MU** / memory makers | 高 | 只看到週期風險，忽略宋分說 AI 可能拉長 cycle | HBM demand、AI server demand、LTA、HBM margin、capacity bottleneck | 正文；整理者判斷 |
| 把 LTA / 預付款誤寫成永久固定價格 | 記憶體 / HBM | 高 | 長約其實採 quarterly reset、index pricing 或 floor / ceiling | LTA pricing terms、ASP、gross margin、cancellation / adjustment terms | 正文 |
| 把 HBM tightness 外推成整體記憶體廠全面 PE 化 | **MU** / memory makers | 高 | HBM 占比不足，或消費 DRAM / NAND 因 PC / mobile cycle 下行拖累整體獲利 | HBM revenue / margin mix、consumer memory demand、capacity shift、CSP CAPEX | 留言 `c-227123438`、`c-227227907` |
| 供給擴張比市場預期更快 | **MU**, **005930.KS**, **000660.KS** | 高 | HBM / DRAM capex 大幅增加，bit supply 超過 demand | memory makers capex、wafer starts、HBM capacity、bit supply growth | 正文 |
| AI server demand normalizes | memory makers / AI supply chain | 高 | GPU capex 放慢、CSP pull-in 降低、AI ROI 壓力升高 | hyperscaler capex、GPU shipment、server build, CSP inventory | 正文；整理者判斷 |
| 客戶庫存累積 | memory makers | 中高 | PC / mobile / CSP 客戶提前拉貨後轉為去庫存 | downstream inventory、bookings、lead time、pricing quotes | 正文 |
| 替代與優化降低 memory intensity | HBM / DRAM | 中 | server memory optimization、software efficiency、hardware architecture changes 降低 unit demand | memory per GPU / server、software optimization、model efficiency | 正文 |

## 延伸追蹤

| 日期 / 項目 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 每季 | AI memory cycle 是否仍處於供不應求 / PB 擴張或 earnings catch-up 階段 | **MU**, **005930.KS**, **000660.KS** | 正面若 HBM demand 續強且供給反應慢；負面若市場開始提前定價供給增加 | PB multiple、DRAM / NAND / HBM pricing、inventory、capex、bit supply、AI server demand | 本篇 |
| 每季 | HBM 是否足以改變整體記憶體廠估值分類 | **MU** / memory makers | 正面若 HBM revenue / profit mix 提升且現金流更穩；負面若消費記憶體 cycle 仍主導整體波動 | HBM mix、consumer DRAM / NAND demand、CSP CAPEX、capacity allocation、PB range | 留言補充 |
| 每季 | HBM capacity expansion 是否讓 supply catch up with demand | **MU** / memory makers | 若 capex 快速轉產能，cycle 可能進入晚段 | HBM capacity、advanced packaging bottleneck、yield、supplier capex | 本篇 |
| 每季 | LTA / 預付款是否轉成可持續 revenue / margin，而非只保供應 | **MU** / memory makers | 正面若 volume、price、margin 同步穩定；負面若價格重設或客戶拉貨放慢 | LTA pricing terms、ASP、gross margin、customer inventory、CSP pull-in | 本篇 |
| 未定 | 市場是否真的把 memory 從短週期股重估為長週期循環股 | **MU** / memory sector | 正面為 PB 區間抬高；負面為高 PB 後壓縮 | PB range、cycle duration、supply discipline、customer demand visibility | 本篇；`indexes/framework_index.md` |

## 整理者延伸

這篇應該接在 2026-03-07「定價階段 / 視野鎖定紀律框架」與 2026-03-09「分析師備忘錄 #1」後面讀。3/7 建立 Multiple Expansion、Earnings Catch-up、Multiple Compression；3/9 提到 memory prepayment 與 AI CAPEX 見頂論矛盾；3/12 進一步說明為什麼即使 AI memory demand 很強，機構仍要用 PB 和 cycle stage 來判斷市場定價。

對 **MU** 查詢時，這篇不是單股估值文，也沒有買點、賣點或目標價。可記為宋分對 memory / HBM 週期估值方法的 L2 框架文：AI 讓 cycle 變長的可能性上升，但只要供給可以擴張、庫存可以累積、價格可以反轉，PB 仍是比 PE 更核心的機構語言。

---
