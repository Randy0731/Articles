# 宋分分析師底層系統 #2：從營收到 EPS 的營業槓桿 re-rate 框架

- **KOL**：宋分 / 美股送分題
- **來源**：Substack 免費電子報 + 推廣 Note + 延伸 Note / 留言補充 + PDF raw 備份
- **類型**：Substack 文章 / 分析師底層系統 / 損益表 / 營業槓桿 / re-rate
- **發文時間**：電子報 2026-04-14 05:30 UTC（台北 13:30；Substack API / JSON-LD）；推廣 Note 2026-04-14 08:43 UTC；資訊不對稱補充 2026-04-14 16:21 UTC；市場解碼 #17 延伸 Note 2026-04-16 08:37 UTC；未商業化公司補充 2026-04-16 09:25 UTC
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://openbookandeasypoint.substack.com/p/2epsre-rate；https://substack.com/@openbookandeasypoint/note/c-243165675；https://substack.com/profile/291548189-7f8e80a19001/note/c-243356518；https://substack.com/@openbookandeasypoint/note/c-244250577；https://substack.com/profile/291548189-7f8e80a19001/note/c-244260921
- **source_id**：宋分-20260414-analyst-system-2-income-statement-operating-leverage-rerate-429faebd；宋分-20260414-analyst-system-2-operating-leverage-promo-93f619b2；宋分-20260414-information-asymmetry-formal-catalyst-positioning-ebb19533；宋分-20260416-market-decoding-17-good-loss-bad-loss-operating-leverage-bb2725cf；宋分-20260416-pre-commercial-long-term-option-success-probability-5a559dc4
- **raw 路徑 / URL**：`KOL/宋分/raw/20260414_宋分_analyst_system_2_operating_leverage_宋分-20260414-analyst-system-2-income-statement-operating-leverage-rerate-429faebd.pdf`；URL
- **OCR 狀態**：不適用 / 未 OCR（Substack API / JSON-LD 文字完整可讀；使用者提供 9 頁 PDF 作 raw 備份，未另行 OCR）
- **相關 ticker**：無具名 ticker（Aurora Systems 為假設公司；Nvidia 只作供應商舉例）
- **主題 tags**：#財報, #ReRating, #估值風險, #軟體SaaS

## 主旨

宋分在「分析師底層系統 #2」把研究焦點從「營收有沒有成長、EPS 有沒有 beat」改成「營收一路穿過毛利、費用、營業利益到 EPS 的過程中，價值有沒有被放大」。核心判斷是：高品質營收增加、毛利率邊際改善、費用是投資而非失控、營業利益開始因 operating leverage 擴張，才是 re-rate 的財務底層。

2026-04-14 補充把分析師流程延伸到「利多前股價先動」的資訊不對稱問題：若沒有特定財報日、投資者日或正式大節日，股價莫名發動可能代表利多或謠言正在被提前交易，但這部分賭的成分高；除非原本已有基本面 thesis，否則不應只因價格異動追逐消息。2026-04-16 補充再把同一框架延伸成兩個判斷：第一，虧損本身不是問題，要看虧損是在投資未來還是在填過去的洞；第二，還沒商業化的公司不能用一般 EPS / PE 起手，而更像「長期選擇權」，核心變數是市場願意給多少成功機率 `p`。

本文是純框架文，沒有真實單股 thesis、價位、催化劑或買賣建議。Aurora Systems 是教學假設公司；文中 Nvidia 僅用於說明公司可能預付供應商款項鎖產能，不寫成 **NVDA** 單股觀點。

## 補充來源

| source_id | 發文時間 | 類型 | 作用 |
|---|---|---|---|
| 宋分-20260414-analyst-system-2-operating-leverage-promo-93f619b2 | 2026-04-14 08:43 UTC | Substack Note / 推廣 Note | 摘要完整電子報，強調營業槓桿是股價主升段的損益表訊號 |
| 宋分-20260414-information-asymmetry-formal-catalyst-positioning-ebb19533 | 2026-04-14 16:21 UTC | Substack Note Reply / 留言補充 | 補充資訊不對稱與正式催化劑前佈局：無正式事件時的莫名上漲可能是利多或謠言，不應脫離基本面 thesis 追逐 |
| 宋分-20260416-market-decoding-17-good-loss-bad-loss-operating-leverage-bb2725cf | 2026-04-16 08:37 UTC | Substack Note / 市場解碼 #17 | 補強「好虧損 vs 壞虧損」：市場看公司賺錢能力是否變強，不是只看 EPS 是否轉正 |
| 宋分-20260416-pre-commercial-long-term-option-success-probability-5a559dc4 | 2026-04-16 09:25 UTC | Substack Note Reply / 留言補充 | 補充未商業化公司的估值方式：股價近似成功機率 `p` × TAM × 利潤率 × 折現 |

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| 無具名 ticker | 損益表與 operating leverage 教學框架 | 不適用 | 不更新 ticker / watchlist / `Stocks/` | 原文使用 Aurora Systems 作假設案例；Nvidia 只是供應商例子，沒有公司級分析、價位、催化劑或投資立場 |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker |
|---|---|---|---|---|
| 損益表價值放大 / 營業槓桿 Re-rate 框架 | 分析師看損益表不是看單一營收或 EPS，而是看價值是否在 revenue -> gross profit -> Opex -> operating income -> EPS 過程中被放大 | 財報季、成長股、SaaS / AI 新業務、公司從投資期進入利潤釋放期 | revenue mix、gross margin、Opex growth、operating margin、operating leverage、EPS quality、share count | 無具名 ticker |
| 健康投資 vs 惡化分流框架補強 | 費用增加不一定壞；若 R&D / SG&A 帶來高品質成長且毛利不崩，是投資；若費用膨脹但營收 / 毛利不跟，偏 de-rate | Opex 上升、虧損擴大、SBC 增加、公司宣稱投資未來 | R&D productivity、SG&A efficiency、SBC dilution、revenue growth vs Opex growth、gross margin support | 無具名 ticker |
| 資訊不對稱 / 正式催化劑前佈局框架 | 股價在無財報日、無投資者日等正式事件前莫名上漲，可能反映產業資訊不對稱、利多提前交易或謠言；機構通常偏好能寫成報告的大型正式時間點，散戶也應回到既有基本面 thesis，而不是單純追消息 | 利多前股價先動、無明確事件的異常上漲、財報 / 投資者日前佈局、想分辨基本面 thesis 與消息賭局 | event calendar、earnings / investor day、price / volume spike、rumor quality、industry channel check、post-news reaction、fundamental support | 無具名 ticker |
| EPS 品質檢查 | EPS 成長可能來自回購、業外收益、稅率下降或一次性項目；真正要問的是本業盈餘明年是否仍在 | EPS beat 但股價不漲、目標價下修、管理層用 Non-GAAP 強調獲利 | non-operating income、buyback、tax rate、SBC、diluted shares、normalized earnings | 無具名 ticker |
| 未商業化公司 / 長期選擇權成功機率框架 | 對尚未商業化的公司，市場更像在定價成功機率 `p`，而不是用當期 EPS 或 PE；技術、現金與外部背書會改變 `p` | pre-revenue / early commercialization 公司、平台尚未證明、TAM 很大但 EPS 不可用 | probability of success、TAM、profit margin、discount rate、cash runway、technical progress、policy / strategic backing | 無具名 ticker |

## 宋分框架拆解

### 損益表價值放大 / 營業槓桿 Re-rate 框架

**核心邏輯**：宋分把損益表拆成五層：營收、毛利、費用、營業利益、EPS。第一層先問營收成長來自 recurring revenue、SaaS、AI 結構增量，還是低毛利硬體與降價訂單；第二層看毛利率改善是否來自 product mix 與規模經濟；第三層看 Opex 是 R&D / 市場擴張，還是行政膨脹；第四層才看營業利益是否因營收跑快於費用而擴張；第五層再檢查 EPS 是本業產生，還是靠回購、賣資產、稅率或一次性項目做出來。

**整理者判斷**：這篇是 2026-03-31「底層系統 #1」的下一步。#1 教的是先從 10-K / 10-Q 找公司披露與三表矛盾；#2 則把三表中的損益表拆細，判斷找到的變化值不值得 re-rate。換句話說，#1 是「找變化」，#2 是「判斷變化是否會被價值放大」。

### 營業槓桿是主升段的損益表訊號

**核心邏輯**：營業槓桿不是單純高成長，而是營收增速開始高於費用增速。若營收 +20%、費用只 +5%，營業利益可能大幅超過營收成長；若營收 +20%、費用 +25%，公司仍未進入賺錢模式。宋分把這一層視為「商業模式成立」的證據，也是分析師用來找主升段的關鍵。4/16 市場解碼 #17 進一步補充：好的虧損是毛利上升、高品質營收增加、費用投入研發 / 業務，且營收成長速度大於費用成長；壞的虧損則是毛利下降、營收靠降價撐、費用失控且沒有帶動成長。

**整理者判斷**：這也補強 2026-04-13 的「財報季利潤率轉折」框架：EPS beat 只是結果，margin / operating income 開始轉折才是市場可能先 re-rate 的原因。

### 未商業化公司 / 長期選擇權成功機率框架

**核心邏輯**：宋分在 4/16 留言補充中說，還沒商業化的公司有另一種估法，會被當成「長期選擇權」。簡化公式是：股價近似成功機率 `p` × 未來市場規模 `TAM` × 利潤率 × 折現。這裡最大變動因素是成功機率 `p`；若市場原本只給 5% 成功機率，後來因技術突破、政策支持或類似公司成功而提高到 10%，理論價值就可能大幅上修。

**整理者判斷**：這段不是叫投資人買未商業化公司，而是把「EPS 不可用」時市場在定價什麼講清楚。它和本文的損益表框架互補：商業化公司看營收、毛利、費用、營業利益與 EPS 的價值放大；未商業化公司則先看技術進度、現金能不能撐到那一天、外部背書是否提高成功機率。

### 資訊不對稱 / 正式催化劑前佈局框架

**核心邏輯**：宋分在 4/14 留言補充中說，產業資訊不對稱常讓利多消息前已有知情者或產業第一線人士先佈局，這一點連機構也不一定有優勢。如果沒有特定財報日、投資者日或正式時間點，股價突然莫名上漲，後續可能出現利多，也可能只是謠言；等消息浮上檯面後，市場反而未必買單。宋分的機構流程是：對大型正式事件做提前研究與佈局，因為能從產業資訊推估公司可能在大節日宣布什麼，也比較能寫成報告；若不是正式事件，通常不太參與。

**整理者判斷**：這段補強本文「分析師流程」的邊界。它不是鼓勵追逐異動，而是把可研究的催化劑與不可研究的消息賭局分開：若投資人本來就有基本面 thesis，看到股價先動可以小幅調整參與；但當利多出來後股價回檔，仍必須靠原本 thesis 支撐，而不是靠謠言本身。

### EPS 品質與股數稀釋檢查

**核心邏輯**：EPS = 淨利 / 股數，因此 EPS 上升不一定代表公司變強。回購可以縮小分母，賣資產、匯兌、稅率下降可以暫時墊高淨利，SBC 則可能讓 GAAP 難看但更重要的是稀釋股東。宋分提醒，分析師真正會問的是：這個 EPS 明年還在嗎？

**整理者判斷**：這一段可和 2026-03-26 現金流品質文一起使用：EPS 要被 OCF / FCF、share count、SBC 與非經常性損益驗證，否則容易把財務操作誤認為本業 re-rate。

## 關鍵證據

| 證據 | 來源 | 整理者判斷 |
|---|---|---|
| 主文把損益表拆成 revenue -> gross profit -> Opex -> operating income -> EPS | 電子報主文 / 推廣 Note | 形成「損益表價值放大」框架 |
| 主文區分高品質 recurring revenue / SaaS、結構成長 AI 與低品質硬體收入 | 電子報主文 | 營收成長要看來源與可預測性，不是只看總成長率 |
| 主文說毛利率改善需分 product mix / scale economy，不能只看毛利率高低 | 電子報主文 | 毛利是競爭力證據，重點是邊際改善與原因 |
| 主文把 R&D / SG&A / SBC 拆成好費用與壞費用 | 電子報主文 | 費用是資本配置能力的檢查，不是單純成本 |
| 主文將 operating leverage 定義為營收跑快於費用，營業利益進入放大期 | 電子報主文 / 推廣 Note | 這是本文最重要的 re-rate 觸發條件 |
| 主文提醒 EPS 可能由回購、賣資產、稅率下降或股數變化製造 | 電子報主文 | EPS beat 需回到本業盈餘品質與稀釋檢查 |
| 4/14 留言補充說明資訊不對稱下，無正式事件前的莫名上漲可能是利多提前交易，也可能只是謠言 | Substack Note `c-243356518` | 補強「可研究催化劑」與「消息賭局」分流，正式事件較能用分析師報告方式提前佈局 |
| 4/16 市場解碼 #17 將虧損拆成投資未來與填過去的洞 | Substack Note `c-244250577` | 補強「EPS 不是起點，營業利益才是轉折層」 |
| 4/16 留言補充提出未商業化公司的長期選擇權估值 | Substack Note `c-244260921` | 補出非 EPS 公司如何被市場用成功機率 `p` 重新定價 |

## 風險與反例

| 風險 | 相關 ticker | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 把低品質營收誤讀成成長 | 無具名 ticker | 高 | 營收成長來自低毛利硬體、降價訂單或一次性收入 | revenue mix、gross margin、recurring revenue share | 電子報主文 |
| 毛利率改善不可持續 | 無具名 ticker | 中高 | 毛利變化來自一次性成本下降、庫存減損基期扭曲或折舊 / CAPEX 時點 | product mix、COGS notes、inventory write-down、depreciation | 電子報主文 |
| 費用是失控而不是投資 | 無具名 ticker | 高 | Opex / SBC 上升但營收、毛利與新產品驗證沒有跟上 | R&D output、SG&A efficiency、SBC / revenue、share count | 電子報主文 |
| EPS 被財務操作墊高 | 無具名 ticker | 高 | EPS 成長來自回購、賣資產、稅率下降或非經常性收益 | buyback、non-operating income、effective tax rate、diluted shares | 電子報主文 |
| 把虧損一律視為壞消息 | 無具名 ticker | 中高 | 公司還在虧損，但毛利、營收品質與營業槓桿正在改善 | gross margin、revenue quality、Opex growth vs revenue growth、operating loss trend | Substack Note `c-244250577` |
| 把股價莫名上漲誤讀成必然利多 | 無具名 ticker | 高 | 無正式事件、無可寫報告的基本面證據，只因價格異動或謠言追逐 | event calendar、rumor source、post-news reaction、fundamental thesis support、position size | Substack Note `c-243356518` |
| 把長期選擇權當成確定性 EPS 公司 | 無具名 ticker | 高 | 未商業化公司尚無穩定收入或利潤，卻用一般 PE / EPS 直接估值 | cash runway、technical milestones、policy / strategic backing、probability of success | Substack Note `c-244260921`；整理者判斷 |
| 把假設案例映射成真實公司 thesis | Aurora Systems（假設案例） | 中 | 將教學案例或 Nvidia 供應商例子寫成單股觀點 | 是否有真實 ticker、官方 filing、公司級數據 | 整理者判斷 |

## 延伸追蹤

| 項目 | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|
| 後續「分析師底層系統」系列 | 框架延伸 | 是否繼續拆解資產負債表、現金流量表、估值與財報附註 | 電子報 / 推廣 Note |
| 與底層系統 #1 合併使用 | 財報初讀 -> 損益表拆解 | 先找 disclosure / 三表矛盾，再判斷損益表是否出現價值放大 | `20260331_analyst_system_1_10k_10q_research_framework.md` |
| 與現金流品質框架合併使用 | re-rate / de-rate 分流 | EPS / operating income 是否被 OCF / FCF、SBC、share count 與 working capital 支撐 | `20260326_market_decoding_13_cash_flow_quality.md` |
| 與正式催化劑 / 財報前研究合併使用 | 研究型佈局 vs 消息賭局分流 | 是否有財報日、投資者日、產品發表或可驗證產業資訊；若只是異常上漲或謠言，需降低信心並回到基本面 thesis | Substack Note `c-243356518` |
| 未商業化公司成功機率追蹤 | 長期選擇權 re-rate / de-rate | 技術是否推進、現金是否足夠活到商業化、是否有政策或大企業背書 | Substack Note `c-244260921` |

## 整理者延伸

這篇把「財報好」拆成更可檢查的路徑：高品質營收能否穿過毛利與費用，最後變成可持續的營業利益與 EPS。後續查詢宋分對財報季、re-rate、SaaS / AI 新業務或成長股投資期的判斷時，這篇可作為損益表入口；但它本身不提供任何單股買賣建議。

## 修訂紀錄

| 日期 | 類型 | 說明 |
|---|---|---|
| 2026-04-28 | 補充版 | 補入 2026-04-14 資訊不對稱 / 正式催化劑前佈局留言補充 `c-243356518`，並保存使用者提供 9 頁 PDF raw 備份。 |
| 2026-04-28 | 補充版 | 補入 2026-04-16 市場解碼 #17 Note 與未商業化公司留言補充，新增「好虧損 vs 壞虧損」與「長期選擇權成功機率」段落。 |
