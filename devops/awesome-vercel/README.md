[](#awesome-vercel-previously-zeit-)Awesome Vercel（以前是 ZEIT）
==================================================== ====================

[![真棒](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

在開源領域，圍繞 [Vercel](https://vercel.com) 發生了很多事情。為了讓開發人員更容易獲得這些資源，我決定為他們創建一個列表。我們在這裡！

* [助手](#helpers)
* [庫](#libraries)
* [服務](#services)
* [部署示例](#deployment-examples)
* [樣板](#boilerplates)
* [API 客戶端](#api-clients)
* [Vercel 展示](#Vercel-展示)
* [相關列表](#related-lists)
* [社區](#communities)

### [](#helpers)助手

* [now-logs](https://logs.now.sh) - [📖](https://github.com/berzniz/now-logs) - Vercel 的實時日誌記錄
* [now-no-alias](https://github.com/remy/now-no-alias) - Vercel 列出空閒部署的 CLI 工具（沒有活動別名）。
* [now-pipeline](https://github.com/bahmutov/now-pipeline) - 部署、運行 e2e 測試並在測試通過時切換別名的單個命令。
* [now-redirect](https://github.com/vdanchenkov/now-redirect) - 輕鬆部署重定向，如 `www.domain.com` 到 `domain.com`。
* [zeit-deployments](https://github.com/pranaygp/zeit-deployments) - _deprecated_ - 將一個小型 Next.js 應用程序部署到 Vercel，其中列出了所有 Vercel 部署。
* [now-env](https://github.com/sergiodxa/now-env) - _deprecated_ 在開發中使用 now.json 環境變量和機密。
* [now-ab](https://github.com/sergiodxa/now-ab) - _deprecated_ AB 使用簡單部署測試兩個或更多 Now 部署。
* [now-server](https://github.com/markmarijnissen/now-server) - 別名路徑的本地開發服務器。
* [now-token](https://github.com/shawnbot/now-token) - 從 Node 或命令行輕鬆訪問您的 Vercel API 訪問令牌。

### [](#libraries)庫

看看[awesome-micro](https://github.com/amio/awesome-micro)！😌

### [](#services)服務

* [deploy.now.sh](https://deploy.now.sh) - 單擊按鈕將 git repos 部署到 Vercel。
* [stage.now.sh](https://stage.now.sh) - 從 GitHub 拉取請求自動創建登台環境。
* [pullmeapp](https://github.com/ricardocasares/pullmeapp) - 使用個性化別名暫存您的 GitHub 拉取請求。

### [](#deployment-examples)部署示例

* [ws](https://ws.now.sh) - [📖](https://github.com/hemanth/ws-now) - 簡單的 echo web-socket。
* [micro-link](https://micro-link.now.sh) - [📖](https://github.com/xkawi/micro-link) - 用於生成和解析可共享動態鏈接的簡約微服務（又名深度鏈接）。
* [image-upload](https://getexponent.com/@community/image-upload-example) - [📖](https://github.com/exponentjs/image-upload-example) - 演示如何從 ImagePicker 上傳圖像。

### [](#boilerplates)樣板

* [micro-rest](https://github.com/hyperfuse/micro-rest) - 輕鬆部署微 REST 服務。
* [datasette](https://github.com/simonw/datasette) - 立即將 SQLite 數據庫部署為 JSON API，例如 https://australian-dogs.now.sh/
* [now-go](https://github.com/amio/now-go) - 在 1 分鐘內創建和部署個人 tinyurl 服務。
* [create-react-app-now](https://github.com/xkawi/create-react-app-now) - 使用 Vercel 輕鬆部署 react.js 應用程序。
* [micro-graphql](https://github.com/hyperfuse/micro-graphql) - 輕鬆部署微 GraphQL 服務。有關將 GraphQL 與 Micro 一起使用的示例，請參閱 [micro-graphql-example](https://www.github.com/timneutkens/micro-graphql)
* [create-micro](https://github.com/romuloalves/create-micro) - 創建一個基本的微服務。
* [meteor-now](https://github.com/mazlix/meteor-now) - 通過 Vercel 將 MeteorJS 應用程序部署在一條線上。
* [nuxt-micro-template](https://github.com/vuchl/nuxt-micro-template) - vue-cli 創建 [nuxt](https://github.com/nuxt/nuxt.js) 的腳手架) 帶有 [micro](https://github.com/zeit/micro) 後端的應用程序
* [micro-authentication-starter](https://github.com/littleStudent/micro-authentication-starter) - [micro](https://github.com/zeit/micro) 使用`內置身份驗證的入門套件bcrypt` 和 `jsonwebtokens`
* [aframe-next-static](https://github.com/michaltakac/aframe-next-static) - 使用 A-frame 和 React 構建 WebVR 應用程序，將它們導出並作為 Vercel 上的靜態站點提供服務。
* [next-init](https://www.npmjs.com/package/next-init) - 最簡單的 Next.js 生成器。
* [next.js-typescript-starter-kit](https://github.com/deptno/next.js-typescript-starter-kit) - Next.js@5 + redux + typescript，用於 SEO、分析的簡單配置. 你可以在 tsx 中使用 styled-jsx。

### [](#api-clients)API 客戶端

* [now-client](https://github.com/zeit/now-client) - _deprecated_ - 現在他們的 API 的 JavaScript 客戶端。
* [zeit-client-api](https://github.com/massless/zeit-client-api) - 另一個用於管理您的 Vercel 帳戶的 JavaScript 客戶端。
* [now-fetch](https://github.com/shawnbot/now-fetch) - 一個輕量級的 Vercel API 包裝器，具有熟悉的 `fetch()` 接口。
* [pynow](https://github.com/controversial/pynow) - Vercel API 的 python 客戶端。
* [nash](https://github.com/littleStudent/now_dashboard) - _deprecated_ 一個用於管理部署、別名和機密的網絡 [dashboard](https://nash.now.sh)。
* [now4j](https://github.com/rm3l/now4j) - Vercel API 的非官方 Java 客戶端
* [know](https://github.com/rm3l/know) - Vercel API 的非官方 Kotlin 客戶端
* [now-php-client](https://github.com/joecohens/now-php-client) - Vercel API 的非官方 PHP 5.4+ 客戶端

### [](#vercel-showcase)Vercel 展示

* [illustrated-algorithms.now.sh](https://illustrated-algorithms.now.sh/) - 該項目旨在通過其執行的交互式可視化揭示算法背後的機制。
* [next-news.now.sh](https://next-news.now.sh/) - 使用 Next.js 製作的黑客新聞
* [colors.now.sh](https://colors.now.sh/) - Material Design 顏色瀏覽器和選擇器
* [rainbow.now.sh](https://rainbow.now.sh) - 一個 Material Design 和 Flat Design 顏色選擇器
* [xvg.now.sh](https://xvg.now.sh/) - 一個用於調試 SVG 路徑的 Chrome 擴展
* [newton.now.sh](https://newton.now.sh/) - 一個真正的高級數學微服務
* [fe-lenses.now.sh](https://fe-lenses.now.sh/) - 全畫幅 E 卡口鏡頭目錄
* [shot.now.sh](https://shot.now.sh/) - 截圖即服務
* [mess.now.sh](https://mess.now.sh/) - 帶有混亂字體的模糊文本
* [md.now.sh](https://md.now.sh/) - Markdown 渲染服務
* [go.now.sh](https://go.now.sh) - 個人 tinyurl 服務
* [up.now.sh](https://up.now.sh/) - 用於檢查網站是否正常運行的微服務
* [e.now.sh](https://e.now.sh/) - 用於服務、列出和搜索表情符號的微服務
* [f.now.sh](https://f.now.sh/) - 通過國家代碼獲取國旗圖標的微服務
* [gif.now.sh](https://gif.now.sh) - Giphy 翻譯 API 的簡單微服務
* [emails.now.sh](https://emails.now.sh) - 輕鬆將電子郵件遞送服務部署到 Vercel
* [next-time.now.sh](https://next-time.now.sh) ([src](https://github.com/billymoon/next-time)) - 一個非常小的 Vercel 主題時鐘（演示同構頁面渲染）
* [georgeo.now.sh](https://github.com/rmpato/georgeo) - 具有 API 和 [Web 界面](https://georgeo.now.sh) 的地理編碼服務
* [platzi-now.now.sh](https://platzi-now.now.sh/) - Next.js + Docker GraphQL 服務器應用程序部署到 Now.sh 使用別名路徑組合它們
* [micro-github-latest.now.sh](https://micro-github-latest.now.sh/) - [📖](https://github.com/evenchange4/micro-github-latest) -用於下載 GitHub 發布的最新資產的微服務。
* [micro-medium-api.now.sh](https://micro-medium-api.now.sh/) - [📖](https://github.com/evenchange4/micro-medium-api) -用於獲取 Medium 最新帖子的微服務。
* [now-swift-example.now.sh](https://now-swift-example.now.sh/) - [📖](https://github.com/aranajhonny/now-swift-example) -在部署到 Now.sh 的 Docker 容器中使用服務器端 Swift + Kitura 框架的示例。
* [builderbook.org](https://builderbook.org/) - [📖](https://github.com/builderbook/builderbook) - 用於編寫和託管文檔或銷售書籍的開源 Web 應用程序。使用 Now 部署並使用 React、Material-UI、Next.js、Express、Mongoose、MongoDB 構建。
* [pompom.now.sh](https://pompom.now.sh/) - [📖](https://github.com/pantharshit00/pomodoro-gatsby) - 使用 React 和 Gatsby 製作的開源番茄鐘。超快，移動友好，深色主題，離線工作。還有完成通知和警報
* [kap-now](https://github.com/lucaperret/kap-now) - 使用 Vercel 部署 [Kapture](https://github.com/wulkano/kap)。
* [drone-now](https://github.com/lucaperret/drone-now) - 在 [Drone CI](https://drone.io) 管道中部署到 Vercel。
* [vscode-now](https://github.com/lucaperret/vscode-now) - 在 VS Code 中創建和管理您的部署和別名。
* [releasebutler.now.sh](https://releasebutler.now.sh/) - 獲取流行前端框架和庫的發布和變更日誌！
* [carbon.now.sh](https://carbon.now.sh/) - 創建和分享您的源代碼的精美圖片。開始鍵入或將文件拖放到文本區域以開始。
* [iss.now.sh](https://iss.now.sh) - 當 ISS 通過您上方時接收推送通知的服務
* [circleci-artifacts.now.sh](https://circleci-artifacts.now.sh/) - 用於重定向到您最新的 CircleCI 構建工件的永久鏈接，因此您可以直接從項目中託管二進製文件、文檔和其他文件圈子 CI 工作。
* [whatdoyouhear.now.sh](https://whatdoyouhear.now.sh) - Yanny 還是 Laurel？
* [ipinfo.no​​w.sh](https://github.com/GitSquared/ipapi) - _deprecated_ 由 Now 提供支持的快速可靠的 geoip API。
* [bashplate.now.sh](https://bashplate.now.sh) - Bash Plate 允許您為負責接收、解析、驗證和記錄腳本參數的 shell 腳本生成樣板。
* [icon.now.sh](https://icon.now.sh) - SVG 圖標佔位符微服務。
* [github-contributions.now.sh](https://github-contributions.now.sh) - :octocat: GitHub 貢獻圖表生成器

### [](#related-lists)相關列表

* [awesome-hyper](https://github.com/bnb/awesome-hyper) - 令人愉快的 Hyper 插件、主題和資源。

### [](#communities)社區

* [Vercel](https://github.com/zeit/now/discussions) - Github 上的 Vercel

[](#contribute)貢獻
-------------------------

1. [fork](https://help.github.com/articles/fork-a-repo/) 這個倉庫到你自己的 GitHub 賬號然後[clone](https://help.github.com/articles/ cloning-a-repository/) 到您的本地設備。
2.開始做出改變！