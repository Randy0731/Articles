# Tag Taxonomy

本文件定義全專案優先使用的 tag。新增 tag 前先檢查本文件，能歸入既有 tag 就不要新造同義詞。

## 使用原則

- tag 用 `#` 開頭，不加空白，例如 `#AI基建`。
- 每篇文章通常使用 1-5 個 tags；不要為了完整而塞滿。
- `主題 tags` 用於 KOL / Research；`母題標籤` 用於個股專案。
- 個股專案若有專屬母題，優先使用該股專屬 tag。
- 新 tag 只在既有 tag 無法表達時新增，並同步更新本文件與 `kol_config.yaml`（若是個股專屬母題）。

## 通用主題 Tags

| Tag | 定義 | 適用例子 |
|---|---|---|
| `#AI基建` | AI 算力、資料中心、GPU、電力、網路與雲端資本開支 | NVDA、AVGO、ANET、VRT、資料中心電力 |
| `#Memory` | DRAM、NAND、HBM、記憶體景氣循環 | MU、Samsung、SK Hynix、HBM4 |
| `#半導體設備` | 先進製程、封裝、設備、晶圓廠資本開支 | ASML、AMAT、LRCX、CoWoS |
| `#功率半導體` | 電源轉換、功率元件、SiC / GaN、資料中心電力與高壓供電元件 | ON、ADI、MPWR、NVTS、STM、TXN |
| `#先進封裝` | CoWoS、Chiplet、封裝產能與瓶頸 | TSM、AVGO、NVDA 供應鏈 |
| `#軟體SaaS` | 企業軟體、資安、資料平台、雲端 SaaS | MSFT、CRWD、RBRK、DDOG |
| `#國防科技` | defense tech、無人系統、C-UAS、軍民兩用 | ONDS、RCAT、AVAV、KTOS |
| `#能源電力` | 電網、儲能、發電、核能、天然氣、電力需求 | EOSE、SMR、CEG、VST |
| `#核能` | 核電、SMR、燃料、監管與部署 | SMR、CEG、BWXT |
| `#儲能` | 電池、長時儲能、電網儲能、商用部署 | EOSE、FLNC、STEM |
| `#消費成長` | 餐飲、零售、品牌、會員與同店銷售 | CAVA、BROS、CELH |
| `#生技醫療` | 臨床、FDA、藥物數據、醫療設備 | VKTX、LNTH、ALMU |
| `#金融流動性` | CTA、暗池、VIX、資金流、positioning | 宏觀週報、量化資金流 |
| `#地緣政治` | 戰爭、關稅、供應鏈重組、國防政策 | 中東、台海、澳洲國防支出 |
| `#宏觀利率` | Fed、通膨、就業、殖利率、美元 | CPI、FOMC、NFP |
| `#大宗商品` | 原物料、金屬、能源商品與 commodity cycle 供需 | 銅、黃金、原油、鈾、鋰、稀土 |
| `#加密貨幣` | Bitcoin、Ethereum、ETF、stablecoin、DeFi、RWA、crypto custody 與鏈上金融基礎設施 | BTC、ETH、IBIT、COIN、CRCL、ONDO、BUIDL、USDC |

## 事件 Tags

| Tag | 定義 |
|---|---|
| `#財報` | 季報、年報、guidance、earnings call |
| `#訂單合約` | 新訂單、合約、採購、客戶部署 |
| `#併購` | 收購、合併、資產出售、策略投資 |
| `#增發融資` | ATM、warrant、convertible、股本稀釋、債務再融資 |
| `#監管審批` | FDA、NRC、DOE、FAA、DoD 等審批或補助 |
| `#產品節點` | 量產、交付、認證、技術里程碑 |
| `#分析師動作` | 升降評、目標價調整、券商報告 |
| `#管理層發言` | CEO / CFO / IR 發言、訪談、法說會重點 |
| `#內部人交易` | CEO、董事、高階主管或大股東買賣自家公司股票 |

## 風險 Tags

| Tag | 定義 |
|---|---|
| `#估值風險` | valuation 過高、multiple 壓縮 |
| `#現金流風險` | 現金不足、burn rate、營運現金流轉弱 |
| `#執行風險` | 量產、交付、整合、成本控制不確定 |
| `#競爭風險` | 對手、替代技術、價格戰 |
| `#政策風險` | 補助、關稅、監管、政府採購變動 |
| `#供應鏈風險` | 零組件、產能、材料、供應商瓶頸 |
| `#稀釋風險` | 增發、warrant、可轉債、授權股 |

## 框架 Tags

| Tag | 定義 |
|---|---|
| `#ReRating` | 估值重評、敘事升級、機構定價變化 |
| `#CCC` | 宋分 / KP 類 CCC 訊號或相近機構級 re-rating 框架 |
| `#TypeATypeB` | 財務確定性 vs 敘事催化的分類 |
| `#上駟中駟` | 美股老司機分級框架 |
| `#投資與投機` | 投資 / 投機邊界、倉位與時間框架 |
| `#圍地論` | 長期卡位、提早佈局、等待市場理解 |
| `#機構洗盤` | 籌碼、解禁、增發、機構換手與洗盤敘事 |

## 個股專屬母題

### ONDS

| Tag | 定義 |
|---|---|
| `#十年繁榮` | CEO 定調的 10-year boom 敘事 |
| `#142K據點TAM` | 由下而上的 TAM 估算 |
| `#空地一體` | 空中 + 反制 + 地面整合的戰略框架 |
| `#PS小於1倍` | 併購套利財務模板 |
| `#DualUse` | 軍事 / 國土安全 / 公共安全 / 基建四客群通吃 |
| `#以色列併購` | 以色列公司收購案 |
| `#以色列訂單` | 以色列國防部 / IDF 相關訂單與合約 |
| `#以色列人事` | 前 Rafael 高層、IDF 將領等以色列人才招募 |
| `#機構洗盤` | PLTR 類比的洗盤劇本 |
| `#EPS終極裁判` | 併購成敗以 EPS 提升為核心標準 |
| `#授權股稀釋` | 授權股、增發與稀釋追蹤 |
| `#NATO佈局` | 歐洲與北約市場拓展 |
| `#垂直整合` | SPAI / LPTH / KOPN 等技術堆疊投資 |

### EOSE

| Tag | 定義 |
|---|---|
| `#鋅電池儲能` | Eos zinc battery 技術與差異化 |
| `#LDES長時儲能` | long duration energy storage 需求與部署 |
| `#DOE貸款` | DOE loan、補助、政策資金與撥款條件 |
| `#產能爬坡` | 製造產能、自動化、良率與出貨節奏 |
| `#訂單Backlog` | backlog、commercial pipeline、客戶簽約 |
| `#毛利轉正` | gross margin 改善與單位經濟 |
| `#現金流轉正` | 現金消耗、融資需求與 EBITDA / FCF 路徑 |
| `#稀釋與融資` | 增發、債務、warrant、資本結構 |

### SMR

| Tag | 定義 |
|---|---|
| `#小型模組化反應爐` | NuScale SMR 技術、部署與商業化 |
| `#NRC認證` | NRC licensing、設計認證、監管節點 |
| `#客戶部署` | 客戶簽約、PPA、部署地點與專案進度 |
| `#DOE與政策補助` | DOE、政府資金、核能政策支持 |
| `#成本與工期` | 建造成本、延宕、專案取消與成本超支 |
| `#HALEU燃料` | HALEU / uranium 燃料供應與瓶頸 |
| `#資料中心電力` | AI / data center 對核能電力需求的敘事 |
| `#核能安全敘事` | 安全性、公共接受度、監管與事故風險 |
