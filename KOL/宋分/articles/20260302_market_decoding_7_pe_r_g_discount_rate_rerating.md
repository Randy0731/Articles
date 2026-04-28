# 市場解碼 #7：半導體 20x、SaaS 60x 與 PE 的 r-g 框架

- **KOL**：宋分 / 美股送分題
- **來源**：Substack Note
- **類型**：Substack Note / 純框架文 / PE、折現率、r-g 與 re-rating
- **發文時間**：2026-03-02 06:20 UTC（台北 14:20；Substack JSON-LD）
- **整理日期**：2026-04-28
- **原始檔案 / URL**：https://substack.com/@openbookandeasypoint/note/c-221748725
- **source_id**：宋分-20260302-pe-r-g-discount-rate-multiple-rerating-ad9c7e32
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用（Substack Note JSON-LD 正文可讀）
- **相關 ticker**：無具名 ticker；半導體 / SaaS 僅為產業與商業模式類別
- **主題 tags**：#ReRating, #估值風險, #投資與投機

## 主旨

宋分這篇「市場解碼 #7」延續 DCF、PE target、PEG 與分析師流程系列，拆解 PE 區間到底怎麼來。核心不是「半導體天生就該 20x、SaaS 天生就該 60x」，而是 PE 其實是市場對未來現金流風險與成長的簡化報價。

他的公式是：

```text
PE ≈ 1 / (資本成本 r - 長期成長率 g)
```

因此倍數不是天上掉下來的數字，而是市場在估計 `r - g`。當公司未來現金流波動大、Capex 高、折舊壓力重、景氣循環明顯，市場會要求更高 `r`，PE 自然偏低；當現金流穩定、毛利高、再投資需求低、訂閱收入可預測，市場願意降低 `r`，PE 可能非線性放大。

本文無具名 ticker，不更新 ticker index、watchlist、catalyst 或 `Stocks/`。這是估值框架文，不是買賣建議。

## Ticker 分流

| Ticker / 類別 | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| 無具名 ticker | PE / r-g / discount rate 框架 | 不適用 | 不更新 ticker / watchlist / `Stocks/` | 原文沒有對任何單一公司提出估值、催化劑、風險或操作觀點 |
| 半導體 | 低 PE / 高資本密集案例 | 類別語境 | theme / framework | 原文用成熟半導體說明高 Capex、折舊、循環、訂單可預測性低如何推高 r、壓低 PE |
| SaaS | 高 PE / 低資本密集案例 | 類別語境 | theme / framework | 原文用 SaaS 說明高毛利、訂閱制、留存率與低邊際成本如何降低 r、放大 PE |

## 框架摘要表

| 框架 | 核心邏輯 | 適用情境 | 觀察指標 | 相關 ticker |
|---|---|---|---|---|
| PE 倍數 r-g / 折現率重估框架 | PE 約等於 `1 / (r - g)`；高 PE 不一定貴，低 PE 不一定便宜，重點是市場認為風險補償與長期成長差距多大 | 判斷半導體、SaaS、成長股、循環股、re-rating / de-rating、DCF 與 PE target 差異 | cost of capital r、long-term growth g、risk premium、cash flow quality、Capex intensity、cyclicality、FCF、gross margin、retention、reinvestment need | 無具名 ticker |
| 現金機器 vs 資本消耗機 | 機構先看公司若資本市場關閉是否能活下來；現金流越自給自足、r 越低，倍數越容易擴張 | 高 Capex / 週期公司 vs 高毛利訂閱公司、成長股 DCF 安全檢查 | FCF、Capex、depreciation、external financing need、gross margin、subscription revenue、retention | 半導體 / SaaS 類別 |
| 分類改變造成 re-rating | 機構不是只調 EPS，而是判斷市場三年後會把公司歸在哪一類；若從一次性循環變成結構性滲透，g 被拉長且 r-g 縮小，multiple 會重寫 | 成長股主升段、產業滲透率提升、商業模式轉折、market category change | structural vs cyclical growth、penetration rate、growth duration、risk premium compression、multiple expansion | 全市場 |

## 宋分框架拆解

### PE 是 r-g 的倒數

**核心邏輯**：宋分把 PE 還原成股利折現模型 / Gordon growth model 的簡化語言。若成熟半導體長期成長 6%、市場要求報酬 11%，`r - g = 5%`，`1 / 5% = 20x`。若優質 SaaS 成熟後長期成長 5%、資本成本 7%，`r - g = 2%`，`1 / 2% = 50x`。

**短引文**：
> 宋分（2026-03-02）：「PE 高 ≠ 貴」

**整理者判斷**：這篇補強 2026-02-24 的 DCF / PE target 框架。前文說 DCF 是今日收購價，PE target 是未來轉售價；本篇進一步說 PE target 其實是在預測市場未來願意給的 `r - g`。

### 半導體為什麼常見 18-25x

**核心邏輯**：宋分把半導體拆成「資本密集型製造業」而非單純科技股。高 Capex、折舊壓力、景氣循環、訂單可預測性低，都使未來現金流波動大；市場因此提高折現率 / 風險補償。若長期成長約 5-8%、資本成本約 10-13%，`r - g` 落在 4-7%，PE 大約落在 14-25x，成熟半導體 18-25x 不是慣例，而是由成長與風險差距推導。

**觀察指標**：Capex intensity、折舊、cycle amplitude、order visibility、FCF during downturn、external financing need、long-term growth、risk premium。

### SaaS 為什麼可以 40-60x

**核心邏輯**：SaaS 的高 PE 不是只因為近年成長高，而是市場相信成熟後現金流仍穩定、再投資需求低、風險低。若成熟後 long-term growth 5%、cost of capital 6.5-7%，`r - g` 只有 1.5-2%，PE 會放大到 50-66x。

**整理者判斷**：本篇用 SaaS 作現金流品質 / 低再投資需求案例，不等於對所有 SaaS 公司給高 PE 的正當化。若留存率下降、CAC 回收變差、growth duration 縮短或競爭加劇，`r` 會上升、`g` 會下降，multiple 也會快速收縮。

### 主升段不是 EPS 爆發，而是 r 被下修

**核心邏輯**：宋分認為機構真正押注的是 risk premium 下降。當市場從懷疑轉向相信，`r` 只要下修 1%，`r - g` gap 就可能非線性縮小，PE 可能從 20x 跳到 35x 或更高。這就是 re-rating 的數學來源。

**短引文**：
> 宋分（2026-03-02）：「本益比是市場對風險的利率報價。」

**整理者判斷**：這段與確定性提升 / 市場信任建立框架直接相接：股價大幅波動不一定是 EPS 瞬間變好或變壞，而是市場對未來風險與可持續成長的「利率」改變。

## 關鍵證據

| 證據 | 來源 | 整理者判斷 |
|---|---|---|
| 原文用 `PE ≈ 1 / (r - g)` 解釋 18-25x 與 40-60x | Substack Note / JSON-LD | 新增 PE 倍數 r-g 框架 |
| 半導體被定義為資本密集型製造業，具高 Capex、折舊、循環與低訂單可預測性 | Substack Note / JSON-LD | 解釋為何市場對半導體收高風險補償 |
| SaaS 被定義為高毛利、訂閱制、留存高、低邊際成本與低再投資需求 | Substack Note / JSON-LD | 解釋為何市場願意降低折現率並給高 PE |
| 原文列出 gap 5% -> 20x、4% -> 25x、3% -> 33x、2% -> 50x、1.5% -> 66x | Substack Note / JSON-LD | 說明 PE 是倒數，r-g 差距小變動會非線性放大 multiple |
| 原文將機構問題改寫成「這家公司在我的模型裡 r-g 是多少」 | Substack Note / JSON-LD | 補強分析師流程：不要只問合理 PE 幾倍 |
| 原文連回 DCF / PE target：DCF 是今日收購價，PE target 是一年後市場願意給的新 r-g | Substack Note / JSON-LD | 補強既有 DCF 收購價值 / PE 轉售市場 re-rating 框架 |

## 風險與反例

| 風險 | 相關類別 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|---|
| 高 PE 被誤認為一定合理 | SaaS / 成長股 | 高 | 市場以低 r 定價，但 cash flow quality、retention 或 growth duration 轉弱 | retention, net revenue retention, CAC payback, FCF margin, competition | 整理者判斷 |
| 低 PE 被誤認為一定便宜 | 半導體 / 循環股 | 高 | 低 PE 反映高 r、低 g 或高 cyclicality，而不是錯殺 | cycle position, Capex, order visibility, FCF, inventory | Substack Note |
| 公式被機械套用 | 全市場 | 中高 | 用單一 long-term g / r 直接算 PE，忽略分階段成長與 terminal assumptions | stage growth, terminal growth, risk premium, WACC, scenario analysis | Substack Note；整理者判斷 |
| 類別錯判造成 multiple 重寫方向錯誤 | 全市場 | 高 | 把一次性景氣循環誤判為結構性滲透率提升，或把 structural growth 誤判為 cycle peak | market category, penetration, recurring revenue, margin durability | Substack Note |
| DCF 與 PE target 被混為同一件事 | 全市場 | 中高 | 忽略 DCF 是今日保守 intrinsic value，PE target 是預測未來市場願意給的新 r-g | discount rate, growth assumption, time point, exit multiple | Substack Note |

## 延伸追蹤

| 項目 | 影響方向 | 追蹤重點 | 出處 |
|---|---|---|---|
| 與 #5 DCF / PE target 框架串接 | 補強既有框架 | DCF 是今日收購價 / downside protection；PE target 是未來市場願意給的折現率與交易價 | `KOL/宋分/articles/20260224_dcf_pe_target_rerating_resale_market.md`；本篇 |
| 與 #3 PEG 框架串接 | 補強既有框架 | 成長是一次性還是結構性，會影響 `g` 是否被市場拉長 | `KOL/宋分/articles/20260219_peg_market_decoding_growth_mispricing.md`；本篇 |
| 後續若套到具名公司 | 另行 ticker 分流 | 若宋分把 r-g / discount rate 框架套到具名 ticker，需重新判斷 L1-L4；本篇不提前映射任何 ticker | 本篇整理 |

## 整理者延伸

這篇是宋分「市場解碼」系列中最直接把 PE 和 DCF 數學接上的一篇。查詢宋分估值框架時，可以把它放在這條鏈上：Forward PE 看市場預期差，DCF 檢查 downside protection，PEG 看 growth duration 是否被低估，PE target / re-rating 則是在押注市場一年後願意給的 `r - g`。

本篇沒有對半導體或 SaaS 中任何公司給出目標價、買點、賣點或正式觀點。整理時應保留為 framework，不把「半導體 18-25x」或「SaaS 40-60x」機械套用到單一 ticker。

---
