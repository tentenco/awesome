# Awesome Shopify [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[<img src="shopify.png" width="250px" align="right" alt="Shopify">](https://www.shopify.com/?ref=vitalogy)

> 精選的 [Shopify](https://www.shopify.com) 資源、庫和開源項目列表。

[Shopify](https://www.shopify.com/blog/what-is-shopify?ref=vitalogy) 是一個流行的電子商務平台，允許建立和管理在線商店。
如果您想投稿，請閱讀[投稿指南](https://github.com/julionc/awesome-shopify/blob/master/contributing.md)。
感謝所有 [貢獻者](https://github.com/julionc/awesome-shopify/graphs/contributors)，你們太棒了，沒有你們就不可能！

＃＃ 內容

- [社區](#community)
- [文檔](#documentation)
- [前端開發](#front-end-development)
- [手機](#mobile)
- [圖書館](#libraries)
  - [紅寶石](#ruby)
  - [Python](#python)
  - [JavaScript](#javascript)
  - [點網](#dotnet)
  - [靈藥](#靈藥)
  - [哈斯克爾](#haskell)
  - [Java](#java)
  - [Golang](#golang)
  - [PHP](#php)
  - [R](#r)
  - [銹]（#銹）
- [示例](#examples)
  - [JavaScript 示例](#javascript-examples)
  - [PHP 示例](#php-examples)
  - [Python 示例](#python-examples)
  - [Ruby 示例](#ruby-examples)
  - [Elixir 示例](#elixir-examples)
- [代碼片段](#code-snippets)
- [工具](#tools)

＃＃ 社區

- [@ShopifyPartners](https://twitter.com/ShopifyPartners) - Shopify 合作夥伴官方 Twitter 帳戶。
- [@ShopifyDevs](https://twitter.com/ShopifyDevs) - Shopify 開發團隊 Twitter 帳戶。
- [社區論壇](https://community.shopify.com/) - 討論電子商務最佳實踐以及如何擁有成功的在線商店。
- [Shopify Partners Slack 社區](https://shopifypartners.slack.com/) - Shopify Partners Slack 官方頻道。如果您是合作夥伴，請轉到您的資源選項卡，它也應該在那裡鏈接。
- [Shopify Devs Discord 社區](https://discord.gg/mdyHp6km2B) - Shopify Devs Discord 官方頻道。
- [eCommTalk](http://ecommtalk.com/) - 一個 Slack 社區，旨在將 Shopify 愛好者聚集在一起。
- [/r/shopify](https://www.reddit.com/r/shopify) - Shopify Reddit 社區。

## 文檔

- [開發者更新日誌](https://developers.shopify.com/changelog) - 官方開發者更新日誌博客，其中包含對 API 和其他開發者產品的重要更改。
- [開發者指南](https://help.shopify.com/api/guides) - 如果您不熟悉為 Shopify 開發應用程序，請查看官方指南以大致了解該過程。
- [Shopify - 身份驗證的 OAuth 流程](https://help.shopify.com/api/guides/authentication/oauth) - 本指南將引導您完成 OAuth 授權過程。
- [Shopify 合作夥伴帳戶](https://www.shopify.com/partners?ref=vitalogy) - 如果您還沒有 Shopify 合作夥伴帳戶，請前往此處創建一個，您需要先擁有它開始開發應用程序。
- [應用要求清單](https://help.shopify.com/api/listing-in-the-app-store/app-review-checklist) - 用於向 Shopify 應用商店提交應用。
- [關於開發商店你需要知道的一切](https://www.shopify.com/partners/blog/development-stores?ref=vitalogy) - 了解開發商店。

## 前端開發

### 用戶界面/用戶體驗

- [Shopify Polaris](https://polaris.shopify.com) - Polaris 是一個 React 組件庫，旨在幫助開發者為商家創造最佳體驗。[GitHub](https://github.com/Shopify/polaris):sunny:.
- [Slate](https://github.com/Shopify/slate) - Slate 是用於開發 Shopify 主題的工具包，旨在幫助您的工作流程並加快開發、測試和部署主題的過程。
- [Shopify Polaris UI 套件](https://polaris.shopify.com/resources/polaris-ui-kit) - Sketch UI 套件提供了一組可重複使用的組件，幫助您為 Shopify 製作出色的產品。
- [Polaris 圖標瀏覽器](https://polaris-icons.shopify.com) - 一組簡單且信息豐富的圖標，這些圖標利用了 Polaris 設計系統的視覺語言。
- [Shopify 主題實驗室](https://github.com/uicrooks/shopify-theme-lab) - 可定制的模塊化開發環境，用於快速創建 Shopify 主題，與 Vue.js 和 Tailwind CSS 捆綁在一起。
- [Shopify Packer](https://github.com/hayes0724/shopify-packer) - 使用 Webpack 5 的 Shopify 現代開發工具。易於擴展和定制，零構建配置，與 Slate 和現有網站兼容。

### CSS 框架

- [Foundationify](https://github.com/lukebussey/foundationify) - 基於響應式 Zurb Foundation 5 框架的 Shopify 主題。
- [Uptown CSS](https://github.com/shoppad/uptowncss/) - Uptown CSS 是一個語義工具包，旨在幫助開發人員構建完全響應的 Shopify 應用程序。

### 液體模板

- [Liquid](https://shopify.github.io/liquid/) - Liquid 是一種安全的、面向客戶的模板語言，適用於靈活的 Web 應用程序。
- [Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet) - 使用 Liquid 構建 Shopify 主題的資源。
- [Liquid 模板語言參考](https://shopify.dev/docs/themes/liquid/reference) - Liquid 是所有 Shopify 主題的支柱，用於將動態內容加載到在線商店的頁面。

### Shopify 在線商店 2.0

- [Shopify Dawn](https://github.com/Shopify/dawn) - Shopify 的第一個源可用參考主題，內置在線商店 2.0 功能和性能。
- [Figma - Shopify 的 Dawn 主題 - 在線商店 2.0](https://www.figma.com/community/file/1017615468313501249) - 如果您正在為新的 Shopify 在線商店 2.0 設計主題並且希望擁有 Dawn主題作為一個很好地放在一起的 Figma 文件。
- [Helium](https://github.com/idbakkasse/helium) - 從頭開始的 Shopify 主題環境⚙️，具有在線商店 2.0 功能。構建時考慮到了性能⚡️和最佳實踐，在 SASS/ES6 文件更改上具有熱模塊重新加載以實現快速開發和更多其他開箱即用的功能......
＃＃＃ 其他

- [Liquid Ajax Cart](https://liquid-ajax-cart.js.org) - 一個 JavaScript 庫，用於使用 Liquid 模板構建 Shopify Ajax-carts。
- [Cart.js](https://cartjs.org) - 一個 JavaScript 庫，為 Shopify 主題的購物車提供動力。
- [Shopify Skeleton 主題](https://github.com/Shopify/skeleton-theme) - 一個簡化的 Shopify 主題。
- [shopify-css-import](https://github.com/Shopify/shopify-css-import) - 使用 Grunt.js 或 Gulp.js 將 CSS 導入功能添加到 Shopify 主題開發中。
- [在您的自定義店面中設置和使用 Shopify 元字段](https://www.zauberware.com/en/articles/2019/setup-and-use-shopify-metafields-in-your-custom-storefront/) - 使用用於創建和獲取 Shopify 元字段的 GraphQL API。

＃＃ 移動的

您可以使用 iOS 和 Android Buy SDK 將 Shopify 結賬集成到您的移動應用程序中。這使您可以通過該應用銷售您的任何實體產品，並在您的 Shopify 後台中跟踪銷售信息。[在此處了解更多信息›](https://help.shopify.com/en/api/storefront-api/tools)。

＃＃＃ 安卓

- [Shopify Mobile for Android](https://www.shopify.com/install/android)
- [Shopify 移動購買 SDK](https://github.com/Shopify/mobile-buy-sdk-android)

### iOS

- [Shopify Mobile for iPhone](https://www.shopify.com/install/mobile)
- [Shopify 移動購買 SDK](https://github.com/Shopify/mobile-buy-sdk-ios)

###

## 庫

您可以使用官方 Shopify 庫或以下任何第三方庫來驗證 Shopify API 並與之交互。

### 紅寶石

- [shopify_api](https://github.com/Shopify/shopify_api) - Shopify Ruby API。
- [shopify_app](https://github.com/Shopify/shopify_app) - Ruby on Rails 引擎。
- [omniauth-shopify-oauth2](https://github.com/Shopify/omniauth-shopify-oauth2) - 使用 OmniAuth 進行身份驗證。
- [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Shopify Sinatra 應用程序。
- [lucid_shopify](https://github.com/luciddesign/lucid_shopify) - Shopify API 的基本接口。

＃＃＃ Python

- [shopify_python_api](https://github.com/Shopify/shopify_python_api) - ShopifyAPI 庫允許 Python 開發人員以編程方式訪問商店的管理部分。
- [django-shopify-auth](https://github.com/discolabs/django-shopify-auth) - 用於將 Shopify 身份驗證添加到 Django 應用程序的包。
- [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook) - 在 Django 中接收 Shopify Webhook 的包。

### JavaScript

- [@shopify/koa-shopify-auth](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-auth) - Koa HTTP 中間件框架的 Shopify Auth。
- [@shopify/koa-shopify-graphql-proxy](https://github.com/Shopify/quilt/blob/master/packages/koa-shopify-graphql-proxy/README.md) - Koa 的 Shopify GraphQL 代理HTTP 中間件框架。
- [@shopify/koa-shopify-webhooks](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-webhooks) - 適用於 Koa HTTP 中間件框架的 Shopify Webhooks 中間件。
- [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) - Shopify JavaScript 購買 SDK。
- [shopify-api-node](https://github.com/MONEI/Shopify-api-node) - Node.js Shopify 連接器。
- [shopify-node-api](https://github.com/christophergregory/shopify-node-api) - Shopify API 的 OAuth2 模塊。
- [shopify-nextjs-toolbox](https://github.com/ctrlaltdylan/shopify-nextjs-toolbox) - 一組服務器端和客戶端 NextJs 實用程序，用於與 Shopify 的 OAuth 和 App Bridge 身份驗證集成。

### 點網

- [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) - Shopify 的 .NET 庫。
- [agileharbor/shopifyAccess](https://github.com/agileharbor/shopifyAccess) - Shoppify API .NET 包裝器。

### 靈藥

- [sticksnleaves/exshopify](https://github.com/sticksnleaves/exshopify) - Shopify API 的 Elixir 客戶端。
- [pixelunion/elixir-shopifyapi](https://github.com/pixelunion/elixir-shopifyapi) - ShopifyAPI 和 Plug.ShopifyAPI Elixir 客戶端。
- [shopify_elixir](https://github.com/sdn90/shopify_elixir) - Elixir 的 Shopify API 庫。

### 哈斯克爾

- [haskell-shopify](https://github.com/aaronlevin/haskell-shopify) - Shopify API 的類型安全 Haskell 客戶端。

### 爪哇

- [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) - Shopify API 的 Java 包裝器。

### 哥朗

- [gopify](https://github.com/oussama4/gopify) - 一個用於在 Go 中開發 Shopify 應用程序的簡單包。
- [bold-commerce/go-shopify](https://github.com/bold-commerce/go-shopify) - Shopify API 的 Go 客戶端。
- [go-shopify](https://github.com/kiwih/go-shopify) - Golang 工具，用於連接 Shopify 的 API。
- [shoauth](https://github.com/darrenpeters/shoauth) - Golang 的 Shopify oauth (oauth2) 中間件。

### PHP

- [PHP 的 Shopify API 庫](https://github.com/Shopify/shopify-php-api) - 官方庫支持 PHP Shopify 應用程序訪問 Shopify Admin API 🚀。
- [pizdata/oauth2-shopify-php](https://github.com/pizdata/oauth2-shopify-php) - OAuth 2.0 客戶端的 Shopify 提供商。
- [multidimension-al/oauth2-shopify](https://github.com/multidimension-al/oauth2-shopify) - Shopify 對 PHP League 的 OAuth 2.0 客戶端的 OAuth 2.0 支持。
- [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) - 基於 Guzzle 的 API 客戶端。
- [phpclassic/php-shopify](https://github.com/phpclassic/php-shopify) - Shopify API 的 PHP SDK。
- [ZfrShopify](https://github.com/zf-fr/zfr-shopify) - 圍繞 Shopify API 的 Guzzle 客戶端。
- [Laravel 的 Shopify API 包](https://github.com/joshrps/laravel-shopify-API-wrapper) - Laravel API 包裝器。
- [donutdan4114/shopify](https://github.com/donutdan4114/shopify) - 一個簡單的 Shopify PHP SDK，供私有應用程序輕鬆與 Shopify API 交互。
- [slince/shopify-api-php](https://github.com/slince/shopify-api-php) - 適用於 PHP 的 Shopify API 客戶端。
- [ohmybrew/Basic-Shopify-API](https://github.com/ohmybrew/Basic-Shopify-API) - 一個簡單的、經過測試的、使用 Guzzle for REST 和 GraphQL 的 Shopify API 包裝器。
- [osiset/laravel-shopify](https://github.com/osiset/laravel-shopify) - 一個功能齊全的 Laravel 包，用於幫助 Shopify 應用程序開發。
- [buy-button-wordpress](https://github.com/Shopify/buy-button-wordpress) - 購買按鈕的 Wordpress 插件。
- [bold-shopify-toolkit](https://github.com/bold-commerce/bold-shopify-toolkit) - 基於 Symfony 的 Shopify api 包裝器。
- [oseintow/laravel-shopify](https://github.com/oseintow/laravel-shopify) - Laravel Shopify 是一個簡單的包，它有助於構建與 Shopify 的強大集成。
- [tothjmt/Laravel-Shopify](https://github.com/tothjmt/Laravel-Shopify) - Laravel / Shopify API 包裝器。
- [CakePHP 插件](https://github.com/cmcdonaldca/CakePHP-Shopify-Plugin) - CakePHP 的簡單插件。

### R

- [shopifyr](https://github.com/charliebone/shopifyr/) - 旨在為 R 中的 Shopify Admin API 提供易於使用的界面。

### 銹

- [Ventmere/shopify](https://github.com/Ventmere/shopify/) - 適用於 Rust 的 Shopify API 客戶端。

＃＃ 例子

一個開源項目

### JavaScript 示例

- [Shopify App Node](https://github.com/Shopify/shopify-app-node) - 使用 Node、Next.js、Shopify-koa-auth、Polaris 和 App Bridge 創建嵌入式 Shopify 應用程序的樣板反應：晴天：。
- [Storefront API 示例](https://github.com/Shopify/storefront-api-examples) - 基於 Shopify 的 Storefront API 構建的示例自定義店面應用程序。
- [產品評論示例應用程序](https://github.com/Shopify/product-reviews-sample-app) - 示例應用程序是作為參考構建的，以了解如何結合使用 Shopify 開發人員工具來創建功能齊全的應用程序。
- [SmallAwesomeShop](https://github.com/JsssCode/SmallAwesomeShop) - 使用 Shopify 的 Storefront GraphQL API 的 Angular 7 應用示例。
- [使用 Node.js、MongoDB 和 Next.js 的 Shopify 應用程序](https://github.com/kinngh/shopify-node-mongodb-next-app) - 使用 Node.js、MongoDB 和 Next 製作的樣板嵌入式應用程序。 js。
- [帶有會話令牌的 Next.JS 應用程序](https://github.com/ctrlaltdylan/shopify-session-tokens-nextjs) - 由帶有會話令牌的 NextJS 提供支持的 Shopify 應用程序示例（無需自定義服務器）。
- [Vue Storefront 2](https://github.com/vuestorefront/shopify) - Shopify 的 Vue Storefront 2 集成。
- [使用 Node.js、MongoDB、React.js 和 Express 的 Shopify 應用程序](https://github.com/kinngh/shopify-express-mongodb-app) - 使用 Express.js、MongoDB 和 React 製作的樣板嵌入式應用程序。 js 與 webhook、GDPR 路由、貨幣化和更多連接並準備就緒。
- [Shopify App Starter (Typescript, Mongo, Express, React)](https://github.com/yoMerce/shopify-app-starter) - 一個用 Typescript 編寫的 shopify 應用啟動器。它使用 Mongodb、Express 和 React。

### PHP 示例

- [shopify-app-php](https://github.com/Shopify/shopify-app-php) - Shopify PHP 應用程序示例 (Laravel)。

### Python 示例

- [shopify_django_app](https://github.com/shopify/shopify_django_app) - Shopify Django 應用示例。

### Ruby 示例

- [shopify-fulfillment-integration](https://github.com/Shopify/shopify-fulfillment-integration) - 與 Shopify 的示例履行服務集成。
- [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) - [Hosted Payment SDK]使用示例(https://docs.shopify.com/api/sdks/hosted-支付 SDK）。
- [shopify-sim](https://github.com/urbandictionary/shopify-sim) - Sinatra 應用程序可在本地預覽 Shopify 主題。
- [shopify-surge-pricing](https://github.com/kevinhughes27/shopify-surge-pricing) - 基於購物車更新 webhook 的 Shopify 激增定價演示。
- [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) - 購買指定產品時自動發送稅單的 Shopify 應用。
- [partner-metrics-for-shopify](https://github.com/forsbergplustwo/partner-metrics-for-shopify) - Rails 上 Shopify 合作夥伴的指標儀表板。
- [Shopify 應用入門工具包](https://github.com/ASoftCo/shopify-app-starter-kit) - 用 Ruby on Rails 編寫的 Shopify 應用樣板，帶有適當的工具，可讓您的 Shopify 應用快速啟動並運行🚀。

### Elixir 示例

- [pixelunion/elixir-shopify-app](https://github.com/pixelunion/elixir-shopify-app) - Elixir Shopify App 樣板 (Phoenix)。

## 代碼片段

- [freakdesign/Shopify-code-snippets](https://github.com/freakdesign/Shopify-code-snippets) - Shopify 代碼片段示例和提示。
- [vikrantnegi/shopify-code-snippets](https://github.com/vikrantnegi/shopify-code-snippets) - Shopify 開發人員的代碼片段彙編。
- [gocomet/snippets](https://github.com/gocomet/snippets) - 代碼片段的集合，通常用於 Shopify。

＃＃ 工具

＃＃＃ 應用程序

- [Shopify developer-tools](https://github.com/shopifypartners/developer-tools) - 一個 macOS 應用程序，可連接到您的 Shopify 商店並允許您對 Admin API 進行經過身份驗證的調用，生成虛擬數據，並查看和自定義 Polaris 組件。[更多信息]（https://www.shopify.com/partners/blog/developer-tools）。

### 瀏覽器擴展

- [Shopify Theme Inspector for Chrome](https://chrome.google.com/webstore/detail/shopify-theme-inspector-f/fndnankcflemoafdeboboehphmiijkgp) - 在您的 Shopify 商店中配置和調試 Liquid 模板。
- [ShopifyFD 儀表板工具](https://github.com/freakdesign/shopifyFD) - 為 Shopify 儀表板提供附加功能的 Chrome 擴展。
- [Shopify 的自定義字段](https://github.com/freakdesign/shopify-custom-fields) - 瀏覽自定義字段的 Chrome 擴展。
- [Shopify App Detector](https://chrome.google.com/webstore/detail/shopify-app-detector-by-f/lhfdhjladfcmghahdbcmlceajdlbkale) - 檢測 Shopify 商店使用的應用程序和主題。[GitHub](https://github.com/feracommerce/shopify_app_detector)
- [Shopify 主題嚮導](https://chrome.google.com/webstore/detail/shopify-theme-wizard-by-e/fhkelfkhcaokghlkckfgjoejhanelped) - 檢測 Shopify 商店使用的主題。

### 命令行工具

- [Shopify CLI](https://github.com/Shopify/shopify-cli) - Shopify CLI 可幫助您更快地針對 Shopify 平台進行構建🚀。
- [Shopify Theme Kit](https://github.com/Shopify/themekit) - Shopify 主題開發命令行工具。
- [Shopify 主題檢查](https://github.com/Shopify/theme-check) - 終極 Shopify 主題 Linter。
- [ziplinesFly](http://ziplines.pixelcab.in) - 輕鬆進入 Shopify 開發流程。
- [grunt-shopify](https://github.com/wilr/grunt-shopify) - 用於發布 Shopify 主題資產的 Grunt 插件。
- [Shopify 開發工具](https://github.com/ScreenStaring/shopify-dev-tools) - 協助應用程序和商店的開發/維護：操作元字段和 webhook、打開管理頁面、檢索商店信息等.
- [Shopify ID 導出](https://github.com/ScreenStaring/shopify_id_export) - 將 Shopify 產品和變體 ID（連同其他標識符）轉儲到 CSV 或 JSON 文件中。
- [Shopify 電子郵件模板同步客戶端](https://github.com/mash/shync) - Shync 可以從您的 Shopify 商店管理員簽出/下載 Shopify 電子郵件模板到您的本地計算機，並在您的本地計算機上推送/同步您的電子郵件模板本地機器到 Shopify。

### 編輯器

- [VS Code Liquid](https://github.com/panoply/vscode-liquid) - Liquid VS Code 擴展，支持格式化、語法高亮等。
- [Shopify Textmate Bundle](https://github.com/meeech/shopify.tmbundle) - 用於與 Shopify 主題資產交互的 Textmate Bundle。
- [vim-liquid](https://github.com/tpope/vim-liquid) - Vim Liquid 運行時文件。
- [VS Code Liquid Snippets Extension](https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets) - VS Code 編輯器的擴展，帶有 Shopify Liquid 的自動完成片段。

＃＃＃ 服務

- [Ngrok](https://ngrok.com) - Ngrok 是一個工具，可以輕鬆地將您的開發環境公開到 Internet。
- [RequestBin](http://requestbin.net) - 它給你一個桶來捕獲外部請求。這對於查看 [Shopify Webhook](https://help.shopify.com/en/manual/orders/notifications/webhooks) 的內容非常有用。
- [Hookdeck](https://hookdeck.io) - Hookdeck 是一種使用自定義重試邏輯、警報和過濾來監控 [Shopify Webhooks](https://help.shopify.com/api/reference/webhook) 的工具. 在開發和生產中使用 webhook 時，有助於提供可見性並節省時間。

### 實用程序

- [Shopify 產品 CSV 和圖像](https://github.com/shopifypartners/shopify-product-csvs-and-images) - 讓您的 Shopify 開發商店開始使用出色的產品數據。
- [UnProduct-Shopify](https://github.com/byjord/UnProduct-Shopify) - Shopify 平台的非統一測試產品數據。使用 UnProduct-Shopify 模擬真實世界的產品。
- [Sketch Shopify 數據填充器](https://github.com/shopifypartners/sketch-shopify-data-populator)
- [City 電子商務 UI 套件](https://github.com/shopifypartners/City-Ecommerce-UI-Kit) - City 是我們基於虛構時尚服裝店的免費電子商務 UI 套件。（原型 Shopify 商店設計）