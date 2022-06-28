# Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status ](https://img.shields.io/travis/chiraggude/awesome-laravel/master.svg?style=flat)](https://travis-ci.org/chiraggude/awesome-laravel)

> 精選的書籤、軟件包、教程、視頻和其他來自 Laravel 生態系統的酷資源的精選列表。

靈感來自 [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

＃＃ 目錄

- [必需品](#essentials)
- [包](#packages)
- [流行包](#popular-packages)
- [開發設置](#development-setup)
- [應用程序託管](#application-hosting)
- [應用部署](#application-deployment)
- [代碼片段](#code-snippets)
- [教程和博客](#tutorials--blogs)
- [視頻](#videos)
- [會議](#conferences)
- [書籍](#books)
- [啟動項目](#starter-projects)
- [參考代碼庫](#codebases-for-reference)
- [內容管理系統](#content-management-systems)
- [播客](#podcasts)
- [社區](#community)
- [工作](#jobs)
- [託管開發工具](#hosted-development-tools)
- [雜項](#雜項)

## 要點

* [Laravel](https://laravel.com) ([文檔](https://laravel.com/docs))
* [Laravel API 參考](https://laravel.com/api/master/)
* [流明](https://lumen.laravel.com) ([文檔](https://lumen.laravel.com/docs))
* [Laracasts](https://laracasts.com)
* [Laravel 新聞](https://laravel-news.com) ([存檔](https://laravel-news.com/archive/))

## 包

* [包裝師](https://packagist.org/)
* [Laravel 集體](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## 熱門套餐

> 這是 Laravel 項目中經常使用的有據可查、經過測試的包的列表。如果您正在尋找 PHP 包的詳盡列表，請查看上面提到的包存儲庫。

＃＃＃＃＃ 開發者工具

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - Laravel 的智能 CRUD 生成器
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - 為IDE自動補全生成幫助文件
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - 擴展內置文件生成器
* [Laravel API/Scaffold/CRUD Generator](https://github.com/InfyOmLabs/laravel-generator) - APIs、CRUD 腳手架等的生成器。
* [Laravel Tinx](https://github.com/furey/tinx) - 從 Tinker 內部重新加載 Laravel Tinker 會話
* [Laravel API 文檔生成器](https://github.com/mpociot/laravel-apidoc-generator) - 自動生成你的 API 文檔
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - 用於創建 Laravel 包的 CLI 工具
* [工作台導出到遷移](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - 用於將模型導出到 Laravel 遷移的工作台插件
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - 列出所有已安裝的包、它們的依賴項、應用程序和服務器詳細信息
* [LaRecipe](https://github.com/saleem-hadad/larecipe) - 在您的 Laravel 應用程序中使用 Markdown 為您的產品編寫精美的文檔。
* [Prequel](https://github.com/Protoqol/Prequel/) - 為 Laravel 調整的清晰簡潔的數據庫管理 GUI。

##### 測試和調試

* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - 在使用您的應用程序時生成 Laravel 集成測試的 Chrome 擴展
* [Laravel 測試工廠生成器](https://github.com/mpociot/laravel-test-factory-helper) - 從現有模型生成 Laravel 測試工廠
* [Clockwork](https://github.com/itsgoingd/clockwork) - 集成 Clockwork Chrome 擴展，用於調試和分析應用程序
* [調試欄](https://github.com/barryvdh/laravel-debugbar) - 將 PHP 調試欄與 Laravel 集成
* [Ignition](https://github.com/facade/ignition) - Laravel 應用程序的漂亮錯誤頁面
* [Laravel 5 日誌查看器](https://github.com/rap2hpoutre/laravel-log-viewer) - 日誌查看器
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - 提供日誌查看器
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - 將異常記錄到數據庫中並向您發送通知
* [郵件預覽](https://github.com/themsaid/laravel-mail-preview) - 在網頁瀏覽器或郵件客戶端預覽發送的郵件
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - 一個集成 Nette Tracy 調試器的 Laravel 包
* [Laravel Terminal](https://github.com/recca0120/laravel-terminal) - 在網絡瀏覽器中運行 artisan
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Laravel 路由的類似 Postman 的工具
* [Laravel Tail](https://github.com/spatie/laravel-tail) - 缺少的 tail 命令
* [Laravel Telescope](https://github.com/laravel/telescope) - Laravel Telescope 是一個優雅的 Laravel 框架調試助手

##### 身份驗證和授權

* [Bouncer](https://github.com/JosephSilber/bouncer) - 角色和權限
* [Laratrust](https://github.com/santigarcor/laratrust) - 角色、權限和團隊
* [委託](https://github.com/Zizaco/entrust) - 基於角色的權限
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - API 的 JSON Web Token 身份驗證
* [Laravel 權限](https://github.com/spatie/laravel-permission) - 將用戶與角色和權限相關聯
* [Defender](https://github.com/artesaos/defender) - 角色和權限
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 授權服務器和資源服務器
* [Socialite](https://github.com/laravel/socialite) - 使用 Facebook、Google、Twitter 等進行 OAuth 身份驗證。
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100 多個社交名流社交認證提供商，支持 Lumen
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google 雙重身份驗證模塊
* [Laravel 用戶驗證](https://github.com/jrean/laravel-user-verification) - 處理用戶驗證流程和驗證電子郵件
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP 認證和 Active Directory 管理
* [Doorman](https://github.com/clarkeash/doorman) - 使用邀請碼限制對 Laravel 應用程序的訪問
* [Laravel Heyman](https://github.com/imanghafoori1/laravel-heyman) - Heyman 在上面的角色權限包停止的地方繼續

##### 實用程序

* [Awes.io](https://github.com/awes-io/awes-io) - 基於 Vue (Nuxt.js)、TailwindCSS 和 Laravel 作為後端的 CRM、SaaS、ERP 樣板。
* [Artisan View](https://github.com/svenluijten/artisan-view) - 通過 artisan 管理 Laravel 項目中的視圖
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - 用於創建 Bootstrap 3 標記的類集
* [Captcha](https://github.com/mewebstudio/captcha) - 一個反機器人圖像驗證系統
* [Charts](https://github.com/ConsoleTVs/Charts) - 多庫圖表包創建交互式圖表
* [Lavacharts](https://github.com/kevinkhill/lavacharts) - 由 Google Chart API 提供支持的 PHP 圖表和圖表
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - 過濾器模型及其關係
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - 為 Eloquent 模型創建 slugs
* [Eloquent 可排序](https://github.com/spatie/eloquent-sortable) - Eloquent 模型的可排序行為
* [HTML](https://github.com/LaravelCollective/html) - Laravel 的 HTML 和表單構建器
* [多租戶](https://github.com/hyn/multi-tenant) - 靈活的多租戶與路由、資產和數據庫的安全分離
* [Laravel 表單構建器](https://github.com/kristijanhusak/laravel-form-b​​uilder) - 受 Symfony 表單構建器啟發的表單構建器
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - 在你的 Laravel 應用中記錄活動
* [Laravel 審計](https://github.com/owen-it/laravel-auditing) - 對 Eloquent 模型的審計
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - 創建和管理麵包屑
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - 一組方便的集合宏
* [Laravel Cookie 同意](https://github.com/spatie/laravel-cookie-consent) - 讓你的 Laravel 應用程序遵守瘋狂的歐盟 cookie 法律
* [Laravel 數據表](https://github.com/yajra/laravel-datatables) - jQuery 數據表 API
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - 根據訪問者的 IP 地址確定網站訪問者的位置
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - 使用 [Hashids](http://hashids.org/php/) 生成唯一的、非連續的 id
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - 作為您的用戶之一進行身份驗證的包
* [Laravel Mailbox](https://github.com/beyondcode/laravel-mailbox) - 處理傳入電子郵件的包
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark 降價解析器
* [Laravel 菜單](https://github.com/spatie/laravel-menu) - Laravel 的 Html 菜單生成器
* [Laravel Talk](https://github.com/nahid/talk) - 實時用戶消息系統
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - 用戶消息系統
* [Laravel 審核](https://github.com/hootlex/laravel-moderation) - 批准或拒絕帖子、評論、用戶等資源。
* [Laravel 標籤](https://github.com/spatie/laravel-tags) - 添加標籤和可標記行為
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - 從請求中收集信息以識別和存儲
* [Listify](https://github.com/lookitsatravis/listify) - 為任何 Eloquent 模型添加排序/排序功能
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Google 新的 noCAPTCHA (reCAPTCHA) 助手
* [淨化器](https://github.com/mewebstudio/purifier) - HTML 過濾器
* [Revisionable](https://github.com/VentureCraft/revisionable) - 為 Eloquent 模型創建修訂歷史
* [SEOTools](https://github.com/artesaos/seotools) - 一些常用 SEO 技術的助手
* [頁面緩存](https://github.com/JosephSilber/page-cache) - 將響應緩存為磁盤上的靜態文件，以實現閃電般的快速頁面加載
* [Laravel 設置](https://github.com/anlutro/laravel-settings) - 存儲在 JSON 文件中的持久配置設置
* [友情](https://github.com/hootlex/laravel-friendships) - 友情管理系統
* [團隊合作](https://github.com/mpociot/teamwork) - 用戶與邀請系統的團隊關聯
* [驗證](https://github.com/dwightwatson/validating) - 驗證 Eloquent 模型的特徵
* [增值稅計算器](https://github.com/mpociot/vat-calculator) - 處理與歐盟 MOSS 增值稅法規相關的所有難題
* [Laravel UUID](https://github.com/webpatser/laravel-uuid) - 根據 RFC 4122 標準生成 UUID
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - 允許用戶按照安裝嚮導安裝您的應用程序，例如 WordPress
* [Laravel Modules](https://github.com/nWidart/laravel-modules) - 簡單的模塊管理
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - 電話號碼驗證器和格式化程序
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - 簡化阻塞和禁止 Eloquent 模型
* [Laravel 代理](https://github.com/fideloper/TrustedProxy) - 在負載均衡器或其他中介之後處理會話。
* [Laravel 視頻聊天](https://github.com/PHPJunior/laravel-video-chat) - 使用 Socket.IO 和 WebRTC 進行視頻聊天
* [Laravel 小部件](https://github.com/arrilot/laravel-widgets) - 查看作曲家的強大替代方案。
* [安全標頭](https://github.com/BePsvPT/secure-headers) - 將安全相關標頭添加到 HTTP 響應
* [Laravel Nova](https://nova.laravel.com/) - Nova 是一個設計精美的 Laravel 管理面板
* [Laravel Love](https://github.com/cybercog/laravel-love) - 它讓人們表達他們對內容的感受。用喜歡或不喜歡對 Eloquent 模型做出反應。
* [stancl/tenancy](https://github.com/stancl/tenancy) - Laravel 應用程序的自動租用。無需更改代碼。

##### 媒體和文檔管理

* [Intervention Image](https://github.com/Intervention/image) - 用於創建、編輯和合成圖像的圖像處理庫
* [Laravel ImageUp](https://github.com/qcod/laravel-imageup) - 又一個圖像處理包，增加了大量的額外功能
* [Laravel Glide](https://github.com/spatie/laravel-glide) - 使用 Glide 輕鬆轉換圖像
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - 將文件與 Eloquent 模型相關聯
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - 使用 wkhtmltopdf 的 HTML 到 PDF 生成器
* [Laravel DOMPDF](https://github.com/barryvdh/laravel-dompdf) - 使用 [dompdf](https://github.com/dompdf/dompdf) 的 HTML 到 PDF 生成器
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - 基於ORM的文件上傳管理器
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - 導入導出Excel和CSV文件
* [Fast Excel](https://github.com/rap2hpoutre/fast-excel) - Laravel 的快速 XLSX、CSV 和 ODT 導入和導出
* [Laravolt Avatar](https://github.com/laravolt/avatar) - 即插即用，將姓名、電子郵件和任何其他字符串變成漂亮的頭像（或 gravatar），毫不費力。
* [Laravel FFmpeg](https://github.com/pascalbaljetmedia/laravel-ffmpeg) - 這個包為 Laravel 5.8 提供了與 FFmpeg 的集成。

##### 與 Javascript 集成

* [Laroute](https://github.com/aaronlord/laroute) - 從 JavaScript 生成 Laravel 路由 URL
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - 將服務器端字符串/數組/集合/whatever 傳遞給 JavaScript
* [Javascript 驗證](https://github.com/proengsoft/laravel-jsvalidation) - 使用驗證規則、消息、FormRequest 和驗證器在客戶端驗證表單
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - 一個 Pjax 中間件
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - 將變量導出到 JavaScript 的 Blade 指令
* [Ziggy](https://github.com/tightenco/ziggy) - 在 JavaScript 中使用你的 Laravel 命名路由
* [LiveWire](https://github.com/livewire/livewire) - 一個神奇的 Laravel 前端框架

##### 數據庫、ORM、遷移和播種

* [備份管理器](https://github.com/backup-manager/laravel) - 從 S3、Dropbox、SFTP 等備份和恢復數據庫。
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - 嵌套集模式實現
* [ClosureTable](https://github.com/franzose/ClosureTable) - 閉包表模式實現
* [Eloquence](https://github.com/kirkbushell/eloquence) - Eloquent 模型的額外功能
* [iSeed](https://github.com/orangehill/iseed) - 從現有的數據庫表生成一個新的種子文件
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - 通過 OCI8 的 Oracle DB 驅動程序
* [Laravel 備份](https://github.com/spatie/laravel-backup) - 備份你的應用
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM 實現
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - 支持 MongoDB 的 Eloquent 模型和查詢構建器
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - 從現有數據庫生成遷移
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Eloquent ORM 的擴展
* [Tenanti](https://github.com/orchestral/tenanti) - 多租戶數據庫模式管理器
* [Laravel Repository](https://github.com/andersao/l5-repository) - 抽像數據庫層的存儲庫
* [Lada Cache](https://github.com/spiritix/lada-cache) - 一個基於 Redis 的、完全自動化和可擴展的數據庫緩存層
* [Laravel MySQL 空間擴展](https://github.com/grimzy/laravel-mysql-spatial) - 輕鬆使用 MySQL 空間數據類型和 MySQL 空間函數

＃＃＃＃＃ 搜索

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - 將 Algolia Search API 集成到 Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Eloquent 模型的 Elasticsearch
* [Plastic](https://github.com/sleimanx2/plastic) - 流暢地映射和搜索 Elasticsearch
* [Laravel Search](https://github.com/mmanos/laravel-search) - Elasticsearch、Algolia 和 ZendSearch 的統一 API
* [SearchIndex](https://github.com/spatie/searchindex) - 從 Algolia 或 Elasticsearch 存儲和檢索對象
* [可搜索](https://github.com/nicolaslopezj/searchable) - 為 Eloquent 模型添加簡單搜索功能的特徵
* [TNTSearch](https://github.com/teamtnt/tntsearch) - 一個用 PHP 編寫的全功能全文搜索引擎
* [TNTSearch driver](https://github.com/teamtnt/laravel-scout-tntsearch-driver) - 基於TNTSearch的[Laravel Scout](https://github.com/laravel/scout) 搜索包驅動
* [Laravel-Searchy](https://github.com/TomLingham/Laravel-Searchy) - 模糊搜索、基本字符串匹配、Levenshtein 距離

##### API

* [ApiGuard](https://github.com/chrisbjr/api-guard) - 允許使用 API 密鑰進行 API 身份驗證
* [Dingo API](https://github.com/dingo/api) - 用於開發 RESTful API 的多用途工具包
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - 添加 CORS (Cross-Origin Resource Sharing) 頭文件支持
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - 使用 Fractal 輸出複雜、靈活、AJAX/RESTful 的數據結構
* [Laravel GraphQL](https://github.com/rebing/graphql-laravel) - 支持 Relay、eloquent 模型、驗證和 GraphiQL
* [Lighthouse](https://github.com/nuwave/lighthouse) - Laravel 即將推出的 GraphQL 庫
* [Laravel Responder](https://github.com/flugger/laravel-responder) - 使用 Fractal 構建自定義 API 響應

##### 任務、命令和調度

* [Dispatcher](https://github.com/indatus/dispatcher) - Artisan 命令的調度程序
* [Elixir](https://github.com/laravel/elixir) - 運行 Gulp 任務的 Node (NPM) 包
* [Mix](https://github.com/JeffreyWay/laravel-mix) - 用於定義基本 webpack 構建步驟的 Fluent API
* [Envoy](https://github.com/laravel/envoy) - SSH 任務運行器

##### 付款

* [Cashier](https://github.com/laravel/cashier) - 使用 Stripe 進行訂閱計費
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - 集成 [Omnipay](https://github.com/thephpleague/omnipay) PHP 庫

＃＃＃＃＃ 優化

* [干預圖像緩存](https://github.com/Intervention/imagecache) - 干預圖像類的緩存擴展
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier
* [Rememberable](https://github.com/dwightwatson/rememberable) - Eloquent 的查詢緩存
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - 頁面部分緩存
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - 通過緩存整個響應來加速應用程序

##### 監控

* [Horizo​​n](https://github.com/laravel/horizo​​n) - 使用簡單的 Web UI 監控和配置隊列
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - 當排隊的作業失敗時得到通知
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - 一個功能強大且易於配置的正常運行時間和 ssl 監視器
* [Larametrics](https://github.com/aschmelyun/larametrics) - Laravel 應用程序的自託管指標和通知平台

##### 本地化

* [語言文件](https://github.com/caouecs/Laravel-lang) - 37 種語言的驗證、分頁和提醒語言行
* [Laravel 本地化](https://github.com/mcamara/laravel-localization) - 通過路由添加 i18n 支持
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - 通過將翻譯存儲為 JSON 使 Eloquent 模型可翻譯
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - 檢索和存儲可翻譯的 Eloquent 模型實例
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - 將 Eloquent 模型翻譯成多種語言
* [Laravel Date](https://github.com/jenssegers/date) - 一個庫，可幫助您處理多種語言的日期，基於 Carbon
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - 從 Artisan 控制台管理語言文件
* [Laravel Translation](https://github.com/waavi/translation) - 翻譯和本地化管理
* [Linguist](https://github.com/keevitaja/linguist) - Laravel 的 i18n 本地化支持

##### 第三方服務集成

* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - 從 Google Analytics 中檢索頁面瀏覽量和其他數據
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 橋
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API 橋
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API 橋
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - 使用 Mailchimp 發送時事通訊
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API 橋

## 開發設置

* [Homestead](https://laravel.com/docs/master/homestead) - Laravel 的官方 Vagrant 盒子
* [Valet](https://laravel.com/docs/master/valet) - Mac 用戶開發環境
* [Valet Linux](https://github.com/cpriego/valet-linux) - Linux 用戶開發環境
* [LaraDock](https://github.com/LaraDock/laradock) - 在 Docker 上運行 Laravel（類似於 Homestead，但用於 Docker 而不是 Vagrant）
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - 單個 Docker 容器中的 Homestead 環境
* [Laragon](https://laragon.org/) - Windows 上的獨立開發環境
* [Stacker](https://github.com/Maxlab/stacker) - Docker上本地Web開發環境
* [Devilbox](https://github.com/cytopia/devilbox) - 每個 PHP 版本的 dockerized 和通用 LAMP/MEAN 堆棧
* [Vessel](https://vessel.shippingdocker.com) - Laravel 的簡單 Docker 開發環境
* [Lando](https://docs.lando.dev/config/laravel.html) - 基於Docker構建的本地開發環境工具

## 應用程序託管

* [蒸汽](https://vapor.laravel.com)
* [Forge](https://forge.laravel.com/) ([ForgeRecipes](https://forgerecipes.com/))
* [堡壘兔](https://www.fortrabbit.com/laravel-hosting)
* [Heroku](https://www.heroku.com/) ([文檔](https://devcenter.heroku.com/articles/getting-started-with-laravel))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([教程](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html ))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)
* [普洛伊](https://ploi.io/)
* [CodePier](https://codepier.io?ref=awesome-laravel)
* [運行雲](https://runcloud.io/)

## 應用部署

* [Deployer](https://deployer.org/) - 開箱即用支持 Laravel 的部署工具
* [Envoyer](https://envoyer.io/) - PHP 和 Laravel 項目的零停機部署程序
* [Rocketeer](https://github.com/rocketeers/rocketeer) - 任務運行器和部署包

## 代碼片段

* [Laravel LTS 備忘單](https://summerblue.github.io/laravel5-cheatsheet/) ([中文版](https://cs.phphub.org/))
* [Laravel 技巧](http://laravel-tricks.com/)

## 教程和博客

* [泰勒奧特威爾](http://taylorotwell.com/)
* [Tuts+](https://code.tutsplus.com/categories/laravel)
* [中](https://medium.com/tag/laravel/latest)
* [Laravel 日報](https://laraveldaily.com/)
* [蘇格蘭威士忌](https://scotch.io/tag/laravel)
* [數字海洋](https://www.digitalocean.com/community/search?q=laravel&primary_filter=newest&type=tutorials)
* [馬特斯托弗](https://mattstauffer.co/blog)
* [素食比特](https://vegibit.com/tag/laravel/)
* [霓虹海嘯](https://www.neontsunami.com/tags/laravel)
* [Dor.ky](https://dor.ky/tag/laravel/)
* [Stillat](https://stillat.com/explore/categories/laravel-5)
* [簡易 Laravel 圖書博客](http://www.easylaravelbook.com/blog/)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/category/laravel-5/) (ES)
* [Cloudways Laravel 博客](http://cloudways.com/blog/laravel)
* [Laravel 最佳實踐](https://github.com/alexeymezenin/laravel-best-practices)
* [Pusher Laravel 教程](https://pusher.com/tutorials?tag=Laravel)
* [LaraShout](https://larashout.com/)

## 視頻

* [Laracasts](https://laracasts.com/)
* [代碼課程](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [黑客服務器](https://serversforhackers.com/laravel-perf)
* [測試驅動的 Laravel](https://course.testdrivenlaravel.com/)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel) (ES)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Laracademy](https://laracademy.co/)
* [開發營銷人員](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel)
* [林達](https://www.lynda.com/search?q=laravel)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Bitfumes](https://www.youtube.com/bitfumes)
* [ConfidentLaravel](https://confidentlaravel.com/)

## 會議

* [Laracon 美國](http://laracon.us/)
* [Laracon 歐盟](http://laracon.eu/)
* [Laracon Online](https://laracon.net/)
* [Laraconf 巴西](http://laraconfbrasil.com.br/)
* [Laracon 澳大利亞](https://laracon.com.au/)
* [Laravel Live UK](https://laravellive.uk/)
* [Laravel Live India](https://laravellive.in/)
* [Laravel 尼日利亞](https://laravelnigeria.com)

#####視頻

* [Laracon EU 2018](https://www.youtube.com/playlist?list=PLMdXHJK-lGoC64wnqvm6v1R5dsuAV-MpS)
* [Laracon US 2018](https://www.youtube.com/playlist?list=PL-yJve--iT5oM2LgF37VXsBb8Os4ZulIc)
* [Laracon EU 2017](https://www.youtube.com/playlist?list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Laracon 美國 2017](https://www.youtube.com/playlist?list=PL-yJve--iT5oaLQA6OI8TWLVSOBP1qhs3)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon 美國 2016](https://www.youtube.com/playlist?list=PL-yJve--iT5o9fH_cRY0u6P751pcF59GK)
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* Laracon 美國 2015
* [Laracon EU 2014](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCYhxlU3OJ5bOGhcKtDMkcN)
* [Laracon 美國 2014](https://www.youtube.com/channel/UCRawXmZv30Vf_MivyPYb_GQ/videos)
* [Laracon EU 2013](https://www.youtube.com/playlist?list=PLMdXHJK-lGoB-CIVsiQt0WU8WcYrb5eoe)
* [Laracon 美國 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## 書籍

* [Laravel Starter](https://www.amazon.com/Laravel-Starter-Shawn-McCool-ebook/dp/B00ABFQ0AS) 作者：Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: Code Smart](https://leanpub.com/codesmart) by Dayle Rees
* [Laravel：從學徒到工匠](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) 由 Christopher Pitt 和 Taylor Otwell 撰寫
* [Laravel 測試解碼](https://leanpub.com/laravel-testing-decoded) 由 Jeffrey Way
* [重構為集合](https://adamwathan.me/refactoring-to-collections/) 作者：Adam Wathan
* [實現 Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [使用 Laravel 4 完成工作](https://leanpub.com/gettingstuffdonelaravel) 作者：Chuck Heintzelman
* [Laravel 應用程序開發藍圖](https://www.packtpub.com/web-development/laravel-application-development-blueprints) 作者：Arda Kılıçdağı 和 Halil İbrahim Yılmaz
* [構建你不會討厭的 API](https://leanpub.com/build-apis-you-wont-hate) 作者：Phil Sturgeon
* [將前端組件與 Web 應用程序集成](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel 設計模式和最佳實踐](https://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) 作者：Arda Kılıçdağı 和 Halil İbrahim Yılmaz
* [學習 Laravel 4 應用程序開發](https://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Laravel 4 入門](https://www.packtpub.com/web-development/getting-started-laravel-4) 作者：Raphaël Saunier
* [Laravel 應用程序開發手冊](https://www.packtpub.com/web-development/laravel-application-development-cookbook) 作者 Terry Matula
* [使用 Parse REST API 構建 Web 應用程序](https://leanpub.com/building-web-applications-using-parse-rest-api) 作者：Mhd Zaher Ghaibeh
* [Laravel - 我的第一個框架](https://leanpub.com/laravel-first-framework) 由 Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) 作者：W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [使用 Laravel 和 Stripe 輕鬆進行電子商務](https://leanpub.com/easyecommerce)，作者：W. Jason Gilmore 和 Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [使用 PHP 和 Laravel 設計模式](https://leanpub.com/larasign)，作者 Kelt Docins
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) 作者：Christopher John Pecoraro
* [如何使用 Pusher 構建實時 Laravel 應用程序](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [學習 Laravel 的 Eloquent](https://www.amazon.com/Learning-Laravels-Eloquent-Francesco-Malatesta-ebook/dp/B00YSILQ6C) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel 和 AngularJS](https://leanpub.com/laravel-and-angularjs) 作者 Daniel Schmitz 和 Daniel Pedrinha Georgii
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [使用 Lumen 編寫 API](https://leanpub.com/lumen-apis) 作者 Paul Redmond
* [Laravel 生存指南](https://leanpub.com/laravelsurvivalguide) 作者 Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck
* [Laravel 5.4 For Beginners](https://leanpub.com/laravel-5-4-for-beginners) by Bill Keck
* [Laravel 啟動並運行](https://www.amazon.com/gp/product/1491936088) 作者：Matt Stauffer
* [Laravel Companion](https://leanpub.com/laravelcompanion-secondedition) 作者：Johnathon Koster
* [使用 CloudFormation 在 AWS 上部署 Laravel](https://leanpub.com/laravel-aws) 作者：Lionel Martin
* [React Native 和 Laravel 用於未來的移動開發](https://leanpub.com/rn_laravel) by Ega Radiegtya
* [黑客服務器](https://book.serversforhackers.com) by Chris Fidao
* [全棧 Vue.js 2 和 Laravel 5](https://www.amazon.com/Full-Stack-Vue-js-Laravel-frontend-together/dp/1788299582) 作者：Anthony Gore
* [使用 Laravel 構建 API](https://buildanapi.com) by Wacky Studio

## 入門項目

* [火花](https://spark.laravel.com/)
* [LaraAdmin](https://github.com/dwijitsolutions/laraadmin)
* [塗鴉生成器](https://github.com/GrafiteInc/Builder)
* [Laravel 樣板](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter)
* [AdminLTE Laravel](https://github.com/acacha/adminlte-laravel)
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter)
* [Laravel API 入門工具包](https://github.com/joselfonseca/laravel-api)
* [Laravel 背包](https://github.com/Laravel-Backpack/Base)
* [SomelineStarter](https://github.com/someline/someline-starter)
* [Laravel 管理員](https://github.com/z-song/laravel-admin)
* [航海者](https://github.com/the-control-group/voyager)
* [蘭花](https://github.com/TheOrchid/Platform)
* [Laravel REST API 樣板](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt)
* [Hello API](https://github.com/Porto-SAP/Hello-API)
* [帶流明的 REST API](https://github.com/hasib32/rest-api-with-lumen)
* [Laravel Zero - 控制台應用程序](https://github.com/laravel-zero/laravel-zero)
* [Apiato](https://github.com/apiato/apiato)
* [Laravel 管理面板](https://github.com/viralsolani/laravel-adminpanel)
* [Laravel Vue 樣板](https://github.com/alefesouza/laravel-vue-boilerplate)
* [Laravel 恩索](https://github.com/laravel-enso/enso)
* [帶有 Vue 的 Laravel 模板](https://github.com/wmhello/laravel_template_with_vue)

## 參考代碼庫

* [Cachet](https://github.com/cachethq/Cachet) - 網站和 API 的狀態頁面系統
* [Deployer](https://github.com/REBELinBLUE/deployer) - 應用部署系統
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - 使用 Git 和 Scrum 進行任務管理
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - 發票、費用和時間跟踪應用程序
* [Koel](https://github.com/phanan/koel) - 個人音樂流媒體服務器
* [Laravel.io](https://github.com/laravelio/portal) - Laravel.io 社區門戶的來源
* [Attendize](https://github.com/Attendize/Attendize) - 售票及活動管理平台
* [Antvel](https://github.com/ant-vel/App) - 電子商務平台
* [Jigsaw](https://github.com/tightenco/jigsaw) - 靜態站點生成器
* [Canvas](https://github.com/cnvs/canvas) - Laravel 發布平台
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo 是博客平台，使用 Laravel 和 Vue.js 構建
* [Screeenly](https://github.com/stefanzweifel/screeenly) - 通過 API 創建網站截圖
* [Voten](https://github.com/voten-co/voten) - 21 世紀的實時社交書籤
* [Monica](https://github.com/monicahq/monica) - 個人關係管理系統
* [Snipe-IT](https://github.com/snipe/snipe-it) - IT 資產/許可證管理系統
* [Akaunting](https://github.com/akaunting/akaunting) - 小企業和自由職業者的會計軟件
* [Torch](https://github.com/mattstauffer/Torch) - 在非 Laravel 應用程序中使用每個 Illuminate 組件的示例
* [Pixelfed](https://github.com/pixelfed/pixelfed) - 一個免費且合乎道德的照片共享平台，由 ActivityPub 聯盟提供支持


## 內容管理系統

* [OctoberCMS](https://github.com/octobercms/october)
* [SleepingOwlAdmin](https://github.com/LaravelRUS/SleepingOwlAdmin)
* [PyroCMS](https://github.com/pyrocms/pyrocms)
* [LavaLite](https://github.com/LavaLite/cms)
* [TypiCMS](https://github.com/typicms/base)
* [Asgard CMS](https://github.com/AsgardCms/Platform)
* [微weber](https://github.com/microweber/microweber)
* [Coaster CMS](https://github.com/web-feet/coastercms)
* [靜態](https://statamic.com/)
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/)
* [PJ 博客](https://github.com/jcc/blog/)
* [Laralum](https://github.com/Laralum/Laralum)
* [斜紋](https://github.com/area17/twill)

## 播客

* [Laravel 播客](http://www.laravelpodcast.com/)
* [Laravel 新聞播客](https://laravel-news.com/podcast/ )
* [Laracasts 片段](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (西班牙語)](http://hechoenlaravel.com)

＃＃ 社區

* [Laracasts 論壇](https://laracasts.com/discuss)
* [Laravel.io 論壇](http://laravel.io/forum)
* [Larachat Slack](https://larachat.slack.com/) ([註冊](https://larachat.co/register))
* [吉特](https://gitter.im/laravel/laravel)
* [IRC 頻道](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [推特](https://twitter.com/laravelphp)
* [谷歌+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](https://www.quora.com/topic/Laravel)
* [臉書](https://www.facebook.com/LaravelCommunity)
* [領英](https://www.linkedin.com/groups/4419933/profile)

##### 本地用戶組

* [Laravel 全球社區](https://www.facebook.com/groups/group.laravel/)
* [LaravelES Slack](https://laraveles.slack.com) ([註冊](http://laraveles.com/blog/wp-login.php?action=slack-invitation))
* [Laravel India](https://laravellive.in/), [Slack Signup](https://laravelliveindia.slack.com/join/shared_invite/enQtNjQyMDE4NDA3MDQzLWMyZmIxNGZkNGVkNGFmMzE1MTgyOGNiZGY1ZmU1ZDQ3Mzk2ODBlZGJlODk3ZmI0OWNlZmI5MzQyZDJhYzg1NjE), [Twitter](https://twitter.com/ LaravelLiveIN)、[Facebook](https://www.facebook.com/laravellive/)、[Youtube](https://www.youtube.com/channel/UC6TxYSHI7g9FMJ7VlHk72Yg)
* [Laravel UK](https://laravelphp.uk/)、[Slack 註冊](https://laravelphp.uk/login/slack)
* [Laravel 俄羅斯](https://laravel.ru/) ([VK 群](http://m.vk.com/laravel_rus))
* [Laravel 法國](https://laravel.fr/)
* [Laravel 孟加拉國](https://www.facebook.com/groups/LaravelBanglaDesh/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook](https://www.facebook.com/groups/laravel/), [Telegram](https://t.me/ laravelindonesia))
* [Laravel 巴西](http://www.laravel.com.br/) ([Facebook](https://www.facebook.com/groups/laravelbrasil/), [Slack](http://slack. laravel.com.br), [Telegram](https://telegram.me/laravelbr), [GitHub](https://github.com/laravelbrasil), [Discord](https://discord.gg/9dpuWeZ ))
* [Laravel 土耳其](http://www.laravel.gen.tr/) ([Facebook](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel 尼日利亞](http://www.laravelnigeria.com/) ([Facebook](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel 中國](https://phphub.org/)
* [Laravel 台灣](https://laravel.tw/) ([Facebook](https://www.facebook.com/groups/laravel.tw/))
* [Laravel 西班牙語](http://laraveles.com/foro/)
* [Laravel 韓國](https://www.laravel.co.kr/) ([Facebook](https://www.facebook.com/groups/laravelkorea/))
* [Laravel 日本](http://laravel.jp/) ([Facebook](https://www.facebook.com/groups/laravel.jp/))
* [Laravel 馬來西亞](https://www.facebook.com/groups/laravel.my/)
* [Laravel 阿爾及利亞](https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel 希臘](http://www.laravel.gr) ([Facebook](https://www.facebook.com/laravelgr))
* [Laravel 中東](http://laravelme.com/) ([Facebook](https://www.facebook.com/laravelme))
* [Laravel 格魯吉亞](https://www.facebook.com/groups/laravel.georgia/)
* [Laravel 意大利](http://laravel-italia.it)
* [Laravel 越南](https://www.facebook.com/groups/vietnam.laravel/)
* [Laravel 斯洛文尼亞](https://www.facebook.com/groups/laravelslovenija/)
* [Laravel 匈牙利](https://laravel.hu)
* [Laravel 喀麥隆](https://laravelcm.com/) ([Slack](https://laravelcm.slack.com)、[GitHub](https://github.com/laravelcm)、[Facebook]( https://www.facebook.com/laravelcm), [推特](https://twitter.com/laravelcm))
* [Laravel 菲律賓](https://www.facebook.com/groups/laravelph)

##### 聚會

* [所有聚會](http://www.meetup.com/topics/laravel/)
* [倫敦聚會](https://www.meetup.com/London-Laravel/)
* [布宜諾斯艾利斯聚會](https://www.meetup.com/Laravel-Buenos-Aires/)
* [雅典-希臘聚會](https://www.meetup.com/athens-laravel-meetup/)
* [哥本哈根聚會](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [底特律聚會](https://www.meetup.com/Laravel-Detroit/)
* [巴黎聚會](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [墨爾本聚會](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [布達佩斯聚會](https://www.meetup.com/Laravel-Hungary-Meetup/)

＃＃ 工作

* [LaraJobs](https://larajobs.com/)
* [Laravel 大師](https://laravelgurus.com/)

## 託管開發工具

* [Laravel Shift](https://laravelshift.com/) - Laravel 項目的自動升級工具
* [Laravel Schema Designer](http://laravelsd.com/) - 創建、導出和共享數據庫模式
* [StyleCI](https://styleci.io) - PHP 編碼風格服務

＃＃ 各種各樣的

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - 付費腳本和插件
* [Laravel Collections](https://laravelcollections.com) - 每個 Laravel 開發者都轉到資源站點
* [LaravelLinks](https://telegram.me/laravellinks) - 一個電報頻道，致力於分享偉大的 Laravel 資源

## 貢獻

找到了很棒的包、博客、課程或視頻？向我發送拉取請求！

#### 準則

* 請為每個建議提出單獨的拉取請求
* 確保 Travis 測試通過你的拉取請求
* 對鏈接使用以下格式：\[Resource\]\(URL\)
* 想要推薦套餐？閱讀[貢獻指南](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* 歡迎新類別或對現有類別的改進

＃＃ 執照

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome Laravel 在 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) 下獲得許可。