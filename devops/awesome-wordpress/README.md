# Awesome WordPress
一個非常棒的 WordPress 資源、主題、插件和閃亮的東西的精選列表。

靈感來自 [awesome](https://github.com/sindresorhus/awesome) 和 [awesome-php](https://github.com/ziadoz/awesome-php)。

- [很棒的 WordPress](#awesome-wordpress)
	- [核心]（#核心）
	- [主題和框架](#themes-and-framework)
	- [古騰堡]（#古騰堡）
	- [插件](#plugins)
		- [特色插件](#featured-plugins)
		- [搜索引擎優化](#seo)
		- [開發](#dev-plugins)
		- [自定義帖子類型](#custom-post-type)
		- [安裝程序和生成器](#installer-and-generators)
		- [圖片和媒體庫](#images-and-media-gallery)
		- [性能]（#性能）
		- [電子商務](#e-commerce)
		- [安全和管理](#security-and-management)
		- [表單和模塊](#forms-and-modules)
		- [小部件](#widget)		
		- [移動和備份](#move-and-backup)
		- [營銷](#marketing)
		- [谷歌分析](#google-analytics)
	- [命令行](#commandline)
	- [資源](#resources)
		- [課程](#classes)
		- [主題定制器](#theme-customizer)
		- [網站](#websites)
		- [書籍](#books)
	- [貢獻](#contributing)

＃＃ 核

* [GitHub 上的 WordPress](https://github.com/WordPress/WordPress) - WordPress，Git 化。每 15 分鐘通過 SVN 同步一次，包括分支和標籤！
* [WordPress 編碼標準](https://make.wordpress.org/core/handbook/coding-standards/) - WordPress 編碼標準的目的是為 WordPress 開放的各個方面的協作和審查創建基線源項目和社區，從核心代碼到主題再到插件。
* [定制器 API](https://developer.wordpress.org/themes/advanced-topics/customizer-api/) - 定制器是實時預覽對 WordPress 的任何更改的框架。它為用戶提供了一個簡單而一致的界面，以自定義他們的主題和網站的各個方面，從顏色和佈局到小部件、菜單等等。主題和插件都可以向定制器添加自定義選項。定制器是為您的主題添加選項的規範方式。
* [自動化測試](https://make.wordpress.org/core/handbook/automated-testing/) - 這是運行和編寫 WordPress 測試的概述。自動化測試是運行測試用例，不需要手動干預來運行每個測試用例。這通常是編寫具有多個測試用例的測試套件以及運行測試套件或套件的庫和命令行工具的形式。測試套件的執行通常是手動的，開發人員可以在命令行上選擇要運行的套件，但這不是必需的。該過程可以自動化並不時進行檢查，以確保在代碼更改時不會引入任何問題。


## 主題和框架

* [_S](https://github.com/automattic/_s) - 嗨。我是一個名為 _s 或下劃線的入門主題，如果你願意的話。我是一個用於黑客攻擊的主題，所以不要將我用作父主題。相反，試著把我變成下一個最棒的 WordPress 主題。這就是我來這裡的目的。
* [Bones](http://themble.com/bones/) - 用於快速 WordPress 開發的 HTML5、移動優先啟動主題。
* [Sage](https://roots.io/sage/) - Sage 是一個基於 HTML5 Boilerplate、gulp、Bower 和 Bootstrap 的 WordPress 入門主題，它將幫助您製作更好的主題。
* [WordPlate](https://wordplate.github.io/) - WordPlate 試圖簡化圍繞 WordPress 開發的模糊性。
* [WP MVC](http://wpmvc.org/) - WP MVC 是一個 MVC 框架，它使 WordPress 開發更快、更容易、更優雅。它是一個成熟的框架，其約定類似於 Ruby on Rails 和 CakePHP
* [CherryFramework](https://github.com/CherryFramework/CherryFramework) - 完全響應式設計，易於安裝，穩定更新，大量短代碼和小部件，集成引導功能。Cherry Framework 為您帶來的所有內容，讓您在網站設計中獲得直接的體驗
* [Gantry Framework](https://github.com/gantry/gantry5) - 下一代主題框架。當 RocketTheme 開發團隊想要將我們廣泛的自定義 Joomla 和 WordPress 模板功能整合到一個簡單易用的框架中時，Gantry 就誕生了
* [Runway Framework](https://github.com/parallelus/Runway-Framework) - 創建 WordPress 主題的更好方法。Runway 是為創建 WordPress 主題而構建的，它包含 WordPress 開發人員定義的“主題框架”的兩個經典含義。但是 Runway 不僅僅是一個主題框架，Runway 是一個主題開發環境。
* [Kirki](http://kirki.org/) - Kirki 不是一個框架。這是一個工具包，允許 WordPress 開發人員使用定制器並通過抽象代碼來利用其高級功能和靈活性，並使每個人都可以更輕鬆地創建美麗而有意義的用戶體驗。
* [Wp 開發者主題](https://github.com/heitorspedroso/wp-developer-theme) - 這個主題被開發為開發者手中的快速工具，通過它開發者已經可以創建主題而無需擔心已經準備好的文件結構並且具有預定義的循環而不影響 html / css
* [HTML5 Blank](http://html5blank.com/) - HTML5 WordPress 樣板主題。
* [Odin WP](http://wpod.in/) - 由 WordPress Brasil Group 開發的基礎主題，用於幫助 WordPress 主題的敏捷開發。
* [Landing Pages](https://wordpress.org/support/plugin/landing-pages/) - 用於構建具有拆分測試功能的單頁演示文稿的框架。
* [Titan Framework](https://github.com/gambitph/Titan-Framework) - 最容易使用的 WordPress 選項框架。Titan Framework 允許主題和插件開發人員只需幾行簡單的代碼即可創建管理頁面、選項、元框和主題定制器選項。
* [create-wp-react-app](https://github.com/matzeeable/wp-reactjs-starter) - 使用 REST API、webpack、babel、MobX 和 MobX 生成下一個現代插件的 WordPress CLI狀態樹

##古騰堡
* [創建 Guten Block](https://github.com/ahmadawais/create-guten-block) - 用於構建 Gutenberg 塊插件的零配置工具包。
* [Gutenberg 自定義字段](https://github.com/youknowriad/gcf) - 在 Gutenberg 中創建自定義字段的插件。
* [Gutenberg 示例](https://github.com/WordPress/gutenberg-examples) - 塊的官方 WordPress 示例。
* [Gutenberg 手冊](https://wordpress.org/gutenberg/handbook/) - Gutenberg 的官方概述，WordPress 的新編輯器。
* [Gutenberg 遷移指南](https://github.com/danielbachhuber/gutenberg-migration-guide) - WP 開發人員通過顯示 Gutenberg 等效項將他們的主題和插件遷移到 Gutenberg 的指南。

* [Gutenblock](https://github.com/crossfield/gutenblock) - 用於創建塊插件的替代工具包。
*

## 插件

### 特色插件
*有機會成為 WordPress 核心的插件*

* [Shortcake](https://wordpress.org/plugins/shortcode-ui/) - 與 add_shortcode 一起使用，Shortcake 提供了一個用戶友好的界面，用於向帖子添加簡碼，並在內容編輯器中查看和編輯它.
* [Gutenberg](https://wordpress.org/plugins/gutenberg/) - 新的帖子和頁面構建體驗將使編寫豐富的帖子變得毫不費力，使今天可能需要短代碼、自定義 HTML 或“神秘”的事情變得容易肉”嵌入發現。

#### 搜索引擎優化

* [重定向](https://wordpress.org/plugins/redirection/) - 重定向是一個 WordPress 插件，用於管理 301 重定向並跟踪 404 錯誤，無需了解 Apache .htaccess 文件。
* [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - 改進您的 WordPress SEO：使用 Yoast SEO 插件編寫更好的內容並擁有一個完全優化的 WordPress 網站。
* [Broken Link Checker](https://wordpress.org/plugins/broken-link-checker/) - 此插件將監控您的博客以查找損壞的鏈接，並讓您知道是否找到任何鏈接。

#### 開發插件
*插件可以幫助您的工作流程*

* [主題檢查](https://wordpress.org/plugins/theme-check/) - 主題檢查插件是測試主題並確保其符合最新主題審查標準的簡單方法。有了它，您可以在您的主題上運行 WordPress.org 用於主題提交的所有相同的自動化測試工具。
* [查詢監視器](https://wordpress.org/plugins/query-monitor/) - 查詢監視器是 WordPress 的開發者工具面板。它支持調試數據庫查詢、PHP 錯誤、掛鉤和操作、塊編輯器塊、排隊腳本和样式表、HTTP API 調用等。
* [Posts 2 Posts](https://wordpress.org/plugins/posts-to-posts/) - 帖子、頁面、自定義帖子類型、用戶之間的高效多對多連接。
* [TGM Plugin Activation](tgmpluginactivation.com/) - TGM Plugin Activation 是一個 PHP 庫，可讓您輕鬆要求或推薦 WordPress 主題（和插件）的插件。它允許您的用戶使用原生 WordPress 類、函數和接口以單一或批量方式安裝甚至自動激活插件。您可以參考預打包的插件、來自 WordPress 插件庫的插件，甚至是託管在 Internet 上其他地方的插件。
* [Revisr](https://wordpress.org/plugins/revisr/) - Revisr 允許您使用 Git 存儲庫管理您的 WordPress 網站。使用 Git 存儲庫部署和管理 WordPress 的必備插件。
* [調試欄](http://wordpress.org/plugins/debug-bar/) - 向管理欄添加調試菜單，顯示查詢、緩存和其他有用的調試信息。
* [調試欄擴展器](http://wordpress.org/plugins/debug-bar-extender/) - 使用附加選項卡擴展調試欄插件，以測量檢查點和查找變量內容之間的運行時間。
* [WP Rollback](https://wordpress.org/plugins/wp-rollback/screenshots/) - 像老闆一樣回滾（或轉發）任何 WordPress.org 插件或主題。
* [會員](https://wordpress.org/plugins/members/) - 會員是一個插件，可以擴展您對博客的控制。它是一個用戶、角色和內容管理插件，旨在使 WordPress 成為更強大的 CMS。插件的基礎是其廣泛的角色和能力管理系統。這是所有當前功能和計劃的未來功能的支柱。
* [GitHub Updater](https://github.com/afragen/github-updater) - 一個簡單的插件，可以自動更新您的 GitHub、Bitbucket 或 GitLab 託管的 WordPress 插件和主題。它還允許遠程安裝插件或主題。
* [重寫規則檢查器](https://wordpress.org/plugins/rewrite-rules-inspector/) - 一個簡單的 WordPress 管理工具，用於檢查您的重寫規則。查看所有重寫規則的列表，查看哪些重寫規則與給定的 URL 匹配（以及它們匹配的優先級），或按不同的重寫規則源進行過濾。對重寫規則執行軟刷新以重新生成它們。
* [CMB2](https://wordpress.org/plugins/cmb2/) - CMB2 是 WordPress 的元框、自定義字段和表單庫，會讓您大吃一驚。
* [Ship](http://ship.getherbert.com/) - 在 GitHub 上標記一個版本並自動發送到官方 WordPress.org 插件 SVN
* [Simply Show Hooks](https://wordpress.org/plugins/simply-show-hooks/) - Simply Show Hooks 可幫助主題和插件開發人員快速查看所有操作和過濾器掛鉤在任何 WordPress 頁面上的位置。
* [WP Inspect](https://wordpress.org/plugins/wp-inspect/) - WP Inspect 插件使用在請求生命週期中調用的操作和過濾器（掛鉤）直觀地註釋頁面。
* [Timber](https://github.com/timber/timber) - 將 [Twig](http://twig.sensiolabs.org/doc/templates.html) 模板功能添加到您的主題並保持您的模板代碼分開從你的PHP。
* [子主題檢查](https://wordpress.org/plugins/child-theme-check/) - 警告您子主題中的過時模板文件，並顯示父子主題模板之間更改的差異視圖。
* [一鍵式子主題](https://wordpress.org/plugins/one-click-child-theme/) - 將主題選項添加到任何活動主題，允許您製作子主題。


### 自定義帖子類型

* [自定義帖子類型 UI](https://wordpress.org/plugins/custom-post-type-ui/) - 自定義帖子類型 UI 提供了一個易於使用的界面，用於為您的網站註冊和管理自定義帖子類型和分類法.
* [工具集類型](https://wordpress.org/plugins/types//) - 工具集類型讓您可以向 WordPress 管理員添加自定義帖子類型、自定義字段和自定義分類法。方便的儀表板可讓您從一個地方控制一切。
* [Pods](https://wordpress.org/plugins/pods/) - 使用 Pods 框架在一個位置管理所有自定義內容需求。您可以創建和編輯自定義帖子類型、分類法、字段並擴展現有的 WordPress 對象，如用戶、媒體、帖子和頁面，或擴展其他插件的自定義帖子類型——所有這些都來自 Pod。
* [WordPress Creation Kit](https://wordpress.org/plugins/wck-custom-fields-and-custom-post-types-creator/) - WordPress Creation Kit 包含三個工具，可以幫助您創建和維護自定義帖子類型、自定義分類法，最重要的是，您的帖子、頁面或 CPT 的自定義字段和元框。
* [MB 自定義帖子類型](https://wordpress.org/plugins/mb-custom-post-type/) - MB 自定義帖子類型通過提供管理區域中易於使用的界面。
* [自定義帖子類型固定鏈接](https://wordpress.org/plugins/custom-post-type-permalinks/) - 自定義帖子類型固定鏈接可讓您編輯自定義帖子類型的固定鏈接結構


#### 安裝程序和生成器

* [WP 快速安裝](http://wp-quick-install.com/) - WordPress 安裝可能很長：下載、解壓、上傳、插件和主題安裝。WP Quick Install 將處理所有這些事情。只需將這個小腳本上傳到您要安裝 WordPress 的位置
* [GenerateWP](http://generatewp.com/) - 使用最新的 WordPress 編碼標準和 API 為您的 WordPress 項目創建自定義和高質量代碼的最簡單和最快的方法。
* [FakerPress](https://wordpress.org/plugins/fakerpress/) - FakerPress 是一種為您的 WordPress 生成虛假內容的簡潔方式，非常適合需要測試的開發人員

#### 圖片和媒體庫
*所有關於媒體項目管理*

* [增強型媒體庫](https://wordpress.org/plugins/enhanced-media-library/) - 更好的WordPress媒體庫管理
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Imsanity 會自動調整巨大圖像上傳的大小。投稿人會上傳大照片嗎？厭倦了手動縮放？瘋狂拯救！
* [上傳後調整圖像大小](https://wordpress.org/plugins/resize-image-after-upload/) - 上傳時自動調整圖像大小的幕後插件，將大小限制在指定的最大 h/w 內. 使用標準的 WP 功能。
* [重新生成縮略圖](https://wordpress.org/plugins/regenerate-thumbnails/) - 重新生成縮略圖允許您重新生成圖像附件的縮略圖。如果您在之前上傳圖像後更改了任何縮略圖尺寸（通過設置 -> 媒體）或更改為具有不同特色帖子圖像尺寸的主題，這將非常方便。
* [啟用媒體替換](https://wordpress.org/plugins/enable-media-replace/) - 只需在媒體庫編輯視圖中上傳新文件即可替換附件文件。
* [多個帖子縮略圖](https://wordpress.org/plugins/multiple-post-thumbnails/) - 將多個帖子縮略圖添加到帖子類型。如果您曾經想要在帖子中使用多個特色圖片，那麼此插件適合您。
* [來自 FTP 的媒體](https://wordpress.org/plugins/media-from-ftp/) - 從已通過 FTP 上傳的文件註冊到媒體庫。
* [WP Tiles](https://wordpress.org/plugins/wp-tiles/) - 使用 WP Tiles 在 WordPress 網站的任何位置輕鬆添加漂亮的、完全可自定義的帖子磁貼或平鋪畫廊。
* [Wanna Isotope](https://wordpress.org/plugins/wanna-isotope/) - 一個插件，可輕鬆構建具有任何內容（帖子、頁面或自定義帖子類型）的同位素/砌體佈局。響應式網格，可過濾的內容。
* [寶麗來畫廊](https://wordpress.org/plugins/polaroid-gallery/) - 寶麗來畫廊是一個用於 WordPress 媒體庫的 CSS3 和 jQuery 圖像畫廊插件。它用於在當前頁面或帖子上將圖像疊加為寶麗來圖片，並使用 WordPress 媒體庫。使用寶麗來畫廊，您可以為您的博客文章添加獨特的視圖。寶麗來畫廊增添了昔日美好時光的感覺。
* [Fly Dynamic Image Resizer](https://wordpress.org/plugins/fly-dynamic-image-resizer/) - 通過動態生成自定義大小的圖像來減少磁盤空間和上傳時間。
* [Sirv Image CDN](https://wordpress.org/plugins/sirv/) - 使用 Sirv 的 Image CDN 即時優化和調整圖像大小。只需更改 URL 即可操作圖像。

＃＃＃＃ 表現

* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) - 簡單但有效的插件允許您廣泛清理 WordPress 數據庫並對其進行優化，而無需進行手動查詢。
* [P3](https://wordpress.org/plugins/p3-profiler/) - 此插件通過測量它們對您網站加載時間的影響來創建您的 WordPress 網站插件性能的配置文件。通常，由於插件配置不當或插件太多，WordPress 網站加載緩慢。通過使用 P3 插件，您可以縮小導致網站運行緩慢的任何因素。
* [插件加載過濾器](https://wordpress.org/plugins/plugin-load-filter/) - 雖然已經安裝了很多插件，如果你不想激活所有的頁面，你可以停用每個單獨頁面的不必要的插件。通過插件的過濾激活，可以加快顯示響應速度。
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) - Autoptimize 是一種有效的性能工具，通過優化 JS、CSS、圖像（包括延遲加載）、HTML 和 Google 字體來加速網站，異步 JS，刪除表情符號等。

＃＃＃＃ 電子商務

* [Hubaga](https://github.com/picocodes/hubaga/) - Hubaga 是一個面向開發者的輕量級電子商務插件。它有很多優化可以提高您的轉化率，例如單字段結帳和 instacheck。
* [Easy Digital Downloads](https://wordpress.org/plugins/easy-digital-downloads/) - Easy Digital Downloads 是一個完整的電子商務解決方案，用於以輕便、高性能且易於使用的插件銷售數字產品. Easy Digital Downloads 不是試圖提供所有功能，而是通過僅提供您需要的功能來簡單而完整地銷售數字產品。
* [WooCommerce](https://wordpress.org/plugins/woocommerce/) - 將您的 WordPress 網站轉變為純種電子商務商店。提供企業級質量和功能，以您可以信賴的名稱為後盾。對 WooCommerce 電子商務插件說“你好”。

#### 安全和管理
*反垃圾郵件，防止暴力破解，ecc*

* [GoodBye Captcha](https://wordpress.org/plugins/goodbye-captcha/) - 一個非常強大的反垃圾郵件插件，可以阻止垃圾郵件機器人而不會煩人的驗證碼圖像。
* [鎖定 WP 管理員](https://wordpress.org/plugins/lockdown-wp-admin/) - 鎖定 WP 管理員對入侵者隱藏管理和登錄屏幕。它可以隱藏 WordPress Admin (/wp-admin/) 和登錄 (/wp-login.php)
* [MainWP](https://mainwp.com/) - 自託管開源管理器，用於從一個位置維護您的 WordPress 站點。
* [隱形登錄頁面](https://www.wordpress.org/plugins/stealth-login-page/) - 在不編輯 .htaccess 文件的情況下保護您的儀表板——第一個完全阻止遠程機器人登錄請求的文件。
* [Antispam Bee](https://wordpress.org/plugins/antispam-bee/) - 告別在您的 WorddPress 博客或網站上評論垃圾郵件。Antispam Bee 有效地阻止垃圾郵件評論和引用，無需驗證碼。它免費、無廣告且符合歐洲數據隱私標準。
* [流](https://wordpress.org/plugins/stream/) - 流是跟踪 WordPress 網站上發生的內容更改的最簡單和最安全的方式，然後以組織精美的細節查看它們。
* [簡單登錄日誌](https://wordpress.org/plugins/simple-login-log/) - 此插件保留 WordPress 用戶登錄的日誌。提供用戶和日期過濾以及導出功能。
* [iThemes 安全性](https://wordpress.org/plugins/better-wp-security/) - 消除 WordPress 安全性的猜測。iThemes Security 在易於使用的 WordPress 安全插件中提供了 30 多種鎖定 WordPress 的方法。
* [Sucuri Security – 審計、惡意軟件掃描和安全強化](https://wordpress.org/plugins/sucuri-scanner/) - 它結合了以下功能：遠程惡意軟件掃描、文件完整性監控、安全活動審計、黑名單監控等。 .
* [Easy Updates Manager](https://wordpress.org/plugins/stops-core-theme-and-plugin-updates/) - Easy Updates Manager 是一個輕巧但功能強大的插件，可讓您管理所有類型的更新您的單個站點安裝或在 WordPress Multisite 中。憑藉大量設置為配置提供了無限可能，Easy Updates Manager 是任何想要控制其網站更新的人的明顯選擇。
* [Wordfence 安全 - 防火牆和惡意軟件掃描](https://wordpress.org/plugins/wordfence/) - Wordfence 包括一個端點防火牆和惡意軟件掃描程序，它們從頭開始構建以保護 WordPress。Web 應用程序防火牆可識別並阻止惡意流量。由一個 100% 專注於 WordPress 安全性的大型團隊構建和維護。惡意軟件掃描程序檢查核心文件、主題和插件是否存在惡意軟件、不良 URL、後門、SEO 垃圾郵件、惡意重定向和代碼注入。
* [CloudFlare WAF 和 CDN](https://www.cloudflare.com/integrations/wordpress/) = CloudFlare 為 WordPress、CDN 和 WordPress 站點的 DDOS 緩解提供託管 WAF（Web 應用程序防火牆）規則

＃＃＃＃ 儀錶盤

* [前端儀表板](https://wordpress.org/plugins/frontend-dashboard/) - 前端儀表板與大量自定義功能捆綁在一起，可以輕鬆自定義用戶配置文件、帖子、登錄、註冊、自定義角色自定義首頁。


#### 表單和模塊

* [Caldera Forms](https://wordpress.org/plugins/caldera-forms/) - 一種不同類型的 WordPress 表單構建器。借助基於響應式網格的直觀拖放界面和各種附加組件，借助 Caldera Forms，為您的 WordPress 網站創建在任何設備上看起來都很棒的表單從未如此簡單。
* [Ninja Forms](https://wordpress.org/plugins/ninja-forms/) - Ninja Forms 是構建 WordPress 網站所需的任何表單的最簡單方法。不再弄亂代碼或擔心編造的限制。使用非常強大的 Ninja Forms 框架提供的簡單拖放界面創建您想要的表單。

#### 小部件

* [小部件選項](https://wordpress.org/plugins/widget-options/) - 更好地控制小部件。在指定頁面和設備上輕鬆顯示或隱藏 WordPress 小部件和/或分配自定義對齊方式。
* [Widget Logic](https://wordpress.org/plugins/widget-logic/) - 這個插件為每個小部件提供了一個額外的控製字段，稱為“小部件邏輯”，可讓您控制小部件將出現的頁面。文本字段允許您使用 WP 的條件標籤或任何通用 PHP 代碼。
* [小部件輸出緩存](https://wordpress.org/plugins/widget-output-cache/) - 使用 PHP 輸出緩衝來提取小部件輸出並將其存儲到 WordPress 瞬態中以便更快地檢索。它還向小部件控件添加了一個複選框，以將其排除在緩存之外。


#### 移動和備份
*如果您需要移動安裝*

* [一體化 WP 遷移](https://wordpress.org/plugins/all-in-one-wp-migration/) - 該插件允許您導出數據庫、媒體文件、插件和主題。您可以在數據庫上應用無限的查找/替換操作，該插件還將修復查找/替換操作期間發生的任何序列化問題。
* [Duplicator](https://wordpress.org/plugins/duplicator/) - 將整個站點從一個位置複製、克隆、備份、移動和傳輸到另一個位置。
* [UpdraftPlus 備份和恢復](https://wordpress.org/plugins/updraftplus/) - UpdraftPlus 簡化了備份（和恢復）。備份到雲（Amazon S3（或兼容）、Dropbox、Google Drive、Rackspace Cloud、DreamObjects、FTP、Openstack Swift、UpdraftPlus Vault 和電子郵件）並單擊即可恢復。文件和數據庫的備份可以有單獨的計劃。
* [BackWPup](https://wordpress.org/plugins/backwpup/) - 備份插件 BackWPup Free 可用於保存您的完整安裝，包括 /wp-content/ 並將它們推送到外部備份服務，如 Dropbox， S3、FTP 等等，請參見下面的列表。使用單個備份 .zip 文件，您可以輕鬆恢復安裝。
* [MultiSite Clone Duplicator](https://wordpress.org/plugins/multisite-clone-duplicator/) - MultiSite Clone Duplicator 為您的網絡安裝添加了“複製站點”功能。它允許您將網絡中的任何站點克隆到一個新站點：可以復制所有數據、文件、用戶和角色。
* [WP-CFM](https://wordpress.org/plugins/wp-cfm/) - WP-CFM 允許您將數據庫配置複製到文件系統/從文件系統複製。無需複制整個數據庫即可輕鬆部署配置更改。WP-CFM 類似於 Drupal 的 Features 模塊。


＃＃＃＃ 營銷
* [Leads](https://wordpress.org/support/plugin/leads/) - 提供深入的訪客跟踪和列表收集+細分工具。
* [號召性用語](https://wordpress.org/support/plugin/cta/) - 為號召性用語、贊助廣告和數據收集工作提供模板驅動的廣告投放系統。

＃＃＃＃ 谷歌分析
* [Analytify](https://wordpress.org/plugins/wp-analytify/) - 用於 WordPress 的 Google Analytics Dashboard - Analytify 為 WordPress 中的任何地方（帖子、頁面和自定義帖子類型）提供簡單而完整的 Google Analytics
* [MonsterInsights](https://wordpress.org/plugins/google-analytics-for-wordpress/) - MonsterInsights，一個完整的 Google Analytics for WordPress 插件，簡單而強大。

＃＃ 命令行

* [WP-CLI](http://wp-cli.org/) - WP-CLI 是一組用於管理 WordPress 安裝的命令行工具。您無需使用網絡瀏覽器即可更新插件、設置多站點安裝等等。
* [WPScan](http://wpscan.org/) - WPScan 是一個黑盒 WordPress 漏洞掃描器。

＃＃ 資源

#### 主題定制器
* [多圖像控件](https://github.com/lucatume/multi-image-control) - 一個主題定制器控件，允許選擇和排序多個圖像。

#### 類
* [wp-custom-post-type-class](https://github.com/jjgrainger/wp-custom-post-type-class) - 用於輕鬆創建 Wordpress 自定義帖子類型的 PHP 類
* [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker) - 一個自定義的 WordPress 導航步行器類，使用 WordPress 內置的自定義主題在自定義主題中完全實現 Twitter Bootstrap 3.0+ 導航樣式在菜單管理器中。

＃＃＃＃ 知識
* [10up Engineering Best Practices](http://10up.github.io/Engineering-Best-Practices/) - 作為一家公司，我們努力提供能夠產生一流用戶體驗的網站和組件。為了提高效率，我們需要標準化我們使用什麼以及如何使用它。標準化我們的工具、框架、庫、樣式、版本控制甚至語言將使我們能夠更好地理解其他人項目的內部運作，並自己產生更好的解決方案。

#### 網站

* [Stackexchange](http://wordpress.stackexchange.com/) - WordPress 開發 Stack Exchange 是一個面向 WordPress 開發人員和管理員的問答網站。它是 100% 免費的，無需註冊。
* [Tom McFarlin](https://tommcfarlin.com/about/) - 專業 WordPress 開發的視角
* [Mark on WordPress](https://markjaquith.wordpress.com/) - WordPress 把食物放在我的桌子上。
* [WordPress 上的 Otto](http://ottopress.com/) - 你必須使用 Ottopress 才能獲得鮮榨的 Otto
* [Nacin](http://nacin.com/) - WordPress 首席開發人員
* [Konstantin Kovshenin](http://kovshenin.com/) - WordPress、Automattic 和開源
* [Automattic](http://automattic.com/) - 我們是 WordPress.com 背後的人，該網站每月提供超過 158 億個頁面，以及許多其他流行服務，例如 Akismet、Jetpack、和 VaultPress。我們堅信開源，我們的絕大多數工作都可以在 GPL 等許可下獲得。
* [WPChat](http://www.wpchat.com) - WordPress 討論的熱門論壇。
* [WordPress Tavern](https://wptavern.com/) - WPTavern 提供有關 Wordpress 及其生態系統的新聞和每周播客。
* [Quora](https://www.quora.com/topic/WordPress) - Quora 中針對 Wordpress 用戶和開發人員的問答。
* [Wordpress subreddit](https://www.reddit.com/r/Wordpress/) - 關於 WordPress 的新聞、文章和討論的 Subreddit。對於高級用戶，請嘗試 [ProWordpress subreddit](https://www.reddit.com/r/ProWordPress/)
#### 資源列表

* [Awesome WordPress by dropndot](https://github.com/dropndot/awesome-wordpress) - 令人敬畏的 WordPress 主題、插件和框架開發資源和 WordPress 社區的精選列表。
* [用於學習 WordPress 的編程社區策劃資源](https://hackr.io/tutorials/learn-wordpress)
* [wpmudev.org](http://premium.wpmudev.org/blog/35-resources-for-kick-ass-wordpress-developers/) -35+ 資源成為 Kick Ass WordPress 開發人員
* 【WordPress智能開發者工具箱】(http://code.tutsplus.com/tutorials/toolbox-of-the-smart-wordpress-developer-series-introduction--cms-23663) - WordPress的核心夠不夠為你？不，可能不是。幾乎所有時間，我們都會安裝 WordPress 插件和主題來幫助構建我們的網站。沒關係，因為 WordPress 並不是一個萬能的解決方案。我們確實需要額外的功能和設計元素，我們通過插件和主題來滿足我們的需求......等等。
* [Awesome WordPress Developer Tips](https://github.com/Mte90/awesome-wordpress-developer-tips) - 包含非常棒且現成的代碼、片段或示例的精選列表，沒有庫或外部包，適合開發人員使用。
* [由 WordPress 提供支持](https://github.com/minthemiddle/powered-by-wordpress) - 使用 WordPress 的 Alexa 排名前 100 萬的網站的精選列表，按類別和排名排序。
* [最佳 WordPress 託管服務提供商比較](https://thishosting.rocks/best-wordpress-hosting/) - 最佳 WordPress 託管服務提供商的詳細文章/比較。


## 書籍

* [深入了解 WordPress](https://digwp.com/book/) - 關於這個世界上最受歡迎的出版平台，有很多東西要學。從您學習 WordPress 的第一步到保護、自定義和維護您的網站到未來，本書包含了真正實用的信息。
* [WordPress 的故事](https://github.com/WordPress/book) - WordPress 的歷史和發展。這本書目前是第 1 版，由 Siobhan McKeown 撰寫，由 Krista Stevens 編輯，並收到了來自社區成員的有用請求。

## 貢獻

我們歡迎對這個很棒的列表做出任何貢獻！請向我們發送拉取請求。

* 對於貢獻，[fork 項目](https://github.com/miziomon/awesome-wordpress/fork)
* 要報告損壞的鏈接或想要刪除鏈接，[使用問題](https://github.com/miziomon/awesome-wordpress/issues)