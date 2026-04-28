# GOOGL 筆記 2026Q1

此檔用於收錄 2026Q1 的一般 **GOOGL** / **GOOG** 筆記。里程碑事件放 `Stocks/GOOGL/milestones/`，長文深度分析放 `Stocks/GOOGL/longform/`。

## 文章索引（按發文時間倒序）

| 發文時間 | 整理日期 | 標題 | source_id | 相關 ticker | 主題 tags | 備註 |
|---|---|---|---|---|---|---|
| 2026-02-14 02:30 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：百年債、Apollo OCS 與 AI 基建公用事業化 | KP_FOMOSoc-20260214-kp-thinking-note-29-alphabet-century-bond-ai-disruption-google-ocs-hbm4-amat-openai-cerebras-msft-asts-cc671a80 | **GOOG**, **GOOGL**, **LITE**, **MU**, **005930.KS**, **000660.KS** | #AI基建 #雲端基建 #Memory #金融流動性 #增發融資 #ReRating #執行風險 | L3；Alphabet century bond / AI capex financing / Google Apollo OCS / TPU v8 HBM rumor calibration |
| 2026-02-07 02:45 UTC | 2026-04-29 | KP / FOMOSoc 對 **GOOGL** 的觀點摘要：AI 沒有殺死搜尋，而是擴張搜尋與商業意圖 | KP_FOMOSoc-20260207-kp-thinking-note-28-amazon-google-amd-nvo-mstr-nvidia-openai-spacex-xai-fe4e3d99 | **GOOG**, **GOOGL**, **AMZN** | #AI基建 #軟體SaaS #財報 #ReRating #競爭風險 #估值風險 | L3；AI Search expansion / ads intent quality / Direct Offers / UCP / capex justification |

---

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：百年債、Apollo OCS 與 AI 基建公用事業化

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第29期_GoogleOCS_HBM4_AMAT_OpenAI_MSFT_ASTS.md`
- **原始來源**：https://www.fomosoc.com/p/hbm4openainvdahbm-kp29
- **source_id**：KP_FOMOSoc-20260214-kp-thinking-note-29-alphabet-century-bond-ai-disruption-google-ocs-hbm4-amat-openai-cerebras-msft-asts-cc671a80
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown）
- **OCR 狀態**：不適用
- **類型**：Substack 公開週報 / Alphabet debt financing / Google Apollo OCS / TPU / HBM
- **發文時間**：2026-02-14 02:30 UTC（台北 10:30）
- **整理日期**：2026-04-29
- **交會等級**：L3
- **事件類型**：Alphabet century bond / AI capex financing / optical circuit switching / HBM architecture calibration
- **主題 / 母題標籤**：#AI基建 #雲端基建 #Memory #金融流動性 #增發融資 #ReRating #執行風險

### 對 **GOOGL** 的影響

KP 將 Alphabet 約 200 億美元多幣種債券、尤其是英鎊百年債，解讀為 Google 把自己定位成「數位公用事業」的資本市場訊號。英國 DB pension / insurance 對超長天期資產有負債匹配需求，50 年期 Gilts 提供定價 anchor，Solvency II 又讓 AA 級長債具資本效率。這讓 Alphabet 能用低於股權的成本替 2026 年 1750-1850 億美元級 AI capex 借到時間。

另一條是 Google Apollo OCS。KP 認為 AI factory 的瓶頸不只在 TPU，而在數萬顆 TPU 如何低功耗、低延遲協同。傳統 switch 需要 O-E-O 轉換，KP 口徑功耗約 3000W；Apollo OCS 用 MEMS 微鏡開全光通道，功耗約 100W，並可透過更換兩端光模組從 800G 升到 1.6T。這補強 **GOOGL** 在 TPU / Cloud AI infrastructure 的 full-stack 差異化。

KP 同時校準「TPU v8 用光取代 HBM」的傳聞：training 端仍需要 HBM 的 10-20ns latency 與高頻寬密度，外部 optical DRAM pool 即使理想情境也可能 300ns+，不適合完全替代 HBM。Samsung HBM4 通過 Google TPU v8 驗證，反而是 Google 仍沿用 HBM 的反證。整理者判定：本篇與第28期 AI Search、以及大叔 2026-02-21 capex / century bond 里程碑互相補強；一邊是收入端 Search cash flow，一邊是資本結構與光互聯效率。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏正面 L3；Alphabet 的資本成本、Search 現金流、TPU / OCS full-stack 共同支撐 AI infrastructure utility thesis |
| **資本結構訊號** | 百年債代表市場願意把 Alphabet 視為長期高信用資產，而不只是高增長科技股 |
| **基建訊號** | Apollo OCS 讓 Google TPU cluster 的互聯 / 功耗 / 延遲有差異化，光互聯是 AI data center 神經系統 |
| **技術校準** | OCS 不等於 training 端捨棄 HBM；更可能是記憶體分層與 inference memory pooling |
| **主要風險** | AI capex / depreciation 吃掉 FCF、OCS 成本 / adoption 不透明、TPU 圍牆花園、HBM 供應與光學供應鏈集中 |

### 價位與催化劑

| 類型 | 內容 | 日期 / 數字 | 來源 | 備註 |
|---|---|---|---|---|
| Debt financing | Alphabet 多幣種債券約 200 億美元，含英鎊百年債 | 2026-02 | KP 文章口徑 | 與大叔 2026-02-21 L4 里程碑呼應 |
| Capex guide | 2026 capex 約 1750-1850 億美元 | 2026 | KP 文章口徑 | 需追折舊 / FCF / revenue absorption |
| Bond demand | 百年英鎊債訂單近 100 億英鎊，KP 稱約 10 倍超額認購 | 2026-02 | KP 文章口徑 | 信用市場對 Alphabet 長期現金流信任票 |
| OCS power | 傳統 switch 約 3000W；OCS 約 100W | 2026 | KP 文章 / TrendForce 口徑 | 需用供應鏈和 Google disclosure 後續校準 |
| Optics demand | Google 可能吃下 600 萬顆以上 800G / 1.6T 光模組 | 2026 | KP 文章 / TrendForce 口徑 | 對 Lumentum / 中際旭創 / 新易盛為 read-through |
| HBM latency | HBM 約 10-20ns；optical memory pool 可能 300ns+ | 技術對照 | KP 文章口徑 | 支撐 training 不會完全捨棄 HBM 的判斷 |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| 百年債變成資本壓力 | 高 | AI revenue / Search / Cloud 無法吸收 capex、depreciation 與利息 | FCF、depreciation、interest expense、bond spread、rating | KP 文章 / 整理者判斷 |
| OCS 效率難轉 revenue | 中高 | 光互聯降低功耗但未帶動 Cloud AI revenue 或 TPU external adoption | TPU utilization、Cloud AI revenue、AI gross margin、OCS deployment | KP 文章 |
| TPU / OCS 圍牆花園 | 中高 | 技術優勢只存在 Google 內部，無法吸引外部 workload | external TPU customers、developer tooling、pricing、PyTorch / TorchTPU adoption | 整理者判斷 |
| HBM 供應 / memory hierarchy 風險 | 中 | Samsung / SK Hynix / MU HBM qualification 或供應價格影響 TPU roadmap | HBM4 qualification、HBM pricing、TPU launch timing | KP 文章 |

### 呼應連結

| 既有篇章 | 關係 |
|---|---|
| `Stocks/GOOGL/milestones/GOOGL_里程碑_20260221_Alphabet資本支出百年債與AI基建護城河.md` | 大叔一週後把 Alphabet capex / century bond 升級為正式追蹤里程碑；KP 第29期提供同主題早期 L3 脈絡 |
| 本檔 KP 2026-02-07 AI Search expansion | 第28期補 Search 現金流與交易閉環，第29期補資本結構與光互聯基建 |
| `Stocks/GOOGL/quarterly/GOOGL_筆記_2025Q4.md` 的 Ironwood / TorchTPU / Intersect Power | 第29期把 TPU / Cloud AI infrastructure 再延伸到 Apollo OCS 與 HBM memory hierarchy |

## KP / FOMOSoc 對 **GOOGL** 的觀點摘要：AI 沒有殺死搜尋，而是擴張搜尋與商業意圖

- **來源 KOL**：KP / FOMOSoc
- **原文主整理**：`KOL/KP_FOMOSoc/weekly/KP_KP思考筆記第28期_AMZN_Google_AMD_NVO_MSTR_NvidiaOpenAI.md`
- **原始來源**：https://www.fomosoc.com/p/kp28
- **source_id**：KP_FOMOSoc-20260207-kp-thinking-note-28-amazon-google-amd-nvo-mstr-nvidia-openai-spacex-xai-fe4e3d99
- **raw 路徑 / URL**：URL（未另存 raw；Jina Reader Markdown）
- **OCR 狀態**：不適用
- **類型**：Substack 公開週報 / Alphabet Q4 2025 / AI Search / AI ads / capex
- **發文時間**：2026-02-07 02:45 UTC（台北 10:45）
- **整理日期**：2026-04-29
- **交會等級**：L3
- **事件類型**：Search revenue reacceleration / AI Mode usage / ads quality / Direct Offers / Universal Commerce Protocol
- **主題 / 母題標籤**：#AI基建 #軟體SaaS #財報 #ReRating #競爭風險 #估值風險

### 對 **GOOGL** 的影響

KP 將 Alphabet Q4 2025 搜尋收入年增 17%、達 631 億美元，解讀為「AI Search 不是搜尋死亡，而是搜尋邊界擴張」。市場原本擔心 AI Overviews / ChatGPT 式答案會讓使用者不再點搜尋與廣告，但 KP 認為 Google 財報顯示相反方向：AI Mode 查詢量翻倍、查詢長度約為傳統搜尋三倍，且近六分之一 AI Mode query 來自語音或圖片，代表 AI 把原本難以輸入、難以表達、難以變現的需求變成新的查詢場景。

商業含義在廣告 quality 與 transaction layer。Gemini 進入 Google 廣告品質系統後，可更精準理解長尾意圖，減少無效廣告，把模糊需求轉成更高 ROI 的廣告匹配。Direct Offers 與 Universal Commerce Protocol 則讓 Google 有機會從「搜尋 / 導流」進入「AI 對話中完成交易」的閉環，對 Amazon 這類商品搜尋入口構成外溢競爭。

整理者判定這是 **GOOGL** L3：它直接補強 Search 現金流在 AI 時代的韌性與再加速可能，也讓 2026 capex 1750-1850 億美元的合理性多一層收入端支撐。但本篇也提高了 capex / depreciation、AI query cost、ad cannibalization、commerce platform regulatory pushback 的追蹤權重。

### 觀點摘要

| 面向 | 內容 |
|---|---|
| **立場** | 偏正面；AI Search 將 Search 從藍色連結擴張成更長、更高意圖、更可交易的互動層 |
| **正面訊號** | Search revenue +17%、AI Mode query doubled、query length 3x、語音 / 圖片入口打開新需求、Gemini 改善 ad matching |
| **商業升級** | Direct Offers / UCP 可能把 Google Search 從導流平台推向交易平台 |
| **資本開支含義** | 若 Search revenue 仍能保持 15%+ 成長且 ad ROI 提升，1750-1850 億美元 capex 可視為規模 / 效率軍備競賽的入場券 |
| **主要風險** | AI query compute cost、capex / depreciation、paid-click cannibalization、commerce transaction regulatory risk、Amazon / OpenAI / Perplexity 競爭 |

### 價位與催化劑

| 類型 | 內容 | 日期 / 數字 | 來源 | 備註 |
|---|---|---|---|---|
| Search revenue | Alphabet Q4 2025 Search revenue 達 631 億美元，年增 17% | 2025Q4 | KP 文章口徑 | 需用 Alphabet official filing / earnings release 後續校準 |
| AI Mode usage | AI Mode 查詢量翻倍，query length 約傳統搜尋 3 倍 | 2025Q4 / 2026Q1 | KP 文章口徑 | 代表 AI 可能創造增量 demand，而非只 cannibalize |
| Multimodal query | 近六分之一 AI Mode query 來自語音或圖片 | 2025Q4 / 2026Q1 | KP 文章口徑 | 新搜尋場景與廣告意圖來源 |
| Capex guide | 2026 capex 約 1750-1850 億美元 | 2026 | KP 文章口徑 | 核心檢查是 Search / Cloud / AI revenue 是否吸收折舊與 compute cost |
| Commerce layer | Direct Offers / Universal Commerce Protocol | 測試中 | KP 文章口徑 | 對 Amazon 商品搜尋 / checkout flow 是競爭 read-through |

### 風險表

| 風險 | 風險等級 | 觸發條件 | 觀察指標 | 出處 |
|---|---|---|---|---|
| AI Search 成本高於 monetization | 高 | AI query 成本 / depreciation 上升，但 ad revenue / conversion 沒有同步增加 | Search revenue、AI ad load、TAC、capex、depreciation、operating margin | KP 文章 / 整理者判斷 |
| Paid clicks 被 AI answer cannibalize | 中高 | 使用者在 AI answer 中取得答案但不進一步交易或點擊 | paid clicks、CPC / CPA、conversion attribution、publisher traffic | KP 文章 / 整理者判斷 |
| Commerce platform 監管 / 商家反彈 | 中高 | Google 從導流變交易平台，引發 antitrust、merchant fee 或平台自我偏好爭議 | Direct Offers rollout、UCP terms、regulatory filings、merchant complaints | 整理者判斷 |
| 過度外推 AI Mode usage | 中 | 查詢量和長度成長無法轉成高毛利 revenue，只增加 compute consumption | AI Mode retention、ad ROI、Search & Other growth、Cloud TPU utilization | KP 文章 / 整理者判斷 |

### 呼應連結

| 既有篇章 | 關係 |
|---|---|
| `KOL/Bytc/articles/20260414_google_search_ai_capex_ad_model.md` | Bytc 後續從 AI Search 成本 / monetization 角度檢查 Google 印鈔機變貴；KP 第28期提供較早的 Search expansion 正面脈絡 |
| `Stocks/GOOGL/milestones/GOOGL_里程碑_20260221_Alphabet資本支出百年債與AI基建護城河.md` | 大叔把 Alphabet capex / century bond 寫成 AI infrastructure utility moat；KP 第28期補上 Search revenue 能否支撐 capex 的 business-side anchor |
| `Stocks/GOOGL/quarterly/GOOGL_筆記_2025Q4.md` | 既有 KP TPU / Cloud / Intersect Power 脈絡偏 infrastructure；本篇直接補 Search 現金流與交易層 |
