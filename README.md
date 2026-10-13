# DMIT 價格：從 $36.9/年 到 $759.9/月，搞懂三大機房與 Pro／Eyeball／Tier 1 的價差再下單

搜「DMIT 價格」的人，最後通常會撞上同一個疑問：同樣是 1 核 1G 的 VPS，為什麼 DMIT 可以賣 $36.9 一年，也可以賣 $39.9 一個月？

這不是官網標錯，也不是活動機在唬人。DMIT 的定價主要不是按 CPU 和記憶體算，而是按「你買哪一條線路、放在哪個機房」算。把這件事搞清楚，價格表就不再是一堆看不懂的英文方案名。

這篇把洛杉磯（LAX）、香港（HKG）、東京（TYO）三個機房的實際價格整理成表，順便講清楚隱形成本、優惠碼怎麼用，以及哪些方案其實不值得多花錢。

## DMIT 的價格由四件事決定

**線路的檔次。** DMIT 每個機房都切三種網路：

- Tier 1（T1）：國際 BGP 線路，沒有中國大陸專項優化，勝在便宜、頻寬大、流量多
- Eyeball（EB）：三網回程走 CMIN2／9929 這類中國方向優化線路，價格中等
- Premium（Pro）：三網回程 CN2 GIA，價格最高，也是最多人衝著它來的

**機房位置。** 香港 Pro 最低配月付 $39.9，洛杉磯 Pro 最低配月付 $9.99，東京 Pro 是 $21.9。同一個品牌、同一條 CN2 GIA 線路概念，價差可以到四倍。

**伺服器平台代次。** 官網方案名後面常掛著 AS3、AN4、AN5，對應的分別是 AMD EPYC 7003、9004、9005 系列處理器。新平台不一定漲價（香港 Pro 升 AN5 後起步價仍是 $39.9），但同一系列的不同代次可能同時在架，價格也就跟著有落差。

**庫存。** DMIT 走的是限量補貨模式，熱門方案補一批賣一批。你查到某個價格，隔兩週再打開可能已經 out of stock，或者只剩貴的那一檔。所以下面所有數字都請當成「價格水位」來看，最後以購物車顯示為準。

## DMIT 洛杉磯（LAX）價格表

### Tier 1 國際線路

| 方案 | 規格（CPU／記憶體／儲存） | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| T1.WEE | 1 核 / 1GB / 20GB SSD | 1TB · 4Gbps | $36.9 | 年付；超量限速 100Mbps 不限量 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.TINY | 1 核 / 1GB / 20GB SSD | 2TB · 4Gbps | $6.9 | 月付，年付約 $76.9 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.STARTER | 1～2 核 / 2GB / 40GB SSD | 4TB · 10Gbps | $12.9 | 月付，年付約 $154.8 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MINI | 2 核 / 2～4GB / 60～80GB SSD | 8TB · 10Gbps | $21.9 | 月付，年付約 $262.8 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MICRO | 4 核 / 4GB / 120GB SSD | 16TB · 10Gbps | $32.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MEDIUM | 4 核 / 8GB / 160GB SSD | 32TB · 10Gbps | $49.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.LARGE | 8 核 / 16GB / 320GB SSD | 64TB · 10Gbps | $99.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.GIANT | 8 核 / 24GB / 640GB SSD | 128TB · 10Gbps | $199.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

### Premium 與 Eyeball

| 方案 | 規格（CPU／記憶體／儲存） | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| Pro.TINY | 1 核 / 2GB / 20GB SSD | 1TB · 1Gbps | $9.99 | 月付；年付約 $88.88，低配年付折扣最深 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.Pocket | 2 核 / 2GB / 40GB SSD | 1.5TB · 4Gbps | $14.9 | 月付，年付約 $159.98 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.STARTER | 2 核 / 2GB / 80GB SSD | 3TB · 10Gbps | $29.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MINI | 4 核 / 4GB / 80GB SSD | 5TB · 10Gbps | $58.88 | 月付；超量限速 8Mbps | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MICRO | 4 核 / 4GB / 160GB SSD | 7TB · 10Gbps | $74.99 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MEDIUM | 6 核 / 8GB / 160GB SSD | 14TB · 10Gbps | $168.88 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.LARGE | 8 核 / 16GB / 320GB SSD | 25TB · 10Gbps | $338.88 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.GIANT | 12 核 / 24GB / 640GB SSD | 50TB · 10Gbps | $619.99 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.TINY | 1 核 / 2GB / 20GB SSD | 1.5TB · 2Gbps | $9.99 | 月付；同價位流量比 Pro 多 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.Pocket | 2 核 / 2GB / 40GB SSD | 3TB · 4Gbps | $14.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.STARTER | 2 核 / 2GB / 80GB SSD | 5TB · 10Gbps | $29.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.MINI | 4 核 / 4GB / 80GB SSD | 10TB · 10Gbps | $58.88 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.MICRO | 4 核 / 4GB / 160GB SSD | 14TB · 10Gbps | $74.99 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| EB.MEDIUM | 6 核 / 8GB / 160GB SSD | 30TB · 10Gbps | $199.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

洛杉磯有兩件事要注意。一是同一組方案在 AS3 舊平台上報價略高（Pro.TINY 為 $10.90），新平台補貨後才回到 $9.99 這一檔。二是 EB 系列在相近價格下給的流量明顯比 Pro 多，LAX 地區電信方向已優化到聯通 9929，所以「行動：選 Pro、電信／聯通：看 EB」這種老說法現在未必成立，實際差別比過去小。

## DMIT 香港（HKG）價格表

### Tier 1 國際線路

| 方案 | 規格 | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| T1.WEE | 1 核 / 1GB / 20GB SSD | 1TB · 4Gbps | $36.9 | 年付；超量限速 50Mbps 不限量 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.TINY | 1 核 / 1GB / 20GB SSD | 2TB · 4Gbps | $6.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.STARTER | 1 核 / 2GB / 40GB SSD | 4TB · 10Gbps | $12.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MINI | 2 核 / 2GB / 60GB SSD | 8TB · 10Gbps | $21.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MICRO | 4 核 / 4GB / 80GB SSD | 16TB · 10Gbps | $32.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MEDIUM | 4 核 / 8GB / 160GB SSD | 32TB · 10Gbps | $49.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.LARGE | 8 核 / 16GB / 320GB SSD | 64TB · 10Gbps | $99.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.GIANT | 8 核 / 24GB / 640GB SSD | 128TB · 10Gbps | $199.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

### Premium（三網 CN2 GIA）

| 方案 | 規格 | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| Pro.TINY | 1 核 / 1GB / 20GB SSD | 500GB · 1Gbps | $39.9 | 月付，年付約 $478 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.STARTER | 1 核 / 2GB / 40GB SSD | 1TB · 1Gbps | $79.9 | 月付，年付約 $958 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MINI | 2 核 / 2GB / 60GB SSD | 1.5TB · 1Gbps | $119.9～126.9 | 月付，依平台代次有差異 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MICRO | 2～4 核 / 4GB / 80GB SSD | 2TB · 1Gbps | $159.9～179.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MEDIUM | 4 核 / 4～8GB / 160GB SSD | 2.5TB · 1Gbps | $179.9～239.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.LARGE | 4 核 / 8GB / 240～320GB SSD | 3TB · 1Gbps | $239.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.GIANT | 8 核 / 16GB / 320GB SSD | 6TB · 1Gbps | $499.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

如果補到的是 AN5（AMD EPYC 9005）平台的規格，大配置那一端定價會拉高：AN5.Pro.MINI 4 核 / 4GB / 80GB / 1.5TB 為 $149.9、MICRO 4 核 / 4GB / 160GB / 2TB 為 $199.9、MEDIUM 6 核 / 8GB / 160GB / 2.5TB 為 $279.9、LARGE 8 核 / 16GB / 320GB / 3TB 為 $359.9、GIANT 12 核 / 24GB / 640GB / 6TB 為 $759.9。這排數字取自官網購物車頁面，也是香港 Pro 目前價格天花板的來源。

香港 Eyeball（HKG.EB）目前多數規格處於缺貨或不定時補貨狀態，下單前建議直接在購物車頁面確認可選項。

## DMIT 東京（TYO）價格表

### Premium（三網 CN2 GIA）

| 方案 | 規格 | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| Pro.TINY | 1 核 / 1GB / 20GB SSD | 500GB · 1Gbps | $21.9 | 月付，年付約 $262 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.STARTER | 1 核 / 2GB / 40GB SSD | 1TB · 1Gbps | $39.9 | 月付，年付約 $478 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MINI | 2 核 / 2GB / 60GB SSD | 2TB · 1Gbps | $79.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MICRO | 4 核 / 4GB / 80GB SSD | 4TB · 1Gbps | $159.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.MEDIUM | 4 核 / 8GB / 160GB SSD | 5TB · 1Gbps | $259.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.LARGE | 8 核 / 16GB / 320GB SSD | 8TB · 1Gbps | $429.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| Pro.GIANT | 8 核 / 24GB / 640GB SSD | 15TB · 1Gbps | $799.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

### Tier 1 國際線路

東京 T1 的價格結構與香港、洛杉磯一致：WEE 年付 $36.9，TINY $6.9/月起，一路到 GIANT $199.9/月，超量後限速 50Mbps 繼續跑、不停機。搭配季付以上的 7 折優惠碼，T1.TINY 年付可壓到約 $53.83，是目前東京最便宜的入手方式。

| 方案 | 規格 | 流量 · 頻寬 | 價格 | 週期與備註 | 購買 |
| --- | --- | --- | --- | --- | --- |
| T1.WEE | 1 核 / 1GB / 20GB SSD | 1TB · 4Gbps | $36.9 | 年付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.TINY | 1 核 / 1GB / 20GB SSD | 2TB · 4Gbps | $6.9（7 折後年付約 $53.83） | 月付／年付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.STARTER | 1～2 核 / 2GB / 40GB SSD | 4TB · 10Gbps | $12.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MINI | 2 核 / 2～4GB / 60～80GB SSD | 8TB · 10Gbps | $21.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MICRO | 4 核 / 4GB / 80GB SSD | 16TB · 10Gbps | $32.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.MEDIUM | 4 核 / 8GB / 160GB SSD | 32TB · 10Gbps | $49.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.LARGE | 8 核 / 16GB / 320GB SSD | 64TB · 10Gbps | $99.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |
| T1.GIANT | 8 核 / 24GB / 640GB SSD | 128TB · 10Gbps | $199.9 | 月付 | [ 查看此方案價格](https://www.dmit.io/aff.php?aff=12046) |

東京 Eyeball 系列已經確定下線，官方目前只保留 Premium 與 Tier 1，想買 EB 的話得往洛杉磯或香港找。東京 Pro 的庫存也一直偏緊，補貨多半來自回收的 IP 資源，賣完不一定短期內再上。

## 年付真的比月付便宜嗎

比你想的少。從官網列出的價格看，洛杉磯 Pro 最低配 TINY 的年付大概是 75 折（約 $88.88/年），其餘多數機型是 9 折左右。香港與東京的 Pro 系列更直接：HKG.Pro.TINY 月付 $39.9、年付 $478，換算下來年付幾乎等於月付 ×12，年付本身沒有額外優惠。

也就是說，想在 DMIT 身上省錢，重點不在拉長付款週期，而在用對優惠碼。

## 目前流通的 DMIT 優惠碼

優惠碼通常綁定特定機房、特定產品線和特定付款週期，帶 RECURRING 的是循環折扣（續費也打折）。結帳時選好週期，填入代碼按 Validate Code 驗證，通過才會顯示折後價。

| 優惠碼 | 適用範圍 | 折扣 |
| --- | --- | --- |
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | 洛杉磯 EB，TINY 以上非月付 | 8 折循環 |
| `202510_HKG_TYO_PRO_20OFF_RECURRING` | 香港／東京 Pro，季付以上 | 8 折循環 |
| `202510_HKG_TYO_T1_30OFF_RECURRING` | 香港／東京 T1，季付以上（不含 WEE） | 7 折循環 |
| `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` | 東京 T1，季付以上 | 7 折 |
| `Lite-Annually-Recur-30OFF` / `Lite-Semi-Annually-Recur-20OFF` | Standard／Lite 網路系列，年付／半年付 | 7 折／8 折 |
| `EXISTING-CUSTOMER-10OFF` | 月消費超過 $3.33 的老客戶 | 9 折 |

這些代碼來自第三方整理，活動機型與時效性都變動很快，別假設一定有效。最保險的做法是先在購物車試 Validate Code，過了再付款。

## 只看標價會漏掉的成本

**換 IP 要錢。** IP 完全被封（ICMP 與 TCP 全埠不通）時，同時滿足距開機滿 7 天、距上次換 IP 滿 15 天，每個 IP 可免費換一次。其他情況換 IP 收 $5。

**超量處理方式不一樣。** T1 系列（WEE）流量用完後降速不限量，架站不會斷；洛杉磯 Pro／EB 超量後限速在 4～10Mbps 之間，還能繼續用；東京 Pro 流量超出是暫停服務。如果你的業務不能接受停機，選購前務必看清楚這一欄。

**退款窗口。** 新購服務 3 天內且流量使用不超過 30GB 可申請全額退款，30 天內可按剩餘價值申請部分退款，條件依官方退款規則認定。

**限量機型是另一條價格線。** 洛杉磯偶爾會上架 LAX.Pro.MALIBU（1 核 1G／20GB／1TB，$49.9/年）與 PVM.LAX.EB.WEE（$39.9/年）這類特價機，價格比常規方案低一截，但售完不補，能不能遇到全憑運氣。

## 不同預算怎麼選

- 一年只想花 $40 以內：T1.WEE，$36.9/年，選洛杉磯版超量後限速 100Mbps，比香港、東京的 50Mbps 寬鬆
- 每月 $7～13：T1.TINY 或 T1.STARTER，國際線路，適合海外業務、落地、自己搭中轉
- 想要中國方向優化又不想付 $40/月：洛杉磯 Pro.TINY $9.99/月，同價位 EB.TINY 流量更多
- 香港延遲優先：HKG.Pro.TINY $39.9/月，三網回程 CN2 GIA，這是香港機房最便宜的一檔
- 日本 CN2 GIA：TYO.Pro.TINY $21.9/月，庫存緊張，遇到補貨就別猶豫太久

付款方面支援支付寶、PayPal 與信用卡，也有中文客服，對中國大陸與港澳台用戶的門檻不算高。

## 常見問題

**DMIT 為什麼比一般 VPS 貴？**
貴的是線路不是硬體。CN2 GIA、CMIN2、CU PM 這類與三大運營商直簽的資源本身成本就高，加上全系 AMD EPYC 與不超售的定位，價格自然壓不下來。反過來說，如果你不需要中國大陸方向的表現，Tier 1 系列的年付價其實跟一般便宜 VPS 差不多。

**最便宜的方案夠用嗎？**
$36.9/年的 T1.WEE 只有 1 核 1GB、20GB SSD，跑個小站、監控、跳板或輕量 API 沒問題，但要放資料庫或高流量服務就撐不住。流量超了會降速到 100Mbps，不會直接停機，這點比不少同價位產品友善。

**價格會一直變嗎？**
會。DMIT 的機型、平台代次與庫存幾乎每季都在動，同一方案在不同時間看到的價格可能不一樣。查價前先用官方 Looking Glass（`lg.dmit.sh`）測一下各地延遲，再對照購物車的即時報價，比翻二手資料可靠。

**下單前還有什麼要注意？**
熱門機型缺貨是常態，很多時候不是價格問題而是買不到。看到價格合適、庫存又在，就別放在購物車裡慢慢想。

想直接比對目前所有可下單方案與即時價格，可以從這裡進：

[👉 查看 DMIT 最新價格與庫存](https://www.dmit.io/aff.php?aff=12046)
