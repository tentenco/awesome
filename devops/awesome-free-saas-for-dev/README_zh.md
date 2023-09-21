免費開發者資源 SaaS
====

開發人員和開源作者現在擁有大量提供免費套餐的服務，但很難找到所有這些服務來做出明智的決策。

這是為開發人員提供免費套餐的軟體（SaaS、PaaS、IaaS 等）和其他產品的清單。

此特定清單的範圍僅限於基礎設施開發人員（系統管理員、DevOps 從業人員等）可能會發現有用的內容。我們喜歡所有的免費服務，但最好保持主題。

**注意**：此清單僅適用於即服務產品，不適用於自架軟體。一項服務要符合資格，必須提供免費套餐，而不僅僅是免費試用。如果免費套餐有時間限制，則必須持續至少一年。我們也從安全角度考慮免費層，因此 SSO 很好，但我不會接受將 TLS 限制為僅限付費層的服務。

目錄
==

*   [主要雲端提供者的始終免費限制](#major-cloud-providers)
*   [雲端管理解決方案](#cloud-management-solutions)
*   [分析、事件和統計](#analytics-events-and-statistics)
*   [API、資料和機器學習](#apis-data-and-ml)
*   [神器倉庫](#artifact-repos)
*   [BaaS](#baas)
*   [低程式碼平台](#low-code-platform)
*   [CDN 和保護](#cdn-and-protection)
*   [持續整合和持續交付](#ci-and-cd)
*   [內容管理系統](#cms)
*   [程式碼生成](#code-generation)
*   [代碼品質](#code-quality)
*   [代碼搜尋和瀏覽](#code-search-and-browsing)
*   [崩潰和異常處理](#crash-and-exception-handling)
*   [地圖上的數據視覺化](#data-visualization-on-maps)
*   [託管資料服務](#managed-data-services)
*   [設計和使用者介面](#design-and-ui)
*   [設計靈感](#design-inspiration)
*   [開發部落格網站](#dev-blogging-sites)
*   [域名系統](#dns)
*   [Docker相關](#docker-related)
*   [領域](#domain)
*   [電子郵件](#email)
*   [功能切換管理平台](#feature-toggles-management-platforms)
*   [字體](#font)
*   [形式](#forms)
*   [基礎設施即服務](#iaas)
*   [IDE 和程式碼編輯](#ide-and-code-editing)
*   [國際手機號碼驗證API和SDK](#international-mobile-number-verification-api-and-sdk)
*   [問題追蹤與專案管理](#issue-tracking-and-project-management)
*   [日誌管理](#log-management)
*   [行動應用程式分發和回饋](#mobile-app-distribution-and-feedback)
*   [管理系統](#management-system)
*   [訊息傳遞和串流媒體](#messaging-and-streaming)
*   [各種各樣的](#miscellaneous)
*   [監控](#monitoring)
*   [平台即服務](#paas)
*   [封裝建置系統](#package-build-system)
*   [支付和帳單集成](#payment-and-billing-integration)
*   [隱私管理](#privacy-management)
*   [截圖API](#screenshot-apis)
*   [Flutter 相關以及在沒有 Mac 的情況下建立 IOS 應用程式](#flutter-related-and-building-ios-apps-without-mac)
*   [搜尋](#search)
*   [安全和公鑰基礎設施](#security-and-pki)
*   [認證、授權和使用者管理](#authentication-authorization-and-user-management)
*   [原始碼儲存庫](#source-code-repos)
*   [儲存和媒體處理](#storage-and-media-processing)
*   [隧道、WebRTC、Web Socket 伺服器和其他路由器](#tunneling-webrtc-web-socket-servers-and-other-routers)
*   [測試](#testing)
*   [團隊和協作工具](#tools-for-teams-and-collaboration)
*   [翻譯管理](#translation-management)
*   [流浪者相關](#vagrant-related)
*   [訪客會話錄音](#visitor-session-recording)
*   [虛擬主機](#web-hosting)
*   [評論平台](#commenting-platforms)
*   [基於瀏覽器的硬體仿真](#browser-based-hardware-emulation-written-in-javascript)
*   [遠端桌面工具](#remote-desktop-tools)
*   [遊戲開發](#game-development)
*   [其他免費資源](#other-free-resources)

主要雲端供應商
-------

*   [谷歌雲端平台](https://cloud.google.com)
    
    *   App Engine - 每天 28 小時前端實例，每天 9 小時後端實例
    *   Cloud Firestore - 1GB 儲存、每天 50,000 次讀取、20,000 次寫入、20,000 次刪除
    *   計算引擎 - 1 個非搶佔式 e2-micro、30GB HDD、5GB 快照儲存（僅限某些區域）、每月從北美到所有區域目的地（不包括中國和澳洲）的 1 GB 網路出站流量
    *   雲端儲存 - 5GB、1GB 網路出口
    *   Cloud Shell - 基於 Web 的 Linux shell/基本 IDE，具有 5GB 持久性儲存。每週限制 60 小時
    *   Cloud Pub/Sub - 每月 10GB 訊息
    *   雲端函數 - 每月 200 萬次呼叫（包括後台呼叫和 HTTP 呼叫）
    *   Cloud Run - 每月 200 萬個請求、360,000 GB 秒記憶體、180,000 vCPU 秒運算時間、每月來自北美的 1 GB 網路出站流量
    *   Google Kubernetes Engine - 一個可用區叢集不需要支付叢集管理費。每個用戶節點按標準 Compute Engine 定價收費
    *   BigQuery - 每月 1 TB 查詢，每月 10 GB 存儲
    *   雲端建置 - 每天 120 分鐘構建
    *   雲端來源儲存庫 - 最多 5 個使用者、50 GB 儲存、50 GB 出口
    *   [Google Colab](https://colab.research.google.com/) - 免費 Jupyter Notebooks 開發環境。
    *   完整、詳細的清單 - [https://cloud.google.com/free](https://cloud.google.com/free)
*   [亞馬遜網路服務](https://aws.amazon.com)
    
    *   [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出站量和每月 2M 次函數調用
    *   [Cloudwatch](https://aws.amazon.com/cloudwatch/) - 10 個自訂指標和 10 個警報
    *   [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分鐘的建置時間
    *   [CodeCommit](https://aws.amazon.com/codecommit/) - 5 個活躍用戶、50GB 儲存空間和每月 10000 個請求
    *   [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 個活動管道
    *   [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 資料庫
    *   [EC2](https://aws.amazon.com/ec2/) - 每月 750 小時的 t2.micro 或 t3.micro（12 個月）。每月 100GB 出站流量
    *   [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用 (SSD) 或磁性 (12mo)
    *   [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 每月 750 小時（12 個月）
    *   [RDS](https://aws.amazon.com/rds/) - 每月 750 小時的 db.t2.micro、db.t3.micro 或 db.t4g.micro、20GB 通用 (SSD) 儲存、20GB 儲存備份
    *   [Glacier](https://aws.amazon.com/glacier) - 10GB 長期物件存儲
    *   [Lambda](https://aws.amazon.com/lambda/) - 每月 100 萬個請求
    *   [SNS](https://aws.amazon.com/sns/) - 每月發布 100 萬次
    *   [SES](https://aws.amazon.com/ses/) - 每月 62.000 則訊息
    *   [SQS](https://aws.amazon.com/sqs/) - 100 萬個訊息佇列請求
    *   完整、詳細的清單 - [https://aws.amazon.com/free/](https://aws.amazon.com/free/)
*   [微軟Azure](https://azure.microsoft.com)
    
    *   [虛擬機器](https://azure.microsoft.com/services/virtual-machines/)\- 1 個 B1S Linux 虛擬機器、1 個 B1S Windows 虛擬機器 (12mo)
    *   [應用服務](https://azure.microsoft.com/services/app-service/)\- 10 個網路、行動或 API 應用（60 CPU 分鐘/天）
    *   [功能](https://azure.microsoft.com/services/functions/)\- 每月 100 萬個請求
    *   [開發測試實驗室](https://azure.microsoft.com/services/devtest-lab/)\- 實現快速、簡單且精實的開發測試環境
    *   [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 個對象
    *   [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月儲存 50,000 個用戶
    *   [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 個活躍用戶，無限的私人 Git 儲存庫
    *   [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 個免費平行作業，時間不限，適用於 Linux、macOS 和 Windows 開源
    *   [Microsoft IoT 中心](https://azure.microsoft.com/services/iot-hub/)\- 每天 8,000 則訊息
    *   [負載平衡器](https://azure.microsoft.com/services/load-balancer/)\- 1 個免費公共負載平衡 IP (VIP)
    *   [通知中心](https://azure.microsoft.com/services/notification-hubs/)\- 100 萬條推播通知
    *   [頻寬](https://azure.microsoft.com/pricing/details/bandwidth/)\- 每月 15GB 入站（12 個月）和 5GB 出站
    *   [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 5GB 儲存和 400 RU 的預配置吞吐量
    *   [靜態 Web 應用程式](https://azure.microsoft.com/pricing/details/app-service/static/)— 使用免費 SSL、驗證/授權和自訂網域建置、部署和託管靜態應用程式和無伺服器功能
    *   [儲存](https://azure.microsoft.com/services/storage/)\- 5GB LRS 檔案或 Blob 儲存（12 個月）
    *   [認知服務](https://azure.microsoft.com/services/cognitive-services/)\- AI/ML API（電腦視覺、翻譯器、臉部偵測、機器人...），提供免費套餐，包括有限的交易
    *   [認知搜尋](https://azure.microsoft.com/services/search/#features)\- 基於人工智慧的搜尋和索引服務，免費搜尋 10,000 個文檔
    *   [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 託管 Kubernetes 服務，免費叢集管理
    *   [事件網格](https://azure.microsoft.com/services/event-grid/)\- 100K 次操作/月
    *   完整、詳細的清單 - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)
*   [甲骨文雲](https://www.oracle.com/cloud/)
    
    *   計算
        *   2 個基於 AMD 的計算虛擬機，每個虛擬機具有 1/8 OCPU 和 1 GB 內存
        *   4 個基於 Arm 的 Ampere A1 核心和 24 GB 內存，可用作一台虛擬機或最多 4 台虛擬機
        *   實例[空閒時將被回收](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)
    *   區塊卷 - 2 個卷，總計 200 GB（用於計算）
    *   物件儲存 - 10 GB
    *   負載平衡器 - 1 個 10 Mbps 實例
    *   資料庫 - 2 個 DB，每個 20 GB
    *   監控 - 5 億個攝取資料點、10 億個檢索資料點
    *   頻寬 - 每月 10 TB 出口，基於 x64 的 VM 上的速度限制為 50 Mbps，基於 ARM 的 VM 上的速度限制為 500 Mbps \* 核心數
    *   公用 IP - 2 個用於虛擬機器的 IPv4，1 個用於負載平衡器的 IPv4
    *   通知 - 每月 100 萬個傳遞選項，每月發送 1000 封電子郵件
    *   完整、詳細的清單 - [https://www.oracle.com/cloud/free/](https://www.oracle.com/cloud/free/)
*   [IBM 雲端](https://www.ibm.com/cloud/free/)
    
    *   雲端函數 - 每月 500 萬次執行
    *   物件儲存 - 每月 25GB
    *   Cloudant 資料庫 - 1 GB 資料存儲
    *   Db2 資料庫 - 100MB 資料存儲
    *   API Connect - 每月 50,000 次 API 呼叫
    *   可用性監控 - 每月 300 萬個數據點
    *   日誌分析 - 500MB 每日日誌
    *   完整、詳細的清單 - [https://www.ibm.com/cloud/free/](https://www.ibm.com/cloud/free/)
*   [雲耀](https://www.cloudflare.com/)
    
    *   [應用程式服務](https://www.cloudflare.com/plans/)\- 適用於無限數量網域的免費DNS、DDoS 防護、CDN 以及免費SSL、防火牆規則和頁面規則、WAF、殭屍程式緩解、免費不限流量限制- 每個網域1 條規則、分析、電子郵件轉發
    *   [零信任和 SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 個使用者、24 小時活動記錄、3 個網路位置
    *   [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 您可以使用[快速隧道](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/run-tunnel/trycloudflare)，透過隧道將本地運行的 HTTP 連接埠公開到 trycloudflare.com 上的隨機子網域，無需帳戶。[零信任](https://www.cloudflare.com/products/zero-trust/)免費方案中的更多功能（TCP 隧道、負載平衡、VPN） 。
    *   [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 的全球網路上免費部署無伺服器程式碼。每天 10 萬個請求。
    *   [Workers KV](https://developers.cloudflare.com/kv) - 每天 100k 讀取請求、每天 1000 個寫入請求、每天 1000 個刪除請求、每天 1000 個清單請求、1 GB 儲存數據
    *   [R2](https://developers.cloudflare.com/r2/) - 每月 10 GB、每月 100 萬次 A 類操作、每月 1000 萬次 B 類操作
    *   [D1](https://developers.cloudflare.com/d1/) - 每天讀取 500 萬行，每天寫入 10 萬行，1 GB 存儲
    *   [Pages](https://developers.cloudflare.com/pages/) - 在 Cloudflare 快速、安全的全球網路上開發和部署您的 Web 應用程式。每月 500 個建置、100 個自訂網域、整合 SSL、無限免費席位、無限預覽部署以及透過 Cloudflare Workers 整合實現的全堆疊功能。
    *   [隊列](https://developers.cloudflare.com/queues/)\- 每月 100 萬次操作

**[⬆️回到頂部](#table-of-contents)**

雲端管理解決方案
--------

*   [Brainboard](https://www.brainboard.co) - 端到端視覺化建置和管理雲端基礎架構的協作解決方案。
*   [Cloud 66](https://www.cloud66.com/) - 免費用於個人專案（包括 1 個部署伺服器、1 個靜態網站），Cloud 66 為您提供在任何雲端上建置、部署和擴展應用程式所需的一切，而無需擔心「伺服器問題」。
*   [Pulumi](https://www.pulumi.com/) — 現代基礎設施即程式碼平台，讓您可以使用熟悉的程式語言和工具來建置、部署和管理雲端基礎架構。
*   [Selefra](https://www.selefra.io/) - Selefra 免費套餐為個人用戶提供掃描單一來源連線的功能，以發現雲端/基礎設施/SaaS 配置層級的安全性和合規性問題。
*   [terraform.io](https://www.terraform.io/) — Terraform 雲。最多 500 個資源的免費遠端狀態管理和團隊協作。
*   [scalr.com](https://scalr.com/) - Scalr 是一款 Terraform 自動化和協作 (TACO) 產品，用於在 Terraform 管理的基礎架構和配置上更好地協作和自動化。完全支援 Terraform CLI、與 OPA 整合和分層配置模型。沒有 SSO 稅。所有功能均包含在內。每月最多免費運行 50 次。

**[⬆️回到頂部](#table-of-contents)**

原始碼儲存庫
------

*   [Bitbucket](https://bitbucket.org/) — 最多 5 個使用者的無限公共和私人 Git 儲存庫，具有 CI/CD 管道
*   [chiselapp.com](https://chiselapp.com/) — 無限的公共和私人化石儲存庫
*   [codebasehq.com](https://www.codebasehq.com/) — 一個免費項目，擁有 100 MB 空間和 2 個用戶
*   [Codeberg.org](https://codeberg.org/) - 免費和開源專案的無限公共和私人 Git 儲存庫。使用[Codeberg Pages](https://codeberg.page/)託管靜態網站。
*   [GitGud－](https://gitgud.io)無限的私人和公共儲存庫。永遠免費。由 GitLab 和 Sapphire 提供支援。未提供 CI/CD。
*   [GitHub](https://github.com/) — 無限的公共儲存庫和無限的私人儲存庫（具有無限的協作者）。除此之外，還提供其他一些免費服務（還有更多，但我們在這裡列出了主要的服務）：
    *   [CI/CD](https://github.com/features/actions)（公開回購免費，私人回購免費 2000 分鐘/月）
    *   [Codespaces](https://github.com/codespaces) - 託管在雲端的開發環境。每月免費提供 120 個核心小時和 15 GB 代碼空間儲存。
    *   [靜態網站託管](https://pages.github.com)（免費用於公共儲存庫）
    *   [套件託管和容器註冊表](https://github.com/features/packages)（公共儲存庫免費，私人儲存庫免費使用 CI/CD 以外的 500 MB 儲存和 1GB 頻寬）
    *   專案管理和問題追蹤。
    *   [GitHub Copilot](https://github.com/features/copilot) — 由 OpenAI Codex 提供支援的 AI 配對程式設計師和完成工具。提供程式碼審查、自動完成、文件和重構。透過 GitHub 學生開發包向學生免費提供。
*   [gitlab.com](https://about.gitlab.com/) — 無限的公共和私人 Git 儲存庫，最多可容納 5 位協作者。也提供以下功能：
    *   [CI/CD](https://about.gitlab.com/product/continuous-integration)（公共回購免費，私人回購每月 400 分鐘）
    *   [帶有GitLab 頁面的](https://about.gitlab.com/product/pages)靜態網站。
    *   每個儲存庫的容器註冊表限制為 10 GB。
    *   專案管理和問題追蹤。
*   [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社群版的友善分支，為 Mercurial 提供支持
*   [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 開發應用程式的儲存庫和工具，您還有一個離子儲存庫
*   [NotABug](https://notabug.org) — NotABug.org 是一個免費軟體程式碼協作平台，適用於免費授權的項目，基於 Git
*   [OSDN](https://osdn.net/) - OSDN.net 是為開源軟體開發人員提供的免費服務，提供 SVN/Git/Mercurial/Bazaar/CVS 儲存庫等。
*   [Pagure.io](https://pagure.io) — Pagure.io 是一個免費開源軟體程式碼協作平台，適用於 FOSS 授權的項目，基於 Git
*   [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免費 1GB 雲端和 Git、Mercurial 或 SVN 儲存庫。
*   [pijul.com](https://pijul.com/) - 無限制的免費開源分散式版本控制系統。它的顯著特點是基於完善的補丁理論，這使得它易於學習和使用，並且真正分佈式。解決了git/hg/svn/darcs的許多問題。
*   [Plasticscm.com](https://plasticscm.com/) — 對個人、OSS 和非營利組織免費
*   [projectlocker.com](https://projectlocker.com) — 一個免費的私人專案（Git 和 Subversion），擁有 50 MB 空間
*   [RocketGit](https://rocketgit.com) — 基於 Git 的儲存庫託管。無限的公共和私人存儲庫。
*   [savannah.gnu.org](https://savannah.gnu.org/) - 充當自由軟體專案的協作軟體開發管理系統（針對 GNU 專案）
*   [savannah.nongnu.org](https://savannah.nongnu.org/) - 充當自由軟體專案（針對非 GNU 專案）的協作軟體開發管理系統

**[⬆️回到頂部](#table-of-contents)**

API、資料和機器學習
-----------

*   [IP.City](https://ip.city) — 每天 100 個免費 IP 地理定位請求
*   [A11yWatch](https://a11ywatch.com) - 強大的大規模網路無障礙工具。免費的網站範圍內的網路可訪問性測試及其他測試每天都會重置。
*   [抽象 API](https://www.abstractapi.com) — 適用於各種用例的 API 套件，包括 IP 地理定位、性別偵測甚至電子郵件驗證。
*   [Apify](https://www.apify.com/) - 網路抓取和自動化平台，可為任何網站建立 API 並提取資料。現成的抓取工具、整合代理程式和客製化解決方案。免費計劃，每月包含 5 美元的平台積分。
*   [API Mocha](https://apimocha.com) - 完全免費的線上 API 模擬，用於測試和原型設計。每天最多發出 500 個請求，完全可自訂的 API 回應，下載模擬規則作為 Postman 集合。
*   [APITemplate.io](https://apitemplate.io) - 使用簡單的 API 或 Zapier 和 Airtable 等自動化工具自動產生圖像和 PDF 文件。無需 CSS/HTML。免費方案包含 50 張圖像/月和 3 個模板。
*   [APIToolkit.io](https://apitoolkit.io) - 充分了解 API 和後端中發生的情況所需的所有工具。具有自動 API 合約驗證和監控功能。免費方案涵蓋每月最多 20,000 個請求的伺服器。
*   [Arize AI](https://arize.com/) - 用於模型監控和資料品質和效能漂移等根本問題的機器學習可觀測性。最多可免費使用兩個模型。
*   [Atlas 工具包](https://atlastk.org/)\- 用於開發可立即存取的單頁 Web 應用程式的輕量級程式庫。適用於 Java、Node.js、Perl、Python 和 Ruby。
*   [Beeceptor](https://beeceptor.com) - 在幾秒鐘內模擬休息 API，偽造 API 回應等等。每天免費 50 個請求、公共儀表板、開放端點（任何擁有儀表板連結的人都可以查看請求和回應）。
*   [bigml.com](https://bigml.com/) — 託管機器學習演算法。無限免費開發任務，每個任務限制 16 MB 資料。
*   [瀏覽 AI](https://www.browse.ai) — 在網路上擷取和監控資料。每月 50 個積分免費。
*   [Bruzu](https://bruzu.com/) — 自動化影像製作。使用 API、整合或無程式碼表產生大量影像變體。API 是免費的，附有浮水印。
*   [Calendarific](https://calendarific.com) - 適用於 200 多個國家的企業級公共假期 API 服務。免費方案包括每月 1000 次通話。
*   [Canopy](https://www.canopyapi.co/) - 用於 Amazon.com 產品、搜尋和類別資料的 GraphQL API。免費方案包括每月 100 次通話。
*   [Clarifai](https://www.clarifai.com) — 用於自訂人臉辨識和偵測的影像 API。能夠訓練AI模型。免費方案每月有 5000 次通話。
*   [Cloudmersive](https://cloudmersive.com/) — 實用 API 平台，可完全存取擴充功能的 API 函式庫，包括文件轉換、病毒掃描等，每月呼叫 800 次。
*   [Colaboratory](https://colab.research.google.com) — 基於 Web 的免費 Python 筆記型電腦環境，配備 Nvidia Tesla K80 GPU。
*   [Collect2](https://collect2.com) — 建立 API 端點來測試、自動化和連接 Webhooks。免費方案允許兩個資料集、2000 筆記錄、1 個轉發器和 1 個警報。
*   [商務層](https://commercelayer.io)\- 可組合的商務 API，可以從任何前端建立、下達和管理訂單。開發者計畫允許每月 100 個訂單和最多 1,000 個 SKU 免費。
*   [轉換工具](https://conversiontools.io/)\- 用於文件、圖像、視訊、音訊、電子書的線上文件轉換器。REST API 可用。Node.js、PHP、Python 的函式庫。支援最大 50 GB 的檔案（對於付費方案）。免費套餐受到檔案大小和每天轉換次數的限制。
*   [Coupler](https://www.coupler.io/) - 在應用程式之間同步的資料整合工具。它可以創建即時儀表板和報告、轉換和操作值、收集和備份見解。免費方案擁有無限用戶、每月 100 次運行、1000 行以及無限整合。
*   [CraftMyPDF](https://craftmypdf.com) - 使用拖放編輯器和簡單的 API 從可重複使用的範本自動產生 PDF 文件。免費方案包含每月 100 個 PDF 和 3 個範本。
*   [CurlHub](https://curlhub.io) — 用於檢查和偵錯 API 呼叫的代理服務。免費方案包括每月 10,000 個請求。
*   [CurrencyScoop](https://currencyscoop.com) - 用於金融科技應用程式的即時貨幣資料 API。免費方案包括每月 5000 次通話。
*   [Cube](https://cube.dev/) - Cube 幫助資料工程師和應用程式開發人員從現代資料儲存中存取數據，將其組織成一致的定義，並將其交付給每個應用程式。使用 Cube 最快的方法是使用 Cube Cloud，它有免費套餐，每月可使用 1GB 數據。
*   [資料擷取器](https://datafetcher.com)\- 無需程式碼即可將 Airtable 連接到任何應用程式或 API。用於在 Airtable 中執行 API 請求的類似 Postman 的介面。與數十個應用程式預先建立的整合。免費方案包括每月 100 次運行。
*   [Dataimporter.io](https://www.dataimporter.io) - 用於連接、清理資料並將資料匯入 Salesforce 的工具。免費方案每月最多包含 20,000 筆記錄。
*   [Datalore](https://datalore.jetbrains.com) - Jetbrains 的 Python 筆記本。包括 10 GB 儲存空間和每月 120 小時的運行時間。
*   [Data Miner](https://dataminer.io/) - 瀏覽器擴充功能（Google Chrome、MS Edge），用於從網頁 CSV 或 Excel 擷取資料。免費方案每月為您提供 500 頁。
*   [Datapane](https://datapane.com) - 用於在 Python 中建立互動式報告以及將 Python 腳本和 Jupyter Notebook 部署為自助服務工具的 API。
*   [DB-IP](https://db-ip.com/api/free) - 免費的 IP 地理定位 API，每個 IP 每天有 1k 請求。CC-BY 4.0 許可證下的 Lite 資料庫也是免費的。
*   [DB Designer](https://www.dbdesigner.net/) — 基於雲端的資料庫模式設計和建模工具，提供 2 個資料庫模型和每個模型 10 個表的免費入門計劃。
*   [DeepAR](https://developer.deepar.ai) — 具有一個 SDK 的適用於任何平台的擴增實境臉部濾鏡。免費方案提供最多 10 個每月活躍用戶 (MAU) 並追蹤最多 4 個面孔
*   [Deepnote](https://deepnote.com) - 一種新型數據科學筆記本。與 Jupyter 相容，可即時協作並在雲端運作。免費套餐包括無限的個人項目、長達 750 小時的標準硬體以及最多 3 名編輯的團隊。
*   [Diggernaut](https://www.diggernaut.com/) - 基於雲端的網路抓取和資料提取平台，用於將任何網站轉換為資料集或像使用 API 一樣使用它。免費方案包括每月 5K 頁面請求。
*   [疾病.sh](https://disease.sh/) — 一個免費的 API，為建立 Covid-19 相關的有用應用程式提供準確的數據。
*   [dreamfactory.com](https://dreamfactory.com/) — 適用於行動、Web 和 IoT 應用程式的開源 REST API 後端。連接任何 SQL/NoSQL 資料庫、檔案儲存系統或外部服務，它會立即建立一個全面的 REST API 平台，具有即時文件、使用者管理等功能。
*   [DynamicDocs](https://advicement.io) - 基於 LaTeX 模板，使用 JSON 到 PDF API 來產生 PDF 文件。免費方案允許每月 50 次 API 呼叫並存取模板庫。
*   [DynaPictures](https://dynapictures.com) - 設計自動化工具，可讓您透過 REST API 動態產生影像。即時變更顏色、文字、徽標和圖像。免費方案包括每月 30 張生成的圖像和 3 個圖像模板。
*   [Efemarai](https://efemarai.com) - ML 模型和資料的測試和調試平台。可視化任何計算圖。每月為開發人員免費提供 30 次調試會話。
*   [Einblick](https://www.einblick.ai/) - 一個現代資料科學平台，將 Python 筆記本引入協作畫布，並包含自動執行常見任務的工具，例如建立預測模型 (AutoML) 或比較群體。免費套餐包括 5 個畫布和無限個合作者。
*   [Exspanse](https://exspanse.com) - 用於建置、訓練和部署 ML 模型和 AI 解決方案的 MLOPS 平台。免費方案提供建立無限專案、5Gb 雲端儲存、5 個 Docker 容器映像的能力。
*   [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 基於 Web 的免費 HTTP 用戶端，用於傳送 HTTP 請求。
*   [Export SDK](https://exportsdk.com) - PDF 生成器 API，帶有拖放模板編輯器，還提供 SDK 和無程式碼整合。免費方案包含每月 250 頁、無限用戶和三個模板。
*   [file.coffee](https://file.coffee/) - 一個平台，您最多可以儲存 15MB/檔案（一個帳戶可儲存 30/MB 檔案）。
*   [Flatirons Fuse](https://flatironsdevelopment.com/products/fuse/) - 一款嵌入式 CSV 和電子表格匯入工具，可快速、輕鬆、輕鬆地將資料匯入您的網站。
*   [FraudLabs Pro](https://www.fraudlabspro.com) — 篩選訂單交易是否有信用卡支付詐欺行為。此 REST API 將根據訂單的輸入參數偵測所有可能的詐欺特徵。免費微型方案每月有 500 筆交易。
*   [Geekflare API](https://geekflare.com/api) - Geekflare API 可讓您截取螢幕截圖、審核網站、TLS 掃描、DNS 查找、測試 TTFB 等等。免費方案提供 3000 個 API 請求。
*   [GeoCod](https://geocod.xyz) — 免費地理編碼 API：將郵遞地址轉換為地理座標或將地理座標轉換為郵遞地址（反向地理編碼）。
*   [GeoDataSource](https://www.geodatasource.com) - 使用緯度和經度座標尋找城市名稱的位置搜尋服務。每月最多免費 API 查詢 500 次。
*   [Glitterly](https://glitterly.app/) - 以程式設計方式從基本模板產生動態影像。Restful API 和 nocode 整合。免費套餐每月提供 50 張圖片和 5 個範本。
*   [GoodData](https://www.gooddata.com/) - 資料即服務 - 建立互動式且富有洞察力的儀表板。免費方案包含 5 個工作區和 100 MB/工作區。
*   [Hex](https://hex.tech/) - 用於筆記本、資料應用程式和知識庫的協作資料平台。免費社群版本，最多可有 3 位作者和 5 個項目。每位作者一個具有 4GB RAM 的計算配置檔。
*   [Hook0](https://www.hook0.com/) - Hook0 是一個開源 Webhooks 即服務 (WaaS)，可讓線上產品輕鬆提供 Webhooks。每月發送多達 3,000 個事件，並免費保留 7 天的歷史記錄。
*   [Hoppscotch](https://hoppscotch.io) - 一個免費、快速且美觀的 API 請求產生器。
*   [Hybiscus](https://hybiscus.dev/) - 使用簡單的宣告式 API 建立 pdf 報告。免費套餐包括每月最多 100 個單頁報告，並且能夠自訂調色板和字體。
*   [Invantive Cloud](https://cloud.invantive.com/) — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）存取 70 多個（雲端）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma。包括資料複製和交換。為開發人員和實施顧問提供免費計劃。對於數據量有限的特定平台免費。
*   [ipaddress.sh](https://ipaddress.sh) — 取得不同[格式](https://about.ipaddress.sh/)的公用 IP 位址的簡單服務。
*   [ipbase.com](https://ipbase.com) - IP 地理定位 API - 永久免費計劃，每月涵蓋 150 個請求。
*   [Iploka](https://iploka.com/) — IP 到地理定位 API - 為開發人員提供永久免費計劃，每月限制 10k 請求。
*   [IP 地理定位](https://ipgeolocation.io/)— IP 地理定位 API - 為開發人員提供永久免費計劃，每月 30k 請求（1k/天）限制。
*   [IP 地理定位 API](https://www.abstractapi.com/ip-geolocation-api) — 摘要中的 IP 地理定位 API - 廣泛的免費計劃，每月允許 20,000 個請求。
*   [IP2Location](https://www.ip2location.com) — 免費增值 IP 地理定位服務。LITE 資料庫可供免費下載。匯入伺服器資料庫並進行本地查詢，確定城市、座標和ISP資訊。
*   [IP2Location.io](https://www.ip2location.io/) — 免費增值、快速可靠的 IP 地理定位 API，用於確定城市、座標、ISP 等地理定位資料。免費方案提供每月 30k 積分。訂閱付費方案以獲取更多高級功能，或聯絡我們以取得個人化方案。
*   [ipapi](https://ipapi.co/) - Kloudend, Inc 的 IP 位址定位 API - 可靠的地理定位 API，基於 AWS 構建，深受財富 500 強企業信賴。免費套餐提供每月 30,000 次查找（1,000 次/天），無需註冊。聯絡我們以取得更高限額的試用方案。
*   [IPinfo](https://ipinfo.io/) — 快速、準確且免費（高達 50k/月）的 IP 位址資料 API。提供包含地理位置、公司、營運商、IP 範圍、網域、濫用聯絡人等詳細資訊的 API。所有付費API均可免費試用。
*   [IPList](https://www.iplist.cc) — 尋找有關任何 IP 位址的詳細信息，例如 Geo IP 資訊、tor 位址、主機名稱和 ASN 詳細資訊。對個人和企業用戶免費。
*   [BigDataCloud](https://www.bigdatacloud.com/) - 為現代網路提供快速、準確且免費（無限製或高達 10K-50K/月）的 API，例如 IP 地理定位、反向地理編碼、網路洞察、電子郵件和電話驗證、客戶資訊等。
*   [IPTrace](https://iptrace.io) — 一個極為簡單的 API，可為您的企業提供可靠且有用的 IP 地理定位資料。
*   [JSON2Video](https://json2video.com) - 一種影片編輯 API，用於以程式設計方式或無程式碼自動化影片行銷和社群媒體影片。
*   [JSON IP](https://getjsonip.com) — 傳回要求的用戶端的公用 IP 位址。免費套餐無需註冊。可以使用客戶端 JS 直接從瀏覽器請求使用 CORS 資料。對於監控客戶端和伺服器 IP 變更的服務很有用。無限請求。
*   [konghq.com](https://konghq.com/) — API 市場以及用於私人和公共 API 的強大工具。對於免費套餐，某些功能受到限制，例如監控、警報和支援。
*   [Kreya](https://kreya.app) — 免費的 gRPC GUI 用戶端，用於呼叫和測試 gRPC API。可以透過伺服器反射導入 gRPC API。
*   [輕鬆](https://www.lightly.ai/)— 使用正確的數據來改善您的機器學習模型。免費使用最多 1000 個樣本的資料集。
*   [LoginLlama](https://loginllama.app) - 登入安全性 API，用於偵測詐欺和可疑登入並通知您的客戶。每月 1,000 次登入免費。
*   [MailboxValidator](https://www.mailboxvalidator.com) — 使用真實郵件伺服器連線來確認有效電子郵件的電子郵件驗證服務。免費 API 方案每月有 300 次驗證。
*   [Meteosource Weather API](https://www.meteosource.com/) — 用於當前和預報天氣資料的全球天氣 API。預測基於更多天氣模型的機器學習組合，以實現更高的準確性。免費套餐每天可撥打 400 通電話。
*   [microlink.io](https://microlink.io/) – 它將任何網站轉化為數據，例如元標記標準化、美容連結預覽、抓取功能或螢幕截圖即服務。每天 100 個請求免費。
*   [Monkeylearn.com](https://monkeylearn.com/) — 使用機器學習進行文字分析，每月免費 300 次查詢。
*   [MockAPI](https://www.mockapi.io/) — MockAPI 是一個簡單的工具，可讓您輕鬆模擬 API、產生自訂資料並使用 RESTful 介面對其執行操作。MockAPI 旨在用作原型設計/測試/學習工具。1 個項目/每個項目 4 個資源免費。
*   [Mockfly](https://www.mockfly.dev/) — Mockfly 是個值得信賴的 API 模擬和功能標誌管理開發工具。透過直覺的介面快速產生和控制模擬 API。免費套餐每天提供 500 個請求。
*   [Mocki](https://mocki.io) - 一個工具，可讓您建立同步到 GitHub 儲存庫的模擬 GraphQL 和 REST API。簡單的 REST API 無需註冊即可免費建立和使用。
*   [Mocko.dev](https://mocko.dev/) — 代理您的 API，免費選擇要在雲端中模擬的端點並檢查流量。加快您的開發和整合測試。
*   [Mocky](https://designer.mocky.io/) - 一個簡單的 Web 應用程序，用於產生自訂 HTTP 回應以模擬 HTTP 請求。也可以作為[開源版本](https://github.com/julien-lafont/Mocky)提供。
*   [reqres.in](https://reqres.in) - 一個免費託管的 REST-API，準備回應您的 AJAX 請求。
*   [microenv.com](https://microenv.com) — 為開發人員建立假 REST API，可以在 docker 容器中產生程式碼和應用程式。
*   [neptune.ai](https://neptune.ai/) - 記錄、儲存、顯示、組織、比較和查詢所有 MLOps 元資料。個人免費：1 名會員、100 GB 元資料儲存、200 小時監控/月
*   [新聞 API](https://newsapi.org) — 使用程式碼在網路上搜尋新聞，取得 JSON 結果。開發人員每月免費獲得 3,000 次查詢。
*   [Nordigen](https://nordigen.com) — 免費開放銀行資料 API。PSD2。將歐盟+英國的 2300 多家銀行與您的應用程式/軟體連接起來。
*   [Nyckel](https://www.nyckel.com) — 訓練、部署和呼叫圖像和文字 ML 模型。免費訓練，最多5000條訓練資料。每月免費調用 1000 次模型。
*   [Observable－](https://observablehq.com/)一個利用資料進行創建、協作和學習的地方。免費：無限筆記本，無限出版，每本筆記本五位編輯。
*   [OCR.Space](https://ocr.space/) — 一種 OCR API，可解析圖像和 pdf 文件，以 JSON 格式傳回文字結果。每月 25,000 個請求免費。
*   [Duply.co](https://duply.co) — 從 API 和 URL 建立動態影像，設計模板一次並重複使用。免費套餐每月可透過 API 和 URL 建立 70 張圖像，並透過表單建立最多 100 張圖像。
*   [OpenAPI3 Designer](https://openapidesigner.com/) — 免費直覺地建立 Open API 3 定義。
*   [Orchest](https://orchest.io) - 用於資料科學的可視化管道編輯器和工作流程編排器，1 個免費實例，提供開源版本。
*   [parsehub.com](https://parsehub.com/) — 從動態網站中提取數據，將動態網站轉換為 API，免費 5 個項目。
*   [pdfEndpoint.com](https://pdfendpoint.com) - 使用簡單的 API 輕鬆將 html 或 url 轉換為 pdf。每月 100 次免費轉換。
*   [PDF Factory](https://pdf-factory.com) - PDF 自動化 API、視覺化範本編輯器、動態資料整合和使用 API 的 PDF 渲染。免費方案附帶 1 個模板，每月 100 個 PDF。
*   [Pixela](https://pixe.la/) - 免費的日流資料庫服務。所有操作均透過API執行。也可以使用熱圖和折線圖進行視覺化。
*   [回發](https://postbacks.io/)\- 稍後請求 HTTP 回呼。註冊後可獲得 8,000 個免費請求。
*   [Postman](https://postman.com) — 使用 Postman（一個用於 API 開發的協作平台）簡化工作流程並更快地創建更好的 API。永久免費使用郵遞員應用程式。Postman 雲端功能也是永久免費的，但有一定限制。
*   [PrefectCloud](https://www.prefect.io/cloud/) — 資料流自動化的完整平台。所有方案均包含每月 20,000 次免費運行。對於大多數小型企業來說，這足以支援 ETL。
*   [Preset Cloud](https://preset.io/) - 託管的 Apache Superset 服務。對於最多 5 個使用者的團隊永遠免費，具有無限的儀表板和圖表、無程式碼圖表產生器和協作 SQL 編輯器。
*   [PromptLeo](https://promptleo.com/) - 為創作者和開發者提供的提示工程平台。提供提示工程庫、提示表單和提示工程API。免費方案提供 1 個提示表單、1 個提示 API 端點、每月 30 個代。
*   [PromptLoop](https://www.promptloop.com/) - 使用 AI 和 GPT-3 等大型語言模型以及單一簡單的電子表格公式來轉換、理解和分析 Google 表格中的文字。每月前 2,000 個積分免費。
*   [ProxyCrawl](https://proxycrawl.com/) — 無需代理、基礎設施或瀏覽器即可抓取和抓取網站。我們為您解決驗證碼並防止您被封鎖。前 1000 次通話免費。
*   [Public-Apis Github Repo](https://github.com/public-apis/public-apis) — 免費公共 API 清單。
*   [Supportivekoala](https://supportivekoala.com/) — 讓您透過範本輸入自動產生影像。免費方案可讓您每週創建最多 100 張圖像。
*   [QuickMocker](https://quickmocker.com/) — 在您自己的子網域下管理線上虛假API 端點，將請求轉送至localhost URL 進行Webhook 開發和測試，使用RegExp 和多種HTTP 方法作為URL 路徑，確定端點的優先權，以及用於回應模板的100 多個短代碼（動態或虛假回應值） ，從 JSON 格式的 OpenAPI (Swagger) 規​​格匯入，代理請求，透過 IP 位址和授權標頭限制端點。免費帳戶提供 1 個隨機子網域、10 個端點、5 個 RegExp URL 路徑、每個端點 50 個短代碼、每天 100 個請求、請求日誌中的 50 個歷史記錄。
*   [Rapidapi](https://rapidapi.com/) - 世界上最大的 API 中心 數以百萬計的開發人員發現並連接到數千個 API，使用有趣的挑戰（帶有解決方案！）和互動式範例進行 API 開發。
*   [RequestBin.com](https://requestbin.com) — 建立一個可以傳送 HTTP 請求給其的免費端點。傳送到該端點的任何 HTTP 請求都會與關聯的負載和標頭一起記錄，以便您可以觀察來自 Webhook 和其他服務的請求。
*   [Roboflow](https://roboflow.com) - 建立和部署自訂電腦視覺模型，無需具備機器學習經驗。免費套餐包含最多 1,000 張免費來源圖片。
*   [ROBOHASH](https://robohash.org/) - 從任何文字產生獨特（酷:）影像的 Web 服務。
*   [SaturnCloud](https://saturncloud.io/) - 資料科學雲端環境，允許運行 Jupyter 筆記本和 Dask 叢集。每月 30 小時免費計算和 3 小時 Dask。
*   [Scraper's Proxy](https://scrapersproxy.com) — 用於抓取的簡單 HTTP 代理 API。匿名抓取，無需擔心限制、封鎖或驗證碼。每月成功抓取的前 100 個免費，包括 javascript 渲染（如果您聯繫支援人員，可以獲取更多）。
*   [ScrapingAnt](https://scrapingant.com/) — 無頭 Chrome 抓取 API 和免費檢查代理服務。JavaScript 渲染、進階旋轉代理、避免驗證碼。提供免費方案。
*   [ScraperBox](https://scraperbox.com/) — 使用真正的 Chrome 瀏覽器和代理程式輪替的不可偵測的網頁抓取 API。使用簡單的 API 呼叫即可抓取任何網頁。免費方案每月有 1000 個請求。
*   [ScrapingDog](https://scrapingdog.com/) — Scrapingdog 處理數百萬個代理程式、瀏覽器和驗證碼，以便在單一 API 呼叫中為您提供任何網頁的 HTML。它還提供了適用於 Chrome 和 Firefox 的 Web Scraper 以及滿足即時抓取需求的軟體。提供免費方案。
*   [scrapinghub.com](https://scrapinghub.com) — 使用視覺化介面和外掛程式進行資料抓取。免費方案包括在共享伺服器上無限制地抓取。
*   [Simplescraper](https://simplescraper.io) — 每次操作後觸發您的 webhook。免費方案包括 100 個雲端抓取積分。
*   [Select Star](https://www.selectstar.com/) - 是一個智慧數據發現平台，可自動分析和記錄您的數據。免費的輕型層，具有 1 個資料來源、最多 100 個表格和最多 10 個使用者。
*   [Sheetson](https://sheetson.com) - 立即將任何 Google Sheets 轉換為 RESTful API。提供免費方案。
*   [Shipyard](https://www.shipyardapp.com) — 用於雲端的低程式碼資料編排平台。混合使用低程式碼模板和您的程式碼（Python、Node.js、Bash、SQL）進行建置。我們的免費開發者計劃每月為一名用戶提供 10 小時的運行時間 - 足以自動化多個工作流程。
*   [shrtcode API](https://shrtco.de/docs) - 免費 URL 縮短 API，無需授權，無請求限制。
*   [SerpApi](https://serpapi.com/) - 即時搜尋引擎抓取 API。返回 Google、Youtube、Bing、百度、沃爾瑪和許多其他引擎的結構化 JSON 結果。免費方案包括每月 100 次成功的 API 呼叫。
*   [Sofodata](https://www.sofodata.com/) - 從 CSV 檔案建立安全的 RESTful API。上傳 CSV 檔案並透過其 API 立即存取數據，從而加快應用程式開發速度。免費方案包括 2 個 API 和每月 2,500 次 API 呼叫。無需信用卡。
*   [Stoplight](https://stoplight.io/) - 用於協作設計和記錄 API 的 Saas。免費方案提供免費的設計、模擬和文件工具來幫助您入門。
*   [Svix](https://www.svix.com/) - Webhooks 即服務。每月免費發送多達 50,000 條訊息。
*   [TemplateTo](https://templateto.com) - 使用我們的拖放編輯器和簡單的 API 從可重複使用的範本自動產生 PDF/TXT 文件。免費方案包含 450 個 PDF/月和 3 個範本。
*   [TinyMCE](https://www.tiny.cloud) - 富文本編輯 API。核心功能免費，無限制使用。
*   [Webhook Store](https://www.openwebhook.io) - 用於儲存第三方 Webhook 並在本機上偵錯它們的工具（ngrok 風格）。開源且可自行託管。免費個人網域_使用者名稱_.github.webhook.store，免費公共網域_任何內容_.webhook.store。
*   [權重和偏差](https://wandb.ai)— 開發人員優先的 MLOps 平台。透過實驗追蹤、資料集版本控制和模型管理，更快地建立更好的模型。免費方案僅適用於個人項目，包含 100 GB 儲存空間。
*   [wit.ai](https://wit.ai/) — 開發人員的 NLP。
*   [Wolfram.com](https://wolfram.com/language/) — 雲端內建知識為基礎的演算法。
*   [wrapapi.com](https://wrapapi.com/) — 將任何網站變成參數化 API。每月 30,000 次 API 呼叫。
*   [ZenRows](https://www.zenrows.com/) — Web 抓取 API 和代理伺服器，可繞過任何反機器人解決方案，同時提供 JavaScript 渲染、旋轉代理程式和地理定位。1000 次 API 呼叫的免費方案。
*   [Zenscrape](https://zenscrape.com/web-scraping-api) — 具有無頭瀏覽器、住宅 IP 和簡單定價的 Web 抓取 API。每月 1000 次免費 API 調用，為學生和非營利組織提供額外免費積分。
*   [ip-api](https://ip-api.com) — IP 地理定位 API，免費用於非商業用途，無需 API 金鑰，免費方案的相同 IP 位址限制為 45 個請求/分鐘。
*   [WebScraping.AI](https://webscraping.ai) - 簡單的 Web Scraping API，具有內建解析、Chrome 渲染和代理程式。每月 2000 次免費 API 呼叫。
*   [Zipcodebase](https://zipcodebase.com) - 免費郵遞區號 API，存取全球郵遞區號資料。每月 10000 個免費請求。
*   [Huggingface.co](https://huggingface.co) - 為 Pytorch、TensorFlow 和 JAX 建置、訓練和部署 NLP 模型。每個月可釋放多達 30k 個輸入字元。
*   [vatcheckapi.com](https://vatcheckapi.com) - 簡單且免費的增值稅號驗證 API。每月 500 個免費請求。
*   [numlookupapi.com](https://numlookupapi.com) - 免費電話號碼驗證 API - 每月 10 萬個免費請求。
*   [Volca](https://volca.io#api) - 免費 API，提供程式語言和資料庫系統等技術清單。無限制的免費請求。
*   [Query.me](https://query.me) - 協作資料筆記本，以類似腳本的方式執行，並允許透過 SQL、API 和越來越多的自訂區塊（如 Slack 和電子郵件）取得和傳送資料。小型團隊免費。
*   [ERD Lab](https://www.erdlab.io) — 為開發人員製作的基於雲端的免費實體關係圖 (ERD) 工具。
*   [區別是什麼](https://whatthediff.ai)\- AI 支援的代碼審查助手。免費方案的限制為每月 25,000 個代幣（約 10 個 PR）。
*   [Zipcodestack](https://zipcodestack.com) - 免費郵遞區號 API 和郵遞區號驗證。每月 10000 個免費請求。

**[⬆️回到頂部](#table-of-contents)**

神器倉庫
----

*   [Artifactory](https://jfrog.com/start-free/) - 一個工件儲存庫，支援多種套件格式，例如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS。包括包掃描工具 XRay 和 CI/CD 工具 Pipelines（以前稱為 Shippable），每月免費使用 2,000 CI/CD 分鐘。
*   [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他建置系統的預設工件儲存庫。
*   [cloudrepo.io](https://cloudrepo.io) - 基於雲端的私有和公有、Maven 和 PyPi 儲存庫。對於開源專案免費。
*   [cloudsmith.io](https://cloudsmith.io) — 適用於 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等的簡單、安全且集中的儲存庫服務。免費層+免費開源。
*   [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 專案的 Maven 儲存庫，對公共專案免費。
*   [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — 易於使用的儲存庫託管：Maven、RPM、DEB、PyPi、NPM 和 RubyGem 套件（有免費套餐）。
*   [repsy.io](https://repsy.io) — 1 GB 免費的私人/公共 Maven 儲存庫。
*   [Gemfury](https://gemfury.com) - Maven、PyPi、NPM、Go Module、Nuget、APT、RPM 儲存庫的私人和公共工件儲存庫。免費用於公共項目。
*   [paperspace](https://www.paperspace.com/) — 建立和擴展 AI 模型，開發、訓練和部署 AI 應用程序，免費規劃：公共專案、5Gb 儲存、基本實例。

**[⬆️回到頂部](#table-of-contents)**

團隊和協作工具
-------

*   [3Cols](https://3cols.com/) - 一個免費的基於雲端的程式碼片段管理器，用於個人和協作程式碼。
*   [Bitwarden](https://bitwarden.com) — 個人、團隊和商業組織儲存、共享和同步敏感資料的最簡單、最安全的方式。
*   [Braid](https://www.braidchat.com/) — 專為團隊設計的聊天應用程式。公共存取群組免費，使用者、歷史記錄和整合不受限制。它還提供可自架的開源版本。
*   [cally.com](https://cally.com/) — 尋找召開會議的最佳時間和日期。使用簡單，非常適合小型和大型團體。
*   [Calendly](https://calendly.com) — Calendly 是用來連結和安排會議的工具。免費方案為每個使用者提供 1 個日曆連線和無限次會議。還提供桌面和行動應用程式。
*   [Discord](https://discord.com/) — 與公共/私人房間聊天。Markdown 文字、語音、視訊和螢幕分享功能。免費供無限用戶使用。
*   [Telegram](https://telegram.org/) — Telegram 適合所有想要快速可靠的訊息和通話的人。商業用戶和小型團隊可能喜歡大型群組、用戶名、桌面應用程式和強大的文件共享選項。
*   [Duckly](https://duckly.com/) — 與您的團隊即時交談和協作。與任何 IDE 配對程式設計、終端機分享、語音、視訊和螢幕分享。小團隊免費。
*   [Dyte](https://dyte.io) - 對開發人員最友好的即時視訊和音訊 SDK，具有協作插件以提高生產力和參與度。免費套餐包括每月 10,000 分鐘的即時視訊/音訊使用量。
*   [Evernote.com](https://evernote.com/) — 組織資訊的工具。分享您的筆記並與其他人一起工作
*   [Fibery](https://fibery.io/) — 連結的工作空間平台。單一用戶免費，最多 2 GB 磁碟空間。
*   [Filestash](https://www.filestash.app) — 類似 Dropbox 的檔案管理器，可連接到一系列協定和平台：S3、FTP、SFTP、Minio、Git、WebDAV、Backblaze、LDAP 等。
*   [flock.com](https://flock.com) — 為您的團隊提供更快的溝通方式。免費無限訊息、頻道、用戶、應用程式和集成
*   [聚會](https://www.gather.town/)\- 更好的線上見面方式。Gather 以完全可自訂的空間為中心，讓您與社區共度時光就像現實生活一樣輕鬆。最多 10 個並髮用戶免費。
*   [gokanban.io](https://gokanban.io) - 基於語法，無需註冊看板即可快速使用。免費，沒有任何限制。
*   [flat.social](https://flat.social) - 用於團隊會議和歡樂時光社交的互動式可自訂空間。無限次會議，最多可免費容納 8 個並髮用戶。
*   [GitDailys](https://gitdailies.com) - 團隊在 GitHub 上提交和拉取請求活動的每日報告。包括推送視覺化工具、同儕識別系統、自訂警報產生器。免費方案擁有無限用戶、3 個儲存庫、3 個警報配置。
*   [gitter.im](https://gitter.im/) — 聊天，用於 GitHub。無限制的公共和私人房間，最多 25 人的團隊免費
*   [Hackmd.io](https://hackmd.io/) - 用於 Markdown 格式文件/文件的即時協作和編寫工具。與 GoogleDocs 類似，但適用於 Markdown 文件。免費無限數量的“筆記”，但私人筆記和模板的協作者（受邀者）數量[將受到限制](https://hackmd.io/pricing)。
*   [hangouts.google.com](https://hangouts.google.com/) — 一個可以進行所有對話的地方，免費，需要一個 Google 帳戶
*   [HeySpace](https://hey.space) - 具有聊天、行事曆、時間軸和視訊通話功能的任務管理工具。最多 5 位用戶免費。
*   [helplightning.com](https://www.helplightning.com/) — 透過擴增實境影片提供協助。免費，無需分析、加密、支持
*   [ideascale.com](https://ideascale.com/) — 允許客戶提交想法並投票，1 個社區的 25 名成員免費
*   [Igloo](https://www.igloosoftware.com/) — 用於共用文件、部落格和日曆等的內部入口網站。最多可免費容納 10 位使用者。
*   [Keybase](https://keybase.io/) — Keybase 是 Slack 的一個很酷的 FOSS 替代品，它可以保證每個人的聊天和文件的安全，從家庭到社區再到公司。
*   [Google Meet](https://meet.google.com/) — 使用 Google Meet 滿足您企業的線上視訊會議需求。Meet 提供安全、易於加入的線上會議。
*   [/meet for Slack](https://meetslack.com) - 透過在任何頻道、群組或 DM 中使用 /meet 直接從 Slack 啟動 Google 會議。免費，沒有任何限制。
*   [Livecycle](https://www.livecycle.io/) — Livecycle 是一個包容性協作平台，讓跨職能產品團隊和開源專案的工作流程變得順暢。
*   [標記](https://www.markup.io/)— 標記可讓您直接在網站、PDF 和圖像上收集回饋。
*   [可視化調試](https://visualdebug.com)\- 用於更好的客戶端與開發人員溝通的可視化反饋工具
*   [meet.jit.si](https://meet.jit.si/) — 一鍵視訊對話、螢幕分享，免費
*   [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams 是一個基於聊天的數位中心，可透過單一體驗將對話、內容和應用程式匯集到一個地方。最多 50 萬用戶免費。
*   [Miro](https://miro.com/) - 適用於分散式團隊的可擴展、安全、跨裝置和企業級團隊協作白板。具有免費增值方案。
*   [nootiz](https://www.nootiz.com/) - 用於收集和管理任何網站上的視覺回饋的首選工具
*   [Notion](https://www.notion.so/) -Notion 是一款筆記和協作應用程序，支援 Markdown，還整合了任務、wiki 和資料庫。該公司將該應用程式描述為一個用於記筆記、專案管理和任務管理的一體化工作空間。除了跨平台應用程式之外，還可以透過大多數網頁瀏覽器存取它。
*   [Nuclino](https://www.nuclino.com) - 一個輕量級的協作式 wiki，包含您團隊的所有知識、文件和註解。免費方案包含所有基本功能，最多 50 個項目，5GB 總儲存空間。
*   [OnlineInterview.io](https://onlineinterview.io/) - 免費程式碼面試平台，具有嵌入式視訊聊天、繪圖板和線上程式碼編輯器，您可以在瀏覽器上編譯和運行程式碼。一鍵創建遠端面試室。
*   [Quidlo 時間表](https://www.quidlo.com/timesheets)\- 適合團隊的簡單時間表和時間追蹤應用程式。免費方案具有時間追蹤和產生報告功能，最多可供 10 個用戶使用。
*   [PageShare.dev](https://www.pageshare.dev) - 將視覺評論功能新增至 GitHub Pull 要求中，無需部署網站。每月最多可免費使用 10 頁，總共可免費使用 100MB 的儲存空間。
*   [Pendulums](https://pendulums.io/) - Pendulums 是一款免費時間追蹤工具，透過易於使用的介面和有用的統計數據，幫助您更好地管理時間。
*   [Pumble](https://pumble.com) - 免費團隊聊天應用程式。無限用戶和訊息歷史記錄，永久免費。
*   [Raindrop.io](https://raindrop.io) - 適用於 macOS、Windows、Android、iOS 和 Web 的私密且安全的書籤應用程式。免費無限書籤和協作。
*   [element.io](https://element.io/) — 一種基於 Matrix 的去中心化開源通訊工具。群組聊天、直接訊息、加密檔案傳輸、語音和視訊聊天以及與其他服務的輕鬆整合。
*   [Rocket.Chat](https://rocket.chat/) - 具有全通路功能、矩陣聯盟、與其他應用程式橋接、無限訊息傳遞和完整訊息傳遞歷史記錄的開源通訊平台。
*   [seafile.com](https://www.seafile.com/) — 私人或雲端儲存、文件共享、同步、討論。私人版本已滿。雲端版只有1GB
*   [Sema](https://www.semasoftware.com/) - 免費的開發人員組合工具，能夠將多個儲存庫的貢獻合併並快照到單一報表中。
*   [Slab－](https://slab.com/)團隊為本的現代知識管理服務。最多 10 位用戶免費。
*   [slack.com](https://slack.com/) — 免費供無限用戶使用，但有一些功能限制
*   [Spectrum](https://spectrum.chat/) - 免費創建公共或私人社區。
*   [StatusPile](https://www.statuspile.com/) - 狀態頁面的狀態頁面。追蹤上游提供者的狀態頁面。
*   [Stickies](https://stickies.app/) - 用於腦力激盪、內容管理和筆記的視覺協作應用程式。最多可免費使用 3 面牆、無限用戶、1 GB 儲存空間。
*   [talky.io](https://talky.io/) — 免費群組視訊聊天。匿名的。點對點。無需外掛、註冊或付款
*   [Teamhood](https://teamhood.com/) - 免費專案、任務和問題追蹤軟體。透過泳道和完整的 Scrum 實作支援看板。具有整合的時間追蹤。免費供 5 個使用者和 3 個項目組合使用。
*   [Teamplify](https://teamplify.com) - 透過團隊分析和智慧每日站會改善團隊開發流程。包括針對遠端優先團隊的全功能休假管理。最多 5 位用戶的小型團隊免費。
*   [Tefter](https://tefter.io) - 具有強大 Slack 整合的書籤應用程式。對開源團隊免費。
*   [TeleType](https://teletype.oorja.io/) — 共用終端、語音、程式碼、白板等。無需登錄，為開發人員提供端對端加密協作。
*   [TimeCamp](https://www.timecamp.com/) - 無限用戶的免費時間追蹤軟體。輕鬆與 Jira、Trello、Asana 等 PM 工具整合。
*   [twist.com](https://twist.com) — 一款非同步友好的團隊溝通應用程序，對話保持井井有條且切題。提供免費和無限的計劃。為符合資格的團隊提供折扣。
*   [tldraw.com](https://tldraw.com) — 免費開源白板和圖表工具，具有智慧箭頭、捕捉、便箋和 SVG 匯出等功能。用於協作編輯的多人遊戲模式。也提供免費的官方 VS Code 擴充。
*   [BookmarkOS.com](https://bookmarkos.com) - 可自訂線上桌面中的免費一體化書籤管理器、標籤管理器和任務管理器，具有資料夾協作功能。
*   [typetalk.com](https://www.typetalk.com/) — 透過網路或行動裝置上的即時訊息與您的團隊分享和討論想法
*   [Tugboat](https://tugboat.qa) - 預覽每個拉取請求，自動化且按需。所有人免費，非營利組織免費獲得 Nano 等級。
*   [Which.com](https://whereby.com/) — 一鍵式視訊對話，免費（以前稱為appear.in）
*   [Windmill.dev](https://windmill.dev/) - Windmill 是一個開源開發人員平台，可透過最少的 Python 和 Typescript 腳本快速建立生產級多步驟自動化和內部應用程式。您可以創建最多 3 個非高級工作區並成為免費用戶。
*   [vadoo.tv](https://vadoo.tv/) — 影片託管和行銷變得簡單。只需單擊即可上傳影片。記錄、管理、分享等等。免費套餐每月提供最多 10 個影片、1 GB 儲存空間、10 GB 頻寬
*   [userforge.com](https://userforge.com/) - 互連的線上角色、使用者故事和上下文映射。協助維持設計和開發同步，最多可免費供 3 個角色和 2 個協作者使用。
*   [wistia.com](https://wistia.com/) — 影片託管，具有觀眾分析、高清影片傳輸和行銷工具，可協助了解您的訪客、25 個影片和 Wistia 品牌播放器
*   [wormhol.org](https://www.wormhol.org/) — 簡單的文件分享服務。與任意數量的同伴共享高達 5GB 的無限檔案。
*   [Zoom.us](https://zoom.us/) — 安全視訊和網路會議，提供附加元件。免費限時40分鐘
*   [shtab.app](https://shtab.app/) - 專案管理服務，透過基於人工智慧的追蹤器使辦公室協作和遠端透明。
*   [Zulip](https://zulip.com/) — 使用獨特的類似電子郵件的線程模型進行即時聊天。免費方案包括 10,000 條搜尋紀錄訊息和高達 5 GB 的檔案儲存空間。它還提供可自架的開源版本。
*   [robocorp.com](https://robocorp.com) - 用於為自動化營運提供支援的開源堆疊。免費試用雲端功能並實施簡單的自動化。機器人工作 240 分鐘/月，助手運行 10 次，儲存空間 100 MB。
*   [Fleep.io](https://fleep.io/) — Fleep 是 Slack 的替代品。它為小型團隊提供免費計劃，具有完整的訊息歷史記錄、無限的 1:1 對話、1 組對話和 1 GB 檔案儲存空間。
*   [Chanty.com](https://chanty.com/) — Chanty 是 Slack 的另一個替代品。它為小型團隊（最多10 人）提供永久免費計劃，提供無限的公共和私人對話、可搜尋的歷史記錄、無限的1:1 音訊通話、無限的語音訊息、10 個整合以及每個團隊20 GB的儲存空間。
*   [ruttl.com](https://ruttl.com/) — 最好的一體化回饋工具，用於收集數位回饋和評論網站、PDF 和圖像。
*   [Mattermost](https://mattermost.com/) — 技術團隊的安全協作。免費計劃，包含無限頻道、劇本、看板、用戶、10GB 儲存空間等。
*   [Webvizio](https://webvizio.com) — 網站回饋工具、網站審查軟體和錯誤報告工具，用於直接在即時網站和 Web 應用程式、圖像、PDF 和設計文件上簡化任務的 Web 開發協作。
*   [Pullflow](https://pullflow.com) — Pullflow 提供了一個 AI 增強平台，用於在 GitHub、Slack 和 VS Code 進行程式碼審查協作。
*   [Webex](https://www.webex.com/) — 視訊會議免費計劃，每次會議 40 分鐘，有 100 名與會者。
*   [RingCentral](https://www.ringcentral.com/) — 視訊會議免費計劃，每次會議 50 分鐘，有 100 名參與者。

**[⬆️回到頂部](#table-of-contents)**

內容管理系統
------

*   [acquia.com](https://www.acquia.com/) — Drupal 網站的託管。開發者免費套餐。也提供免費開發工具（例如 Acquia Dev Desktop）
*   [內容豐富](https://www.contentful.com/)——無頭 CMS。雲端中的內容管理和交付 API。附帶 1 個免費社區空間，其中包括 5 個用戶、25K 筆記錄、48 種內容類型、2 個區域設定。
*   [Cosmic](https://www.cosmicjs.com/) — 無頭 CMS 和 API 工具包。為開發人員提供免費的個人計劃。
*   [Crystallize－](https://crystallize.com)具有電子商務支援的無頭 PIM。內建 GraphQL API。免費版本包括無限用戶、1000 個目錄項目、5 GB/月頻寬和 25k/月 API 呼叫。
*   [DatoCMS](https://www.datocms.com/) - 為小型專案提供免費套餐。DatoCMS 是一個基於 GraphQL 的 CMS。在較低層，您每月有 10 萬次通話。
*   [Directus](https://directus.io) — 無頭 CMS。一個完全免費的開源平台，用於管理本地或雲端的資產和資料庫內容。沒有限製或付費牆。
*   [FrontAid](https://frontaid.io/) — 無頭 CMS，將 JSON 內容直接儲存在您自己的 Git 儲存庫中。無限制。
*   [kontent.ai](https://www.kontent.ai) - 內容即服務平台，為您提供無頭 CMS 的所有優勢，同時為行銷人員提供支援。開發人員計劃為 2 個用戶提供無限的項目，每個用戶有 2 個環境、500 個內容項目、2 種語言（帶交付和管理 API）以及自訂元素支援。更大的計劃可滿足您的需求。
*   [Prismic](https://www.prismic.io/) — 無頭 CMS。具有完全託管和可擴展 API 的內容管理介面。社群計畫為 1 位使用者提供無限的 API 呼叫、文件、自訂類型、資產和區域設定。您下一個項目所需的一切。更大的免費方案可用於開放內容/開源專案。
*   [Sanity.io](https://www.sanity.io/) - 結構化內容平台，配有開源編輯環境和即時託管資料儲存。無限的項目。無限的管理員使用者、3 個非管理員使用者、2 個資料集、500K API CDN 請求、10GB 頻寬、每個專案免費包含 5GB 資源。
*   [sensenet](https://sensenet.com) - API 優先的無頭 CMS，為各種規模的企業提供企業級解決方案。開發人員計畫提供 3 個使用者、500 個內容項目、3 個內建角色、25+5 種內容類型、完全可存取的 REST API、文件預覽產生和 Office Online 編輯。
*   [TinaCMS](https://tina.io/) — 取代 Forestry.io。支援 Markdown、MDX 和 JSON 的開源 Git 支援的無頭 CMS。基本優惠是免費的，有兩個用戶可用。
*   [GatsbyjsCMS](https://www.gatsbyjs.com/) - Gatsby 是一個快速、靈活的框架，使使用任何 CMS、API 或資料庫建立網站再次變得有趣。建立和部署無頭網站，以吸引更多流量、更好地轉換並賺取更多收入！
*   [Hygraph](https://hygraph.com/) - 為小型專案提供免費套餐。GraphQL 第一個 API。從傳統解決方案轉向 GraphQL 原生 Headless CMS，並首先提供全通路內容 API。
*   [Squidex](https://squidex.io/) - 為小型專案提供免費套餐。首先是 API/GraphQL。開源，基於事件來源（自動處理每個變更）。
*   [InstaWP](https://instawp.com/) - 在幾秒鐘內啟動 WordPress 網站。免費套餐包含：5 個活動站點、500 MB 空間、48 小時站點過期。
*   [Storyblok](https://www.storyblok.com) - 開發人員和行銷人員的無頭 CMS，可與所有現代框架配合使用。社群（免費）層提供管理API、視覺化編輯器、10 個資料來源、自訂欄位類型、國際化（無限語言/區域設定）、資產管理器（最多2500 個資產）、影像最佳化服務、搜尋查詢、 Webhook + 250GB 流量/月包含。

**[⬆️回到頂部](#table-of-contents)**

程式碼生成
-----

*   [Appinvento](https://appinvento.io/) — AppInvento 是一個免費的無程式碼應用程式建構器。在自動產生的後端程式碼中，使用者可以完全存取原始碼以及無限的API和路由，從而可以進行廣泛的整合。免費方案包括三個項目、五個表格和一個 Google 外掛程式。
*   [DhiWise](https://www.dhiwise.com/) — 利用 DhiWise 的創新代碼生成技術將 Figma 設計無縫轉化為動態 Flutter 和 React 應用程序，優化您的工作流程並幫助您比以往更快地打造卓越的移動和 Web 體驗。
*   [Codeium](https://www.codeium.com/) — Codeium 是一款免費的 AI 驅動的代碼完成工具。它支援 20 多種程式語言（Python、JavaScript、Java、TypeScript、PHP、C/C++、Go 等），並與所有主要的獨立和 Web IDE 整合。
*   [Metalama](https://www.postsharp.net/metalama) - 僅適用於 C#。Metalama 在編譯過程中動態產生程式碼樣板，以便您的原始碼保持乾淨。它對開源專案完全免費，其商業友好的免費層包括 3 個方面。
*   [tabnine.com](https://www.tabnine.com/) — Tabnine 透過提供從世界上所有程式碼中學到的見解，幫助開發人員更快地創建更好的軟體。插件可用。

**[⬆️回到頂部](#table-of-contents)**

代碼品質
----

*   [beanstalkapp.com](https://beanstalkapp.com/) — 編寫、審查和部署程式碼的完整工作流程），1 個使用者的免費帳戶和 1 個具有 100 MB 儲存空間的儲存庫
*   [browserling.com](https://www.browserling.com/) — 即時互動跨瀏覽器測試，在 Vista 下以 1024 x 768 解析度與 MS IE 9 進行僅 3 分鐘的免費會話
*   [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自動程式碼審查，免費提供無限的公共和私人儲存庫
*   [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 用於 DevOps 的自動化基礎架構作為程式碼審查工具，與 GitHub、Bitbucket 和 GitLab（甚至是自架）整合。除了標準語言之外，它還分析 Ansible、Terraform、CloudFormation、Kubernetes 等。（開源免費）
*   [CodeBeat](https://codebeat.co) — 適用於多種語言的自動程式碼審查平台。透過 Slack 和電子郵件集成，公共儲存庫永久免費。
*   [codeclimate.com](https://codeclimate.com/) — 自動程式碼審查，免費開放原始碼和無限的組織擁有的私人儲存庫（最多 4 個合作者）。學生和機構也免費。
*   [codecov.io](https://codecov.io/) — 程式碼覆蓋率工具 (SaaS)，免費開源和 1 個免費私人儲存庫
*   [CodeFactor](https://www.codefactor.io) — Git 的自動程式碼審查。免費版本包括無限用戶、無限公共儲存庫和 1 個私人儲存庫。
*   [codescene.io](https://codescene.io/) - CodeScene 根據開發人員如何使用程式碼來確定技術債的優先級，並視覺化團隊耦合和系統掌握等組織因素。免費開源。
*   [CodSpeed](https://codspeed.io) - 自動追蹤 CI 管道中的效能。借助精確且一致的指標，在部署之前捕獲效能回歸。開源專案永久免費。
*   [coveralls.io](https://coveralls.io/) — 顯示測試覆蓋率報告，免費開源
*   [dareboost](https://dareboost.com) - 每月 5 份關於網路效能、可近性、安全性的免費分析報告
*   [deepcode.ai](https://www.deepcode.ai) — DeepCode 基於 AI 發現錯誤、安全漏洞、效能和 API 問題。DeepCode 的分析速度使我們能夠即時分析您的程式碼，並在您點擊 IDE 中的儲存按鈕時提供結果。支援的語言包括 Java、C/C++、JavaScript、Python 和 TypeScript。與 GitHub、BitBucket 和 GitLab 整合。對於開源和私人儲存庫免費，最多可免費供 30 名開發人員使用。
*   [deepscan.io](https://deepscan.io) — 進階靜態分析，用於自動尋找 JavaScript 程式碼中的執行時間錯誤，免費開源
*   [DeepSource](https://deepsource.io/) - DeepSource 不斷分析原始碼更改，尋找並修復按安全性、效能、反模式、錯誤風險、文件和風格分類的問題。與 GitHub、GitLab 和 Bitbucket 的本機整合。
*   [Eversql.com](https://www.eversql.com/) — EverSQL - #1 資料庫最佳化平台。自動神奇地獲得對資料庫和 SQL 查詢的重要見解。
*   [gerrithub.io](https://review.gerrithub.io/) — 免費的 GitHub 儲存庫的 Gerrit 程式碼審查
*   [gocover.io](https://gocover.io/) — 任何[Go](https://golang.org/)套件的程式碼覆蓋率
*   [goreportcard.com](https://goreportcard.com/) — Go 專案的程式碼質量，免費開源
*   [gtmetrix.com](https://gtmetrix.com/) — 優化網站的報告和全面建議
*   [Wholesale.dev](https://holistic.dev/) - 用於 Postgresql 最佳化的 #1 靜態程式碼分析器。效能、安全性和架構師資料庫問題自動偵測服務
*   [houndci.com](https://houndci.com/) — GitHub 上關於程式碼品質的評論，免費開源
*   [Moderne.io](https://app.moderne.io) — 自動原始碼重構。Moderne 提供框架遷移、帶有修復功能的程式碼分析以及無與倫比的大規模程式碼轉換，因此開發人員可以將時間花在建立新事物上，而不是維護舊事物。免費開源。
*   [reviewable.io](https://reviewable.io/) — GitHub 儲存庫的程式碼審查，免費用於公共或個人儲存庫
*   [parsers.dev](https://parsers.dev/) - 抽象語法樹解析器和中間表示編譯器作為服務
*   [scan.coverity.com](https://scan.coverity.com/) — Java、C/C++、C# 和 JavaScript 的靜態程式碼分析，免費開源
*   [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持續檢查平台，免費開源
*   [Semandiff.com](https://app.semanticdiff.com/) — 用於 GitHub 拉取請求和提交的程式語言感知差異，對公共儲存庫免費
*   [shields.io](https://shields.io) — 開源專案的品質元資料徽章
*   [sonarcloud.io](https://sonarcloud.io) — Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 以及更多語言的自動原始碼分析，免費開源
*   [SourceLevel](https://sourcelevel.io/) — 自動程式碼審查與團隊分析。開源和最多 5 名合作者的組織免費。
*   [Viezly](https://viezly.com/) - 增強的程式碼審查工具，可以更輕鬆地閱讀和導航程式碼。免費開源，免費個人使用。
*   [webceo.com](https://www.webceo.com/) — SEO 工具，但也有程式碼驗證和不同類型的建議
*   [Zoompf.com](https://zoompf.com/) — 修復網站的效能，詳細分析

**[⬆️回到頂部](#table-of-contents)**

代碼搜尋和瀏覽
-------

*   [Librarys.io](https://libraries.io/) — 32 個不同的套件管理器的搜尋和依賴項更新通知，免費開源
*   [Namae](https://namae.dev/) - 在 github、gitlab、heroku、netlify 等各種網站上搜尋您的專案名稱的可用性。
*   [searchcode.com](https://searchcode.com/) — 全面的基於文字的程式碼搜索，免費開源
*   [sourcegraph.com](https://about.sourcegraph.com/) — Java、Go、Python、Node.js 等，程式碼搜尋/交叉引用，免費開源
*   [ticgit.com](https://www.tickgit.com/) — 顯示`TODO`註解（和其他標記）以識別值得返回以進行改進的程式碼區域。
*   [CodeKeep](https://codekeep.io) - Google Keep 程式碼片段。組織、發現和共享程式碼片段，具有強大的程式碼螢幕截圖工具，具有預設模板和連結功能。

**[⬆️回到頂部](#table-of-contents)**

持續整合和持續交付
---------

*   [AccessLint](https://github.com/marketplace/accesslint) — AccessLint 將自動化 Web 可存取性測試引入您的開發工作流程。它是免費的，用於開源和教育目的。
*   [appcircle.io](https://appcircle.io) — 適用於 iOS 和 Android 的自動化行動 CI/CD/CT，具有線上裝置模擬器。20 分鐘建置超時（開源為 60 分鐘），單並發免費。
*   [appveyor.com](https://www.appveyor.com/) — 適用於 Windows 的 CD 服務，免費開源
*   [Argonaut](https://argonaut.dev/) - 只需幾分鐘即可在您的雲端部署應用程式和基礎架構。支援 Kubernetes 和 Lambda 環境上的自訂和第三方應用程式部署。免費套餐允許 5 個環境和 2 個用戶無限應用程式和部署。
*   [bitrise.io](https://www.bitrise.io/) — 適用於本機或混合行動應用程式的 CI/CD。每月 200 次免費構建，構建時間為 10 分鐘，團隊成員為兩名。OSS 專案的建置時間為 45 分鐘、+1 並發性和無限的團隊規模。
*   [buddy.works](https://buddy.works/) — 一個 CI/CD，包含 5 個免費項目和 1 個並發運行（120 次執行/月）
*   [buddybuild.com](https://www.buddybuild.com/) — 在一個無縫的迭代系統中建置、部署您的 iOS 和 Android 應用程式並收集回饋
*   [建築風箏](https://buildkite.com)
    *   管道：免費開發者等級包括無限並發、最多 3 個用戶、每月 5000 分鐘工作時間和 30 天建置保留，以及更多針對開源專案的免費內容
    *   [測試分析](https://buildkite.com/test-analytics)— 充分利用您的測試套件，可與任何 CI 平台搭配使用。免費開發人員等級包括每月 10 萬次測試執行，以及更多開源專案的免費內容。
*   [bytebase.com](https://www.bytebase.com/) — 資料庫 CI/CD 和 DevOps。20 個以下使用者和 10 個資料庫實例免費
*   [CircleCI](https://circleci.com/) — 全面的免費計劃，包含 GitHub、GitLab 和 BitBucket 儲存庫的託管 CI/CD 服務中包含的所有功能。多個資源類別、Docker、Windows、Mac OS 和 ARM 執行器以及本機運行器、測試分割、Docker 層快取和其他進階 CI/CD 功能。每月最多可免費執行 6000 分鐘，合作者數量不受限制，私人專案中最多可有 30 個平行作業，開源專案最多可免費建立 80,000 分鐘。
*   [cirrus-ci.org](https://cirrus-ci.org) - 免費用於公共 GitHub 儲存庫
*   [codefresh.io](https://codefresh.io) — 終身免費方案：1 個建置、1 個環境、共享伺服器、無限的公共儲存庫
*   [codemagic.io](https://codemagic.io/) - 每月免費 500 分鐘建置時間
*   [codeship.com](https://codeship.com/) — 每月 100 個私人構建，5 個私人項目，開源無限制
*   [deploybot.com](https://www.deploybot.com/) — 1 個儲存庫，包含 10 個部署，免費開源
*   [deployhq.com](https://www.deployhq.com/) — 1 個項目，每天進行 10 次部署（每月 30 分鐘建置）
*   [無人機](https://cloud.drone.io/)\- 無人機雲端使開發人員能夠跨多種架構運行持續交付管道 - 包括 x86 和 Arm（32 位元和 64 位元） - 全部集中在一個地方
*   [LayerCI－](https://layerci.com)全端專案的 CI。1 個全端預覽環境，配備 5GB 記憶體和 3 個 CPU。
*   [semaphoreci.com](https://semaphoreci.com/) — 免費開源，每月 100 個私人構建
*   [Squash Labs](https://www.squash.io/) — 為每個分支建立一個虛擬機，並使您的應用程式可以透過唯一的 URL、無限的公共和私人儲存庫、高達 2 GB 的虛擬機大小來使用。
*   [styleci.io](https://styleci.io/) — 僅限公共 GitHub 儲存庫
*   [Mergify](https://mergify.io) — GitHub 的工作流程自動化和合併佇列 — 免費用於公共 GitHub 儲存庫
*   [Make](https://www.make.com/en) — 工作流程自動化工具，可讓您使用 UI 連接應用程式並自動化工作流程，它支援許多應用程式和最受歡迎的 API。對公共 GitHub 儲存庫免費，免費套餐具有 100 Mb、1000 次操作和 15 分鐘的最小間隔。
*   [Spacelift](https://spacelift.io/) - 基礎架構即程式碼的管理平台。免費規劃功能：IaC 協作、Terraform 模組註冊表、ChatOps 整合、開放策略代理的持續資源合規性、使用 SAML 2.0 的 SSO 以及對公共工作人員池的存取：每月最多 200 分鐘
*   [microtica.com](https://microtica.com/) - 使用現成的基礎架構元件啟動環境，在 AWS 上免費部署應用程式並支援您的生產工作負載。免費套餐包括 1 個環境（在您的 AWS 帳戶上）、2 個 Kubernetes 服務、每月 100 分鐘的建置時間以及每月 20 次部署。

**[⬆️回到頂部](#table-of-contents)**

測試
--

*   [Applitools.com](https://applitools.com/) — 適用於 Web、本機行動和桌面應用程式的智慧視覺驗證。與幾乎所有自動化解決方案（如 Selenium 和 Karma）和遠端運行程序（Sauce Labs、瀏覽器堆疊）整合。免費開源。單一用戶的免費套餐，每週檢查點有限。
*   [胃口大開](https://appetize.io)— 直接在瀏覽器中在此基於雲端的 Android 手機/平板電腦模擬器和 iPhone/iPad 模擬器上測試您的 Android 和 iOS 應用程式。免費套餐包括每月 1 個並發會話，使用時間為 100 分鐘。應用程式大小沒有限制。
*   [Apptim](https://apptim.com) — 一種行動測試工具，使沒有效能工程技能的人能夠評估應用程式的效能和使用者體驗 (UX)。使用您自己的裝置的桌面版是 100% 免費的，並且在 iOS 和 Android 上進行無限測試。
*   [Bencher](https://bencher.dev/) - 一套連續基準測試工具，旨在捕捉 CI 中的效能回歸。所有公共項目免費。
*   [BugBug](https://bugbug.io/) - 用於 Web 應用程式的輕量級測試自動化工具。易於學習，不需要編碼。您可以在自己的電腦上免費執行無限測試。只需支付額外的月費，您還可以獲得雲端監控和 CI/CD 整合。
*   [lambdatest.com](https://www.lambdatest.com/) — 對 selenium 和 cypress 進行手動、視覺化、螢幕截圖和自動瀏覽器測試，[免費開源](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
*   [browserstack.com](https://www.browserstack.com/) — 手動和自動瀏覽器測試，[免費開源](https://www.browserstack.com/open-source?ref=pricing)
*   [checkbot.io](https://www.checkbot.io/) — 瀏覽器擴展，用於測試您的網站是否遵循 50 多個 SEO、速度和安全最佳實踐。小型網站的免費套餐。
*   [checklyhq.com](https://checklyhq.com) - Checkly 是現代堆疊的 API 和 E2E 監控平台：可程式化、靈活且熱愛 JavaScript。為開發者提供慷慨的免費套餐。
*   [crossbrowsertesting.com](https://crossbrowsertesting.com) - 雲端中的手動、視覺化和 Selenium 瀏覽器測試 -[免費開源](https://crossbrowsertesting.com/open-source)
*   [cypress.io](https://www.cypress.io/) - 對瀏覽器中運行的任何內容進行快速、簡單且可靠的測試。Cypress Test Runner 永遠是免費且開源，沒有任何限制和限制。Cypress Dashboard 對於最多 5 個使用者的開源專案是免費的。
*   [Cypress Recorder by Preflight](https://cypress.preflight.com/) - 在瀏覽器上建立人工智慧驅動的 Cypress 測試/POM 模型。除了人工智慧部分之外，它是開源的。每月可免費進行 5 次測試創建，包括自我修復腳本、電子郵件和視覺化測試。
*   [everystep-automation.com](https://www.everystep-automation.com/) — 記錄和重播在網頁瀏覽器中執行的所有步驟並建立腳本，...免費且選項較少
*   [Gremlin](https://www.gremlin.com/gremlin-free-software) — Gremlin 的混沌工程工具使您能夠安全、可靠、簡單地將故障注入系統中，以在弱點導致客戶面臨的問題之前找到弱點。Gremlin Free 提供最多 5 個主機或容器的關閉和 CPU 攻擊的存取權限。
*   [gridlastic.com](https://www.gridlastic.com/) — Selenium 網格測試，免費規劃最多 4 個同步 Selenium 節點/10 個網格啟動/4,000 測試分鐘/月
*   [katalon.com](https://katalon.com) - 提供一個測試平台，可以幫助各種規模的團隊達到不同的測試成熟度水平，包括 Katalon Studio、TestOps（+ 免費的可視化測試）、TestCloud 和 Katalon Recorder。
*   [Keploy](https://keploy.io/) - Keploy 是開發人員的功能測試工具包。它透過記錄真實的 API 呼叫來產生 API 的 E2E 測試 (KTests) 以及模擬或存根 (KMocks)。它是免費的開源軟體。
*   [loadmill.com](https://www.loadmill.com/) - 透過分析網路流量自動建立 API 和負載測試。每月免費模擬最多 50 個並髮用戶，最多 60 分鐘。
*   [preflight.com](https://preflight.com) - 無程式碼自動化 Web 測試。在瀏覽器上記錄可適應 UI 變更的測試，並在 Windows 電腦上執行它們。與您的 CI/CD 整合。免費方案包括每月 50 次測試運行，包括影片、HTML 會話等。
*   [percy.io](https://percy.io) - 將視覺化測試新增至任何 Web 應用程式、靜態網站、樣式指南或元件庫。無限的團隊成員、演示應用程式和無限的專案、每月 5,000 個快照。
*   [Saucelabs.com](https://saucelabs.com/) — 跨瀏覽器測試、Selenium 測試和行動測試。免費方案包括每週 2000 個積分。他們還為選定的開源專案提供免費許可證，可以[在此處](https://opensource.saucelabs.com/)申請。
*   [snippets.uilicious.com](https://snippets.uilicious.com) - 它類似於 CodePen，但用於跨瀏覽器測試。UI-licious 允許編寫使用者故事等測試，並提供免費平台 - UI-licious Snippets - 讓您在 Chrome 上免費執行無限數量的測試，無需註冊，每次測試運行最多 3 分鐘。發現錯誤？您只需將唯一的 URL 複製到您的測試中，即可向您的開發人員準確展示如何重現該錯誤。
*   [testbot.com](https://testingbot.com/) — Selenium 瀏覽器和裝置測試，[免費開源](https://testingbot.com/open-source)
*   [Testspace.com](https://testspace.com/) - 用於發布自動化測試結果的儀表板和使用 GitHub 將手動測試作為程式碼實作的框架。該服務對每月 450 個結果的[開源帳戶免費。](https://github.com/marketplace/testspace-com)
*   [tesults.com](https://www.tesults.com) — 測試結果報告和測試用例管理。與流行的測試框架整合。開源軟體開發人員、個人、教育工作者和小型團隊可以要求除基本免費項目之外的折扣和免費產品。
*   [websitepulse.com](https://www.websitepulse.com/tools/) — 各種免費網路和伺服器工具。
*   [qase.io](https://qase.io) - 開發和 QA 團隊的測試管理系統。管理測試案例、編寫測試運行、執行測試運行、追蹤缺陷並衡量影響。免費套餐包含所有核心功能，可用於配件的空間為 500Mb，最多可供 3 位使用者使用。
*   [knapsackpro.com](https://knapsackpro.com) - 在任何 CI 提供者上透過最佳測試套件並行化來加速您的測試。在平行 CI 節點上拆分 Ruby、JavaScript 測試以節省時間。最多 10 分鐘測試文件的免費方案和開源專案的免費無限計劃。
*   [webhook.site](https://webhook.site) - 驗證 webhook、出站 HTTP 請求或具有自訂 URL 的電子郵件。臨時 URL 和電子郵件地址始終免費。
*   [Vaadin](https://vaadin.com) — 使用 Java 或 TypeScript 建立可擴展的 UI，並使用整合工具、元件和設計系統來更快地迭代、更好地設計並簡化開發流程。無限項目，5 年免費維護。
*   [webhook-test.com](https://webhook-test.com) - 在與唯一 URL 整合期間偵錯和檢查 webhook、http 請求。完全免費，可以建立無限數量的 URL 並接收請求。
*   [welltested.ai](https://welltested.ai) - 使用 AI 為 Flutter 等行動語言在幾分鐘內產生單元和整合測試。開發者永久免費。

**[⬆️回到頂部](#table-of-contents)**

安全和公鑰基礎設施
---------

*   [Alivault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 發現網路中受感染的系統
*   [atomist.com](https://atomist.com/) — 一種更快、更方便地自動化各種開發任務的方法。現在處於測試階段。
*   [Bridgecrew](https://bridgecrew.io/) — 由開源工具[Checkov](https://github.com/bridgecrewio/checkov)支援的基礎設施即程式碼 (IaC) 安全性。Bridgecrew 核心平台免費提供最多 50 個 IaC 資源。
*   [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 安全性與合規性審核與監控
*   [CodeNotary.io](https://www.codenotary.io/) — 開源平台，具有不可磨滅的證據來公證程式碼、文件、目錄或容器
*   [crypteron.com](https://www.crypteron.com/) — 雲端優先、開發人員友善的安全平台可防止 .NET 和 Java 應用程式中的資料洩露
*   [Cyber​​Chef](https://gchq.github.io/CyberChef/) - 一個簡單、直觀的網頁應用程序，用於分析和解碼/編碼數據，而無需處理複雜的工具或程式語言。就像密碼學和加密領域的瑞士軍刀。所有功能均可免費使用，無限制。開源，如果您想自行託管。
*   [DAS](https://signup.styra.com/) — Styra DAS 免費、全生命週期策略管理，用於建立、部署和管理開放策略代理程式 (OPA) 授權
*   [Datree](https://www.datree.io/) - 開源 CLI 工具，透過確保清單和 Helm 圖表遵循最佳實踐以及組織的策略來防止 Kubernetes 錯誤配置
*   [Dependabot](https://dependabot.com/)自動更新 Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模組和 GitHub Actions。
*   [DJ Checkup](https://djcheckup.com) — 使用這個免費的自動化檢查工具掃描您的 Django 網站是否有安全漏洞。從 Pony Checkup 網站分叉。
*   [Doppler](https://doppler.com/) — 用於應用程式機密和配置的通用機密管理器，支援同步到各種雲端提供者。5 位用戶免費，具有基本的存取控制。
*   [Dotenv](https://dotenv.org/) — 快速、安全地同步您的 .env 檔案。停止透過 Slack 和電子郵件等不安全管道共享您的 .env 文件，再也不會丟失重要的 .env 文件。最多 3 位隊友免費。
*   [GitGuardian](https://www.gitguardian.com) — 透過自動秘密偵測和修復來保護原始碼中的秘密。掃描您的 git 儲存庫以查找 350 多種類型的機密和敏感文件 - 對於個人和 25 名或更少開發人員的團隊免費。
*   [我被pw了嗎？](https://haveibeenpwned.com)— 用於取得違規資訊的 REST API。
*   [Hostedscan.com](https://hostedscan.com) — 用於 Web 應用程式、伺服器和網路的線上漏洞掃描程式。每月 10 次免費掃描。
*   [Infisical](https://infisical.com/) - 開源平台，可讓您管理整個團隊和基礎架構中的開發人員機密：從本地開發到登台/生產第三方服務。最多 5 位開發者免費。
*   [Internet.nl](https://internet.nl) — 測試現代網路標準，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
*   [keychest.net](https://keychest.net) - 使用整合 CT 資料庫進行 SSL 到期管理和憑證購買
*   [Letsencrypt.org](https://letsencrypt.org/) — 免費 SSL 憑證授權單位，其憑證受到所有主要瀏覽器的信任
*   [meterian.io](https://www.meterian.io/) - 監控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 專案的依賴項中的安全漏洞。一個私人項目免費，開源專案不受限制。
*   [Mozilla Observatory](https://observatory.mozilla.org/) — 尋找並修復網站中的安全漏洞。
*   [opswat.com](https://www.opswat.com/) — 電腦、裝置、應用程式、設定等的安全監控...免費 25 個使用者和 30 天歷史使用者。
*   [openapi.security](https://openapi.security/) - 免費工具，可快速檢查任何基於 OpenAPI / Swagger 的 API 的安全性。無需註冊。
*   [pixee.ai](https://pixee.ai) - 自動化產品安全工程師，作為免費的 GitHub 機器人，將 PR 提交到您的 java 程式碼庫以自動解決漏洞。其他語言即將推出！
*   [pyup.io](https://pyup.io) — 監控 Python 依賴項是否有安全漏洞並自動更新。一個私人項目免費，開源專案不受限制。
*   [qualys.com](https://www.qualys.com/community-edition) — 尋找 Web 應用程式漏洞，審核 OWASP 風險
*   [reCAPTCHAMe](https://recaptchame.com/) — 免費的 reCAPTCHA 和 hCAPTCHA 後端服務。無需伺服器端編碼。適用於靜態網站。
*   [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 違規報告
*   [ringcaptcha.com](https://ringcaptcha.com/) — 使用電話號碼作為 ID 的工具，免費提供
*   [seclookup.com](https://seclookup.com/) - Seclookup API 可以豐富 SIEM 中的網域威脅指標，提供全面的網域名稱信息，改善威脅偵測和回應。[在這裡](https://account.seclookup.com/)免費獲得 50K 查詢。
*   [snyk.io](https://snyk.io) — 可以找到並修復開源依賴項中的已知安全漏洞。對開源專案進行無限的測試和修復。您的私人項目每月僅限 200 次測試。
*   [ssllabs.com](https://www.ssllabs.com/ssltest/) — 對任何 SSL Web 伺服器的配置進行非常深入的分析
*   [SOOS](https://soos.io) - 免費、無限制的開源專案 SCA 掃描。在發布前檢測並修復安全威脅。透過簡單有效的解決方案保護您的專案。
*   [StackHawk](https://www.stackhawk.com/)在整個管道中自動進行應用程式掃描，以便在安全漏洞投入生產之前找到並修復它們。單一應用程式的無限掃描和環境。
*   [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免費網站安全檢查和惡意軟體掃描程序
*   [Protectumus](https://protectumus.com) - 適用於 PHP 的免費網站安全檢查、網站防毒和伺服器防火牆 (WAF)。免費套餐中註冊用戶的電子郵件通知。
*   [TestTLS.com](https://testtls.com) - 測試 SSL/TLS 服務的安全伺服器設定、憑證、鍊等。不限於 HTTPS。
*   [Threatconnect.com](https://threatconnect.com) — 威脅情報：它是為開始了解網路威脅情報的個人研究人員、分析師和組織而設計的。釋放最多 3 位用戶
*   [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — 自動漏洞掃描。免費計劃允許每週進行 XSS 掃描
*   [Ubiq Security](https://ubiqsecurity.com/) — 使用 3 行程式碼和自動金鑰管理來加密和解密資料。1 個應用程式免費，每月最多 1,000,000 次加密。
*   [Virgil Security](https://virgilsecurity.com/) — 用於在數位解決方案中實施端對端加密、資料庫保護、物聯網安全等的工具和服務。最多 250 個用戶的應用程式免費。
*   [Virushee](https://virushee.com/) — 隱私導向的文件/資料掃描，由混合啟發式和人工智慧輔助引擎提供支援。可以使用內部動態沙箱分析。每個檔案上傳限制為 50MB
*   [Escape GraphQL Quickscan](https://escape.tech/) - 對 GraphQL 端點進行一鍵安全掃描。免費，無需登入。

**[⬆️回到頂部](#table-of-contents)**

認證、授權和使用者管理
-----------

*   [Aserto](https://www.aserto.com) - 細粒度授權作為應用程式和 API 的服務。釋放最多 1000 個 MAU 和 100 個授權者實例。
*   [asgardeo.io](https://wso2.com/asgardeo) - SSO、MFA、無密碼身份驗證等的無縫整合。包括前端和後端應用程式的 SDK。免費最多 1000 個 MAU 和 5 個身分提供者。
*   [Auth0](https://auth0.com/) — 託管 SSO。最多 7000 名活躍用戶和 2 個社交身分提供者。
*   [Authgear](https://www.authgear.com) - 在幾分鐘內將無密碼、OTP、2FA、SSO 引入您的應用程式。包括所有前端。釋放最多 5000 個 MAU。
*   [Authress](https://authress.io/) — 身分驗證登入和存取控制，任何專案的無限身分提供者。臉書、Google、推特等。前 1000 次 API 呼叫免費。
*   [Authy](https://authy.com) - 多個裝置上的雙重認證 (2FA)，並附有備份。Google 身份驗證器的直接替代品。最多 100 次成功的身份驗證免費。
*   [文員](https://clerk.com)— 使用者管理、身份驗證、具有預先建置 UI 元件的 2FA/MFA。免費釋放最多 5,000 名每月活躍用戶。
*   [Cloud-IAM](https://www.cloud-iam.com/) — Keycloak 身分和存取管理即服務。釋放最多 100 個使用者和 1 個領域。
*   [Descope](https://www.descope.com/) — 高度可自訂的 AuthN 流程，同時採用無程式碼和 API/SDK 方法，每月免費 7,500 個活躍用戶，50 個租戶（最多 5 個 SAML/SSO 租戶）。
*   [duo.com](https://duo.com/) — 網站或應用程式的雙重認證 (2FA)。10 個用戶免費，所有身份驗證方法，無限制，集成，硬體令牌。
*   [Jumpcloud](https://jumpcloud.com/) — 提供類似 Azure AD 的目錄即服務、使用者管理、單一登入和 RADIUS 驗證。最多 10 位用戶免費。
*   [Kinde](https://kinde.com/) - 簡單、強大的身份驗證，您可以在幾分鐘內與您的產品整合。開始使用 7,500 個免費月活躍用戶所需的一切。
*   [logintc.com](https://www.logintc.com/) — 透過推播通知進行雙重認證 (2FA)，免費 10 位使用者使用，VPN、網站和 SSH
*   [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在幾分鐘內輕鬆地在您的網路、行動裝置或任何應用程式上實現無密碼身份驗證。
*   [Okta](https://developer.okta.com/signup/) — 使用者管理、身分驗證和授權。每月最多 100 名活躍用戶免費。
*   [onelogin.com](https://www.onelogin.com/) — 身分即服務 (IDaaS)、單一登入身分提供者、雲端 SSO IdP、3 個公司應用程式和 5 個個人應用程式、無限用戶
*   [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/零信任託管安全平台。具有所有安全功能的永久免費開發者帳戶、無限的團隊成員、200 個每日活躍用戶和 25k/月 權限檢查。
*   [Stytch](https://www.stytch.com/) - 靈活的驗證 API 和 SDK，具有防存取密碼、無密碼登入流程、MFA、SSO 等。電子郵件/簡訊發送 + 內建故障轉移和詐欺保護。免費提供 5,000 個每月活躍用戶 (B2C) 或免費提供 1,000 個每月活躍用戶和 25 個組織 (B2B)。
*   [SuperTokens](https://supertokens.com/) - 原生整合到您的應用程式中的開源使用者身份驗證 - 讓您能夠快速入門，同時控制使用者和開發人員體驗。最多 5000 個月活躍用戶免費。
*   [Warrant](https://warrant.dev/) — 為您的應用程式託管企業級授權和存取控制服務。免費套餐包括每月 100 萬個 API 請求和 1,000 個授權規則。
*   [ZITADEL Cloud](https://zitadel.com) — 一站式使用者和存取管理，適合您並支援多租戶 (B2B) 使用案例。免費最多可處理 25'000 個經過驗證的請求，並具有所有安全功能（OTP、無密碼、政策等無需付費）。
*   [PropelAuth](https://propelauth.com) — 只需幾行程式碼即可立即向任何規模的公司銷售，免費最多 200 個用戶和 10k 事務電子郵件（帶有浮水印品牌：「由 PropelAuth 提供支援」）。
*   [Logto](https://logto.io/) - 開發、保護和管理產品的使用者身分 - 用於身分驗證和授權。最多 5,000 個 MAU 免費，並提供開源自託管選項。

**[⬆️回到頂部](#table-of-contents)**

行動應用程式分發和回饋
-----------

*   [TestApp.io](https://testapp.io) - 確保您的行動應用程式正常運作的首選平台。免費方案：一個應用程式、分析、無限版本和安裝以及回饋收集。
*   [Diawi](https://www.diawi.com) - 將 iOS 和 Android 應用程式直接部署到裝置。免費方案：應用程式上傳、受密碼保護的連結、1 天過期、10 次安裝。
*   [InstallOnAir](https://www.installonair.com) - 透過無線方式分發 iOS 和 Android 應用程式。免費方案：無限上傳、私人連結、訪客有效期限為 2 天、註冊用戶有效期限為 60 天。
*   [GetUpdraft](https://www.getupdraft.com) - 分發行動應用程式以進行測試。免費方案包括：1 個應用程式項目、3 個應用程式版本、500 MB 儲存空間以及每月 100 次應用程式安裝。
*   [Appho.st](https://appho.st) - 行動應用程式託管平台。免費方案包括：5 個應用程式、每月 50 次下載、最大檔案大小為 100MB。

**[⬆️回到頂部](#table-of-contents)**

管理系統
----

*   [bitnami.com](https://bitnami.com/) — 在 IaaS 上部署準備好的應用程式。免費管理 1 個 AWS 微型實例
*   [Esper](https://esper.io) — 適用於具有 DevOps 的 Android 裝置的 MDM 和 MAM。100 台裝置免費，擁有 1 個使用者授權和 25 MB 應用程式儲存空間。
*   [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的裝置管理，免費 3 台設備
*   [Miradore](https://miradore.com) — 設備管理服務。隨時了解您的設備群的最新動態，並免費保護無限數量的設備。免費方案提供基本功能。
*   [moss.sh](https://moss.sh) - 幫助開發人員部署和管理他們的網頁應用程式和伺服器。每月免費最多 25 次 git 部署
*   [runcloud.io](https://runcloud.io/) - 主要關注 PHP 專案的伺服器管理。最多 1 台伺服器免費。
*   [ploi.io](https://ploi.io/) - 伺服器管理工具，可輕鬆管理和部署您的伺服器和網站。1台伺服器免費。

**[⬆️回到頂部](#table-of-contents)**

訊息傳遞和串流媒體
---------

*   [Ably](https://www.ably.com/) - 即時訊息服務，具有存在性、持久性和保證的交付。免費方案包括每月 300 萬條訊息、100 個峰值連接和 100 個峰值通道。
*   [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服務。Little Lemur 方案：每月最多 100 萬條訊息，最多 20 個並發連接，最多 100 個隊列，最多 10,000 條排隊訊息，不同可用區中的多個節點
*   [connectycube.com](https://connectycube.com) - 無限聊天訊息、p2p 語音和視訊通話、文件附件和推播通知。最多 1000 個用戶的應用程式免費。
*   [courier.com](https://www.courier.com/) — 用於推播、應用程式內、電子郵件、聊天、簡訊和其他訊息傳遞管道的單一 API，具有範本管理和其他功能。免費方案包括每月 10,000 條訊息。
*   [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 將您的 MQTT 裝置連接到雲端原生 IoT 訊息傳遞代理程式。永久免費連接最多 100 個裝置（無需信用卡）。
*   [Knock.app](https://knock.app) – 為開發人員提供的通知基礎設施。透過單一 API 呼叫傳送到多個管道，例如應用程式內、電子郵件、簡訊、Slack 和推送。免費方案包括每月 10,000 條訊息。
*   [Pusher.com](https://pusher.com/) — 即時訊息服務。每天免費最多 100 個並發連接和 200,000 條訊息
*   [scaledrone.com](https://www.scaledrone.com/) — 即時訊息服務。每天免費最多 20 個並發連接和 100,000 個事件
*   [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io)作為一項服務。全球、AWS、GCP 和 Azure。永久免費，每月 4k 訊息大小、50 個活動連線和 5GB 資料。
*   [cloudkarafka.com](https://www.cloudkarafka.com/) - 免費共享 Kafka 集群，最多 5 個主題，每個主題 10MB 數據，數據保留 28 天。
*   [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin 和 React 訊息傳遞每月處理 100 萬筆交易。事務可能包含多個訊息。
*   [eyeson API](https://developers.eyeson.team/) - 基於WebRTC（SFU、MCU）建立視訊平台的視訊通訊API服務。允許即時資料注入、視訊佈局、錄製、功能齊全的託管 Web UI（快速入門）或自訂 UI 包。為開發人員提供每月 1000 分鐘會議時間的[免費套餐。](https://apiservice.eyeson.com/api-pricing)
*   [Upstash Kafka](https://upstash.com/kafka) - 無伺服器 Kafka 雲端產品，依請求定價。它有一個免費套餐，每天最多可發送 10000 條訊息。
*   [webpushr](https://www.webpushr.com/) - 網路推播通知 - 最多 10k 訂閱者免費、無限推播通知、瀏覽器內訊息傳遞
*   [Scramjet Cloud Platform Beta](https://www.scramjet.org/#join-beta) - 免費測試版中的端對端串流處理平台，在測試版結束後提供 15 PB 秒的免費運算。
*   [httpSMS](https://httpsms.com) - 使用 Android 手機作為簡訊網關發送和接收簡訊。每月最多可免費發送和接收 200 則訊息。

**[⬆️回到頂部](#table-of-contents)**

日誌管理
----

*   [bugfender.com](https://bugfender.com/) — 每天免費最多 100k 行日誌並保留 24 小時
*   [logentries.com](https://logentries.com/) — 每月最多免費 5 GB，保留 7 天
*   [loggly.com](https://www.loggly.com/) — 單一使用者免費，200MB/天，保留 7 天
*   [logz.io](https://logz.io/) — 免費高達 1 GB/天，保留 1 天
*   [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management) — 由 Manage Engine 提供支援的日誌管理服務。免費方案提供 50 GB 儲存空間，保留 1 個月。
*   [papertrailapp.com](https://papertrailapp.com/) — 48 小時搜索，7 天存檔，50 MB/月
*   [sematext.com](https://sematext.com/logsene) — 免費高達 500 MB/天，保留 7 天
*   [sumologic.com](https://www.sumologic.com/) — 免費高達 500 MB/天，保留 7 天
*   [logflare.app](https://logflare.app/) — 每個應用程式每月最多可免費使用 12,960,000 個條目，保留 3 天
*   [logtail.com](https://logtail.com/) — 基於 ClickHouse 的 SQL 相容日誌管理。每月最多免費 1 GB，保留 3 天。
*   [logzab.com](https://logzab.com/) — 審計追蹤管理系統。每月免費 1.000 個使用者活動日誌，保留 1 個月，最多可用於 5 個專案。

**[⬆️回到頂部](#table-of-contents)**

翻譯管理
----

*   [crowdin.com](https://crowdin.com/) — 無限的專案、無限的字串和開源合作者
*   [gitlocalize.com](https://gitlocalize.com) - 免費且無限的私人和公共儲存庫
*   [Lecto](https://lecto.ai/) - 具有免費層的機器翻譯 API（30 個免費請求，每個請求 1000 個翻譯字元）。與 Loco Translate Wordpress 外掛程式整合。
*   [lingohub.com](https://lingohub.com/) — 最多免費 3 位用戶，始終免費開源
*   [localazy.com](https://localazy.com) - 免費提供 1000 種原始語言字串、無限語言、無限貢獻者、啟動和開源交易
*   [Localeum](https://localeum.com) - 免費最多 1000 個字串、1 個使用者、無限語言、無限項目
*   [localizely.com](https://localizely.com/) — 免費開源
*   [Loco](https://localise.biz/) — 最多 2000 個免費翻譯、無限制翻譯人員、10 種語言/專案、1000 個可翻譯資產/項目
*   [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用戶的限量免費版，免費開源
*   [POEditor](https://poeditor.com/) — 免費最多 1000 個字串
*   [SimpleLocalize](https://simplelocalize.io/) - 免費最多 100 個翻譯鍵、無限字串、無限語言、啟動優惠
*   [Texterify](https://texterify.com/) - 單一使用者免費
*   [Tolgee](https://tolgee.io) - 免費 SaaS 產品，翻譯有限，永久免費的自架版本
*   [transifex.com](https://www.transifex.com/) — 免費開源
*   [Translation.io](https://translation.io) - 免費開源
*   [Translized](https://translized.com) - 免費最多 1000 個字串、1 個使用者、無限語言、無限項目
*   [webtranslateit.com](https://webtranslateit.com/) — 免費最多 500 個字串
*   [weblate.org](https://weblate.org/) — 免費的 libre 專案免費，免費層最多可包含 10,000 個字串來源，並且可在本地進行無限制的自託管。
*   [免費 PO 編輯器](https://pofile.net/free-po-editor)— 對所有人免費

**[⬆️回到頂部](#table-of-contents)**

監控
--

*   [Pingmeter.com](https://pingmeter.com/) - 5 個正常運作時間監視器，間隔 10 分鐘。監控 SSH、HTTP、HTTPS 和任何自訂 TCP 連接埠。
*   [appdynamics.com](https://www.appdynamics.com/) — 24 小時免費指標，應用程式效能管理代理程式僅限於一種 Java、一種 .NET、一種 PHP 和一種 Node.js
*   [appneta.com](https://www.appneta.com/) — 免費，資料保留 1 小時
*   [appspector.com](https://appspector.com/) - 任務控制，用於遠端 iOS/Android/Flutter 偵錯。小流量使用免費（64MB 日誌）。
*   [assertible.com](https://assertible.com) — 自動化 API 測試和監控。為團隊和個人提供免費計劃。
*   [checklyhq.com](https://checklyhq.com) - 為開發人員提供開源 E2E / 綜合監控和深度 API 監控。具有 5 個用戶和超過 50k 次檢查運行的免費方案。
*   [circonus.com](https://www.circonus.com/) — 免費提供 20 個指標
*   [cloudploit.com](https://cloudsploit.com) — AWS 安全性和設定監控。免費：無限按需掃描、無限用戶、無限儲存帳戶。訂閱：自動掃描、API存取等。
*   [cronitor.io](https://cronitor.io/) - cron 作業、網站、API 等的效能洞察和正常運行時間監控。具有 5 台顯示器的免費套餐。
*   [datadoghq.com](https://www.datadoghq.com/) — 最多 5 個節點免費
*   [deadmanssnitch.com](https://deadmanssnitch.com/) — 監控 cron 作業。1 個免費告密者（監控者），如果您推薦其他人註冊，則更多
*   [downtimemonkey.com](https://downtimemonkey.com/) — 60 個正常運作時間監視器，間隔 5 分鐘。電子郵件、Slack 警報。
*   [economize.cloud](https://economize.cloud) — Economize 透過組織雲端資源、最佳化和報告雲端資源來幫助揭開雲端基礎設施成本的神秘面紗。每月在 Google Cloud Platform 上消費不超過 5000 美元即可免費。
*   [elastic.co](https://www.elastic.co/solutions/apm) — 為 JS 開發人員提供即時效能洞察。免費並保留 24 小時數據
*   [freeboard.io](https://freeboard.io/) — 免費用於公共項目。物聯網 (IoT) 專案的儀表板
*   [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud 是一個可組合的可觀察性平台，將指標和日誌與 Grafana 整合。免費：3 個使用者、10 個儀表板、100 個警報、Prometheus 和 Graphite 中的指標儲存（10,000 個系列，保留 14 天）、Loki 中的日誌儲存（50 GB 日誌，保留 14 天）
*   [healthchecks.io](https://healthchecks.io) — 監控您的 cron 作業和後台任務。最多 20 張支票免費。
*   [spector.dev](https://www.inspector.dev) - 不到一分鐘的完整即時監控儀表板，並且永久免費。
*   [Instrumentalapp.com](https://instrumentalapp.com) - 美觀且易於使用的應用程式和伺服器監控，可免費提供多達 500 個指標和 3 小時的資料可見性
*   [keychest.net/speedtest](https://keychest.net/speedtest) - 針對 Digital Ocean 的獨立速度測試和 TLS 握手延遲測試
*   [Letsmonitor.org](https://letsmonitor.org) - SSL 監控，最多免費支援 5 個監視器
*   [loader.io](https://loader.io/) — 有限制的免費負載測試工具
*   [meercode.io](https://meercode.io/) — Meercode 是 CI/CD 建構的終極監控儀表板。免費開源和 1 個私有儲存庫。
*   [netdata.cloud](https://www.netdata.cloud/) — Netdata 是一個開源工具，旨在收集即時指標。這是一個快速成長的偉大產品。github上也可以找到！
*   [newrelic.com](https://www.newrelic.com) — New Relic 可觀測平台，旨在幫助工程師創建更完美的軟體。從單體應用到無伺服器，您可以偵測所有內容，然後分析、排除故障並最佳化整個軟體堆疊。免費方案提供 100GB/月的免費資料攝取、1 個免費完整存取用戶和無限的免費基本用戶。
*   [Middleware.io](https://middleware.io/) - 中間件可觀察性平台提供對應用程式和堆疊的完整可見性，因此您可以大規模監控和診斷問題。他們有一個供開發社群使用的永久免費計劃，允許對最多 1M 日誌事件進行日誌監控，對最多 2 台主機進行基礎設施監控和 APM。
*   [nixstats.com](https://nixstats.com) - 一台伺服器免費。電子郵件通知、公共狀態頁面、60 秒間隔等等。
*   [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot 是一個可靠的正常運作時間監視器，適用於 JS 為基礎的 Web 應用程式和網站。5 次正常運行時間檢查（針對靜態網站和 API），間隔 5 分鐘，1 次瀏覽器檢查，間隔 15 分鐘。也提供自動公共狀態頁面（支援第 3 方正常運作時間監控）。最多 3 位用戶免費，透過 Slack、Discord 和電子郵件發出警報。
*   [opsgenie.com](https://www.opsgenie.com/) — 強大的警報和待命管理，用於運營始終在線的服務。釋放最多 5 個用戶。
*   [paessler.com](https://www.paessler.com/) — 強大的基礎設施和網路監控解決方案，包括警報、強大的視覺化功能和基本報告。釋放多達 100 個感測器。
*   [syagent.com](https://syagent.com/) — 非商業免費伺服器監控服務、警報和指標。
*   [pagerly.io](https://pagerly.io/) - 在 Slack 上管理待命（與 Pagerduty、OpsGenie 整合）。免費最多 1 個團隊（一個團隊指一個待命）
*   [pagertree.com](https://pagertree.com/) - 用於警報和待命管理的簡單介面。釋放最多 5 個用戶。
*   [pingbreak.com](https://pingbreak.com/) — 現代正常運作時間監控服務。檢查無限的 URL 並透過 Discord、Slack 或電子郵件取得停機通知。
*   [pingpong.one](https://pingpong.one/) — 附監控的進階狀態頁面平台。免費套餐包括一個帶有 SSL 子網域的公共可自訂狀態頁面。Pro 計劃免費提供給開源專案和非營利組織。
*   [robusta.dev](https://home.robusta.dev/) — 強大的 Kubernetes 監控，基於 Prometheus。帶上您自己的 Prometheus 或安裝一體化捆綁包。免費套餐包含最多 20 個 Kubernetes 節點。透過 Slack、Microsoft Teams、Discord 等發出警報。與 PagerDuty、OpsGenie、VictorOps、DataDog 和許多其他工具整合。
*   [sematext.com](https://sematext.com/) — 24 小時免費指標、無限數量的伺服器、10 個自訂指標、500,000 個自訂指標資料點、無限的儀表板、使用者等。
*   [sitemonki.com](https://sitemonki.com/) — 網站、網域、Cron 和 SSL 監控，每個類別 5 個免費監控器
*   [sitesure.net](https://sitesure.net) - 網站和 cron 監控 - 2 個免費監視器
*   [skylight.io](https://www.skylight.io/) — 前 100,000 個請求免費（僅限 Rails）
*   [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 效能監控 API，檢查 Ping、DNS 等。
*   [stathat.com](https://www.stathat.com/) — 免費開始使用 10 個統計數據，無過期時間
*   [statuscake.com](https://www.statuscake.com/) — 網站監控，無限制免費測試，但有限制
*   [statusgator.com](https://statusgator.com/) — 狀態頁面監控，3 個免費監視器
*   [milleyes.com](https://www.thousandeyes.com/) — 網路與使用者體驗監控。免費提供主要網路服務的 3 個地點和 20 個資料來源
*   [uptimerobot.com](https://uptimerobot.com/) — 網站監控，免費 50 個監視器
*   [uptimetoolbox.com](https://uptimetoolbox.com/) — 免費監控 5 個網站，60 秒間隔，公共狀態頁面。
*   [zenduty.com](https://www.zenduty.com/) — 適用於網路營運、站點可靠性工程和 DevOps 團隊的端到端事件管理、警報、待命管理和回應編排平台。最多 5 位用戶免費。
*   [instatus.com](https://instatus.com) - 10 秒內獲得漂亮的狀態頁面。永久免費，無限訂閱者和無限團隊。
*   [Squadcast.com](https://squadcast.com) - Squadcast 是一款端到端事件管理軟體，旨在協助您推廣 SRE 最佳實務。永久免費方案可供最多 10 位用戶使用。
*   [RoboMiri.com](https://robomiri.com/) - RoboMiri 是穩定的正常運作時間監視器，提供廣泛的監視器：cronjob、關鍵字、網站、連接埠、ping。免費進行 25 次正常運轉時間檢查，每 3 分鐘檢查一次。透過電話、簡訊、電子郵件和 Web Hook 發出警報。
*   [更好的堆疊](https://betterstack.com/better-uptime)\- 單一產品中的正常運行時間監控、事件管理、待命調度/警報和狀態頁面。免費方案中包含 10 個顯示器，每 3 分鐘檢查一次以及狀態頁面。
*   [Pulsetic](https://pulsetic.com) - 10 個監視器、6 個月歷史正常運行時間/日誌、無限狀態頁面和自訂網域！免費獲得無限時間和無限電子郵件提醒。無需信用卡。
*   [Wachete](https://www.wachete.com) - 監控 5 個頁面，每 24 小時檢查一次。

**[⬆️回到頂部](#table-of-contents)**

崩潰和異常處理
-------

*   [CatchJS.com](https://catchjs.com/) - 使用螢幕截圖和點擊軌跡進行 JavaScript 錯誤追蹤。對於開源專案免費。
*   [bugsnag.com](https://www.bugsnag.com/) — 初次試用後每月最多可免費解決 2,000 個錯誤
*   [elmah.io](https://elmah.io/) — 為 Web 開發人員提供錯誤日誌記錄和正常運行時間監控。免費小型企業訂閱開源專案。
*   [擁抱](https://embrace.io/)——行動應用程式監控。每年最多 100 萬個用戶會話的小型團隊免費。
*   [異常](https://exceptionless.com)\- 即時錯誤、功能、日誌報告等。每月/1 位用戶免費參加 3000 場活動。開源且易於自行託管，可無限使用。
*   [GlitchTip](https://glitchtip.com/) — 簡單的開源錯誤追蹤。與開源 Sentry SDK 相容。每月免費舉辦 1000 場活動，也可以無限制自行舉辦
*   [honeybadger.io](https://www.honeybadger.io) - 異常、正常運作時間和 cron 監控。對小型團隊和開源專案免費（每月 12,000 個錯誤）。
*   [memfault.com](https://memfault.com) — 用於設備可觀察性和調試的雲端平台。[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp)和[Laird](https://app.memfault.com/register-laird)裝置可免費使用 100 台裝置。
*   [rollbar.com](https://rollbar.com/) — 異常和錯誤監控、每月 5,000 個錯誤的免費計劃、無限用戶、30 天保留
*   [Sentry.io](https://sentry.io/) — Sentry 即時追蹤應用程式異常，有一個小型免費方案。每月 5000 個錯誤/1 個用戶免費，如果自架則不受限制使用
*   [Axiom](https://axiom.co/) — 儲存最多 0.5 TB 的日誌，保留 30 天。包括與 Vercel 等平台的整合以及透過電子郵件/Discord 通知程式進行進階資料查詢。
*   [Semaphr](https://semaphr.com) — 適用於您的行動應用程式的免費一體式終止開關。

**[⬆️回到頂部](#table-of-contents)**

搜尋
--

*   [algolia.com](https://www.algolia.com/) — 託管搜尋即輸入（即時）。免費駭客計畫多達 10,000 個文件和 100,000 次操作。適用於社區/開源專案的更大免費計劃
*   [bonsai.io](https://bonsai.io/) — 免費 1 GB 記憶體和 1 GB 儲存空間
*   [CommandBar](https://www.commandbar.com/) - 統一搜尋列即服務，基於 Web 的 UI 小部件/插件，允許使用者在產品中搜尋內容、導航、功能等，這有助於發現。最多 1000 名每月活躍用戶免費，命令無限制。
*   [Magny](https://magny.io) - 協助實施命令面板（例如應用程式內搜尋）的 SaaS 服務，可大幅減少使用者在應用程式中尋找任何內容的時間，從而充分利用使用者體驗和效率。
*   [searchly.com](http://www.searchly.com/) — 免費 2 個索引和 20 MB 儲存空間
*   [pagedart.com](https://pagedart.com/) - 人工智慧搜尋即服務，免費層包括 1000 個文件、50000 個搜尋。對於有價值的項目，可以提供更大的免費套餐。
*   [Meilisearch](https://www.meilisearch.com/) - 一款開源、快如閃電且高度相關的搜尋引擎，可輕鬆融入您的應用程式、網站和工作流程。免費方案包括每月 100K 文件和 10K 搜尋。

**[⬆️回到頂部](#table-of-contents)**

電子郵件
----

*   [10Minutemail](https://10minutemail.com) - 用於測試的免費臨時電子郵件。
*   [AnonAddy](https://anonaddy.com) - 開源匿名電子郵件轉發，免費建立無限的電子郵件別名
*   [Antideo](https://www.antideo.com) — 免費套餐中每小時 10 個 API 請求，用於電子郵件驗證、IP 和電話號碼驗證。無需信用卡。
*   [Bump](https://bump.email/) - 免費 10 個 Bump 電子郵件地址、1 個自訂網域
*   [Burnermail](https://burnermail.io/) – 免費 5 個 Burner 電子郵件地址、1 個信箱、7 天信箱歷史記錄
*   [Buttondown](https://buttondown.email/) — 時事通訊服務。最多 100 位訂閱者免費
*   [CloudMailin](https://www.cloudmailin.com/) - 透過 HTTP POST 傳入電子郵件和事務性出站 - 每月 10,000 封免費電子郵件
*   [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 為開發人員提供的電子郵件驗證和驗證 API，每月 800 個免費 API 請求
*   [Contact.do](https://contact.do/) — 連結中的聯絡表單（聯絡表位）- 完全免費！
*   [debugmail.io](https://debugmail.io/) — 易於開發人員使用的測試郵件伺服器
*   [DNSExit](https://dnsexit.com/) - 您的網域下最多可免費使用 2 個電子郵件地址，並擁有 100MB 的儲存空間。IMAP、POP3、SMTP、SPF/DKIM 支援。
*   [emaildrop.io](https://emaildrop.io/) — 免費的一次性電子郵件提供者。可以透過 GraphQL API 建立電子郵件地址。
*   [EmailLabs.io](https://emaillabs.io/en) — 每月免費發送多達 9,000 封電子郵件，每天最多發送 300 封電子郵件。
*   [EmailOctopus](https://emailoctopus.com) - 每月最多 2,500 個訂閱者和 10,000 封電子郵件免費
*   [EmailJS](https://www.emailjs.com/) – 這不是一個完整的電子郵件伺服器，這只是電子郵件用戶端，您可以使用它直接從客戶端發送電子郵件，而不會暴露您的憑證，免費層有：200 個每月請求，2 個電子郵件模板，最多50Kb 的請求，有限聯絡人歷史記錄。
*   [EtherealMail](https://ethereal.email) - Ethereal 是一個假冒的 SMTP 服務，主要針對 Nodemailer 和 EmailEngine 用戶（但不限於）。這是一種完全免費的反交易電子郵件服務，訊息永遠不會被傳遞。
*   [Tempmailers](https://tempmailers.com/) - 免費產生無限量的臨時電子郵件地址
*   [Emailvalidation.io](https://emailvalidation.io) - 每月 100 次免費電子郵件驗證
*   [fakermail.com](https://fakermail.com/) — 免費的臨時電子郵件，用於測試儲存的最後 100 個電子郵件帳戶。
*   [forwardemail.net](https://forwardemail.net) — 自訂網域的免費電子郵件轉發。使用您的網域建立和轉發無限數量的電子郵件地址（**注意**：如果您使用.casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.，則必須付費。因垃圾郵件而導致貸款、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD）
*   [HotTempMail](https://hottempmail.com/) - 無限的免費臨時電子郵件或一次性臨時電子郵件地址。一天後自動過期。
*   [模仿電子郵件](https://imitate.email)\- 沙箱電子郵件伺服器，用於跨 build/qa 和 ci/cd 測試電子郵件功能。免費帳號每天永遠收到 15 封電子郵件。
*   [ImprovMX](https://improvmx.com) – 免費電子郵件轉發
*   [EForw](https://www.eforw.com) – 1 個網域的免費電子郵件轉寄。從您的網域接收和發送電子郵件。
*   [inboxkitten.com](https://inboxkitten.com/) - 免費臨時/一次性電子郵件收件匣，最多可自動刪除 3 天的電子郵件。開源，並且可以自行託管。
*   [mail-tester.com](https://www.mail-tester.com) — 測試電子郵件的 dns/spf/dkim/dmarc 設定是否正確，20 個免費/月
*   [dkimvalidator.com](https://dkimvalidator.com/) - 測試電子郵件的 dns/spf/dkim/dmarc 設定是否正確，由 roundsphere.com 提供的免費服務
*   [mailcatcher.me](https://mailcatcher.me/) — 擷取郵件並透過 Web 介面提供服務
*   [Mailcheck.ai](https://www.mailcheck.ai/) - 阻止使用者使用臨時電子郵件地址註冊，每小時 120 個請求（每月約 86,400 個）
*   [Mailchimp](https://mailchimp.com/) — 每月免費 500 個訂閱者和 1,000 封電子郵件
*   [MailerLite.com](https://www.mailerlite.com) — 1,000 位訂閱者/月，12,000 封電子郵件/月免費
*   [MailerSend.com](https://www.mailersend.com) — 電子郵件 API、SMTP，每月免費發送 3,000 封電子郵件，用於交易電子郵件
*   [mailinator.com](https://www.mailinator.com/) — 免費的公開電子郵件系統，您可以在其中使用任何您想要的收件匣
*   [Mailjet](https://www.mailjet.com/) — 每月免費發送 6,000 封電子郵件（每日發送限制為 200 封電子郵件）
*   [Mailnesia](https://mailnesia.com) - 免費臨時/一次性電子郵件，自動訪問註冊連結。
*   [mailsac.com](https://mailsac.com) - 用於臨時電子郵件測試的免費 API、免費公共電子郵件託管、出站擷取、電子郵件到 slack/websocket/webhook（每月 1,500 個 API 限制）
*   [Mailtie.com](https://mailtie.com/) - 為您的網域提供免費電子郵件轉發。無需註冊。永遠免費。
*   [Mailtrap.io](https://mailtrap.io/) — 用於開發的假 SMTP 伺服器，免費計劃，有 1 個收件箱，100 條訊息，沒有團隊成員，每秒 2 封電子郵件，沒有轉發規則
*   [Mailvalidator.io](https://mailvalidator.io/) - 每月免費驗證 300 封電子郵件，即時 API，可進行批次處理
*   [Mail7.io](https://www.mail7.io/) — 為 QA 開發人員提供的免費臨時電子郵件地址。使用 Web 介面或 API 立即建立電子郵件地址
*   [Mutant Mail](https://www.mutantmail.com/) – 免費 10 個電子郵件 ID、1 個網域、1 個信箱。所有電子郵件 ID 的單一郵箱。
*   [Outlook.com](https://outlook.live.com/owa/) - 免費個人電子郵件和行事曆
*   [Parsio.io](https://parsio.io) — 免費電子郵件解析器（轉發電子郵件，提取數據，將其發送到您的伺服器）
*   [pepipost.com](https://pepipost.com) — 第一個月免費發送 30,000 封電子郵件，然後每天免費發送前 100 封電子郵件
*   [郵戳](https://postmarkapp.com/)\- 每月 100 封電子郵件免費，無限 DMARC 每週摘要
*   [Proton Mail](https://proton.me/mail) - 具有內建端對端加密功能的免費安全電子郵件帳戶服務提供者。免費 1GB 儲存空間。
*   [Queuemail.dev](https://queuemail.dev) — 可靠的電子郵件傳送 API。免費套餐（每月 10,000 封電子郵件）。異步發送。使用多個 SMTP 伺服器。黑名單、日誌記錄、追蹤、Webhooks 等等...
*   [QuickEmailVerification](https://quickemailverification.com) — 每天在免費套餐中免費驗證 100 封電子郵件以及其他免費 API，例如 DEA Detector、DNS Lookup、SPF Detector 等。
*   [寄件者](https://www.sender.net)每月最多 15,000 封電子郵件，最多 2,500 位訂閱者
*   [SendGrid](https://sendgrid.com/) — 每天 100 封電子郵件和 2,000 個免費聯絡人
*   [Sendinblue](https://www.sendinblue.com/) — 每月 9,000 封電子郵件，每天免費 300 封電子郵件
*   [Sendpulse](https://sendpulse.com) — 500 位訂閱者/月，12,000 封電子郵件/月免費
*   [SimpleLogin](https://simplelogin.io/) – 開源、可自架的電子郵件別名/轉送解決方案。免費 5 個別名、無限頻寬、無限回覆/發送。教育工作者（學生、研究人員等）免費。
*   [Skiff](https://skiff.com/) - 開源、端對端加密匿名電子郵件服務，註冊時無需詢問其他詳細信息，免費10GB 驅動器存儲空間，您自己網站的1 個自定義域，每個帳戶為您的電子郵件地址提供4 個免費別名。E2EE 環境的附加加密錢包支援。
*   [Substack](https://substack.com) — 無限制的免費電子報服務。當您收費時就開始付款。
*   [Tempmailo](https://tempmailo.com/) - 無限的免費臨時電子郵件地址。兩天後自動過期。
*   [Takeout](https://takeout.bysourfruit.com) - 不斷更新的電子郵件服務，讓發送電子郵件變得極為容易。每月 500 封交易電子郵件免費。
*   [temp-mail.io](https://temp-mail.io) — 免費的一次性臨時電子郵件服務，一次可轉發多封電子郵件
*   [tinyletter.com](https://tinyletter.com/) — 每月 5,000 名訂閱者免費
*   [rashmail.com](https://www.trashmail.com) - 免費的一次性電子郵件地址，具有轉發功能和地址自動過期功能
*   [Tutanota](https://tutanota.com/) - 免費安全電子郵件帳戶服務供應商，內建端對端加密，無廣告，無追蹤。免費 1GB 儲存空間。其中也部分[開源](https://github.com/tutao/tutanota)，因此您可以選擇自行託管。
*   [Validator.Pizza](https://www.validator.pizza/) — 用於偵測一次性電子郵件的免費 API
*   [Verifalia](https://verifalia.com/email-verification-api) — 即時電子郵件驗證 API，具有郵箱確認和一次性電子郵件地址偵測器；每天 25 次免費電子郵件驗證。
*   [verimail.io](https://verimail.io/) — 批次和 API 電子郵件驗證服務。每月 100 次免費驗證
*   [Zoho](https://www.zoho.com) — 最初是電子郵件供應商，但現在提供一套服務，其中一些服務有免費方案。有免費方案的服務清單：
    *   [](https://zoho.com/mail)5 位使用者免費[發送電子郵件。](https://zoho.com/mail)5 GB/使用者和 25 MB 附件限制，1 個網域。
    *   [Sprints](https://zoho.com/sprints)免費提供 5 個使用者、5 個項目和 500MB 儲存空間。
    *   [文件](https://zoho.com/docs)— 免費供 5 位使用者使用，上傳限制為 1 GB，儲存空間為 5 GB。Zoho Office 套件（Writer、Sheets 和 Show）與其捆綁在一起。
    *   [項目](https://zoho.com/projects)— 免費供 3 個使用者、2 個項目和 10 MB 附件限制。同樣的計劃也適用於[Bugtracker](https://zoho.com/bugtracker)。
    *   [Connect](https://zoho.com/connect) — 免費為 25 位使用者提供團隊協作，包括 3 個群組、3 個自訂應用程式、3 個看板、3 個手冊、10 個整合以及管道、活動和論壇。
    *   [會議](https://zoho.com/meeting)— 最多可容納 3 位會議參與者和 10 位網路研討會參與者的會議。
    *   [Vault](https://zoho.com/vault) — 個人免費密碼管理。
    *   [Showtime](https://zoho.com/showtime) — 另一種會議軟體，用於培訓最多 5 位與會者的遠距會議。
    *   [Notebook](https://zoho.com/notebook) — Evernote 的免費替代方案。
    *   [Wiki](https://zoho.com/wiki) — 免費供 3 位使用者使用，擁有 50 MB 儲存空間、無限頁面、zip 備份、RSS 和 Atom 提要、存取控制和可自訂 CSS。
    *   [訂閱](https://zoho.com/subscriptions)— 為 20 位客戶/訂閱和 1 位使用者免費提供定期計費管理，所有付款託管均由 Zoho 自行完成。儲存最後 40 個訂閱指標
    *   [結帳](https://zoho.com/checkout)— 產品帳單管理，包含 3 個頁面和最多 50 筆付款。
    *   [服務台](https://zoho.com/desk)— 擁有 3 位代理商和私人知識庫、電子郵件票證的客戶支援管理。[與 1 名遠端技術人員和 5 台無人值守電腦的Assist](https://zoho.com/assist)整合。
    *   [Cliq](https://zoho.com/cliq) — 團隊聊天軟體，具有 100 GB 儲存空間、無限使用者、每個通道 100 個使用者和 SSO。
    *   [活動](https://zoho.com/campaigns)
    *   [形式](https://zoho.com/forms)
    *   [符號](https://zoho.com/sign)
    *   [調查](https://zoho.com/surveys)
    *   [預訂](https://zoho.com/bookings)
    *   [分析](https://zoho.com/analytics)
*   [重新發送](https://resend.com)\- 面向開發人員的交易電子郵件 API。每月 3,000 封電子郵件，每天免費 100 封電子郵件，1 個自訂網域。

**[⬆️回到頂部](#table-of-contents)**

功能切換管理平台
--------

*   [ConfigCat](https://configcat.com) - ConfigCat 是一項以開發人員為中心的功能標誌服務，具有無限的團隊規模、出色的支援和合理的價格標籤。每月免費方案最多 10 個標誌、2 個環境、1 個產品和 500 萬個請求。
*   [Flagsmith](https://flagsmith.com) - 自信地發布功能；跨 Web、行動和伺服器端應用程式管理功能標誌。使用我們的託管 API、部署到您自己的私有雲或在本地運行。
*   [GrowthBook](https://growthbook.io) - 開源功能標誌和 A/B 測試供應商，具有內建貝葉斯統計分析引擎。最多 3 位用戶免費，無限制的功能標誌和實驗。
*   [糖蜜](https://www.molasses.app)\- 強大的功能標記和 A/B 測試。釋放最多 3 個環境，每個環境有 5 個功能標誌。
*   [Toggled.dev](https://www.toggled.dev) - 企業級、可擴充和多區域功能切換管理平台。免費方案最多 10 個標誌、2 個環境、無限請求。SDK、分析儀表板、發布日曆、Slack 通知和所有其他功能都包含在無限免費方案中。

**[⬆️回到頂部](#table-of-contents)**

字體
--

*   [dafont](https://www.dafont.com/) - 本網站上提供的字體是其作者的財產，並且是免費軟體、共享軟體、演示版本或公共領域。
*   [Everything Fonts](https://everythingfonts.com/) - 提供多種工具；@font-face，單位轉換器，字體提示和字體提交器。
*   [Font Squirrel](https://www.fontsquirrel.com/) - 商業作品許可的免費軟體字體。手工選擇這些字體並以易於使用的格式呈現。
*   [Google Fonts](https://fonts.google.com/) - 許多免費字體，可以透過下載或 Google CDN 的連結輕鬆快速地安裝在網站中。
*   [FontGet](https://www.fontget.com/) - 有多種字體可供下載，並用標籤整齊地分類。
*   [Fontshare](https://www.fontshare.com/) - 是一項免費字體服務。這是一個不斷增長的專業級字體集合，100% 免費供個人和商業使用。
*   [Befonts](https://befonts.com/) - 提供幾種獨特的字體供個人或商業用途。
*   [網頁字體](https://fontofweb.com/)\- 識別網站上使用的所有字體以及它們的使用方式。
*   [兔子](https://bunny.net)
    *   [Bunny Fonts](https://fonts.bunny.net/) - 所有帶有 Google Fonts drop-in 相容 API 的 Google Fonts。以隱私為導向！
    *   [Bunny DNS](https://bunny.net/dns/) - DNS 託管，2000 萬次免費查詢
*   [FontsKey](https://www.fontskey.com/) - 提供個人使用的免費字體和商業付費字體，並且可以輸入文字進行快速過濾。

**[⬆️回到頂部](#table-of-contents)**

形式
--

*   [Feathery](https://feathery.io) - 功能強大、開發人員友好的表單產生器。建立註冊和登入、使用者入門、支付流程、複雜的財務應用程式等。免費方案允許每月最多 250 次提交和 5 個有效表格。
*   [Form-Data](https://form-data.com) - 無程式碼表單後端。垃圾郵件過濾器、電子郵件通知和自動回覆、webhooks、zapier、重定向、AJAX 或 POST 等。免費方案提供無限量的表單、每月 20 份提交以及帶有表單資料徽章的額外 2000 份提交。
*   [FabForm](https://fabform.io/) - 為智慧開發人員提供的表單後端平台。免費方案允許每月提交 250 份表格。友善的現代圖形使用者介面。與 Google Sheets、Airtable、Slack、電子郵件等整合。
*   [Form.taxi](https://form.taxi/) — HTML 表單提交的端點。具有通知、垃圾郵件攔截器和符合 GDPR 的資料處理功能。基本使用的免費方案。
*   [Formcake.com](https://formcake.com) - 開發人員的表單後端，免費方案允許無限的表單，100 次提交，Zapier 整合。不需要任何函式庫或相依性。
*   [Formcarry.com](https://formcarry.com) - HTTP POST 表單端點，免費方案每月允許 100 次提交。
*   [formingo.co](https://www.formingo.co/) - 靜態網站的簡單 HTML 表單，無需註冊帳戶即可免費開始。免費方案允許每月 500 次提交，可自訂回覆電子郵件地址。
*   [FormKeep.com](https://www.formkeep.com/) - 每月可提交 50 份無限表單、垃圾郵件防護、電子郵件通知以及可匯出 HTML 的拖放設計器。其他功能包括自訂欄位規則、團隊以及與 Google Sheets、Slack、ActiveCampaign 和 Zapier 的整合。
*   [formlets.com](https://formlets.com/) — 線上表單、每月無限的單頁表格、每月 100 份提交、電子郵件通知。
*   [formspark.io](https://formspark.io/) - 表單到電子郵件服務，免費方案允許無限量的表單，每月提交 250 份，由客戶支援團隊提供支援。
*   [Formspree.io](https://formspree.io/) — 使用 HTTP POST 要求傳送電子郵件。免費層級限制為每個表單每月提交 50 次。
*   [Formsubmit.co](https://formsubmit.co/) — HTML 表單的簡單表單端點。永遠免費。無需註冊。
*   [getform.io](https://getform.io/) - 為設計者和開發者提供的表單後端平台，1 個表單，50 個提交，單個文件上傳，100MB 文件存儲。
*   [HeroTofu.com](https://herotofu.com/) - 具有機器人檢測和加密存檔的表單後端。透過 UI 將提交轉發至電子郵件、Slack 或 Zapier。使用您自己的前端，無需伺服器程式碼。免費方案提供無限量的表格和每月 100 份提交。
*   [HeyForm.net](https://heyform.net/) - 拖放在線表單產生器。免費套餐可讓您建立無限量的表單並收集無限量的提交內容。配備預建模板、反垃圾郵件和 100MB 檔案儲存。
*   [Tally.so](https://tally.so/) - 99% 的功能都是完全免費的。免費套餐可讓您擁有以下功能：無限的表單、無限的提交、電子郵件通知、表單邏輯、收款、文件上傳、自訂感謝頁面等等。
*   [Hyperforms.app](https://hyperforms.app/) — 在幾秒鐘內建立表單到電子郵件等，無需後端程式碼。個人帳戶每月最多可免費向您提交 50 份表格。
*   [Kwes.io](https://kwes.io/) - 功能豐富的表單端點。非常適合靜態網站。免費方案包括最多 1 個網站，每月最多提交 50 條內容。
*   [Pageclip](https://pageclip.co/) - 免費方案允許一個網站、一份表格、每月 1,000 份提交。
*   [Qualtrics Survey－](https://qualtrics.com/free-account)使用這個一流的工具來建立專業的表格和調查。50 多個專家設計的調查範本。免費帳戶的限制為 1 項活躍調查、100 個回覆/調查和 8 種回覆類型。
*   [Screeb](https://screeb.app/) - 用於解碼使用者行為的應用內調查和產品分析。永久免費計劃允許 500 個每月活躍用戶、無限的回應和事件、許多整合、匯出和定期報告。
*   [smartforms.dev](https://smartforms.dev/) - 為您的網站提供強大而簡單的表單後端，永久免費計劃允許每月50 次提交，250MB 文件存儲，Zapier 集成，CSV/JSON 導出，自定義重定向，自定義響應頁面，Telegram和Slack 機器人，單一電子郵件通知。
*   [staticforms.xyz](https://www.staticforms.xyz/) - 免費整合 HTML 表單，無需任何伺服器端程式碼。用戶提交表單後，一封包含表單內容的電子郵件將發送到您的註冊地址。
*   [stepFORM.io](https://stepform.io) - 測驗和表單產生器。免費方案有 5 個表格，每個表格最多 3 個步驟，每月 50 個回覆。
*   [Typeform.com](https://www.typeform.com/) — 在網站上包含設計精美的表單。免費方案僅允許每個表單 10 個字段，每月僅允許 100 個回覆。
*   [WaiverStevie.com](https://waiverstevie.com) - 具有 REST API 的電子簽名平台。使用 webhook 接收通知。免費計劃水印簽署的文件，但允許無限的信封+簽名。
*   [Web3Forms](https://web3forms.com) - 靜態和 JAMStack 網站的聯絡表單，無需編寫後端程式碼。免費方案允許無限表格、無限域名和每月 250 次提交。
*   [WebAsk](https://webask.io) - 調查和表格產生器。免費方案每個帳戶有 3 項調查，每月 100 個回复，每個調查 10 個元素。
*   [Wufoo](https://www.wufoo.com/) - 在網站上使用的快速表單。免費方案每月提交的數量上限為 100 份。
*   [formpost.app](https://formpost.app) - 免費、無限制的表格到電子郵件服務。免費設定自訂重定向、自動回應、網路鉤子等。
*   [Formester.com](https://formester.com) - 在您的網站上共享和嵌入外觀獨特的表單 - 創建的表單數量沒有限制，也沒有計劃限制的功能。每月最多可免費提交 100 份作品。
*   [SimplePDF.eu](https://simplepdf.eu/embed) - 在您的網站上嵌入 PDF 編輯器，並將任何 PDF 轉換為可填寫的表單。免費方案允許無限量的 PDF，每個 PDF 可以提交 3 次。
*   [forms.app](https://forms.app/) — 建立具有強大功能（如條件邏輯、自動分數計算器和人工智慧）的線上表單。透過免費方案收集最多 100 個回复，將表單嵌入到網站上，或透過連結使用它們。

**[⬆️回到頂部](#table-of-contents)**

CDN 和保護
-------

*   [bootstrapcdn.com](https://www.bootstrapcdn.com/) — bootstrap、bootswatch 和 fontawesome.io 的 CDN
*   [cdnjs.com](https://cdnjs.com/) — 簡單。快速地。可靠的。最好的內容交付。cdnjs 是一項由 Cloudflare 提供支援的免費開源 CDN 服務，受到超過 11% 的網站信任。
*   [Developers.google.com](https://developers.google.com/speed/libraries/) — Google 託管庫是最受歡迎的開源 JavaScript 庫的內容分發網絡
*   [Stellate](https://stellate.co/) -Stellate 是適用於 GraphQL API 的快速、可靠的 CDN，並且免費提供 2 項服務。
*   [jsdelivr.com](https://www.jsdelivr.com/) — 一張免費、快速、可靠的開源 CDN。支援 npm、GitHub、WordPress、Deno 等。
*   [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 託管流行的第三方 JavaScript 程式庫（例如 jQuery），讓您能夠輕鬆地將它們新增至您的 Web 應用程式中
*   [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免費 DDoS 保護和 SSL 證書
*   [PageCDN.com](https://pagecdn.com/) - 為所有人提供免費的公開 CDN，為開源/非營利組織提供免費的私人 CDN。
*   [Skypack](https://www.skypack.dev/) — 100% 原生 ES 模組 JavaScript CDN。每個網域每月 100 萬個請求免費。
*   [raw.githack.com —](https://raw.githack.com/) **rawgit.com**的現代替代品，它只是使用 Cloudflare 託管文件
*   [section.io](https://www.section.io/) — 一種啟動和管理完整 Varnish 快取解決方案的簡單方法。據說一個網站永遠免費
*   [statically.io](https://statically.io/) — Git 儲存庫（GitHub、GitLab、Bitbucket）、WordPress 相關資產和圖像的 CDN
*   [toranproxy.com](https://toranproxy.com/) — Packagist 和 GitHub 的代理商。CD 永遠不會失敗。免費供個人使用，1 名開發人員，無支持
*   [UNPKG](https://unpkg.com/) — npm 上所有內容的 CDN
*   [weserv](https://images.weserv.nl/) — 影像快取和調整大小服務。使用全球快取即時處理圖像。
*   [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免費 DDoS 防護
*   [格芯](https://gcorelabs.com/)
    *   [CDN](https://gcorelabs.com/cdn/) — 全球內容交付網絡，每月免費 1 TB 和 100 萬個請求。
    *   [DNS 託管](https://gcorelabs.com/dns/)— 免費 DNS 託管。
*   [LightCDN](https://www.lightcdn.com) - 免費 100GB CDN，內含 8 個國際流行音樂。無限制的 HTTP(S) 請求。

**[⬆️回到頂部](#table-of-contents)**

平台即服務
-----

*   [anvil.works](https://anvil.works) - 僅使用 Python 進行 Web 應用程式開發。免費套餐，無限應用程序，30 秒超時。
*   [configure.it](https://www.configure.it/) — 行動應用程式開發平台，免費 2 個專案使用，功能有限但沒有資源限制
*   [codenameone.com](https://www.codenameone.com/) — 針對 Java/Kotlin 開發人員的開源、跨平台、行動應用程式開發工具鏈。免費用於商業用途，項目數量不受限制
*   [Cosmonic](https://cosmonic.com) - 功能豐富的 WebAssembly PaaS 和 SDK，可實現低樣板、靈活且預設安全的微服務。始終免費層包括託管主機、25 個微服務，以及強大的鍵值儲存、負載平衡公共 HTTP 端點等功能。
*   [Cyclic](https://www.cyclic.sh) - 全端應用程式託管 - 推送到 Github 以建置和部署 Javascript/Node.js 應用程式。包括：身份驗證、Cron 作業、自訂網域、資料庫、儲存和流程日誌。付費方案包括：基於分公司的環境、多區域部署和增加的限制。
*   [Deno Deploy](https://deno.com/deploy) - 在全球邊緣執行 JavaScript、TypeScript 和 WebAssembly 的分散式系統。免費套餐包括每天 100,000 個請求和每月 100 GiB 資料傳輸。
*   [domcloud.co](https://domcloud.co) – Linux 託管服務，也提供 GitHub、SSH 和 MariaDB/Postgres 資料庫的 CI/CD。免費版本有 1 GB 儲存空間和 1 GB 網路/月限制，並且僅限於免費網域。
*   [encore.dev](https://encore.dev/) — 使用靜態分析提供自動化基礎架構、無樣板程式碼等的後端框架。包括用於業餘愛好專案的免費雲端託管。
*   [gigalixir.com](https://gigalixir.com/) - Gigalixir 為 Elixir/Phoenix 應用程式提供 1 個永不休眠的免費實例，以及僅限 2 個連接、10, 000 行且無備份的免費 PostgreSQL 資料庫。
*   [Glitch](https://glitch.com/) — 免費公共託管，具有程式碼共享和即時協作等功能。免費方案有 1000 小時/月的限制。
*   [Mendix](https://www.mendix.com/) — 企業快速應用程式開發，無限數量的免費沙箱環境，支援無限用戶，每個應用程式 0.5 GB 儲存和 1 GB RAM。免費套餐中也允許使用 Studio 和 Studio Pro IDE。
*   [m3o.com](https://m3o.com) - 用於 API 服務開發的雲端平台。M3O 是一個完全託管的微即服務產品，專注於雲端中的 Go 微服務開發。免費套餐足以運行 5 項服務並與其他人合作。
*   [Pipedream.com](https://pipedream.com) - 為開發人員打造的整合平台。基於任何觸發器開發任何工作流程。工作流程是程式碼，您可以[免費](https://docs.pipedream.com/pricing/)運行。無需管理伺服器或雲端資源。
*   [pythonanywhere.com](https://www.pythonanywhere.com/) — 雲端 Python 應用程式託管。初學者帳戶免費，1 個位於 your-username.pythonanywhere.com 網域的 Python Web 應用程序，512 MB 私人文件存儲，1 個 MySQL 資料庫
*   [無伺服器雲端](https://www.serverless.com/cloud)\- 無伺服器雲端可讓您使用程式碼基礎架構方法（無 yaml，無基礎架構配置）建置無伺服器 API、資料庫和_儲存_。該產品由 Serverless Inc. 提供，目前處於公共預覽階段。
*   [Fly.io](https://fly.io/) - Fly 是一個需要在全球運行的應用程式的平台。它在靠近用戶的地方運行您的程式碼，並在您的應用程式最繁忙的城市擴展計算。編寫程式碼，將其打包到 Docker 映像中，將其部署到 Fly 平台，然後讓它完成所有工作，以保持應用程式的敏捷性。免費配額包括最多 3 個共享 cpu-1x 256mb 虛擬機器、3GB 持久磁碟區儲存（總計）和 160GB 出站資料傳輸。
*   [Divio](https://www.divio.com/) - 一個僅使用 Docker 管理雲端應用程式部署的平台。可免費訂閱開發項目。需要卡片且無自訂網域支援。
*   [Koyeb](https://www.koyeb.com) -Koyeb 是一個開發人員友好的無伺服器平台，用於在全球部署應用程式。透過基於 git 的部署、本機自動縮放、全球邊緣網路以及內建服務網格和發現，無縫運行 Docker 容器、Web 應用程式和 API。Koyeb 提供兩種 Nano 服務，透過其永久免費層運行您的應用程序，並透過免費資源贊助開源專案。免費方案需要卡片資訊。
*   [Napkin](https://www.napkin.io/) - FaaS，記憶體 500Mb，預設逾時 15 秒，每月免費 API 呼叫 5,000 次，速率限制為每秒 5 次呼叫。
*   [Meteor Cloud](https://www.meteor.com/cloud) — Galaxy 託管。Meteor 自己的 Meteor 應用程式平台即服務，其中包括免費的 MongoDB 共享託管和自動 SSL。
*   [Northflank](https://northflank.com) — 使用強大的 UI、API 和 CLI 建置和部署微服務、作業和託管資料庫。從版本控制和外部 Docker 註冊表無縫擴展容器。免費套餐包括 2 項服務、2 個 cron 作業和 1 個資料庫。
*   [YepCode](https://yepcode.io) - 在無伺服器環境中連接 API 和服務的一體化平台。它帶來了 NoCode 工具的所有敏捷性和優勢，同時也具有使用程式語言的所有功能。免費套餐包括[1.000 yeps](https://yepcode.io/pricing/)。
*   [WunderGraph](https://cloud.wundergraph.com) - 一個開源平台，可讓您快速建立、發布和管理現代 API。內建 CI/CD、GitHub 整合、自動 HTTPS。[免費方案](https://wundergraph.com/pricing)最多 3 個項目、1GB 出口、每月 300 分鐘的建置時間[](https://wundergraph.com/pricing)
*   [Doprax Cloud](https://www.doprax.com) — 為您的應用程式、網站和 API 提供雲端託管。一個應用程式免費，配備 4 \* 256MB 內存和 2 GB 磁碟。要創建應用程式空間，您的帳戶信用餘額至少需要 3 美元。
*   [Zeabur](https://zeabur.com) - 一鍵部署您的服務。3 項服務免費，每月 5 美元免費積分。

**[⬆️回到頂部](#table-of-contents)**

BaaS
----

*   [Activepieces](https://www.activepieces.com) - 建立自動化流程以在應用程式後端將多個應用程式連接在一起。例如，當您的應用程式中觸發事件時，請發送 Slack 訊息或新增 Google 試算表行。每月最多可釋放 5,000 個任務。
*   [back4app.com](https://www.back4app.com) - Back4App 是一個基於 Parse Platform 的易於使用、靈活且可擴展的後端。
*   [backendless.com](https://backendless.com/) — 行動與 Web Baas，免費提供 1 GB 檔案儲存空間，每月推播通知 50000 條，表中包含 1000 個資料物件。
*   [BMC 開發人員計畫](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp)— BMC 開發人員計畫提供文件和資源來為您的企業建置和部署數位創新。存取全面的個人沙箱，其中包括平台、SDK 以及可用於建置和自訂應用程式的元件庫。
*   [凸.dev](https://convex.dev/) - 反應式後端即服務，託管資料（具有關聯式和可序列化 ACID 交易的文件）、無伺服器功能和用於將更新串流傳輸到各種客戶端的 Websocket。小型專案免費 - 每月最多 1M 筆記錄、5M 次函數呼叫。
*   [darklang.com](https://darklang.com/) - 與編輯器和基礎架構結合的託管語言。測試期間免費，測試後計劃提供慷慨的免費套餐。
*   [Firebase](https://firebase.com) — Firebase 可協助您建置和執行成功的應用程式。免費 Spark 方案提供身份驗證、託管、Firebase ML、即時資料庫、雲端儲存、測試實驗室。A/B 測試、分析、應用程式分發、應用程式索引、雲端訊息傳遞 (FCM)、Crashlytics、動態連結、應用程式內訊息傳遞、效能監控、預測和遠端配置始終免費。
*   [Flutter Flow](https://flutterflow.io) — 無需編寫任何程式碼即可建立 Flutter 應用程式 UI。還有 Firebase 整合。免費計劃包括對 UI Builder 和免費模板的完全存取權限。
*   [getstream.io](https://getstream.io/) — 在幾個小時而不是幾週內建立可擴展的應用程式內聊天、訊息傳遞、視訊和音訊以及來源
*   [hasura.io](https://hasura.io/) — Hasura 可以擴展您現有的資料庫（無論其託管在何處），並提供即時 GraphQL API，可安全地存取 Web、行動和資料整合工作負載。免費每月 1GB 資料傳輸。
*   [iron.io](https://www.iron.io/) — 非同步任務處理（如 AWS Lambda），提供免費套餐和 1 個月免費試用
*   [nhost.io](https://nhost.io) - 用於網路和行動應用程式的無伺服器後端。免費方案包括：PostgreSQL、GraphQL (Hasura)、驗證、儲存和無伺服器功能。
*   [nudge-hook.net](https://nudge-hook.net/client) — 作業排程 API（附有 swagger/openapi 用戶端）。允許您根據需要安排任意數量的 adhoc/cron/定期 webhook 交付。所有人免費（無需註冊），但無限的時間表僅限於最多 500 次「輕推」。接受捐款。
*   [onesignal.com](https://onesignal.com/) — 無限制的免費推播通知
*   [paraio.com](https://paraio.com) — 具有靈活驗證、全文搜尋和快取的後端服務 API。1 個應用程式免費，1GB 應用程式資料。
*   [Progress.com](https://www.progress.com/kinvey) — 行動後端，入門計畫每秒有無限的請求，具有 1 GB 的資料儲存空間。企業應用支援
*   [pubnub.com](https://www.pubnub.com/) — 每月最多 100 萬條訊息和 100 個日常活躍裝置的免費推播通知
*   [Pushbots.com](https://pushbots.com/) — 推播通知服務。每月最多免費推送 150 萬次
*   [Pushcrew.com](https://pushcrew.com/) — 推播通知服務。最多 2000 位訂閱者的無限通知
*   [Pusher.com](https://pusher.com/beams) — 為 2000 名每月活躍用戶提供免費、無限制的推播通知。適用於 iOS 和 Android 裝置的單一 API。
*   [engagespot.co](https://engagespot.co/) — 為開發人員提供的通知基礎設施。每月最多 100 名活躍用戶免費。
*   [Quickblox.com](https://quickblox.com/) — 用於即時訊息、視訊和語音通話以及推播通知的通訊後端
*   [Restspace.io](https://restspace.io/) - 使用驗證、資料、檔案、電子郵件 API、範本等服務設定伺服器，然後組成管道並轉換資料。
*   [Salesforce 開發人員計畫](https://developer.salesforce.com/signup)— 使用拖放工具快速建立應用程式。透過點擊自訂您的資料模型。使用 Apex 程式碼更進一步。使用強大的 API 與任何東西整合。透過企業級安全性保持保護。透過點擊或任何領先的 Web 框架自訂 UI。免費開發者計畫可以存取完整的閃電平台。
*   [ServiceNow 開發人員計畫](https://developer.servicenow.com/)— 快速建置、測試和部署應用程序，使您的組織更好地工作。免費實例並存取早期預覽。
*   [simperium.com](https://simperium.com/) — 即時、自動地將數據移動到任何地方，多平台，無限制發送和存儲結構化數據，最大數量。2,500 位使用者/月
*   [stackstorm.com](https://stackstorm.com/) — 應用程式、服務和工作流程的事件驅動自動化，免費，無流量，存取控制，LDAP，...
*   [Streamdata.io](https://streamdata.io/) — 將任何 REST API 轉換為事件驅動的流 API。免費方案最多 100 萬個訊息和 10 個並發連線。
*   [Supabase](https://supabase.com) — 用於建立後端的開源 Firebase 替代方案。免費方案提供身份驗證、即時資料庫和物件儲存。
*   [tyk.io](https://tyk.io/) — 具有身分驗證、配額、監控和分析功能的 API 管理。免費雲端產品
*   [zapier.com](https://zapier.com/) — 連接您使用的應用程式以自動執行任務。5 次 zap，每 15 分鐘一次，每月 100 項任務
*   [IFTTT](https://ifttt.com) — 自動化您喜愛的應用程式和裝置。免費 2 個小程序
*   [整合](https://integrately.com)— 只需單擊即可自動執行繁瑣的任務。免費 100 個任務、15 分鐘  
    更新時間、5 個活動自動化、webhooks。
*   [LeanCloud－](https://leancloud.app/)行動後端。1GB 資料儲存、256MB 實例、3K API 請求/天、10K 推送/天都是免費的。（API與Parse Platform非常相似）

**[⬆️回到頂部](#table-of-contents)**

低程式碼平台
------

*   [BudiBase](https://budibase.com/) — Budibase 是一個開源低程式碼平台，可在幾分鐘內建立內部應用程式。支援 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s
*   [appsmith](https://www.appsmith.com/) - 用於建立管理面板、內部工具和儀表板的低程式碼專案。與超過 15 個資料庫和任何 API 整合。
*   [ToolJet](https://www.tooljet.com/) — 用於建立業務應用程式的可擴展低程式碼框架。連接到資料庫、雲端儲存、GraphQL、API 端點、Airtable 等，並使用拖放應用程式生成器建立應用程式。
*   [ReTool](https://retool.com/) — 用於建立內部應用程式的低程式碼平台。Retool 是高度可破解的。如果您可以使用 JavaScript 和 API 編寫它，則可以在 Retool 中建置它。免費套餐每月最多允許 5 個用戶、無限的應用程式和 API 連線。
*   [DronaHQ](https://www.dronahq.com/) — DronaHQ - 一個低代碼平台，可幫助工程團隊和產品經理建立內部工具、自訂使用者旅程、數位體驗、自動化、自訂管理面板、操作應用程序，速度提高 10 倍。
*   [ILLA Cloud](https://www.illacloud.com/) — ILLA Cloud - 一個強大的開源低程式碼平台，供開發人員建立內部工具。透過使用 ILLA 的元件和操作庫，開發人員可以節省建置工具的大量時間。5 名團隊成員免費。
*   [outsystems.com](https://www.outsystems.com/) — 適用於本地或雲端的企業 Web 開發 PaaS，免費的「個人環境」產品允許無限的程式碼和高達 1 GB 的資料庫

**[⬆️回到頂部](#table-of-contents)**

虛擬主機
----

*   [Alwaysdata](https://www.alwaysdata.com/) — 100 MB 免費網站寄存，支援 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自訂 Web 伺服器，透過 FTP、WebDAV 和 SSH 存取；包括郵箱、郵件清單和應用程式安裝程式。
*   [Awardspace.com](https://www.awardspace.com) — 免費網站寄存 + 免費短網域、PHP、MySQL、應用程式安裝程式、電子郵件傳送和無廣告。
*   [Bubble](https://bubble.io/) — 無需代碼即可使用視覺化編程建立網頁和行動應用程序，免費使用 Bubble 品牌。
*   [dAppling Network](https://www.dappling.network/) - 用於 Web3 前端的去中心化 Web 託管平台，專注於增加正常運行時間、安全性並為使用者提供額外的存取點。
*   [DigitalOcean](https://www.digitalocean.com/pricing) - 在應用程式平台入門層上免費建置和部署 3 個靜態網站。
*   [Drive To Web](https://drv.tw) — 從 Google Drive 和 OneDrive 直接託管到網路。僅靜態站點。永遠免費。每個 Google/Microsoft 帳號一個網站。
*   [DuckDocs](https://duckdocs.com) - Markdown 支援的文件託管，有點像託管的 Docusaurus。每個站點 10 個頁面免費。
*   [Fenix Web Server](https://preview.fenixwebserver.com) - 一款開發人員桌面應用程序，用於在本地託管網站並公開共享（即時）。使用其漂亮的使用者介面、API 和/或 CLI，隨心所欲地工作。
*   [免費託管](https://freehostingnoads.net/)— 免費託管 PHP 5、Perl、CGI、MySQL、FTP、檔案管理器、POP 電子郵件、免費子網域、免費網域託管、DNS 區域編輯器、網站統計、免費線上支援以及更多功能由其他免費主機提供。
*   [Freehostia](https://www.freehostia.com) — FreeHostia 提供免費主機服務，包括。業界最佳的控制面板和 50 多個免費應用程式的一鍵安裝。即時設定。沒有強制廣告。
*   [HelioHost](https://heliohost.org) — 非營利免費網站寄存，附Plesk 控制面板、PHP、Node.js、Python、Django、Flask、.NET、Perl、CGI、MySQL、PostgreSQL、SQLite、IMAP/POP3/SMTP 電子郵件、無限頻寬、免費子網域, 1000 MB 免費儲存空間，並可選擇升級。
*   [Lecturify](https://www.lecturify.net/index.en.html) - 具有 sftp 存取權限的網站託管，用於檔案上傳和下載，可用 php。
*   [Neocities](https://neocities.org) — 靜態、1 GB 免費儲存空間和 200 GB 頻寬。
*   [Netlify](https://www.netlify.com/) — 免費建置、部署和託管靜態網站/應用程序，提供 100 GB 資料和每月 100 GB 頻寬。
*   [pantheon.io](https://pantheon.io/) — Drupal 和 WordPress 託管、自動化 DevOps 和可擴展的基礎設施。開發商和機構免費。沒有自訂網域。
*   [readthedocs.org](https://readthedocs.org/) — 免費文件託管，具有版本控制、PDF 生成等功能
*   [render.com](https://render.com) — 統一的雲，用於建立和運行應用程式和網站，具有免費的 SSL、全球 CDN、專用網路、Git 自動部署以及完全免費的 Web 服務、資料庫和靜態網頁計劃。
*   [SourceForge](https://sourceforge.net/) — 免費尋找、建立和發布開源軟體
*   [Stormkit](https://stormkit.io/) — 將建置、部署和託管與 JAMStack 或 Node.JS 應用程式的 git 流程無縫整合。每月免費 50 GB 頻寬和 10m 請求，包括免費 SSL。
*   [Surge.sh](https://surge.sh/) — 前端開發人員的靜態 Web 發布。具有自訂網域支援的無限站點
*   [telegra.ph](https://telegra.ph/)使用 Quill 輕鬆創建網頁
*   [tilda.cc](https://tilda.cc/) — 一個站點，50 個頁面，50 MB 存儲空間，僅 170 多個可用的主要預定義塊，沒有字體，沒有圖標，也沒有自定義域
*   [Vercel](https://vercel.com/) — 每次使用免費的 SSL、全球 CDN 和獨特的預覽 URL 建置、部署和託管 Web 應用程式`git push`。非常適合 Next.js 和其他靜態站點產生器。
*   [Versoly](https://versoly.com/) — 專注於 SaaS 的網站建立器 - 無限的網站、70 多個區塊、5 個範本、自訂 CSS、favicon、SEO 和表單。沒有自訂網域。
*   [Qoddi](https://qoddi.com) - 類似於 Heroku 的 PaaS 服務，具有以開發人員為中心的方法和全包功能。靜態資產、暫存和開發應用程式的免費方案。
*   [FreeFlarum](https://freeflarum.com/) - 社群支援的免費 Flarum 託管，最多可容納 250 個使用者（捐贈以刪除頁腳浮水印）。
*   [flek.co](https://fleek.co/) - 在開放網路及其協議上無縫免費建立現代網站和應用程序，無限的網站和 50 GB/月的頻寬。
*   [MDB GO](https://mdbgo.com/) - 免費託管 1 個項目，容器 TTL 為 2 週，每個項目 500mb RAM，SFTP - 1G 磁碟空間。
*   [Patr Cloud](https://patr.cloud/) — 一個易於使用的雲端平台，在其付費服務中，它提供免費託管 3 個靜態網站。
*   [Serv00.com](https://serv00.com/) — 3 GB 免費網頁寄存，每日備份（7 天）。支援：Crontab 作業、SSH 存取、儲存庫（GIT、SVN 和 Mercurial），支援：MySQL、PostgreSQL、MongoDB、PHP、Node.js、Python、Ruby、Java、Perl、TCL/TK、Lua、Erlang、Rust、 Pascal、C、C++、D、R 等等。

**[⬆️回到頂部](#table-of-contents)**

域名系統
----

*   [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - 由 CloudFlare 提供的免費公共 DNS 解析器，快速且安全（加密您的 DNS 查詢）。可用於繞過網路供應商的 DNS 封鎖、防止 DNS 查詢間諜活動以及[封鎖成人和惡意軟體內容](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)。[也可以透過 API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests)使用。注意：只是 DNS 解析器，而不是 DNS 託管服務商。
*   [1984.is](https://www.1984.is/product/freedns/) — 帶有 API 的免費 DNS 服務，以及許多其他免費 DNS 功能。
*   [cloudns.net](https://www.cloudns.net/) — 免費 DNS 託管最多 1 個包含 50 筆記錄的網域
*   [deSEC](https://desec.io) - 具有 API 支援的免費 DNS 託管，設計時考慮到安全性。在開源軟體上運作並受[SSE](https://www.securesystems.de/)支援。
*   [dns.he.net](https://dns.he.net/) — 具有動態 DNS 支援的免費 DNS 託管服務
*   [Zonomi](https://zonomi.com/) — 免費 DNS 託管服務，具有即時 DNS 傳播功能。免費方案：1 個 DNS 區域（網域名稱），最多 10 筆 DNS 記錄。
*   [dnspod.com](https://www.dnspod.com/) — 免費 DNS 託管。
*   [duckdns.org](https://www.duckdns.org/) — 免費 DDNS，免費層最多包含 5 個網域。帶有各種設定的配置指南。
*   [freedns.afraid.org](https://freedns.afraid.org/) — 免費 DNS 託管。也提供基於眾多公共用戶[貢獻的網域的](https://freedns.afraid.org/domain/registry/)免費子網域。註冊後從「子網域」選單取得免費子網域。
*   [luadns.com](https://www.luadns.com/) — 免費 DNS 託管，3 個網域，所有功能都有合理的限制
*   [namecheap.com](https://www.namecheap.com/domains/freedns/) — 免費 DNS。網域數量沒有限制
*   [nextdns.io](https://nextdns.io) - 基於 DNS 的防火牆，每月 30 萬次免費查詢
*   [noip](https://www.noip.com/) — 動態 DNS 服務，允許最多 3 個免費主機名，每 30 天確認一次
*   [sslip.io](https://sslip.io/) — 免費 DNS 服務，當使用內建 IP 位址的主機名稱進行查詢時，會傳回該 IP 位址。
*   [zilore.com](https://zilore.com/en/dns) — 免費 DNS 託管，免費提供 5 個網域。
*   [zoneedit.com](https://www.zoneedit.com/free-dns/) — 免費 DNS 託管，支援動態 DNS。
*   [zonewatcher.com](https://zonewatcher.com) — 自動備份與 DNS 變更監控。1 個免費域名
*   [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 華為免費 DNS 託管
*   [Hetzner](https://www.hetzner.com/dns-console) – Hetzner 提供的免費 DNS 託管，具有 API 支援。
*   [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 個網域的免費 DNS 託管和 DNSSEC 支持

**[⬆️回到頂部](#table-of-contents)**

領域
--

*   [eu.org](https://nic.eu.org) — 免費 eu.org 網域。請求通常會在 14 天內獲得批准。
*   [pp.ua](https://nic.ua/) — 免費 pp.ua 子域。

**[⬆️回到頂部](#table-of-contents)**

基礎設施即服務
-------

*   [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 雲端儲存。無限期免費 10 GB（類似 Amazon S3）物件存儲
*   [filebase.com](https://filebase.com/) - 由區塊鏈支援的 S3 相容物件儲存。5 GB 無限期免費儲存空間。
*   [scaleway](https://www.scaleway.com/en/object-storage/) — S3 相容的物件儲存。免費 75 GB 儲存空間和外部傳出流量（需要信用卡）。
*   [Storj](https://storj.io/) — 應用程式和開發人員的去中心化私有雲端儲存。免費方案提供 1 個項目、25 GB 儲存空間、每月 25 GB 頻寬。
*   [Tebi](https://tebi.io/) - S3 相容物件儲存。免費 25 GB 儲存和 250GB 出站傳輸。
*   [Idrive e2](https://www.idrive.com/e2/) - S3 相容物件儲存。每月 10 GB 免費儲存空間和 10 GB 下載頻寬。
*   [C2 物件儲存](https://c2.synology.com/en-us/pricing/object-storage)\- S3 相容物件儲存。15 GB 免費儲存空間和每月 15 GB 下載量。
*   [Spheron](https://spheron.network/) — 從去中心化雲端儲存、虛擬主機到去中心化運算，為應用程式和開發人員在一個平台下提供服務，免費方案提供 5GB 儲存、100GB 頻寬、無限網域和項目，5w哦rtH哦FC哦米p你teres哦你rCes（瓦哦rtH50 噸 AWS）。

**[⬆️回到頂部](#table-of-contents)**

託管資料服務
------

*   [Aiven](https://aiven.io/) - Aiven 在其開源資料平台上提供免費的 PostgreSQL、MySQL 和 Redis 計劃。單節點、1 個 CPU、1GB RAM，對於 PostgreSQL 和 MySQL，5GB 儲存。輕鬆遷移到更大的計劃或跨雲端。
*   [airtable.com](https://airtable.com/) — 看起來像電子表格，但它是一個關係資料庫，無限的基數，1,200 行/基數和 1,000 個 API 請求/月
*   [Astra](https://www.datastax.com/products/datastax-astra/) — 雲端原生 Cassandra 即服務，具有[80GB 免費套餐](https://www.datastax.com/products/datastax-astra/pricing)
*   [codehooks.io](https://codehooks.io/) — JavaScript 無伺服器 API/後端和資料庫服務，具有函數、Mongdb-ish 查詢、鍵/值查找、作業系統和訊息佇列。每個項目免費 1 個實例，每月免費 5000 筆記錄和 5000 次調用，包括 3 名開發人員。無需信用卡。
*   [CrateDB](https://crate.io/) - 用於即時分析的分散式開源 SQL 資料庫。[免費層 CRFREE](https://crate.io/lp-crfree)：具有 2 個 CPU、2 GiB 記憶體、8 GiB 儲存的節點。每個組織 1 個集群，無需付款方式。
*   [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL 即服務，20 MB 免費
*   [FaunaDB](https://fauna.com/) — 無伺服器雲端資料庫，具有原生 GraphQL、多模型存取和高達 100 MB 的每日免費套餐
*   [HarperDb](https://harperdb.io/) — 無伺服器雲端資料庫，具有基於 JSON 的動態模式、3000 IOPS 和 1GB 存儲
*   [Upstash](https://upstash.com/) — 無伺服器 Redis，免費套餐每天最多 10,000 個請求、最大資料庫大小 256MB 和 20 個並發連接
*   [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免費套餐提供 512 MB
*   [redsmin.com](https://www.redsmin.com/) — Redis 線上即時監控與管理服務，免費監控 1 個 Redis 實例
*   [redislabs](https://redislabs.com/try-free/) - 免費 30MB redis 實例
*   [MemCachier](https://www.memcachier.com/) — 託管 Memcache 服務。免費提供高達 25MB、1 個代理伺服器和基本分析
*   [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 至 192MB 免費的 MySQL、PostgreSQL 或 MongoDB
*   [SeaTable](https://seatable.io/) — 由 Seafile 團隊建構的靈活的、類似電子表格的資料庫。無限表、2,000 行、1 個月版本控制、最多 25 名團隊成員。
*   [skyvia.com](https://skyvia.com/) — 雲端數據平台，提供免費套餐，所有計劃在測試階段都是完全免費的
*   [StackBy](https://stackby.com/) — 一種工具，集電子表格的靈活性、資料庫的強大功能以及與您喜愛的業務應用程式的內建整合於一體。免費方案包括無限用戶、10 個堆疊、每個堆疊 2GB 附件。
*   [TiDB Cloud](https://en.pingcap.com/tidb-cloud/) — TiDB 是一個開源的 MySQL 相容的分散式 HTAP RDBMS。TiDB Serverless 每月免費提供 5GB 行儲存和 5GB 列儲存以及 5000 萬個請求單元（RU）。
*   [Turso by ChiselStrike](https://chiselstrike.com/) - Turso 是邊緣資料庫中的 SQLite 開發人員體驗。Turso 提供永久免費入門計劃、8 GB 總儲存空間、最多 3 個資料庫、最多 3 個位置、每月 10 億行讀取以及 SQLite 本地開發支援。
*   [InfluxDB](https://www.influxdata.com/) — 時間序列資料庫，可釋放高達 3MB/5 分鐘寫入、30MB/5 分鐘讀取和 10,000 個基數序列
*   [restdb.io](https://restdb.io/) - 快速且簡單的 NoSQL 雲端資料庫服務。透過restdb.io，您可以獲得架構、關聯、自動 REST API（帶有類似 MongoDB 的查詢）以及用於處理資料的高效多用戶管理 UI。免費方案允許 3 個用戶、2500 筆記錄和每秒 1 個 API 請求。
*   [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 免費 CockroachDB 高達 5GB 和 1vCPU（有限[請求單位](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta)）
*   [Neo4j Aura](https://neo4j.com/cloud/aura/) — 具有 Cypher 查詢語言和 REST API 的託管本機圖形 DBMS/分析平台。圖大小限制（50k 節點，175k 關係）。
*   [Neon](https://neon.tech/) — 託管 PostgreSQL，10 個分支，每個分支 3 GB 存儲，主分支計算的活動時間沒有限制，非主分支計算每月（總計）100 小時的活動時間。
*   [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free) — 使用 GraphQL API 管理原生圖形 DBMS。每天僅限 1 MB 資料傳輸。
*   [Tinybird](https://tinybird.co) - 無伺服器託管 ClickHouse，透過 HTTP 進行無連線資料攝取，讓您可以將 SQL 查詢發佈為託管 HTTP API。免費方案無時間限制，每天 10GB 儲存 + 1000 個 API 請求。
*   [TigerGraph Cloud](https://www.tigergraph.com/cloud/) — 託管本機圖形 DBMS/分析平台，具有類似 SQL 的圖形查詢語言和 REST API。一個具有 2 個 vCPU、8GB 記憶體和 50GB 儲存空間的免費實例，在 1 小時不活動後進入休眠狀態。
*   [TerminusCMS](https://terminusdb.com/pricing) — TerminusDB 的託管免費服務，TerminusDB 是一個用 Prolog 和 Rust 編寫的文件和圖形資料庫。開發人員免費，企業部署和支援付費服務。
*   [Planetscale](https://planetscale.com/) - PlanetScale 是一個由Vitess 支援的MySQL 相容的無伺服器資料庫平台，1 個免費資料庫，1 個生產分支和1 個開發分支，5GB 存儲，每個資料庫每月讀取10 億行，每個資料庫每月寫入1000 萬行。
*   [YugabyteDB](https://cloud.yugabyte.com) - YugabyteDB 是一個與 PostgreSQL 相容的分散式 SQL 資料庫。雲端免費層是 2 個 vCPU、4GB RAM、10GB 磁碟。
*   [filess.io](https://filess.io) - filess.io 是一個平台，您可以在其中免費建立以下 DBMS 的 1 個資料庫：MySQL、MariaDB、MongoDB、PostgreSQL。
*   [xata.io](https://xata.io) - Xata 是一個無伺服器資料庫，具有內建的強大搜尋和分析功能。一個 API、多個類型安全的客戶端程式庫，並針對您的開發工作流程進行了最佳化。永久免費套餐對於業餘愛好者來說已經足夠了，它附帶 3 個 Xata 單位，單位定義請參閱網站。
*   [8base.com](https://www.8base.com/) - 8base 是一個全端低程式碼開發平台，專為 JavaScript 開發人員構建，基於 MySQL 和 GraphQL 以及無伺服器後端即服務，它允許您使用 UI 應用程式生成器快速開始構建 Web 應用程式並且易於擴展，免費套餐包括：行數：2,500，儲存：500Mb，無伺服器運算：1Gb/h，客戶端應用程式用戶：5。

**[⬆️回到頂部](#table-of-contents)**

隧道、WebRTC、Web Socket 伺服器和其他路由器
------------------------------

*   [Pinggy](https://pinggy.io) — 使用單一指令即可取得本機的公共 URL，無需下載。HTTPS / TCP / TLS 隧道。免費方案的隧道使用壽命為 60 分鐘。
*   [傳送帶.cloud](https://conveyor.cloud/) — Visual Studio 擴展，用於將 IIS Express 公開到本地網路或透過隧道公開到公共 URL。
*   [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一項託管 VPN 服務，可讓您透過免費方案安全地將類似 LAN 的網路擴展到分散式團隊，允許最多 5 人的無限網絡
*   [localhost.run](https://localhost.run/) — 透過隧道將本機執行的伺服器公開到公用 URL。
*   [localtunnel](https://theboroer.github.io/localtunnel-www/) — 透過隧道將本機運行的伺服器公開到公用 URL。免費託管版本，並且[開源](https://github.com/localtunnel/localtunnel)。
*   [ngrok.com](https://ngrok.com/) — 透過隧道將本地運行的伺服器公開到公共 URL。
*   [Radmin VPN](https://www.radmin-vpn.com/) — 透過 VPN 將多台電腦連接在一起，從而實現類似 LAN 的網路。無限的同行。（Hamachi替代品）
*   [segment.com](https://segment.com/) — 將事件轉換並路由到其他第三方服務的中心。每月 100,000 場活動免費
*   [STUN](https://en.wikipedia.org/wiki/STUN) — 使用者資料封包協定 \[UDP\] 透過網路位址轉換器 \[NAT\] 的會話遍歷
    *   Google STUN — [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302)
    *   Twilio STUN — [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp)
*   [Tailscale](https://tailscale.com/) — 零設定 VPN，使用開源 WireGuard 協定。安裝在 MacOS、iOS、Windows、Linux 和 Android 裝置上。適合 100 台裝置和 3 位使用者的個人使用的免費方案。
*   [webhookrelay.com](https://webhookrelay.com) — 管理、偵錯、扇出並將所有 Webhook 代理到公用或內部（即：本機）目的地。此外，透過取得公共 HTTP 端點 ( )，透過隧道公開在專用網路中執行的伺服器`https://yoursubdomain.webrelay.io <----> http://localhost:8080`。
*   [Hookdeck](https://hookdeck.com/pricing) — 從一個地方開發、測試和監控您的 webhooks。每月 10 萬次請求和 10 萬次嘗試，保留 3 天。
*   [Xirsys](https://www.xirsys.com/pricing/) — 無限 STUN 使用 + 每月 500 MB TURN 頻寬、頻寬上限、單一地理區域。
*   [ZeroTier](https://www.zerotier.com) — FOSS 管理的虛擬乙太網路即服務。免費方案中 25 個客戶端的無限端對端加密網路。桌面/行動/北美客戶端；用於設定自訂路由規則和批准專用網路上的新客戶端節點的 Web 介面
*   [LocalXpose](https://localxpose.io) - 反向代理，使您能夠將本地主機伺服器公開到網際網路。免費方案的隧道壽命為 15 分鐘。
*   [Traefik-Hub](https://traefik.io/traefik-hub/) - 透過隧道將本地運行的服務發佈到公共自訂 URL，並透過存取控制保護它們。一個集群中的 5 個服務免費。
*   [公開](https://expose.dev/)\- 透過安全隧道公開本地站點。免費方案包括 EU 伺服器、隨機子網域和單一使用者。
*   [計量](https://www.metered.ca/)— 免費 TURN 伺服器，包含 50GB 每月 TURN 使用量。

**[⬆️回到頂部](#table-of-contents)**

問題追蹤與專案管理
---------

*   [acunote.com](https://www.acunote.com/) — 最多可供 5 名團隊成員使用的免費專案管理和 SCRUM 軟體
*   [asana.com](https://asana.com/) — 免費與合作者合作的私人項目
*   [待辦事項清單](https://backlog.com)— 您的團隊在一個平台上發布優秀專案所需的一切。免費方案提供 1 個具有 10 個使用者和 100MB 儲存空間的項目。
*   [Basecamp](https://basecamp.com/personal) - 待辦事項清單、里程碑管理、類似論壇的訊息傳遞、文件共享和時間追蹤。最多 3 個項目、20 個使用者和 1GB 儲存空間。
*   [bitrix24.com](https://www.bitrix24.com/) — 內部網路與專案管理工具。免費方案有 5GB，可供無限用戶使用。
*   [cacoo.com](https://cacoo.com/) — 即時線上圖表：流程圖、UML、網路。自由最大。15 個使用者/圖表，25 張
*   [Chpokify](https://chpokify.com/) - 基於團隊的規劃撲克，可節省衝刺估算時間。免費最多 5 個用戶、免費 Jira 整合、無限視訊通話、無限團隊、無限會話。
*   [clickup.com](https://clickup.com/) — 專案管理。免費的高級版本，帶有雲端儲存。提供行動應用程式和 Git 集成
*   [Clockify](https://clockify.me) - 時間追蹤器和時間表應用程序，可讓您追蹤跨專案的工作時間。無限用戶，永久免費。
*   [Cloudcraft](https://cloudcraft.co/) — 使用 Cloudcraft 視覺化設計器在幾分鐘內設計出專業的架構圖，並透過可顯示即時資料的智慧元件針對 AWS 進行了最佳化。免費方案為單一用戶提供無限的私人圖表。
*   [Codegiant](https://codegiant.io) — 具有儲存庫託管和 CI/CD 的專案管理。免費方案提供無限的儲存庫、專案和文檔，由 5 名團隊成員組成。每月 500 CI/CD 分鐘。每月 30000 分鐘無伺服器程式碼運行時間。1GB 儲存庫儲存。
*   [Confluence](https://www.atlassian.com/software/confluence) - Atlassian 的內容協作工具，用於幫助團隊有效地協作和分享知識。免費方案最多 10 個用戶。
*   [contriber.com](https://www.contriber.com/) — 可自訂的專案管理平台、免費入門計畫、5 個工作區
*   [sketchs.net](https://app.diagrams.net/) — 本地儲存在 Google Drive、OneDrive 或 Dropbox 中的線上圖表。所有功能和儲存等級均免費
*   [freedcamp.com](https://freedcamp.com/) - 任務、討論、里程碑、時間追蹤、日曆、文件和密碼管理器。免費計劃，項目、使用者和文件儲存不受限制。
*   [easyretro.io](https://www.easyretro.io/) — 簡單直覺的衝刺回顧工具。免費方案有 3 個公共板，每個板每月有 1 次調查。
*   [GForge](https://gforge.com) — 專案管理和問題追蹤工具集，適用於具有自營和 SaaS 選項的複雜專案。SaaS 免費方案為前 5 位用戶免費提供開源專案。
*   [gleek.io](https://www.gleek.io) — 為開發人員提供的免費描述到圖表工具。使用關鍵字建立非正式的 UML 類別、物件或實體關係圖。
*   [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector 輸出兩個 GraphQL 模式之間的變更清單。每個變更都經過精確解釋並標記為破壞性、非破壞性或危險性。
*   [huboard.com](https://huboard.com/) — 針對 GitHub 問題的即時專案管理，免費開源
*   [Hygger](https://hygger.io) — 專案管理平台。免費方案提供無限的用戶、項目和板以及 100 MB 儲存空間。
*   [Instabug](https://instabug.com) — 適用於行動應用程式的全面錯誤報告和應用程式內回饋 SDK。免費方案最多 1 個應用程式和 1 個會員。
*   [Ilograph](https://www.ilograph.com/) — 互動式圖表，讓使用者可以從多個角度和詳細程度查看其基礎架構。圖表可以用程式碼來表達。免費套餐擁有無限的私人圖表，最多可容納 3 位觀看者。
*   [Jira](https://www.atlassian.com/software/jira) — 在許多企業環境中使用的高階軟體開發專案管理工具。免費方案最多 10 個用戶。
*   [kanbanflow.com](https://kanbanflow.com/) — 基於董事會的專案管理。免費，高級版本有更多選擇
*   [kanbantool.com](https://kanbantool.com/) — 以看板為基礎的專案管理。免費方案有 2 個板、2 個用戶，沒有附件或文件。
*   [Kitemaker.co](https://kitemaker.co) - 在產品開發過程的所有階段進行協作，並追蹤 Slack、Discord、Figma 和 Github 的工作。無限用戶，無限空間。免費方案最多 250 個工作項目。
*   [Kiter.app](https://www.kiter.app/) - 讓任何人都可以組織自己的求職並追蹤面試、機會和聯繫。強大的網頁應用程式和 Chrome 擴充功能。完全免費。
*   [Kumu.io](https://kumu.io/) — 具有動畫、裝飾、過濾器、聚類、電子表格導入等的關係圖。免費套餐允許無限的公共項目。圖形大小不受限制。為學生提供免費的私人項目。如果您不想將文件公開在線上（上傳、編輯、下載、丟棄），則可以使用沙盒模式。
*   [線性](https://linear.app/)— 具有簡化介面的問題追蹤器。會員免費，上傳檔案大小不超過 10MB，250 期（不含存檔）
*   [Lucidchart](https://www.lucidchart.com/) - 具有協作功能的線上圖表工具。免費規劃，包含 3 個可編輯文件、100 個專業範本和基本協作功能。
*   [MeisterTask](https://www.meistertask.com/) — 團隊線上任務管理。免費最多3個項目，項目成員不受限制。
*   [MeuScrum](https://www.meuscrum.com/en) - 附看板的免費線上 Scrum 工具
*   [nTask](https://www.ntaskmanager.com/) — 專案管理軟體，使您的團隊能夠協作、規劃、分析和管理日常任務​​。基本方案永久免費，100 MB 儲存空間，5 個使用者/團隊。無限的工作空間、會議、任務、時間表和問題追蹤。
*   [Ora](https://ora.pm/) - 敏捷任務管理和團隊協作。最多 3 位用戶免費，檔案大小限制為 10 MB。
*   [hubtaltracker.com](https://www.pivotaltracker.com/) — 免費用於無限的公共項目和兩個私人項目，總共有 3 個活躍用戶（讀寫）和無限的被動用戶（唯讀）。
*   [Plaky](https://plaky.com) - 免費任務管理（看板）軟體，沒有任何限制。無限用戶，無限項目，永久免費。
*   [plan.io](https://plan.io/) — 具有儲存庫託管和更多選項的專案管理。2 位使用者、10 位客戶和 500MB 儲存空間免費
*   [Plane](https://plane.so/) - Plane 是一個簡單的、可擴展的、開源的專案和產品管理工具。會員免費，上傳檔案大小不超過 5MB，1000 期。
*   [planitpoker.com](https://www.planitpoker.com/) — 免費線上規劃撲克（估算工具）
*   [point.poker](https://www.point.poker/) - 線上規劃撲克（基於共識的估計工具）。免費提供無限用戶、團隊、會議、回合和投票。無需註冊。
*   [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直覺的介面，最多可免費容納 5 個使用者。
*   [Shake](https://www.shakebugs.com/) - 適用於行動應用程式的應用程式內錯誤報告和回饋工具。免費計劃，每個應用程式每月 10 個錯誤報告。
*   [快捷方式](https://shortcut.com/)\- 專案管理平台。最多 10 位用戶永久免費。
*   [SpeedBoard](https://speedboard.app) - 敏捷和 Scrum 回顧委員會 - 免費。
*   [SuperPM](https://superpm.app/) - 多功能專案管理平台。最多可免費使用 3 個項目、無限用戶、1 GB 儲存空間。
*   [Tadum](https://tadum.app) - 專為定期會議設計的會議議程和會議記錄應用程序，免費供 10 人以下的團隊使用
*   [taiga.io](https://taiga.io/) — 新創公司和敏捷開發人員的專案管理平台，免費開源
*   [Tara AI](https://tara.ai/) — 簡單的衝刺管理服務。免費方案具有無限的任務、衝刺和工作空間，沒有用戶限制。
*   [targetprocess.com](https://www.targetprocess.com/) — 視覺化專案管理，從看板和 Scrum 到幾乎任何操作流程。免費供無限用戶使用，最多 1,000 個資料實體 {[更多詳情](https://www.targetprocess.com/pricing/)}
*   [taskade.com](https://www.taskade.com/) — 團隊的即時協作任務清單和大綱。免費方案有： 1 個包含無限任務和專案的工作區；1GB檔案儲存空間；1週的項目歷史；每場視訊會議有 5 位與會者。
*   [taskulu.com](https://taskulu.com/) — 基於角色的專案管理。釋放最多 5 個用戶。與 GitHub/Trello/Dropbox/Google Drive 集成
*   [teamwork.com](https://teamwork.com/) — 專案管理與團隊聊天。5 個用戶和 2 個項目免費。提供高級計劃。
*   [teleretro.com](https://www.teleretro.com/) — 簡單有趣的回顧工具，包含破冰遊戲、GIF 和表情符號。免費方案包括 3 次回顧和無限會員。
*   [testlio.com](https://testlio.com/) — 問題追蹤、測試管理和 Beta 測試平台。免費供私人使用
*   [terrastruct.com](https://terrastruct.com/) — 專門用於軟體架構的線上圖表製作器。每個圖表最多 4 層的免費層。
*   [todoist.com](https://todoist.com/) — 協作與個人任務管理。免費方案有：5個活躍項目，項目中有5個用戶，文件上傳最多5MB，3個過濾器，1週的活動歷史記錄。
*   [trello.com](https://trello.com/) — 基於董事會的專案管理。無限個個人看板，10 個團隊看板。
*   [Tweek](https://tweek.so/) - 簡單的每週待辦事項行事曆和任務管理。
*   [ubertesters.com](https://ubertesters.com/) — 測試平台、整合和眾測者，2 個項目，5 名成員
*   [vabotu](https://vabotu.com/) - 專案管理的協作工具。提供免費和其他方案。自由職業計畫適用於 10 位用戶，包括訊息傳遞、任務板、5GB 線上儲存、工作區、匯出資料。
*   [Wikifactory](https://wikifactory.com/) — 包含專案、VCS 和問題的產品設計服務。免費方案提供無限的專案和協作者以及 3GB 儲存空間。
*   [Yodiz](https://www.yodiz.com/) — 敏捷開發與問題追蹤。最多可免費使用 3 位用戶，物品不受限制。
*   [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — 免費託管的 YouTrack (InCloud)，適用於 FOSS 專案、私人專案（3 位使用者免費）。包括時間追蹤和敏捷板
*   [zenhub.com](https://www.zenhub.com) — GitHub 內唯一的專案管理解決方案。公共倉庫、OSS 和非營利組織免費
*   [zenkit.com](https://zenkit.com) — 專案管理與協作工具。最多 5 名會員免費，附件 5 GB。
*   [Zube](https://zube.io) — 專案管理，提供 4 個專案和 4 個使用者的免費方案。GitHub 整合可用。
*   [Toggl](https://toggl.com/) — 提供 2 個免費的生產力工具。[Toggl Track](https://toggl.com/track/)時間管理和追蹤應用程式提供免費計劃，提供專為自由工作者設計的無縫時間追蹤和報告。它擁有無限的追蹤記錄、項目、客戶、標籤、報告等。Toggl [Plan](https://toggl.com/plan/)用於任務規劃，為獨立開發人員提供免費計劃，具有無限的任務、里程碑和時間表。
*   [Sflow](https://sflow.io) — sflow.io 是一個專案管理工具，專為軟體敏捷開發、行銷、銷售和客戶支援而構建，特別適用於外包專案和跨組織協作專案。免費方案最多 3 個項目和 5 名會員。
*   [Pulse.red](https://pulse.red) — 適用於專案的免費簡約時間追蹤器和時間表應用程式。

**[⬆️回到頂部](#table-of-contents)**

儲存和媒體處理
-------

*   [AndroidFileHost](https://androidfilehost.com/) - 免費文件共享平台，速度、頻寬、文件數、下載數等均不受限制。主要針對 Android 開發相關文件，如 APK 構建、自訂 ROM 和修改等。但似乎也接受任何其他文件。
*   [borgbase.com](https://www.borgbase.com/) — 用於 Borg Backup 的簡單且安全的異地備份託管。10 GB 可用備份空間和 2 個儲存庫。
*   [Icedrive.net](https://www.icedrive.net/) - 簡單的雲端儲存服務。10 GB 免費儲存空間
*   [sync.com](https://www.sync.com/) - 端對端雲端儲存服務。5 GB 免費儲存空間
*   [pcloud.com](https://www.pcloud.com/) - 雲端儲存服務。高達 10 GB 的免費儲存空間
*   [Sirv.com](https://sirv.com/) — 智慧型影像 CDN，具有動態影像最佳化和調整大小功能。免費方案包括 500 MB 儲存空間和 2 GB 頻寬。
*   [cloudimage.io](https://www.cloudimage.io/en/home) — 全面的影像最佳化和 CDN 服務，在全球擁有 1500 多個存在點。多種影像縮放、壓縮、浮水印功能。用於響應式影像、360 度影像製作和影像編輯的開源插件。免費包月計劃，提供 25GB CDN 流量和 25GB 快取儲存以及無限轉換。
*   [cloudinary.com](https://cloudinary.com/) — 網站和應用程式的圖像上傳、強大的操作、儲存和交付，以及 Ruby、Python、Java、PHP、Objective-C 等庫。免費套餐包括 25 個每月積分。1 個積分相當於 1,000 次影像轉換、1 GB 儲存空間或 1 GB CDN 使用量。
*   [embed.ly](https://embed.ly/) — 提供用於在網頁中嵌入媒體、響應式圖像縮放、從網頁中提取元素的 API。每月最多可免費存取 5,000 個 URL，每秒 15 個請求
*   [filestack.com](https://www.filestack.com/) — 檔案選擇器、轉換和交付，免費提供 250 個檔案、500 次轉換和 3 GB 頻寬
*   [file.io](https://www.file.io) - 2 GB 的檔案儲存空間。下載 1 次後檔案將自動刪除。用於與儲存互動的 REST API。速率限制 1 個請求/分鐘。
*   [freetools.site](https://freetools.site/) — 免費線上工具。轉換或編輯文件、圖像、音訊、視訊等。
*   [GoFile.io](https://gofile.io/) - 免費檔案共用和儲存平台，可透過基於 Web 的 UI 和 API 使用。不限製檔案大小、頻寬、下載次數等。但是當檔案變為非活動狀態（超過 10 天沒有下載）時，它將被刪除。
*   [gutlet.com](https://www.gumlet.com/) — 影像調整大小即服務。它還優化圖像並透過 CDN 執行交付。免費套餐包括 1 GB 頻寬和一年內每月無限數量的圖像處理。
*   [image-charts.com](https://www.image-charts.com/) — 帶有浮水印的無限圖像圖表生成
*   [Imgbot](https://github.com/marketplace/imgbot) — Imgbot 是一個友善的機器人，可以優化您的影像並節省您的時間。優化的圖像意味著在不犧牲品質的情況下更小的檔案大小。它是免費的開源軟體。
*   [imgen](https://www.jitbit.com/imgen/) - 免費無限社交封面圖片產生 API，無浮水印
*   [kraken.io](https://kraken.io/) — 網站效能圖片優化即服務，免費方案最大檔案大小為 1 MB
*   [kvstore.io](https://www.kvstore.io/) — 鍵值儲存服務。免費套餐允許 100 個密鑰、1KB/密鑰、100 次呼叫/小時
*   [npoint.io](https://www.npoint.io/) — 具有協作模式編輯功能的 JSON 存儲
*   [nitropack.io](https://nitropack.io/) - 透過完整的前端優化（快取、圖片和程式碼優化、CDN），加快網站的自動運行速度。每月最多 5,000 次瀏覽量免費
*   [otixo.com](https://www.otixo.com/) — 從一處加密、共用、複製和移動所有雲端儲存檔案。基本計劃提供無限的文件傳輸，最大 250 MB。文件大小並允許 5 個加密文件
*   [packagecloud.io](https://packagecloud.io/) — YUM、APT、RubyGem 和 PyPI 的託管套件儲存庫。有限的免費計劃，可根據要求提供開源計劃
*   [getpantry.cloud](https://getpantry.cloud/) — 一個簡單的 JSON 資料儲存 API，非常適合個人專案、黑客馬拉松和行動應用程式！
*   [piio.co](https://piio.co/) — 為每個網站提供響應式圖像優化和交付。為開發者和個人網站提供免費方案。包括開箱即用的免費 CDN、WebP 和延遲載入。
*   [Pinata IPFS](https://pinata.cloud) — Pinata 是在 IPFS 上上傳和管理文件的最簡單方法。我們友善的使用者介面與 IPFS API 結合，使 Pinata 成為平台、創作者和收藏者最簡單的 IPFS 固定服務。1 GB 免費儲存空間以及 API 存取權。
*   [placekitten.com](https://placekitten.com/) — 一種快速而簡單的服務，用於獲取小貓的照片以用作佔位符
*   [plot.ly](https://plot.ly/) — 繪製圖表並分享您的數據。免費套餐包括無限量的公共文件和 10 個私人文件
*   [podio.com](https://podio.com/) — 您可以與最多五人的團隊一起使用 Podio，並嘗試基本計劃的功能（使用者管理除外）
*   [QuickChart](https://quickchart.io) — 產生可嵌入的圖像圖表、圖形和 QR 程式碼
*   [redbooth.com](https://redbooth.com) — P2P 檔案同步，最多 2 位使用者免費
*   [resmush.it](https://resmush.it) — reSmush.it 是一個提供圖像優化的免費 API。reSmush.it 已在最常見的 CMS 上實現，例如 Wordpress、Drupal 或 Magento。reSmush.it 是最常用的圖像優化 API，已處理超過 70 億張圖像，並且仍然免費。
*   [Shotstack](https://shotstack.io) - 用於大規模產生和編輯影片的 API。每月最多免費 20 分鐘的渲染視頻
*   [tinypng.com](https://tinypng.com/) — 用於壓縮 PNG 和 JPEG 映像並調整其大小的 API，每月免費提供 500 次壓縮
*   [transloadit.com](https://transloadit.com/) — 處理文件上傳和視訊、音訊、圖像、文件的編碼。透過 GitHub 學生開發包免費開放給開源、慈善機構和學生。商業應用程式可免費獲得 2 GB 用於測試驅動
*   [twicpics.com](https://www.twicpics.com) - 響應式圖像即服務。它提供圖像 CDN、媒體處理 API 和前端庫來自動優化圖像。該服務每月最多可免費使用 3GB 流量。
*   [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare 為媒體管道提供基於尖端演算法的終極工具包。所有功能均完全免費供開發人員使用：檔案上傳 API 和 UI、圖片 CDN 和來源服務、自適應交付和智慧壓縮。限制免費方案具有 3000 次上傳、3 GB 流量和 3 GB 儲存空間。
*   [imagekit.io](https://imagekit.io) – 具有自動最佳化、即時轉換和儲存功能的影像 CDN，您可以在幾分鐘內與現有設定整合。免費方案包括每月高達 20GB 的頻寬。
*   [internxt.com](https://internxt.com) – Internxt Drive 是一種零知識文件儲存服務，基於絕對隱私和毫不妥協的安全性。註冊並永久免費獲得 10 GB！
*   [degoo.com](https://degoo.com/) – 基於人工智慧的雲端存儲，免費高達 20 Gb，3 台設備，5 Gb 推薦獎金（90 天帳戶不活動）。

**[⬆️回到頂部](#table-of-contents)**

設計和使用者介面
--------

*   [AllTheFreeStock](https://allthefreestock.com) - 免費庫存圖片、音訊和影片的精選清單。
*   [Float UI](https://floatui.com/) - 免費的 Web 開發工具，即使對於非設計師也能輕鬆創建具有時尚設計的現代響應式網站。
*   [Ant Design Landing Page](https://landing.ant.design/) - Ant Design Landing Page 提供了由 Ant Motion 的運動組件所建構的模板。擁有豐富的首頁模板，下載模板程式碼包，即可快速使用。您也可以使用編輯器快速建立自己的專用頁面。
*   [Backlight](https://backlight.dev/) — Backlight 專注於開發人員和設計師之間的協作，是一個非常完整的編碼平台，團隊可以在其中構建、記錄、發布、擴展和維護設計系統。免費計劃允許最多3 名編輯人員在1 個設計系統上工作，且查看者數量不受限制。
*   [BoxySVG](https://boxy-svg.com/app) — 一款免費的可安裝 Web 應用程序，用於繪製 SVG 並以 svg、png、jpeg 和其他格式匯出。
*   [Circum Icons](https://circumicons.com) - React、Vue 和 Svelte 的一致開源圖示作為 SVG.
*   [clevebrush.com](https://www.cleverbrush.com/) — 免費圖形設計/照片拼貼應用程序，他們還提供付費整合作為組件。
*   [cloudconvert.com](https://cloudconvert.com/) — 將任何內容轉換為任何內容。208 種支援格式，包括影片到 gif。
*   [CodeMyUI](https://codemyui.com) - 精心挑選的網頁設計和 UI 靈感與程式碼片段的集合。
*   [ColorKit](https://colorkit.co/) - 在線上建立調色板或從頂級調色板中獲取靈感。
*   [Coolors](https://coolors.co/) - 調色板產生器。自由的。
*   [Branition](https://branition.com/colors) - 手工策劃的最適合品牌的調色板。
*   [css-gradient.com](https://www.css-gradient.com/) - 輕鬆產生自訂跨瀏覽器 CSS 漸層的免費工具。RGB 和 HEX 格式。
*   [easyvectors.com](https://easyvectors.com/) — EasyVectors.com 是優質免費 SVG 向量藝術的庫存。完全免費下載最佳向量圖。
*   [Figma.com](https://www.figma.com) — 團隊線上協作設計工具；免費套餐包括無限的文件和檢視器，最多 2 個編輯器和 3 個項目。
*   [framer.com](https://www.framer.com/) - Framer 可以幫助您迭代和動畫化您的下一個應用程式、網站或產品的介面創意 - 從強大的佈局開始。對於任何驗證 Framer 作為專業原型設計工具的人：無限的查看者、最多 2 名編輯、最多 3 個項目。
*   [freeforcommercialuse.net](https://freeforcommercialuse.net/) — FFCU 無憂模型/財產發布 庫存照片
*   [Gradientos](https://www.gradientos.app) - 讓選擇漸層變得快速又簡單。
*   [Icon Horse](https://icon.horse) – 透過我們簡單的 API 取得任何網站的最高解析度圖示。
*   [Icons8](https://icons8.com) — 圖示、插圖、照片、音樂和設計工具。免費方案提供有限的低解析度格式。當您使用我們的資源時連結到 Icons8。
*   [Invision App](https://www.invisionapp.com) - UI 設計與原型工具。提供桌面和網路應用程式。可免費與 1 個活動原型一起使用。
*   [landen.co](https://www.landen.co) — 為您的新創公司產生、編輯和發布精美的網站和登陸頁面。全部無代碼。免費套餐可讓您擁有一個完全可自訂並在網路上發布的網站。
*   [Quant Ux](https://quant-ux.com/) - Quant Ux 是一個原型設計和設計工具。\- 它是完全免費且開源的。
*   [lensdump.com](https://lensdump.com/) - 免費雲端圖像託管。
*   [Lorem Picsum](https://picsum.photos/) - 免費工具，易於使用的時尚佔位符。只需在我們的 URL 後面添加您想要的圖像尺寸（寬度和高度），您就會獲得隨機圖像。
*   [LottieFiles](https://lottiefiles.com/) - 世界上最大的線上平台，為設計師、開發人員等提供世界上最小的動畫格式。存取適用於 Android、iOS 和 Web 的 Lottie 動畫工具和外掛程式。
*   [MagicPattern](https://www.magicpattern.design/tools) — CSS 和 SVG 背景產生器以及漸層、圖案和斑點工具的集合。
*   [marvelapp.com](https://marvelapp.com/) — 設計、原型製作和協作，僅限一名用戶和一個專案的免費計劃。
*   [Mindmup.com](https://www.mindmup.com/) — 免費無限量心智圖，並將其儲存在雲端。您的心智圖可以透過任何裝置隨時隨地使用。
*   [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc 是一款功能強大的設計協作和交付工具。免費方案包括 3 個用戶和 5 個項目，提供所有可用功能。
*   [mockupmark.com](https://mockupmark.com/create/free) — 為社群媒體和電子商務創建逼真的 T 恤和服裝模型，40 個免費模型。
*   [Octopus.do](https://octopus.do) — 視覺化網站地圖產生器。即時建立您的網站結構並快速共享它以與您的團隊或客戶合作。
*   [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的開源設計工具。
*   [Penpot](https://penpot.app) - 網路為基礎的開源設計和原型製作工具。支援 SVG。完全免費。
*   [pexels.com](https://www.pexels.com/) - 商業用途的免費庫存照片。擁有免費的 API，允許您透過關鍵字搜尋照片。
*   [photopea.com](https://www.photopea.com) — 一款免費、高級的線上設計編輯器，帶有 Adob​​e Photoshop UI，支援 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch 應用程式）。
*   [pixlr.com](https://pixlr.com/) — 商業級的免費線上瀏覽器編輯器。
*   [Plasmic](https://www.plasmic.app/) - 快速、易於使用、功能強大的網頁設計工具和頁面建立器，可整合到您的程式碼庫中。建立響應式頁面或複雜元件；可選擇使用代碼擴充；並發佈到生產網站和應用程式。
*   [Pravatar](https://pravatar.cc/) - 產生隨機/佔位假頭像，該網址可以直接熱連結到您的網頁/應用程式中。
*   [Proto.io](https://www.proto.io) - 無需編碼即可建立完全互動的 UI 原型。免費試用結束後可使用免費套餐。免費套餐包括：1 個用戶、1 個項目、5 個原型、100MB 線上儲存和 proto.io 應用程式中的預覽。
*   [resizeappicon.com](https://resizeappicon.com/) — 一項用於調整應用程式圖示大小和管理應用程式圖示的簡單服務。
*   [Rive](https://rive.app) — 創建精美的動畫並將其發送到任何平台。個人永久免費。該服務是一個編輯器，它也在其伺服器上託管所有圖形。它們還為許多平台提供運行時來運行使用 Rive 製作的圖形。
*   [Storyset.com](https://storyset.com/) — 使用此工具為您的專案創建精彩的免費客製化插圖。
*   [smartmockups.com](https://smartmockups.com/) — 建立產品模型，200 個免費模型。
*   [tabler-icons.io](https://tabler-icons.io/) — 超過 1500 個免費複製和貼上 SVG 可編輯圖示。
*   [UI Avatars](https://ui-avatars.com/) - 產生帶有姓名縮寫的頭像。這些網址可以直接熱連結到您的網頁/應用程式。支援透過url配置參數。
*   [unDraw](https://undraw.co/) - 不斷更新的精美 svg 圖像集合，您可以完全免費且無需歸屬地使用。
*   [unsplash.com](https://unsplash.com/) - 用於商業和非商業目的的免費庫存照片（做任何你想做的許可）。
*   [vectr.com](https://vectr.com/) — 適用於 Web + 桌面的免費設計應用程式。
*   [walkme.com](https://www.walkme.com/) — 企業級指導與參與平台，免費規劃 3 次步行，最多 5 步/步。
*   [Webflow](https://webflow.com) - 所見即所得網站建立器，具有動畫和網站託管。2個項目免費。
*   [Updrafts.app](https://updrafts.app) - 用於基於 tailwindcss 設計的所見即所得網站建立器。免費用於非商業用途。
*   [Whimsical.com](https://whimsical.com/) - 協作流程圖、線框圖、便條紙和心智圖。創建最多 4 個空閒板。
*   [Zeplin](https://zeplin.io/) — 設計師和開發人員協作平台。顯示設計、資產和風格指南。1 個項目免費。
*   [Pixelixe](https://pixelixe.com/) — 線上創作和編輯引人入勝且獨特的圖形和圖像。
*   [Responsively App](https://responsively.app) - 一個免費的開發工具，用於更快、更精確的響應式 Web 應用程式開發。
*   [SceneLab](https://scenelab.io) - 線上模型圖形編輯器，具有不斷擴展的免費設計模板集合
*   [xLayers](https://xlayers.dev) - 預覽 Sketch 設計檔案並將其轉換為 Angular、React、Vue、LitElement、Stencil、Xamarin 等（免費開源，位於[https://github.com/xlayers/xlayers](https://github.com/xlayers/xlayers)）
*   [Grapedrop](https://grapedrop.com/) — 基於 GrapesJS 框架的響應式、功能強大、SEO 最佳化的網頁建構器。前 5 頁免費，無限的自訂網域，所有功能和簡單的用法。
*   [Mastershot](https://mastershot.app) - 完全免費的基於瀏覽器的影片編輯器。無浮水印，最高 1080p 匯出選項。
*   [Unicorn Platform](https://unicornplatform.com/) - 輕鬆建立具有託管功能的登陸頁面。1 個免費網站。
*   [react-favicon.com](https://react-favicon.com/) - 使用任何字體和圖示庫使用 React 和 JSX 為您的網站產生 Favicons。
*   [svgrepo.com](https://www.svgrepo.com/) - 使用各種向量庫探索、搜尋並找到最適合您的專案的圖示或向量。下載免費的 SVG 向量用於商業用途。
*   [haikei.app](https://www.haikei.app/) - Haikei 是一款用於產生獨特的 SVG 形狀、背景和圖案的 Web 應用程式 - 可與您的設計工具和工作流程一起使用。
*   [Canva](https://canva.com) - 用於創建視覺內容的免費線上設計工具。
*   [Superdesigner](https://superdesigner.co) - 一系列免費設計工具，只需點擊幾下即可建立獨特的背景、圖案、形狀、圖像等。
*   [TeleportHQ](https://teleporthq.io/) - 低程式碼前端設計開發平台。TeleportHQ 是一個協作前端平台，可立即建立和發布無頭靜態網站。3個免費項目，無限合作者，免費代碼匯出。
*   [vector.express](https://vector.express) — 快速輕鬆地轉換您的 AI、CDR、DWG、DXF、EPS、HPGL、PDF、PLT、PS 和 SVG 向量。
*   [Vertopal](https://www.vertopal.com) - Vertopal 是一個免費的線上平台，用於將文件轉換為各種文件格式。包括 JPG 到 SVG、GIF 到 APNG、PNG 到 WEBP、JSON 到 XML 等開發人員轉換器。
*   [okso.app](https://okso.app) - 簡約的線上繪圖應用程式。允許創建快速草圖和視覺筆記。將草圖匯出為 PNG、JPG、SVG 和 WEBP。也可以作為 PWA 安裝。所有人免費使用（無需註冊）。
*   [Wdrfree SVG](https://wdrfree.com/free-svg) - 黑白免費 SVG 剪切檔。
*   [Lucide](https://lucide.dev) - 免費可自訂且一致的 SVG 圖標工具包。
*   [MDBootstrap](https://mdbootstrap.com/) - 免費供個人和商業使用 Bootstrap、Angular、React 和 Vue UI 套件，包含 700 多個組件、令人驚嘆的模板、1 分鐘安裝、廣泛的教程和龐大的社區。
*   [Tailwind Elements](https://tailwind-elements.com/) - 使用 Tailwind CSS 重新創建的免費 Bootstrap 元件，但具有更好的設計和更多功能。
*   [DaisyUI－](https://daisyui.com/)免費。「使用 Tailwind CSS 但編寫更少的類別名稱」提供了按鈕等元件。
*   [Scrollbar.app——](https://scrollbar.app)簡單的免費網頁應用程序，用於設計網路的自訂捲軸。
*   [css.glass－](https://css.glass/)使用 CSS 創建玻璃形態設計的免費網頁應用程式。
*   [hypercolor.dev](https://hypercolor.dev/) ——Tailwind CSS 顏色漸層的精選集合，還提供各種生成器來創建您自己的。
*   [iconify.design](https://icon-sets.iconify.design/)－100多個圖示套件的集合，具有統一的介面。允許您跨包搜尋圖示並將單個圖示匯出為 SVG 或流行的 Web 框架。
*   [NextUI－](https://nextui.org/)免費。漂亮、快速、現代的 React 和 Next.js UI 函式庫。
*   [Glyphs－](https://glyphs.fyi/)免費、網路上最強大的圖示、完全可編輯且真正的開源設計系統。
*   [ShadcnUI——](https://ui.shadcn.com/)設計精美的元件，您可以將其複製並貼上到您的應用程式中。無障礙。可客製化。開源。
*   [HyperUI－](https://www.hyperui.dev/)免費開源 Tailwind CSS 元件。

**[⬆️回到頂部](#table-of-contents)**

設計靈感
----

*   [謝謝。](https://www.awwwards.com/)\- \[熱門網站\] 展示所有設計最佳的網站（由設計師投票選出）。
*   [Behance](https://www.behance.net/) - \[設計展示\] 設計師展示作品的地方。可依 UI/UX 項目的類別進行篩選。
*   [dribbble](https://dribbble.com/) - \[設計展示\] 獨特的設計靈感，一般不是來自真實的應用。
*   [登陸](https://landings.dev/)\- \[網頁截圖\] 根據您的喜好找到最適合您設計靈感的登陸頁面。
*   [LovelyLanding.net](https://www.lovelylanding.net/) - \[登陸頁面設計\] 經常更新的登陸頁面截圖。包括桌面、平板電腦和行動裝置的螢幕截圖。
*   [Mobbin](https://mobbin.design/) - \[行動螢幕截圖\] 使用我們包含 50,000 多個完全可搜尋的行動應用程式螢幕截圖的程式庫，節省 UI 和 UX 研究時間。
*   [Mobile Patterns](https://www.mobile-patterns.com/) - \[手機螢幕截圖\] 一個設計靈感庫，提供最佳的 UI UX 模式（iOS 和 Android），供設計師、開發人員和產品製造商參考。
*   [Screenlane](https://screenlane.com/) - \[手機螢幕截圖\] 獲取靈感並跟上最新的網頁和行動應用程式 UI 設計趨勢。可按模式和應用程式過濾。
*   [scrnshts](https://scrnshts.club/) - \[手機螢幕截圖\] 精選的最佳應用程式商店設計螢幕截圖集合。
*   [UI Garage](https://uigarage.net/) - \[行動和網頁截圖\] 每日 UI 靈感和模式，供設計師、開發人員為您的專案尋找靈感、工具和最佳資源。
*   [Refero](https://refero.design/) - \[Web 螢幕截圖\] 來自優秀 Web 應用程式的已標記且可搜尋的設計參考集合。

**[⬆️回到頂部](#table-of-contents)**

地圖上的數據視覺化
---------

*   [IP 地理定位](https://ipgeolocation.io/)— 免費開發者計畫每月可處理 30K 請求。
*   [carto.com](https://carto.com/) — 根據您的資料和公共資料建立地圖和地理空間 API。
*   [Clockwork Micro](https://clockworkmicro.com/) — 像發條一樣運作的地圖工具。每月 50,000 次免費查詢（地圖圖塊、db2vector、海拔）。
*   [Developers.arcgis.com](https://developers.arcgis.com) — 用於跨 Web、桌面和行動裝置的地圖、地理空間資料儲存、分析、地理編碼、路由等的 API 和 SDK。2,000,000 個免費底圖圖塊、20,000 個非儲存地理編碼、20,000 條簡單路線、5,000 次行駛時間計算、每月 5GB 免費圖塊+資料儲存。
*   [Foursquare](https://developer.foursquare.com/) - 來自 Places API 和 Pilgrim SDK 的位置發現、地點搜尋和上下文感知內容。
*   [geoapify.com](https://www.geoapify.com/) - 向量和柵格地圖圖塊、地理編碼、地點、路線、等值線 API。每天 3000 個免費請求。
*   [geocod.io](https://www.geocod.io/) — 透過 API 或 CSV 上傳進行地理編碼。每天 2,500 次免費查詢。
*   [geocodify.com](https://geocodify.com/) — 透過 API 或 CSV 上傳進行地理編碼和地理解析。每月 10,000 次免費查詢。
*   [geojs.io](https://www.geojs.io/) - 高度可用的 REST/JSON/JSONP IP 地理位置尋找 API。
*   [giscloud.com](https://www.giscloud.com/) — 線上視覺化、分析和分享地理資料。
*   [graphhopper.com](https://www.graphhopper.com/)為開發人員提供了用於路由、路由最佳化、距離矩陣、地理編碼、地圖匹配的免費軟體包。
*   [這裡](https://developer.here.com/)\- 用於地圖和位置感知應用程式的 API 和 SDK。每月 25 萬筆交易免費。
*   [locationiq.com](https://locationiq.com/) — 地理編碼、地圖和路由 API。每天 5000 個請求免費。
*   [mapbox.com](https://www.mapbox.com/) — 地圖、地理空間服務和用於顯示地圖資料的 SDK。
*   [maptiler.com](https://www.maptiler.com/cloud/) — 用於地圖視覺化的向量地圖、地圖服務和 SDK。免費向量圖塊，每週更新和四種地圖樣式。
*   [nextbillion.ai](https://nextbillion.ai/) - 地圖相關服務：地理編碼、導航（方向、路線、路線優化、距離矩陣）、地圖 SDK（向量、靜態、移動 SDK）。每項服務均[免費且有指定配額。](https://nextbillion.ai/pricing)
*   [opencagedata.com](https://opencagedata.com) — 聚合 OpenStreetMap 和其他開放地理資源的地理編碼 API。每天 2,500 次免費查詢。
*   [osmnames](https://osmnames.org/) — 地理編碼，搜尋結果依相關維基百科頁面的受歡迎程度排名。
*   [positionstack](https://positionstack.com/) - 全球地點和座標的免費地理編碼。每月 25.000 個請求供個人使用。
*   [stadiamaps.com](https://stadiamaps.com/) — 地圖圖塊、路線、導航和其他地理空間 API。每天 2,500 次免費地圖視圖和 API 請求，用於非商業使用和測試。
*   [maps.stamen.com](http://maps.stamen.com/) - 免費地圖圖塊和圖塊託管。
*   [ipstack](https://ipstack.com/) - 透過 IP 位址定位和識別網站訪客
*   [Geokeo api](https://geokeo.com) - 具有語言校正等功能的地理編碼 api。全球覆蓋。每日 2,500 次免費查詢

**[⬆️回到頂部](#table-of-contents)**

封裝建置系統
------

*   [build.opensuse.org](https://build.opensuse.org/) — 多個發行版（SUSE、EL、Fedora、Debian 等）的軟體包建置服務。
*   [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — 用於 Fedora 和 EL 的基於模擬的 RPM 構建服務。
*   [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 建置服務。

**[⬆️回到頂部](#table-of-contents)**

IDE 和程式碼編輯
----------

*   [3v4l](https://3v4l.org/) - 免費線上 PHP shell 和程式碼片段共享網站，在 300 多個 PHP 版本中運行您的程式碼
*   [Android Studio](https://d.android.com/studio) — Android Studio 提供了在各種類型的 Android 裝置上建置應用程式的最快工具。開源 IDE，對所有人免費，是開發 Android 應用程式的最佳選擇。適用於 Windows、Mac、Linux 甚至 ChromeOS！
*   [Apache Netbeans](https://netbeans.apache.org/) — 開發環境、工具平台和應用程式框架。
*   [apiary.io](https://apiary.io/) — 協作設計 API，具有即時 API 模擬和產生的文件（免費提供無限的 API 藍圖和無限的用戶，只需一個管理員帳戶和託管文件）。
*   [Binder](https://mybinder.org/) - 將 Git 儲存庫轉變為互動筆記本的集合。這是一項免費的公共服務。
*   [BlueJ](https://bluej.org) — 專為初學者設計的免費 Java 開發環境，全球有數百萬人使用。由 Oracle 和簡單的 GUI 提供支持，可以幫助初學者。
*   [Bootify.io](https://bootify.io/) - 具有自訂資料庫和 REST API 的 Spring Boot 應用程式產生器。
*   [cacher.io](https://www.cacher.io) — 帶有標籤的程式碼片段管理器，支援 100 多種程式語言。
*   [Code::Blocks](https://codeblocks.org) — 免費的 Fortran 和 C/C++ IDE。開源並可在 Windows、macOS 和 Linux 上運作。
*   [codiga.io](https://codiga.io/) — 編碼助手，可讓您直接在 IDE 中搜尋、定義和重複使用程式碼片段。對個人和小型組織免費。
*   [codesnip.com.br](https://codesnip.com.br) — 帶有類別、搜尋和標籤的簡單程式碼片段管理器。免費且無限制。
*   [cocalc.com](https://cocalc.com/) —（以前稱為 cloud.sagemath.com 的 SageMathCloud） — 雲端中的協作運算。透過瀏覽器存取完整的 Ubuntu，內建協作和大量預先安裝的數學、科學、資料科學免費軟體：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等。
*   [code.cs50.io](https://code.cs50.io/) - Visual Studio Code for CS50 是 code.cs50.io 上的 Web 應用程序，它為學生和教師調整了 GitHub Codespaces。
*   [codepen.io](https://codepen.io/) — CodePen 是網路前端的遊樂場。
*   [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preact 等的線上遊樂場。
*   [Components.studio](https://webcomponents.dev/) - 獨立編寫元件程式碼，在故事中視覺化它們，測試它們並將它們發佈到 npm 上。
*   [Eclipse Che](https://www.eclipse.org/che/) - 開發團隊為基礎的基於 Web 的 Kubernetes 原生 IDE，具有多語言支援。開源和社群驅動。[可以在workspaces.openshift.com](https://workspaces.openshift.com/)上找到由Red Hat 託管的線上實例。
*   [fakejson.com](https://fakejson.com/) — FakeJSON 可以幫助您使用其 API 快速產生假資料。發出 API 請求，描述您想要什麼以及如何獲得它。API 以 JSON 形式傳回所有內容。加快創意進入市場的過程，並假裝它直到你成功。
*   [GitPod](https://www.gitpod.io) — GitHub 專案的即時、可立即編碼的開發環境。免費套餐包括每月 50 小時。
*   [ide.goorm.io](https://ide.goorm.io) goormIDE 是雲端的完整 IDE。多語言支援、基於 Linux 的容器（透過功能齊全的基於 Web 的終端）、連接埠轉送、自訂 url、即時協作和聊天、共享連結、Git/Subversion 支援。還有更多功能（免費方案包括每個容器 1GB RAM 和 10GB 儲存空間、5 個容器插槽）。
*   [JDoodle](https://www.jdoodle.com) — 適用於 60 多種程式語言的線上編譯器和編輯器，提供免費的 REST API 程式碼計劃，每天編譯最多 200 個積分。
*   [jetbrains.com](https://jetbrains.com/products.html) — 生產力工具、IDE 與部署工具（又稱[IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/)等）。學生、教師、開源和使用者群體的免費許可證。
*   [jsbin.com](https://jsbin.com) — JS Bin 是前端 Web 的另一個遊樂場和程式碼共享網站（HTML、CSS 和 JavaScript。也支援 Markdown、Jade 和 Sass）。
*   [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 Web 的遊樂場和程式碼共享網站，也支援協作。
*   [JSONPlaceholder](https://jsonplaceholder.typicode.com/)一些以 JSON 格式傳回一些虛假資料的 REST API 端點。如果您想在本地運行伺服器，也可以使用原始程式碼。
*   [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一款相容於 Delphi 的跨平台 IDE，用於快速應用程式開發。
*   [micro-jaymock](https://micro-jaymock.now.sh/) - 用於產生虛假 JSON 資料的微型 API 模擬微服務。
*   [mockable.io](https://www.mockable.io/) — Mockable 是一個簡單的可設定服務，用於模擬 RESTful API 或 SOAP Web 服務。此線上服務可讓您快速定義 REST API 或 SOAP 端點並讓它們傳回 JSON 或 XML 資料。
*   [mockaroo](https://mockaroo.com/) — Mockaroo 可讓您產生 CSV、JSON、SQL 和 Excel 格式的真實測試資料。您也可以為後端 API 建立模擬。
*   [Mocklets](https://mocklets.com) - 基於 HTTP 的模擬 API 模擬器，有助於模擬 API，以實現更快的平行開發和更全面的測試，並具有終身免費套餐。
*   [Paiza](https://paiza.cloud/en/) — 在瀏覽器中開發 Web 應用程序，無需進行任何設定。免費方案提供 1 台具有 24 小時使用壽命和每天 4 小時運行時間的伺服器，具有 2 個 CPU 核心、2 GB RAM 和 1 GB 儲存空間。
*   [Prepros](https://prepros.io/) - Prepros 可以開箱即用地編譯Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和TypeScript，重新加載您的瀏覽器，使開發和測試您的網站變得非常容易，以便您可以專注於使它們變得完美。您也可以只需單擊幾下即可添加自己的工具。
*   [Replit](https://replit.com/) — 適用於各種程式語言的雲端編碼環境。
*   [SoloLearn](https://code.sololearn.com) — 一個非常適合運行程式碼片段的雲端編程遊樂場。支援多種程式語言。運行程式碼不需要註冊，但需要在其平台上保存程式碼時需要註冊。也為初學者和中級編碼員提供免費課程。
*   [stackblitz.com](https://stackblitz.com/) — 用於建立、編輯和部署全端應用程式的線上/雲端程式碼 IDE。支援任何流行的基於 NodeJs 的前端和後端框架。建立新專案的短連結： https: [//node.new](https://node.new)。
*   [Visual Studio Code](https://code.visualstudio.com/) - 程式碼編輯器重新定義和最佳化，用於建置和偵錯現代 Web 和雲端應用程式。由微軟開發。
    *   [桌面](https://code.visualstudio.com)\-（Windows、macOS 和 Linux）。
    *   [線上](https://vscode.dev)\- （瀏覽器）
*   [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — 功能齊全的IDE，具有數千個擴充功能、跨平台應用程式開發（適用於iOS 和Android 的Microsoft 擴充功能可供下載）、桌面、Web 和雲端開發、多語言支援（C#、C++、JavaScript 、Python、 PHP 等）。
*   [VSCodium](https://vscodium.com/) - 社群驅動、無遙測/追蹤、免費授權的 Microsoft 編輯器 VSCode 的二進位發行版
*   [wakatime.com](https://wakatime.com/) — 關於您的程式設計活動的量化自我指標，使用文字編輯器插件，有限的免費方案。
*   [WebComponents.dev](https://webcomponents.dev/) — 瀏覽器內 IDE，可使用 58 個可用範本單獨編碼 Web 元件，支援故事和測試。
*   [PHPSandbox](https://phpsandbox.io/) — PHP 線上開發環境。

**[⬆️回到頂部](#table-of-contents)**

分析、事件和統計
--------

*   [Dwh.dev](https://dwh.dev) - 資料雲可觀測性解決方案（雪花）。免費供個人使用。
*   [Hightouch](https://hightouch.com/) - Hightouch 是一個反向 ETL 平台，可協助您將資料倉儲中的客戶資料同步到 CRM、行銷和支援工具。免費套餐為您提供一個同步數據的目的地。
*   [Avo](https://avo.app/) — 簡化的分析發布工作流程。單一真實來源追蹤計畫、類型安全分析追蹤庫、應用程式內偵錯器、資料可觀察性，可在發布之前擷取所有資料問題。免費提供 2 位工作區成員和 1 小時資料可觀察性回顧。
*   [Branch](https://branch.io) — 移動分析平台。免費套餐為多達 10K 行動應用程式用戶提供深度連結和其他服務。
*   [Cauldron](https://cauldron.io) — 分析開源解決方案，讓使用者可以將來自多個協作平台的資訊聚合為不同類型的資料來源（Git、Github、Gitlab...）。免費套餐包括無限數量的報告。
*   [Census](https://www.getcensus.com/) — 反向 ETL 和營運分析平台。將資料倉儲中的 10 個欄位同步到 60 多個 SaaS，例如 Salesforce、Zendesk 或 Amplitude。
*   [Clicky](https://clicky.com) — 網站分析平台。免費方案 1 個具有 3000 次瀏覽次數分析的網站。
*   [Databox](https://databox.com) — 結合其他分析和 BI 平台的業務洞察和分析。免費方案提供 3 個使用者、儀表板和資料來源。11M歷史資料記錄。
*   [indicative.com](https://indicative.com/) — 客戶分析平台，用於優化客戶參與度、提高轉換率並提高保留率。每月釋放多達 2500 萬個事件，資料保留 6 個月。
*   [Panelbear.com](https://panelbear.com/) — 速度極快且私密，免費套餐包括每月 5,000 次綜合瀏覽量，無限網站
*   [Hitsteps.com](https://hitsteps.com/) — 1 個網站每月 2,000 瀏覽量
*   [amplitude.com](https://amplitude.com/) — 每月 100 萬個事件，最多 2 個應用程式
*   [GoatCounter](https://www.goatcounter.com/) — GoatCounter 是一個開源網路分析平台，可作為託管服務（免費用於非商業用途）或自託管應用程式。它的目標是提供易於使用且有意義的隱私友善網路分析，作為 Google Analytics 或 Matomo 的替代方案。免費套餐適用於非商業用途，包括無限數量的網站、6 個月的資料保留和每月 10 萬頁瀏覽量。
*   [谷歌分析](https://analytics.google.com/)—Google分析
*   [Expensify](https://www.expensify.com/) — 費用報告、免費的個人報告批准工作流程
*   [getinsights.io](https://getinsights.io) - 注重隱私、無 cookie 的分析，每月免費提供多達 5000 個事件。
*   [heap.io](https://heap.io) — 自動擷取 iOS 或 Web 應用程式中的每個使用者操作。每月最多 5,000 次訪問免費
*   [Hotjar](https://hotjar.com) — 網站分析與報告。免費方案允許每天 2000 次瀏覽量。每天 100 個快照（最大容量：300）。3張快照熱圖，可保存365天。無限的團隊成員。
*   [Keen](https://keen.io/) — 用於資料收集、分析和視覺化的自訂分析。每月 1,000 場活動免費
*   [Yandex.Metrica](https://metrica.yandex.com/) — 無限免費分析
*   [Mixpanel](https://mixpanel.com/) — 每月 10 萬名追蹤用戶、無限數據歷史記錄和席位、美國或歐盟數據駐留
*   [Moesif](https://www.moesif.com) — REST 和 GraphQL 的 API 分析。（免費最多 50 萬次 API 呼叫/月）
*   [Optimizely.com](https://www.optimizely.com) — A/B 測試解決方案、免費入門計劃、1 個網站、1 個 iOS 和 1 個 Android 應用程序
*   [Microsoft PowerBI](https://powerbi.com) — Microsoft 的業務洞察與分析。免費方案提供 100 萬個使用者許可證的有限使用。
*   [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 無限制的免費分析
*   [Row Zero](https://rowzero.io) - 速度極快、連接的電子表格。直接連接到資料資料庫、S3 和 API。即時導入、分析、繪製圖表並共享數百萬行。3 本免費（永久）的練習本。
*   [sematext.com](https://sematext.com/cloud/) — 每月最多可免費執行 50 K 次操作、保留 1 天的資料、無限的儀表板、使用者等。
*   [類似的網路](https://similarweb.com)——網路和行動應用程式的分析。免費方案為每個指標提供 5 個結果、1 個月的行動應用程式資料和 3 個月的網站資料。
*   [StatCounter](https://statcounter.com/) — 網站瀏覽者分析。免費計劃分析 500 個最近訪客。
*   [Tableau 開發人員計畫](https://www.tableau.com/developer)— 創新、創造並使 Tableau 完美地適合您的組織。免費開發者計畫為 Tableau Online 提供個人開發沙盒許可證。該版本是最新的預發布版本，因此資料開發人員可以測試這個卓越平台的每個功能。
*   [usabilityhub.com](https://usabilityhub.com/) — 在真人身上測試設計和模型，追蹤訪客。一位用戶免費，無限測試
*   [woopra.com](https://www.woopra.com/) — 免費用戶分析平台，可進行 50 萬次操作、90 天資料保留、30 多個一鍵整合。
*   [counter.dev](https://counter.dev) — 網路分析變得簡單，因此隱私友好。免費或透過捐贈支付您想要的費用。
*   [PostHog](https://posthog.com) - 完整的產品分析套件免費，每月最多可追蹤 100 萬個事件
*   [Uptrace](https://uptrace.dev) - 分散式追蹤工具，可協助開發人員找出故障並尋找效能瓶頸。有免費計劃，提供開源項目的免費個人訂閱，並且有開源版本。
*   [Microsoft Clarity](https://clarity.microsoft.com/) - Clarity 是一款免費且易於使用的工具，可捕捉真實的人們如何實際使用您的網站。
*   [Beampipe.io](https://beampipe.io) - Beampipe 是簡單、注重隱私的網路分析。免費最多 5 個網域和 10,000 每月頁面瀏覽量。
*   [Aptabase](https://aptabase.com) — 適用於行動和桌面應用程式的開源、隱私友好且簡單的分析。適用於 Swift、Kotlin、React Native、Flutter、Electron 等的 SDK。每月最多可免費舉辦 20,000 場活動。

**[⬆️回到頂部](#table-of-contents)**

訪客會話錄音
------

*   [Visualime.com](https://www.visualime.com/) — 免費且無限制的會話錄製，無流量限制
*   [Reactflow.com](https://www.reactflow.com/) — 每個網站：每天 1,000 頁面瀏覽量、3 個熱圖、3 個小部件、免費錯誤跟踪
*   [OpenReplay.com](https://www.openreplay.com) - 使用用於錯誤重現的開發工具的開源會話重播、用於即時支援的即時會話以及產品分析套件。每月 1,000 次會話，可存取所有功能並保留 7 天。
*   [LogRocket.com](https://www.logrocket.com) - 每月 1,000 個會話，保留 30 天，錯誤跟踪，實時模式
*   [FullStory.com](https://www.fullstory.com) — 每月 1,000 個會話，資料保留 1 個月，擁有 3 個使用者席位。更多資訊[請參閱此處](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition)。
*   [hotjar.com](https://www.hotjar.com/) — 每個網站：每月 1,050 頁面瀏覽量，無限熱圖，資料儲存 3 個月，...
*   [spectlet.com](https://www.inspectlet.com/) — 1 個網站每月免費 2,500 次會話
*   [Microsoft Clarity](https://clarity.microsoft.com/) - 會話錄音完全免費，「無流量限制」、無專案限制、無取樣
*   [mouseflow.com](https://mouseflow.com/) — 1 個網站每月免費 500 次會話
*   [mousestats.com](https://www.mousestats.com/) — 1 個網站每月免費 100 次會話
*   [smartlook.com](https://www.smartlook.com/) — 適用於網路和行動應用程式的免費軟體包（1500 個會話/月）、3 個熱圖、1 個漏斗、1 個月的數據歷史記錄
*   [usersurge.com](https://www.usersurge.com/) — 個人每月 25 萬次會談。
*   [howuku.com](https://howuku.com) — 追蹤使用者互動、參與度和事件。每月最多 5,000 次訪問免費
*   [UXtweak.com](https://www.uxtweak.com/) — 記錄並觀察訪客如何使用您的網站或應用程式。小型專案免費無限時間

**[⬆️回到頂部](#table-of-contents)**

國際手機號碼驗證API和SDK
---------------

*   [Cognalys](https://cognalys.com/) — 透過比使用 SMS 閘道更創新且可靠的方法進行免費增值手機號碼驗證。每天免費 10 次嘗試和 15 次驗證
*   [numverify](https://numverify.com/) — 全球電話號碼驗證並尋找 JSON API。每月 250 個 API 請求
*   [veriphone](https://veriphone.io/) — 使用免費、快速、可靠的 JSON API 進行全球電話號碼驗證。每月 1000 個請求

**[⬆️回到頂部](#table-of-contents)**

支付和帳單集成
-------

*   [Adapty.io](https://adapty.io/) – 具有開源 SDK 的一站式解決方案，用於將行動應用程式內訂閱整合到 iOS、Android、React Native、Flutter、Unity 或 Web 應用程式。免費獲得每月高達 10,000 美元的收入。
*   [CoinMarketCap](https://coinmarketcap.com/api/) — 提供加密貨幣市場數據，包括最新的加密貨幣和法定貨幣匯率。免費套餐每月提供 10K 通話積分。
*   [CurrencyFreaks](https://currencyfreaks.com/) — 提供目前和歷史貨幣匯率。免費的開發者計劃每月有 1000 個請求。
*   [CoinGecko](https://www.coingecko.com/en/api) — 提供加密貨幣市場數據，包括最新的加密貨幣匯率和歷史數據。免費套餐需要歸屬。
*   [CurrencyApi](https://currencyapi.net/) — 實體和加密貨幣的即時匯率，以 JSON 和 XML 形式提供。免費套餐每月提供 1,250 個 API 請求。
*   [currencylayer](https://currencylayer.com/) — 為您的企業提供可靠的匯率和貨幣轉換，每月免費 1,000 個 API 請求
*   [currencystack.io](https://currencystack.io/) — 154 種貨幣的可生產即時匯率。
*   [Exchangerate-api.com](https://www.exchangerate-api.com) - 易於使用的貨幣轉換 JSON API。免費套餐，無請求限制。
*   [FraudLabsPRO](https://www.fraudlabspro.com) — 協助商家防止付款詐欺和退款。免費微型方案每月可進行 500 次查詢。
*   [MailPopin](https://mailpop.in) - 透過上下文資訊充分利用您的 Stripe 通知。
*   [Moesif API 貨幣化](https://www.moesif.com/)\- 透過基於使用情況的計費從 API 中產生收入。連接到 Stripe、Chargebee 等。免費套餐每月提供 30,000 個事件。
*   [Nami ML](https://www.namiml.com/) - 用於 iOS 和 Android 上的應用程式內購買和訂閱的完整平台，包括無程式碼付費牆、CRM 和分析。免費使用運行 IAP 業務的所有基本功能。
*   [RevenueCat](https://www.revenuecat.com/) — 用於應用程式內購買和訂閱的託管後端（iOS 和 Android）。免費提供高達 10,000 美元/月的追蹤收入。
*   [vatlayer](https://vatlayer.com/) — 即時增值稅號碼驗證和歐盟增值稅稅率 API，每月免費 100 個 API 請求
*   [Freecurrencyapi.net](https://freecurrencyapi.net/) — 免費貨幣換算和匯率資料 API。無需 API 金鑰即可每小時 10 個請求，免費註冊後每月可處理 50,000 個請求。

**[⬆️回到頂部](#table-of-contents)**

Docker相關
--------

*   [canister.io](https://canister.io/) — 20 個供開發人員使用的免費私有儲存庫，30 個供團隊建置和儲存 Docker 映像的免費私人儲存庫
*   [容器註冊服務](https://container-registry.com/)\- 基於 Harbor 的容器管理解決方案。免費方案為私有儲存庫提供 1 GB 儲存空間。
*   [Docker Hub](https://hub.docker.com) — 一個免費的私人儲存庫和無限的公共儲存庫，用於建置和儲存 Docker 映像
*   [Play with Docker](https://labs.play-with-docker.com/) — 一個學習 Docker 的簡單、互動且有趣的遊樂場。
*   [quay.io](https://quay.io/) — 使用無限的免費公共儲存庫建置和儲存容器映像
*   [Platform9](https://platform9.com/) - 託管 Kubernetes 平面。免費方案提供最多 3 個叢集和 20 個節點的管理功能。注意：您必須自行提供叢集基礎架構。

**[⬆️回到頂部](#table-of-contents)**

流浪者相關
-----

*   [Vagrant Cloud](https://app.vagrantup.com) - HashiCorp Vagrant Cloud。Vagrant 盒子託管。
*   [Vagrantbox.es](https://www.vagrantbox.es/) — 另一種公共盒子索引

**[⬆️回到頂部](#table-of-contents)**

開發部落格網站
-------

*   [BearBlog](https://bearblog.dev/) - 極簡主義和 Markdown 支援的部落格和網站建立器。
*   [Dev.to](https://dev.to/) - 程式設計師分享想法並互相幫助成長的地方。
*   [Hashnode](https://hashnode.com/) — 為開發人員提供的無憂部落格軟體！
*   [中等](https://medium.com/)— 更明智地了解對您來說重要的事情。
*   [AyeDot](https://ayedot.com/) — 以現代多媒體短格式迷你部落格的形式與世界免費分享您的想法、知識和故事。

**[⬆️回到頂部](#table-of-contents)**

評論平台
----

*   [GraphComment](https://graphcomment.com/) - GraphComment 是一個評論平台，可協助您從網站的受眾建立一個活躍的社群。
*   [Utterances](https://utteranc.es/) - 基於 GitHub 問題構建的輕量級評論小部件。使用 GitHub 問題進行部落格評論、維基頁面等！
*   [Disqus](https://disqus.com/) - Disqus 是一個網路社群平台，被網路上數十萬個網站使用。
*   [Remarkbox](https://www.remarkbox.com/) - 開源託管評論平台，為「幾個網域的一位版主完全控制行為和外觀」付費
*   [IntenseDebate](https://intensedebate.com/) - 適用於 WordPress、Tumblr、Blogger 和許多其他網站平台的功能豐富的評論系統。

**[⬆️回到頂部](#table-of-contents)**

截圖API
-----

*   [ApiFlash](https://apiflash.com) — 基於 Aws Lambda 和 Chrome 的螢幕截圖 API。處理整頁、捕捉時間、視窗尺寸…
*   [microlink.io](https://microlink.io/) – 它將任何網站轉化為數據，例如元標記標準化、美容連結預覽、抓取功能或螢幕截圖即服務。每天 250 個請求免費。
*   [ScreenshotAPI.net](https://screenshotapi.net/) - 螢幕截圖 API 使用一個簡單的 API 呼叫來產生任何網站的螢幕截圖。按比例建置並託管在 Google Cloud 上。每月提供 100 張免費螢幕截圖。
*   [Screenshotlayer.com](https://screenshotlayer.com/) — 捕捉任何網站的高度可自訂的快照。每月免費 100 張快照
*   [snapshotmachine.com](https://www.screenshotmachine.com/) — 每月捕獲 100 個快照，png、gif 和 jpg，包括完整長度的捕獲，而不僅僅是主頁
*   [PhantomJsCloud](https://PhantomJsCloud.com) — 瀏覽器自動化和頁面渲染。免費套餐每天最多提供 500 頁。自 2017 年起免費套餐。
*   [Webshrinker.com](https://webshrinker.com) — Web Shrinker 提供網站螢幕截圖和網域智慧 API 服務。每月免費 100 個請求。
*   [Httpic.com](https://httpic.com) — 將任何網站轉換為 jpg、png 或 pdf。擷取全頁螢幕截圖、調整視窗、注入自訂程式碼。免費套餐為 150 張圖像/月。
*   [螢幕截圖](https://screenshotson.click)— 您的螢幕截圖 API。具有高度可自訂的捕捉選項。每月免費 100 張螢幕截圖。

**[⬆️回到頂部](#table-of-contents)**

Flutter 相關以及在沒有 Mac 的情況下建立 IOS 應用程式
-----------------------------------

*   [FlutLab](https://flutlab.io/) - FlutLab 是一個現代 Flutter 線上 IDE，也是創建、調試和建立跨平台專案的最佳場所。使用 Flutter 建立 iOS（不含 Mac）和 Android 應用程式。
*   [CodeMagic](https://codemagic.io/) - Codemagic 是一個針對行動應用程式的完全託管和管理的 CI/CD。您可以使用基於 GUI 的 CI/CD 工具來建置、測試和部署。免費套餐提供每月 500 分鐘免費時間，以及配備 2.3Ghz 和 8GB RAM 的 Mac Mini 實例。
*   [FlutterFlow](https://flutterflow.io/) - FlutterFlow 是一個基於瀏覽器的拖放介面，用於使用 flutter 建立行動應用程式.

**[⬆️回到頂部](#table-of-contents)**

用 Javascript 編寫的基於瀏覽器的硬體模擬
--------------------------

*   [JsLinux](https://bellard.org/jslinux) — 一個非常快速的 x86 虛擬機，能夠運行 Linux 和 Windows 2k。
*   [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) — 一個 OpenRISC 虛擬機，能夠在網路支援下運行 Linux。
*   [v86](https://copy.sh/v86) — 能夠直接在瀏覽器中執行 Linux 和其他作業系統的 x86 虛擬機器。

**[⬆️回到頂部](#table-of-contents)**

隱私管理
----

*   [Bearer](https://www.bearer.sh/) - 透過稽核和連續工作流程協助實施隱私設計，以便組織遵守 GDPR 和其他法規。免費套餐僅限於較小的團隊和 SaaS 版本。
*   [Osano](https://www.osano.com/) - 同意管理和合規平台，涵蓋從 GDPR 表示到 cookie 橫幅的所有內容。免費套餐提供基本功能。
*   [Iubenda](https://www.iubenda.com/) - 隱私權和 cookie 政策以及同意管理。免費套餐提供有限的隱私權和 Cookie 政策以及 Cookie 橫幅。
*   [Cookiefirst](https://cookiefirst.com/) - Cookie 橫幅、審核和多語言同意管理解決方案。免費套餐提供一次性掃描和單一橫幅。
*   [Ketch](https://www.ketch.com/) - 同意管理和隱私框架工具。免費套餐提供大多數功能，但訪客數量有限。

**[⬆️回到頂部](#table-of-contents)**

各種各樣的
-----

*   [BinShare.net](https://binshare.net) - 建立和共用程式碼或二進位檔案。可作為美麗的圖像（例如 Twitter / Facebook 貼文）或作為連結（例如聊天或論壇）進行分享。
*   [Blynk](https://blynk.io) — 帶有 API 的 SaaS，用於控制、建置和評估 IoT 設備。包含 5 台裝置的免費開發者方案、免費雲端和資料儲存。還提供行動應用程式。
*   [Bricks Note Calculator](https://free.getbricks.app/) - 筆記應用程式 (PWA)，具有強大的內建多行計算器。
*   [Carbon.now.sh](https://carbon.now.sh) - 以美觀的類似螢幕截圖的圖像格式建立和分享程式碼片段。通常用於在 Twitter 或部落格文章上美觀地分享/炫耀程式碼片段。
*   [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中時間追蹤和編碼指標的擴展。
*   [Codepng](https://www.codepng.app) - 從原始碼創建精彩的快照，您可以在社交媒體上分享。
*   [CodeToImage](https://codetoimage.com/) - 建立程式碼或文字的螢幕截圖以在社群媒體上分享。
*   [Cronhooks](https://cronhooks.io/) - 按時間安排或重複的 webhooks。免費計劃允許 5 個臨時時間表。
*   [cron-job.org](https://cron-job.org) - 線上 cronjobs 服務。無限職位免費。
*   [datelist.io](https://datelist.io) - 線上預訂/預約安排系統。每月最多免費 5 次預訂，包括 1 份日曆
*   [docsapp.io](https://www.docsapp.io/) — 發佈文件最簡單的方法，免費開源
*   [網域轉址](https://domain-forward.com/)\- 一種轉送任何 URL 或網域的簡單工具。每月免費最多 5 個網域和 20 萬個請求。
*   [Elementor](https://elementor.com) — WordPress 網站建立器。免費方案包含 40 多個基本小部件。
*   [Form2Channel](https://form2channel.com) — 在您的網站上放置靜態 html 表單，並直接接收提交至 Google Sheets、電子郵件、Slack、Telegram 或 Http 的提交內容。無需編碼。
*   [Format Express](https://www.format-express.dev) - JSON / XML / SQL 的即時線上格式化程式。
*   [FOSSA](https://fossa.com/) - 針對第三方程式碼、許可證合規性和漏洞的可擴展的端對端管理。
*   [fullcontact.com](https://www.fullcontact.com/developer/pricing/) — 透過將社交資料添加到您的應用程式中，幫助您的用戶更了解他們的聯絡人。每月 500 次免費 Person API 匹配
*   [Hook Relay](https://www.hookrelay.dev/) - 輕鬆為您的應用程式新增 Webhook 支援：為您完成佇列、帶回退的重試和日誌記錄。免費方案每天有 100 次交付、14 天保留和 3 個掛鉤端點。
*   [http2.pro](https://http2.pro) — HTTP/2 協定就緒測試和客戶端 HTTP/2 支援檢測 API。
*   [kandi](https://kandi.openweaver.com/) — 快速啟動應用程式開發：透過程式碼片段和開源程式庫重複使用更快地建立自訂功能、用例並完成應用程式。
*   [Base64 解碼器/編碼器](https://devpal.co/base64-decode/)— 用於解碼和編碼資料的線上免費工具。
*   [newreleases.io](https://newreleases.io/) - 從 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、. NET NuGet、Rust Cargo 和 Docker Hub。
*   [OnlineExifViewer](https://onlineexifviewer.com/) — 即時在線查看照片的 EXIF 數據，包括 GPS 位置和元數據。
*   [PDFMonkey](https://www.pdfmonkey.io/) — 在儀表板中管理 PDF 模板，使用動態資料呼叫 API，下載 PDF。每月提供 300 個免費文件。
*   [Pika 程式碼螢幕截圖](https://pika.style/templates/code-image)— 使用擴充功能從程式碼片段和 VSCode 建立漂亮的、可自訂的螢幕截圖。
*   [QuickType.io](https://quicktype.io/) - 從 JSON、模式和 GraphQL 快速自動產生模型/類別/類型/介面和序列化器，以便使用任何程式語言快速、安全地處理資料。將 JSON 轉換為任何語言的華麗、類型安全的程式碼。
*   [RandomKeygen](https://randomkeygen.com/) - 一款適合行動裝置的免費工具，提供各種隨機產生的金鑰和密碼，您可以使用它們來保護任何應用程式、服務或裝置的安全。
*   [ray.so](https://ray.so/) - 創建程式碼片段的漂亮圖像。
*   [readme.com](https://readme.com/) — 精美的文件變得簡單，免費開源。
*   [redirection.io](https://redirection.io/) — 用於管理企業、行銷和 SEO 的 HTTP 重定向的 SaaS 工具。
*   [redirect.pizza](https://redirect.pizza/) - 透過 HTTPS 支援輕鬆管理重定向。免費方案包括 10 個來源和每月 100.000 次點擊。
*   [ReqBin](https://www.reqbin.com/) — 在線上發布 HTTP 請求。流行的請求方法包括 GET、POST、PUT、DELETE 和 HEAD。支援標頭和令牌身份驗證。包括用於保存您的請求的基本登入系統。
*   [智慧汽車 API](https://smartcar.com) - 用於汽車定位、取得油箱、電池電量、里程表、開/鎖車門等的 API。
*   [snappify](https://snappify.com) - 讓開發人員能夠創建令人驚嘆的視覺效果。從漂亮的程式碼片段到完善的技術演示。免費方案包括一次最多 3 個快照、無限下載和每月 5 個人工智慧驅動的程式碼解釋。
*   [日出和日落](https://sunrisesunset.io/api/)\- 取得給定經度和緯度的日出和日落時間。
*   [superfeedr.com](https://superfeedr.com/) — 符合 PubSubHubbub 標準的即時提要、匯出、分析。免費，客製化較少
*   [SurveyMonkey.com](https://www.surveymonkey.com) — 建立線上調查。線上分析結果。免費計劃每次調查僅允許 10 個問題和 100 個答案。
*   [Tiledesk](https://tiledesk.com) - 建立聊天機器人和對話應用程式。為他們帶來全通路：從您的網站（即時聊天小工具）到 WhatsApp。具有無限聊天機器人的免費方案。
*   [Versionfeeds](https://versionfeeds.com) — 用於發布您喜愛的軟體的自訂 RSS 來源。將您的程式語言、函式庫或喜愛的工具的最新版本集中在一個來源中。（前3次免費）
*   [videoinu](https://videoinu.com) — 線上建立和編輯螢幕錄影和其他影片。

**[⬆️回到頂部](#table-of-contents)**

遠端桌面工具
------

*   [Getscreen.me](https://getscreen.me) — 2 台裝置免費，會話數量和持續時間沒有限制
*   [Apache Guacamole™](https://guacamole.apache.org/) — 開源無客戶端遠端桌面網關
*   [RemSupp](https://remsupp.com) — 按需支援和永久存取設備（免費每天 2 次會議）
*   [RustDesk](https://rustdesk.com/) - 適合所有人的開源虛擬/遠端桌面基礎架構！

**[⬆️回到頂部](#table-of-contents)**

遊戲開發
----

*   [itch.io](https://itch.io/game-assets) — 免費/付費資源，如精靈、圖塊集、角色包…
*   [Gamefresco.com](https://gamefresco.com/) — 發現、收集和分享來自世界各地遊戲藝術家的免費遊戲資產。
*   [GameDevMarket](https://gamedevmarket.net) — 免費/付費資源，如 2D、3D、音訊、GUI。
*   [OpenGameArt](https://opengameart.org) — 開源遊戲資產，如音樂、聲音、精靈、GIF...
*   [CraftPix](https://craftpix.net) — 免費/付費資源，如 2D、3D、音訊、GUI、背景、圖示、圖塊集、遊戲套件。
*   [遊戲圖示](https://game-icons.net/)\- 根據 CC-BY 授權提供的免費可樣式 SVG/PNG 圖示。
*   [LoSpec](https://lospec.com/) — 用於創建像素藝術和其他限制性數位藝術的線上工具，有大量教學/托盤清單可供您的遊戲選擇
*   [ArtStation](https://www.artstation.com/) - 免費/付費 2D、3D 資源和音訊、圖標、圖塊集、遊戲套件等的 MarketPlace，此外，它還可用於展示您的藝術作品集。
*   [Rive](https://rive.app/community/) - 社區資產以及使用其免費計劃創建您自己的遊戲資產。
*   [Poly Pizza](https://poly.pizza/) - 免費低多邊形 3D 資源
*   [3Dassets.one](https://3dassets.one/) - 超過 8,000 個免費/付費 3D 模型以及用於製作紋理的 PBR 材料。
*   [3DModelsCC0](https://www.3dmodelscc0.com/) - 用於遊戲開發的公共領域 3D 模型庫。
*   [Kenney](https://www.kenney.nl/assets/) - 免費（CC0 1.0 通用許可）2D、3D、音訊和 UI 遊戲資源。
*   [Poliigon](https://www.poliigon.com/) - 免費和付費紋理（具有可變解析度）、模型、HDRI 和畫筆。提供免費插件以匯出到 Blender 等軟體。

**[⬆️回到頂部](#table-of-contents)**

其他免費資源
------

*   [Buff.tools](https://buff.tools/) - 一款一體式數位工具箱，具有 Web、SEO、AI、網域管理、單位轉換、計算器和影像處理工具。
*   [ElevateAI](https://www.elevateai.com) - 每月免費獲得最多 200 小時的音訊轉錄。
*   [get.localhost.direct](https://get.localhost.direct) — 更好的`*.localhost.direct`通配符公共 CA 簽署 SSL 證書，用於具有子網域支援的本機主機開發
*   [Framacloud — 法國非營利組織](https://degooglisons-internet.org/en/list/)[Framasoft](https://framasoft.org/en/)提供的免費/自由開源軟體和 SaaS 清單。
*   [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 提供給開發人員的免費開放原始碼軟體中心。
*   [GitHub Education](https://education.github.com/pack) — 為學生提供的免費服務集合。需要註冊。
*   [Microsoft 365 開發人員計畫](https://developer.microsoft.com/microsoft-365/dev-program)— 取得為 Microsoft 365 平台建置解決方案所需的免費沙箱、工具和其他資源。此訂閱是為期 90 天[的 Microsoft 365 E5 訂閱](https://www.microsoft.com/microsoft-365/enterprise/e5)（Windows 除外），可續訂。如果您積極參與開發（使用遙測數據和演算法進行測量），則會更新它。
*   [RedHat for Developers](https://developers.redhat.com) — 免費存取專為開發人員提供的紅帽產品，包括 RHEL、OpenShift、CodeReady 等。限個人方案。也提供免費電子書供參考。
*   [smsreceivefree.com](https://smsreceivefree.com/) — 提供免費的臨時和一次性電話號碼。
*   [sandbox.httpsms.com](https://sandbox.httpsms.com) — 免費發送和接收測試簡訊。
*   [simplebackups.io](https://simplebackups.io/) — 直接儲存到雲端儲存供應商（AWS、DigitalOcean、Backblaze...）的伺服器和資料庫（MySQL、PostgreSQL、MongoDB）的備份自動化服務。提供 1 次備份的免費方案。
*   [SnapShooter](https://snapshooter.com/) — 適用於 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的備份解決方案，支援將資料庫、檔案系統和應用程式直接備份到基於 s3 的儲存。提供免費計劃，其中包含一項資源的每日備份。
*   [主題選擇](https://themeselection.com/)— 精選高品質、現代設計、專業且易於使用的免費管理儀表板模板、  
    HTML 主題和 UI 套件，以更快地創建您的應用程式！
*   [Web.Dev](https://web.dev/measure/) — 這是一個免費工具，可讓您查看網站的表現並改善 SEO，以在搜尋引擎中獲得更高的排名。
*   [SmallDev.tools](https://smalldev.tools/) — 為開發人員提供的免費工具，可讓您編碼/解碼各種格式、縮小HTML/CSS/Javascript、美化、產生假/測試真實的JSON/CSV 和多種其他格式的資料集以及更多功能。具有令人愉快的介面。
*   [UseCSV by Layercode](https://layercode.com/usecsv) — 在幾分鐘內將 CSV 和 Excel 匯入新增至您的 Web 應用程式。為您的用戶提供愉快且強大的數據導入體驗。免費開始使用，無需任何信用卡詳細信息，立即開始整合 UseCSV。您可以建立無限個導入器並上傳最大 100Mb 的檔案。
*   [按鈕產生器](https://markodenic.com/tools/buttons-generator/)— 您可以在專案中使用 100 多個按鈕。
*   [WrapPixel](https://www.wrappixel.com/) — 下載使用 Angular、React、VueJs、NextJs 和 NuxtJs 創建的高品質免費和高級管理儀表板模板！
*   [Utils.fun](https://utils.fun/en) — 所有基於瀏覽器運算能力的離線日常和開發工具，包括浮水印生成、螢幕錄製、編解碼、加解密和程式碼格式化，都是完全免費的，不上傳任何資料到雲端進行處理。
*   [免費程式碼工具](https://freecodetools.org/)－100% 免費的有效程式碼工具。Markdown 編輯器、程式碼壓縮器/美化器、二維碼產生器、開放圖譜產生器、Twitter 卡產生器等。
*   [regex101](https://regex101.com/) — 免費此網站可讓您測試和偵錯正規表示式 (regex)。它提供了正規表示式編輯器和測試器，以及用於學習正規表示式的有用文件和資源。
*   [Kody Tools](https://www.kodytools.com/dev-tools) — 100 多個開發工具，包括格式化程式、壓縮器和轉換器。
*   [AdminMart](https://adminmart.com/) — 使用 Angular、Bootstrap、React、VueJs、NextJs 和 NuxtJs 創建的高品質免費和高級管理儀表板和網站模板！
*   [Glob tester](https://globster.xyz/) — 一個讓您設計和測試 glob 模式的網站。它也提供了學習全域模式的資源。
*   [OpenUtils](https://openutils.org/) - 為開發人員提供了各種免費工具，例如 HTML/CSS/JavaScript 格式化程式、壓縮器、轉換器、編碼器/解碼器等等。

