# Free for Dev



#### free for dev

\==================================

開發人員和開源作者現在擁有大量提供免費層級的服務，但很難找到所有這些服務來做出明智的決定。

這是為開發人員提供免費套餐的軟件（SaaS、PaaS、IaaS 等）和其他產品的列表。

此特定列表的範圍僅限於基礎設施開發人員（系統管理員、DevOps 從業者等）可能會發現有用的內容。我們喜歡那裡的所有免費服務，但最好保持主題。有時它有點像一條灰線，所以這有點固執己見；如果我不接受您的貢獻，請不要生氣。

此列表是 1100 多人的 Pull Requests、評論、想法和工作的結果。您也可以通過發送 [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服務或刪除產品已更改或已停用的服務來提供幫助。

**注意**：此列表僅適用於即服務產品，不適用於自託管軟件。要使一項服務符合條件，它必須提供免費套餐，而不僅僅是免費試用。如果免費套餐有時間限制，則必須至少為一年。我們還從安全角度考慮免費層，因此 SSO 很好，但我不會接受將 TLS 限制為僅付費層的服務。

## 目錄

* 主要雲提供商的永遠免費限制
* 雲管理解決方案
* 分析、事件和統計
* API、數據和機器學習
* 工件存儲庫
* BaaS
* CDN 和保護
* CI 和 CD
* CMS
* 代碼質量
* 代碼搜索和瀏覽
* 崩潰和異常處理
* 地圖上的數據可視化
* DBaaS
* 設計和 UI
* 設計靈感
* 開發博客站點
* DNS
* Docker 相關
* 域
* 電子郵件
* 字體
* 表格
* IaaS
* IDE 和代碼編輯
* 國際手機號碼驗證API和SDK
* 問題跟踪和項目管理
* 日誌管理
* 管理系統
* 消息和流媒體
* 雜項
* 監控
* PaaS
* 包構建系統
* 支付和計費集成
* 隱私管理
* 屏幕截圖 API
* Flutter 相關和在沒有 Mac 的情況下構建 IOS 應用程序
* 搜索
* 安全和 PKI
* 源代碼倉庫
* 存儲和媒體處理
* 隧道、WebRTC、Web Socket 服務器和其他路由器
* 測試
* 團隊和協作工具
* 翻譯管理
* Vagrant 相關
* 訪問者會話記錄
* 虛擬主機
* 評論平台
* 基於瀏覽器的硬件仿真
* 遠程桌面工具
* 遊戲開發
* 其他免費資源

主要雲提供商

***

* [谷歌云平台](https://cloud.google.com)
  * App Engine - 每天 28 個前端實例小時，每天 9 個後端實例小時
  * Cloud Firestore - 1GB 存儲，50,000 次讀取，20,000 次寫入，每天 20,000 次刪除
  * Compute Engine - 1 個非搶占式 e2-micro、30GB 硬盤、5GB 快照存儲（僅限某些地區）、每月從北美到所有地區目的地（不包括中國和澳大利亞）的 1GB 網絡出口
  * 雲存儲 - 5GB、1GB 網絡出口
  * Cloud Shell - 具有 5GB 持久存儲的基於 Web 的 Linux shell/基本 IDE。每週 60 小時限制
  * Cloud Pub/Sub - 每月 10GB 的消息
  * Cloud Functions - 每月 200 萬次調用（包括後台和 HTTP 調用）
  * Cloud Run - 每月 200 萬次請求、360,000 GB 秒內存、180,000 vCPU 秒計算時間、每月從北美流出的 1 GB 網絡
  * Google Kubernetes Engine - 一個區域集群不收取集群管理費。每個用戶節點均按標準 Compute Engine 價格收費
  * BigQuery - 每月 1 TB 的查詢，每月 10 GB 的存儲空間
  * Cloud Build - 每天 120 分鐘的構建時間
  * 雲源存儲庫 - 最多 5 個用戶、50 GB 存儲、50 GB 出口
  * [Google Collab](https://colab.research.google.com/) - 免費的 Jupyter Notebooks 開發環境。
  * 完整、詳細的列表 - [https://cloud.google.com/free](https://cloud.google.com/free)
* [亞馬遜網絡服務](https://aws.amazon.com)
  * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出口
  * [Cloudwatch](https://aws.amazon.com/cloudwatch/) - 10 個自定義指標和 10 個警報
  * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分鐘的構建時間
  * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 個活躍用戶、50GB 存儲空間和每月 10000 個請求
  * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 個活動管道
  * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL DB
  * [EC2](https://aws.amazon.com/ec2/) - t2.micro 或 t3.micro(12mo) 每月 750 小時
  * [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用型 (SSD) 或磁性 (12mo)
  * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 每月 750 小時（12 個月）
  * [Glacier](https://aws.amazon.com/glacier) - 10GB 長期對象存儲
  * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 萬次請求
  * [SNS](https://aws.amazon.com/sns/) - 每月 100 萬次發布
  * [SES](https://aws.amazon.com/ses/) - 每月 62.000 條消息
  * [SQS](https://aws.amazon.com/sqs/) - 100 萬個消息隊列請求
  * 完整、詳細的列表 - [https://aws.amazon.com/free/](https://aws.amazon.com/free/)
* [微軟 Azure](https://azure.microsoft.com)
  * [虛擬機](https://azure.microsoft.com/services/virtual-machines/) - 1 個 B1S Linux VM，1 個 B1S Windows VM (12mo)
  * [應用服務](https://azure.microsoft.com/services/app-service/) - 10 個 Web、移動或 API 應用（60 CPU 分鐘/天）
  * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 萬次請求
  * [開發測試實驗室](https://azure.microsoft.com/services/devtest-lab/) - 啟用快速、簡單和精益的開發測試環境
  * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 個對象
  * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月存儲 50,000 個用戶
  * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 個活躍用戶，無限的私有 Git 存儲庫
  * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 個免費的並行作業，用於 Linux、macOS 和 Windows 的開源無限分鐘
  * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 條消息
  * [負載均衡器](https://azure.microsoft.com/services/load-balancer/) - 1 個免費的公共負載均衡 IP (VIP)
  * [通知中心](https://azure.microsoft.com/services/notification-hubs/) - 100 萬條推送通知
  * [帶寬](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月 15GB 入站 (12mo) 和 5GB 出站
  * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 存儲和 400 RU 的預置吞吐量
  * [靜態 Web 應用程序](https://azure.microsoft.com/pricing/details/app-service/static/) — 構建、部署和託管靜態應用程序和無服務器功能，具有免費 SSL、身份驗證/授權和自定義域
  * [存儲](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存儲 (12mo)
  * [認知服務](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（計算機視覺、翻譯器、人臉檢測、機器人......）免費層級，包括有限交易
  * [認知搜索](https://azure.microsoft.com/services/search/#features) - 基於人工智能的搜索和索引服務，免費獲取 10,000 個文檔
  * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 託管Kubernetes服務，免費集群管理
  * [事件網格](https://azure.microsoft.com/services/event-grid/) - 100K 操作/月
  * 完整、詳細的列表 - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)
* [甲骨文云](https://www.oracle.com/cloud/)
  * 計算 - 2 個基於 x64，每個具有 1 GB RAM，4 個基於 Arm 的 Ampere A1 內核和 24 GB 內存，可用作一個 VM 或最多 4 個 VM
  * 塊卷 - 4 個卷，總共 200 GB（用於計算）
  * 對象存儲 - 10 GB
  * 負載均衡器 - 1 個 10 Mbps 的實例
  * 數據庫 - 2 個數據庫，每個 20 GB
  * 監控 - 5 億個攝取數據點，10 億個檢索數據點
  * 帶寬 - 每月 10 TB 出口，在基於 x64 的 VM 上速度限制為 50 Mbps，在基於 ARM 的 VM 上速度限制為 500 Mbps \* 核心數
  * 公共 IP - 2 個 IPv4 用於 VM，1 個 IPv4 用於負載平衡器
  * 通知 - 每月 100 萬個遞送選項，每月發送 1000 封電子郵件
  * 完整、詳細的列表 - [https://www.oracle.com/cloud/free/](https://www.oracle.com/cloud/free/)
* [IBM Cloud](https://www.ibm.com/cloud/free/)
  * Cloud Functions - 每月執行 500 萬次
  * 對象存儲 - 每月 25GB
  * Cloudant 數據庫 - 1 GB 數據存儲
  * Db2 數據庫 - 100MB 數據存儲
  * API Connect - 每月 50,000 次 API 調用
  * 可用性監控 - 每月 300 萬個數據點
  * 日誌分析 - 500MB 的每日日誌
  * 完整、詳細的列表 - [https://www.ibm.com/cloud/free/](https://www.ibm.com/cloud/free/)

雲管理解決方案

***

* [Brainboard](https://www.brainboard.co) - 從端到端可視化構建和管理雲基礎設施的協作解決方案。
* [Pulumi](https://www.pulumi.com/) — 現代基礎架構即代碼平台，允許您使用熟悉的編程語言和工具來構建、部署和管理雲基礎架構。
* [terraform.io](https://www.terraform.io/) — Terraform 雲。免費遠程狀態管理和團隊協作，最多可容納 5 個用戶。

### 源代碼倉庫

* [Bitbucket](https://bitbucket.org/) — 使用 Pipelines for CI/CD 為最多 5 個用戶提供無限的公共和私有 Git 存儲庫
* [chiselapp.com](https://chiselapp.com/) — 無限的公共和私有 Fossil 存儲庫
* [codebasehq.com](https://www.codebasehq.com/) — 一個 100 MB 空間和 2 個用戶的免費項目
* [Codeberg.org](https://codeberg.org/) - 免費和開源項目的無限公共和私有 Git 存儲庫。使用 [Codeberg Pages](https://codeberg.page/) 託管靜態網站。
* [Gitea.com](https://www.gitea.com/) - 無限的公共和私人 Git 存儲庫
* [GitGud](https://gitgud.io) — 無限的私有和公共存儲庫。永遠免費。由 GitLab 和藍寶石提供支持。未提供 CI/CD。
* [GitHub](https://github.com/) — 無限的公共存儲庫和無限的私有存儲庫（有無限的合作者）。除此之外，提供的其他一些免費服務（還有更多，但我們在這裡列出主要的）是：
  * [CI/CD](https://github.com/features/actions)（公共回購免費，私人回購免費2000分鐘/月）
  * [靜態網站託管](https://pages.github.com)（公共回購免費）
  * [Package Hosting & Container Registry](https://github.com/features/packages) （公共倉庫免費，500 MB 存儲空間和 CI/CD 外 1GB 帶寬免費用於私人倉庫）
  * 項目管理和問題跟踪。
* [gitlab.com](https://about.gitlab.com/) — 無限的公共和私人 Git 存儲庫，最多有 5 個協作者。還提供以下功能：
  * [CI/CD](https://about.gitlab.com/product/continuous-integration)（公共回購免費，私人回購400分鐘/月）
  * 帶有 [GitLab 頁面](https://about.gitlab.com/product/pages) 的靜態站點。
  * 每個 repo 限制為 10 GB 的 Container Registry。
  * 項目管理和問題跟踪。
* [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社區版的友好分支，為 Mercurial 提供支持
* [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 開發應用程序的回購和工具，你也有一個離子回購
* [NotABug](https://notabug.org) — NotABug.org 是一個免費軟件代碼協作平台，用於免費許可的項目，基於 Git
* [OSDN](https://osdn.net/) - OSDN.net 是面向開源軟件開發人員的免費服務，提供 SVN/Git/Mercurial/Bazaar/CVS 存儲庫等。
* [Pagure.io](https://pagure.io) — Pagure.io 是一個免費的開源軟件代碼協作平台，用於 FOSS 許可項目，基於 Git
* [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免費 1GB 雲和 Git、Mercurial 或 SVN 存儲庫。
* [pijul.com](https://pijul.com/) - 無限制的免費開源分佈式版本控制系統。它的顯著特點是建立在完善的補丁理論基礎上，易於學習和使用，真正的分佈式。解決了 git/hg/svn/darcs 的很多問題。
* [plasticscm.com](https://plasticscm.com/) — 個人、OSS 和非營利組織免費
* [projectlocker.com](https://projectlocker.com) — 一個 50 MB 空間的免費私人項目（Git 和 Subversion）
* [RocketGit](https://rocketgit.com) — 基於 Git 的存儲庫託管。無限的公共和私人存儲庫。
* [savannah.gnu.org](https://savannah.gnu.org/) - 作為免費軟件項目的協作軟件開發管理系統（用於 GNU 項目）
* [savannah.nongnu.org](https://savannah.nongnu.org/) - 作為自由軟件項目的協作軟件開發管理系統（非 GNU 項目）

### API、數據和機器學習

* [IP.City](https://ip.city) — 每天 100 個免費 IP 地理定位請求
* [A11yWatch](https://a11ywatch.com) - 強大的大規模 Web 可訪問性工具。免費的網站範圍內的網絡可訪問性測試，除此之外，每天都會重置。
* [Abstract API](https://www.abstractapi.com) — 適用於各種用例的 API 套件，包括 IP 地理定位、性別檢測甚至電子郵件驗證。
* [algorithmia.com](https://algorithmia.com/) — 免費託管算法。包括運行算法的免費每月津貼。現在有了 CLI 支持。
* [Apify](https://www.apify.com/) — Web 抓取和自動化平台，可為任何網站創建 API 並提取數據。現成的抓取工具、集成代理和定制解決方案。每月包含 5 美元平台積分的免費計劃。
* [API Mocha](https://apimocha.com) - 完全免費的在線 API 模擬，用於測試和原型設計。每天最多發出 500 個請求，完全可定制的 API 響應，將模擬規則下載為 Postman 集合。
* [APITemplate.io](https://apitemplate.io) - 使用簡單的 API 或 Zapier 和 Airtable 等自動化工具自動生成圖像和 PDF 文檔。不需要 CSS/HTML。免費計劃附帶 50 張圖片/月和 3 個模板。
* [Atlas 工具包](https://atlastk.org/) - 用於開發可立即訪問的單頁 Web 應用程序的輕量級庫。適用於 Java、Node.js、Perl、Python 和 Ruby。
* [Beeceptor](https://beeceptor.com) - 在幾秒鐘內模擬一個 rest API，偽造 API 響應等等。每天免費 50 個請求，公共儀表板，開放端點（任何擁有儀表板鏈接的人都可以查看請求和響應）。
* [bigml.com](https://bigml.com/) — 託管機器學習算法。無限的免費開發任務，16 MB 數據/任務的限制。
* [Bruzu](https://bruzu.com/) — 自動化圖像製作。使用 API、集成或 nocode 表生成大量圖像變體。API 是免費的，帶有水印。
* [Calendarific](https://calendarific.com) - 200 多個國家/地區的企業級公共假期 API 服務。免費計劃包括每月 1000 次通話。
* [Clarifai](https://www.clarifai.com) — 用於自定義人臉識別和檢測的圖像 API。能夠訓練人工智能模型。免費計劃每月有 5000 個電話。
* [cogram](https://www.cogram.com/old-home) - Cogram 使用人工智能在 Jupyter Notebook 中為您提供代碼建議。每月免費生成 1,000 次代碼。
* [Cloudmersive](https://cloudmersive.com/) — 實用 API 平台，可完全訪問廣泛的 API 庫，包括文檔轉換、病毒掃描等，每月調用 800 次。
* [Colaboratory](https://colab.research.google.com) — 帶有 Nvidia Tesla K80 GPU 的基於 Web 的免費 Python 筆記本環境。
* [Collect2](https://collect2.com) — 創建一個 API 端點來測試、自動化和連接 webhook。免費計劃允許兩個數據集、2000 條記錄、1 個轉發器和 1 個警報。
* [轉換工具](https://conversiontools.io/) - 用於文檔、圖像、視頻、音頻、電子書的在線文件轉換器。REST API 可用。Node.js、PHP、Python 的庫。支持最大 50 GB 的文件（用於付費計劃）。免費套餐受文件大小和每天轉換次數的限制。
* [Coupler](https://www.coupler.io/) - 在應用程序之間同步的數據集成工具。它可以創建實時儀表板和報告、轉換和操作值、收集和備份見解。免費計劃有無限用戶，每月 100 次運行 1000 行和無限集成。
* [CraftMyPDF](https://craftmypdf.com) - 使用拖放式編輯器和簡單的 API 從可重複使用的模板自動生成 PDF 文檔。免費計劃附帶 100 個 PDF/月和 3 個模板。
* [CurlHub](https://curlhub.io) — 用於檢查和調試 API 調用的代理服務。免費計劃包括每月 10,000 個請求。
* [CurrencyScoop](https://currencyscoop.com) - 用於金融科技應用的實時貨幣數據 API。免費計劃包括每月 5000 次通話。
* [Dataimporter.io](https://www.dataimporter.io) - 用於連接、清理和將數據導入 Salesforce 的工具。免費計劃每月最多包含 20,000 條記錄。
* [Data Miner](https://dataminer.io/) - 用於從網頁 CSV 或 Excel 中提取數據的瀏覽器擴展程序（Google Chrome、MS Edge）。免費計劃每月為您提供 500 頁。
* [Datapane](https://datapane.com) - 用於在 Python 中構建交互式報告並將 Python 腳本和 Jupyter Notebooks 部署為自助服務工具的 API。
* [DB-IP](https://db-ip.com/api/free) - 免費 IP 地理定位 API，每個 IP 每天 1k 請求。CC-BY 4.0 許可下的精簡數據庫也是免費的。
* [DB Designer](https://www.dbdesigner.net/) — 基於雲的數據庫模式設計和建模工具，具有 2 個數據庫模型和每個模型 10 個表的免費入門計劃。
* [DeepAR](https://developer.deepar.ai) — 具有一個 SDK 的任何平台的增強現實面部過濾器。免費計劃提供多達 10 個每月活躍用戶 (MAU) 並跟踪多達 4 個面孔
* [Deepnote](https://deepnote.com) - 一種新型的數據科學筆記本。Jupyter 兼容實時協作並在雲中運行。免費套餐包括無限的個人項目、長達 750 小時的標準硬件和最多 3 名編輯的團隊。
* [Diggernaut](https://www.diggernaut.com/) — 基於雲的網絡抓取和數據提取平台，用於將任何網站轉換為數據集或像使用 API 一樣使用它。免費計劃包括每月 5K 頁面請求。
* [Disease.sh](https://disease.sh/) — 免費 API，為構建與 Covid-19 相關的有用應用程序提供準確數據。
* [dominodatalab.com](https://www.dominodatalab.com) — 支持 Python、R、Spark、Hadoop、MATLAB 等的數據科學。
* [dreamfactory.com](https://dreamfactory.com/) — 用於移動、Web 和 IoT 應用程序的開源 REST API 後端。連接任何 SQL/NoSQL 數據庫、文件存儲系統或外部服務，它會立即創建一個具有實時文檔、用戶管理、...
* [DynaPictures](https://dynapictures.com) - 設計自動化工具，可讓您通過 REST API 動態生成圖像。即時更改顏色、文本、徽標和圖像。免費計劃包括每月 30 個生成的圖像和 3 個圖像模板。
* [Efemarai](https://efemarai.com) - ML 模型和數據的測試和調試平台。可視化任何計算圖。每月為開發人員免費提供 30 次調試會話。
* [Einblick](https://www.einblick.ai/) - 一個現代數據科學平台，可將 Python 筆記本帶入協作畫布，並包含自動執行常見任務的工具，例如構建預測模型 (AutoML) 或比較人群。免費套餐包括 5 幅畫布和無限的合作者。
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免費的基於 Web 的 HTTP 客戶端發送 HTTP 請求。
* [Export SDK](https://exportsdk.com) - 帶有拖放模板編輯器的 PDF 生成器 API，還提供 SDK 和無代碼集成。免費計劃每月提供 250 頁、無限用戶和三個模板。
* [file.coffee](https://file.coffee/) - 一個平台，您可以在其中存儲高達 15MB/文件（30/MB 文件與帳戶）。
* [Flatirons Fuse](https://flatironsdevelopment.com/products/fuse/) - 一種可嵌入的 CSV 和電子表格導入工具，可讓您快速、輕鬆、輕鬆地將數據導入您的網站。
* [FraudLabs Pro](https://www.fraudlabspro.com) — 篩選信用卡支付欺詐的訂單交易。此 REST API 將根據訂單的輸入參數檢測所有可能的欺詐特徵。免費微型計劃每月有 500 筆交易。
* [FreeGeoIP.app](https://freegeoip.app/) - 完全免費的地理 IP 信息（JSON、CSV、XML）。無需註冊，每小時 15000 次查詢的速率限制。
* [Geekflare API](https://geekflare.com/api) - Geekflare API 讓您可以截取屏幕截圖、審核網站、TLS 掃描、DNS 查找、測試 TTFB 等等。免費計劃提供 3000 個 API 請求。
* [GeoDataSource](https://www.geodatasource.com) — 使用緯度和經度坐標查找城市名稱的位置搜索服務。免費 API 查詢每月最多 500 次。
* [Glitterly](https://glitterly.app/) - 以編程方式從基本模板生成動態圖像。Restful API 和 nocode 集成。免費套餐每月提供 50 張圖片和 5 個模板。
* [GoodData](https://www.gooddata.com/) - 數據即服務 - 創建交互式且富有洞察力的儀表板。免費層包含 5 個工作區和 100 MB/工作區。
* [Hex](https://hex.tech/) - 用於筆記本、數據應用程序和知識庫的協作數據平台。免費社區版本，最多 3 個作者和 5 個項目。每位作者一個計算配置文件，4GB RAM。
* [Hookbin](https://hookbin.com/) - 創建唯一的（公共或私有）端點來收集、解析和檢查 HTTP 請求。檢查標頭、正文、查詢字符串、cookie、上傳的文件等。對於測試/檢查 webhook 很有用。類似於 RequestBin 和 Webhook.site。
* [Hoppscotch](https://hoppscotch.io) - 免費、快速、美觀的 API 請求構建器。
* [Hybiscus](https://hybiscus.dev/) - 使用簡單的聲明式 API 構建 pdf 報告。免費套餐包括每月最多 100 個單頁報告，能夠自定義顏色托盤和字體。
* [Invantive Cloud](https://cloud.invantive.com/) — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）訪問 70 多個（雲）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma。包括數據複製和交換。開發人員和實施顧問的免費計劃。對數據量有限制的特定平台免費。
* [ipaddress.sh](https://ipaddress.sh) — 獲取不同 [格式](https://about.ipaddress.sh/) 的公共 IP 地址的簡單服務。
* [Iploka](https://iploka.com/) - IP 到 Geolocation API - 為每月 10k 請求限制的開發人員提供永久免費計劃。
* [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API - 為每月 30k 請求（1k/天）限制的開發人員提供永久免費計劃。
* [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) - Abstract 的 IP Geolocation API - 廣泛的免費計劃，每月允許 20,000 個請求。
* [IP2Location](https://www.ip2location.com) — 免費增值 IP 地理定位服務。LITE 數據庫可免費下載。將數據庫導入服務器，進行本地查詢，確定城市、坐標和ISP信息。
* [IP2Location.io](https://www.ip2location.io/) — 免費增值，快速可靠的 IP 地理定位 API，用於確定城市、坐標、ISP 等地理定位數據。免費計劃提供每月 30k 積分。訂閱付費計劃以獲得更多高級功能或聯繫我們以獲得個性化計劃。
* [ipapi](https://ipapi.co/) - Kloudend, Inc 的 IP 地址定位 API - 可靠的地理定位 API，建立在 AWS 上，受到財富 500 強的信任。免費套餐每月提供 30k 次查找（1k/天）無需註冊。聯繫我們獲取更高限額的試用計劃。
* [IPinfo](https://ipinfo.io/) — 快速、準確且免費（每月最多 50k）的 IP 地址數據 API。提供有關地理位置、公司、運營商、IP 範圍、域、濫用聯繫人等詳細信息的 API。所有付費 API 均可免費試用。
* [IPFast](https://ip-fast.com/) — 使用免費、最快和簡單的查找工具查找您的 IP 地址和相關詳細信息。
* [IPList](https://www.iplist.cc) — 查找任何 IP 地址的詳細信息，例如 Geo IP 信息、Tor 地址、主機名和 ASN 詳細信息。個人和企業用戶免費。
* [BigDataCloud](https://www.bigdatacloud.com/) - 為現代網絡提供快速、準確和免費（無限或高達 10K-50K/月）的 API，如 IP 地理定位、反向地理編碼、網絡洞察、電子郵件和電話驗證、客戶信息等。
* [IPTrace](https://iptrace.io) — 一個非常簡單的 API，可為您的企業提供可靠且有用的 IP 地理定位數據。
* [JSON IP](https://getjsonip.com) — 返回請求它的客戶端的公共 IP 地址。免費層無需註冊。可以使用客戶端 JS 直接從瀏覽器請求使用 CORS 數據。對於監控客戶端和服務器 IP 變化的服務很有用。無限請求。
* [konghq.com/](https://konghq.com/) — API 市場和強大的私有和公共 API 工具。在免費層中，某些功能會受到限制，例如監控、警報和支持。
* [Kreya](https://kreya.app) — 免費的 gRPC GUI 客戶端，用於調用和測試 gRPC API。可以通過服務器反射導入 gRPC API。
* [KSoft.Si](https://api.ksoft.si/) — 主要針對不和諧機器人的免費歌詞 api。還提供廣泛的圖像和用戶數據庫
* [Lightly](https://www.lightly.ai/) — 使用正確的數據改進您的機器學習模型。免費使用多達 1'000 個樣本的數據集。
* [MailboxValidator](https://www.mailboxvalidator.com) — 使用真實郵件服務器連接來確認有效電子郵件的電子郵件驗證服務。免費 API 計劃每月有 300 次驗證。
* [microlink.io](https://microlink.io/) – 它將任何網站轉化為數據，例如元標記規範化、美麗鏈接預覽、抓取功能或屏幕截圖即服務。每天 100 個請求/天免費。
* [monkeylearn.com](https://monkeylearn.com/) — 使用機器學習進行文本分析，每月免費 300 次查詢。
* [MockAPI](https://www.mockapi.io/) — MockAPI 是一個簡單的工具，可讓您輕鬆地模擬 API、生成自定義數據並使用 RESTful 接口對其執行操作。MockAPI 旨在用作原型設計/測試/學習工具。每個項目免費 1 個項目/50 個資源。
* [Mocki](https://mocki.io) - 一種工具，可讓您創建同步到 GitHub 存儲庫的模擬 GraphQL 和 REST API。無需註冊即可免費創建和使用簡單的 REST API。
* [Mocko.dev](https://mocko.dev/) — 代理您的 API，免費選擇要在雲中模擬的端點並檢查流量。加快您的開發和集成測試。
* [Mocky](https://designer.mocky.io/) - 一個簡單的 Web 應用程序，用於生成自定義 HTTP 響應以模擬 HTTP 請求。也可作為 [開源](https://github.com/julien-lafont/Mocky)。
* [reqres.in](https://reqres.in) - 一個免費託管的 REST-API，可隨時響應您的 AJAX 請求。
* [microenv.com](https://microenv.com) — 為開發人員創建假 REST API，以便在 docker 容器中生成代碼和應用程序。
* [neptune.ai](https://neptune.ai/) - 記錄、存儲、顯示、組織、比較和查詢所有 MLOps 元數據。個人免費：1 名成員、100 GB 元數據存儲、200 小時監控/月
* [News API](https://newsapi.org) — 使用代碼在網絡上搜索新聞，獲取 JSON 結果。開發人員每月免費獲得 3,000 個查詢。
* [Nordigen](https://nordigen.com) — 免費開放銀行數據 API。PSD2。將 2300 多家銀行與您在 EU+UK 的應用程序/軟件聯繫起來。
* [Observable](https://observablehq.com/) — 一個使用數據創建、協作和學習的地方。免費：無限筆記本，無限出版，每個筆記本五個編輯。
* [OCR.Space](https://ocr.space/) — 一個 OCR API，它解析圖像和 pdf 文件，以 JSON 格式返回文本結果。每月免費 25,000 個請求。
* [Duply.co](https://duply.co) — 從 API 和 URL 創建動態圖像，設計模板一次並重複使用。免費套餐每月通過 API 和 URL 創建 70 張圖片，通過 Form 創建最多 100 張圖片。
* [前端從零到一](https://www.fezto.xyz/) — 立即從您的 OpenAPI 或 Swagger 規範啟動應用程序，看看合作夥伴如何體驗您的 API。自由的。自定義和代碼的付費層。
* [OpenAPI3 Designer](https://openapidesigner.com/) — 免費直觀地創建 Open API 3 定義。
* [Orchest](https://orchest.io) — 用於數據科學的可視化管道編輯器和工作流編排器，1 個免費實例，開源版本可用。
* [parsehub.com](https://parsehub.com/) — 從動態站點中提取數據，將動態站點轉換為 API，5 個項目免費。
* [Pixela](https://pixe.la/) - 免費日流數據庫服務。所有操作均由 API 執行。也可以使用熱圖和折線圖進行可視化。
* [回發](https://postbacks.io/) - 稍後請求 HTTP 回調。註冊時有 8,000 個免費請求。
* [Postman](https://postman.com) — 使用用於 API 開發的協作平台 Postman，簡化工作流程並更快地創建更好的 API。永久免費使用 Postman 應用程序。郵遞員雲功能也永遠免費，但有一定的限制。
* [PrefectCloud](https://www.prefect.io/cloud/) — 一個完整的數據流自動化平台。所有計劃都包括每月 20,000 次免費運行。這足以支持大多數小型企業的 ETL。
* [Preset Cloud](https://preset.io/) - 託管的 Apache Superset 服務。最多 5 個用戶的團隊永遠免費，具有無限的儀表板和圖表、無代碼圖表構建器和協作 SQL 編輯器。
* [ProxyCrawl](https://proxycrawl.com/) — 無需代理、基礎設施或瀏覽器即可抓取和抓取網站。我們為您解決驗證碼並防止您被阻止。前 1000 次通話是免費的。
* [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — 免費的公共 API 列表。
* [Supportivekoala](https://supportivekoala.com/) — 允許您通過模板輸入自動生成圖像。免費計劃允許您每週創建多達 100 張圖像。
* [QuickMocker](https://quickmocker.com/) — 管理您自己子域下的在線虛假 API 端點，將請求轉發到 localhost URL 以進行 webhook 開發和測試，使用 RegExp 和多種 HTTP 方法進行 URL 路徑，優先級端點等超過 100 個短代碼（動態或虛假響應值），用於響應模板、從 JSON 格式的 OpenAPI（Swagger）規範導入、代理請求、通過 IP 地址和授權標頭限制端點。免費帳戶提供 1 個隨機子域、10 個端點、5 個 RegExp URL 路徑、每個端點 50 個短代碼、每天 100 個請求、請求日誌中的 50 個歷史記錄。
* [Rapidapi](https://rapidapi.com/) - 世界上最大的 API 中心數以百萬計的開發人員發現並連接到數千個 API，使用有趣的挑戰（有解決方案！）和交互式示例進行 API 開發。
* [RequestBin.com](https://requestbin.com) — 創建一個免費端點，您可以向其發送 HTTP 請求。發送到該端點的任何 HTTP 請求都將與相關的有效負載和標頭一起記錄，以便您可以觀察來自 webhook 和其他服務的請求。
* [restlet.com](https://restlet.com/products/apispark/) — APISpark 使任何 API、應用程序或數據所有者能夠通過直觀的瀏覽器界面在幾分鐘內成為 API 提供者。
* [Roboflow](https://roboflow.com) - 無需機器學習經驗即可創建和部署自定義計算機視覺模型。免費套餐包括多達 1,000 個免費源圖像。
* [ROBOHASH](https://robohash.org/) - 從任何文本生成獨特（酷 :) 圖像的 Web 服務。
* [SaturnCloud](https://saturncloud.io/) - 數據科學云環境，允許運行 Jupyter 筆記本和 Dask 集群。每月 30 小時免費計算和 3 小時 Dask。
* [Scraper.AI](https://scraper.ai) - 將任何網站變成可消費的 API 供您構建的 SaaS。每月免費 50 次提取和 10000 次 API 調用。
* [Scraper's Proxy](https://scrapersproxy.com) — 用於抓取的簡單 HTTP 代理 API。匿名抓取，而不必擔心限制、阻止或驗證碼。每月前 100 次成功抓取免費，包括 javascript 渲染（如果您聯繫支持人員可以獲得更多）。
* [ScrapingAnt](https://scrapingant.com/) — 無頭 Chrome 抓取 API 和免費檢查代理服務。Javascript 渲染、高級輪換代理、避免驗證碼。提供免費計劃。
* [ScraperBox](https://scraperbox.com/) — 使用真正的 Chrome 瀏覽器和代理輪換無法檢測到的 Web 抓取 API。使用簡單的 API 調用來抓取任何網頁。免費計劃每月有 1000 個請求。
* [ScrapingDog](https://scrapingdog.com/) — Scrapingdog 處理數以百萬計的代理、瀏覽器和驗證碼，在單個 API 調用中為您提供任何網頁的 HTML。它還提供適用於 Chrome 和 Firefox 的 Web Scraper 以及用於即時抓取需求的軟件。提供免費計劃。
* [scrapinghub.com](https://scrapinghub.com) — 使用可視化界面和插件進行數據抓取。免費計劃包括在共享服務器上無限制抓取。
* [Select Star](https://www.selectstar.com/) - 是一個智能數據發現平台，可自動分析和記錄您的數據。具有 1 個數據源、最多 100 個表和最多 10 個用戶的免費輕型層。
* [Sheetson](https://sheetson.com) - 立即將任何 Google 表格轉換為 RESTful API。提供免費計劃。
* [shrtcode API](https://shrtco.de/docs) - 免費的 URL Shortening API 無需授權且無請求限制。
* [SerpApi](https://serpapi.com/) - 實時搜索引擎抓取 API。返回 Google、Youtube、Bing、百度、沃爾瑪和許多其他引擎的結構化 JSON 結果。免費計劃包括每月 100 次成功的 API 調用。
* [Similar Words API](https://word-simi.herokuapp.com/) — 查找相似詞的 API，詞彙量約為 400 萬個單詞。
* [Sofodata](https://www.sofodata.com/) - 從 CSV 文件創建安全的 RESTful API。上傳 CSV 文件並通過其 API 立即訪問數據，從而加快應用程序開發。免費計劃包括每月 2 個 API 和 2,500 個 API 調用。無需信用卡。
* [Stoplight](https://stoplight.io/) - 用於協作設計和記錄 API 的 Saas。免費計劃提供免費的設計、模擬和文檔工具供您入門。
* [tamber](https://tamber.com) — 在您的應用中加入深度學習驅動的推薦。免費 5k 月活躍用戶。
* [TinyMCE](https://www.tiny.cloud) - 富文本編輯 API。核心功能免費無限使用。
* [Unixtime](https://unixtime.co.za) - 將 Unixtime 轉換為 DateTime 的免費 API，反之亦然。
* [unscan](https://unscan.co) - 用於掃描圖像以查找 NSFW 和文件以查找惡意軟件的免費 API。每秒 100 個請求。
* [Webhook.site](https://webhook.site) - 使用這個即時顯示請求的便捷工具輕鬆測試 HTTP webhook。
* [wit.ai](https://wit.ai/) — 面向開發人員的 NLP。
* [wolfram.com](https://wolfram.com/language/) — 雲端內置基於知識的算法。
* [wrapapi.com](https://wrapapi.com/) — 將任何網站轉換為參數化 API。每月 30k API 調用。
* [ZenRows](https://www.zenrows.com/) — Web Scraping API 和代理服務器，可繞過任何反機器人解決方案，同時提供 javascript 渲染、旋轉代理和地理定位。1000 個 API 調用的免費層級。
* [Zenscrape](https://zenscrape.com/web-scraping-api) — 具有無頭瀏覽器、住宅 IP 和簡單定價的 Web 抓取 API。每月 1000 次免費 API 調用，為學生和非營利組織提供額外的免費積分。
* [ip-api](https://ip-api.com) — IP Geolocation API，非商業用途免費，無需 API 密鑰，免費計劃的同一 IP 地址限制為 45 req/分鐘。
* [WebScraping.AI](https://webscraping.ai) - 簡單的 Web Scraping API，內置解析、Chrome 渲染和代理。每月 2000 次免費 API 調用。
* [Zipcodebase](https://zipcodebase.com) - 免費郵政編碼 API，訪問全球郵政編碼數據。10000 個免費請求/月。
* [EVA](https://eva.pingutil.com/) - 免費的電子郵件驗證器 API，有助於識別電子郵件是否是一次性的以及是否具有有效的 MX 記錄。
* [happi.dev](https://happi.dev) - 免費增值 api 服務集合（音樂、匯率、鍵值存儲、語言檢測、密碼生成器、二維碼生成器、歌詞）。每月 4000 次免費 API 調用。
* [huggingface.co](https://huggingface.co) - 為 Pytorch、TensorFlow 和 JAX 構建、訓練和部署 NLP 模型。每月最多可釋放 30k 個輸入字符。
* [vatcheckapi.com](https://vatcheckapi.com) - 簡單且免費的增值稅號驗證 API。每月 500 個免費請求。
* [numlookupapi.com](https://numlookupapi.com) - 免費電話號碼驗證 API - 100k 免費請求/月。

### 工件回購

* [Artifactory](https://jfrog.com/start-free/) - 支持多種包格式的工件存儲庫，如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS。包括包掃描工具 XRay 和 CI/CD 工具 Pipelines（以前稱為 Shippable），每月免費提供 2,000 CI/CD 分鐘。
* [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他構建系統的默認工件存儲庫。
* [cloudrepo.io](https://cloudrepo.io) - 基於雲的私有和公共、Maven 和 PyPi 存儲庫。對開源項目免費。
* [cloudsmith.io](https://cloudsmith.io) — 適用於 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的簡單、安全和集中的存儲庫服務。免費層 + 免費用於開源。
* [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 項目的 Maven 存儲庫，公共項目免費。
* [packagecloud.io](https://packagecloud.io/users/new?plan=free\_usage\_plan) — 易於使用的存儲庫託管：Maven、RPM、DEB、PyPi、NPM 和 RubyGem 包（有免費層）。
* [repsy.io](https://repsy.io) — 1 GB 免費私有/公共 Maven 存儲庫。
* [Gemfury](https://gemfury.com) — Maven、PyPi、NPM、Go Module、Nuget、APT、RPM 存儲庫的私有和公共工件存儲庫。公共項目免費。

團隊和協作工具

***

* [3Cols](https://3cols.com/) - 基於雲的免費代碼片段管理器，用於個人和協作代碼。
* [Bitwarden](https://bitwarden.com) — 個人、團隊和企業組織存儲、共享和同步敏感數據的最簡單、最安全的方式。
* [Braid](https://www.braidchat.com/) — 專為團隊設計的聊天應用程序。對公共訪問組、無限用戶、歷史記錄和集成免費。它還提供自託管的開源版本。
* [cally.com](https://cally.com/) — 查找會議的最佳時間和日期。使用簡單，非常適合小型和大型團體。
* [Calendly](https://calendly.com) — Calendly 是用於連接和安排會議的工具。免費計劃為每位用戶提供 1 個日曆連接和無限次會議。還提供桌面和移動應用程序。
* [Discord](https://discord.com/) — 與公共/私人房間聊天。Markdown 文本、語音、視頻和屏幕共享功能。無限用戶免費。
* [Telegram](https://telegram.org/) — Telegram 適用於所有想要快速可靠的消息傳遞和通話的人。企業用戶和小型團隊可能喜歡大型群組、用戶名、桌面應用程序和強大的文件共享選項。
* [Duckly](https://duckly.com/) — 與您的團隊實時交談和協作。與任何 IDE 配對編程、終端共享、語音、視頻和屏幕共享。小團隊免費。
* [Dyte](https://dyte.io) - 對開發人員最友好的實時視頻和音頻 SDK，具有協作插件以提高生產力和參與度。免費套餐包括每月 10,000 分鐘的實時視頻/音頻使用。
* [evernote.com](https://evernote.com/) — 用於組織信息的工具。分享您的筆記並與他人合作
* [Fibery](https://fibery.io/) — 連接的工作空間平台。單用戶免費，最多 2 GB 磁盤空間。
* [Filestash](https://www.filestash.app) — 類似於 Dropbox 的文件管理器，可連接到一系列協議和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等。
* [flock.com](https://flock.com) — 一種更快的團隊溝通方式。免費無限的消息、渠道、用戶、應用程序和集成
* [Flowdash](https://flowdash.com/) — 自動化業務工作流程。免費套餐最多可容納 3 個用戶、1000 個任務和 3 個工作流。
* [flowdock.com](https://www.flowdock.com/) — 聊天和收件箱，最多 5 人的團隊免費
* [Gather](https://www.gather.town/) - 一種更好的在線見面方式。Gather 以完全可定制的空間為中心，讓您與社區共度時光就像在現實生活中一樣輕鬆。最多 25 個並髮用戶免費。
* [flat.social](https://flat.social) - 用於團隊會議和歡樂時光社交的交互式可定制空間。無限會議，最多釋放 8 個並髮用戶。
* [GitDailys](https://gitdailies.com) - 團隊在 GitHub 上的提交和拉取請求活動的每日報告。包括推送可視化工具、對等識別系統、自定義警報生成器。免費層有無限用戶、3 個存儲庫、3 個警報配置。
* [gitter.im](https://gitter.im/) — 聊天，用於 GitHub。無限制的公共和私人房間，最多 25 人的團隊免費
* [hangouts.google.com](https://hangouts.google.com/) — 一個可以免費進行所有對話的地方，需要一個 Google 帳戶
* [HeySpace](https://hey.space) - 帶有聊天、日曆、時間線和視頻通話的任務管理工具。最多 5 位用戶免費。
* [helplightning.com](https://www.helplightning.com/) — 通過增強現實幫助視頻。免費，無需分析、加密、支持
* [ideascale.com](https://ideascale.com/) — 允許客戶提交想法和投票，1 個社區中的 25 名成員免費
* [Igloo](https://www.igloosoftware.com/) — 用於共享文檔、博客和日曆等的內部門戶。最多 10 位用戶免費。
* [Keybase](https://keybase.io/) — Keybase 是 Slack 的一個很酷的 FOSS 替代品，它可以確保每個人的聊天和文件安全，從家庭到社區再到公司。
* [Google Meet](https://meet.google.com/) — 使用 Google Meet 滿足您企業的在線視頻會議需求。Meet 提供安全、易於加入的在線會議。
* [/meet for Slack](https://meetslack.com) - 在任何頻道、組或 DM 中使用 /meet 直接從 Slack 啟動 Google 會議。免費，沒有任何限制。
* [Livecycle](https://www.livecycle.io/) — Livecycle 是一個包容性協作平台，可讓跨職能產品團隊和開源項目的工作流程順暢無阻。
* [MarkUp](https://www.markup.io/) — MarkUp 讓您可以直接在您的網站、PDF 和圖像上收集反饋。
* [meet.jit.si](https://meet.jit.si/) — 一鍵視頻對話，屏幕共享，免費
* [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams 是一個基於聊天的數字中心，可通過單一體驗將對話、內容和應用程序集中在一個地方。最多 50 萬用戶免費。
* [Miro](https://miro.com/) - 適用於分佈式團隊的可擴展、安全、跨設備和企業就緒的團隊協作白板。有免費增值計劃。
* [nootiz](https://www.nootiz.com/) - 在任何網站上收集和管理視覺反饋的首選工具
* [Notion](https://www.notion.so/) - Notion 是一個支持 Markdown 的筆記和協作應用程序，它還集成了任務、wiki 和數據庫。該公司將該應用程序描述為用於記筆記、項目管理和任務管理的一體化工作區。除了跨平台應用程序外，它還可以通過大多數網絡瀏覽器訪問。
* [Nuclino](https://www.nuclino.com) - 一個輕量級的協作 wiki，包含您團隊的所有知識、文檔和筆記。具有所有基本功能的免費計劃，最多 50 個項目，5GB 總存儲空間。
* [Quidlo Timesheets](https://www.quidlo.com/timesheets) - 一個簡單的團隊時間表和時間跟踪應用程序。免費計劃具有時間跟踪和生成報告功能，最多可供 10 個用戶使用。
* [PageShare.dev](https://www.pageshare.dev) - 將視覺評論功能添加到 GitHub 拉取請求中，無需部署網站。每個月最多免費提供 10 頁，總共 100MB 的存儲空間。
* [Pendulums](https://pendulums.io/) - Pendulums 是一款免費的時間跟踪工具，它通過易於使用的界面和有用的統計數據幫助您以更好的方式管理您的時間。
* [Raindrop.io](https://raindrop.io) - 適用於 macOS、Windows、Android、iOS 和 Web 的私密且安全的書籤應用程序。免費無限書籤和協作。
* [element.io](https://element.io/) — 一個基於 Matrix 的去中心化開源通信工具。群聊、直接消息、加密文件傳輸、語音和視頻聊天以及與其他服務的輕鬆集成。
* [Rocket.Chat](https://rocket.chat/) - 團隊共享收件箱，安全、無限制和開源。
* [seafile.com](https://www.seafile.com/) — 私有或云存儲、文件共享、同步、討論。私人版已滿。雲版本只有 1 GB
* [Sema](https://www.semasoftware.com/) - 免費的開發人員組合工具，能夠將跨多個存儲庫的貢獻合併和快照到一個報告中。
* [Slab](https://slab.com/) — 面向團隊的現代知識管理服務。最多 10 個用戶免費。
* [slack.com](https://slack.com/) — 對無限用戶免費，但有一些功能限制
* [Spectrum](https://spectrum.chat/) - 免費創建公共或私人社區。
* [StatusPile](https://www.statuspile.com/) - 狀態頁面的狀態頁面。跟踪上游提供商的狀態頁面。
* [Stickies](https://stickies.app/) - 用於頭腦風暴、內容管理和筆記的視覺協作應用程序。最多可免費使用 3 面牆、無限用戶、1 GB 存儲空間。
* [talky.io](https://talky.io/) — 免費群視頻聊天。匿名的。點對點。無需插件、註冊或付款
* [Teamhood](https://teamhood.com/) - 免費的項目、任務和問題跟踪軟件。通過泳道和完整的 Scrum 實施支持看板。具有集成的時間跟踪。5 個用戶和 3 個項目組合免費。
* [Tefter](https://tefter.io) - 具有強大 Slack 集成的書籤應用程序。對開源團隊免費。
* [TeleType](https://teletype.oorja.io/) — 共享終端、語音、代碼、白板等。無需登錄，面向開發人員的端到端加密協作。
* [TimeCamp](https://www.timecamp.com/) - 無限用戶的免費時間跟踪軟件。與 Jira、Trello、Asana 等 PM 工具輕鬆集成。
* [Tree Schema](https://treeschema.com/) — 使用 API 進行數據目錄和元數據管理，以將數據沿襲作為代碼進行管理。最多 5 名用戶的團隊免費。
* [twist.com](https://twist.com) — 一個異步友好的團隊交流應用程序，其中的對話保持井井有條並切合主題。提供免費和無限計劃。為符合條件的團隊提供折扣。
* [BookmarkOS.com](https://bookmarkos.com) - 可自定義的在線桌面中的免費多合一書籤管理器、標籤管理器和任務管理器，具有文件夾協作功能。
* [typetalk.com](https://www.typetalk.com/) — 通過網絡或手機上的即時消息與您的團隊分享和討論想法
* [Tugboat](https://tugboat.qa) - 預覽每個拉取請求，自動化和按需。對所有人免費，為非營利組織提供免費的 Nano 層級。
* [whereby.com](https://whereby.com/)——一鍵視頻對話，免費（原名appear.in）
* [windmill.dev](https://windmill.dev/) - Windmill 是一個開源開發者平台，可以從最小的 Python 和 Typescript 腳本快速構建生產級多步驟自動化和內部應用程序。免費用戶，您可以創建並成為最多 3 個非高級工作區的成員。
* [vadoo.tv](https://vadoo.tv/) — 視頻託管和營銷變得簡單。一鍵上傳視頻。記錄、管理、分享等等。免費套餐最多提供 10 個視頻、1 GB 存儲空間、10 GB 帶寬/月
* [vspace](https://vvv.space/) — 帶有私人/公共空間的免費鏈接管理器，包括 slack 和 google docs 集成以及 chrome 插件。
* [userforge.com](https://userforge.com/) - 相互關聯的在線角色、用戶故事和上下文映射。幫助保持設計和開發同步，最多可免費供 3 個角色和 2 個協作者使用。
* [wistia.com](https://wistia.com/) — 具有觀眾分析、高清視頻交付和營銷工具的視頻託管，以幫助了解您的訪問者、25 個視頻和 Wistia 品牌播放器
* [wormhol.org](https://www.wormhol.org/) — 簡單的文件共享服務。與盡可能多的同行共享不超過 5GB 的無限文件。
* [zoom.us](https://zoom.us/) — 安全視頻和網絡會議，提供附加組件。免費限時 40 分鐘
* [shtab.app](https://shtab.app/) - 項目管理服務，可通過基於 AI 的跟踪器實現辦公室協作和遠程透明。
* [Zulip](https://zulip.com/) — 具有獨特的類似電子郵件的線程模型的實時聊天。免費計劃包括 10,000 條搜索歷史消息和高達 5 GB 的文件存儲空間。它還提供自託管的開源版本。
* [Automate.io](https://automate.io) - 簡單和復雜的自動化工作流程工具，具有 200 多個應用程序集成。每月 300 次操作和 5 個機器人是免費的
* [robocorp.com](https://robocorp.com) - 用於支持自動化操作的開源堆棧。免費試用雲功能並實施簡單的自動化。機器人工作 240 分鐘/月，10 次助手運行，100 MB 存儲空間。
* [Fleep.io](https://fleep.io/) — Fleep 是 Slack 的替代品。它為具有完整消息歷史記錄、無限 1 對 1 對話、1 組對話和 1 GB 文件存儲的小型團隊提供免費計劃。
* [Chanty.com](https://chanty.com/) — Chanty 是 Slack 的另一種替代品。它為小型團隊（最多 10 個）提供永久免費計劃，包括無限的公共和私人對話、可搜索的歷史記錄、無限的 1:1 音頻通話、無限的語音消息、10 次集成和每個團隊 20 GB 的存儲空間。
* [ruttl.com](https://ruttl.com/) — 收集數字反饋和審查網站、PDF 和圖像的最佳一體化反饋工具。

### CMS

* [acquia.com](https://www.acquia.com/) — Drupal 網站的託管。開發人員的免費套餐。還提供免費的開發工具（例如 Acquia Dev Desktop）
* [內容豐富](https://www.contentful.com/) — 無頭 CMS。雲中的內容管理和交付 API。附帶一個免費社區空間，其中包括 5 個用戶、25K 條記錄、48 種內容類型、2 個語言環境。
* [Cosmic](https://www.cosmicjs.com/) — 無頭 CMS 和 API 工具包。開發人員的免費個人計劃。
* [Crystallize](https://crystallize.com) — 支持電子商務的無頭 PIM。內置 GraphQL API。免費版包括無限用戶、1000 個目錄項、5 GB/月帶寬和 25k/月 API 調用。
* [DatoCMS](https://www.datocms.com/) - 為小型項目提供免費套餐。DatoCMS 是一個基於 GraphQL 的 CMS。在較低層，您每月有 10 萬次通話。
* [Directus](https://directus.io) — 無頭 CMS。一個完全免費的開源平台，用於在本地或云端管理資產和數據庫內容。沒有限製或付費牆。
* [Forestry.io/](https://forestry.io/) — 無頭 CMS。為您的編輯提供 Git 的強大功能。輕鬆創建和編輯基於 Markdown 的內容。附帶三個免費網站，其中包括 3 個編輯器、即時預覽。與託管在 Netlify/GitHubpages/ 其他地方的博客集成
* [FrontAid](https://frontaid.io/) — 將 JSON 內容直接存儲在您自己的 Git 存儲庫中的無頭 CMS。沒有限制。
* [kontent.ai](https://www.kontent.ai) - 一個內容即服務平台，為您提供所有無頭 CMS 優勢，同時為營銷人員提供支持。開發人員計劃為 2 個用戶提供無限項目，每個用戶有 2 個環境、500 個內容項、2 種語言以及交付和管理 API，以及自定義元素支持。更大的計劃可滿足您的需求。
* [Prismic](https://www.prismic.io/) — 無頭 CMS。具有完全託管和可擴展 API 的內容管理界面。社區計劃為 1 位用戶提供無限的 API 調用、文檔、自定義類型、資產和語言環境。您下一個項目所需的一切。更大的免費計劃可用於開放內容/開源項目。
* [Sanity.io](https://www.sanity.io/) - 帶有開源編輯環境和實時託管數據存儲的結構化內容平台。無限的項目。無限的管理員用戶、3 個非管理員用戶、2 個數據集、500K API CDN 請求、10GB 帶寬、每個項目免費包含 5GB 資產。
* [sensenet](https://sensenet.com) - API 優先的無頭 CMS，為各種規模的企業提供企業級解決方案。開發人員計劃提供 3 個用戶、500 個內容項、3 個內置角色、25+5 種內容類型、完全可訪問的 REST API、文檔預覽生成和 Office Online 編輯。
* [GatsbyjsCMS](https://www.gatsbyjs.com/) - Gatsby 是一個快速靈活的框架，它讓使用任何 CMS、API 或數據庫構建網站再次變得有趣。構建和部署無頭網站，以推動更多流量、更好地轉換並獲得更多收入！
* [GraphCMS](https://graphcms.com/) - 為小型項目提供免費套餐。GraphQL 第一個 API。從遺留解決方案轉移到 GraphQL 原生 Headless CMS - 並首先提供全渠道內容 API。
* [Squidex](https://squidex.io/) - 為小型項目提供免費套餐。首先是 API/GraphQL。開源，基於事件溯源（自動處理每一個變化）。
* [InstaWP](https://instawp.com/) - 在幾秒鐘內啟動一個 WordPress 網站。免費套餐包含：5 個活動站點、500 MB 空間、48 小時站點到期。

### 代碼質量

* [SoftaCheck](https://www.softacheck.com/) — 使用 cppcheck 和 clang-tidy 等開源工具對 C/C++ 代碼進行靜態分析並自動為使用 doxygen 的用戶生成代碼文檔的在線工具。這個工具是免費使用的。
* [beanstalkapp.com](https://beanstalkapp.com/) — 編寫、審查和部署代碼的完整工作流程），1 個用戶的免費帳戶和 1 個具有 100 MB 存儲空間的存儲庫
* [browserling.com](https://www.browserling.com/) — 實時交互式跨瀏覽器測試，在 Vista 下以 1024 x 768 分辨率使用 MS IE 9 只需 3 分鐘免費會話
* [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自動代碼審查，對無限的公共和私有存儲庫免費
* [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 作為 DevOps 代碼審查工具的自動化基礎架構與 GitHub、Bitbucket 和 GitLab 集成（甚至自託管）。除了標準語言，它還分析 Ansible、Terraform、CloudFormation、Kubernetes 等。（開源免費）
* [CodeBeat](https://codebeat.co) — 可用於多種語言的自動代碼審查平台。與 Slack 和電子郵件集成的公共存儲庫永遠免費。
* [codeclimate.com](https://codeclimate.com/) — 自動代碼審查，對開源免費和無限的組織擁有的私人倉庫（最多 4 個合作者）。對學生和機構也免費。
* [codecov.io](https://codecov.io/) — 代碼覆蓋工具 (SaaS)，對開源免費和 1 個免費私人回購
* [CodeFactor](https://www.codefactor.io) — Git 的自動代碼審查。免費版包括無限用戶、無限公共存儲庫和 1 個私人存儲庫。
* [codescene.io](https://codescene.io/) - CodeScene 根據開發人員使用代碼的方式優先考慮技術債務，並可視化團隊耦合和系統掌握等組織因素。開源免費。
* [coveralls.io](https://coveralls.io/) — 顯示測試覆蓋率報告，開源免費
* [dareboost](https://dareboost.com) - 每月 5 份免費的網絡性能、可訪問性、安全性分析報告
* [deepcode.ai](https://www.deepcode.ai) — DeepCode 基於 AI 發現錯誤、安全漏洞、性能和 API 問題。DeepCode 的分析速度使我們能夠實時分析您的代碼並在您點擊 IDE 中的保存按鈕時提供結果。支持的語言有 Java、C/C++、JavaScript、Python 和 TypeScript。與 GitHub、BitBucket 和 GitLab 集成。對開源和私人存儲庫免費，最多可釋放 30 名開發人員。
* [deepscan.io](https://deepscan.io) — 高級靜態分析，用於自動查找 JavaScript 代碼中的運行時錯誤，開源免費
* [DeepSource](https://deepsource.io/) - DeepSource 持續分析源代碼更改，發現並修復按安全、性能、反模式、錯誤風險、文檔和样式分類的問題。與 GitHub、GitLab 和 Bitbucket 的原生集成。
* [eversql.com](https://www.eversql.com/) — EverSQL - 數據庫優化的第一平台。自動神奇地獲得對您的數據庫和 SQL 查詢的重要見解。
* [gerrithub.io](https://review.gerrithub.io/) — 免費對 GitHub 存儲庫進行 Gerrit 代碼審查
* [gocover.io](https://gocover.io/) — 任何 [Go](https://golang.org/) 包的代碼覆蓋率
* [goreportcard.com](https://goreportcard.com/) — Go 項目的代碼質量，開源免費
* [gtmetrix.com](https://gtmetrix.com/) — 優化網站的報告和全面建議
* [holistic.dev](https://holistic.dev/) - 用於 Postgresql 優化的#1 靜態代碼分析器。性能、安全和架構數據庫問題自動檢測服務
* [houndci.com](https://houndci.com/) — 對 GitHub 提交關於代碼質量的評論，對開源免費
* [insight.sensiolabs.com](https://insight.sensiolabs.com/) — PHP/Symfony 項目的代碼質量，開源免費
* [lgtm.com](https://lgtm.com) — 針對 Java、Python、JavaScript、TypeScript、C#、C 和 C++ 的持續安全分析，開源免費
* [Moderne.io](https://app.moderne.io) — 自動源代碼重構。Moderne 提供框架遷移、帶有補救措施的代碼分析以及無與倫比的大規模代碼轉換，因此開發人員可以將時間花在構建新事物上，而不是維護舊事物。開源免費。
* [reviewable.io](https://reviewable.io/) — GitHub 存儲庫的代碼審查，公共或個人存儲庫免費
* [parsers.dev](https://parsers.dev/) - 抽象語法樹解析器和中間表示編譯器即服務
* [scan.coverity.com](https://scan.coverity.com/) — 針對 Java、C/C++、C# 和 JavaScript 的靜態代碼分析，開源免費
* [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持續檢查平台，開源免費
* [shields.io](https://shields.io) — 開源項目的質量元數據徽章
* [Sider](https://sider.review) — 多種語言的代碼審查平台。支持與 GitHub 集成。對擁有無限用戶的公共存儲庫免費。
* [sonarcloud.io](https://sonarcloud.io) — Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 甚至更多語言的自動源代碼分析, 開源免費
* [SourceLevel](https://sourcelevel.io/) — 自動代碼審查和團隊分析。開放源代碼和最多 5 個合作者的組織免費。
* [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI 審查您的拉取請求並提交拼寫錯誤，對開源免費。
* [Viezly](https://viezly.com/) - 增強的代碼審查工具，便於代碼閱讀和導航。開源免費，個人使用免費。
* [webceo.com](https://www.webceo.com/) — SEO 工具，但也有代碼驗證和不同類型的建議
* [zoompf.com](https://zoompf.com/) — 修復你的網站性能，詳細分析

代碼搜索和瀏覽

***

* [tabnine.com](https://www.tabnine.com/) — Tabnine 通過提供從世界上所有代碼中學到的見解，幫助開發人員更快地創建更好的軟件。插件可用。
* [libraries.io](https://libraries.io/) — 32 個不同的包管理器的搜索和依賴更新通知，開源免費
* [Namae](https://namae.dev/) - 搜索各種網站，如 github、gitlab、heroku、netlify 等，以獲取項目名稱的可用性。
* [searchcode.com](https://searchcode.com/) — 全面的基於文本的代碼搜索，開源免費
* [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，代碼搜索/交叉引用，開源免費
* [tickgit.com](https://www.tickgit.com/) — 顯示 `TODO` 註釋（和其他標記）以識別值得返回以進行改進的代碼區域。
* [CodeKeep](https://codekeep.io) - 用於代碼片段的 Google Keep。組織、發現和共享代碼片段，具有強大的代碼截圖工具，帶有預設模板和鏈接功能。

### CI 和 CD

* [AccessLint](https://github.com/marketplace/accesslint) — AccessLint 將自動化的 Web 可訪問性測試引入您的開發工作流程。它對於開源和教育目的是免費的。
* [appcircle.io](https://appcircle.io) — 適用於 iOS 和 Android 的自動化移動 CI/CD/CT，帶有在線設備模擬器。20 分鐘構建超時（開源為 60 分鐘），單並發免費。
* [appveyor.com](https://www.appveyor.com/) — Windows 的 CD 服務，開源免費
* [Argonaut](https://argonaut.dev/) - 在幾分鐘內在您的雲上部署應用程序和基礎設施。支持在 Kubernetes 和 Lambda 環境中部署自定義和第三方應用程序。免費層允許為 5 個環境和 2 個用戶提供無限的應用程序和部署。
* [bitrise.io](https://www.bitrise.io/) — 適用於原生或混合移動應用程序的 CI/CD。每月 200 次免費構建 10 分鐘構建時間和兩名團隊成員。OSS 項目獲得 45 分鐘的構建時間、+1 並發和無限的團隊規模。
* [buddy.works](https://buddy.works/) — 包含 5 個免費項目和 1 個並發運行的 CI/CD（120 次執行/月）
* [buddybuild.com](https://www.buddybuild.com/) — 在一個無縫的迭代系統中為您的 iOS 和 Android 應用程序構建、部署和收集反饋
* [circleci.com](https://circleci.com/) — 一個並發構建免費
* [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 存儲庫免費
* [codefresh.io](https://codefresh.io) — 終身免費計劃：1 個構建、1 個環境、共享服務器、無限制的公共回購
* [codemagic.io](https://codemagic.io/) - 每月免費 500 分鐘構建
* [codeship.com](https://codeship.com/) — 每月 100 個私有構建，5 個私有項目，開源無限制
* [deployhq.com](https://www.deployhq.com/) — 1 個項目，每日部署 10 次（每月 30 分鐘構建）
* [drone](https://cloud.drone.io/) - Drone Cloud 使開發人員能夠跨多種架構運行持續交付管道 - 包括 x86 和 Arm（32 位和 64 位） - 所有這些都在一個地方
* [LayerCI](https://layerci.com) — 全棧項目的 CI。1 個具有 5GB 內存和 3 個 CPU 的完整堆棧預覽環境。
* [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) — 持續集成服務比較
* [scalr.com](https://scalr.com/) - Terraform 的遠程狀態和操作後端，具有完整的 CLI 支持、與 OPA 的集成和分層配置模型。最多釋放 5 個用戶。
* [semaphoreci.com](https://semaphoreci.com/) — 開源免費，每月 100 次私有構建
* [Squash Labs](https://www.squash.io/) — 為每個分支創建一個 VM，並使您的應用可從唯一的 URL、無限的公共和私有存儲庫、高達 2 GB 的 VM 大小。
* [stackahoy.io](https://stackahoy.io) — 100% 免費。無限的部署、分支和構建
* [styleci.io](https://styleci.io/) - 僅限公共 GitHub 存儲庫
* [Mergify](https://mergify.io) — GitHub 的工作流自動化和合併隊列 — 公共 GitHub 存儲庫免費
* [Integromat](https://www.integromat.com) — 工作流程自動化工具，可讓您使用 UI 連接應用程序並自動化工作流程，它支持許多應用程序和最流行的 API。公共 GitHub 存儲庫免費，免費層級為 100 Mb、1000 次操作和 15 分鐘的最小間隔。
* [Spacelift](https://spacelift.io/) - 基礎設施即代碼的管理平台。免費計劃功能：IaC 協作、Terraform 模塊註冊表、ChatOps 集成、與 Open Policy Agent 的持續資源合規性、使用 SAML 2.0 的 SSO 以及對公共工作池的訪問：最多 200 分鐘/月

### 測試

* [Applitools.com](https://applitools.com/) — 適用於 Web、本機移動和桌面應用程序的智能視覺驗證。與幾乎所有自動化解決方案（如 Selenium 和 Karma）和遠程運行器（Sauce Labs、Browser Stack）集成。免費用於開源。每週檢查點有限的單個用戶的免費套餐。
* [Appetize](https://appetize.io) — 直接在瀏覽器中在此基於雲的 Android 手機/平板電腦模擬器和 iPhone/iPad 模擬器上測試您的 Android 和 iOS 應用程序。免費套餐包括 1 個並發會話，每月使用 100 分鐘。應用程序大小沒有限制。
* [Bird Eats Bug](https://www.birdeatsbug.com/) — 更快（更好）地報告錯誤。使用 Bird 瀏覽器擴展記錄您的屏幕，它將自動捕獲工程師需要調試的技術數據。適合小型團隊的免費套餐。
* [BugBug](https://bugbug.io/) - 用於 Web 應用程序的輕量級測試自動化工具。易於學習，不需要編碼。您可以在自己的計算機上免費運行無限制的測試。支付額外的月費，您還可以獲得云監控和 CI/CD 集成。
* [lambdatest.com](https://www.lambdatest.com/) — selenium 和 cypress 的手動、可視化、屏幕截圖和自動瀏覽器測試，\[開源免費]\(https://www.lambdatest.com/開源跨瀏覽器測試工具）
* [browserstack.com](https://www.browserstack.com/) — 手動和自動瀏覽器測試，[開源免費](https://www.browserstack.com/open-source?ref=pricing)
* [checkbot.io](https://www.checkbot.io/) — 測試您的網站是否遵循 50 多個 SEO、速度和安全最佳實踐的瀏覽器擴展。小型網站的免費套餐。
* [checklyhq.com](https://checklyhq.com) - Checkly 是現代堆棧的 API 和 E2E 監控平台：可編程、靈活且熱愛 JavaScript。為開發人員提供的免費套餐。
* [crossbrowsertesting.com](https://crossbrowsertesting.com) - 雲中的手動、可視化和 Selenium 瀏覽器測試 - [開源免費](https://crossbrowsertesting.com/open-source)
* [cypress.io](https://www.cypress.io/) - 對在瀏覽器中運行的任何東西進行快速、簡單和可靠的測試。Cypress Test Runner 始終是免費和開源的，沒有任何限制和限制。Cypress Dashboard 對最多 5 個用戶的開源項目是免費的。
* [Cypress Recorder by Preflight](https://cypress.preflight.com/) - 在您的瀏覽器上創建 AI 驅動的 Cypress 測試/POM 模型。它是開源的，除了 AI 部分。每月免費進行 5 次測試創建，包括自我修復腳本、電子郵件和可視化測試。
* [everystep-automation.com](https://www.everystep-automation.com/) — 記錄和回放在 Web 瀏覽器中進行的所有步驟並創建腳本，...免費，選項更少
* [Gremlin](https://www.gremlin.com/gremlin-free-software) — Gremlin 的混沌工程工具允許您安全、可靠、簡單地將故障注入您的系統，以便在它們導致面向客戶的問題之前發現弱點. Gremlin Free 提供對多達 5 個主機或容器的關閉和 CPU 攻擊的訪問權限。
* [gridlastic.com](https://www.gridlastic.com/) — Selenium 網格測試，免費計劃多達 4 個同時的 selenium 節點/10 個網格啟動/4,000 分鐘測試/月
* [katalon.com](https://katalon.com) - 提供了一個測試平台，可以幫助各種規模的團隊在不同的測試成熟度級別，包括 Katalon Studio、TestOps（+ 免費可視化測試）、TestCloud 和 Katalon Recorder .
* [loadmill.com](https://www.loadmill.com/) - 通過分析網絡流量自動創建 API 和負載測試。每月免費模擬多達 50 個並髮用戶長達 60 分鐘。
* [preflight.com](https://preflight.com) - 無代碼自動化 Web 測試。在瀏覽器上記錄對 UI 更改具有彈性的測試並在 Windows 機器上運行它們。與您的 CI/CD 集成。免費計劃包括每月 50 次測試運行，包括視頻、HTML 會話等。
* [percy.io](https://percy.io) - 將可視化測試添加到任何 Web 應用程序、靜態站點、樣式指南或組件庫。無限的團隊成員，演示應用程序和無限的項目，5,000 個快照/月。
* [saucelabs.com](https://saucelabs.com/) — 跨瀏覽器測試、Selenium 測試和移動測試，[開源免費](https://saucelabs.com/open-source)
* [snippets.uilicious.com](https://snippets.uilicious.com) - 類似於 CodePen，但用於跨瀏覽器測試。UI-licious 允許編寫用戶故事之類的測試，並提供免費平台 - UI-licious Snippets - 允許您在 Chrome 上免費運行無限數量的測試，無需註冊，每次測試運行最多 3 分鐘。發現錯誤？您可以簡單地將唯一的 url 複製到您的測試中，以準確地向您的開發人員展示如何重現錯誤。
* [testingbot.com](https://testingbot.com/) — Selenium 瀏覽器和設備測試，[開源免費](https://testingbot.com/open-source)
* [Testspace.com](https://testspace.com/) - 用於發布自動化測試結果的儀表板和用於使用 GitHub 將手動測試作為代碼實施的框架。該服務是 [開源免費](https://github.com/marketplace/testspace-com) 每月有 450 個結果。
* [tesults.com](https://www.tesults.com) — 測試結果報告和測試用例管理。與流行的測試框架集成。開源軟件開發人員、個人、教育工作者和小團隊入門可以要求超出基本免費項目的折扣和免費產品。
* [websitepulse.com](https://www.websitepulse.com/tools/) — 各種免費的網絡和服務器工具。
* [qase.io](https://qase.io) - 開發和 QA 團隊的測試管理系統。管理測試用例、編寫測試運行、執行測試運行、跟踪缺陷和衡量影響。免費層包括所有核心功能，500Mb 可用於附件和最多 3 個用戶。
* [knapsackpro.com](https://knapsackpro.com) - 在任何 CI 提供商上使用最佳測試套件並行化加速您的測試。在並行 CI 節點上拆分 Ruby、JavaScript 測試以節省時間。長達 10 分鐘測試文件的免費計劃和開源項目的免費無限計劃。
* [webhook.site](https://webhook.site) - 使用自定義 URL 驗證 webhook、出站 HTTP 請求或電子郵件。臨時 URL 和電子郵件地址始終免費。
* [Vaadin](https://vaadin.com) — 使用 Java 或 TypeScript 構建可擴展的 UI，並使用集成的工具、組件和設計系統來更快地迭代、更好地設計並簡化開發過程。無限項目，5 年免費維護。

### 安全和 PKI

* [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 發現您網絡中的受損系統
* [asgardeo.io](https://wso2.com/asgardeo) - 無縫集成 SSO、MFA、無密碼身份驗證等。包括用於前端和後端應用程序的 SDK。釋放多達 1000 個 MAU 和 5 個身份提供者。
* [atomist.com](https://atomist.com/) — 一種更快速、更方便的自動化各種開發任務的方式。現在處於測試階段。
* [auth0.com](https://auth0.com/) — 為開發 SSO 免費託管。最多 2 個用於閉源項目的社交身份提供者。
* [Authgear](https://www.authgear.com) - 在幾分鐘內為您的應用程序帶來無密碼、OTP、2FA、SSO。包括所有前端。釋放多達 5000 個 MAU。
* [Authress](https://authress.io/) — 身份驗證登錄和訪問控制，任何項目的無限身份提供者。臉書、谷歌、推特等。前 1000 個 API 調用是免費的。
* [Authy](https://authy.com) - 多台設備上的雙重身份驗證 (2FA)，帶有備份。Google Authenticator 的直接替代品。免費進行多達 100 次成功的身份驗證。
* [Bridgecrew](https://bridgecrew.io/) — 由開源工具支持的基礎設施即代碼 (IaC) 安全性 - [Checkov](https://github.com/bridgecrewio/checkov)。核心 Bridgecrew 平台可免費使用多達 50 個 IaC 資源。
* [Clerk.dev](https://clerk.dev/) — 用戶管理、身份驗證、2FA/MFA 以及預構建的 UI 組件。每月最多釋放 500 名活躍用戶。
* [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 安全性和合規性審計和監控
* [Cmd](https://cmd.com/) — 為您的雲或數據中心中的每個 Linux 實例提供實時訪問控制和動態策略實施的安全平台
* [CodeNotary.io](https://www.codenotary.io/) — 具有不可磨滅證據的開源平台，用於公證代碼、文件、目錄或容器
* [crypteron.com](https://www.crypteron.com/) — 雲優先、對開發人員友好的安全平台可防止 .NET 和 Java 應用程序中的數據洩露
* [DAS](https://signup.styra.com/) — Styra DAS 免費，全生命週期策略管理，用於創建、部署和管理開放策略代理 (OPA) 授權
* [Datree](https://www.datree.io/) — 開源 CLI 工具，通過確保清單和 Helm 圖表遵循最佳實踐以及組織的政策來防止 Kubernetes 錯誤配置
* [Dependabot](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模塊的自動依賴更新和 GitHub 操作。
* [DJ Checkup](https://djcheckup.com) — 使用這款免費、自動化的檢查工具掃描您的 Django 站點以查找安全漏洞。從 Pony Checkup 網站分叉。
* [Doppler](https://doppler.com/) — 用於應用程序機密和配置的通用機密管理器，支持同步到各種雲提供商。具有基本訪問控制的 5 位用戶免費。
* [Dotenv](https://dotenv.org/) — 快速、安全地同步您的 .env 文件。停止通過 Slack 和電子郵件等不安全的渠道共享您的 .env 文件，並且再也不會丟失重要的 .env 文件。最多 3 名隊友免費。
* [duo.com](https://duo.com/) — 網站或應用程序的雙重身份驗證 (2FA)。10 個用戶免費，所有身份驗證方法，無限制，集成，硬件令牌。
* [GitGuardian](https://www.gitguardian.com) — 通過自動化的秘密檢測和修復將秘密從源代碼中排除。掃描您的 git 存儲庫以查找 350 多種類型的機密和敏感文件 - 免費供 25 名或更少開發人員的個人和團隊使用。
* [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — 開源的免費 SSL 證書
* [我是否被攻擊了嗎？](https://haveibeenpwned.com) — 用於獲取違規信息的 REST API。
* [hostedscan.com](https://hostedscan.com) — Web 應用程序、服務器和網絡的在線漏洞掃描程序。每月 10 次免費掃描。
* [Internet.nl](https://internet.nl) — 測試現代互聯網標準，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
* [Jumpcloud](https://jumpcloud.com/) — 提供類似於 Azure AD 的目錄即服務、用戶管理、單點登錄和 RADIUS 身份驗證。最多 10 個用戶免費。
* [keychest.net](https://keychest.net) - SSL 到期管理和證書購買與集成 CT 數據庫
* [letsencrypt.org](https://letsencrypt.org/) — 免費的 SSL 證書頒發機構，其證書受到所有主要瀏覽器的信任
* [LoginRadius](https://www.loginradius.com/) — 免費的託管用戶身份驗證服務。電子郵件註冊和 3 個社交服務提供商。
* [logintc.com](https://www.logintc.com/) — 通過推送通知進行的雙重身份驗證 (2FA)，10 位用戶、VPN、網站和 SSH 免費
* [meterian.io](https://www.meterian.io/) - 監控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 項目的依賴項中的安全漏洞。一個私人項目免費，開源項目無限。
* [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在幾分鐘內輕鬆地在您的 Web、移動設備或任何應用程序上實現無密碼身份驗證。
* [Mozilla Observatory](https://observatory.mozilla.org/) — 查找並修復您網站中的安全漏洞。
* [Okta](https://developer.okta.com/) — 用戶管理、身份驗證和授權。每月最多 1000 名活躍用戶免費。
* [onelogin.com](https://www.onelogin.com/) — 身份即服務 (IDaaS)、單點登錄身份提供商、雲 SSO IdP、3 個公司應用程序和 5 個個人應用程序、無限用戶
* [Operous](https://operous.dev/) — 雲實例測試工具，具有一套全面、自動化的最佳實踐、性能和安全性測試套件。免費套餐為 1 位用戶提供 100 分鐘測試時間、10 個測試套件和最多 5 個實例。
* [opswat.com](https://www.opswat.com/) — 計算機、設備、應用程序、配置的安全監控……免費 25 位用戶和 30 天歷史用戶。
* [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/Zero Trust 託管安全平台。具有所有安全功能、無限團隊成員、200 個每日活躍用戶和 25k/mo 權限檢查的永久免費開發者帳戶。
* [pyup.io](https://pyup.io) — 監控 Python 依賴項是否存在安全漏洞並自動更新它們。一個私人項目免費，開源項目無限。
* [quallys.com](https://www.quallys.com/community-edition) — 查找 Web 應用漏洞，審核 OWASP 風險
* [reCAPTCHAMe](https://recaptchame.com/) — 免費的 reCAPTCHA 和 hCAPTCHA 後端服務。無需服務器端編碼。適用於靜態網站。
* [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 違規報告
* [ringcaptcha.com](https://ringcaptcha.com/) — 使用電話號碼作為 id 的工具，免費提供
* [sawolabs.com](https://sawolabs.com/) - 通過在您的應用程序中集成無密碼身份驗證來簡化登錄並改善用戶體驗。每月 5000 次免費認證。
* [seclookup.com](https://seclookup.com/) - Seclookup API 可以豐富 SIEM 中的域威脅指標，提供全面的域名信息，改進威脅檢測和響應。[在這裡](https://account.seclookup.com/) 免費獲取 50K 查詢。
* [snyk.io](https://snyk.io) — 可以找到並修復開源依賴項中的已知安全漏洞。開源項目的無限測試和修復。您的私人項目每月限制為 200 次測試。
* [ssllabs.com](https://www.ssllabs.com/ssltest/) — 非常深入地分析任何 SSL Web 服務器的配置
* [StackHawk](https://www.stackhawk.com/) 在整個管道中自動掃描應用程序，以在安全漏洞投入生產之前發現並修復它們。單個應用程序的無限掃描和環境。
* [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免費的網站安全檢查和惡意軟件掃描程序
* [SuperTokens](https://supertokens.com/) - 原生集成到您的應用程序中的開源用戶身份驗證 - 使您能夠在控制用戶和開發人員體驗的同時快速入門。免費獲得最多 5000 個 MAU。
* [Protectumus](https://protectumus.com) - 適用於 PHP 的免費網站安全檢查、網站防病毒和服務器防火牆 (WAF)。免費套餐中註冊用戶的電子郵件通知。
* [TestTLS.com](https://testtls.com) - 測試 SSL/TLS 服務以獲得安全的服務器配置、證書、鍊等。不限於 HTTPS。
* [threatconnect.com](https://threatconnect.com) — 威脅情報：它專為開始了解網絡威脅情報的個人研究人員、分析師和組織而設計。最多釋放 3 個用戶
* [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — 自動漏洞掃描。免費計劃允許每週 XSS 掃描
* [Ubiq Security](https://ubiqsecurity.com/) — 使用 3 行代碼和自動密鑰管理加密和解密數據。1 個應用程序和每月最多 1,000,000 次加密免費。
* [Virgil Security](https://virgilsecurity.com/) — 用於在您的數字解決方案中實施端到端加密、數據庫保護、物聯網安全等的工具和服務。最多 250 個用戶的應用程序免費。
* [Virushee](https://virushee.com/) — 由混合啟發式和 AI 輔助引擎提供支持的面向隱私的文件/數據掃描。可以使用內部動態沙盒分析。每個文件上傳限制為 50MB
* [Warrant](https://warrant.dev/) — 為您的應用託管企業級授權和訪問控制服務。免費套餐包括每月 100 萬次 API 請求和 1,000 條授權規則。
* [Escape GraphQL Quickscan](https://escape.tech/quickscan) - 一鍵安全掃描您的 GraphQL 端點。免費，無需登錄。

### 管理系統

* [bitnami.com](https://bitnami.com/) — 在 IaaS 上部署準備好的應用程序。免費管理 1 個 AWS 微實例
* [Esper](https://esper.io) — 適用於具有 DevOps 的 Android 設備的 MDM 和 MAM。100 台設備免費，1 個用戶許可證和 25 MB 應用程序存儲。
* [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的設備管理，3 台設備免費
* [Miradore](https://miradore.com) — 設備管理服務。隨時了解您的設備群並免費保護無限數量的設備。免費計劃提供基本功能。
* [moss.sh](https://moss.sh) - 幫助開發人員部署和管理他們的 Web 應用程序和服務器。每月最多釋放 25 次 git 部署
* [runcloud.io](https://runcloud.io/) - 主要針對 PHP 項目的服務器管理。最多可免費使用 1 台服務器。
* [ploi.io](https://ploi.io/) - 服務器管理工具，可輕鬆管理和部署您的服務器和站點。1台服務器免費。

消息和流式傳輸

***

* [Ably](https://www.ably.com/) - 具有存在、持久性和保證交付的實時消息服務。免費計劃包括每月 300 萬條消息、100 個高峰連接和 100 個高峰頻道。
* [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服務。Little Lemur 計劃：最大 100 萬條消息/月，最大 20 個並發連接，最大 100 個隊列，最大 10,000 條排隊消息，不同 AZ 的多個節點
* [connectycube.com](https://connectycube.com) - 無限的聊天消息、p2p 語音和視頻通話、文件附件和推送通知。免費提供高達 20K MAU 的應用程序。
* [courier.com](https://www.courier.com/) — 用於推送、應用內、電子郵件、聊天、短信和其他消息傳遞渠道的單一 API，具有模板管理和其他功能。免費計劃包括 10,000 條消息/月。
* [knock.app](https://knock.app) – 開發人員的通知基礎設施。發送到應用內、電子郵件、SMS、Slack 等多個渠道，並通過單個 API 調用進行推送。免費計劃包括 10,000 條消息/月。
* [pusher.com](https://pusher.com/) — 實時消息服務。免費提供多達 100 個同時連接和 200,000 條消息/天
* [scaledrone.com](https://www.scaledrone.com/) — 實時消息服務。免費提供多達 20 個同時連接和 100,000 個事件/天
* [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作為服務。全球、AWS、GCP 和 Azure。每月 4k 消息大小、50 個活動連接和 5GB 數據，永久免費。
* [cloudkarafka.com](https://www.cloudkarafka.com/) - 免費共享 Kafka 集群，最多 5 個主題，每個主題 10MB 數據和 28 天數據保留。
* [pubnub.com](https://www.pubnub.com/) - 每月 100 萬筆交易的 Swift、Kotlin 和 React 消息傳遞。事務可能包含多條消息。
* [eyeson API](https://developers.eyeson.team/) - 基於WebRTC（SFU，MCU）搭建視頻平台的視頻通信API服務。允許實時數據注入、視頻佈局、錄製、功能齊全的託管 Web UI（快速入門）或自定義 UI 包。有一個 [開發人員免費套餐](https://apiservice.eyeson.com/api-pricing)，每月有 1000 分鐘會議記錄。
* [Upstash Kafka](https://upstash.com/kafka) - 按請求定價的無服務器 Kafka 雲產品。它有一個免費層，每天最多 10000 條消息。
* [webpushr](https://www.webpushr.com/) - 網絡推送通知 - 最多 10k 訂閱者免費，無限制推送通知，瀏覽器內消息
* [Scramjet Cloud Platform Beta](https://www.scramjet.org/#join-beta) - 一個端到端的流處理平台，處於免費測試階段，在測試結束後提供 15 PB 秒的免費計算。

### 日誌管理

* [bugfender.com](https://bugfender.com/) — 每天最多釋放 10 萬條日誌行，24 小時保留
* [humio.com](https://www.humio.com/) — 最多免費 16 GB/天，保留 7 天
* [logdna.com](https://logdna.com) - 單個用戶免費，無保留，無限主機和來源
* [logentries.com](https://logentries.com/) — 每月最多免費 5 GB，保留 7 天
* [loggly.com](https://www.loggly.com/) — 單個用戶免費，200MB/天，保留 7 天
* [logz.io](https://logz.io/) — 每天最多免費 1 GB，保留 1 天
* [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management) — 由 Manage Engine 提供支持的日誌管理服務。免費計劃提供 50 GB 存儲空間和 1 個月的保留期。
* [papertrailapp.com](https://papertrailapp.com/) — 48 小時搜索，7 天存檔，50 MB/月
* [sematext.com](https://sematext.com/logsene) — 每天最多免費 500 MB，保留 7 天
* [sumologic.com](https://www.sumologic.com/) — 每天最多免費 500 MB，保留 7 天
* [logflare.app](https://logflare.app/) — 每個應用每月最多 12,960,000 個條目免費，保留 3 天
* [logtail.com](https://logtail.com/) — 基於 ClickHouse 的 SQL 兼容日誌管理。每月最多免費 1 GB，保留 3 天。
* [crowdin.com](https://crowdin.com/) — 無限的項目、無限的字符串和開源合作者
* [gitlocalize.com](https://gitlocalize.com) - 私有和公共存儲庫免費且無限制
* [Lecto](https://lecto.ai/) - 具有免費層級的機器翻譯 API（30 個免費請求，每個請求 1000 個翻譯字符）。與 Loco Translate Wordpress 插件集成。
* [lingohub.com](https://lingohub.com/) — 最多免費 3 位用戶，對開源始終免費
* [localazy.com](https://localazy.com) - 免費提供 1000 種源語言字符串、無限語言、無限貢獻者、啟動和開源交易
* [Localeum](https://localeum.com) - 最多免費 1000 個字符串，1 個用戶，無限語言，無限項目
* [localizely.com](https://localizely.com/) — 開源免費
* [Loco](https://localise.biz/) — 免費提供多達 2000 個翻譯，無限翻譯，10 種語言/項目，1000 個可翻譯資產/項目
* [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用戶的有限免費版，開源免費
* [POEditor](https://poeditor.com/) — 最多釋放 1000 個字符串
* [SimpleLocalize](https://simplelocalize.io/) - 最多免費 100 個翻譯鍵，無限字符串，無限語言，啟動交易
* [Texterify](https://texterify.com/) - 單個用戶免費
* [Tolgee](https://tolgee.io) - 提供有限翻譯的免費 SaaS 產品，永久免費的自託管版本
* [transifex.com](https://www.transifex.com/) — 開源免費
* [Translation.io](https://translation.io) - 開源免費
* [Translized](https://translized.com) - 最多免費 1000 個字符串，1 個用戶，無限語言，無限項目
* [webtranslateit.com](https://webtranslateit.com/) — 最多釋放 500 個字符串
* [weblate.org](https://weblate.org/) — 對於免費層級的自由項目，最多 10,000 個字符串源是免費的，並且是無限的本地自託管。
* [免費 PO 編輯器](https://pofile.net/free-po-editor) — 所有人免費

### 監控

* [Pingmeter.com](https://pingmeter.com/) - 5 個正常運行時間監視器，間隔 10 分鐘。監控 SSH、HTTP、HTTPS 和任何自定義 TCP 端口。
* [appdynamics.com](https://www.appdynamics.com/) — 24 小時免費指標，應用程序性能管理代理僅限於一個 Java、一個 .NET、一個 PHP 和一個 Node.js
* [appneta.com](https://www.appneta.com/) — 免費，數據保留 1 小時
* [assertible.com](https://assertible.com) — 自動化 API 測試和監控。團隊和個人的免費計劃。
* [blackfire.io](https://blackfire.io/) — Blackfire 是 SaaS 交付的應用程序性能解決方案。免費黑客計劃（僅限 PHP）
* [checklyhq.com](https://checklyhq.com) - 面向開發人員的開源 E2E / 綜合監控和深度 API 監控。包含 5 個用戶和 50k+ 檢查運行的免費計劃。
* [circonus.com](https://www.circonus.com/) — 20 個指標免費
* [cloudsploit.com](https://cloudsploit.com) — AWS 安全和配置監控。免費：無限制的按需掃描、無限制的用戶、無限制的存儲帳戶。訂閱：自動掃描、API訪問等。
* [cronitor.io](https://cronitor.io/) - 對 cron 作業、網站、API 等的性能洞察和正常運行時間監控。帶 5 台顯示器的免費套餐。
* [datadoghq.com](https://www.datadoghq.com/) — 最多 5 個節點免費
* [deadmanssnitch.com](https://deadmanssnitch.com/) — 監控 cron 作業。1 個免費告密者（監視器），如果您推薦其他人註冊，則更多
* [economize.cloud](https://economize.cloud) — Economize 通過組織雲資源、優化和報告相同的內容來幫助揭開雲基礎設施成本的神秘面紗。每月在 Google Cloud Platform 上花費高達 5000 美元即可免費使用。
* [elastic.co](https://www.elastic.co/solutions/apm) — 為 JS 開發人員提供即時性能洞察。免費提供 24 小時數據保留
* [freeboard.io](https://freeboard.io/) — 公共項目免費。物聯網 (IoT) 項目的儀表板
* [freshworks.com](https://www.freshworks.com/website-monitoring/) — 以 1 分鐘的間隔監控 50 個 URL，包含 10 個全球位置和 5 個免費的公共狀態頁面
* [gitential.com](https://gitential.com) — 軟件開發分析平台。免費：無限的公共存儲庫，無限的用戶，私人存儲庫的免費試用。可用於企業的本地版本。
* [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud 是一個可組合的可觀察性平台，將指標和日誌與 Grafana 集成。免費：3 個用戶，10 個儀表板，100 個警報，Prometheus 和 Graphite 中的指標存儲（10,000 系列，14 天保留），Loki 中的日誌存儲（50 GB 日誌，14 天保留）
* [healthchecks.io](https://healthchecks.io) — 監控您的 cron 作業和後台任務。最多可免費進行 20 次檢查。
* [inspector.dev](https://www.inspector.dev) - 不到一分鐘的完整實時監控儀表板，永久免費。
* [instrumentalapp.com](https://instrumentalapp.com) - 美觀且易於使用的應用程序和服務器監控，多達 500 個指標和 3 小時的免費數據可見性
* [keychest.net/speedtest](https://keychest.net/speedtest) - 針對 Digital Ocean 的獨立速度測試和 TLS 握手延遲測試
* [letsmonitor.org](https://letsmonitor.org) - SSL 監控，最多可免費使用 5 台顯示器
* [loader.io](https://loader.io/) — 有限制的免費負載測試工具
* [meercode.io](https://meercode.io/) — Meercode 是您的 CI/CD 構建的終極監控儀表板。免費提供開源和 1 個私有存儲庫。
* [netdata.cloud](https://www.netdata.cloud/) — Netdata 是一個開源工具，旨在收集實時指標。快速增長的產品。也可以在github上找到！
* [newrelic.com](https://www.newrelic.com) — New Relic 可觀察性平台旨在幫助工程師創建更完美的軟件。從單體應用到無服務器，您可以檢測所有內容，然後分析、排除故障並優化您的整個軟件堆棧。免費套餐提供每月 100GB 的免費數據攝取、1 個免費的完全訪問用戶和無限的免費基本用戶。
* [nixstats.com](https://nixstats.com) - 一台服務器免費。電子郵件通知、公共狀態頁面、60 秒間隔等。
* [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot 是基於 JS 的 Web 應用程序和網站的可靠正常運行時間監視器。5 次正常運行時間檢查（針對靜態網站和 API），間隔 5 分鐘，1 次瀏覽器檢查，間隔 15 分鐘。還提供自動化的公共狀態頁面（支持第 3 方正常運行時間監控）。最多 3 位用戶免費，通過 Slack、Discord 和電子郵件發送警報。
* [opsgenie.com](https://www.opsgenie.com/) — 用於運行始終在線服務的強大警報和待命管理。最多釋放 5 個用戶。
* [paessler.com](https://www.paessler.com/) — 強大的基礎設施和網絡監控解決方案，包括警報、強大的可視化功能和基本報告。釋放多達 100 個傳感器。
* [syagent.com](https://syagent.com/) — 非商業免費服務器監控服務、警報和指標。
* [pagertree.com](https://pagertree.com/) - 用於警報和待命管理的簡單界面。最多釋放 5 個用戶。
* [pingbreak.com](https://pingbreak.com/) — 現代正常運行時間監控服務。檢查無限 URL 並通過 Discord、Slack 或電子郵件獲取停機通知。
* [pingpong.one](https://pingpong.one/) — 具有監控功能的高級狀態頁面平台。免費套餐包括一個帶有 SSL 子域的公共可定制狀態頁面。專業計劃免費提供給開源項目和非營利組織。
* [sematext.com](https://sematext.com/) — 免費 24 小時指標、無限數量的服務器、10 個自定義指標、500,000 個自定義指標數據點、無限的儀表板、用戶等。
* [sitemonki.com](https://sitemonki.com/) — 網站、域、Cron 和 SSL 監控，每個類別免費 5 個監控器
* [skylight.io](https://www.skylight.io/) — 前 100,000 個請求免費（僅限 Rails）
* [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能監控 API，檢查 Ping、DNS 等。
* [stathat.com](https://www.stathat.com/) — 免費開始使用 10 個統計數據，沒有過期
* [statuscake.com](https://www.statuscake.com/) — 網站監控，無限制的免費測試
* [statusgator.com](https://statusgator.com/) — 狀態頁面監控，3 個免費監控
* [thousandeyes.com](https://www.thousandeyes.com/) — 網絡和用戶體驗監控。免費提供主要網絡服務的 3 個位置和 20 個數據源
* [thundra.io/apm](https://www.thundra.io/apm) — 應用程序監控和調試。擁有每月最多 25 萬次調用的免費套餐。
* [uptimerobot.com](https://uptimerobot.com/) — 網站監控，免費 50 台顯示器
* [uptimetoolbox.com](https://uptimetoolbox.com/) — 免費監控 5 個網站，60 秒間隔，公開狀態頁面。
* [zenduty.com](https://www.zenduty.com/) — 用於網絡運營、站點可靠性工程和 DevOps 團隊的端到端事件管理、警報、待命管理和響應編排平台。最多 5 位用戶免費。
* [asayer.io](https://asayer.io/pricing.html) — openreplay 的託管版本，一種開源會話重播（FullStory 和 LogRocket 的替代品）。每月免費 1k 次會話，保留 14 天
* [lean20.com](https://lean20.com/product/status/) - 事件報告的公共狀態頁面。100% 免費。
* [instatus.com](https://instatus.com) - 在 10 秒內獲得漂亮的狀態頁面。無限訂閱和無限團隊永遠免費。
* [Squadcast.com](https://squadcast.com) - Squadcast 是一種端到端的事件管理軟件，旨在幫助您推廣 SRE 最佳實踐。永久免費計劃可供多達 10 位用戶使用。
* [RoboMiri.com](https://robomiri.com/) - RoboMiri 是一款穩定的正常運行時間監控器，提供多種監控器：cronjob、關鍵字、網站、端口、ping。25 次正常運行時間檢查，每 3 分鐘免費檢查一次。通過電話、短信、電子郵件和 Web Hook 發出警報。
* [Better Stack](https://betterstack.com/better-uptime) - 單一產品中的正常運行時間監控、事件管理、待命調度/警報和狀態頁面。免費計劃中包含 10 個具有 3 分鐘檢查頻率和狀態頁面的監視器。

崩潰和異常處理

***

* [CatchJS.com](https://catchjs.com/) - 帶有屏幕截圖和點擊軌蹟的 JavaScript 錯誤跟踪。對開源項目免費。
* [bugsnag.com](https://www.bugsnag.com/) — 初次試用後每月最多 2,000 個錯誤免費
* [elmah.io](https://elmah.io/) — Web 開發人員的錯誤記錄和正常運行時間監控。開源項目的免費小型企業訂閱。
* [exceptionless](https://exceptionless.com) — 實時錯誤、功能、日誌報告等。每月/1 位用戶可免費參加 3k 次活動。開源且易於自託管，可無限使用。
* [GlitchTip](https://glitchtip.com/) — 簡單的開源錯誤跟踪。與開源 Sentry SDK 兼容。每月免費舉辦 1000 場活動，或者可以不受限制地自行舉辦活動
* [honeybadger.io](https://www.honeybadger.io) - 異常、正常運行時間和 cron 監控。小型團隊和開源項目免費（每月 12,000 個錯誤）。
* [memfault.com](https://memfault.com) — 用於設備可觀察性和調試的雲平台。[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp) 和 \[Laird]\(https:// /app.memfault.com/register-laird) 設備。
* [rollbar.com](https://rollbar.com/) — 異常和錯誤監控，每月 5,000 個錯誤的免費計劃，無限用戶，30 天保留
* [sentry.io](https://sentry.io/) — Sentry 實時跟踪應用程序異常，有一個小的免費計劃。每月 5k 錯誤/1 位用戶免費，如果自託管則不受限制使用

### 搜索

* [algolia.com](https://www.algolia.com/) — 託管的 search-as-you-type（即時）。免費黑客計劃多達 10,000 個文檔和 100,000 次操作。更大的免費計劃可用於社區/開源項目
* [bonsai.io](https://bonsai.io/) — 免費 1 GB 內存和 1 GB 存儲空間
* [searchly.com](http://www.searchly.com/) — 免費 2 個索引和 20 MB 存儲空間
* [pagedart.com](https://pagedart.com/) - AI 搜索即服務，免費套餐包括 1000 個文檔，50000 次搜索。對於有價值的項目，更大的免費層是可能的。

### 電子郵件

* [10minutemail](https://10minutemail.com) - 用於測試的免費臨時電子郵件。
* [AnonAddy](https://anonaddy.com) - 開源匿名郵件轉發，免費創建無限郵件別名
* [Antideo](https://www.antideo.com) — 每小時 10 個 API 請求，用於免費套餐中的電子郵件驗證、IP 和電話號碼驗證。無需信用卡。
* [biz.mail.ru](https://biz.mail.ru/) — 5,000 個郵箱，每個郵箱 25 GB，每個自定義域使用 DNS 託管
* [Bump](https://bump.email/) - 免費 10 個 Bump 電子郵件地址，1 個自定義域
* [Burnermail](https://burnermail.io/) – 免費 5 個 Burner 電子郵件地址、1 個郵箱、7 天郵箱歷史
* [Buttondown](https://buttondown.email/) — 通訊服務。多達 1,000 名免費訂閱者
* [CloudMailin](https://www.cloudmailin.com/) - 通過 HTTP POST 和事務出站接收電子郵件 - 每月 10,000 封免費電子郵件
* [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 面向開發人員的電子郵件驗證和驗證 API，每月 2,000 個免費 API 請求
* [Contact.do](https://contact.do/) - 鏈接中的聯繫表格（聯繫表格有點） - 完全免費！
* [debugmail.io](https://debugmail.io/) — 易於開發人員使用的測試郵件服務器
* [DNSExit](https://dnsexit.com/) - 在您的域下最多可免費使用 2 個電子郵件地址，並提供 100MB 的存儲空間。IMAP、POP3、SMTP、SPF/DKIM 支持。
* [Email Temporanee](https://emailtemporanee.com/) - 易於使用的免費無限一次性臨時電子郵件地址（臨時電子郵件）。自動過期，即使你可以設置它的一天。
* [EmailLabs.io](https://emaillabs.io/en) — 每月免費發送多達 24 000 封電子郵件。
* [elasticemail.com](https://elasticemail.com) — 每天 100 封免費電子郵件。通過 API 以 0.09 美元的價格發送 1,000 封電子郵件（即用即付）。
* [EmailOctopus](https://emailoctopus.com) - 每月最多 2,500 名訂閱者和 10,000 封電子郵件免費
* [Eva](https://eva.pingutil.com) — 每天使用 REST API 免費驗證 500 萬封電子郵件。無需註冊。
* [fakermail.com](https://fakermail.com/) — 免費的臨時電子郵件，用於測試存儲的最後 100 個電子郵件帳戶。
* [forwardemail.net](https://forwardemail.net) — 自定義域的免費電子郵件轉發。使用您的域名創建和轉發無限數量的電子郵件地址（**注意**：如果您使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、 .loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work 頂級域名（由於垃圾郵件）
* [ImprovMX](https://improvmx.com) – 免費郵件轉發
* [inboxkitten.com](https://inboxkitten.com/) - 免費的臨時/一次性電子郵件收件箱，最多可自動刪除 3 天的電子郵件。開源，可以自託管。
* [inumbo.com](http://inumbo.com/) — 基於 SMTP 的垃圾郵件過濾器，10 位用戶免費
* [kickbox.io](https://kickbox.io/) — 免費驗證 100 封電子郵件，提供實時 API
* [mail.gw](https://mail.gw) — 10 分鐘郵件。免費匿名臨時電子郵件，沒有義務。
* [mail.tm](https://mail.tm) — 具有用戶友好界面的一次性電子郵件。無需註冊。
* [mailazy.com](https://mailazy.com/) — Mailazy 是您唯一需要的簡單交易電子郵件服務。10500 封電子郵件/月永久免費（350 封電子郵件/天發送限制）。
* [mail-tester.com](https://www.mail-tester.com) — 測試電子郵件的 dns/spf/dkim/dmarc 設置是否正確，每月免費 20
* [dkimvalidator.com](https://dkimvalidator.com/) - 測試電子郵件的 dns/spf/dkim/dmarc 設置是否正確，roundsphere.com 提供免費服務
* [mailboxlayer.com](https://mailboxlayer.com/) — 面向開發人員的電子郵件驗證和驗證 JSON API。1,000 個免費 API 請求/月
* [mailcatcher.me](https://mailcatcher.me/) — 捕獲郵件並通過 Web 界面提供服務
* [mailchimp.com](https://mailchimp.com/) — 2,000 名訂閱者和 12,000 封電子郵件/月免費
* [MailerLite.com](https://www.mailerlite.com) — 1,000 名訂閱者/月，12,000 封電子郵件/月免費
* [MailerSend.com](https://www.mailersend.com) — 電子郵件 API、SMTP、12,000 封電子郵件/月免費用於交易電子郵件
* [mailinator.com](https://www.mailinator.com/) — 免費、公共的電子郵件系統，您可以在其中使用任何您想要的收件箱
* [mailjet.com](https://www.mailjet.com/) — 6,000 封電子郵件/月免費（每日發送限制 200 封電子郵件）
* [mailkitchen](https://www.mailkitchen.com/) — 終身免費，無需承諾，每月 10,000 封電子郵件，每天 1,000 封電子郵件
* [mailmenot.io](https://mailmenot.io) — 免費的一次性臨時電子郵件服務，能夠添加多個電子郵件地址
* [Mailnesia](https://mailnesia.com) - 免費的臨時/一次性電子郵件，自動訪問註冊鏈接。
* [mailsac.com](https://mailsac.com) - 用於臨時電子郵件測試的免費 API、免費公共電子郵件託管、出站捕獲、email-to-slack/websocket/webhook（每月 1,500 個 API 限制）
* [Mailtie.com](https://mailtie.com/) - 您的域的免費電子郵件轉發。無需註冊。永遠免費。
* [mailtrap.io](https://mailtrap.io/) — 用於開發的假 SMTP 服務器，免費計劃有 1 個收件箱，50 封郵件，沒有團隊成員，2 封電子郵件/秒，沒有轉發規則
* [mailvalidator.io](https://mailvalidator.io/) - 每月免費驗證 300 封電子郵件，提供批量處理的實時 API
* [mail7.io](https://www.mail7.io/) — QA 開發人員的免費臨時電子郵件地址。使用 Web 界面或 API 立即創建電子郵件地址
* [mohmal.com](https://www.mohmal.com/en) — 一次性臨時電子郵件
* [moosend.com](https://moosend.com/) — 郵件列表管理服務。為初創公司提供 6 個月的免費帳戶
* [Mutant Mail](https://www.mutantmail.com/) – 免費 10 個電子郵件 ID、1 個域、1 個郵箱。所有電子郵件 ID 的單個郵箱。
* [Outlook.com](https://outlook.live.com/owa/) - 免費的個人電子郵件和日曆
* [Parsio.io](https://parsio.io) — 免費電子郵件解析器（轉發電子郵件，提取數據，將其發送到您的服務器）
* [pepipost.com](https://pepipost.com) — 第一個月免費發送 30k 封電子郵件，然後每天免費發送前 100 封電子郵件
* [phplist.com](https://phplist.com/) — 託管版本允許每月免費發送 300 封電子郵件
* [postmarkapp.com](https://postmarkapp.com/) - 100 封電子郵件/月免費，無限制的 DMARC 每週摘要
* [QuickEmailVerification](https://quickemailverification.com) — 在免費套餐中每天免費驗證 100 封電子郵件以及 DEA 檢測器、DNS 查找、SPF 檢測器等其他免費 API。
* [發件人](https://www.sender.net) 每月最多 15 000 封電子郵件 - 最多 2 500 名訂閱者
* [sendgrid.com](https://sendgrid.com/) — 每天 100 封電子郵件和 2,000 個免費聯繫人
* [sendinblue.com](https://www.sendinblue.com/) — 9,000 封電子郵件/月免費
* [sendpulse.com](https://sendpulse.com) — 50 封電子郵件/小時免費，前 12,000 封電子郵件/月免費
* [socketlabs.com](https://www.socketlabs.com) - 第一個月免費發送 40k 封電子郵件，然後每月免費發送前 2000 封電子郵件
* [sparkpost.com](https://www.sparkpost.com/) — 前 500 封電子郵件/月免費
* [Substack](https://substack.com) — 無限制的免費通訊服務。收費時開始付款。
* [Tempmailo](https://tempmailo.com/) - 無限制的免費臨時電子郵件地址。兩天后自動過期。
* [HotTempMail](https://hottempmail.com/) - 無限制的免費臨時電子郵件或一次性臨時電子郵件地址。一天后自動過期。
* [temp-mail.io](https://temp-mail.io) — 免費的一次性臨時電子郵件服務，一次發送多封電子郵件並轉發
* [temp-mail.org](https://temp-mail.org) — 使用 REST API 的臨時、安全、匿名、免費、一次性電子郵件地址，每天免費從其一次性郵箱中獲取 100 封電子郵件。
* [臨時郵件](https://tempmailers.com) — 臨時、一次性、私有域和免費電子郵件系統。
* [testmail.app](https://testmail.app/) - 使用無限郵箱和 GraphQL API 自動化端到端電子郵件測試。100 封電子郵件/月永久免費，開源無限免費。
* [tinyletter.com](https://tinyletter.com/) — 5,000 名訂閱者/月免費
* [trashmail.com](https://www.trashmail.com) - 具有轉發和自動地址到期功能的免費一次性電子郵件地址
* [Validator.Pizza](https://www.validator.pizza/) — 檢測一次性電子郵件的免費 API
* [Verifalia](https://verifalia.com/email-verification-api) — 帶有郵箱確認和一次性電子郵件地址檢測器的實時電子郵件驗證 API；每天 25 次免費電子郵件驗證。
* [verimail.io](https://verimail.io/) — 批量和 API 電子郵件驗證服務。100 次免費驗證/月
* [yopmail.fr](https://www.yopmail.fr/en/) — 一次性電子郵件地址
* [Zoho](https://www.zoho.com) — 最初是一家電子郵件提供商，但現在提供一套服務，其中一些服務有免費計劃。具有免費計劃的服務列表：
  * [電子郵件](https://zoho.com/mail) 5 位用戶免費。5GB/用戶和 25MB 附件限制，1 個域。
  * [Sprints](https://zoho.com/sprints) 5 個用戶、5 個項目和 500MB 存儲空間免費。
  * [Docs](https://zoho.com/docs) — 5 位用戶免費，1 GB 上傳限制和 5 GB 存儲空間。Zoho Office Suite (Writer,Sheets & Show) 與它捆綁在一起。
  * [項目](https://zoho.com/projects) — 3 個用戶免費，2 個項目和 10 MB 附件限制。相同的計劃適用於 [Bugtracker](https://zoho.com/bugtracker)。
  * [連接](https://zoho.com/connect) — 25 位用戶免費團隊協作，包含 3 個組、3 個自定義應用程序、3 個板、3 個手冊、10 個集成以及頻道、活動和論壇。
  * [會議](https://zoho.com/meeting) — 最多 3 名會議參與者和 10 名網絡研討會參與者的會議。
  * [Vault](https://zoho.com/vault) — 個人免費密碼管理。
  * [Showtime](https://zoho.com/showtime) — 另一個會議軟​​件，用於培訓最多 5 名與會者的遠程會議。
  * [Notebook](https://zoho.com/notebook) — Evernote 的免費替代品。
  * [Wiki](https://zoho.com/wiki) — 3 位用戶免費，擁有 50 MB 存儲空間、無限頁面、zip 備份、RSS 和 Atom 提要、訪問控制和可定制的 CSS。
  * [訂閱](https://zoho.com/subscriptions) — 為 20 位客戶/訂閱和 1 位用戶免費提供定期計費管理，所有付款託管均由 Zoho 自己完成。存儲最後 40 個訂閱指標
  * [結帳](https://zoho.com/checkout) — 產品計費管理，包含 3 頁和最多 50 次付款。
  * [Desk](https://zoho.com/desk) — 具有 3 個代理和私人知識庫的客戶支持管理、電子郵件票證。與 [Assist](https://zoho.com/assist) 集成，用於 1 名遠程技術人員和 5 台無人值守的計算機。
  * [Cliq](https://zoho.com/cliq) — 具有 100 GB 存儲空間、無限用戶、每個頻道 100 個用戶和 SSO 的團隊聊天軟件。
  * [活動](https://zoho.com/campaigns)
  * [表格](https://zoho.com/forms)
  * [簽名](https://zoho.com/sign)
  * [調查](https://zoho.com/surveys)
  * [預訂](https://zoho.com/bookings)
  * [分析](https://zoho.com/analytics)
* [SimpleLogin](https://simplelogin.io/) – 開源、可自我託管的電子郵件別名/轉發解決方案。免費5個別名，無限帶寬，無限回复/發送。教育人員（學生、研究人員等）免費。
* [EmailJS](https://www.emailjs.com/) - 這不是一個完整的電子郵件服務器，這只是一個電子郵件客戶端，您可以使用它直接從客戶端發送電子郵件而不會暴露您的憑據，免費層有：每月 200 個請求、2 個電子郵件模板、最大 50Kb 的請求、有限的聯繫歷史記錄。
* [Takeout](https://takeout.bysourfruit.com) - 不斷更新的電子郵件服務，讓發送電子郵件變得非常容易。每月免費發送 500 封交易電子郵件。

### 字體

* [dafont](https://www.dafont.com/) - 本網站提供的字體是其作者的財產，並且是免費軟件、共享軟件、演示版或公共領域。
* [Everything Fonts](https://everythingfonts.com/) - 提供多種工具；@font-face，單位轉換器，字體提示和字體提交者。
* [Font Squirrel](https://www.fontsquirrel.com/) - 獲得商業作品許可的免費字體。手工選擇這些字體並以易於使用的格式呈現。
* [Google 字體](https://fonts.google.com/) - 許多免費字體可以通過下載或 Google 的 CDN 鏈接輕鬆快速地安裝在網站中。
* [FontGet](https://www.fontget.com/) - 有多種字體可供下載並用標籤整齊地排序。
* [Fontshare](https://www.fontshare.com/) - 是一項免費的字體服務。這是一個不斷增長的專業級字體集合，100% 免費供個人和商業使用。
* [Befonts](https://befonts.com/) - 提供多種 unqiue 字體供個人或商業使用。
* [網絡字體](https://fontofweb.com/) - 識別網站上使用的所有字體及其使用方式。
* [兔子](https://bunny.net)
  * [Bunny Fonts](https://fonts.bunny.net/) - 所有帶有 Google Fonts 插件兼容 API 的 Google Fonts。隱私導向！
  * [Bunny DNS](https://bunny.net/dns/) - DNS 託管，2000 萬次免費查詢

### 表格

* [FabForm](https://fabform.io/) - 智能開發者的表單後端平台。免費計劃允許每月提交 250 份表格。友好的現代 GUI。與 Google Sheets、Airtable、Slack、Email 等集成。
* [Form.taxi](https://form.taxi/) — HTML 表單提交的端點。通過通知、垃圾郵件攔截器和符合 GDPR 的數據處理。基本使用的免費計劃。
* [Formcake.com](https://formcake.com) - 開發人員的表單後端，免費計劃允許無限的表單，100 個提交，Zapier 集成。不需要庫或依賴項。
* [Formcarry.com](https://formcarry.com) - HTTP POST 表單端點，免費計劃允許每月 100 次提交。
* [formingo.co](https://www.formingo.co/)- 用於靜態網站的簡單 HTML 表單，無需註冊帳戶即可免費使用。免費計劃允許每月 500 次提交，可自定義回復電子郵件地址。
* [FormKeep.com](https://www.formkeep.com/) - 無限表單，每月提交 50 次，垃圾郵件保護，電子郵件通知和可以導出 HTML 的拖放設計器。其他功能包括自定義字段規則、團隊以及與 Google 表格、Slack、ActiveCampaign 和 Zapier 的集成。
* [formlets.com](https://formlets.com/) — 在線表單、無限單頁表單/月、100 個提交/月、電子郵件通知。
* [formrocket.me](https://www.formrocket.me) - HTML 表單變得簡單，無限制的表單和響應。附帶 Discord 通知等。
* [formspark.io](https://formspark.io/) - 表單到電子郵件服務，免費計劃允許無限制的表單，每月 250 份提交，客戶支持團隊的支持。
* [Formspree.io](https://formspree.io/) — 使用 HTTP POST 請求發送電子郵件。免費層級限制為每個表單每月 50 次提交。
* [Formsubmit.co](https://formsubmit.co/) — HTML 表單的簡單表單端點。永遠免費。無需註冊。
* [getform.io](https://getform.io/) - 設計者和開發者的表單後端平台，1個表單，50個提交，單個文件上傳，100MB文件存儲。
* [HeroTofu.com](https://herotofu.com/) - 帶有機器人檢測和加密存檔的表單後端。通過 UI 將提交轉發到電子郵件、Slack 或 Zapier。使用您自己的前端，無需服務器代碼。免費計劃每月提供無限的表格和 100 次提交。
* [HeyForm.net](https://heyform.net/) - 拖放在線表單生成器。免費層可讓您創建無限的表單並收集無限的提交。帶有預建模板、反垃圾郵件和 100MB 文件存儲。
* [Hyperforms.app](https://hyperforms.app/) — 在幾秒鐘內創建表單到電子郵件等，無需後端代碼。個人帳戶每月最多可免費為您提供 50 份表單提交。
* [Kwes.io](https://kwes.io/) - 功能豐富的表單端點。適用於靜態網站。免費計劃包括最多 1 個網站，每月最多 50 個提交。
* [Pageclip](https://pageclip.co/) - 免費計劃允許一個站點、一個表單、每月 1,000 次提交。
* [Qualtrics 調查](https://qualtrics.com/free-account) — 使用這個一流的工具創建專業表格和調查。50 多個專家設計的調查模板。免費帳戶限制為 1 個活動調查、100 個回复/調查和 8 種回复類型。
* [smartforms.dev](https://smartforms.dev/) - 為您的網站提供強大而簡單的表單後端，永久免費計劃允許每月提交 50 次，250MB 文件存儲，Zapier 集成，CSV/JSON 導出，自定義重定向，自定義響應頁面、Telegram 和 Slack 機器人、單個電子郵件通知。
* [staticforms.xyz](https://www.staticforms.xyz/) - 免費集成 HTML 表單，無需任何服務器端代碼。用戶提交表單後，將向您的註冊地址發送一封包含表單內容的電子郵件。
* [stepFORM.io](https://stepform.io) - 測驗和表單生成器。免費計劃有 5 個表格，每個表格最多 3 個步驟，每月 50 個回复。
* [Typeform.com](https://www.typeform.com/) — 在網站上包含設計精美的表單。免費計劃每個表單只允許 10 個字段和每月 100 個響應。
* [WaiverStevie.com](https://waiverstevie.com) - 帶有 REST API 的電子簽名平台。使用 webhook 接收通知。免費計划水印簽名文件，但允許無限信封+簽名。
* [Web3Forms](https://web3forms.com) - 靜態和 JAMStack 網站的聯繫表格，無需編寫後端代碼。免費計劃允許每月不限表格、不限域和 250 次提交。
* [WebAsk](https://webask.io) - 調查和表單生成器。免費計劃每個帳戶有 3 個調查，每月 100 個回复，每個調查 10 個元素。
* [Wufoo](https://www.wufoo.com/) - 在網站上使用的快速表格。免費計劃每月有 100 次提交的限制。
* [formpost.app](https://formpost.app) - 免費、無限制的表單到電子郵件服務。免費設置自定義重定向、自動響應、webhook 等。

### CDN 和保護

* [bootstrapcdn.com](https://www.bootstrapcdn.com/) — bootstrap、bootswatch 和 fontawesome.io 的 CDN
* [cdnjs.com](https://cdnjs.com/) — 簡單。快速地。可靠的。最好的內容交付。cdnjs 是一項免費的開源 CDN 服務，受到超過 11% 的網站的信任，由 Cloudflare 提供支持。
* [Cloudflare](https://www.cloudflare.com/)
  * CDN 以及免費 SSL
  * 無限數量域的免費 DNS
  * 防火牆規則和頁面規則
  * 分析
  * 郵件轉發
  * [Cloudflare Pages](https://pages.cloudflare.com/) — 免費網絡託管（JAMstack 平台）供前端開發人員協作和部署網站。一次構建 1 個，每月 500 個構建，無限站點，無限請求，無限帶寬。
  * [Cloudflare Workers](https://workers.cloudflare.com/) — 在 Cloudflare 的全球網絡上免費部署無服務器代碼。每天有 100,000 個使用 workers.dev 子域的免費請求。
  * [快速隧道](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare) — 創建從您的服務器到可公開訪問、隨機生成的 trycloudflare.com 的隧道領域。無需帳戶。
* [Combinatronics](https://combinatronics.com/) - 將您的 Github 託管資產（圖像、CSS、JS 等）轉換為 CDN 資產。甚至可以渲染 HTML 文件，例如 [例如來自這個 repo](https://combinatronics.com/ripienaar/free-for-dev/master/index.html)。類似於 rawgit.com 和 raw.githack.com。
* [developers.google.com](https://developers.google.com/speed/libraries/) — Google 託管庫是最流行的開源 JavaScript 庫的內容分發網絡
* [GraphCDN](https://graphcdn.io/) - 擴展、檢查和保護您的 GraphQL API。每月 500 萬次免費請求。
* [Jotcode](https://jotcode.io) - 用於託管簡單腳本、API 和服務器的無服務器平台。免費計劃允許每月運行 100 個腳本
* [jsdelivr.com](https://www.jsdelivr.com/) — 一個免費、快速、可靠的開源 CDN。支持 npm、GitHub、WordPress、Deno 等。
* [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 託管流行的第三方 JavaScript 庫，例如 jQuery，讓您可以輕鬆添加它們到您的 Web 應用程序
* [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免費 DDoS 保護和 SSL 證書
* [PageCDN.com](https://pagecdn.com/) - 為所有人提供免費的公共 CDN，為開源/非營利組織提供免費的私有 CDN。
* [Skypack](https://www.skypack.dev/) — 100% 原生 ES 模塊 JavaScript CDN。每個域每月 100 萬次請求免費。
* [raw.githack.com](https://raw.githack.com/) — **rawgit.com** 的現代替代品，它只是使用 Cloudflare 託管文件
* [section.io](https://www.section.io/) — 一種啟動和管理完整 Varnish 緩存解決方案的簡單方法。據說一個網站永久免費
* [statically.io](https://statically.io/) — Git repos（GitHub、GitLab、Bitbucket）、WordPress 相關資產和圖像的 CDN
* [toranproxy.com](https://toranproxy.com/) — Packagist 和 GitHub 的代理。永遠不會失敗的CD。免費供個人使用，1個開發者，不支持
* [UNPKG](https://unpkg.com/) — npm 上所有內容的 CDN
* [weserv](https://images.weserv.nl/) — 圖像緩存和調整大小服務。使用全球緩存即時處理圖像。
* [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免費 DDoS 防護
* [Gcore](https://gcorelabs.com/)
  * [CDN](https://gcorelabs.com/cdn/) — 全球內容交付網絡，每月免費 1 TB 和 100 萬次請求。
  * [DNS 託管](https://gcorelabs.com/dns/) — 免費 DNS 託管。

### PaaS

* [anvil.works](https://anvil.works) - 只有 Python 的 Web 應用程序開發。無限應用的免費套餐。
* [appharbor.com](https://appharbor.com/) — 一種 .Net PaaS，提供 1 個免費工作者
* [configure.it](https://www.configure.it/) — 移動應用開發平台，2個項目免費，功能有限但無資源限制
* [codenameone.com](https://www.codenameone.com/) — 適用於 Java/Kotlin 開發人員的開源、跨平台、移動應用程序開發工具鏈。免費用於商業用途，項目數量不限
* [Cyclic](https://www.cyclic.sh) - 全棧應用託管 - 推送到 Github 以構建和部署 Javascript/Node.js 應用。包括：身份驗證、Cron 作業、自定義域、數據庫、存儲和流日誌。付費計劃包括：基於分支的環境、多區域部署和增加限制。
* [Deno Deploy](https://deno.com/deploy) - 在全球範圍內運行 JavaScript、TypeScript 和 WebAssembly 的分佈式系統。免費套餐包括每天 100,000 個請求和每月 100 GiB 數據傳輸。
* [Deta](https://www.deta.sh) – 免費部署無限數量的 Node.js 和 Python 應用程序。包括免費的數據庫、身份驗證和電子郵件。
* [domcloud.co](https://domcloud.co) – Linux 託管服務，還為 CI/CD 提供 GitHub、SSH 和 MariaDB/Postgres 數據庫。免費版具有 1 GB 存儲空間和 1 GB 網絡/月限制，並且僅限於免費域。
* [encore.dev](https://encore.dev/) — 使用靜態分析提供自動基礎設施、樣板免費代碼等的後端框架。包括用於愛好項目的免費云託管。
* [gigalixir.com](https://gigalixir.com/) - Gigalixir 為 Elixir/Phoenix 應用程序提供 1 個永不休眠的免費實例，以及限制為 2 個連接、10、000 行且無備份的免費層級 PostgreSQL 數據庫.
* [Glitch](https://glitch.com/) — 免費的公共託管，具有代碼共享和實時協作等功能。免費計劃有 1000 小時/月的限制。
* [Krucible](https://usekrucible.com) — Krucible 是一個用於創建用於測試和開發的 Kubernetes 集群的平台。免費套餐帳戶每月提供 25 個集群小時。
* [Mendix](https://www.mendix.com/) — 企業快速應用程序開發，支持無限用戶的無限數量的免費沙盒環境，每個應用程序 0.5 GB 存儲和 1 GB RAM。免費層也允許使用 Studio 和 Studio Pro IDE。
* [m3o.com](https://m3o.com) - API 服務開發的雲平台。M3O 是一個完全託管的微即服務產品，專注於雲中的 Go 微服務開發。免費套餐足以運行 5 項服務並與他人協作。
* [Okteto Cloud](https://okteto.com) - 專為遠程開發設計的託管 Kubernetes 服務。免費的開發者賬戶有 5 個 Kubernetes 命名空間，3Gi/pod 最多 8Gi/命名空間，1CPU/pod 最多 4CPU/命名空間和 5GB 磁盤空間。應用程序在 24 小時不活動後進入睡眠狀態。
* [opeNode](https://opennode.io) — 開源項目的免費 Node.js 託管。100 GB 帶寬/月，100 MB 內存和 1000 MB 存儲空間。使用 CLI 或現有 Git 存儲庫進行部署。
* [outsystems.com](https://www.outsystems.com/) — 用於本地或云的企業 Web 開發 PaaS，免費的“個人環境”產品允許無限代碼和高達 1 GB 的數據庫
* [pipedream.com](https://pipedream.com) - 為開發人員構建的集成平台。基於任何觸發器開發任何工作流。工作流是代碼，您可以 \[免費] (https://docs.pipedream.com/pricing/) 運行它。無需管理服務器或云資源。
* [pythonanywhere.com](https://www.pythonanywhere.com/) — 雲 Python 應用程序託管。初學者帳戶是免費的，在 your-username.pythonanywhere.com 域中有 1 個 Python Web 應用程序，512 MB 私人文件存儲，一個 MySQL 數據庫
* [sap.com](https://archive.sap.com/documents/docs/DOC-56411/) — SAP 提供的內存平台即服務產品。免費的開發者帳戶附帶 1 GB 結構化、1 GB 非結構化、1 GB Git 數據，並允許您運行 HTML5、Java 和 HANA XS 應用程序
* [無服務器雲](https://www.serverless.com/cloud) - 無服務器雲允許您使用基礎架構代碼方法（無 yaml，無基礎架構配置）構建無服務器 API、數據庫和存儲。該產品由 Serverless Inc. 提供，目前處於公共預覽階段。
* [fly.io](https://fly.io/) - Fly 是一個面向需要在全球範圍內運行的應用程序的平台。它在靠近用戶的地方運行您的代碼，並在您的應用程序最繁忙的城市擴展計算。編寫您的代碼，將其打包成 Docker 映像，將其部署到 Fly 的平台，並讓其完成所有工作以保持您的應用程序快速運行。輔助項目免費，每月 10 美元的服務信用額度自動應用於任何付費服務。而且，如果您運行非常小的虛擬機，那麼積分將大有幫助。
* [Divio](https://www.divio.com/) - 管理僅使用 Docker 部署的雲應用程序的平台。可免費訂閱開發項目，需要卡且無自定義域支持。
* [Koyeb](https://www.koyeb.com) - Koyeb 是一個開發人員友好的無服務器平台，用於在全球部署應用程序。通過基於 git 的部署、本機自動縮放、全球邊緣網絡以及內置的服務網格和發現，無縫運行 Docker 容器、Web 應用程序和 API。Koyeb 提供了兩種納米服務來運行您的應用程序及其永久免費層，並且還贊助具有免費資源的開源項目。
* [Railway](https://railway.app) - 鐵路是一個基礎設施平台，您可以在其中配置基礎設施，在本地使用該基礎設施進行開發，然後部署到雲端。1GB 磁盤，512 MB RAM，每月免費使用 5 美元或 500 小時。
* [Napkin](https://www.napkin.io/) - 具有 1Gb 內存的 FaaS，默認超時時間為 15 秒，每月有 1,000,000 次免費 API 調用。
* [流星雲](https://www.meteor.com/cloud) — Galaxy 託管。Meteor 自己的 Meteor 應用程序平台即服務，其中包括免費的 MongoDB 共享主機和自動 SSL。
* [Northflank](https://northflank.com) — 使用強大的 UI、API 和 CLI 構建和部署微服務、作業和託管數據庫。從版本控制和外部 Docker 註冊表無縫擴展容器。免費套餐包括 2 個服務、2 個 cron 作業和 1 個數據庫。
* [Porter](https://getporter.dev/) - 一種完全託管的 PaaS，可讓團隊自動化 DevOps。porter cloud 的免費基本層提供 1 個集群，最多 10 個 vCPU 和 20 GB 內存。
* [YepCode](https://yepcode.io) - 在無服務器環境中連接 API 和服務的一體化平台。它帶來了 NoCode 工具的所有敏捷性和優勢，但具有使用編程語言的所有功能。免費套餐包括 [1.000 yeps](https://yepcode.io/pricing/)。
* [mogenius](https://mogenius.com/) - 一個代碼到雲平台，可以輕鬆部署任何服務，從靜態網站到高級微服務架構。mogenius 附帶來自 Cloudflare 的完全託管的超擴展雲資源、Kubernetes、CI/CD 和安全性。免費套餐包括 0.5 個 CPU 內核、1 GB RAM、5 GB 流量、2 GB SSD 持久存儲。
* [WayScript](https://www.wayscript.com)- WayScript 是一個\[內部開發者平台 (IDP)]\(https://blog.wayscript.com/what-is-an-internal-developer-platform -idp/)，允許軟件工程師隨時自助服務安全的、基於雲的 (Docker + k8s) 開發人員環境。無需一次性配置資源。快速構建工具、應用程序、API、儀表板、安排 cron 任務等。744 小時 [每月免費運行時間](https://www.wayscript.com/pricing)。

### BaaS

* [ably.com](https://www.ably.com) - 用於實時消息傳遞、推送通知和事件驅動 API 創建的 API。免費計劃有 300 萬條消息/月，100 個並發連接，100 個並發通道。
* [back4app.com](https://www.back4app.com) - Back4App 是一個基於 Parse Platform 的易於使用、靈活且可擴展的後端。
* [backendless.com](https://backendless.com/) — 移動和 Web Baas，免費提供 1 GB 文件存儲空間，每月推送通知 50000 個，表中包含 1000 個數據對象。
* [BMC 開發者計劃](https://developers.bmc.com/site/global/bmc\_helix\_platform/program/overview/index.gsp) — BMC 開發者計劃提供文檔和資源來為您的企業構建和部署數字創新。訪問一個全面的個人沙箱，其中包括平台、SDK 和可用於構建和定制應用程序的組件庫。
* [darklang.com](https://darklang.com/) - 託管語言與編輯器和基礎設施相結合。Beta 期間免費，Beta 後計劃提供慷慨的免費套餐。
* [Firebase](https://firebase.com) — Firebase 幫助您構建和運行成功的應用程序。免費 Spark 計劃提供身份驗證、託管、Firebase ML、實時數據庫、雲存儲、測試實驗室。A/B 測試、分析、應用分發、應用索引、雲消息傳遞 (FCM)、Crashlytics、動態鏈接、應用內消息傳遞、性能監控、預測和遠程配置始終免費。
* [Flutter Flow](https://flutterflow.io) — 無需編寫任何代碼即可構建您的 Flutter App UI。還具有 Firebase 集成。免費計劃包括對 UI Builder 和免費模板的完全訪問權限。
* [getstream.io](https://getstream.io/) — 在幾小時而不是幾週內構建可擴展的新聞源、活動流、聊天和消息傳遞
* [hasura.io](https://hasura.io/) — Hasura 擴展了您託管的現有數據庫，並提供了一個即時 GraphQL API，可以安全地訪問 Web、移動和數據集成工作負載。免費獲得 1GB/月的數據直通。
* [iron.io](https://www.iron.io/) — 具有免費套餐和 1 個月免費試用的異步任務處理（如 AWS Lambda）
* [netlicensing.io](https://netlicensing.io) - 一種經濟高效的集成許可即服務 (LaaS) 解決方案，適用於從桌面到物聯網和 SaaS 的任何平台上的軟件。學生期間 _FREE_ 的基本計劃。
* [nhost.io](https://nhost.io) - Web 和移動應用程序的無服務器後端。免費計劃包括：PostgreSQL、GraphQL (Hasura)、身份驗證、存儲和無服務器函數。
* [onesignal.com](https://onesignal.com/) — 無限制的免費推送通知
* [paraio.com](https://paraio.com) — 具有靈活身份驗證、全文搜索和緩存的後端服務 API。1 個應用程序免費，1GB 應用程序數據。
* [posthook.io](https://posthook.io/) — 作業調度服務。允許您安排特定時間的請求。500 個預定請求/月免費。
* [progress.com](https://www.progress.com/kinvey) — 移動後端，入門計劃具有無限請求/秒，具有 1 GB 數據存儲。企業應用支持
* [pubnub.com](https://www.pubnub.com/) — 每月最多 100 萬條消息和每天 100 台活躍設備的免費推送通知
* [pushbots.com](https://pushbots.com/) — 推送通知服務。每月最多 150 萬次推送免費
* [pushcrew.com](https://pushcrew.com/) — 推送通知服務。多達 2000 個訂閱者的無限通知
* [pusher.com](https://pusher.com/beams) — 為 2000 名每月活躍用戶提供免費、無限制的推送通知。適用於 iOS 和 Android 設備的單一 API。
* [pushtechnology.com](https://www.pushtechnology.com/) — 適用於瀏覽器、智能手機和所有人的實時消息傳遞。100 個並發連接。免費 10 GB 數據/月
* [quickblox.com](https://quickblox.com/) — 用於即時消息、視頻和語音通話以及推送通知的通信後端
* [restspace.io](https://restspace.io/) - 為服務器配置身份驗證、數據、文件、電子郵件 API、模板等服務，然後組合成管道並轉換數據。
* [Salesforce 開發人員計劃](https://developer.salesforce.com/signup) — 使用拖放工具快速構建應用程序。通過點擊自定義您的數據模型。使用 Apex 代碼更進一步。使用強大的 API 與任何東西集成。保持企業級安全保護。通過點擊或任何領先的 Web 框架自定義 UI。免費開發者計劃可讓您訪問完整的閃電平台。
* [ServiceNow 開發人員計劃](https://developer.servicenow.com/) — 快速構建、測試和部署應用程序，讓您的組織更好地工作。免費實例和訪問早期預覽。
* [simperium.com](https://simperium.com/) — 即時自動將數據移動到任何地方，多平台，無限發送和存儲結構化數據，最大。2,500 個用戶/月
* [stackstorm.com](https://stackstorm.com/) — 應用程序、服務和工作流的事件驅動自動化，免費無流、訪問控制、LDAP...
* [streamdata.io](https://streamdata.io/) — 將任何 REST API 轉換為事件驅動的流 API。免費計劃多達 100 萬條消息和 10 個並發連接。
* [Supabase](https://supabase.com) — 構建後端的開源 Firebase 替代方案。免費計劃提供身份驗證、實時數據庫和對象存儲。
* [tyk.io](https://tyk.io/) — 具有身份驗證、配額、監控和分析的 API 管理。免費云產品
* [zapier.com](https://zapier.com/) — 連接您使用的應用程序，以自動執行任務。5 zaps，每 15 分鐘和 100 個任務/月
* [LeanCloud](https://leancloud.app/) — 移動後端。1GB 數據存儲、256MB 實例、3K API 請求/天、10K 推送/天免費。（API 與 Parse Platform 非常相似）
* [BudiBase](https://budibase.com/) - Budibase 是一個開源的低代碼平台，可在幾分鐘內創建內部應用程序。支持 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s

### 虛擬主機

* [Alwaysdata](https://www.alwaysdata.com/) — 100 MB 免費網絡託管，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定義網絡服務器，通過 FTP、WebDAV 和 SSH 訪問；包括郵箱、郵件列表和應用程序安裝程序。
* [Awardspace.com](https://www.awardspace.com) — 免費虛擬主機 + 免費短域名、PHP、MySQL、應用安裝程序、電子郵件發送和無廣告。
* [Bubble](https://bubble.io/) — 無需代碼即可構建 Web 和移動應用程序的可視化編程，免費使用 Bubble 品牌。
* [立即部署](https://deploynow.space) — 更智能地部署。部署更快。立即部署。- 從您的 GitHub 存儲庫免費部署多達 3 個 Web 項目。
* [Drive To Web](https://drv.tw) — 從 Google Drive 和 OneDrive 直接託管到網絡。僅限靜態站點。永遠免費。每個 Google/Microsoft 帳戶一個站點。
* [Fenix Web Server](https://preview.fenixwebserver.com) - 一個開發者桌面應用程序，用於在本地託管站點並公開（實時）共享它們。使用其漂亮的用戶界面、API 和/或 CLI，隨心所欲地工作。
* [免費託管](https://freehostingnoads.net/) — 使用 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 電子郵件、免費子域、免費域託管、DNS 區域編輯器的免費託管、網站統計、免費在線支持和其他免費主機不提供的更多功能。
* [Freehostia](https://www.freehostia.com) — FreeHostia 提供免費託管服務，包括。業界最佳的控制面板和 50 多個免費應用程序的一鍵安裝。即時設置。沒有強制廣告。
* [hostman.com](https://hostman.com) — 從您的 GitHub 存儲庫免費部署多達 3 個靜態站點。
* [Neocities](https://neocities.org) — 靜態、1 GB 免費存儲和 200 GB 帶寬。
* [Netlify](https://www.netlify.com/) — 免費構建、部署和託管靜態站點/應用程序，100 GB 數據和 100 GB/月帶寬。
* [Layer0](https://layer0.co/) - 在由 [Limelight](https://www.limelight.com/) 提供支持的全球 CDN 上部署快速動態 Jamstack 網站，免費提供 100GB/月帶寬和 3環境。
* [pantheon.io](https://pantheon.io/) — Drupal 和 WordPress 託管、自動化 DevOps 和可擴展的基礎架構。開發商和代理商免費
* [readthedocs.org](https://readthedocs.org/) — 帶有版本控制、PDF 生成等功能的免費文檔託管
* [render.com](https://render.com) — 使用免費 SSL、全球 CDN、專用網絡、Git 自動部署以及完全免費的 Web 服務計劃構建和運行應用程序和站點的統一云，數據庫和靜態網頁。
* [SourceForge](https://sourceforge.net/) — 免費查找、創建和發布開源軟件
* [Stormkit](https://stormkit.io/) — 將構建、部署和託管與 JAMStack 或 Node.JS 應用程序的 git 流無縫集成。每月免費 50 GB 帶寬和 1000 萬個請求，包括免費 SSL。
* [surge.sh](https://surge.sh/) — 面向前端開發人員的靜態 Web 發布。具有自定義域支持的無限站點
* [tilda.cc](https://tilda.cc/) — 一個站點，50 個頁面，50 MB 存儲空間，只有 170 多個可用的主要預定義塊，沒有字體，沒有網站圖標，沒有自定義域
* [txti.es](https://txti.es/) — 使用 Markdown 快速創建網頁。
* [Vercel](https://vercel.com/) — 每次執行“git push”時，使用免費的 SSL、全球 CDN 和唯一的預覽 URL 構建、部署和託管 Web 應用程序。非常適合 Next.js 和其他靜態站點生成器。
* [Versoly](https://versoly.com/) - 專注於 SaaS 的網站構建器 - 無限網站、70 多個區塊、5 個模板、自定義 CSS、網站圖標、搜索引擎優化和表單。沒有自定義域。
* [Qoddi](https://qoddi.com) - 類似於 Heroku 的 PaaS 服務，具有以開發人員為中心的方法和全包功能。靜態資產、登台和開發人員應用程序的免費套餐。
* [FreeFlarum](https://freeflarum.com/) - 社區支持的免費 Flarum 託管，最多可容納 250 個用戶（捐贈以從頁腳中刪除水印）。
* [fleek.co](https://fleek.co/) - 在開放式 Web 及其協議上構建現代網站和應用程序，無縫免費、無限網站和 50 GB/月帶寬。

### DNS

* [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - 由 CloudFlare 提供的快速且安全的免費公共 DNS 解析器（加密您的 DNS 查詢）。有助於繞過您的互聯網提供商的 DNS 阻止、防止 DNS 查詢間諜活動以及 [阻止成人和惡意軟件內容](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)。也可以使用 [通過 API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests)。注意：只是一個 DNS 解析器，而不是一個 DNS 主機。
* [1984.is](https://www.1984.is/product/freedns/) — 帶有 API 的免費 DNS 服務，以及許多其他免費 DNS 功能。
* [biz.mail.ru](https://biz.mail.ru) — 最多可容納 5,000 名用戶的免費電子郵件和 DNS 託管
* [cloudns.net](https://www.cloudns.net/) — 免費 DNS 託管最多 1 個域和 50 條記錄
* [dns.he.net](https://dns.he.net/) — 具有動態 DNS 支持的免費 DNS 託管服務
* [dnspod.com](https://www.dnspod.com/) — 免費 DNS 託管。
* [duckdns.org](https://www.duckdns.org/) — 免費 DDNS，免費層最多包含 5 個域。帶有各種設置的配置指南。
* [dynu.com](https://www.dynu.com/) — 免費的動態 DNS 服務
* [freedns.afraid.org](https://freedns.afraid.org/) — 免費 DNS 託管。還提供基於眾多公共用戶\[貢獻域]（https://freedns.afraid.org/domain/registry/）的免費子域。註冊後從“子域”菜單中獲取免費子域。
* [luadns.com](https://www.luadns.com/) — 免費 DNS 託管，3 個域，所有功能都有合理的限制
* [namecheap.com](https://www.namecheap.com/domains/freedns/) — 免費 DNS。域名數量沒有限制
* [nextdns.io](https://nextdns.io) - 基於 DNS 的防火牆，每月 30 萬次免費查詢
* [noip](https://www.noip.com/) — 一種動態 dns 服務，最多允許 3 個免費主機名，每 30 天確認一次
* [ns1.com](https://ns1.com/) — 數據驅動 DNS，自動流量管理，500k 免費查詢
* [nsupdate.info](https://www.nsupdate.info/) — 免費和開源的動態 DNS 服務
* [pointhq.com](https://pointhq.com/developer) — Heroku 上的免費 DNS 託管。
* [sslip.io](https://sslip.io/) — 免費 DNS 服務，當使用具有嵌入式 IP 地址的主機名進行查詢時，會返回該 IP 地址。
* [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — 免費的 DNS 託管。
* [zilore.com](https://zilore.com/en/dns) — 免費 DNS 託管。
* [zoneedit.com](https://www.zoneedit.com/free-dns/) — 具有動態 DNS 支持的免費 DNS 託管。
* [zonewatcher.com](https://zonewatcher.com) — 自動備份和 DNS 更改監控。1 個免費域名
* [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 華為免費DNS託管
* [Hetzner](https://www.hetzner.com/dns-console) – Hetzner 提供的免費 DNS 託管，支持 API。
* [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 個域的免費 DNS 託管和 DNSSEC 支持

### 域

* [freenom](https://freenom.com) — 免費 .tk、.ml、.ga、.cf 和 .gq 域。
* [eu.org](https://nic.eu.org) — 免費的 eu.org 域。請求通常在 14 天內獲得批准。
* [js.org](https://js.org) - 用於 JavaScript 社區的 GitHub 頁面的免費 js.org 子域。
* [js.cool](https://github.com/willin/js.cool) - GitHub Pages 和 Vercel 的免費 js.cool 子域。
* [pp.ua](https://nic.ua/) — 免費的 pp.ua 子域。
* [thedev.id](https://thedev.id) — 為開發人員提供的免費 thedev.id 子域。
* [is-a.dev](https://www.is-a.dev/) — 為開發人員提供免費的 is-a.dev 子域。
* [is-a-good.dev](https://is-a-good.dev) — 為開發人員提供的免費 is-a-good-dev 子域。
* [cluster.ws & wip.la](https://github.com/Olivr/free-domain) — 為開發人員提供免費的 cluster.ws 和 wip.la 子域。

### IaaS

* [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 雲存儲。無限時間的免費 10 GB（類似 Amazon S3）對象存儲
* [filebase.com](https://filebase.com/) - 由區塊鏈支持的 S3 兼容對象存儲。5 GB 免費存儲無限期。
* [fosshost.org](https://fosshost.org/) - 免費開源託管 VPS、網絡、存儲和鏡像託管。
* [scaleway](https://www.scaleway.com/en/object-storage/) — S3 兼容的對象存儲。免費 75 GB 存儲空間和外部傳出流量。
* [Storj](https://storj.io/) — 用於應用程序和開發人員的去中心化私有云存儲。免費計劃提供 3 個項目，每個項目/月 50 GB 存儲空間，每個項目/月 50 GB 帶寬。
* [Tebi](https://tebi.io/) - S3 兼容對象存儲。免費 25 GB 存儲和 250 GB 出站傳輸。
* [Idrive e2](https://www.idrive.com/e2/) - S3 兼容性對象存儲。每月 10 GB 免費存儲空間和 10 GB 下載帶寬。
* [C2 對象存儲](https://c2.synology.com/en-us/pricing/object-storage) - S3 兼容對象存儲。每月 15 GB 免費存儲和 15 GB 下載。

### DBaaS

* [airtable.com](https://airtable.com/) — 看起來像一個電子表格，但它是一個關係數據庫、無限的基數、1,200 行/基數和 1,000 個 API 請求/月
* [Astra](https://www.datastax.com/products/datastax-astra/) — 雲原生 Cassandra 即服務，具有 \[80GB 免費套餐]\(https://www.datastax.com/products/datastax-阿斯特拉/定價）
* [bit.io](https://bit.io) — 託管 PostgreSQL 數據庫服務。1 個數據庫、10GB 存儲、1 個 CPU 和 1GB 內存（突發）。
* [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服務，每月最多 100 萬條消息和 20 個免費連接
* [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服務，20 MB 免費
* [FaunaDB](https://fauna.com/) — 無服務器雲數據庫，具有原生 GraphQL、多模型訪問和高達 100 MB 的每日免費層
* [HarperDb](https://harperdb.io/) — 無服務器雲數據庫，具有基於 JSON 的動態模式，3000 IOPS 和 1GB 存儲
* [Upstash](https://upstash.com/) — 無服務器 Redis，免費層每天最多 10,000 個請求，最大數據庫大小為 256MB，並發連接數為 20
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免費套餐提供 512 MB
* [redsmin.com](https://www.redsmin.com/) — Redis 在線實時監控和管理服務，免費監控 1 個 Redis 實例
* [redislabs](https://redislabs.com/try-free/) - 免費 30MB redis 實例
* [MemCachier](https://www.memcachier.com/) — 託管 Memcache 服務。免費提供高達 25MB 的空間、1 個代理服務器和基本分析
* [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 到 192MB 的 MySQL、PostgreSQL 或 MongoDB 免費層
* [SeaTable](https://seatable.io/) — Seafile 團隊構建的靈活、類似電子表格的數據庫。無限表、2,000 行、1 個月版本控制、最多 25 名團隊成員。
* [skyvia.com](https://skyvia.com/) — 雲數據平台，提供免費套餐，所有計劃在測試階段完全免費
* [StackBy](https://stackby.com/) — 一種工具，它結合了電子表格的靈活性、數據庫的強大功能以及與您最喜歡的業務應用程序的內置集成。免費計劃包括無限用戶、10 個堆棧、每個堆棧 2GB 附件。
* [TiDB Cloud](https://en.pingcap.com/tidb-cloud/) — TiDB 是一個開源的兼容 MySQL 的分佈式 HTAP RDBMS。TiDB Cloud 提供一年免費的 Developer Tier、500 MiB 的 OLTP 存儲和 500 MiB 的 OLAP 存儲。
* [InfluxDB](https://www.influxdata.com/) — Timeseries 數據庫，最多釋放 3MB/5 分鐘寫入、30MB/5 分鐘讀取和 10,000 個基數係列
* [Quickmetrics](https://www.quickmetrics.io/) — 包含儀表板的時間序列數據庫，每天最多釋放 10,000 個事件和總共 5 個指標。
* [restdb.io](https://restdb.io/) - 一個快速簡單的 NoSQL 雲數據庫服務。使用 restdb.io，您可以獲得模式、關係、自動 REST API（帶有類似 MongoDB 的查詢）和用於處理數據的高效多用戶管理 UI。免費計劃每秒允許 3 個用戶、2500 條記錄和 1 個 API 請求。
* [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 免費 CockroachDB 高達 5GB 和 1vCPU（有限 \[請求單位]\(https://www.cockroachlabs.com/docs/cockroachcloud /serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta))
* [Neo4j Aura](https://neo4j.com/cloud/aura/) — 具有 Cypher 查詢語言和 REST API 的託管原生 Graph DBMS/分析平台。圖大小限制（50k 節點，175k 關係）。
* [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free) — 使用 GraphQL API 託管的原生 Graph DBMS。每天限制為 1 MB 數據傳輸。
* [TigerGraph Cloud](https://www.tigergraph.com/cloud/) — 託管原生 Graph DBMS / 分析平台，具有類似 SQL 的圖形查詢語言和 REST API。AWS（4 個 vCPU，7.5 GB 內存，50 GB 磁盤）或 GCP（2 個 vCPU，8 GB 內存，128 GB 磁盤）上的 1 個 TG.Free 實例。免費實例在閒置 1 小時後休眠。
* [TerminusX](https://terminusdb.com/) — TerminusDB 的託管免費服務，TerminusDB 是一個用 Prolog 和 Rust 編寫的文檔和圖形數據庫。開發人員免費，企業部署和支持的付費服務。
* [Macrometa](https://www.macrometa.com/) - 一個 noSQL 數據庫、Pub/Sub、事件處理和無服務器邊緣計算平台，用於構建地理分佈式和實時應用程序。免費開發帳戶可訪問 10,000 次操作/天和 200MB 存儲。
* [Planetscale](https://planetscale.com/) - PlanetScale 是一個兼容 MySQL 的無服務器數據庫平台，由 Vitess 提供支持，3 個數據庫免費提供 10GB 存儲空間，每個數據庫每月讀取 1 億行，寫入 1000 萬行/mo 每個數據庫。
* [YugabyteDB](https://cloud.yugabyte.com) - YugabyteDB 是與 PostgresSQL 兼容的分佈式 SQL 數據庫。雲免費層是 2 個 vCPU、4GB RAM、10GB 磁盤。
* [filess.io](https://filess.io) - filess.io 是一個平台，您可以在其中免費創建最多 5 個以下 DBMS 的數據庫：MySQL、MariaDB、MongoDB、PostreSQL。

隧道、WebRTC、Web Socket 服務器和其他路由器

***

* [conveyor.cloud](https://conveyor.cloud/) — Visual Studio 擴展，用於將 IIS Express 公開到本地網絡或通過隧道公開 URL。
* [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一種託管 VPN 服務，可讓您安全地將類似 LAN 的網絡擴展到分佈式團隊，免費計劃允許最多 5 人的無限網絡
* [localhost.run](https://localhost.run/) — 通過隧道向公共 URL 公開本地運行的服務器。
* [localtunnel](https://theboroer.github.io/localtunnel-www/) — 通過隧道向公共 URL 公開本地運行的服務器。免費託管版本和[開源](https://github.com/localtunnel/localtunnel)。
* [ngrok.com](https://ngrok.com/) — 通過隧道向公共 URL 公開本地運行的服務器。
* [Radmin VPN](https://www.radmin-vpn.com/) — 通過啟用類似 LAN 的網絡的 VPN 將多台計算機連接在一起。無限同行。（Hamachi 替代品）
* [segment.com](https://segment.com/) — 將事件翻譯和路由到其他第三方服務的集線器。100,000 個事件/月免費
* [STUN](https://en.wikipedia.org/wiki/STUN) — 通過網絡地址轉換器 \[NATs] 的用戶數據報協議 \[UDP] 的會話遍歷）
  * 谷歌 STUN — [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302)
  * Twilio STUN — [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp)
* [Tailscale](https://tailscale.com/) — 零配置 VPN，使用開源 WireGuard 協議。安裝在 MacOS、iOS、Windows、Linux 和 Android 設備上。20 台設備供個人使用的免費計劃。
* [webhookrelay.com](https://webhookrelay.com) — 管理、調試、扇出和代理所有 webhook 到公共或內部（即：localhost）目的地。此外，通過獲取公共 HTTP 端點（`https://yoursubdomain.webrelay.io <----> http://localhost:8080`），通過隧道公開在專用網絡中運行的服務器。
* [Hookdeck](https://hookdeck.com/pricing) — 從一個地方開發、測試和監控您的 webhook。每月 10 萬次請求和 10 萬次嘗試，保留 3 天。
* [Xirsys](https://www.xirsys.com) — STUN / TURN 服務器的全球網絡，提供大量免費套餐。
* [ZeroTier](https://www.zerotier.com) — FOSS 管理的虛擬以太網即服務。免費計劃的 100 個客戶端的無限端到端加密網絡。桌面/移動/NA客戶端；用於配置自定義路由規則和批准專用網絡上的新客戶端節點的 Web 界面
* [LocalXpose](https://localxpose.io) — 反向代理，使您能夠將本地主機服務器公開到 Internet。免費計劃有 15 分鐘的隧道壽命。

問題跟踪和項目管理

***

* [acunote.com](https://www.acunote.com/) — 最多 5 名團隊成員的免費項目管理和 SCRUM 軟件
* [asana.com](https://asana.com/) — 與合作者的私人項目免費
* [Backlog](https://backlog.com) — 您的團隊在一個平台上發布偉大項目所需的一切。免費計劃提供 1 個具有 10 個用戶和 100MB 存儲空間的項目。
* [Basecamp](https://basecamp.com/personal) - 待辦事項列表、里程碑管理、類似論壇的消息傳遞、文件共享和時間跟踪。最多 3 個項目、20 個用戶和 1GB 的存儲空間。
* [bitrix24.com](https://www.bitrix24.com/) — 免費的內網和項目管理工具
* [cacoo.com](https://cacoo.com/) — 實時在線圖表：流程圖、UML、網絡。免費最大。15 個用戶/圖表，25 張
* [Chpokify](https://chpokify.com/) — 基於團隊的規劃撲克，可節省 sprint 估算時間。最多釋放 5 位用戶、免費 Jira 集成、無限視頻通話、無限團隊、無限會話。
* [clickup.com](https://clickup.com/) — 項目管理。帶有云存儲的免費高級版本。提供移動應用程序和 Git 集成
* [Cloudcraft](https://cloudcraft.co/) — 使用 Cloudcraft 可視化設計器在幾分鐘內設計出專業的架構圖，針對 AWS 進行了優化，智能組件也顯示實時數據。
* [Codegiant](https://codegiant.io) — 具有存儲庫託管和 CI/CD 的項目管理。免費計劃提供無限的存儲庫、項目和文檔，有 5 名團隊成員。每月 500 CI/CD 分鐘。每月 30000 分鐘無服務器代碼運行時間。1GB 存儲庫存儲。
* [Confluence](https://www.atlassian.com/software/confluence) - Atlassian 的內容協作工具，用於幫助團隊高效協作和共享知識。免費計劃最多 10 個用戶。
* [contriber.com](https://www.contriber.com/) — 可定制的項目管理平台，免費入門計劃，5 個工作區
* [diagrams.net/](https://app.diagrams.net/) — 存儲在本地、Google Drive、OneDrive 或 Dropbox 中的在線圖表。免費提供所有功能和存儲級別
* [freedcamp.com](https://freedcamp.com/) - 任務、討論、里程碑、時間跟踪、日曆、文件和密碼管理器。免費計劃，無限項目、用戶和文件存儲。
* [easyretro.io](https://www.easyretro.io/) — 免費簡單直觀的 sprint 回顧工具
* [GForge](https://gforge.com) — 用於具有自建和 SaaS 選項的複雜項目的項目管理和問題跟踪工具集。SaaS 免費計劃為前 5 名用戶免費提供開源項目。
* [gleek.io](https://www.gleek.io) — 為開發人員提供的免費描述到圖表工具。使用關鍵字創建非正式的 UML 類、對像或實體關係圖。
* [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector 輸出兩個 GraphQL 模式之間的更改列表。每個更改都被精確解釋並標記為破壞性、非破壞性或危險性。
* [huboard.com](https://huboard.com/) — 為您的 GitHub 問題提供即時項目管理，開源免費
* [Hygger](https://hygger.io) — 項目管理平台。免費計劃提供無限的用戶、項目和具有 100 MB 存儲空間的板。
* [Instabug](https://instabug.com) — 適用於移動應用的全面錯誤報告和應用內反饋 SDK。免費計劃最多 1 個應用程序和 1 個成員。
* [Ilograph](https://www.ilograph.com/) — 交互式圖表，允許用戶從多個角度和詳細程度查看其基礎架構。圖表可以用代碼表示。免費層有無限的私人圖表，最多有 3 個查看者。
* [Issue Embed](https://issueembed.dev/) - 網站直接進入您的 Github 問題的錯誤報告工具。個人存儲庫的免費計劃，每月最多 500 個問題和 10,000 個頁面瀏覽量/月。
* [Jira](https://www.atlassian.com/software/jira) — 在許多企業環境中使用的高級軟件開發項目管理工具。免費計劃最多 10 個用戶。
* [kanbanflow.com](https://kanbanflow.com/) — 基於董事會的項目管理。免費的高級版本，提供更多選項
* [kanbantool.com](https://kanbantool.com/) — 基於看板的項目管理。免費的付費計劃，有更多選擇
* [Kitemaker.co](https://kitemaker.co) - 在產品開發過程的所有階段進行協作，並跟踪 Slack、Discord、Figma 和 Github 上的工作。無限用戶，無限空間。免費計劃多達 250 個工作項目。
* [Kumu.io](https://kumu.io/) — 包含動畫、裝飾、過濾器、聚類、電子表格導入等的關係圖。免費層允許無限的公共項目。圖表大小不受限制。為學生提供免費的私人項目。如果您不想讓文件公開在線（上傳、編輯、下載、丟棄），則可以使用沙盒模式。
* [LeanBoard](https://www.leanboard.io) — 用於 GitHub 問題的帶有便籤的協作白板（用於示例映射和其他技術）
* [Linear](https://linear.app/) — 具有流線型界面的問題跟踪器。無限會員免費，文件上傳最大 10MB，250 期（不包括存檔）
* [Lucidchart](https://www.lucidchart.com/) - 具有協作功能的在線圖表工具。包含 3 個可編輯文檔、100 個專業模板和基本協作功能的免費計劃。
* [MeisterTask](https://www.meistertask.com/) — 團隊的在線任務管理。最多釋放 3 個項目，無限的項目成員。
* [MeuScrum](https://www.meuscrum.com/en) - 帶有看板的免費在線 Scrum 工具
* [nTask](https://www.ntaskmanager.com/) — 使您的團隊能夠協作、計劃、分析和管理日常任務​​的項目管理軟件。基本計劃永久免費，具有 100 MB 存儲空間，5 個用戶/團隊。無限的工作空間、會議、任務、時間表和問題跟踪。
* [Ora](https://ora.pm/) - 敏捷任務管理和團隊協作。最多 3 個用戶免費，文件限制為 10 MB。
* [pivotaltracker.com](https://www.pivotaltracker.com/) — 免費用於無限制的公共項目和兩個私有項目，共有 3 個活躍用戶（讀寫）和無限制的被動用戶（只讀）。
* [plan.io](https://plan.io/) — 具有存儲庫託管和更多選項的項目管理。2 位用戶免費，10 位客戶和 500MB 存儲空間
* [planitpoker.com](https://www.planitpoker.com/) — 免費在線規劃撲克（估算工具）
* [saas.zentao.pm](https://saas.zentao.pm/) - 用於問題跟踪和項目管理的應用程序生命週期管理解決方案，本地和開源版本也可用。
* [ScrumFast](https://www.scrumfast.com) - 界面非常直觀的 Scrum 板，最多可釋放 5 個用戶。
* [Shake](https://www.shakebugs.com/) - 用於移動應用的應用內錯誤報告和反饋工具。免費計劃，每個應用程序/每月 10 個錯誤報告。
* [快捷方式](https://shortcut.com/) - 項目管理平台。最多 10 位用戶永久免費。
* [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顧板 - 免費。
* [SuperPM](https://superpm.app/) - 多功能項目管理平台。最多可免費用於 3 個項目、無限用戶、1 GB 存儲空間。
* [Tadum](https://tadum.app) - 專為定期會議設計的會議議程和會議記錄應用程序，最多 10 人的團隊免費
* [taiga.io](https://taiga.io/) — 面向初創公司和敏捷開發人員的項目管理平台，開源免費
* [Tara AI](https://tara.ai/) — 簡單的衝刺管理服務。免費計劃有無限的任務、衝刺和工作空間，沒有用戶限制。
* [targetprocess.com](https://www.targetprocess.com/) — 可視化項目管理，從看板和 Scrum 到幾乎任何操作流程。無限用戶免費，最多 1,000 個數據實體{[更多詳細信息](https://www.targetprocess.com/pricing/)}
* [taskade.com](https://www.taskade.com/) — 團隊的實時協作任務列表和大綱
* [taskulu.com](https://taskulu.com/) — 基於角色的項目管理。最多釋放 5 個用戶。與 GitHub/Trello/Dropbox/Google Drive 集成
* [teamwork.com](https://teamwork.com/) — 項目管理和團隊聊天。5 個用戶和 2 個項目免費。提供高級計劃。
* [teleretro.com](https://www.teleretro.com/) — 帶有破冰船、GIF 和表情符號的簡單有趣的回顧工具。免費計劃包括 3 次復古和無限會員。
* [testlio.com](https://testlio.com/) — 問題跟踪、測試管理和 beta 測試平台。免費供私人使用
* [terrastruct.com](https://terrastruct.com/) — 專門用於軟件架構的在線圖表製作工具。每個圖表最多 4 層的免費層。
* [todoist.com](https://todoist.com/) — 協作和個人任務管理。提供免費、高級和團隊計劃。為符合條件的用戶提供折扣。
* [trello.com](https://trello.com/) — 基於董事會的項目管理。無限的個人板，10 個團隊板。
* [Tweek](https://tweek.so/) — 簡單的每週待辦事項日曆和任務管理。
* [ubertesters.com](https://ubertesters.com/) — 測試平台、集成和眾測者，2 個項目，5 名成員
* [vabotu](https://vabotu.com/) - 用於項目管理的協作工具。提供免費和其他計劃。Freelance 計劃適用於 10 個用戶，包括消息傳遞、任務板、5GB 在線存儲、工作區、導出數據。
* [vivifyscrum.com](https://www.vivifyscrum.com/) — 敏捷項目管理的免費工具。Scrum 兼容
* [Wikifactory](https://wikifactory.com/) — 包含項目、VCS 和問題的產品設計服務。免費計劃提供無限的項目和合作者以及 3GB 存儲空間。
* [Yodiz](https://www.yodiz.com/) — 敏捷開發和問題跟踪。最多釋放 3 個用戶，無限項目。
* [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — 免費託管的 YouTrack (InCloud) 用於 FOSS 項目、私人項目（3 個用戶免費）。包括時間跟踪和敏捷板
* [zenhub.com](https://www.zenhub.com) — GitHub 內唯一的項目管理解決方案。公共存儲庫、OSS 和非營利組織免費
* [zepel.io](https://zepel.io/) - 項目管理工具，可讓您規劃功能、跨學科協作以及一起構建軟件。最多釋放 5 名成員。沒有功能限制。
* [zenkit.com](https://zenkit.com) — 項目管理和協作工具。最多 5 名成員免費，5 GB 附件。
* [Zube](https://zube.io) — 4 個項目和 4 個用戶的免費計劃的項目管理。GitHub 集成可用。
* [Toggl](https://toggl.com/) — 提供 2 個免費的生產力工具。[Toggl Track](https://toggl.com/track/) 用於具有免費計劃的時間管理和跟踪應用程序，提供專為自由職業者設計的無縫時間跟踪和報告。它具有無限的跟踪記錄、項目、客戶、標籤、報告等。和 [Toggl 計劃](https://toggl.com/plan/) 用於任務計劃，它為獨立開發者提供免費計劃，具有無限的任務、里程碑和時間表。

存儲和媒體處理

***

* [borgbase.com](https://www.borgbase.com/) — 用於 Borg Backup 的簡單安全的異地備份託管。10 GB 可用備份空間和 2 個存儲庫。
* [icedrive.net](https://www.icedrive.net/) - 簡單的雲存儲服務。10 GB 免費存儲空間
* [sync.com](https://www.sync.com/) - 端到端雲存儲服務。5 GB 免費存儲空間
* [pcloud.com](https://www.pcloud.com/) - 雲存儲服務。高達 10 GB 的免費存儲空間
* [sirv.com](https://sirv.com/) — 具有動態圖像優化和調整大小的智能圖像 CDN。免費套餐包括 500 MB 的存儲空間和 2 GB 的帶寬。
* [cloudimage.com](https://cloudimage.com/) — 全面的圖像優化和 CDN 服務，在全球擁有 1500 多個接入點。多種圖像縮放、壓縮、水印功能。用於響應式圖像、360 度圖像製作和圖像編輯的開源插件。免費的月度計劃，包含 25GB 的 CDN 流量和 25GB 的緩存存儲和無限轉換。
* [cloudinary.com](https://cloudinary.com/) — 用於網站和應用程序的圖像上傳、強大的操作、存儲和交付，以及用於 Ruby、Python、Java、PHP、Objective-C 等的庫。免費套餐包括 25 個每月積分。1 個積分等於 1,000 個圖像轉換、1 GB 的存儲空間或 1 GB 的 CDN 使用量。
* [easyDB.io](https://easydb.io/) — 一鍵式託管數據庫提供商。它們為您選擇的用於開發目的的編程語言提供數據庫。該數據庫是短暫的，將在免費層 24 或 72 小時後刪除。
* [embed.ly](https://embed.ly/) — 提供用於在網頁中嵌入媒體、響應式圖像縮放、從網頁中提取元素的 API。在 15 個請求/秒的情況下，每月最多免費提供 5,000 個 URL
* [filestack.com](https://www.filestack.com/) — 文件選擇器、轉換和交付，免費提供 250 個文件、500 個轉換和 3 GB 帶寬
* [file.io](https://www.file.io) - 2 GB 的文件存儲空間。文件在 1 次下載後自動刪除。與存儲交互的 REST API。速率限制 1 個請求/分鐘。
* [gumlet.com](https://www.gumlet.com/) — 圖像調整大小即服務。它還優化圖像並通過 CDN 執行交付。免費套餐包括 1 GB 帶寬和 1 年內每月不限次數的圖像處理。
* [image-charts.com](https://www.image-charts.com/) — 帶水印的無限圖像圖表生成
* [Imgbot](https://github.com/marketplace/imgbot) — Imgbot 是一個友好的機器人，可以優化您的圖像並節省您的時間。優化的圖像意味著在不犧牲質量的情況下更小的文件大小。它對開源是免費的。
* [imgen](https://www.jitbit.com/imgen/) - 免費無限社交封面圖片生成API，無水印
* [kraken.io](https://kraken.io/) — 圖像優化網站性能即服務，免費計劃最大 1 MB 文件大小
* [kvstore.io](https://www.kvstore.io/) — 鍵值存儲服務。免費套餐允許 100 個密鑰、1KB/密鑰、100 個呼叫/小時
* [npoint.io](https://www.npoint.io/) — 具有協作模式編輯的 JSON 存儲
* [otixo.com](https://www.otixo.com/) — 從一處加密、共享、複製和移動您的所有云存儲文件。基本計劃提供最大 250 MB 的無限文件傳輸。文件大小並允許 5 個加密文件
* [packagecloud.io](https://packagecloud.io/) — YUM、APT、RubyGem 和 PyPI 的託管包存儲庫。有限的免費計劃，可根據要求提供開源計劃
* [getpantry.cloud](https://getpantry.cloud/) — 一個簡單的 JSON 數據存儲 API，非常適合個人項目、黑客馬拉松和移動應用程序！
* [piio.co](https://piio.co/) — 每個網站的響應式圖像優化和交付。開發人員和個人網站的免費計劃。包括開箱即用的免費 CDN、WebP 和延遲加載。
* [Pinata IPFS](https://pinata.cloud) — Pinata 是在 IPFS 上上傳和管理文件的最簡單方法。我們友好的用戶界面與我們的 IPFS API 相結合，使 Pinata 成為平台、創建者和收集者最簡單的 IPFS 固定服務。1 GB 免費存儲以及對 API 的訪問。
* [placeholder.com](https://placeholder.com/) — 快速簡單的圖片佔位符服務
* [placekitten.com](https://placekitten.com/) — 一種快速簡單的服務，用於獲取小貓的照片以用作佔位符
* [plot.ly](https://plot.ly/) — 繪製並分享您的數據。免費套餐包括無限的公共文件和 10 個私人文件
* [podio.com](https://podio.com/) — 您可以與最多 5 人的團隊一起使用 Podio，並試用基本計劃的功能，但用戶管理除外
* [QuickChart](https://quickchart.io) — 生成可嵌入的圖像圖表、圖形和二維碼
* [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 位用戶免費
* [resmush.it](https://resmush.it) — reSmush.it 是提供圖像優化的免費 API。reSmush.it 已在 Wordpress、Drupal 或 Magento 等最常見的 CMS 上實現。reSmush.it 是最常用的圖像優化 API，已經處理了超過 70 億張圖像，並且仍然是免費的。
* [Skynet](https://siasky.net) — 使用 [Sia](https://sia.tech/) 在去中心化網絡上託管數據和 Web 應用程序的開放協議。免費層提供高達 100GB 的存儲空間。
* [Shotstack](https://shotstack.io) - 用於大規模生成和編輯視頻的 API。每月最多可免費播放 20 分鐘的渲染視頻
* [tinypng.com](https://tinypng.com/) — 用於壓縮和調整 PNG 和 JPEG 圖像大小的 API，每月免費提供 500 次壓縮
* [transloadit.com](https://transloadit.com/) — 處理文件上傳和視頻、音頻、圖像、文檔的編碼。通過 GitHub 學生開發包免費為開源、慈善機構和學生提供。商業應用程序可免費獲得 2 GB 用於試駕
* [twicpics.com](https://www.twicpics.com) - 響應式圖像即服務。它提供圖像 CDN、媒體處理 API 和前端庫來自動優化圖像。該服務每月最多免費提供 3GB 流量。
* [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare 為媒體管道提供基於尖端算法的終極工具包。所有功能都完全免費提供給開發人員：文件上傳 API 和 UI、圖像 CDN 和原始服務、自適應交付和智能壓縮。限制免費層有 3000 次上傳、3 GB 流量和 3 GB 存儲空間。
* [imagekit.io](https://imagekit.io) – 具有自動優化、實時轉換和存儲功能的圖像 CDN，您可以在幾分鐘內與現有設置集成。免費計劃包括每月高達 20GB 的帶寬。
* [internxt.com](https://internxt.com) – Internxt Drive 是一種基於絕對隱私和毫不妥協的安全性的零知識文件存儲服務。註冊並永久免費獲得 2 GB！
* [degoo.com](https://degoo.com/) – 基於 AI 的雲存儲，最多可免費使用 100 Gb、5 台設備、500 Gb 推薦獎金（365 天帳戶不活動）。

### 設計和 UI

* [AllTheFreeStock](https://allthefreestock.com) - 免費庫存圖片、音頻和視頻的精選列表。
* [Ant Design Landing Page](https://landing.ant.design/) - Ant Design Landing Page 提供了由 Ant Motion 的運動組件構建的模板。擁有豐富的首頁模板，模板代碼包下載，快速上手。您還可以使用編輯器快速構建自己的專用頁面。
* [Backlight](https://backlight.dev/) — Backlight 以開發人員和設計師之間的協作為核心，是一個非常完整的編碼平台，團隊可以在其中構建、記錄、發布、擴展和維護設計系統。免費計劃最多允許3 名編輯在 1 個設計系統上工作，查看者不受限制。
* [BoxySVG](https://boxy-svg.com/app) — 一個可免費安裝的 Web 應用程序，用於繪製 SVG 並以 svg、png、jpeg 和其他格式導出。
* [clevebrush.com](https://www.cleverbrush.com/) — 免費的圖形設計/照片拼貼應用程序，他們還提供將其作為組件的付費集成。
* [cloudconvert.com](https://cloudconvert.com/) — 將任何東西轉換為任何東西。208 種支持的格式，包括視頻到 gif。
* [CodeMyUI](https://codemyui.com) - 精選的網頁設計和 UI 靈感與代碼片段集合。
* [ColorKit](https://colorkit.co/) - 在線創建調色板或從頂級調色板中獲取靈感。
* [coolors](https://coolors.co/) - 調色板生成器。自由的。
* [css-gradient.com](https://www.css-gradient.com/) - 輕鬆生成自定義跨瀏覽器 css 漸變的免費工具。RGB 和 HEX 格式。
* [designer.io](https://www.designer.io/) — UI、插圖等設計工具。有一個本機應用程序。自由的。
* [figma.com](https://www.figma.com) — 團隊的在線協作設計工具；免費層包括無限的文件和查看器，最多 2 個編輯器和 3 個項目。
* [framer.com](https://www.framer.com/) - Framer 幫助您為您的下一個應用程序、網站或產品迭代和動畫界面創意——從強大的佈局開始。對於任何將 Framer 驗證為專業原型製作工具的人：無限的查看器、最多 2 個編輯器、最多 3 個項目。
* [Gradientos](https://www.gradientos.app) - 快速輕鬆地選擇漸變。
* [Icon Horse](https://icon.horse) – 通過我們簡單的 API 為任何網站獲取最高分辨率的圖標。
* [Icons8](https://icons8.com) — 圖標、插圖、照片、音樂和設計工具。免費計劃以較低的分辨率提供有限的格式。當您使用我們的資產時鏈接到 Icons8。
* [imagebin.ca](https://imagebin.ca/) — 用於圖像的 Pastebin。
* [Invision App](https://www.invisionapp.com) - UI 設計和原型製作工具。桌面和網絡應用程序可用。免費使用 1 個活動原型。
* [landen.co](https://www.landen.co) — 為您的創業公司生成、編輯和發布精美的網站和登錄頁面。全部沒有代碼。免費套餐允許您擁有一個完全可定制並在網絡上發布的網站。
* [lensdump.com](https://lensdump.com/) - 免費云圖像託管。
* [Lorem Picsum](https://picsum.photos/) - 免費工具，易於使用的時尚佔位符。只需在我們的 URL 後添加您想要的圖像尺寸（寬度和高度），您就會得到一張隨機圖像。
* [LottieFiles](https://lottiefiles.com/) - 世界上最大的在線平台，為設計師、開發人員等提供世界上最小的動畫格式。訪問適用於 Android、iOS 和 Web 的 Lottie 動畫工具和插件。
* [MagicPattern](https://www.magicpattern.design/tools) — CSS & SVG 背景生成器和漸變、圖案和 blob 工具的集合。
* [marvelapp.com](https://marvelapp.com/) — 設計、原型製作和協作，僅限一位用戶和一個項目的免費計劃。
* [Mindmup.com](https://www.mindmup.com/) — 免費無限的思維導圖，並將它們存儲在雲端。您的思維導圖隨處可用，可通過任何設備即時訪問。
* [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc 是一個強大的設計協作和交接工具。免費計劃包括 3 個用戶和 5 個具有所有可用功能的項目。
* [mockupmark.com](https://mockupmark.com/create/free) — 為社交媒體和電子商務創建逼真的 T 恤和服裝模型，40 個免費模型。
* [Octopus.do](https://octopus.do) — 可視站點地圖構建器。實時構建您的網站結構并快速共享它以與您的團隊或客戶協作。
* [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的開源設計工具。
* [Penpot](https://penpot.app) - 基於 Web 的開源設計和原型製作工具。支持 SVG。完全免費。
* [pexels.com](https://www.pexels.com/) - 用於商業用途的免費庫存照片。具有免費的 API，可讓您按關鍵字搜索照片。
* [photopea.com](https://www.photopea.com) — 一個免費的高級在線設計編輯器，帶有支持 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch 應用程序）的 Adob​​e Photoshop UI。
* [pixlr.com](https://pixlr.com/) — 商業級別的免費在線瀏覽器編輯器。
* [Plasmic](https://www.plasmic.app/) - 一個快速、易於使用、功能強大的網頁設計工具和頁面構建器，可集成到您的代碼庫中。構建響應式頁面或複雜組件；可選用代碼擴展；並發佈到生產站點和應用程序。
* [Pravatar](https://pravatar.cc/) - 生成隨機/佔位符假頭像，該網址可以直接在您的網頁/應用程序中進行熱鏈接。
* [Proto.io](https://www.proto.io) - 無需編碼即可創建完全交互式的 UI 原型。免費試用期結束時可用的免費層級。免費套餐包括：1 個用戶、1 個項目、5 個原型、100MB 在線存儲和 proto.io 應用程序中的預覽。
* [resizeappicon.com](https://resizeappicon.com/) — 一個簡單的服務來調整和管理你的應用程序圖標。
* [Rive](https://rive.app) — 創建精美的動畫並將其發送到任何平台。個人永久免費。該服務是一個編輯器，它也在其服務器上託管所有圖形。它們還為許多平台提供運行時以運行使用 Rive 製作的圖形。
* [smartmockups.com](https://smartmockups.com/) — 創建產品模型，200 個免費模型。
* [tabler-icons.io](https://tabler-icons.io/) — 超過 1500 個免費複製和粘貼 SVG 可編輯圖標。
* [UI Avatars](https://ui-avatars.com/) - 生成帶有姓名首字母的頭像。哪些網址可以直接在您的網絡/應用程序中進行熱鏈接。支持通過 url 配置參數。
* [unDraw](https://undraw.co/) - 不斷更新的精美 svg 圖像集合，您可以完全免費使用，無需署名。
* [unsplash.com](https://unsplash.com/) - 用於商業和非商業目的的免費庫存照片（隨心所欲地做許可證）。
* [vectr.com](https://vectr.com/) — 適用於 Web + 桌面的免費設計應用程序。
* [walkme.com](https://www.walkme.com/) — 企業級指導和參與平台，免費計劃 3 步，最多 5 步/步。
* [Webflow](https://webflow.com) - 帶有動畫和網站託管的所見即所得網站構建器。2個項目免費。
* [Updrafts.app](https://updrafts.app) - 所見即所得網站構建器，用於基於 tailwindcss 的設計。免費用於非商業用途。
* [whimsical.com](https://whimsical.com/) - 協作流程圖、線框圖、便箋和思維導圖。創建多達 4 個免費板。
* [Zeplin](https://zeplin.io/) — 設計師和開發者協作平台。展示設計、資產和風格指南。1 個項目免費。
* [Pixelixe](https://pixelixe.com/) — 在線創建和編輯引人入勝且獨特的圖形和圖像。
* [Responsively App](https://responsively.app) - 一個免費的開發工具，用於更快、更精確的響應式 Web 應用程序開發。
* [SceneLab](https://scenelab.io) - 具有不斷擴展的免費設計模板集合的在線模型圖形編輯器
* [xLayers](https://xlayers.dev) - 預覽 Sketch 設計文件並將其轉換為 Angular、React、Vue、LitElement、Stencil、Xamarin 等（在 [https://github.com/xlayers 免費和開源） /xlayers](https://github.com/xlayers/xlayers))
* [Grapedrop](https://grapedrop.com/) — 基於 GrapesJS 框架的響應式、強大、SEO 優化的網頁構建器。前 5 頁免費，無限自定義域，所有功能和簡單使用。
* [Mastershot](https://mastershot.app) - 完全免費的基於瀏覽器的視頻編輯器。無水印，高達 1080p 的導出選項。
* [Unicorn Platform](https://unicornplatform.com/) - 帶有託管的輕鬆登陸頁面構建器。1 個網站免費。
* [react-favicon.com](https://react-favicon.com/) - 使用 React 和 JSX 使用任何字體和圖標庫為您的網站生成 Favicon。
* [svgrepo.com](https://www.svgrepo.com/) - 使用各種矢量庫探索、搜索和找到最適合您的項目的圖標或矢量。下載免費的 SVG Vectors 用於商業用途。
* [haikei.app](https://www.haikei.app/) - Haikei 是一個 Web 應用程序，可生成獨特的 SVG 形狀、背景和圖案 - 可與您的設計工具和工作流程一起使用。
* [Canva](https://canva.com) - 用於創建視覺內容的免費在線設計工具。
* [Superdesigner](https://superdesigner.co) - 一系列免費設計工具，只需單擊幾下即可創建獨特的背景、圖案、形狀、圖像等。
* [vector.express](https://vector.express) — 快速輕鬆地轉換您的 AI、CDR、DWG、DXF、EPS、HPGL、PDF、PLT、PS 和 SVG 矢量。
* [okso.app](https://okso.app) - 簡約的在線繪圖應用程序。允許創建快速草圖和視覺筆記。將草圖導出為 PNG、JPG、SVG 和 WEBP。也可以作為 PWA 安裝。所有人免費使用（無需註冊）。

### 設計靈感

* [awwwards.](https://www.awwwards.com/) - \[熱門網站] 展示所有最佳設計網站（由設計師投票選出）。
* [Behance](https://www.behance.net/) - \[設計展示]設計師展示作品的地方。可使用 UI/UX 項目的類別進行過濾。
* [dribbble](https://dribbble.com/) - \[設計展示] 獨特的設計靈感，一般不是來自實際應用。
* [Mobbin](https://mobbin.design/) - \[Mobile screenshots] 使用我們的 50,000 多個完全可搜索的移動應用截圖庫，節省數小時的 UI 和 UX 研究。
* [Mobile Patterns](https://www.mobile-patterns.com/) - \[Mobile screenshots] 一個設計靈感庫，包含最好的 UI UX 模式（iOS 和 Android），供設計師、開發人員和產品製造商參考.
* [Screenlane](https://screenlane.com/) - \[Mobile screenshots] 獲得靈感並跟上最新的網絡和移動應用程序 UI 設計趨勢。可按模式和應用過濾。
* [scrnshts](https://scrnshts.club/) - \[手機截圖] 精選的最佳應用商店設計截圖集合。
* [UI Garage](https://uigarage.net/) - \[手機和網頁截圖] 每日 UI 靈感和模式，供設計師、開發人員為您的項目尋找靈感、工具和最佳資源。

地圖上的數據可視化

***

* [IP Geolocation](https://ipgeolocation.io/) — 免費的 DEVELOPER 計劃可用於每月 30K 的請求。
* [carto.com](https://carto.com/) — 從您的數據和公共數據創建地圖和地理空間 API。
* [developers.arcgis.com](https://developers.arcgis.com) — 用於跨網絡、桌面和移動設備的地圖、地理空間數據存儲、分析、地理編碼、路由等的 API 和 SDK。2,000,000 個免費底圖切片、20,000 個非存儲地理編碼、20,000 條簡單路線、5,000 次行駛時間計算、每月 5GB 免費切片+數據存儲。
* [Foursquare](https://developer.foursquare.com/) - 來自 Places API 和 Pilgrim SDK 的位置發現、場地搜索和上下文感知內容。
* [geoapify.com](https://www.geoapify.com/) - 矢量和柵格地圖切片、地理編碼、地點、路線、等值線 API。每天 3000 個免費請求。
* [geocod.io](https://www.geocod.io/) — 通過 API 或 CSV 上傳進行地理編碼。每天 2,500 次免費查詢。
* [geocodify.com](https://geocodify.com/) — 通過 API 或 CSV 上傳進行地理編碼和地理解析。10k 免費查詢/月。
* [geojs.io](https://www.geojs.io/) - 高度可用的 REST/JSON/JSONP IP 地理位置查找 API。
* [giscloud.com](https://www.giscloud.com/) — 在線可視化、分析和共享地理數據。
* [gogeo.io](https://gogeo.io/) — 具有易於使用的 API 並支持大數據的地圖和地理空間服務。
* [graphhopper.com](https://www.graphhopper.com/) 為開發人員提供了一個免費包，用於路由、路線優化、距離矩陣、地理編碼、地圖匹配。
* [這裡](https://developer.here.com/) — 用於地圖和位置感知應用的 API 和 SDK。250k 交易/月免費。
* [mapbox.com](https://www.mapbox.com/) — 用於顯示地圖數據的地圖、地理空間服務和 SDK。
* [maptiler.com](https://www.maptiler.com/cloud/) — 用於地圖可視化的矢量地圖、地圖服務和 SDK。具有每週更新和四種地圖樣式的免費矢量瓷磚。
* [opencagedata.com](https://opencagedata.com) — 聚合 OpenStreetMap 和其他開放地理資源的地理編碼 API。每天 2,500 次免費查詢。
* [osmnames](https://osmnames.org/) — 地理編碼，搜索結果按相關維基百科頁面的受歡迎程度排名。
* [positionstack](https://positionstack.com/) - 全球地點和坐標的免費地理編碼。每月 25.000 個供個人使用的請求。
* [stadiamaps.com](https://stadiamaps.com/) — 地圖圖塊、路由、導航和其他地理空間 API。每天 2,500 次免費地圖視圖和 API 請求，用於非商業用途和測試。
* [maps.stamen.com](http://maps.stamen.com/) - 免費地圖圖塊和圖塊託管。
* [GeocodeAPI](https://geocodeapi.io) - 地理編碼 API：基於 Pelias 的地址到坐標轉換和地理解析。通過 CSV 進行批量地理編碼。350000 個免費請求/月。
* [Geokeo api](https://geokeo.com) - 具有語言校正等功能的地理編碼 api。全球覆蓋。每日 2,500 次免費查詢

### 包構建系統

* [build.opensuse.org](https://build.opensuse.org/) — 用於多個發行版（SUSE、EL、Fedora、Debian 等）的包構建服務。
* [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Fedora 和 EL 的基於 Mock 的 RPM 構建服務。
* [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 構建服務。

### IDE 和代碼編輯

* [3v4l](https://3v4l.org/) - 免費在線 PHP shell 和代碼片段共享站點，在 300 多個 PHP 版本中運行您的代碼
* [Android Studio](https://d.android.com/studio) — Android Studio 為在各種類型的 Android 設備上構建應用程序提供了最快的工具。開源 IDE，對所有人免費，是開發 Android 應用程序的最佳選擇。適用於 Windows、Mac、Linux 甚至 ChromeOS！
* [Apache Netbeans](https://netbeans.apache.org/) — 開發環境、工具平台和應用程序框架。
* [apiary.io](https://apiary.io/) — 具有即時 API 模擬和生成文檔的協作設計 API（對於無限的 API 藍圖和無限的用戶免費提供一個管理員帳戶和託管文檔）。
* [Atom](https://atom.io/) - Atom 是一個基於 Electron 的可破解文本編輯器。
* [Binder](https://mybinder.org/) - 將 Git 存儲庫變成交互式筆記本的集合。這是一項免費的公共服務。
* [BlueJ](https://bluej.org) — 為初學者設計的免費 Java 開發環境，全球數百萬人使用。由 Oracle 和簡單的 GUI 提供支持，以幫助初學者。
* [Bootify.io](https://bootify.io/) - 具有自定義數據庫和 REST API 的 Spring Boot 應用程序生成器。
* [cacher.io](https://www.cacher.io) — 帶有標籤並支持 100 多種編程語言的代碼片段管理器。
* [Code::Blocks](https://codeblocks.org) — 免費的 Fortran 和 C/C++ IDE。開源並在 Windows、macOS 和 Linux 上運行。
* [codiga.io](https://codiga.io/) — 編碼助手，可讓您直接在 IDE 中搜索、定義和重用代碼片段。個人和小型組織免費。
* [codesnip.com.br](https://codesnip.com.br) — 帶有類別、搜索和標籤的簡單代碼片段管理器。免費且無限制。
* [cocalc.com](https://cocalc.com/) —（以前位於 cloud.sagemath.com 的 SageMathCloud）— 雲中的協作計算。瀏覽器訪問具有內置協作功能的完整 Ubuntu，以及許多用於數學、科學、數據科學的免費軟件，預裝：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等。
* [code.cs50.io](https://code.cs50.io/) - Visual Studio Code for CS50 是 code.cs50.io 上的一個 Web 應用程序，它為學生和教師改編 GitHub Codespaces。
* [codepen.io](https://codepen.io/) — CodePen 是 Web 前端的遊樂場。
* [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preact 等的在線遊樂場。
* [Components.studio](https://webcomponents.dev/) - 單獨編寫組件代碼，在故事中可視化它們，測試它們並在 npm 上發布它們。
* [Eclipse Che](https://www.eclipse.org/che/) - 基於 Web 的 Kubernetes 原生 IDE，適用於具有多語言支持的開發團隊。開源和社區驅動。Red Hat 託管的在線實例可在 [workspaces.openshift.com](https://workspaces.openshift.com/) 獲得。
* [fakejson.com](https://fakejson.com/) — FakeJSON 幫助您使用其 API 快速生成假數據。發出 API 請求，描述您想要什麼以及您想要的方式。API 以 JSON 格式返回所有內容。加快想法進入市場的過程並偽造它，直到你成功為止。
* [gitpod.io](https://www.gitpod.io) — 用於 GitHub 項目的即時、可編寫代碼的開發環境。開源免費。
* [ide.goorm.io](https://ide.goorm.io) goormIDE 是完整的雲端 IDE。多語言支持、基於 linux 的容器（通過功能齊全的基於 Web 的終端）、端口轉發、自定義 url、實時協作和聊天、共享鏈接、Git/Subversion 支持。還有更多功能（免費層包括每個容器 1GB RAM 和 10GB 存儲，5 個容器插槽）。
* [JDoodle](https://www.jdoodle.com) — 超過 60 種編程語言的在線編譯器和編輯器，提供免費的 REST API 代碼計劃，每天最多編譯 200 個積分。
* [jetbrains.com](https://jetbrains.com/products.html) — 生產力工具、IDE 和部署工具（又名 [IntelliJ IDEA](https://www.jetbrains.com/idea/)、\[PyCharm ]（https://www.jetbrains.com/pycharm/）等）。學生、教師、開源和用戶組的免費許可證。
* [jsbin.com](https://jsbin.com) — JS Bin 是另一個前端 Web（HTML、CSS 和 JavaScript。也支持 Markdown、Jade 和 Sass）的遊樂場和代碼共享站點。
* [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端網絡的遊樂場和代碼共享站點，也支持協作。
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) 一些 REST API 端點以 JSON 格式返回一些假數據。如果您想在本地運行服務器，也可以使用源代碼。
* [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一個兼容 Delphi 的跨平台 IDE，用於快速應用程序開發。
* [micro-jaymock](https://micro-jaymock.now.sh/) - 用於生成虛假 JSON 數據的微型 API 模擬微服務。
* [mockable.io](https://www.mockable.io/) — Mockable 是一個簡單的可配置服務，用於模擬 RESTful API 或 SOAP Web 服務。此在線服務允許您快速定義 REST API 或 SOAP 端點並讓它們返回 JSON 或 XML 數據。
* [mockaroo](https://mockaroo.com/) — Mockaroo 讓您可以生成 CSV、JSON、SQL 和 Excel 格式的真實測試數據。您還可以為後端 API 創建模擬。
* [Mocklets](https://mocklets.com) - 基於 HTTP 的模擬 API 模擬器，有助於模擬 API 以實現更快的並行開發和更全面的測試，並提供終身免費層。
* [Paiza](https://paiza.cloud/en/) — 在瀏覽器中開發 Web 應用程序，無需進行任何設置。免費計劃提供 1 台服務器，其使用壽命為 24 小時，每天運行時間為 4 小時，配備 2 個 CPU 內核、2 GB RAM 和 1 GB 存儲空間。
* [Prepros](https://prepros.io/) - Prepros 可以開箱即用地編譯 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加載你的瀏覽器，讓開髮變得非常容易並測試您的網站，以便您可以專注於使它們變得完美。只需單擊幾下，您也可以添加自己的工具。
* [Replit](https://replit.com/) — 適用於各種程序語言的雲編碼環境。
* [SoloLearn](https://code.sololearn.com) — 一個非常適合運行代碼片段的雲編程遊樂場。支持各種編程語言。運行代碼不需要註冊，但當您需要在他們的平台上保存代碼時需要。還為初學者和中級編碼人員提供免費課程。
* [stackblitz.com](https://stackblitz.com/) — 用於創建、編輯和部署全棧應用程序的在線/雲代碼 IDE。支持任何流行的基於 NodeJs 的前端和後端框架。創建新項目的短鏈接：[https://node.new](https://node.new)。
* [Visual Studio Code](https://code.visualstudio.com/) - 代碼編輯器重新定義和優化，用於構建和調試現代 Web 和雲應用程序。由微軟開發。
  * [桌面](https://code.visualstudio.com) - (Windows、macOS 和 Linux)。
  * [在線](https://vscode.dev) - (瀏覽器)
* [Visual Studio 社區](https://visualstudio.microsoft.com/vs/community/) — 具有數千個擴展的全功能 IDE、跨平台應用程序開發（可下載適用於 iOS 和 Android 的 Microsoft 擴展）、桌面、Web 和雲開發、多語言支持（C#、C++、JavaScript、Python、PHP 等）。
* [VSCodium](https://vscodium.com/) - 社區驅動，無遙測/跟踪，微軟編輯器 VSCode 的免費許可二進制分發
* [wakatime.com](https://wakatime.com/) — 使用文本編輯器插件對您的編碼活動進行量化的自我衡量標準，免費的有限計劃。
* [WebComponents.dev](https://webcomponents.dev/) — 瀏覽器內 IDE，用於對 Web 組件進行隔離編碼，提供 58 個模板，支持故事和測試。
* [PHPSandbox](https://phpsandbox.io/) — PHP 在線開發環境。

分析、事件和統計

***

* [Statvoo Analytics](https://analytics.statvoo.com/) — 為您的所有網站提供永久免費的客戶分析，每月無限次活動
* [Avo](https://avo.app/) — 簡化的分析發布工作流程。單一真實來源跟踪計劃、類型安全分析跟踪庫、應用內調試器、數據可觀察性，以便在發布之前捕獲所有數據問題。2 個工作區成員和 1 小時數據可觀察性回溯免費。
* [Branch](https://branch.io) — 移動分析平台。免費套餐為多達 10K 移動應用用戶提供深度鏈接和其他服務。
* [Census](https://www.getcensus.com/) — 反向 ETL 和運營分析平台。將 10 個字段從您的數據倉庫同步到 60 多個 SaaS，例如 Salesforce、Zendesk 或 Amplitude。
* [Clicky](https://clicky.com) — 網站分析平台。1 個網站的免費計劃，包含 3000 次瀏覽分析。
* [Databox](https://databox.com) — 通過結合其他分析和 BI 平台獲得業務洞察力和分析。免費計劃提供 3 個用戶、儀表板和數據源。11M 歷史數據記錄。
* [使用標誌部署](https://deploywithflags.com) — 功能標誌服務。對管理單個項目標誌的個人開發人員免費。
* [indicative.com](https://indicative.com/) — 客戶分析平台，用於優化客戶參與度、提高轉化率並提高保留率。每月最多釋放 2500 萬個事件，數據保留 6 個月。
* [Panelbear.com](https://panelbear.com/) — 極快且私密的免費套餐包括每月 5,000 次網頁瀏覽量，可用於無限網站
* [Hitsteps.com](https://hitsteps.com/) — 1 個網站每月 2,000 次網頁瀏覽
* [amplitude.com](https://amplitude.com/) — 每月 100 萬個事件，最多 2 個應用
* [Flagsmith](https://www.molasses.app) - 放心發布功能；跨 Web、移動和服務器端應用程序管理功能標誌。使用我們的託管 API，部署到您自己的私有云，或在本地運行
* [GoatCounter](https://www.goatcounter.com/) — GoatCounter 是一個開源網絡分析平台，可作為託管服務（非商業用途免費）或自託管應用程序提供。它旨在提供易於使用且有意義的隱私友好型網絡分析，以替代 Google Analytics 或 Matomo。免費套餐用於非商業用途，包括無限數量的網站、6 個月的數據保留期和 10 萬次/月的網頁瀏覽量。
* [谷歌分析](https://analytics.google.com/) — 谷歌分析
* [Expensify](https://www.expensify.com/) — 費用申報，免費的個人申報審批流程
* [getinsights.io](https://getinsights.io) - 注重隱私、無 cookie 的分析，每月最多可免費處理 5k 事件。
* [heap.io](https://heap.io) — 自動捕獲 iOS 或 Web 應用程序中的每個用戶操作。每月最多 5,000 次訪問免費
* [Hotjar](https://hotjar.com) — 網站分析和報告。免費計劃允許每天 2000 次瀏覽量。每天 100 個快照（最大容量：300）。3 個快照熱圖，可存儲 365 天。無限的團隊成員。
* [Keen](https://keen.io/) — 用於數據收集、分析和可視化的自定義分析。50,000 個事件/月免費
* [Yandex.Metrica](https://metrica.yandex.com/) — 無限制的免費分析
* [Mixpanel](https://mixpanel.com/) — 每月跟踪 100,000 名用戶、無限數據歷史記錄和席位、美國或歐盟數據駐留
* [Moesif](https://www.moesif.com) — REST 和 GraphQL 的 API 分析。（每月最多免費調用 500,000 次 API 調用）
* [Molasses](https://www.molasses.app) - 強大的功能標誌和 A/B 測試。最多釋放 3 個環境，每個環境有 5 個功能標誌。
* [optimizely.com](https://www.optimizely.com) — A/B 測試解決方案、免費入門計劃、1 個網站、1 個 iOS 和 1 個 Android 應用
* [Microsoft PowerBI](https://powerbi.com) — Microsoft 的業務洞察與分析。免費計劃提供 100 萬用戶許可證的有限使用。
* [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 無限制的免費分析
* [sematext.com](https://sematext.com/cloud/) — 每月最多 50,000 次免費操作、1 天數據保留、無限制的儀表板、用戶等。
* [Similar Web](https://similarweb.com) — 網絡和移動應用分析。免費計劃提供每個指標 5 個結果、1 個月的移動應用數據和 3 個月的網站數據。
* [StatCounter](https://statcounter.com/) — 網站查看者分析。用於分析 500 位最近訪問者的免費計劃。
* [Swetrix Analytics](https://swetrix.com/) — 以隱私為中心的網絡分析。免費計劃包括每月最多 5000 個事件。
* [Splitbee](https://splitbee.io/) — 使用 Splitbee 跟踪和優化您的在線業務。免費計劃包括每月最多 2,500 個事件、6 個月的保留期、1 個主動 A/B 測試和 1 個主動自動化。
* [Tableau 開發人員計劃](https://www.tableau.com/developer) — 創新、創建 Tableau 並讓 Tableau 完美地為您的組織工作。免費的開發人員計劃為 Tableau Online 提供了個人開髮沙盒許可證。該版本是最新的預發布版本，因此數據開發人員可以測試這個一流平台的每一個功能。
* [usabilityhub.com](https://usabilityhub.com/) — 在真人身上測試設計和模型，跟踪訪問者。一位用戶免費，無限制測試
* [woopra.com](https://www.woopra.com/) — 用於 500K 操作、90 天數據保留、30+ 一鍵集成的免費用戶分析平台。
* [counter.dev](https://counter.dev) — Web 分析變得簡單，因此對隱私友好。免費或通過捐贈支付您想要的東西。
* [PostHog](https://posthog.com) - 完整的產品分析套件，每月最多可跟踪 100 萬個事件
* [Uptrace](https://uptrace.dev) - 幫助開發人員查明故障並找到性能瓶頸的分佈式跟踪工具。有一個免費計劃，提供免費的個人開源項目訂閱，並且有一個開源版本。
* [Microsoft Clarity](https://clarity.microsoft.com/) - Clarity 是一款免費且易於使用的工具，可捕捉真實用戶如何使用您的網站。

訪客會話記錄

***

* [Visualime.com](https://www.visualime.com/) — 免費且無限制的會話記錄，無流量限制
* [Reactflow.com](https://www.reactflow.com/) - 每個站點：1,000 頁面瀏覽量/天，3 個熱圖，3 個小部件，免費的錯誤跟踪
* [LogRocket.com](https://www.logrocket.com) - 1,000 個會話/月，保留 30 天，錯誤跟踪，實時模式
* [FullStory.com](https://www.fullstory.com) — 1,000 個會話/月，數據保留 1 個月和 3 個用戶席位。更多信息 \[此處]（https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition）。
* [hotjar.com](https://www.hotjar.com/) — 每個站點：每天 2,000 次頁面瀏覽量，3 個熱圖，存儲 3 個月的數據，...
* [inspectlet.com](https://www.inspectlet.com/) — 1 個網站每月免費 2,500 次會話
* [livesession.io](https://livesession.io/) — 1 個網站每月免費 5,000 次會話
* [Microsoft Clarity](https://clarity.microsoft.com/) - 會話錄製完全免費，“無流量限制”、無項目限制、無採樣
* [mouseflow.com](https://mouseflow.com/) — 1 個網站每月免費 500 次會話
* [mousestats.com](https://www.mousestats.com/) — 1 個網站每月免費 100 次會話
* [smartlook.com](https://www.smartlook.com/) — Web 和移動應用程序的免費包（1500 個會話/月）、3 個熱圖、1 個漏斗、1 個月的數據歷史記錄
* [usersurge.com](https://www.usersurge.com/) — 個人每月 25 萬次會話。
* [howuku.com](https://howuku.com) — 跟踪用戶互動、參與度和事件。每月最多 5,000 次訪問免費
* [UXtweak.com](https://www.uxtweak.com/) — 記錄並觀察訪問者如何使用您的網站或應用程序。小項目的免費無限時間

國際手機號碼驗證API和SDK

***

* [Cognalys](https://cognalys.com/) — 通過一種創新且可靠的方法驗證免費增值手機號碼，而不是使用 SMS 網關。每天免費 10 次嘗試和 15 次驗證
* [numverify](https://numverify.com/) — 全球電話號碼驗證和查找 JSON API。250 個 API 請求/月
* [veriphone](https://veriphone.io/) — 免費、快速、可靠的 JSON API 中的全球電話號碼驗證。1000 個請求/月

支付和計費集成

***

* [Adapty.io](https://adapty.io/) – 使用開源 SDK 的一站式解決方案，用於將移動應用內訂閱集成到 iOS、Android、React Native、Flutter、Unity 或 Web 應用。釋放高達 10,000 美元的月收入。
* [CurrencyFreaks](https://currencyfreaks.com/) — 提供當前和歷史貨幣匯率。免費的 DEVELOPER 計劃可用於每月 1000 個請求。
* [CurrencyApi](https://currencyapi.net/) — 實物和加密貨幣的實時匯率，以 JSON 和 XML 格式提供。免費套餐每月提供 1,250 個 API 請求。
* [currencylayer](https://currencylayer.com/) — 為您的業務提供可靠的匯率和貨幣轉換，每月 1,000 個 API 請求免費
* [currencystack.io](https://currencystack.io/) — 154 種貨幣的生產就緒實時匯率。
* [exchangerate-api.com](https://www.exchangerate-api.com) - 一個易於使用的貨幣轉換 JSON API。免費套餐，沒有請求限制。
* [FraudLabsPRO](https://www.fraudlabspro.com) — 幫助商家防止支付欺詐和拒付。免費的微型計劃可用於每月 500 次查詢。
* [MailPopin](https://mailpop.in) - 通過上下文信息充分利用您的 Stripe 通知。
* [Nami ML](https://www.namiml.com/) - 適用於 iOS 和 Android 上的應用內購買和訂閱的完整平台，包括無代碼付費牆、CRM 和分析。免費提供所有基本功能以運行 IAP 業務。
* [RevenueCat](https://www.revenuecat.com/) — 用於應用內購買和訂閱（iOS 和 Android）的託管後端。最多可釋放 $10k/mo 的跟踪收入。
* [vatlayer](https://vatlayer.com/) — 即時增值稅號驗證和歐盟增值稅率 API，每月免費 100 個 API 請求
* [Freecurrencyapi.net](https://freecurrencyapi.net/) — 免費貨幣轉換和匯率數據 API。10 個請求/小時，沒有 API 密鑰，當您免費註冊時，每月 50 000 個請求。

### Docker 相關

* [canister.io](https://canister.io/) — 為開發人員提供 20 個免費私有存儲庫，為團隊構建和存儲 Docker 鏡像提供 30 個免費私有存儲庫
* [Container Registry Service](https://container-registry.com/) - 基於 Harbor 的容器管理解決方案。免費套餐為私有存儲庫提供 1 GB 存儲空間。
* [Docker Hub](https://hub.docker.com) — 一個免費的私有倉庫和無限的公共倉庫來構建和存儲 Docker 鏡像
* [玩 Docker](https://labs.play-with-docker.com/) — 一個簡單、互動且有趣的 Docker 學習平台。
* [quay.io](https://quay.io/) — 使用無限的免費公共存儲庫構建和存儲容器鏡像
* [Platform9](https://platform9.com/) - 託管的 Kubernetes 平面。免費計劃提供多達 3 個集群和 20 個節點的管理功能。注意：您必須自己提供集群基礎設施。

### Vagrant 相關

* [Vagrant Cloud](https://app.vagrantup.com) - HashiCorp Vagrant Cloud。流浪盒託管。
* [Vagrantbox.es](https://www.vagrantbox.es/) — 另一種公共盒子索引

### 開發博客站點

* [BearBlog](https://bearblog.dev/) - 極簡主義和 Markdown 驅動的博客和網站構建器。
* [Dev.to](https://dev.to/) - 程序員在這里分享想法並互相幫助成長。
* [Hashnode](https://hashnode.com/) — 面向開發人員的無憂博客軟件！。
* [Medium](https://medium.com/) — 更聰明地了解對您而言重要的事情。

### 評論平台

* [Staticman](https://staticman.net/) - Staticman 是一個 Node.js 應用程序，它接收用戶生成的內容並將其作為數據文件上傳到 GitHub 和/或 GitLab 存儲庫，使用拉取請求。
* [GraphComment](https://graphcomment.com/) - GraphComment 是一個評論平台，可幫助您從網站的受眾中建立一個活躍的社區。
* [Utterances](https://utteranc.es/) - 基於 GitHub 問題構建的輕量級評論小部件。將 GitHub 問題用於博客評論、wiki 頁面等！
* [Disqus](https://disqus.com/) - Disqus 是一個網絡社區平台，被網絡上成千上萬的網站使用。

### 屏幕截圖 API

* [ApiFlash](https://apiflash.com) — 基於 Aws Lambda 和 Chrome 的屏幕截圖 API。處理整頁，捕捉時間，視口尺寸，......
* [microlink.io](https://microlink.io/) – 它將任何網站轉化為數據，例如元標記規範化、美麗鏈接預覽、抓取功能或屏幕截圖即服務。每天 250 個請求/天免費。
* [ScreenshotAPI.net](https://screenshotapi.net/) - 截圖 API 使用一個簡單的 API 調用來生成任何網站的截圖。構建以擴展並託管在 Google Cloud 上。每月提供 100 個免費截圖。
* [screenshotlayer.com](https://screenshotlayer.com/) — 捕獲任何網站的高度可定制的快照。每月免費 100 張快照
* [screenshotmachine.com](https://www.screenshotmachine.com/) — 捕獲 100 個快照/月，png、gif 和 jpg，包括全長捕獲，不僅是主頁
* [PhantomJsCloud](https://phantomjscloud.com) — 瀏覽器自動化和頁面渲染。免費套餐每天最多提供 500 頁。自 2017 年起免費套餐。
* [Webshrinker.com](https://webshrinker.com) — Web Shrinker 提供網站截圖和域情報 API 服務。每月免費 100 個請求。
* [Httpic.com](https://httpic.com) — 將任何網站轉換為 jpg、png 或 pdf。捕獲整頁截圖，調整視口，注入自定義代碼。每月 150 張圖像的免費套餐。
* [Screenshots](https://screenshotson.click) — You API for Screenshot。具有高度可定制的捕獲選項。每月免費 100 張截圖。

Flutter 相關和無 Mac 構建 IOS 應用

***

* [FlutLab](https://flutlab.io/) - FlutLab 是現代 Flutter 在線 IDE，是創建、調試和構建跨平台項目的最佳場所。使用 Flutter 構建 iOS（無 Mac）和 Android 應用程序。
* [CodeMagic](https://codemagic.io/) - Codemagic 是一個完全託管和託管的移動應用程序 CI/CD。您可以使用基於 GUI 的 CI/CD 工具構建、測試和部署。免費套餐提供每月 500 分鐘的免費通話時間，以及配備 2.3Ghz 和 8GB RAM 的 Mac Mini 實例。
* [FlutterFlow](https://flutterflow.io/) - FlutterFlow 是一個基於瀏覽器的拖放界面，用於使用 Flutter 構建移動應用程序。

用 Javascript 編寫的基於瀏覽器的硬件仿真

***

* [JsLinux](https://bellard.org/jslinux) — 一個非常快速的 x86 虛擬機，能夠運行 Linux 和 Windows 2k。
* [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) — 一個能夠在網絡支持下運行 Linux 的 OpenRISC 虛擬機。
* [v86](https://copy.sh/v86) — 能夠在瀏覽器中直接運行 Linux 和其他操作系統的 x86 虛擬機。

### 隱私管理

* [Bearer](https://www.bearer.sh/) - 通過審計和持續的工作流程幫助通過設計實現隱私，以便組織遵守 GDPR 和其他法規。免費套餐僅限於較小的團隊和 SaaS 版本。
* [Osano](https://www.osano.com/) - 包含從 GDPR 表示到 cookie 橫幅的所有內容的同意管理和合規平台。免費套餐提供基本功能。
* [Iubenda](https://www.iubenda.com/) - 隱私和 cookie 政策以及同意管理。免費套餐提供有限的隱私和 cookie 政策以及 cookie 橫幅。
* [Cookiefirst](https://cookiefirst.com/) - Cookie 橫幅、審核和多語言同意管理解決方案。免費套餐提供一次性掃描和單個橫幅。
* [Ketch](https://www.ketch.com/) - 同意管理和隱私框架工具。免費套餐提供大多數功能，但訪客人數有限。

### 雜項

* [Smartcar API](https://smartcar.com) - 用於汽車定位、獲取油箱、電池電量、里程表、解鎖/鎖門等的 API。
* [Blynk](https://blynk.io) — 一種帶有 API 的 SaaS，用於控制、構建和評估物聯網設備。包含 5 台設備、免費云和數據存儲的免費開發者計劃。移動應用程序也可用。
* [Bricks Note Calculator](https://free.getbricks.app/) - 一款內置多行計算器的筆記應用 (PWA)。
* [Carbon.now.sh](https://carbon.now.sh) - 以類似屏幕截圖的美觀圖像格式創建和共享代碼片段。通常用於在 Twitter 或博客文章上美觀地分享/炫耀代碼片段。
* [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中時間跟踪和編碼指標的擴展。
* [Codepng](https://www.codepng.app) - 從您的源代碼創建很棒的快照，您可以在社交媒體上分享。
* [CodeToImage](https://codetoimage.com/) - 創建代碼或文本的屏幕截圖以在社交媒體上分享。
* [ConfigCat](https://configcat.com) - 跨平台功能標誌服務。適用於所有主要語言的 SDK。免費計劃每月最多 10 個標誌、2 個環境、1 個產品和 500 萬個請求。無限用戶席位。學生每月免費獲得 100 個標誌和 1 億個請求。
* [datelist.io](https://datelist.io) - 在線預約/預約安排系統。每月最多可免費預訂 5 次，包括 1 個日曆
* [docsapp.io](https://www.docsapp.io/) — 發布文檔的最簡單方式，對開源免費
* [Elementor](https://elementor.com) — WordPress 網站建設者。免費計劃提供 40 多個基本小部件。
* [Form2Channel](https://form2channel.com) — 在您的網站上放置一個靜態 html 表單，並直接接收提交到 Google Sheets、Email、Slack、Telegram 或 Http 的提交。無需編碼。
* [FOSSA](https://fossa.com/) - 第三方代碼、許可證合規性和漏洞的可擴展、端到端管理。
* [fullcontact.com](https://www.fullcontact.com/developer/pricing/) — 通過在您的應用中添加社交資料，幫助您的用戶更多地了解他們的聯繫人。500 次免費 Person API 匹配/月
* [http2.pro](https://http2.pro) — HTTP/2 協議就緒測試和客戶端 HTTP/2 支持檢測 API。
* [JWT Decoder](https://jwt.ssotools.com/) — 用於解碼 JWT（JSON Web 令牌）並驗證其簽名的在線免費工具。
* [Base64 解碼器/編碼器](https://devpal.co/base64-decode/) — 用於解碼和編碼數據的在線免費工具。
* [newreleases.io](https://newreleases.io/) - 通過電子郵件、Slack、Telegram、Discord 和自定義 webhook 接收來自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM 的新版本的通知、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo 和 Docker Hub。
* [OnlineExifViewer](https://onlineexifviewer.com/) — 即時在線查看照片的 EXIF 數據，包括 GPS 位置和元數據。
* [PDFMonkey](https://www.pdfmonkey.io/) — 在儀表板中管理 PDF 模板，使用動態數據調用 API，下載您的 PDF。每月提供 1000 個免費文檔。
* [QuickType.io](https://quicktype.io/) - 從 JSON、模式和 GraphQL 快速自動生成模型/類/類型/接口和序列化程序，以便以任何編程語言快速安全地處理數據。將 JSON 轉換為任何語言的華麗、類型安全的代碼。
* [ray.so](https://ray.so/) - 為您的代碼片段創建漂亮的圖像。
* [readme.com](https://readme.com/) — 漂亮的文檔變得簡單，對開源免費。
* [redirection.io](https://redirection.io/) — 用於管理企業、營銷和 SEO 的 HTTP 重定向的 SaaS 工具。
* [redirect.pizza](https://redirect.pizza/) - 通過 HTTPS 支持輕鬆管理重定向。免費計劃包括每月 10 個來源和 100.000 次點擊。
* [ReqBin](https://www.reqbin.com/) — 在線發布 HTTP 請求。流行的請求方法包括 GET、POST、PUT、DELETE 和 HEAD。支持標頭和令牌身份驗證。包括用於保存您的請求的基本登錄系統。
* [日出和日落](https://sunrisesunset.io/api/) - 獲取給定經度和緯度的日出和日落時間。
* [superfeedr.com](https://superfeedr.com/) — 實時 PubSubHubbub 合規提要、導出、分析。免費，定制更少
* [SurveyMonkey.com](https://www.surveymonkey.com) — 創建在線調查。在線分析結果。免費計劃每次調查僅允許 10 個問題和 100 個回复。
* [videoinu](https://videoinu.com) — 在線創建和編輯屏幕錄像和其他視頻。
* [RandomKeygen](https://randomkeygen.com/) - 免費的移動友好工具提供各種隨機生成的密鑰和密碼，可用於保護任何應用程序、服務或設備的安全。
* [Cronit](https://cronit.app) - 在線 cronjobs 服務。免費計劃包括每月 100 個作業執行
* [Cronhooks](https://cronhooks.io/) - 按時安排或重複 webhook。免費計劃允許 5 個臨時計劃。
* [Hook Relay](https://www.hookrelay.dev/) - 輕鬆為您的應用添加 webhook 支持：為您完成排隊、使用退避重試和日誌記錄。免費計劃每天有 100 次交付、14 天保留期和 3 個掛鉤端點。
* [Format Express](https://www.format-express.dev) - JSON / XML / SQL 的即時在線格式化程序。

### 遠程桌面工具

* [Getscreen.me](https://getscreen.me) — 2 台設備免費，會話數量和持續時間沒有限制
* [Apache Guacamole™](https://guacamole.apache.org/) — 開源無客戶端遠程桌面網關
* [RemSupp](https://remsupp.com) — 按需支持和永久訪問設備（每天 2 次免費）
* [RustDesk](https://rustdesk.com/) - 面向所有人的開源虛擬/遠程桌面基礎架構！

### 遊戲開發

* [itch.io](https://itch.io/game-assets) — 免費/付費資產，如精靈、瓷磚集、角色包……
* [GameDevMarket](https://gamedevmarket.net) — 免費/付費資產，如 2D、3D、音頻、GUI。
* [OpenGameArt](https://opengameart.org) — 開源遊戲資產，如音樂、聲音、精靈、gif ......
* [CraftPix](https://craftpix.net) — 免費/付費資產，如 2D、3D、音頻、GUI、背景、圖標、圖塊集、遊戲套件。
* [LoSpec](https://lospec.com/) — 用於創建像素藝術和其他限制性數字藝術的在線工具，有大量教程/托盤列表可供您的遊戲選擇
* [ArtStation](https://www.artstation.com/) - 免費/付費 2D、3D 資產和音頻、圖標、瓷磚套裝、遊戲套件等的 MarketPlace，此外，它還可用於展示您的藝術作品集。
* [Rive](https://rive.app/community/) - 社區資產以及使用其免費計劃創建您自己的遊戲資產。
* [Poly Pizza](https://poly.pizza/) - 免費低多邊形 3D 資產
* [3Dassets.one](https://www.3dassets.one/) - 超過 8,000 個免費/付費 3D 模型，以及用於製作紋理的 PBR 材料。

### 其他免費資源

* [get.localhost.direct](https://get.localhost.direct) — 更好的 `*.localhost.direct` 通配符公共 CA 簽名 SSL 證書，用於 localhost 開發，支持子域
* [Framacloud](https://degooglisons-internet.org/en/list/) — 法國非營利組織 [Framasoft](https://framasoft.org/) 提供的免費/自由開源軟件和 SaaS 列表zh/)。
* [getawesomeness](https://getawesomeness.herokuapp.com) — 從 GitHub 中檢索所有令人驚嘆的精彩……必看
* [github.com — 開發人員的 FOSS](https://github.com/tvvocold/FOSS-for-Dev) — 為開發人員提供的免費和開源軟件中心。
* [GitHub Education](https://education.github.com/pack) — 為學生提供的免費服務集合。需要註冊。
* [Microsoft 365 開發人員計劃](https://developer.microsoft.com/microsoft-365/dev-program) — 獲取構建 Microsoft 365 平台解決方案所需的免費沙箱、工具和其他資源。訂閱為 90 天 [Microsoft 365 E5 訂閱](https://www.microsoft.com/microsoft-365/enterprise/e5)（不包括 Windows），可續訂。如果您積極參與開發（使用遙測數據和算法測量），它會被更新。
* [RedHat for Developers](https://developers.redhat.com) — 專為開發人員免費訪問 Red Hat 產品，包括 RHEL、OpenShift、CodeReady 等。僅限個人計劃。還提供免費電子書以供參考。
* [smsreceivefree.com](https://smsreceivefree.com/) — 提供免費的臨時和一次性電話號碼。
* [simplebackups.io](https://simplebackups.io/) — 直接存儲在雲存儲提供商（AWS、DigitalOcean、Backblaze...）中的服務器和數據庫（MySQL、PostgreSQL、MongoDB）的備份自動化服務。提供 1 個備份的免費計劃。
* [SnapShooter](https://snapshooter.com/) — DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的備份解決方案，支持直接將數據庫、文件系統和應用程序備份到基於 s3 的存儲。為一項資源提供每日備份的免費計劃。
* [Themeselection](https://themeselection.com/) — 精選高品質、現代設計、專業且易於使用的免費管理儀表板模板、HTML 主題和 UI 工具包，以更快地創建您的應用程序！
* [Web.Dev](https://web.dev/measure/) — 這是一個免費工具，可讓您查看網站的性能並改進 SEO 以在搜索引擎中獲得更高的排名。
* [SmallDev.tools](https://smalldev.tools/) — 一個免費的開發者工具，允許您編碼/解碼各種格式，縮小 HTML/CSS/Javascript，美化，生成假/測試真實的 JSON 數據集/CSV 和多種其他格式以及更多功能。具有令人愉快的界面。
* [通過 Layercode 使用 CSV](https://layercode.com/usecsv) — 在幾分鐘內將 CSV 和 Excel 導入您的 Web 應用程序。為您的用戶提供愉快而強大的數據導入體驗。無需任何信用卡詳細信息即可免費開始使用，立即開始集成 UseCSV。您可以創建無限的導入器並上傳最大 100Mb 的文件。
* [按鈕生成器](https://markodenic.com/tools/buttons-generator/) — 100 多個可以在項目中使用的按鈕。
* [WrapPixel](https://www.wrappixel.com/) — 下載使用 Angular、React、VueJs、NextJs 和 NuxtJs 創建的高質量免費和高級管理儀表板模板！



#### 了解更多關於免費的 Github 開發者資源

{% embed url="https://tenten.co/insight/dev/free-for-dev/" %}
