# Awesome Cloudflare [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [<img src="media/cf-logo.svg" width=" 250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> 很棒的 [Cloudflare](https://www.cloudflare.com) 工作人員食譜、開源項目、指南、博客和其他資源的精選列表。

Cloudflare 提供內容交付網絡 (CDN) 服務、DDoS 緩解、互聯網安全和分佈式域名服務器 (DNS) 服務，位於訪問者和 Cloudflare 用戶的託管服務提供商之間，充當網站的反向代理。

＃＃ 內容

- [社區](#community)
- [博客](#blog)
- [DNS](#dns)
- [開發者](#developers)
- [應用程序](#apps)
  - [開源](#open-source)
- [工人](#workers)
  - [參考](#reference)
  - [工具](#tools)
  - [食譜](#recipes)
- [其他](#other)

＃＃ 社區

- [論壇](https://community.cloudflare.com)
- [Reddit](https://www.reddit.com/r/CloudFlare)
- [推特上的`@Cloudflare`](https://twitter.com/cloudflare)
- [臉書](https://www.facebook.com/Cloudflare)
- [YouTube](https://www.youtube.com/cloudflare-)
- [GitHub](https://github.com/cloudflare)
- [GitHub 主題](https://github.com/topics/cloudflare)
- [堆棧交換](https://stackexchange.com/search?q=cloudflare)
- [堆棧溢出]（https://stackoverflow.com/questions/tagged/cloudflare）
- [服務器故障](https://serverfault.com/questions/tagged/cloudflare)

＃＃ 博客

- [官方博客](https://blog.cloudflare.com)

## 域名解析

- [DNS 區域文件](https://github.com/irazasyed/dns-zone-files) - 準備導入通用配置區域文件，方便配置各種服務。
- [Lexicon](https://github.com/AnalogJ/lexicon) - 以標準化方式操作各種 DNS 提供商上的 DNS 記錄的 CLI 工具。
- [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector) - 用於信息收集的多合一 CLI 工具。
- [合作夥伴面板](https://github.com/ZE3kr/Cloudflare-CNAME-Setup) - 託管合作夥伴為客戶提供DNS管理面板的工具。
- [CFPMP](https://github.com/Netrvin/CFPMP) - 合作夥伴管理面板。
- [Flares](https://github.com/lfaoro/flares) - DNS 備份工具。
- [Block Bad Bot Ruleset](https://github.com/SukkaW/cloudflare-block-bad-bot-ruleset) - 收集規則集以通過防火牆規則阻止惡意爬蟲。
- [Docker DDNS](https://github.com/oznu/docker-cloudflare-ddns) - 使用免費 DNS 服務作為動態 DNS 提供者的 Docker 鏡像。
- [Synology 的 DDNS 腳本](https://github.com/joshuaavalon/SynologyCloudflareDDNS) - Synology NAS 的 DDNS 腳本。
- [動態 DNS Bash](https://github.com/yulewang/cloudflare-api-v4-ddns) - bash 腳本中的動態 DNS 更新程序。
- [動態 DNS PHP](https://github.com/lyoshenka/cloudflare-ddns) - PHP 中的動態 DNS 更新程序。
- [動態 DNS Python](https://github.com/adrienbrignon/cloudflare-ddns) - python 中的動態 DNS 更新程序。
- [多供應商 DDNS 腳本](https://github.com/phuslu/ddns) - 多供應商 ddns 腳本，無依賴關係。
- [Argo Tunnel 客戶端](https://github.com/cloudflare/cloudflared) - Argo 隧道的 CLI 客戶端，這是一個通過 Cloudflare 網絡代理任何本地 Web 服務器的隧道守護程序。
- [Upper](https://github.com/ostark/upper) - 在您的網絡服務器前使用緩存代理顯著加快工藝速度。
- [Cloud Buster](https://github.com/SageHack/cloud-buster) - 一個全面的滲透測試工具，用於檢查網站的源 IP 洩漏。
- [CLI 工具](https://github.com/danielpigott/cloudflare-cli) - 用於與 Cloudflare 交互的 CLI 工具。
- [檢測器](https://github.com/k4m4/cloudflare-detect) - 檢測站點是否在 Cloudflare 後面運行。
- [Scrape](https://github.com/Anorov/cloudflare-scrape) - 繞過反機器人頁面的 Python 模塊。
- [CloudFlair](https://github.com/christophetd/CloudFlair) - 用於查找受 CloudFlare 保護的公開網站的源服務器的工具。

## 開發人員

- [開發者中心](https://developers.cloudflare.com) - 開發者文檔，包括所有產品的 API 參考、文章和示例代碼。
- [開源](https://cloudflare.github.io) - 官方開源項目。
- [API 文檔](https://api.cloudflare.com) - API 文檔。
- [集成資源](https://www.cloudflare.com/integrations) - 用於內容管理系統、控制面板、雲提供商、電子商務平台等的插件。
- [技術資源](https://www.cloudflare.com/technical-resources) - 技術工具和資源。
- [Serverlist 時事通訊](https://blog.cloudflare.com/serverlist) - serverlist 是 Cloudflare 策劃的有關所有無服務器事物的時事通訊。

＃＃ 應用

> [Cloudflare Apps](https://www.cloudflare.com/apps/developers) 可讓您將工具或服務發送到數百萬個站點。任何 Cloudflare 客戶都可以在幾秒鐘內在他們的網站上預覽和安裝您的代碼。

- [應用目錄](https://www.cloudflare.com/apps)
- [文檔](https://www.cloudflare.com/apps/developer/docs/getting-started)
- [開發者基金](https://www.cloudflare.com/fund)
- [應用創意](https://github.com/cloudflare-apps/ideas)

### 開源

- [官方 OSS 應用](https://github.com/cloudflare-apps) - 官方應用集合。
- [Logflare](https://github.com/Logflare/cloudflare-app) - 日誌管理和事件分析。

＃＃ 工人

> [Cloudflare Workers](https://www.cloudflare.com/products/cloudflare-workers) 提供無服務器執行環境，允許您創建全新的應用程序或擴充現有應用程序，而無需配置或維護基礎架構。

＃＃＃ 參考

- [文檔](https://workers.cloudflare.com/docs)
- [教程](https://workers.cloudflare.com/docs/tutorials)
- [運行時](https://workers.cloudflare.com/docs/reference/runtime)
- [工人 KV](https://workers.cloudflare.com/docs/reference/storage)

＃＃＃ 工具

- [Wrangler](https://github.com/cloudflare/wrangler) - `wrangler` 是一個 CLI 工具，專為有興趣使用 Cloudflare worker 的人們設計。
- [Playground](https://www.cloudflareworkers.com) - 直接在瀏覽器中針對任何站點預覽和測試代碼的簡單、即時方式。
- [無服務器插件](https://workers.cloudflare.com/docs/reference/tooling/serverless) - 用於 [無服務器框架](https://github.com/serverless/serverless) 的插件，用於開發和部署無服務器應用程序使用工人。
- [Worker App Kit](https://github.com/postlight/cloudflare-worker-app-kit) - 一套方便的工具，用於創建、開發、測試和部署工作應用程序。
- [GitHub Action](https://github.com/cpilsworth/cloudflare-worker-action) - 在推送到主分支時部署工作人員。
- [Workers KV Viewer](https://github.com/jroyal/cloudflare-workers-kv-viewer) - 用於workers KV 存儲的基於CLI 的交互式查看器。
- [重定向管理](https://forwarding.app) - 生成重定向工作者。

### 食譜

- [示例集合](https://github.com/cloudflare/worker-examples) - 食譜集合。
- [Hello World JS Boilerplate](https://github.com/cloudflare/worker-template) - 用於在 JS 中啟動工作項目的模板。
- [Hello World Rust Boilerplate](https://github.com/cloudflare/rustwasm-worker-template) - 使用 wasm-pack 啟動工作項目的模板。
- [路由器](https://github.com/cloudflare/worker-template-router) - 可與 REST API 或應用程序一起用於基本路由邏輯的路由器。
- [靜態](https://github.com/cloudflare/worker-template-static) - 從工作腳本中的原始字符串生成靜態 HTML 或 JSON 頁面。
- [Fetch](https://github.com/cloudflare/worker-template-fetch) - 發出 fetch 請求和生成 JSON post 請求的示例。
- [傳入請求](https://github.com/ashleygwilliams/worker-template-requests) - 讀取 JSON 和表單數據類型的 POST 請求正文的示例。
- [重定向](https://github.com/cloudflare/worker-template-redirect) - 從 Worker 腳本發送單個和批量重定向的示例。
- [Img-Color](https://github.com/xtuc/img-color-worker) - 檢索 png 或 jpeg 圖像的主色。
- [Binast](https://github.com/xtuc/binast-cf-worker-template) - 通過工作人員服務 binast。
- [Pwnage 保護](https://github.com/detroitenglish/pw-pwnage-cfworker) - 安全密碼評分和用戶 pwnage 保護 api - [使用](https://community.cloudflare.com/t/estimate-用戶強度-新密碼-輸入-with-zxcvbn-and-query-haveibeenpwned-for-matches-against-known-hacked-accounts/26378）。
- [緩存清除代理](https://gist.github.com/vdbelt/20f116236d2ebffa92f131e679c0551a) - 代理清除緩存請求 - [用法](https://community.cloudflare.com/t/worker-recipe-cache-purge -代理/29978）。
- [URL 路由器](https://github.com/berstend/service-worker-router) - 快速 url 路由器 - [用法](https://community.cloudflare.com/t/open-source-fast-url -router-for-workers-js-typescript/33406）。
- [邊緣代理](https://github.com/DigitalOptimizationGroup/cloudflare-edge-proxy) - 啟用 A/B 測試、金絲雀發布、把關和 SEO A/B/N 測試。
- [藍/綠部署](https://github.com/DigitalOptimizationGroup/blue-green-cloudflare-workers) - 帶有金絲雀發布的藍/綠部署的工作示例。
- [Preact PWA](https://github.com/DigitalOptimizationGroup/cloudflare-worker-preact-pwa) - Preact 漸進式 Web 應用程序。
- [CURL 攔截器](https://github.com/Gaafar/curl-worker) - 攔截來自 `curl` 命令的請求並返回不同的內容。
- [內置路由器的工作器](https://github.com/anderly/cloudflare-worker-routing) - 允許您將工作器邏輯分離為不同的功能和/或控制器。
- [連接到 Google 存儲](https://community.cloudflare.com/t/connecting-to-google-storage/32350) - 從 Google 的雲存儲中提取文件。
- [CSRF 保護](https://gist.github.com/simonerni/3501b8de6320ac37398d08d9d2d08561) - 通過驗證源/引薦標頭保護任何源不受 CSRF 的影響。
- [URL 查詢字符串解析器](https://community.cloudflare.com/t/parse-url-query-strings-with-cloudflare-workers/90286) - 解析 url 查詢字符串。
- [正則表達式替換和注入](https://community.cloudflare.com/t/perform-regex-replacements-and-inject-css-javascript-with-cloudflare-workers/90279) - 執行正則表達式替換和注入 CSS/ JS。
- [Webpack Boilerplate](https://github.com/detroitenglish/cloudflare-workers-webpack-boilerplate) - 使用 webpack 構建、捆綁和部署工作人員的樣板。
- [基本身份驗證](https://github.com/dommel/cloudflare-workers-basic-auth) - 使用基本身份驗證進行保護。
- [將日誌發送到 Logdna](https://github.com/boynet/cf-logdna-worker) - 將日誌發送到 logdna 的簡單方法。
- [IP 查找服務](https://github.com/matthewgall/beta.ipinfo.in) - 使用工作者的 IP 查找服務。
- [Airtable 代理](https://github.com/portable-cto/airtable-proxy-worker) - 允許您從前端向 Airtable API 發出安全請求。
- [TypeScript Workers](https://github.com/udacity/cloudflare-typescript-workers) - 用於構建經過測試的 typescript worker 的類型和模擬。
- [代理](https://github.com/GitbookIO/proxies-on-cloudflare) - 通過提供滿足常見需求的高級代理原語，可以輕鬆構建工人。
- [Static Worker](https://github.com/manatarms/static-worker) - 提供可以輕鬆託管靜態網站的功能。
- [Bannero](https://github.com/nondanee/bannero) - 用於 simpledesktops 的 Bannero 圖像 API。
- [Hasura](https://github.com/nathanwaters/hasura-cloudflare-worker) - 使用基於 Facebook 的授權和帶有 hasura 的 graphql 代理查詢的示例。
- [IP 重定向](https://community.cloudflare.com/t/ip-redirects/18285) - 根據用戶的 IP 地址重定向用戶。
- [將圖像切換到 WebP](https://github.com/vidaxl-com/cloudflare_webworkers/blob/master/examples/webp.js) - 支持時將圖像重新路由到 webp。
- [地理路由和負載均衡器](https://community.cloudflare.com/t/geographic-routing-and-load-balancing-with-cloudflare-workers/21900) - 地理路由和工作負載均衡。
- [UTM 標籤剝離器](https://community.cloudflare.com/t/strip-utm-query-string/47941) - 在查詢字符串中剝離 UTM 標籤。
- [短 URL 重定向器](https://community.cloudflare.com/t/short-url-using-workers/39877) - 重定向短鏈接。
- [Repo Hunt](https://github.com/signalnerve/repo-hunt) - 每天尋找酷炫的開源項目。
- [Performance Optimized Workers](https://github.com/pmenan/cf-workers) - worker 腳本的集合，通常專注於性能優化。
- [Google reCAPTCHA 驗證](https://github.com/HR/recaptcha-worker) - 處理您的 reCAPTCHA 表單的服務器端驗證。

＃＃ 其他

- [支持](https://support.cloudflare.com)
- [系統狀態](https://www.cloudflarestatus.com)
- [網絡地圖](https://www.cloudflare.com/network)

＃＃ 貢獻

歡迎投稿！首先閱讀 [貢獻指南](contributing.md)。

＃＃ 執照

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

在法律允許的範圍內，[Irfaq Syed](https://github.com/irazasyed) 已放棄所有版權和
本作品的相關或鄰接權。

> Cloudflare 是 Cloudflare, Inc. 的註冊商標。