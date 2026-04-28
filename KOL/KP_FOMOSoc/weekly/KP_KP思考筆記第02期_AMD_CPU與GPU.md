# 當市場只看GPU，AMD憑什麼值這個價? - KP思考筆記（第2期）

- **來源**：KP / FOMOSoc Substack
- **原始連結**：https://www.fomosoc.com/p/gpuamd-kp2
- **發文時間**：2025-08-09 03:30 UTC（台北 11:30）
- **整理日期**：2026-04-29
- **原檔名**：不適用（Substack 公開網頁）
- **source_id**：KP_FOMOSoc-20250809-kp-thinking-note-2-amd-cpu-gpu-39fb459a
- **raw 路徑 / URL**：URL（未另存 raw）
- **OCR 狀態**：不適用（Substack API `body_html` 完整可讀）
- **文章類型**：週報 / KP 思考筆記
- **相關 ticker**：**AMD**, **NVDA**, **INTC**；**AMZN**, **MSFT**, **GOOG**, **GOOGL** 僅為 hyperscaler 客戶脈絡
- **主題 tags**：#AI基建 #財報 #ReRating #估值風險 #競爭風險

## 資料完整性

- 來源透過 Substack API post id `170419463` 與 canonical URL 讀取，`audience=everyone`，正文 HTML 可完整解析。
- 正文有開頭、CPU / training / inference 框架、AMD CPU 業務拆解、估值情境與結尾署名，沒有付費牆截斷或缺頁訊號。
- API 的 `wordcount` 明顯低於正文實際長度，本次以 `body_html` 轉文字後逐段檢查，不以 `wordcount` 判定完整度。

## 主旨

KP 將本期定位為 AMD 深度報告的「導演剪輯版」。核心不是單純討論 AMD 能否追上 **NVDA** 的 GPU，而是提醒市場低估了 AI 推論場景中 CPU 對 GPU 利用率、延遲與系統效率的影響。對 **AMD** 而言，EPYC server CPU 是穩定的資料中心根基，AI GPU 則是更高 beta 的未來敘事；兩條戰線共同決定 AMD 的估值是否合理。

## 本期主題索引

| # | 主題 | 核心論點 | 涉及個股 |
|---|---|---|---|
| 1 | AI 訓練 vs 推論中的 CPU 角色 | 訓練時 CPU 是資料與任務調度者；推論時 CPU 直接影響 GPU 利用率與延遲，不能只看 GPU 峰值算力 | **AMD**, **NVDA** |
| 2 | AMD EPYC 的沉默主力 | 即使市場只看 Instinct GPU，AMD data center 仍有很大部分收入來自 EPYC；CPU 是研發與 AI 追趕的財務底座 | **AMD**, **INTC** |
| 3 | x86 server CPU 權力轉移 | KP 引用 PassMark 口徑稱 AMD EPYC 在 2025Q2 x86 server CPU 市占達約 `50%`，代表 Intel 長期壟斷被打破 | **AMD**, **INTC** |
| 4 | AMD 估值與市場動能 | KP 用 2026 EPS consensus 約 `$5.45` 建立 base / bull / bear 情境；目前約 `35x` 2026 forward P/E 的合理性取決於 AI 執行是否超預期 | **AMD**, **NVDA** |

## Ticker 分流

| Ticker | 文章角色 | 交會等級 | 動作 | 理由 |
|---|---|---|---|---|
| **AMD** | 主角 / CPU + GPU 雙線 thesis / 估值情境 | L3 | 更新 ticker index、watchlist；不建立 `Stocks/AMD/` | 整篇圍繞 AMD，含 EPYC、Instinct、server CPU 市占、2026 EPS / P/E 情境、bull/base/bear 估值與市場動能 |
| **INTC** | 主要競爭者 / Xeon 壟斷被打破 | L2 | 更新 ticker index；補入 `Stocks/INTC/quarterly/INTC_筆記_2025Q3.md` | KP 明確寫到 EPYC 取得約 `50%` x86 server CPU share，Intel 數十年壟斷告終，對 INTC 為歷史競爭風險 |
| **NVDA** | GPU moat / 估值比較標竿 | L1-L2 | 更新 ticker index | 本文用 **NVDA** 作 AI GPU 領導者與估值比較，未形成新的 NVDA 單股 thesis |
| **AMZN**, **MSFT**, **GOOG**, **GOOGL** | hyperscaler 客戶 / EPYC 採用脈絡 | L1 | 更新 ticker index | 只作雲端客戶採用 EPYC 的背景，不形成這些公司個別觀點 |

## 各主題展開

### 主題 1：AI 推論時代，CPU 不是配角

**核心論點**：

KP 把 AI 訓練比喻成建造機場：GPU 是施工團隊，CPU 是建造總監，負責資料預處理、檢查點與多節點協調。訓練階段最終瓶頸仍常在 GPU，但 CPU 若調度不足，會拖慢整體工程。

推論階段則不同。KP 把 CPU 比喻成繁忙機場的空中交通管制員：每個用戶請求都要被接收、排序、tokenize、batch，再送上 GPU 這條昂貴跑道。若 CPU 反應慢，GPU 會閒置，導致利用率下降與 latency 變差。

**KP 觀點**：

KP 引用 AMD 白皮書口徑，稱單純更換更高頻主機 CPU 可讓推論系統平均延遲降低約 `8%-9%`。這使 AI 推論系統設計不能只堆 GPU，而要看 CPU / GPU / software batching / networking 的整體系統效率。

**涉及個股 / 框架**：

- **AMD**：若 AI 進入推論決勝，EPYC CPU 與 Instinct GPU 的組合價值更容易被市場重新評估。
- **NVDA**：仍是 GPU bottleneck 的核心標竿，但本文重點不是否定 GPU，而是指出 GPU 效率會被 CPU / 系統設計約束。

### 主題 2：AMD 的 CPU 業務是沉默主力

**核心論點**：

KP 認為，市場只盯著 AMD 的 GPU 追趕敘事，會忽略 EPYC server CPU 已是 data center 戰役中的穩定根基。AMD data center segment 同時包含 EPYC CPU 與 Instinct AI GPU，KP 推估 2024 年中 CPU 在 data center revenue 中仍約占 `55%-65%`。

**KP 觀點**：

這讓 AMD 的故事不是單線「GPU 能不能追上 NVIDIA」，而是雙線：

| 戰線 | KP 描述 | 投資含義 |
|---|---|---|
| CPU / EPYC | 相對沉靜但穩固，是 AMD data center 的財務底座 | 提供 revenue / margin / R&D support |
| GPU / Instinct | 高 beta、面向未來，市場關注度最高 | 決定估值溢價與 AI upside |

### 主題 3：AMD vs Intel 的 x86 server CPU 權力轉移

**核心論點**：

KP 將 server CPU 市場描述為約 `$22B` 的長期 Intel 帝國，但格局正在改寫。他引用 PassMark 口徑稱，截至 2025Q2，AMD EPYC 已取得 x86 server CPU 約 `50%` 份額，從 2024 年約 `30%` 附近快速推進到與 Intel 勢均力敵。

**KP 觀點**：

KP 認為 hyperscalers 採用 EPYC 的原因包含：

- 性價比優於同代 Xeon。
- 核心密度更高，適合 AI / cloud-native workload。
- 每瓦性能更好，有助降低資料中心電費與營運成本。

**涉及個股 / 框架**：

- **AMD**：EPYC 市占提升是估值底層支撐，不只是 AI GPU optionality。
- **INTC**：這是歷史 L2 競爭風險；Intel 若要重估，後續必須證明 Xeon roadmap、DCAI revenue、Foundry / 先進封裝與 AI 推論 CPU 復權能抵消 EPYC 壓力。

### 主題 4：AMD 估值與市場動能的博弈

**核心論點**：

KP 不採用被一次性事件扭曲的 trailing P/E，而用 2026 EPS consensus 約 `$5.45` 來建立 forward-looking 情境。

| 情境 | KP 口徑 | 解讀 |
|---|---|---|
| Base case | EPS 約 `$5.45`、`35x` P/E，目標價約 `$191` | 穩健執行產品路線圖，達市場共識 |
| Bull case | AI strategy 超預期，挑戰華爾街高階目標約 `$237` | Instinct / data center share 與市場信心同步上修 |
| Bear case | 競爭加劇或利潤不及預期，股價可能回調至約 `$130` | 市場情緒回到基本面與 multiple 壓縮 |

KP 提醒，目前市場給 AMD 約 `35x` 2026 forward P/E、略高於 **NVDA** 的估值水平，背後隱含 AMD 不只會成功，還可能比市場領導者增長更快。這是當前股價最大爭議點。

**KP 觀點**：

AMD 當下不是嚴重低估的便宜貨，也還未到明顯泡沫；它位在「基本面估值合理性」與「市場強勁動能」之間。KP 最後把決策問題留給讀者：相信 AMD 超預期執行、相信 **NVDA** moat 難以撼動，或認為當下市場動能本身就是最值得追隨的信號。

## 框架沉澱

### AI 推論 CPU / GPU 利用率框架

- **一句話定義**：在 AI 推論系統中，GPU 是昂貴跑道，但 CPU 像塔台，負責請求排序、tokenization、batching 與調度；CPU 太慢會讓 GPU 閒置，拖累 latency 與 ROI。
- **適用情境**：AI inference、enterprise AI deployment、CPU:GPU attach ratio、GPU utilization、server architecture、AI data center TCO。
- **觀察指標**：inference latency、GPU utilization、batching efficiency、CPU frequency / cores、CPU:GPU ratio、EPYC / Xeon adoption、data center TCO、AI inference revenue。

### AMD 雙線敘事 / 估值動能博弈框架

- **一句話定義**：AMD 的估值同時取決於 EPYC CPU 的穩定份額 / 現金流底座，以及 Instinct GPU 的高 beta AI upside；若只看 GPU 追趕，會低估 CPU 根基，也可能高估 AI 溢價。
- **適用情境**：AMD、CPU + GPU 混合 data center businesses、AI semiconductor challengers。
- **觀察指標**：EPYC market share、data center segment revenue mix、Instinct revenue、gross margin、2026 / 2027 EPS revision、forward P/E、MI roadmap、hyperscaler customer wins、NVDA / INTC relative performance。

## 風險與備註

- 文中多個市占、EPS、P/E 與目標價為 KP 口徑或其引用資料，未在本次逐項外部校準；入庫時保留為 KOL 觀點，不寫成 official guidance。
- **AMD** 目前仍在 watchlist，不因單篇 KP L3 自動建立正式 `Stocks/AMD/` 專案；後續若使用者要求或更多 KOL L3/L4 需要統整，再升級。
- **INTC** 是本文重要競爭風險，但非主角；只補歷史 L2，不改寫 INTC 目前儀表板的最新立場。
- 本文不是買賣建議。
