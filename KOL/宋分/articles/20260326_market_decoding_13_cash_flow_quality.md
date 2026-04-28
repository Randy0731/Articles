# 市場解碼 #13：現金流品質、FCF 與 Re-rate

- **KOL**：宋分 / 美股送分題
- **來源**：Substack Note + 留言補充截圖
- **類型**：Substack Note / 市場解碼 #13 / 現金流品質 / FCF / re-rate / CAPEX / RPO
- **發文時間**：2026-03-26 03:20 UTC（台北 11:20；Substack 頁面完整可讀）；留言補充 2026-03-26（使用者截圖顯示 Mar 26；精確時間未確認）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://substack.com/@openbookandeasypoint/note/c-233429761；使用者提供 2026-03-26 留言補充截圖
- **source_id**：宋分-20260326-market-decoding-13-cash-flow-quality-c5ce9f5a
- **raw 路徑 / URL**：URL（未另存 raw；使用者提供留言截圖可完整人工辨識）
- **OCR 狀態**：不適用 / 截圖完整
- **相關 ticker**：**TXN** 為已追蹤個股 L2 框架延伸；CSP / hyperscalers、半導體、IC 設計、製造、EV、太陽能等為產業類別語境，不自動映射為具名 ticker
- **主題 tags**：#ReRating, #估值風險, #AI基建

## 主旨

宋分這篇「市場解碼 #13」把估值焦點從 EPS 拉回現金流品質。他的核心觀點是：EPS 是會計結果，現金流才是公司實際把錢收進來、維持營運、支撐資本支出與回饋股東的能力。機構在判斷公司是否值得更高估值時，不只看公司現在看起來會不會賺錢，而是看現金流是否穩定、可預測、能穿越週期。

這篇也補強 2026-03-24 類比晶片文對 **TXN** 的判斷：宋分先前說 **TXN** 目前主要是 FCF 修復，尚非 AI re-rate；本篇則說明為什麼「現金流從不穩定變可預測」才是 re-rate 的真正起點。若未來類比晶片的需求性質從 cyclical 走向 infrastructure，市場會問的不是單季 EPS，而是未來十年能否穩定收現金。

使用者提供的 2026-03-26 留言補充，則把 FCF 計算拆得更實務：`OCF - SBC - maintenance capex` 與 `OCF - SBC - total CAPEX` 兩種方式都會用，差別在於產業成熟度、資本強度與分析目的。

## Ticker / 類別分流

| Ticker / 類別 | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **TXN** | 3/24 FCF 修復 vs AI re-rate 的後續框架補充 | L2 有效觀點；已追蹤個股 | 更新 `Stocks/TXN/quarterly/TXN_筆記_2026Q1.md`、`Stocks/TXN/TXN_index.md` 與儀表板 | 本篇說明 re-rate 真正看的是現金流可預測性，直接補強 **TXN** 是否從 FCF 修復進入 AI 電力基礎設施重估的檢查條件 |
| CSP / hyperscalers | 負 FCF、CAPEX 與 RPO 的判斷案例 | 類別語境 | theme / framework / catalyst 更新；不映射具名 ticker | 原文討論 CAPEX 上升時要看 RPO / 已簽約未認列收入是否同步上升；沒有在本篇建立 **MSFT**、**AMZN**、**GOOG** 等新單股 thesis |
| 成熟 / 穩定產業 | adjusted FCF 計算情境 | 類別語境 | framework 更新 | 留言補充稱消費、成熟 SaaS、公用事業 / 基礎建設等成長 capex 較少，可先用 `OCF - SBC - maint Capex` 估保守 FCF base |
| 高速成長 / 資本密集產業 | growth capex 與 total capex 敏感度情境 | 類別語境 | framework 更新 | 半導體、IC 設計、製造、CSP、EV、太陽能等需同時看 growth capex 是否創造未來現金回報，以及 total capex 後公司還剩多少自由現金 |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker / 類別 |
|---|---|---|---|---|
| 現金流品質 / FCF Re-rate 框架 | EPS 好不代表公司現金流好；市場願意 re-rate 的起點，是現金流從不穩定、週期性、難預測，變成穩定、可預測、可持續 | 看起來很會賺但股價不漲、CAPEX-heavy 公司、從 cycle 走向 infrastructure 的公司 | OCF、FCF、FCF volatility、multi-year FCF trend、AR、inventory、capex intensity、SBC、cash conversion | **TXN**、CSP、資本密集成長股 |
| OCF / FCF / Adjusted FCF 分流 | OCF 看核心營運造血，FCF 看扣除資本支出後還剩多少可分配現金；留言補充把 SBC 與 maintenance / growth capex 拆開看 | 成熟公司、資本密集公司、需要估算保守 FCF base 或成長投資回報的公司 | `OCF - SBC - maint Capex`、`OCF - SBC - total CAPEX`、maintenance capex、growth capex、management guidance | 消費、SaaS、公用事業、半導體、IC 設計、CSP、EV、太陽能 |
| RPO / CAPEX 負 FCF 判斷 | 負 FCF 不一定可怕；若 CAPEX 上升且 RPO / 訂單能見度同步上升，可能是先燒現金換確定未來收入；若 CAPEX 上升但 RPO 不動，風險較高 | CSP / cloud、AI data center、重資本擴張公司、建置期公司 | CAPEX YoY、RPO YoY、revenue conversion、utilization、depreciation、FCF trough / recovery | CSP / hyperscalers、AI infrastructure |

## EPS vs 現金流：機構真正看的問題

宋分用日常例子說明：損益表顯示賺錢，不代表口袋裡真的有現金。公司可能有應收帳款還沒收回、庫存堆高、預付款或其他營運資金占用；因此 EPS 是帳面結果，現金流才更接近企業真實造血能力。

機構看現金流品質，不是只看某一季數字高低，而是看三件事：

| 問題 | 判斷重點 | 反面風險 |
|---|---|---|
| 現金真的進來了嗎？ | 客戶是否付款、應收帳款是否合理、營運現金流是否跟 EPS 同步 | EPS 好但收不到現金，或收入認列領先現金回收太多 |
| 現金流是否穩定？ | 多季 / 多年 FCF 是否可預測，波動是否下降 | 單季大好但下一季大幅轉負，市場不願提高 multiple |
| 現金流能否支撐營運與成長？ | 扣掉必要 CAPEX 後是否仍能維持公司運作，成長 CAPEX 是否有未來回報 | 現金不足以維持現有業務，或 CAPEX 只是在賭未來需求 |

單季現金流常被付款時間、庫存準備與 CAPEX 節奏扭曲，所以宋分強調要看全年與多年。若某公司四季 FCF 分別是 `+100`、`+120`、`+140`、`+160`，市場通常比 `+200`、`-50`、`+300`、`-100` 更願意給高估值，因為前者更可預測。

## OCF 與 FCF：兩個問題，不同用途

宋分把 OCF 與 FCF 拆成兩層：

| 指標 | 回答的問題 | 解讀 |
|---|---|---|
| OCF | 公司核心業務能不能產生現金？ | 驗證營運健康度與 cash conversion |
| FCF | 扣掉資本支出後，公司還剩多少現金？ | 驗證能否回饋股東、降低負債、或不靠外部融資維持成長 |

因此，`FCF = OCF - CAPEX` 不是單純公式，而是把「營運造血」與「維持 / 擴張所需資本」放在一起看。OCF 高但 FCF 低，可能代表公司很會賺現金，但資本支出太大，現金被建廠、伺服器、設備或基礎設施吃掉；OCF 穩、FCF 高，才更像高品質現金機器。

## 留言補充：Maintenance Capex 與 Growth Capex 怎麼拆

使用者提供的截圖中，讀者問：估 FCF 時是否應從 OCF 扣除 SBC，並把 CAPEX 拆成 growth capex 與 maintenance capex，只扣 maintenance capex？

宋分回覆重點是：兩種方法都會用，取決於分析目的與產業型態。

| 分析目的 | 較適合產業 | 常用算法 | 判斷重點 |
|---|---|---|---|
| 看公司現有業務的核心現金產生能力 | 成熟、資本支出穩定、現金流可預測的產業，例如消費、成熟 SaaS、公用事業 / 基礎建設 | `OCF - SBC - maintenance capex` | growth capex 對當前營運波動較小，先看現有業務穩定產生多少現金；若此數為負，代表連維持既有業務都有壓力 |
| 看公司增長潛力與資本效率 | 高速成長、資本密集、需要大額投資擴張的產業，例如半導體、IC 設計、製造、CSP、EV、太陽能 | `OCF - SBC - total CAPEX` 作最保守 FCF，或只扣 maintenance capex 以保留 growth capex 觀察未來成長需求 | 測試公司投資成長後還剩多少現金；同時用不同成長假設看 FCF 走勢 |

整理者判斷：這段可作後續 CAPEX-heavy 公司模型的實務註記。若公司把 growth capex 說成長期投資，仍需用未來 revenue、gross margin、utilization、RPO / backlog 與 cash conversion 驗證，不可直接把 growth capex 從風險中拿掉。

## RPO / CAPEX：負 FCF 不一定是壞事

本篇對 CSP / AI data center 類公司最重要的判斷，是負 FCF 的原因。宋分提醒，機構不會只問「FCF 是不是負的」，而會問「這個 CAPEX 會不會變成未來現金流」。

| 情境 | 解讀 | 觀察指標 |
|---|---|---|
| CAPEX 上升，RPO / 訂單能見度也上升 | 可能是先建置、後認列收入；負 FCF 可能是成長投資 | RPO YoY、signed commitments、revenue conversion、utilization、gross margin |
| CAPEX 上升，但 RPO 不動或下降 | 可能是在押注未來需求，確定性較低 | CAPEX YoY vs RPO YoY、customer commitments、utilization、cancellation / delay risk |
| CAPEX 下降，FCF 回升 | 可能是 FCF 修復，但不一定是 re-rate | CAPEX 是否只是週期下滑、收入是否更可預測、FCF 是否可持續 |

這與 2026-02-06 **AMZN** CAPEX Cycle 3、2026-03-09 分析師備忘錄 #1 以及 2026-03-24 **TXN** FCF 修復框架相連：重點不是單季 FCF 正負，而是 CAPEX 後面有沒有可驗證的未來現金流。

## 對 TXN 的延伸：FCF 修復只是第一步

宋分在 3/24 類比晶片深度文中已明確說，**TXN** 現階段主要是 FCF 修復：前幾年 12 吋廠 CAPEX 高、自由現金流被壓，現在 CAPEX 降、現金流回來，市場先重新相信公司能吐錢。

3/26 這篇提供了更高一層的原因：真正 re-rate 不是「現金流從負轉正」本身，而是市場相信現金流的性質改變。對 **TXN** 來說，後續要看的不是單季 FCF，而是：

| 問題 | 正面訊號 | 反面訊號 |
|---|---|---|
| 現金流是否更可預測？ | data center / AI 電源需求提高，庫存 cycle 變短變淺 | FCF 回升只來自 CAPEX 暫時下降 |
| CAPEX 降低後是否犧牲長期成長？ | maintenance capex 足以維持營運，growth capex 更聚焦高 ROI 機會 | CAPEX 下修來自需求不足或資本配置保守 |
| 類比需求是否從 cyclical 走向 infrastructure？ | AI PMIC / VRM、data center revenue mix、order visibility 持續改善 | 工業 / 車用 cycle 仍完全主導收入與估值 |

因此，本篇不改變宋分對 **TXN** 的操作建議，因為原文沒有提供買賣點；它補的是檢查清單：要把 **TXN** 從 FCF 修復推進到真正 AI re-rate，需要看到現金流可預測性與需求性質的改變。

## 風險與反例

| 風險 | 相關 ticker / 類別 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| EPS 好但現金流品質差 | 全市場 / 成長股 | 高 | 應收帳款、庫存或預付款占用現金，OCF / FCF 跟不上 EPS | AR、inventory、cash conversion、OCF vs net income | Substack Note |
| 單季現金流被過度解讀 | 全市場 | 中高 | 付款時間、庫存準備或 CAPEX 節奏造成單季波動 | TTM FCF、多年 FCF trend、working capital | Substack Note |
| 負 FCF 被錯誤視為一定利空 | CSP / CAPEX-heavy 公司 | 中高 | 忽略 CAPEX 是否有 RPO / 訂單能見度支撐 | CAPEX YoY、RPO YoY、revenue conversion、utilization | Substack Note |
| growth capex 被過度美化 | 半導體、CSP、EV、太陽能 | 高 | 公司把所有擴張都說成 growth investment，但未來收入 / margin 沒兌現 | growth capex ROI、backlog、gross margin、cash conversion | 留言補充；整理者判斷 |
| **TXN** FCF 修復被誤認為 AI re-rate | **TXN** | 高 | CAPEX 下降讓 FCF 回來，但 data center / AI 電源需求未改變現金流可預測性 | CAPEX、FCF、data center revenue mix、AI PMIC / VRM orders、inventory turnover | 本篇連結 2026-03-24 深度文 |

## 延伸追蹤

| 日期 / 項目 | 事件 | 相關 ticker | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|---|---|
| 每季 | FCF 是否從波動、週期性，轉為可預測現金流 | **TXN**、CAPEX-heavy 公司 | 正面若 FCF volatility 下降且現金流來源更可驗證；負面若只是 CAPEX 暫停或 working capital 偶發改善 | OCF、FCF、TTM FCF、multi-year trend、CAPEX、working capital | 本篇 |
| 每季 | CAPEX 是否有 RPO / 訂單能見度支撐 | CSP / hyperscalers | 正面若 RPO / contracted revenue 與 CAPEX 同步上升；負面若 CAPEX 上升但 RPO 不動 | CAPEX YoY、RPO YoY、utilization、revenue conversion | 本篇 |
| 財報 / 管理層指引後 | Maintenance capex 與 growth capex 分類是否可信 | 成熟公司、資本密集成長股 | 正面若管理層分類有歷史資料與投資回報驗證；負面若分類過度主觀 | maintenance capex、growth capex、SBC、capital allocation、ROI | 2026-03-26 留言補充 |

## 整理者延伸

這篇是宋分市場解碼估值系列裡，連接 DCF / PE / re-rate 與財務三表品質的一篇。查詢「公司 EPS 好為什麼股價不漲」時，本篇要和 2026-03-19 PE 壓縮、2026-03-20 風險重新定價一起讀；查詢 CAPEX-heavy 公司時，則要和 2026-02-06 **AMZN** CAPEX Cycle 3、2026-03-09 CSP FCF 觸底框架一起讀。

對 **TXN** 查詢時，本篇是 2026-03-24 深度文的財務語言補強：**TXN** 不是因為 FCF 回升就自動完成 AI re-rate；真正要追的是現金流可預測性是否因 data center / AI 電源需求而改變。

---
