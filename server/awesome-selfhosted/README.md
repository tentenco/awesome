# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https:// /img.shields.io/travis/awesome-selfhosted/awesome-selfhosted/master?label=link%20checks)](https://github.com/awesome-selfhosted/awesome-selfhosted/issues/2266)

自託管是在您自己的服務器上託管和管理應用程序的做法，而不是從 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve. html) 提供者。

這是 [免費](https://en.wikipedia.org/wiki/Free_software) 軟件 [網絡服務](https://en.wikipedia.org/wiki/Network_service) 和 [網絡應用程序](https ://en.wikipedia.org/wiki/Web_application），可以託管在您自己的服務器上。非自由軟件列在 [Non-Free](non-free.md) 頁面上。

請參閱 [貢獻](.github/CONTRIBUTING.md)。

--------------------


＃＃ 目錄

- [軟件](#software)
  - [分析](#analytics)
  - [存檔和數字保存 (DP)](#archiving-and-digital-preservation-dp)
  - [自動化](#automation)
  - [博客平台](#blogging-platforms)
  - [預訂和安排](#booking-and-scheduling)
  - [書籤和鏈接共享](#bookmarks-and-link-sharing)
  - [日曆和聯繫人](#calendar--contacts)
  - [日曆和聯繫人 - CalDAV 或 CardDAV 服務器](#calendar--contacts---caldav-or-carddav-servers)
  - [日曆和聯繫人 - CalDAV 或 CardDAV 基於 Web 的客戶端](#calendar--contacts---caldav-or-carddav-web-based-clients)
  - [通訊](#通訊)
  - [通信 - 自定義通信系統](#communication---custom-communication-systems)
  - [通訊 - 電子郵件](#communication---email)
  - [通訊 - 電子郵件 - 完整解決方案](#communication---email---complete-solutions)
  - [通信 - 電子郵件 - 郵件遞送代理](#communication---email---mail-delivery-agents)
  - [通信 - 電子郵件 - 郵件傳輸代理](#communication---email---mail-transfer-agents)
  - [通訊 - 電子郵件 - 郵件列表和時事通訊](#communication---email---mailing-lists-and-newsletters)
  - [通信 - 電子郵件 - Webmail 客戶端](#communication---email---webmail-clients)
  - [通訊 - IRC](#communication---irc)
  - [通信 - SIP](#communication---sip)
  - [通訊 - 社交網絡和論壇](#communication---social-networks-and-forums)
  - [通信 - XMPP](#communication---xmpp)
  - [通信 - XMPP - 服務器](#communication---xmpp---servers)
  - [通信 - XMPP - Web 客戶端](#communication---xmpp---web-clients)
  - [社區支持農業 (CSA)](#community-supported-agriculture-csa)
  - [會議管理](#conference-management)
  - [內容管理系統 (CMS)](#content-management-systems-cms)
  - [DNS](#dns)
  - [文檔管理](#document-management)
  - [文檔管理 - 電子書](#document-management---e-books)
  - [文檔管理 - 機構資料庫和數字圖書館軟件](#document-management---institutional-repository-and-digital-library-software)
  - [文檔管理 - 集成圖書館系統 (ILS)](#document-management---integrated-library-systems-ils)
  - [電子商務](#e-commerce)
  - [聯合身份驗證](#federated-identity--authentication)
  - [提要閱讀器](#feed-readers)
  - [文件傳輸與同步](#file-transfer--synchronization)
  - [文件傳輸 - 分佈式文件系統](#file-transfer---distributed-filesystems)
  - [文件傳輸 - 對象存儲和文件服務器](#file-transfer---object-storage--file-servers)
  - [文件傳輸 - 點對點文件共享](#file-transfer---peer-to-peer-filesharing)
  - [文件傳輸-單擊和拖放上傳]（#file-transfer---單擊--drag-n-drop-upload）
  - [文件傳輸 - 基於 Web 的文件管理器](#file-transfer---web-based-file-managers)
  - [遊戲](#games)
  - [網關和終端共享](#gateways-and-terminal-sharing)
  - [家譜](#genealogy)
  - [群件](#groupware)
  - [人力資源管理 (HRM)](#human-resources-management-hrm)
  - [物聯網 (IoT)](#internet-of-things-iot)
  - [知識管理工具](#knowledge-management-tools)
  - [學習和課程](#learning-and-courses)
  - [地圖和全球定位系統 (GPS)](#maps-and-global-positioning-system-gps)
  - [媒體流](#media-streaming)
  - [媒體流 - 音頻流](#media-streaming---audio-streaming)
  - [媒體流 - 多媒體流](#media-streaming---multimedia-streaming)
  - [媒體流 - 視頻流](#media-streaming---video-streaming)
  - [雜項](#雜項)
  - [資金、預算和管理](#money-budgeting--management)
  - [監控](#monitoring)
  - [筆記和編輯](#note-taking--editors)
  - [辦公套房](#office-suites)
  - [密碼管理器](#password-managers)
  - [Pastebins](#pastebins)
  - [個人儀表板](#personal-dashboards)
  - [照片和視頻畫廊](#photo-and-video-galleries)
  - [投票和事件](#polls-and-events)
  - [代理](#proxy)
  - [稍後閱讀列表](#read-it-later-lists)
  - [配方管理](#recipe-management)
  - [資源規劃](#resource-planning)
  - [資源計劃-企業資源計劃](#resource-planning---enterprise-resource-planning)
  - [搜索引擎](#search-engines)
  - [自託管解決方案](#self-hosting-solutions)
  - [軟件開發](#software-development)
  - [軟件開發-API管理](#software-development---api-management)
  - [軟件開發 - Bug Trackers](#software-development---bug-trackers)
  - [軟件開發-持續集成與部署](#software-development---continuous-integration--deployment)
  - [軟件開發 - 文檔生成器](#software-development---documentation-generators)
  - [軟件開發 - FaaS & Serverless](#software-development---faas--serverless)
  - [軟件開發 - IDE & 工具](#software-development---ide--tools)
  - [軟件開發-本地化](#software-development---localization)
  - [軟件開發-項目管理](#software-development---project-management)
  - [軟件開發 - UX 測試](#software-development---ux-testing)
  - [靜態站點生成器](#static-site-generators)
  - [狀態/正常運行時間頁面]（#status--uptime-pages）
  - [任務管理和待辦事項](#task-management--to-do-lists)
  - [票務](#ticketing)
  - [時間追踪器](#time-trackers)
  - [網址縮短器](#url-shorteners)
  - [VPN](#vpn)
  - [網絡服務器](#web-servers)
  - [維基](#wikis)
- [許可證列表](#list-of-licenses)
- [反特徵](#anti-features)
- [外部鏈接](#external-links)
- [貢獻](#contributing)
- [作者](#authors)
- [許可證](#license)

--------------------

＃＃ 軟件

### 分析

**[`^ 返回頂部 ^`](#)**

**請訪問[Awesome Analytics](https://github.com/0xnr/awesome-analytics)**

_相關：[個人儀表板](#personal-dashboards)_


### 存檔和數字保存 (DP)

**[`^ 返回頂部 ^`](#)**

_相關：[內容管理系統 (CMS)](#content-management-systems-cms)_

- [訪問內存 (AtoM)](https://www.accesstomemory.org/) - 基於 Web 的開源應用程序，用於在多語言、多存儲庫環境中進行基於標準的檔案描述和訪問。([Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)) `AGPL-3.0-only` `PHP`
- [ArchiveBox](https://archivebox.io/) - 自託管的 _wayback 機器_，可從您的書籤、瀏覽歷史記錄、RSS 提要或其他來源創建網站的 HTML 和屏幕截圖存檔。([源代碼](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python`
- [Archivematica](https://www.archivematica.org/) - 成熟的數字保存系統，旨在維護基於標準的、對數字對象集合的長期訪問。([Demo](https://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica))`AGPL-3.0-only``Python `
- [ArchivesSpace](https://archivesspace.org/) - 檔案信息管理應用程序，用於管理和提供對檔案、手稿和數字對象的 Web 訪問。([Demo](https://archivesspace.org/application/demo/), [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [CKAN](https://ckan.org) - CKAN 是一個製作開放數據網站的工具。([源代碼](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [集體訪問 - 普羅維登斯](https://collectiveaccess.org/) - 高度可配置的基於 Web 的框架，用於管理、描述和發現支持各種元數據標準、數據類型和媒體格式的數字和物理館藏。([源代碼](https://github.com/collectiveaccess/providence)) `GPL-3.0-only` `PHP`
- [Horahora](https://github.com/horahoradev/horahora) - Niconico、Bilibili 和 Youtube 的視頻託管網站和視頻存檔管理器。`麻省理工學院``去`


### 自動化

**[`^ 返回頂部 ^`](#)**

_相關：[物聯網 (IoT)](#internet-of-things-iot)_

- [加速文本](https://github.com/tokenmill/accelerated-text) - 自動生成多種自然語言描述的數據，其措辭和結構各不相同。`Apache-2.0` `Java`
- [Actionsflow](https://github.com/actionsflow/actionsflow) `⚠` - 免費的 Zapier/IFTTT 替代方案，供開發人員根據 Github 操作自動化您的工作流程。`MIT` `Docker/Nodejs`
- [ActiveWorkflow](https://github.com/automaticmode/active_workflow) - 基於軟件代理的智能流程和工作流自動化平台。`麻省理工學院``紅寶石`
- [Alltube](https://www.alltubedownload.net) - [youtube-dl](https://github.com/ytdl-org/youtube-dl) 的 Web 界面，這是一個下載視頻和音頻的程序[100 多個網站](https://ytdl-org.github.io/youtube-dl/supportedsites.html)。([源代碼](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- [AmIUnique](https://amiunique.org/) - 了解您在 Internet 上的可識別性（瀏覽器指紋識別工具）。([源代碼](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- [Baserow](https://baserow.io/) - 開源在線數據庫工具和 Airtable 替代品。無需技術經驗即可創建自己的數據庫。([源代碼](https://gitlab.com/bramw/baserow)) `MIT` `Python/Nodejs`
- [Beehive](https://github.com/muesli/beehive) - 靈活的事件和代理系統，允許您創建自己的代理來執行由事件和過濾器觸發的自動化任務。`AGPL-3.0` `Go`
- [betanin](https://github.com/sentriz/betanin/) - 您的 torrent 客戶端和音樂播放器的中間人音樂組織。基於 beets.io，類似於 Sonarr 和 Radarr。`GPL-3.0` `Python`
- [ChiefOnboarding](https://chiefonboarding.com) - 員工入職平台，允許您配置用戶帳戶並使用待辦事項、資源、文本/電子郵件/Slack 消息等創建序列！可作為門戶網站和 Slack 機器人使用。([源代碼](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Python`
- [CouchPotato](https://couchpota.to/) - CouchPotato 是一個自動的電影視頻庫管理器。以您想要的質量自動搜索、下載和處理 torrent/nzb。([源代碼](https://github.com/CouchPotato/CouchPotatoServer)) `GPL-3.0` `Python`
- [劇集](https://github.com/guptachetan1997/Episodes) `⚠` - 使用 django、bootstrap4 構建的自託管電視節目劇集跟踪器和推薦器。`麻省理工學院``Python`
- [Exadel CompreFace](https://exadel.com/solutions/compreface/) - 人臉識別系統，提供人臉識別、人臉檢測等人臉服務的REST API，可通過docker輕鬆部署。有適用於 Python 和 JavaScript 語言的 SDK。無需事先的機器學習技能即可使用。([源代碼](https://github.com/exadel-inc/CompreFace)) `Apache-2.0` `Docker/Java/Nodejs`
- [feed2toot](https://feed2toot.readthedocs.io/) - Feed2toot 解析 RSS 提要，提取最後的條目並將它們發送到 Mastodon。([源代碼](https://gitlab.com/chaica/feed2toot)) `GPL-3.0` `Python`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer 是一個 WSGI (Python3) 微型 Web 服務，它接受一個提要 URL 列表並返回一個新提要，該提要由每個給定的最近 n 個條目組成提要（返回 Atom、RSS 或 JSON）。([演示](https://mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- [耳機](https://github.com/rembo10/headphones) - NZB 和 Torrent 的自動音樂下載器，用 Python 編寫。它支持 SABnzbd、NZBget、Transmission、µTorrent、Deluge 和 Blackhole。`GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/) - 偵聽 ping 並在 ping 延遲時發送警報的 Django 應用程序。([源代碼](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter) - 將導出銀行文件轉換為兼容的 Homebank csv 的 Web 應用程序。([演示](https://binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5`
- [HRConvert2](https://github.com/zelon88/HRConvert2) - 具有基於會話的身份驗證、自動臨時文件維護和日誌記錄功能的拖放文件轉換服務器。`GPL-3.0` `PHP`
- [Huginn](https://github.com/huginn/huginn) - 允許您構建代理來監控和代表您行事。`麻省理工學院``紅寶石`
- [Kibitzr](https://kibitzr.github.io) - 具有強大集成的輕量級個人網絡助手。([源代碼](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [Krayin](https://krayincrm.com/) - 免費和開源的 Laravel CRM 應用程序。([源代碼](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian 是一個跟踪作者並獲取元數據以滿足您所有數字閱讀需求的程序。它結合使​​用 Goodreads Librarything 和可選的 GoogleBooks 作為作者信息和書籍信息的來源。`GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可以在您的服務器上運行的開源個人助理。([源碼](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Lidarr](https://lidarr.audio/) - Lidarr 是 Usenet 和 BitTorrent 用戶的音樂收藏管理器。([源代碼](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [美杜莎](https://pymedusa.com/) - 電視節目的自動視頻庫管理器。它會監視您最喜歡的節目的新劇集，當它們發佈時，它會發揮它的魔力。([源代碼](https://github.com/pymedusa/Medusa)) `GPL-3.0` `Python`
- [MetaTube](https://github.com/JVT038/MetaTube) `⚠` - 從 YouTube 自動下載音樂的 Web GUI 添加來自 Spotify、Deezer 或 Musicbrainz 的元數據。`GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - youtube-dl 的 Web GUI，支持播放列表。允許從數十個網站下載視頻。`AGPL-3.0` `Python/Nodejs/Docker`
- [nefarious](https://github.com/lardbit/nefarious) - 自動下載電影和電視節目的 Web 應用程序。`GPL-3.0` `Python`
- [NocoDB](https://www.nocodb.com/) - 將任何數據庫變成智能電子表格的無代碼平台。它可以被視為 Airtable 或 Smartsheet 的替代品。([源代碼](https://github.com/nocodb/nocodb)) `GPL-3.0` `Nodejs`
- [OliveTin](https://github.com/OliveTin/OliveTin) - OliveTin 是一個用於運行 Linux shell 命令的 Web 界面。`AGPL-3.0` `Go`
- [Patrowl](https://github.com/Patrowl/PatrowlManager) - 開源、智能和可擴展的安全運營編排平台。`AGPL-3.0` `Python`
- [Podgrab](https://github.com/akhilrex/podgrab) - 輕量級播客管理器和自動播客劇集下載器。它會為您監控播客，並在新劇集上線時自動下載。`GPL-3.0` `Docker/Go`
- [pyLoad](https://pyload.net/) - 輕量級、可定制且可遠程管理的下載器，適用於 Rapidshare.com 或 Uploaded.to 等一鍵式託管網站。([源代碼](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr 是 Sonarr 的獨立分支，經過重新設計，可通過 Usenet 和 BitTorrent 自動下載電影，à la Couchpotato。([源代碼](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [SickRage](https://www.sickrage.ca) - SickRage 是用於電視節目的自動視頻庫管理器。以您想要的質量自動搜索、下載和處理 torrent/nzb。([源代碼](https://github.com/SickRage/SickRage)) `GPL-3.0` `Python`
- [SiteInspector](https://www.getsiteinspector.com/) - 用於捕獲網站上的拼寫錯誤、語法錯誤、斷開鏈接和其他錯誤的基於 Web 的工具。([Demo](https://demo.getsiteinspector.com/reports), [Source Code](https://github.com/siteinspector/siteinspector)) `AGPL-3.0` `Ruby`
- [Sonarr](https://sonarr.tv/) - Usenet 和 BitTorrent 的自動電視節目下載器和管理器。它可以抓取、排序和重命名新劇集，並在質量更好的格式可用時自動升級已下載文件的質量。([源代碼](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [StackStorm](https://stackstorm.com) - StackStorm（又名 _IFTTT for Ops_）是用於自動修復、安全響應、故障排除、部署等的事件驅動自動化。包括規則引擎、工作流、具有 6000 多個操作和 ChatOps 的 160 個集成包。([源代碼](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - 與 aria2 下載器交互的界面。使用非常簡單，只需在任何網絡瀏覽器中下載並打開 index.html。([演示](https://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 用於在遠程服務器上啟動下載的簡單 youtube-dl REST API。`GPL-3.0` `Python`
- [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - 基於 youtube-dl 的受 Material Design 啟發的 YouTube 下載器。支持播放列表、質量選擇、搜索、黑暗模式等，所有這些都採用簡潔現代的設計。`麻省理工學院` `Nodejs`
- [Zenbot](https://github.com/DeviaVir/zenbot) - Zenbot 是一個輕量級、可擴展的人工智能交易機器人，適用於比特幣、以太幣、萊特幣等。`麻省理工學院` `Nodejs`
- [µTask](https://github.com/ovh/utask) - µTask 是一個自動化引擎，用於建模和執行在 yaml 中聲明的業務流程。`BSD-3-Clause` `Go`


### 博客平台

**[`^ 返回頂部 ^`](#)**

_相關：[靜態站點生成器](#static-site-generators)、[內容管理系統 (CMS)](#content-management-systems-cms)_

_另見：[WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 免費、開源項目，旨在開發高性能、功能豐富的博客託管軟件。([源代碼](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [博客](https://github.com/m1k1o/blog) - Facebook 風格的博客。免費、極其輕量級、單用戶且易於安裝。([演示](https://blog.m1k1o.net/)) `GPL-3.0` `PHP`
- [Blogotext](https://github.com/BlogoText/blogotext) - 用 PHP 和 SQLite 編寫的免費博客引擎。這為您提供了安裝過程中無與倫比的簡單性和出色的性能。`麻省理工學院` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - 在幾秒鐘內建立網站或博客的簡單應用程序。Bludit 使用平面文件（JSON 格式的文本文件）來存儲帖子和頁面。([Demo](https://demo.bludit.com/), [Source Code](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Cadmus](https://github.com/ldemafelix/cadmus) - Cadmus 是一個由 Markdown 提供支持的極其輕量級的平面文件博客平台。`麻省理工學院` `PHP`
- [Canvas](https://trycanvas.app/) - 一個 Laravel 發布平台。([源代碼](https://github.com/austintoddj/canvas)) `MIT` `PHP`
- [Castopod](https://castopod.org) - 一個播客管理託管平台，包括最新的播客 2.0 標準、自動 Fediverse 提要、分析、可嵌入播放器等。([源代碼](https://code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP`
- [Chyrp Lite](https://chyrplite.net) - 超棒的超輕量級博客引擎。([源代碼](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dante Stories](https://dante-stories.herokuapp.com/) - 使用 Ruby on Rails 構建的自託管 Medium 平台。([源代碼](https://github.com/michelson/dante-stories)) `MIT` `Ruby`
- [Dotclear](https://dotclear.org/) - 控制您的博客。([源代碼](https://hg.dotclear.org/dotclear)) `GPL-2.0` `PHP`
- [Formtools](https://formtools.org/) - 強大、靈活、免費和開源的 PHP/MySQL 腳本來管理您的表單和數據。([源代碼](https://github.com/formtools)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - 只是一個博客平台。([源碼](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 帶有降價編輯和內置 RSS 閱讀器的私人博客系統。([Demo](https://havenweb.org/demo.html), [Source Code](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [Hotglue](https://hotglue.me/) - Freehand CMS，允許直接在網絡瀏覽器中構建網站。它使用平面文件進行存儲並提供直觀的 GUI。([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPL-3.0` `PHP`
- [htmly](https://www.htmly.com/) - 無數據庫博客平台（平面文件博客）。([Demo](https://demo.htmly.com/), [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [已知](https://withknown.com/) - 協作社交發布平台。([源代碼](https://github.com/idno/known)) `Apache-2.0` `PHP`
- [Plume](https://joinplu.me/) - 基於 ActivityPub 的聯合博客引擎。([源代碼](https://github.com/Plume-org/Plume)) `AGPL-3.0` `Rust`
- [PluXml](https://pluxml.org) - 基於 XML 的博客/CMS 平台。([源代碼](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y) 是一個使用 Smarty 模板的高度可擴展和可定制的 PHP 博客引擎。([源代碼](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`


### 預訂和安排

**[`^ 返回頂部 ^`](#)**

_相關：[民意調查和事件]（#polls-and-events）_

- [Alf.io](https://alf.io/) - 開源訂票系統。([Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.com](https://cal.com/) - 開源在線預約調度系統。([Demo](https://app.cal.com/bailey), [Source Code](https://github.com/calcom/cal.com)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - 一個高度可定制的網絡應用程序，允許您的客戶通過網絡與您預約。([Demo](https://easyappointments.org/demo/), [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`


### 書籤和鏈接共享

**[`^ 返回頂部 ^`](#)**

- [dyu 書籤](https://github.com/dyu/bookmarks) - 由 leveldb 和 uWebSockets 提供支持的單線程/進程書籤應用程序。支持從 Delicious 和 Chrome 導入。([Demo](https://dyuproject.com/bookmarks/)) `Apache-2.0` `Java`
- [Espial](https://github.com/jonschoning/espial) - 一個基於 Web 的開源書籤服務器。`AGPL-3.0` `Haskell`
- [Firefox 帳戶服務器](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 這允許您託管自己的 Firefox 帳戶服務器。([源碼](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs, Java`
- [Firefox 同步服務器](https://github.com/mozilla-services/syncserver) - 同步 Firefox 書籤、密碼、歷史記錄、選項卡、首選項。`MPL-2.0` `Python`
- [Geekmarks](https://geekmarks.dmitryfrank.com/) - 個人書籤服務專注於使用分層標籤的速度和組織。([源代碼](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- [golinks](https://git.mills.io/prologic/golinks) - Web 應用程序，允許您通過將 Web 瀏覽器的默認搜索引擎指向正在運行的實例來創建智能書籤、命令和別名。類似於 bunny1 或 yubnub。([Demo](https://search.mills.io)) `MIT` `Go`
- [Hackershare](https://github.com/hackershare/hackershare) - 黑客的社交書籤網站。([Demo](https://hackershare.dev)) `MIT` `Ruby`
- [LinkAce](https://www.linkace.org/) - 帶有自動備份到 Internet 存檔、鏈接監控和完整 REST API 的書籤存檔。安裝是通過 Docker 完成的，或者作為一個簡單的 PHP 應用程序。([Demo](https://demo.linkace.org/), [Source Code](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `PHP`
- [鏈接](https://github.com/sissbruecker/linkding) - 極簡的書籤管理和快速乾淨的 UI。通過 Docker 簡單安裝，可以在您的 Raspberry Pi 上運行。([Demo](https://demo.linkding.link/)) `MIT` `Docker/Python/Nodejs`
- [龍蝦](https://lobste.rs) - 運行您自己的鏈接聚合站點。([源代碼](https://github.com/jcs/lobsters)) `BSD-3-Clause` `Ruby`
- [No Fuss Bookmarks](https://nofussbm.herokuapp.com/signup.html) - 非常簡單的軟件和服務，用於存儲專門為黑客設計的書籤（不需要花哨的界面，但需要漂亮的 API）。([源代碼](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- [Pinry](https://getpinry.com/) - 為想要保存、標記和共享圖像、視頻和網頁的人們提供的平鋪圖像板系統。([源代碼](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
- [回憶](https://github.com/kanishka-linux/reminiscence) - 自託管書籤和存檔管理器。`AGPL-3.0` `Python`
- [Shaarli](https://github.com/shaarli/Shaarli) - 個人的、極簡的、超快速的、無數據庫的書籤和鏈接共享平台。([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
- [Shiori](https://github.com/go-shiori/shiori) - 使用 Go 構建的簡單書籤管理器。`麻省理工學院``去`
- [ubookmark](https://ungleich.ch/u/projects/ubookmark/) - 啟用 LDAP 的書籤服務。([Demo](https://ipv6.blog), [Source Code](https://code.ungleich.ch/ungleich-public/ubookmark/)) `GPL-2.0` `Python`
- [unmark](https://unmark.it/) - 開源做鏈接的應用程序。([源代碼](https://github.com/cdevroe/unmark)) `MIT` `PHP`
- [xBrowserSync](https://www.xbrowsersync.org) - 用於在瀏覽器和設備之間同步瀏覽器數據的開源工具。([源代碼](https://github.com/xBrowserSync)) `MIT` `Nodejs`


### 日曆和聯繫人

**[`^ 返回頂部 ^`](#)**

_相關：[群件](#groupware)_

_另請參閱：[CalDAV 和 CardDAV 實現的比較 - 維基百科]（https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations）_


### 日曆和聯繫人 - CalDAV 或 CardDAV 服務器

**[`^ 返回頂部 ^`](#)**

- [Baïkal](https://sabre.io/baikal/) - 基於 sabre/dav 的輕量級 CalDAV 和 CardDAV 服務器。([源代碼](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [calypso](https://keithp.com/calypso/) - 基於 Python 的 CalDAV 和 CardDAV 服務器，來自 Radicale。([源代碼](https://keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- [DAViCal](https://www.davical.org/) - 使用 PostgreSQL 數據庫作為數據存儲的日曆共享服務器 (CalDAV)。([源代碼](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP`
- [Davis](https://github.com/tchapi/davis/) - 基於 Symfony 5 和 Bootstrap 4 的簡單、可 docker 化和完全可翻譯的 sabre/dav 管理界面，主要受 Baïkal 啟發。`麻省理工學院` `PHP`
- [DecSync CC](https://f-droid.org/packages/org.decsync.cc/) - 無服務器聯繫人，日曆同步使用您自己的文件同步方法即Syncthing，Nextcloud等（[源代碼]（https ://github.com/39aldo39/DecSyncCC)) `GPL-3.0` `Kotlin`
- [Etebase (EteSync)](https://www.etebase.com/) - 支持日曆和聯繫人數據的端到端加密和日誌式個人信息服務器，為自己的客戶提供服務。([源代碼](https://github.com/etesync/server)) `AGPL-3.0` `Python/Django`
- [Radicale](https://radicale.org/) - 簡單的日曆和聯繫人服務器，管理開銷極低。([源代碼](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- [SabreDAV](https://sabre.io/) - 開源 CardDAV、CalDAV 和 WebDAV 框架和服務器。([源代碼](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://www.xandikos.org/) - 開源 CardDAV 和 CalDAV 服務器，管理開銷最小，由 Git 存儲庫支持。([源代碼](https://github.com/jelmer/xandikos)) `GPL-3.0` `Python`


### 日曆和聯繫人 - CalDAV 或 CardDAV 基於 Web 的客戶端

**[`^ 返回頂部 ^`](#)**

- [AgenDAV](https://agendav.github.io/agendav/) - 具有豐富 AJAX 界面和共享日曆支持的多語言 CalDAV Web 客戶端。([源代碼](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- [Bloben](https://bloben.com) - CalDAV 網絡客戶端。([演示](https://demo.bloben.com/api/v1/users/login-demo?username=demo&password=Bg8v16a4q7gvC&redirect=https://demo.bloben.com/calendar?demo=true), [來源代碼](https://github.com/nibdo/bloben-app)) `AGPL-3.0` `Docker`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync 的官方基於 Web 的客戶端（即他們的 Web 應用程序）。([Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - 開源 CalDAV/CardDAV Web 客戶端實現。([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`


＃＃＃ 溝通

**[`^ 返回頂部 ^`](#)**


### 通信 - 自定義通信系統

**[`^ 返回頂部 ^`](#)**

- [BluetoothCommunicatorExample](https://github.com/niedev/BluetoothCommunicatorExample) - 藍牙 LE 聊天應用程序，用於在具有 P2P 架構的 android 設備之間進行通信。([客戶端](https://github.com/niedev/RTranslator)) `Apache-2.0` `Java`
- [Centrifugo](https://github.com/centrifugal/centrifugo) - 與語言無關的實時消息傳遞（Websocket 或 SockJS）服務器。([演示](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
- [Chaskiq](https://chaskiq.io) - 功能齊全的實時聊天、幫助中心和 CRM，作為 Intercom & Drift、Crisp 等的替代品。([源代碼](https://github.com/chaskiq/chaskiq)) `AGPL-3.0` `Ruby`
- [Chatwoot](https://www.chatwoot.com) - 自託管客戶溝通平台，替代對講和 Zendesk。([源代碼](https://github.com/chatwoot/chatwoot)) `MIT` `Ruby`
- [Cherry](https://github.com/rafael-santiago/cherry) - 微型網絡聊天服務器。`GPL-2.0` `Go`
- [Conduit](https://conduit.rs/) - 由 Matrix 提供支持的簡單、快速、可靠的聊天服務器。([源代碼](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Darkwire.io](https://github.com/darkwire/darkwire.io) - 端到端加密即時網絡聊天。`麻省理工學院` `Nodejs`
- [Element](https://element.io) - 適用於 Web、iOS 和 Android 的全功能 Matrix 客戶端。([源代碼](https://github.com/vector-im/element-web)) `Apache-2.0` `Javascript`
- [Enigma Reloaded](https://github.com/enigma-reloaded/enigma-reloaded) - 適用於任何平台的 DIY 消息和文件加密。`GPL-3.0` `Javascript`
- [Freenet](https://freenetproject.org/index.html) - 匿名共享文件、瀏覽和發布 _freesites_（只能通過 Freenet 訪問的網站）以及在論壇上聊天。([源代碼](https://github.com/freenet/fred)) `GPL-2.0` `Java`
- [Galene](https://galene.org/) - Galène（或 Galene）是一種視頻會議服務器（“SFU”），易於部署，需要適度的服務器資源。([源碼](https://github.com/jech/galene)) `MIT` `Go`
- [GNUnet](https://gnunet.org/) - 用於分散的點對點網絡的免費軟件框架。([源代碼](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 帶有 Android 和 CLI 客戶端的自託管通知服務器，類似於 PushBullet。([源代碼](https://github.com/gotify/server), [客戶端](https://github.com/gotify/android)) `MIT` `Go`
- [Hawkpost](https://hawkpost.co) - HawkPost 是一個網絡應用程序，可讓您創建獨特的鏈接，您可以與希望向您發送重要信息但不知道如何加密的人共享這些鏈接。該消息在他們的瀏覽器中被加密並發送到您的電子郵件地址。([源代碼](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- [Jam](https://jamshelf.com/) - Jam 是 Clubhouse 的開源替代品：用於與朋友和家人交談的私人音頻聊天室。([Demo](https://jam.systems/), [Source Code](https://github.com/jam-systems/jam)) `AGPL-3.0` `Docker/Node.js`
- [Jami](https://jami.net/) - 保護用戶隱私和自由的免費通用通信平台（原 GNU Ring）。([源代碼](https://git.ring.cx/savoirfairelinux/ring-project)) `GPL-3.0` `C++`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet 是一個開源 (MIT) WebRTC Javascript 應用程序，它使用 Jitsi Videobridge 提供高質量、可擴展的視頻會議。([源代碼](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC 兼容的選擇性轉發單元 (SFU)，允許多用戶視頻通信。([源代碼](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- [KChat](https://github.com/php-kchat/kchat) - 基於 PHP 的實時聊天應用程序。`Apache-2.0` `PHP`
- [LeapChat](https://github.com/cryptag/leapchat) - 短暫的、加密的、瀏覽器內的聊天室。`AGPL-3.0` `Javascript`
- [Lets-Chat](https://sdelements.github.io/lets-chat/) - 用 Node.js 編寫的自託管聊天套件。([源代碼](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
- [LibreNews](https://librenews.io/) - 去中心化和安全的突發新聞通知系統。([源代碼](https://github.com/milesmcc/LibreNews-Server/)) `GPL-3.0` `Python`
- [實時助手聊天](https://livehelperchat.com/) - 為您的網站提供實時支持聊天。([源碼](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [LiveKit](https://livekit.io/) - 帶有客戶端 SDK 的現代、可擴展的 WebRTC 會議平台。([Demo](https://livekit.io/playground), [Source Code](https://github.com/livekit/livekit-server)) `Apache-2.0` `Go`
- [Matrix 控制台 Web](https://matrix.org/docs/projects/client/matrix-console-web) - Web 客戶端旨在展示 Matrix 功能，以及 Matrix 標準的參考實現。([源代碼](https://github.com/matrix-org/matrix-angular-sdk)) `Apache-2.0` `Javascript`
- [Mattermost](https://mattermost.org/) - 開源、本地 Slack-alternative。它可以與 Gitlab 集成。([源代碼](https://github.com/mattermost/mattermost-server)) `AGPL-3.0/Apache-2.0` `Go`
- [MiAOU](https://miaou.dystroy.org/login) - 多房間持久聊天服務器。([源碼](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mibew](https://mibew.org) - Mibew Messenger 是一個用 PHP 和 MySQL 編寫的開源實時支持應用程序。它可以直接從您的網站實時提供一對一的聊天幫助。([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延遲、高質量的語音/文本聊天軟件。([源代碼](https://github.com/mumble-voip/mumble), [客戶端](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++`
- [Notifo](https://github.com/notifo-io/notifo) - 支持電子郵件、移動推送、Web 推送、SMS、消息傳遞和 javascript 插件的多渠道通知服務器。([源代碼](https://github.com/notifo-io/notifo)) `MIT` `C#`
- [ntfy](https://ntfy.sh/) - 使用 HTTP PUT/POST 將通知推送到手機或桌面，使用 Android 應用程序、CLI 和 Web 應用程序，類似於 Pushover 和 Gotify。([Demo](https://ntfy.sh/app), [Source Code](https://github.com/binwiederhier/ntfy), [Clients](https://github.com/binwiederhier/ntfy- android)) `Apache-2.0/GPL-2.0` `Go`
- [OTS](https://ots.fyi/) - 在瀏覽器中具有對稱 256 位 AES 加密的一次性秘密共享平台。([源代碼](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [Papercups](https://papercups.io/) - 一個用 Elixir 編寫的開源實時客戶聊天網絡應用程序。([Demo](https://app.papercups.io/demo), [Source Code](https://github.com/papercups-io/papercups)) `MIT` `Elixir`
- [PushBits](https://github.com/pushbits/server) - 自託管通知服務器，用於通過 Matrix 中繼推送通知，類似於 PushBullet 和 Gotify。`ISC``去`
- [pWS](https://github.com/soketi/pws) - pWS 是一個免費的、開源的 Pusher 插件替代方案。`麻省理工學院` `Nodejs`
- [Rallly](https://rallly.co) - Rallly 是 Doodle 的開源替代品，可讓您創建民意調查以對日期和時間進行投票。([源代碼](https://github.com/lukevella/Rallly)) `AGPL-3.0` `Nodejs`
- [RetroShare](https://retroshare.cc) - 安全和分散的通信系統。提供去中心化聊天、論壇、消息傳遞、文件傳輸。([源代碼](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Revolt](https://revolt.chat/) - Revolt 是一個使用現代網絡技術構建的用戶至上的聊天平台。([源代碼](https://github.com/revoltchat)) `AGPL-3.0` `Rust`
- [Rocket.Chat](https://rocket.chat/) - 類似於 Gitter.im 或 Slack 的團隊聊天解決方案。([源代碼](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
- [Screensy](https://github.com/screensy/screensy) - 簡單的點對點屏幕共享解決方案，用於與 WebRTC 共享您的屏幕。([演示](https://screensy.marijn.it)) `GPL-3.0` `Nodejs`
- [噓](https://github.com/smallwat3r/shhh) - 對電子郵件或聊天記錄保密，使用帶有密碼短語和到期日期的安全鏈接共享它們。`麻省理工學院``Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密和安全的聊天和應用平台 - 現在採用雙棘輪 E2E 加密。`AGPL-3.0` `Haskell`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2 是一種開源即時消息傳輸。它允許用戶即使在使用不同的 IM 網絡時也可以一起聊天。([源代碼](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Spreed](https://www.spreed.me/) - WebRTC 音頻/視頻通話、會議服務器和 Web 客戶端。([源代碼](https://github.com/strukturag/spreed-webrtc)) `AGPL-3.0` `Go`
- [StoneAge Messenger](https://cweb.gitlab.io/StoneAge.html) - 自託管的 Android Messenger，與 S3 兼容的存儲是唯一需要的後端。([源代碼](https://gitlab.com/cweb-repos/cweb-conversations), [客戶端](https://f-droid.org/en/packages/com.cweb.messenger/)) ` GPL-3.0` `Java`
- [Synapse](https://matrix.org/docs/projects/server/synapse) - [Matrix](https://matrix.org/) 的服務器，一種用於分散式持久通信的開放標準。([源代碼](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
- [Syndie](https://syndie.de) - Syndie 是一個用於運營分佈式論壇的自由系統。`CC0-1.0` `Java`
- [TextBelt](https://github.com/typpo/textbelt) `⚠` - 使用運營商特定網關免費發送短信且無廣告的外發 SMS API。`麻省理工學院``Javascript`
- [Tinode](https://github.com/tinode) - 即時通訊平台。Go 中的後端。客戶端：Swift iOS、Java Android、JS webapp、腳本化命令行；聊天機器人。([Demo](https://sandbox.tinode.co/), [Source Code](https://github.com/tinode/chat), [Clients](https://github.com/tinnode/webapp )) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 具有音頻和視頻聊天功能的分佈式安全信使。([源代碼](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-vide o-chat-with-tuber/) - 點對點視頻聊天有效。([源代碼](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- [Typebot](https://typebot.io) - Typebot 是一個對話式應用程序構建器，作為 Typeform 或 Landbot 的替代品。([源代碼](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir#wbo) - 用於在架構、繪圖和註釋上實時協作的網絡白板。([演示](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Wirow](https://github.com/wirow-io/wirow-server) - 一個功能齊全的自託管視頻網絡會議平台。`AGPL-3.0` `C`
- [ZeroNet](https://zeronet.io/) `⚠` - 使用比特幣密碼學和 BitTorrent 網絡的開放、免費和不可審查的網站。([源代碼](https://github.com/HelloZeroNet/ZeroNet)) `GPL-2.0` `Python`
- [Zulip](https://zulip.org) - Zulip 是一個功能強大的開源群聊應用程序。([源代碼](https://github.com/zulip/zulip)) `Apache-2.0/Other` `Python`


### 通訊 - 電子郵件

**[`^ 返回頂部 ^`](#)**


### 通信 - 電子郵件 - 完整的解決方案

**[`^ 返回頂部 ^`](#)**

郵件服務器的簡單部署，例如對於沒有經驗或不耐煩的管理員。

- [AnonAddy](https://anonaddy.com) - 用於創建別名的開源電子郵件轉發服務。([源代碼](https://github.com/anonaddy/anonaddy)) `MIT` `PHP`
- [DebOps](https://docs.debops.org/) - 您基於 Debian 的數據中心在一個盒子裡。一組通用 Ansible 角色，可用於管理 Debian 或 Ubuntu 主機。([源代碼](https://github.com/debops/debops)) `GPL-3.0-only` `YAML/Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生產就緒的全棧但簡單的郵件服務器（SMTP、IMAP、LDAP、反垃圾郵件、防病毒等）正在運行一個容器內。只有配置文件，沒有 SQL 數據庫。([源碼](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [emailwiz](https://github.com/LukeSmithxyz/emailwiz) - Luke Smith 的 bash 腳本，用於在 debian 上完全自動化 Postfix/Dovecot/SpamAssassin/OpenDKIM 服務器的設置。`GPL-3.0` `Bash`
- [Excision Mail](https://github.com/Excision-Mail/Excision-Mail) - 全棧，基於 OpenSMTPD 的安全郵件服務器，用於使用 ansible 的 OpenBSD。`ISC` `Shell/Ansible`
- [homebox](https://github.com/progmaticltd/homebox) - Ansible 腳本套件，用於在 Debian 上部署功能齊全的郵件服務器。盡可能不顯眼和自動化，注重穩定性和安全性。`GPL-3.0` `外殼`
- [Inboxen](https://inboxen.org) - Inboxen 是一項為您提供無限數量的獨特收件箱的服務。([源代碼](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基於 Postfix 和 Dovecot 的全功能郵件服務器解決方案。([源代碼](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy 郵件服務器](https://github.com/foxcpp/maddy) - 實現 SMTP（MTA 和 MX）和 IMAP 的一體化郵件服務器。用單個守護程序替換 Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。`GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 使用一個命令將任何 Ubuntu 服務器變成功能齊全的郵件服務器。([源代碼](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基於 Dovecot、Postfix 和其他開源軟件的郵件服務器套件，為管理提供現代 Web UI。([源代碼](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - Mailu 是一個簡單但功能齊全的郵件服務器，作為一組 Docker 鏡像。([源碼](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - Modoboa 是一個郵​​件託管和管理平台，包括現代和簡化的 Web 用戶界面。([源代碼](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Ptorx](https://github.com/xyfir/ptorx) - 電子郵件隱私。通過別名轉發匿名發送和接收。`GPL-3.0` `Nodejs`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生態系統的完整郵件服務器解決方案。`GPL-3.0` `尼克斯`
- [SimpleLogin](https://simplelogin.io) - 用於保護您的電子郵件地址的開源電子郵件別名解決方案。附帶瀏覽器擴展和移動應用程序。([源代碼](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [wildduck](https://wildduck.email/) - 可擴展的無單點故障 IMAP/POP3 郵件服務器。([源代碼](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Nodejs`


### 通信 - 電子郵件 - 郵件遞送代理

**[`^ 返回頂部 ^`](#)**

MDA - IMAP/POP3 軟件

- [Cyrus IMAP](https://www.cyrusimap.org/) - 電子郵件 (IMAP/POP3)、聯繫人和日曆服務器。([源代碼](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [Dovecot](https://www.dovecot.org/) - IMAP 和 POP3 服務器主要考慮安全性而編寫。([源代碼](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
- [MailForm](https://github.com/Feuerhamster/mailform) - Formspree 和 SendGrid 的輕量級自託管開源替代方案。`Apache-2.0` `Nodejs`
- [Piler](https://www.mailpiler.org/wiki/start) - 功能豐富的開源電子郵件歸檔解決方案。([源代碼](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`


### 通信 - 電子郵件 - 郵件傳輸代理

**[`^ 返回頂部 ^`](#)**

MTA / SMTP 服務器

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 專注於簡單、安全和易於操作的 SMTP（電子郵件）服務器。([源代碼](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可擴展的企業郵件/群件服務器，提供 ESMTP、IMAP、POP3、網絡郵件、郵件列表、基本的基於網絡的日曆和日程安排服務。([源代碼](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C`
- [Exim](https://www.exim.org/) - 劍橋大學開發的消息傳輸代理 (MTA)。([源代碼](https://git.exim.org/exim.git)) `GPL-3.0` `C`
- [Haraka](https://haraka.github.io/) - 用 Ja​​vascript 編寫的高性能、可插入的 SMTP 服務器。([源代碼](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- [MailCatcher](https://mailcatcher.me/) - Ruby gem，它部署了一個簡單的 SMTP MTA 網關，接受所有郵件並顯示在 Web 界面中。對調試或開發很有用。([源代碼](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [Maildrop](https://gitlab.com/markbeeson/maildrop) - 一次性電子郵件 SMTP 服務器，對開發也很有用。`麻省理工學院``斯卡拉`
- [MailHog](https://github.com/mailhog/MailHog) - 運行 SMTP MTA 網關的小型 Golang 可執行文件，該網關接受所有郵件並顯示在 Web 界面中。對調試或開發很有用。`麻省理工學院``去`
- [OpenSMTPD](https://opensmtpd.org/) - 來自 OpenBSD 項目的安全 SMTP 服務器實現。([源碼](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- [Postfix](http://www.postfix.org/) - 快速、易於管理和安全的 Sendmail 替換。`IPL-1.0` `C`
- [Qmail](https://cr.yp.to/qmail.html) - 安全的 Sendmail 替換。([源代碼](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 郵件傳輸代理 (MTA)。`發送郵件` `C`
- [Slimta](https://www.slimta.org) - 基於 Python 構建的郵件傳輸庫。([源代碼](https://github.com/slimta/python-slimta)) `MIT` `Python`


### 通信 - 電子郵件 - 郵件列表和時事通訊

**[`^ 返回頂部 ^`](#)**

郵件列表服務器和群發郵件軟件 - 一封郵件發送給多個收件人。

- [Dada Mail](https://dadamailproject.com/) - 基於網絡的列表管理系統，可用於公告列表和/或討論列表。([源代碼](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- [HyperKitty](https://wiki.list.org/HyperKitty) - 開源 Django 應用程序，提供訪問 GNU Mailman v3 檔案的 Web 界面。([Demo](https://lists.mailman3.org/), [Source Code](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 自託管可靠且易於使用的通訊工具。Mailchimp 或 Sendinblue 等專有服務的替代方案。([Demo](https://app.keila.io), [Source Code](https://github.com/pentacent/keila)) `AGPL-3.0` `Elixir`
- [Listmonk](https://listmonk.app/) - 具有現代儀表板的高性能、自託管通訊和郵件列表管理器。([源代碼](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go`
- [Mailman](https://www.gnu.org/software/mailman/) - Gnu 郵件列表服務器。`GPL-3.0` `Python`
- [Mailtrain](https://mailtrain.org/) - 自託管通訊應用程序。([源碼](https://github.com/Mailtrain-org/mailtrain)) `GPL-3.0` `Nodejs`
- [MailyHerald](https://mailyherald.org/) - 自託管 Mailchimp 替代方案，您可以輕鬆地與您的網站集成。幫助您發送和管理您的申請郵件。它支持電子郵件營銷和執行您發送給用戶的每日通知流。([源代碼](https://github.com/Sology/maily_herald)) `LGPL-3.0` `Ruby`
- [Mautic](https://www.mautic.org/) - Mautic 是營銷自動化軟件（電子郵件、社交等）。([源代碼](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [phpList](https://phplist.org) - 對訂閱者、退回和插件進行高級管理的時事通訊和電子郵件營銷。([源代碼](https://github.com/phpList/)) `AGPL-3.0` `PHP`
- [郵政](https://postal.atech.media/) - 功能齊全的開源郵件傳遞平台，用於收發電子郵件。([源代碼](https://github.com/postalhq/postal)) `MIT` `Ruby`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 訪問 GNU Mailman 的 Web 用戶界面。([源代碼](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 具有重新發送功能的啟用 GPG 的郵件列表管理器。([源代碼](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.org/) - 郵件列表管理器。`GPL-2.0` `Perl`


### 通信 - 電子郵件 - Webmail 客戶端

**[`^ 返回頂部 ^`](#)**

- [Afterlogic WebMail Lite](https://afterlogic.org/webmail-lite) - 用於現有 IMAP 郵件服務器、Plesk 或 cPanel 的快速且易於使用的 webmail 前端。([Demo](https://lite.afterlogic.com/), [Source Code](https://github.com/afterlogic/webmail-lite)) `AGPL-3.0` `PHP`
- [Cypht](https://cypht.org) - 您的電子郵件帳戶的供稿閱讀器。([源代碼](https://github.com/jasonmunro/cypht)) `LGPL-2.1` `PHP`
- [IMP](https://www.horde.org/apps/imp/) - 提供對 IMAP 和 POP3 帳戶的網絡郵件訪問的 HORDE 應用程序。([Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)) `GPL-2.0` `PHP`
- [Isotope Mail](https://blog.marcnuri.com/isotope-mail-client-introduction/) - 使用 ReactJS 和 Spring 構建的基於微服務的 webmail 客戶端。([源代碼](https://github.com/manusa/isotope-mail)) `Apache-2.0` `Docker/Java`
- [MailCare](https://mailcare.io) - 開源一次性電子郵件地址服務。([源碼](https://github.com/mailcare/mailcare)) `MIT` `PHP`
- [Mailpile](https://www.mailpile.is/) - 具有搜索、過濾、加密等功能的 Webmail 客戶端。([源代碼](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- [Roundcube](https://roundcube.net) - 基於瀏覽器的 IMAP 客戶端，具有類似應用程序的用戶界面。([源代碼](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP`
- [SnappyMail](https://snappymail.eu/) - 簡單、現代、輕量級和快速的基於 Web 的電子郵件客戶端。（它是 RainLoop 的一個積極開發的分支）。([Demo](https://snappymail.eu/demo/), [Source Code](https://github.com/the-djmaze/snappymail)) `AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一個基於瀏覽器的 IMAP 客戶端。([源代碼](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/))​​ `GPL-2.0` `PHP`


### 交流 - IRC

**[`^ 返回頂部 ^`](#)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) 通訊軟件

- [Convos](https://convos.chat/) - 始終在線的網絡 IRC 客戶端。([Demo](https://convos.chat/#instant-demo), [Source Code](https://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
- [Dispatch](https://github.com/khlieng/dispatch) - 用 Go 編寫的自託管 Web IRC 客戶端。([Demo](https://dispatch.khlieng.com/connect)) `MIT` `Go`
- [Ergo](https://ergo.chat/) - 用 Go 編寫的現代 IRCv3 服務器，結合了 ircd、服務框架和保鏢的功能。([源碼](https://github.com/ergochat/ergo)) `MIT` `Go`
- [發光熊](https://github.com/glowing-bear/glowing-bear/) - WeeChat 的 Web 前端。([演示](https://www.glowing-bear.org)) `GPL-3.0` `Javascript`
- [InspIRCd](https://www.inspircd.org/) - 用 C++ 為 Linux、BSD、Windows 和 macOS 編寫的模塊化 IRC 服務器。([源代碼](https://github.com/inspircd/inspircd)) `GPL-2.0-only` `C++`
- [Kiwi IRC](https://kiwiirc.com/) - 具有主題支持的響應式 Web IRC 客戶端。([Demo](https://kiwiirc.com/nextclient/), [Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 適用於小型或專用網絡的免費、便攜和輕量級 Internet 中繼聊天服務器。([源代碼](https://github.com/ngircd/ngircd)) `GPL-2.0` `C`
- [Quassel IRC](https://quassel-irc.org/) - 分佈式 IRC 客戶端，意味著一個（或多個）客戶端可以連接到中央核心或從中央核心分離。([源代碼](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - RobustIRC 是沒有 netsplits 的 IRC。分佈式 IRC 服務器，基於 RobustSession 協議。([源代碼](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [休息室](https://thelounge.chat/) - 自託管網絡 IRC 客戶端。([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/thelounge)) `MIT` `Nodejs`
- [Tiny Tiny IRC](https://tt-rss.org/tt-irc/) - 一個支持 IRC 的開源 AJAX 驅動的聊天平台 ([Source Code](https://git.tt-rss .org/fox/tt-irc))。`GPL-3.0` `PHP/Java`
- [UnrealIRCd](https://www.unrealircd.org/) - 用 C 語言編寫的模塊化、高級和高度可配置的 IRC 服務器，適用於 Linux、BSD、Windows 和 macOS。([源碼](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [Weechat](https://weechat.org/) - 快速、輕便且可擴展的聊天客戶端。`GPL-3.0` `C`
- [ZNC](https://wiki.znc.in/ZNC) - 高級 IRC 保鏢。([源代碼](https://github.com/znc/znc)) `Apache-2.0` `C++`


### 通信 - SIP

**[`^ 返回頂部 ^`](#)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) 電話軟件

- [Asterisk](https://www.asterisk.org/) - 易於使用但先進的 IP PBX 系統、VoIP 網關和會議服務器。`GPL-2.0` `C`
- [ASTPP](https://www.astppbilling.org/) - 是 Freeswitch 的開源 VoIP 計費解決方案。它支持帶有呼叫評級和信用控制的預付費和後付費計費。它還提供了許多其他功能。([源代碼](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- [Eqi​​vo](https://eqivo.org/) - Eqivo 在 FreeSWITCH 之上實現 API 層，促進 Web 應用程序和支持語音/視頻的端點（例如傳統電話線 (PSTN)、VoIP 電話、webRTC 客戶端）之間的集成等（[源代碼]（https://github.com/rtckit/eqivo））`MIT``PHP`
- [Freepbx](https://www.freepbx.org) - 控制和管理 Asterisk 的基於 Web 的開源 GUI。([源代碼](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可擴展的開源跨平台電話平台。([源代碼](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 開源項目，為名為 FreeSWITCH 的非常強大且高度可擴展的多平台語音交換機提供可定制且靈活的 Web 界面。([源碼](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模塊化 SIP 服務器（註冊商/代理/路由器/等）。([源代碼](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- [Kazoo](https://2600hz.org/) - KAZOO 是一個開源、高度可擴展的軟件平台，旨在提供運營商級的 VoIP 交換機功能和特性。([源碼](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - 使用 ZRTP 加密保護 SIP 電話設置。`GPL-3.0` `Ruby`
- [Routr](https://routr.io) - 輕量級 sip 代理、位置服務器和註冊器，用於可靠且可擴展的 SIP 基礎設施。([源代碼](https://github.com/fonoster/router)) `MIT` `Javascript`
- [SIP3](https://sip3.io/) - VoIP 故障排除和監控平台。([Demo](https://demo.sip3.io), [Source Code](https://github.com/sip3io/)) `Apache-2.0` `Kotlin`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - 故障排除和監控 VoIP 呼叫。([源代碼](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- [SipXcom](https://sipxcom.org/) - 開源統一通信系統。([源代碼](https://github.com/sipXcom/sipxecs)) `AGPL-3.0` `Java`
- [Wazo](https://wazo-platform.org/) - 基於 Asterisk 構建的全功能 IPBX 解決方案，具有集成的 Web 管理界面和 REST-ful API。([源代碼](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 具有集成計費和路由引擎以及 REST API 的 Transit class4 軟交換 (SBC)。([Demo](https://yeti-switch.org/demo.html), [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 交流 - 社交網絡和論壇

**[`^ 返回頂部 ^`](#)**

- [Abilian SBE](https://github.com/abilian/abilian-sbe) - 開源協作和社交網絡框架和平台。`LGPL-2.1` `Python`
- [Anahita](https://www.getanahita.com/) - 開源社交網絡框架和平台。([源代碼](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- [AsmBB](https://board.asm32.info) - 一個用 ASM 編寫的快速、基於 SQLite 的論壇引擎。([源代碼](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [bbPress](https://bbpress.org/) - bbPress 是一個論壇軟件，由 WordPress 的創建者提供。在您的 WordPress.org 網站內輕鬆設置討論論壇。([源代碼](https://bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- [參考書目](https://bibliogram.art) `⚠` - Instagram 的替代前端。([源代碼](https://sr.ht/~cadence/bibliogram/)) `AGPL-3.0` `Nodejs`
- [Bootcamp](https://trybootcamp.vitorfs.com) - 企業社交網絡。([源代碼](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- [Buddycloud](http://buddycloud.com/) - 工具、庫、服務和社區，用於在您的應用程序中構建用戶對用戶、群組和社交消息。節省時間。擴大規模。支持你。([源碼](https://github.com/buddycloud)) `Apache-2.0` `Java`
- [BuddyPress](https://buddypress.org/about/) - 強大的插件，讓您的 WordPress.org 支持的網站超越博客，具有社交網絡功能，如用戶個人資料、活動流、用戶組等。([源代碼](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Cactus Comments](https://cactus.chat/) - Cactus Comments 是一個基於 Matrix 的開放網絡聯合評論系統。([Demo](https://cactus.chat/demo/), [Source Code](https://gitlab.com/cactus-comments/)) `GPL-3.0` `Python`
- [cartuary](https://github.com/daveajones/cartuary) - RSS 閱讀器、可讀性工具、文章存檔器、微博、社交圖管理器和閱讀列表管理器。`CDDL-1.0` `PHP`
- [Commento](https://gitlab.com/commento/commento) - Commento 是一個討論平台，您可以將其嵌入您的博客、新聞文章以及您希望讀者添加評論的任何地方。`麻省理工學院``去`
- [Coral](https://coralproject.net/) - 來自 Vox Media 的更好的評論體驗。([源代碼](https://github.com/coralproject/talk)) `Apache-2.0` `Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分佈式社交網絡服務器。([源代碼](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基於 Ruby 和 JS 的高級論壇/社區解決方案。([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Ruby`
- [dyu 評論](https://github.com/dyu/comments) - 由 leveldb 提供支持的實時、啟用降價的評論引擎。([演示](https://dyu.github.io/comments/real-time/)) `Apache-2.0` `Java`
- [Elgg](https://elgg.org/) - 強大的開源社交網絡引擎。([源代碼](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - Enigma 1/2 是一個現代的、多平台的 BBS 引擎，具有無限的“來電者”和傳統的 DOS 門遊戲支持。([Demo](https://l33t.codes/xibalba-bbs/), [Source Code](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Nodejs/Javascript `
- [EpochTalk](https://github.com/epochtalk/epochtalk) - 下一代論壇軟件。`麻省理工學院` `Nodejs`
- [Flarum](https://flarum.org) - 非常簡單的論壇。Flarum 是下一代論壇軟件，它讓在線討論再次變得有趣。([源代碼](https://github.com/flarum/flarum)) `MIT` `PHP`
- [FlaskBB](https://flaskbb.org/) - FlaskBB 是使用微框架 Flask 用 Python 編寫的論壇軟件。您可以輕鬆創建新主題、帖子和向其他用戶發送私人消息。它還包括基本的管理和審核工具。([源代碼](https://github.com/flaskbb/flaskbb)) `BSD-3-Clause` `Python`
- [FluxBB](https://fluxbb.org/) - 適用於您網站的快速、輕便、用戶友好的論壇軟件。([源代碼](https://github.com/fluxbb/fluxbb)) `GPL-2.0` `PHP`
- [Friendica](https://friendi.ca/) - 社交通訊服務器。([源代碼](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [Glosa](https://github.com/glosa/glosa-server) - 開源評論系統，易於與靜態頁面集成。您可以從 Disqus 導入。`GPL-3.0` `Java`
- [GNU social](https://gnu.io/social/) - 用於公共和私人通信的社交通信軟件。([源代碼](https://notabug.org/diogo/gnu-social)) `AGPL-3.0` `PHP`
- [Gosora](https://gosora-project.com/) - Gosora 是一個用 Go 編寫的超快速和安全的論壇軟件，它平衡了可用性和功能性。([源代碼](https://github.com/Azareal/Gosora)) `GPL-3.0` `Go`
- [Hubzilla](https://hubzilla.org) - 去中心化的身份、隱私、發布、共享、雲存儲和通信/社交平台。([源代碼](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用於私人社交網絡的靈活工具包。([源代碼](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Isso](https://posativ.org/isso/) - 用 Python 和 Javascript 編寫的輕量級評論服務器。它旨在成為 Disqus 的替代品。([源代碼](https://github.com/posativ/isso)) `MIT` `Python`
- [Lemmy](https://join-lemmy.org/) - Fediverse 的鏈接聚合器/reddit 克隆。Reddit 替代品內置於 Rust。([源代碼](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Rust`
- [Libreddit](https://libredd.it/) `⚠` - 用 Rust 編寫的 Reddit 私有前端。([源代碼](https://github.com/spikecodes/libreddit)) `AGPL-3.0` `Rust`
- [Loomio](https://www.loomio.org/) - Loomio 是一種協作決策工具，任何人都可以輕鬆參與影響他們的決策。([源代碼](https://github.com/loomio/loomio)) `AGPL-3.0` `Ruby`
- [Mastodon](https://joinmastodon.org/) - 聯合微博服務器，GNU 社交的替代品。([源代碼](https://github.com/tootsuite/mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - Misago 是功能齊全的現代論壇應用程序，它快速、可擴展且響應迅速。([源代碼](https://github.com/rafalp/Misago)) `GPL-2.0` `Python`
- [Misskey](https://misskey.io/) - Fediverse 的去中心化應用程序式微博服務器/SNS，使用 GNU social 和 Mastodon 等 ActivityPub 協議。([源代碼](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs`
- [Movim](https://movim.eu/) - 基於 XMPP 的現代聯合社交網絡，具有功能齊全的群聊、訂閱和微博。([源代碼](https://github.com/movim/movim)) `AGPL-3.0` `PHP`
- [MyBB](https://mybb.com/) - 免費、可擴展的論壇軟件包。([源代碼](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [Nitter](https://nitter.net) `⚠` - 推特的替代前端。([源代碼](https://github.com/zedeus/nitter)) `AGPL-3.0` `Nimble`
- [NodeBB](https://nodebb.org/) - 為現代網絡構建的論壇軟件。([源碼](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- [Orange 論壇](https://www.goodoldweb.com/) - Orange 論壇是一個易於部署的論壇，具有最小的依賴項並且使用很少的 javascript。([源代碼](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- [OSSN](https://www.opensource-socialnetwork.org/) - 開源社交網絡 (OSSN) 是一個用 PHP 編寫的社交網絡軟件。它允許您創建一個社交網站，並幫助您的成員與具有相似專業或個人興趣的人建立社交關係。([源代碼](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 平板論壇公告板軟件解決方案，可用於與一群人保持聯繫或為您的整個網站提供動力。([源代碼](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PixelFed](https://pixelfed.social) - Pixelfed 是一個替代 Instagram 的開源聯合平台。([源代碼](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 聯合微博服務器、Mastodon、GNU 社交和 ActivityPub 兼容。([源代碼](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [Pump.io](http://pump.io/) - 流媒體服務器，可以滿足人們對社交網絡的真正需求。([源碼](https://github.com/pump-io/pump.io)) `Apache-2.0` `Nodejs`
- [remark42](https://remark42.com/) - 一個輕量級和簡單的評論引擎，它不會監視用戶。它可以嵌入到博客、文章或讀者添加評論的任何其他地方。([Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark42)) `MIT` `Go`
- [Satellity](https://satellity.org/) - 另一個用 Golang、React 和 PostgreSQL 編寫的開源論壇。([源碼](https://github.com/satellity/satellity)) `MIT` `Go`
- [schnack](https://github.com/schn4ck/schnack) - Schnack 是簡單的自託管節點應用程序，用於在靜態網站上進行類似 Disqus 的插入式評論。`LIL-1.0` `Node.js`
- [Scoold](https://scoold.com) - JAR 中的堆棧溢出。一個企業級問答平台，具有全文搜索、SAML、LDAP 集成和社交登錄支持。([Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java`
- [Simple Machines 論壇](https://www.simplemachines.org/) - 免費的專業級軟件包，可讓您在幾分鐘內建立自己的在線社區。([源代碼](https://github.com/SimpleMachines/SMF2.1)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 聯合和分散的個人資料構建器和社交網絡引擎。([Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Python`
- [Talkyard](https://www.talkyard.io/) - 創建一個社區，您的用戶可以在其中提出想法並得到問題的解答。並進行友好的開放式討論和聊天（Slack/StackOverflow/Discourse/Reddit/Disqus 混合）。([Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Scala`
- [Teddit](https://teddit.net) `⚠` - 專注於隱私的替代 Reddit 前端。([源代碼](https://codeberg.org/teddit/teddit)) `AGPL-3.0` `Nodejs`
- [Thredded](https://github.com/thredded/thredded) - 論壇，功能豐富且簡單。`麻省理工學院``紅寶石`
- [Tokumei](https://tokumei.co/) - 匿名微博平台。([源代碼](https://gitlab.com/tokumei/tokumei)) `ISC` `rc`
- [twister](http://twister.net.co/) - 完全分散的 P2P 微博平台，利用比特幣和 BitTorrent 協議的免費軟件實現。([源代碼](https://github.com/miguelfreitas/twister-core)) `MIT` `C++`
- [Vanilla Forums](https://vanillaforums.org/) - 簡單靈活的論壇軟件。([源代碼](https://github.com/vanilla/vanilla)) `GPL-2.0` `PHP`
- [yarn.social](https://yarn.social) - 自託管、類似 Twitter™ 的去中心化微日誌平台。沒有廣告，沒有跟踪，你的內容，你的數據。([源代碼](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`
- [Zusam](https://zusam.org) - 為朋友或家人團體自託管私人論壇的免費和開源方式。([Demo](https://demo.zusam.org), [Source Code](https://github.com/zusam/zusam)) `AGPL-3.0` `PHP`


### 通信 - XMPP

**[`^ 返回頂部 ^`](#)**

[可擴展消息傳遞和存在協議](https://en.wikipedia.org/wiki/XMPP) 軟件


### 通信 - XMPP - 服務器

**[`^ 返回頂部 ^`](#)**

- [ejabberd](https://www.ejabberd.im/) - XMPP 即時通訊服務器。([源代碼](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
- [jackal](https://github.com/ortuman/jackal) - XMPP 服務器，注重穩定性，配置簡單，資源消耗低。`Apache-2.0` `Go`
- [Kontalk](https://www.kontalk.org) - Kontalk 是一個開源 Messenger，類似於 WhatsApp（目前僅適用於 android 的應用程序），包括端到端加密，服務器基於 Tigase XMPP Server。([源代碼](https://github.com/kontalk)) `GPL-3.0` `Java`
- [Metronome IM](https://metronome.im/) - Prosody IM 的分叉。([源碼](https://github.com/maranda/metronome)) `MIT` `Lua`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 專注於性能和可擴展性的移動消息傳遞平台。([源代碼](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 實時協作 (RTC) 服務器。([源代碼](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能豐富且易於配置的 XMPP 服務器。([源碼](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 多合一的 Dockerized 簡單 XMPP 解決方案，包括 Web 管理員和客戶端。([源代碼](https://github.com/snikket-im/snikket-server), [客戶端](https://snikket.org/app/)) `Apache-2.0` `Lua/Python`
- [Tigase](https://tigase.net/xmpp-server) - Java 中的 XMPP 服務器實現。`GPL-3.0` `Java`


### 通信 - XMPP - Web 客戶端

**[`^ 返回頂部 ^`](#)**

- [Candy](https://candy-chat.github.io/candy/) - 用 Ja​​vascript 編寫的多用戶 XMPP 客戶端。([源代碼](https://github.com/candy-chat/candy)) `MIT` `Javascript`
- [Converse.js](https://conversejs.org/) - 瀏覽器中的免費開源 XMPP 聊天客戶端。([源代碼](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [JSXC](https://jsxc.org) - 具有視頻通話、文件傳輸和加密通信的實時 XMPP 網絡聊天應用程序。Nextcloud/Owncloud 和 SOGo 也有版本。([源代碼](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- [Libervia](https://wiki.goffi.org/wiki/Libervia/en) - 來自 Salut à Toi 的 Web 前端。([源代碼](https://repos.goffi.org/libervia-web)) `AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由和分散的通信工具。([源代碼](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 社區支持農業 (CSA)

**[`^ 返回頂部 ^`](#)**

社區支持的農業和食品合作社的管理和行政工具

_相關：[電子商務](#e-commerce)_

- [ACP 管理員](https://acp-admin.ch/) - CSA 管理。管理會員、訂閱、交付、下車地點、會員參與、發票和電子郵件。([源代碼](https://github.com/acp-admin/acp-admin/)) `MIT` `Ruby`
- [Cagette](https://cagette.net/) - 開源網絡應用程序，幫助人們建立更好和可持續的食品系統。有人稱其為“foodhub”——群件和市場的混合體，幫助消費者從當地農民和生產者那裡訂購食物。([源代碼](https://github.com/CagetteNet/cagette)) `GPL-2.0` `Haxe`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 用戶友好的食品合作社開源軟件。([源碼](https://github.com/foodcoopshop/foodcoopshop)) `MIT` `PHP`
- [Foodsoft](https://foodcoops.net/) - 用於管理非營利食品合作社的基於網絡的軟件（產品目錄、訂購、會計、工作安排）。([源代碼](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Ruby`
- [juntagrico](https://juntagrico.org/) - 社區菜園和蔬菜合作社管理平台。([源代碼](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Local Food Nodes](https://localfoodnodes.org/) - 您的開源平台，用於人民驅動的當地食品市場和 CSA。([源碼](https://gitlab.com/localfoodnodes/localfoodnodes)) `MIT` `PHP`
- [開放食品網絡](https://www.openfoodnetwork.org/) - 當地食品的在線市場。它實現了一個獨立的在線食品商店網絡，將農民和食品中心與個人和當地企業聯繫起來。([源代碼](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - 社區支持農業團體的管理平台。([源代碼](https://github.com/OpenOlitor)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 一個基於眾包數據繪製社區支持農業的網絡應用程序。([演示](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 會議管理

**[`^ 返回頂部 ^`](#)**

- [BigBlueButton](https://bigbluebutton.org/) - 支持音頻、視頻、幻燈片（帶白板控件）、聊天和屏幕的實時共享。教師可以通過投票、表情符號和分組討論室與遠程學生互動。([Demo](https://demo.bigbluebutton.org/gl), [Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [會議組織分發 (COD)](http://usecod.com/) - 創建基於 Drupal 的會議和活動網站。([源代碼](https://git.drupalcode.org/project/cod)) `GPL-1.0` `PHP`
- [frab](https://frab.github.io/frab/) - 基於網絡的會議策劃和管理系統。它有助於收集提交內容、管理演講和演講者以及創建時間表。([源代碼](https://github.com/frab/frab)) `MIT` `Ruby`
- [indico](https://getindico.io/) - 一個功能豐富的事件管理系統，造就了@CERN，萬維網誕生的地方。([Demo](https://sandbox.getindico.io/), [Source Code](https://github.com/indico/indico)) `MIT` `Python`
- [開放式會議系統 (OCS)](https://pkp.sfu.ca/ocs/) - 是一款免費的網絡發布工具，可為您的學術會議創建完整的網絡展示。([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)) `GPL-1.0` `PHP`
- [OpenCFP](https://github.com/opencfp/opencfp) - OpenCFP是一個基於PHP的會議演講提交系統。`麻省理工學院` `PHP`
- [osem](https://osem.io/) - 為免費軟件會議量身定制的活動管理。([Demo](https://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`
- [pretalx](https://pretalx.org) - 基於 Web 的活動管理，包括運行論文徵集、審查提交和安排會談。各種相關工具的導出和導入。([源代碼](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 內容管理系統 (CMS)

**[`^ 返回頂部 ^`](#)**

CMS 是設置具有許多功能的網站的實用方法。CMS 通常帶有第三方插件、主題和功能，可以根據您的需要輕鬆添加和定制。

_相關：[博客平台](#blogging-platforms)、[靜態站點生成器](#static-site-generators)_

- [Alfresco 社區版](https://www.alfresco.com/products/community/download) - 處理任何類型內容的開源企業內容管理軟件，允許用戶輕鬆共享和協作處理內容。([源代碼](https://hub.alfresco.com/t5/alfresco-content-services-hub/project-overview-repository/ba-p/290502)) `LGPL-3.0` `Java`
- [撇號](https://apostrophecms.org/) - 專注於可擴展的上下文編輯工具的 CMS。([Demo](https://dashboard.apostrophecmsdemo.org), [Source Code](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [b2evolution CMS](https://b2evolution.net/) - 有史以來集成度最高的 CMS：b2evolution 包含構建網站以發布、共享和與社區互動所需的一切。([源碼](https://github.com/b2evolution/b2evolution)) `GPL-2.0` `PHP`
- [背景 CMS](https://backdropcms.org/) - 適用於中小型企業和非營利組織的綜合 CMS。([源代碼](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [BigTree CMS](https://www.bigtreecms.org/) - 直截了當、有據可查，並且能夠使用 PHP 和 MySQL 編寫。([源碼](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- [Bolt CMS](https://bolt.cm/) - 開源內容管理工具，力求盡可能簡單直接。([Demo](https://try.bolt.cm/), [Source Code](https://github.com/bolt/bolt)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 開源內容管理系統，更快、更輕鬆地管理網站內容，可從小型企業擴展到大型企業。([源代碼](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-1.0` `PHP`
- [Cockpit](https://getcockpit.com) - 管理任何結構化內容的簡單內容平台。([源代碼](https://github.com/agentejo/cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 開源內容管理系統。([源碼](https://github.com/concrete5/concrete5)) `MIT` `PHP`
- [Contao](https://contao.org/) - Contao 是一款功能強大的開源 CMS，可讓您創建專業網站和可擴展的 Web 應用程序。([源代碼](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 面向設計師的簡單開源 CMS。([源代碼](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Directus](https://directus.io/) - 適用於您的 SQL 數據庫的即時應用程序和 API。Directus 使用面向開發人員的實時 GraphQL+REST API 和麵向非技術用戶的直觀管理應用程序包裝新的或現有的 SQL 數據庫。([源碼](https://github.com/directus/directus)) `GPL-3.0` `Nodejs`
- [Drupal](https://www.drupal.org/) - 先進的開源內容管理平台。([源代碼](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 用於研究實驗室的在線實驗室筆記本。存儲實驗、使用數據庫查找試劑或協議、使用可信時間戳為實驗合法地添加時間戳、導出為 pdf 或 zip 存檔、與合作者共享……。([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 使用 JSON 模式為數據庫驅動的網站提供動力的內容管理系統。提供權限管理和自動 REST API。`麻省理工學院` `Nodejs`
- [Flextype](https://flextype.org/) - Flextype 是一個開源混合內容管理系統，具有無頭 CMS 的自由和傳統 CMS 的全部功能。([Demo](https://demo.flextype.org/), [Source Code](https://github.com/flextype/flextype)) `MIT` `PHP`
- [GetSimple CMS](http://get-simple.info/) - 最簡單的內容管理系統。曾經。([源碼](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPL-3.0` `PHP`
- [Joomla!](https://www.joomla.org/) - 高級內容管理系統 (CMS)。([源代碼](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS 和 Web 應用平台。([Demo](https://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [MODX](https://modx.com/) - MODX 是一個先進的內容管理和發布平台。當前版本稱為“革命”。([源代碼](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos 或 TYPO3 Neos（適用於版本 1）是現代的開源 CMS。([源代碼](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero 是一個社交和團結經濟網絡的網絡平台，包含博客、電子投資組合、CMS、RSS、專題討論、活動議程和集體智慧以促進團結同一系統中的經濟。`AGPL-3.0` `Ruby`
- [十月](https://octobercms.com/) - 免費、開源、自託管的 CMS 平台。([源代碼](https://github.com/octobercms/october)) `MIT` `PHP`
- [Omeka](https://omeka.org) - 創建複雜的敘述並分享豐富的館藏，在您的服務器上使用 Omeka 遵守都柏林核心標準，專為學者、博物館、圖書館、檔案館和愛好者而設計。([Demo](https://omeka.org/classic/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Pagekit](https://pagekit.com/) - 創建和分享新的現代 CMS。([源碼](https://github.com/pagekit/pagekit)) `MIT` `PHP`
- [Pico](https://picocms.org/) - 極其簡單、速度極快的平面文件 CMS。([源碼](https://github.com/picocms/Pico)) `MIT` `PHP`
- [Pimcore](https://www.pimcore.org/) - 多渠道體驗和參與管理平台。([源代碼](https://github.com/pimcore/pimcore)) `GPL-3.0-or-later` `PHP`
- [Plone](https://plone.org/) - 強大的開源 CMS 系統。([源代碼](https://github.com/plone)) `ZPL-2.0` `Python`
- [ProcessWire](https://processwire.com/) - ProcessWire 是一個開源內容管理系統 (CMS) 和 Web 應用程序框架，旨在滿足設計人員、開發人員及其客戶的需求。([源代碼](https://github.com/ryancramerdesign/ProcessWire)) `MPL-2.0` `PHP`
- [PropertyWebBuilder](https://propertywebbuilder.com) - 用於創建房地產網站的終極 Ruby on Rails 引擎。([Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- [Publify](https://publify.github.io/) - 簡單但功能齊全的網絡發佈軟件。([源代碼](https://github.com/publify/publify)) `MIT` `Ruby`
- [Rapido](https://framagit.org/InfoLibre/rapido) - 使用 Rapido 創建您的網站。編輯、發布和共享協作內容。`AGPL-3.0` `Go`
- [REDAXO](https://www.redaxo.org) - 簡單、靈活且有用的內容管理系統（僅提供德語文檔）。([源代碼](https://github.com/redaxo/redaxo)) `MIT` `PHP`
- [Redaxscript](https://redaxscript.com) - 用於 MySQL、SQLite 和 PostgreSQL 的超輕量級 CMS。([Demo](https://demo.redaxscript.com/login), [Source Code](https://github.com/redaxscript/redaxscript)) `GPL-3.0` `PHP`
- [Roadiz](https://www.roadiz.io/) - 基於節點系統的現代 CMS，可以處理多種類型的服務。([源碼](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- [SilverStripe](https://www.silverstripe.org) - 易於使用的CMS，底層強大的MVC框架。([Demo](https://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向網絡作者的協作工作、多語言環境和簡單易用的互聯網出版系統。([源代碼](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 基於 MongoDB、CQRS 和事件溯源的無頭 CMS。([Demo](https://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 最先進的開源內容管理框架（headless-CMS），輕鬆構建強大的 API。([源碼](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Textpattern](https://textpattern.com/) - 靈活、優雅且易於使用的 CMS。([Demo](https://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 作者友好的平面文件 cms，帶有基於 vue.js 的可視化降價編輯器。([源代碼](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 強大而先進的 CMS，擁有龐大的社區。([源代碼](https://github.com/TYPO3/TYPO3.CMS)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的 CMS。免費和開源，擁有一個了不起的社區。([源代碼](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Wagtail](https://wagtail.io/) - 專注於靈活性和用戶體驗的 Django 內容管理系統。([源代碼](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基於 Laravel PHP 框架構建的快速且安全的內容管理系統。([源碼](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - WonderCMS 是自 2008 年以來最小的平面文件 CMS。([Demo](https://www.wondercms.com/demo), [Source Code](https ://github.com/robiso/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 世界上最常用的博客和 CMS 引擎。([源代碼](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`
- [WriteFreely](https://writefreely.org) - 編寫軟件來創建一個極簡主義的聯合博客——或整個社區。([源碼](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### DNS

**[`^ 返回頂部 ^`](#)**

_另見：[awesome-sysadmin/DNS](https://github.com/awesome-foss/awesome-sysadmin#dns)_

- [blocky](https://github.com/0xERR0R/blocky) - 快速和輕量級的 DNS 代理（如 Pi-hole）作為具有許多功能的本地網絡的廣告攔截器。`Apache-2.0` `Go`
- [CoreDNS](https://coredns.io/) - 插件驅動的 DNS 服務器，支持代理到 Google 的 DNS-over-HTTPS。([源代碼](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- [Maza 廣告攔截](https://maza-ad-blocking.andros.dev/) - 本地廣告攔截器。像 Pi-hole 但在本地並使用您的操作系統。([源代碼](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Bash`
- [nsupdate.info](https://www.nsupdate.info/) - nsupdate.info 是一個動態 DNS 服務。([Demo](https://www.nsupdate.info/account/register/), [Source Code](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- [SPF 工具箱](https://spftoolbox.com) - 用於查找 SPF、MX、Whois 等 DNS 記錄的應用程序。([源代碼](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`


＃＃＃ 文件管理

**[`^ 返回頂部 ^`](#)**

- [DOCAT](https://github.com/randombenj/docat) - 託管您的文檔。簡單的。版本化。想要。`麻省理工學院` `Python/Docker`
- [Docspell](https://docspell.org) - 自動標記文檔組織者和存檔。([源代碼](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core/) - 一個簡單的私人文檔管理系統，具有以數字方式組織文檔的基本功能。`GPL-3.0` `Ruby`
- [I, Librarian](https://i-librarian.net) - I, Librarian 可以整理PDF文件和辦公文件。它為工業界和學術界的學生和研究小組提供了許多額外的功能。([Demo](https://i-librarian.net/demo/), [Source Code](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 免費開源電子文檔管理系統。具有預覽生成、OCR 和自動分類等功能的文檔電子保管庫。([源代碼](https://gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) - 無紙化的一個分支，添加了一個新的界面和許多其他的底層變化。掃描、索引和歸檔所有紙質文檔。([演示](https://demo.paperless-ngx.com/)) `GPL-3.0` `Python`
- [Papermerge](https://www.papermerge.com) - 專注於掃描文檔（電子檔案）的開源文檔管理系統。以類似於 Dropbox/Google Drive 的方式提供文件瀏覽功能。OCR、全文搜索、文本覆蓋/選擇。([源代碼](https://github.com/ciur/papermerge)) `Apache-2.0` `Python`
- [paper{s}pace](https://dedicatedcode.com/projects.html) - 用於管理所有離線文檔的小型 Web 應用程序。為您的文檔提供可搜索的存儲空間，並提醒您即將完成的任務。([源代碼](https://gitlab.com/dedicatedcode/paperspace)) `MIT` `Java`
- [Teedy](https://teedy.io/) - (Ex SismicsDocs) 輕量級文檔管理系統，包含您可以從大型昂貴解決方案中獲得的所有功能。([源代碼](https://github.com/sismics/docs)) `GPL-2.0` `Java`


### 文檔管理 - 電子書

**[`^ 返回頂部 ^`](#)**

- [BicBucStriim](https://projekte.textmulch.de/bicbucstriim/) - 提供對 Calibre Library 電子書收藏的基於 Web 的訪問。([源代碼](https://github.com/rvolz/BicBucStriim)) `MIT` `PHP`
- [Calibre Web](https://github.com/janeczku/calibre-web) - Web 應用程序為使用現有 Calibre 數據庫瀏覽、閱讀和下載電子書提供了一個乾淨的界面。`GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 電子書庫管理器，可以查看、轉換和編目大多數主要電子書格式的電子書，並提供內置 Web 服務器對於遠程客戶端。([Demo](https://calibre-ebook.com/demo), [Source Code](https://launchpad.net/calibre)) `GPL-3.0` `Python`
- [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - 輕量級電子書服務器替代 Calibre 內容服務器或 Calibre2OPDS。([Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)) `GPL-2.0` `PHP`
- [Kavita](https://www.kavitareader.com/) - 具有用戶管理、評分和評論以及元數據支持的跨平台電子書/manga/comic/pdf 服務器和網絡閱讀器。([Demo](https://wiki.kavitareader.com/en/kavita-demo), [Source Code](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET Core/碼頭工人`
- [Komga](https://komga.org) - 具有 API 和 OPDS 支持的漫畫/漫畫/BD 媒體服務器、用於探索圖書館的現代 Web 界面以及 Web 閱讀器。([源代碼](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [Mango](https://github.com/hkalexling/Mango) - 內置 MangaDex 下載器的漫畫服務器和網絡閱讀器。`麻省理工學院``水晶`
- [pyShelf](https://github.com/th3r00t/pyShelf) - 輕量級電子書服務器。`GPL-3.0` `Python`
- [Tanoshi](https://github.com/faldez/tanoshi) - 帶有擴展的自託管網絡漫畫閱讀器。`麻省理工學院``銹`
- [The Epube](https://tt-rss.org/the-epube) - 使用 EPUB.js、Bootstrap 和 Calibre 的自託管 Web EPUB 閱讀器。([源代碼](https://git.tt-rss.org/fox/the-epube)) `GPL-3.0` `PHP`


### 文檔管理 - 機構資料庫和數字圖書館軟件

**[`^ 返回頂部 ^`](#)**

- [DSpace](https://duraspace.org/dspace/) - 提供對數字資源的持久訪問的交鑰匙存儲庫應用程序。([源代碼](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 具有靈活元數據和工作流模型的數字文檔管理系統，主要針對學術機構。([Demo](http://tryme.demo.eprints-hosting.org/), [Source Code](https://github.com/eprints/eprints)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://fedorarepository.org/) - 強大的模塊化存儲系統，用於管理和傳播數字內容，特別適用於數字圖書館和檔案館，用於訪問和保存。([源代碼](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 具有良好用戶體驗的高度可擴展的交鑰匙研究數據管理平台。([Demo](https://inveniordm.web.cern.ch/), [Source Code](https://github.com/inveniosoftware/), [Clients](https://inveniosoftware.org/products/ rdm/)) `MIT` `Python`
- [Islandora](https://islandora.ca/) - Drupal 模塊，用於瀏覽和管理基於 Fedora 的數字存儲庫。([源碼](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera 框架的前端，它本身是一個 Ruby on Rails 應用程序，用於瀏覽和管理基於 Fedora 的數字存儲庫。([源代碼](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文檔管理 - 集成圖書館系統 (ILS)

**[`^ 返回頂部 ^`](#)**

_相關：[內容管理系統 (CMS)](#content-management-systems-cms)、[存檔和數字保存 (DP)](#archiving-and-digital-preservation-dp)_

- [Evergreen](https://evergreen-ils.org) - 高度可擴展的圖書館軟件，可幫助圖書館顧客查找圖書館資料，並幫助圖書館管理、編目和流通這些資料。([源代碼](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- [Koha](https://koha-community.org/) - 企業級 ILS，具有用於獲取、流通、編目、標籤打印、離線流通等模塊，可在無法訪問互聯網時使用，等等。([Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 可以作為具有聯合功能的服務運行的大型 ILS，主要用於圖書館網絡。包括大多數標準模塊（流通、收購、編目……）和基於網絡的公共和專業界面。([Demo](https://ils.test.rero.ch/), [Source Code](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Other`


＃＃＃ 電子商務

**[`^ 返回頂部 ^`](#)**

_相關：[社區支持農業 (CSA)](#community-supported-agriculture-csa)_

- [Aimeos](https://aimeos.org/) - 超快速的開源電子商務框架，用於構建自定義在線商店、市場和復雜的 B2B 應用程序，使用 Laravel 擴展到數十億個項目。([Demo](https://demo.aimeos.org/), [Source Code](https://github.com/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Attendize](https://www.attendize.com/) - 售票和活動管理平台。([源代碼](https://github.com/attendize/attendize)) `AAL` `PHP`
- [Bagisto](https://bagisto.com/en/) - 領先的 Laravel 開源電子商務框架，具有多庫存來源、稅收、本地化、直銷和更多令人興奮的功能。([Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - CoreShop 是 Pimcore 的電子商務插件。([源代碼](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal Commerce 是 Drupal CMS 的流行電子商務模塊，支持數十種支付、運輸和購物相關模塊。([源代碼](https://github.com/drupalcommerce/commerce)) `GPL-2.0` `PHP`
- [Magento](https://magento.com/) - 開放式全渠道創新的領先提供商。([Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [Microweber](https://microweber.com/) - 拖放 CMS 和在線商店。([Demo](https://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- [開源 POS](https://www.opensourcepos.org/) - 開源銷售點是一個基於網絡的銷售點系統。([源碼](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- [OpenBazaar](https://www.openbazaar.org) - 使用加密貨幣的去中心化市場。([源碼](https://github.com/openbazaar/openbazaar-go)) `MIT` `Go`
- [OpenCart](https://www.opencart.com) - 免費開源購物車解決方案。([源代碼](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [OXID eShop](https://oxidforge.org) - OXID eShop 是一個靈活的開源電子商務軟件，具有廣泛的功能。([Demo](https://demoshop.oxid-esales.com/community-edition/), [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP `
- [PrestaShop](https://www.prestashop.com/) - PrestaShop 提供免費、開源和完全可擴展的電子商務解決方案。([Demo](https://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 基於 Django 的活動門票銷售平台。([源代碼](https://github.com/pretix)) `Apache-2.0` `Python`
- [Reaction Commerce](https://reactioncommerce.com/) - 可定制、實時反應式、Javascript 商務平台。([源代碼](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`
- [Saleor](https://saleor.io) - 基於 Django 的開源電子商務店面。([Demo](https://demo.getsaleor.com/), [Source Code](https://github.com/mirumee/saleor)) `BSD-3-Clause` `Python`
- [Shopware 社區版](https://shopware.com/community/) - 德國製造的基於 PHP 的開源電子商務軟件。([Demo](https://www.shopware.com/en/test-demo/), [Source Code](https://github.com/shopware/platform)) `MIT` `PHP`
- [Shuup](https://www.shuup.com/) - Django 為小型和大型網站提供完全可定制的開源電子商務框架。([源代碼](https://github.com/shuup/shuup)) `AGPL-3.0` `Python`
- [Solidus](https://solidus.io/) - 一個免費的開源電子商務平台，可讓您完全控制您的商店。([Demo](http://demo.solidus.io/), [Source Code](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby`
- [Spree Commerce](https://spreecommerce.org) - Spree 是一個完整的、模塊化和 API 驅動的開源電子商務解決方案，適用於 Ruby on Rails。([Demo](https://new-ux.spreecommerce.org/), [Source Code](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - Symfony2 為電子商務提供支持的開源全棧平台。([Demo](https://sylius.com/try/), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia 是一個開源且靈活的電子商務解決方案。([Demo](https://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 基於 Node.js、TypeScript 和 GraphQL 構建的無頭商務框架。([Demo](https://demo.vendure.io), [Source Code](https://github.com/vendure-ecommerce/vendure)) `MIT` `Nodejs`
- [WooCommerce](https://woocommerce.com/) - 基於 WordPress 的電子商務解決方案。([源代碼](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`
- [Yclas](https://yclas.com/) - 用於分類網站的免費開源、自託管 CMS。([源代碼](https://github.com/yclas/yclas)) `GPL-3.0` `PHP`


### 聯合身份和身份驗證

**[`^ 返回頂部 ^`](#)**

**請訪問 [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**


### 供稿讀者

**[`^ 返回頂部 ^`](#)**

[新聞聚合器](https://en.wikipedia.org/wiki/News_aggregator)，也稱為提要聚合器、提要閱讀器、新聞閱讀器，[RSS](https://en.wikipedia.org/wiki/RSS ) 閱讀器或簡單的聚合器，是客戶端軟件或網絡應用程序，可將在線報紙、博客/視頻博客、播客和其他更新等聚合網絡內容聚合在一個位置以便於查看。這部分還包括 RSS/Atom 自動化工具。

- [CommaFeed](https://www.commafeed.com/) - 受 Google Reader 啟發的自託管 RSS 閱讀器。([源代碼](https://github.com/Athou/commafeed)) `Apache-2.0` `Java`
- [FeedHQ](https://feedhq.org/) - FeedHQ 是一個基於網絡的提要閱讀器。([源代碼](https://github.com/feedhq/feedhq)) `BSD-3-Clause` `Python`
- [Feedpushr](https://github.com/ncarlier/feedpushr) - 強大的 RSS 聚合器，能夠將文章轉換和發送到許多輸出。單個二進製文件，可通過插件擴展。`GPL-3.0` `Go`
- [FreshRSS](https://freshrss.org/) - 自託管 RSS 提要聚合器。([Demo](https://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Clients](https://github.com/Alkarex /EasyRSS)) `AGPL-3.0` `PHP`
- [全文 RSS](https://fivefilters.org/content-only) - 從新聞站點和博客中提取文章內容，並將僅包含故事摘錄的 RSS 提要轉換為全文提要。由 FiveFilters.org 開發。([源代碼](https://bitbucket.org/fivefilters/full-text-rss)) `GPL-3.0` `PHP`
- [Goeland](https://github.com/slurdge/goeland) - 閱讀 RSS/Atom 提要並過濾/消化它們以創建精美的電子郵件。`麻省理工學院``去`
- [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - Tiny Tiny RSS 的更多功能。([源代碼](https://github.com/nhoening/gritttt-rss)) `BSD-2-Clause` `Python`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（只是另一個 RSS 閱讀器）是一個基於網絡的新聞聚合器和閱讀器（Newspipe 的分支）。([Demo](https://www.jarr.info/), [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Python`
- [Kriss Feed](https://tontof.net/kriss/feed/) - 簡單而智能（或愚蠢）的 Feed 閱讀器。([Demo](https://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed)) `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed（用於 Light Feed）是一個免費且極簡的 RSS 聚合器。`AGPL-3.0` `PHP`
- [Leselys](https://github.com/toxinu/leselys) - 你非常優雅的 RSS 閱讀器。`AGPL-3.0` `Python`
- [Lite-Reader](https://github.com/cubny/lite-reader) - 在您自己的機器上使用一個簡單而精簡的應用程序閱讀您的提要。([Demo](http://cubny.com/lite-reader/)) `BSD-3-Clause` `PHP`
- [Miniflux](https://miniflux.app/) - Miniflux 是一個極簡主義和開源的新聞閱讀器，用 Go 和 PostgreSQL 編寫。([源代碼](https://github.com/miniflux/v2)) `Apache-2.0` `Go`
- [Moonmoon](https://moonmoon.org/) - 簡單的提要聚合器（類似行星）：它只聚合提要並將它們吐出在一頁中。([源代碼](https://github.com/moonmoon/moonmoon)) `BSD-3-Clause` `PHP`
- [NewsBlur](https://www.newsblur.com/) - NewsBlur 是一款個人新聞閱讀器，可將人們聚集在一起談論世界。舊樂器的新聲音。([源代碼](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [newsdash](https://github.com/buzz/newsdash) - 受 iGoogle 和 Netvibes 啟發的新聞儀表板。`AGPL-3.0` `Nodejs`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Newspipe 是一個網絡新聞閱讀器。([演示](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [PolitePol](https://github.com/taroved/pol) - 用於為任何網頁創建 RSS 提要的在線工具。([Demo](https://politepol.com)) `MIT` `Python`
- [閱讀器](https://github.com/lemon24/reader) - Python 提要閱讀器 Web 應用程序和庫（因此您可以使用它來構建自己的），只有標準庫和純 Python 依賴項。`BSD-3-Clause` `Python`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - rss-bridge 是一個 PHP 項目，能夠為沒有 ATOM 提要的網站生成 ATOM 提要。`Unlicense` `PHP`
- [RSS 全文代理](https://github.com/Kombustor/rss-fulltext-proxy) - 鏡像 RSS 提要以返回從網站提取的項目的完整內容。`麻省理工學院` `Nodejs`
- [RSS 合併](https://github.com/taophp/rss-merger) - PHP 腳本，它將多個 RSS / Atom 提要作為輸入並將它們合併為單個 RSS 提要。`GPL-2.0` `PHP`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster是一個易於使用的基於 Web 的 RSS 聚合器和閱讀器，與 Fever API 兼容，是 Google Reader 的替代品。`麻省理工學院` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 獲取 RSS/Atom-feeds 並將新內容推送到任何電子郵件接收器，支持 OPML。`GPL-2.0` `Python`
- [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - 從同一文件夾中的媒體文件列表自動生成有效 RSS 和 Atom 提要的簡單腳本。`麻省理工學院` `PHP`
- [Selfoss](https://selfoss.aditu.de/) - 新的多功能 rss 閱讀器、直播、混搭、聚合 Web 應用程序。([源碼](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Sismics Reader](https://www.sismics.com/reader/) - 免費和開源的提要閱讀器，包括所有主要的谷歌閱讀器功能。([Demo](https://www.sismics.com/reader/#!/demo), [Source Code](https://github.com/sismics/reader)) `GPL-2.0` `Java`
- [Stringer](https://github.com/swanson/stringer) - 正在進行中的自託管、反社會 RSS 閱讀器。`麻省理工學院``紅寶石`
- [Temboz](https://github.com/fazalmajid/temboz) - 兩列提要閱讀器，強調過濾功能以管理信息過載。`麻省理工學院``Python`
- [Tiny Tiny RSS](https://tt-rss.org) - 開源的基於 Web 的新聞提要 (RSS/Atom) 閱讀器和聚合器。([演示](https://srv.tt-rss.org/tt-rss/), [源代碼](https://git.tt-rss.org/fox/tt-rss)) `GPL- 3.0` `PHP`
- [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - Tiny Tiny RSS 的移動 webapp。`AGPL-3.0` `Javascript`
- [ttrss-reader](https://github.com/kucrut/ttrss-reader) - TTRSS 的輕量級響應式客戶端。`GPL-2.0` `Javascript`
- [Winds](https://getstream.io/winds/) `⚠` - 使用 React/Redux/Sails/Node 和 Stream 構建的開源和漂亮的 RSS 閱讀器。它展示了由 Stream API 提供支持的個性化提要。([Demo](https://winds.getstream.io/), [Source Code](https://github.com/GetStream/Winds)) `BSD-3-Clause` `Nodejs`


### 文件傳輸和同步

**[`^ 返回頂部 ^`](#)**

_相關：[群件](#groupware)_

- [Git Annex](https://git-annex.branchable.com/) - 計算機、服務器、外置驅動器之間的文件同步。([源代碼](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - Kinto 是一個極簡的 JSON 存儲服務，具有同步和共享能力。([源代碼](https://github.com/Kinto)) `Apache-2.0` `Python`
- [myDrive](https://github.com/subnub/myDrive) - 功能齊全的在線存儲解決方案、上傳/下載文件、照片/視頻查看器等，全部通過網絡客戶端完成。([Demo](https://mydrive-demo.herokuapp.com/)) `GPL-3.0` `Nodejs`
- [Nextcloud](https://nextcloud.com/) - 根據您的條件從任何設備訪問和共享您的文件、日曆、聯繫人、郵件和 [更多](https://apps.nextcloud.com/)。([Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- [OpenSSH SFTP 服務器](https://www.openssh.com/) - 安全文件傳輸程序。([源代碼](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD-2-Clause` `C`
- [ownCloud](https://owncloud.org/) - 用於保存、同步、查看、編輯和共享文件、日曆、地址簿等的多合一解決方案。([源代碼](https://github.com/owncloud/core), [客戶端](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP`
- [Peergos](https://peergos.org) - 安全和私密的在線空間，您可以在其中存儲、共享和查看您的照片、視頻、音樂和文檔。還包括日曆、新聞提要、任務列表、聊天和電子郵件客戶端。([Demo](https://demo.peergos.net), [Source Code](https://github.com/Peergos)) `AGPL-3.0` `Java`
- [Pydio](https://pydio.com/) - 將任何 Web 服務器變成強大的文件管理系統和主流雲存儲提供商的替代品。([源代碼](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba 是適用於 Linux 和 Unix 的標準 Windows 互操作性程序套件。它為使用 SMB/CIFS 協議的所有客戶端提供安全、穩定和快速的文件和打印服務。([源代碼](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要用於團隊和組織的文件託管和共享解決方案。([源碼](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [SparkleShare](https://sparkleshare.org/) - 自託管、即時、安全的文件同步。([源代碼](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- [Syncany](https://www.syncany.org/) - 用於任意存儲後端的安全文件同步軟件，開源雲存儲和文件共享應用程序。將您的文件安全地同步到任何類型的存儲設備。`GPL-3.0` `Java`
- [Syncthing](https://syncthing.net/) - Syncthing 是一個開源的點對點文件同步工具。([源碼](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison 是適用於 OSX、Unix 和 Windows 的文件同步工具。`GPL-3.0` `OCaml`
- [Z-Push](https://z-push.org/) - Microsoft 的 ActiveSync 協議的實現。([源代碼](https://stash.kopano.io/projects/ZHUB/repos/z-push)) `AGPL-3.0` `PHP`


### 文件傳輸 - 分佈式文件系統

**[`^ 返回頂部 ^`](#)**

**請訪問 [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**


### 文件傳輸 - 對象存儲和文件服務器

**[`^ 返回頂部 ^`](#)**

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 一種開源的地理分佈式存儲服務，您可以自行託管以滿足許多需求 - S3 兼容。([源代碼](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Rust`
- [Minio](https://minio.io/) - Minio 是一個與 Amazon S3 API 兼容的開源對象存儲服務器。([源代碼](https://github.com/minio/minio)) `Apache-2.0` `Go`
- [SeaweedFS](https://github.com/chrislusf/seaweedfs) - SeaweedFS 是一個開源的分佈式文件系統，支持WebDAV、S3 API、FUSE mount、HDFS等，針對大量小文件進行了優化，易於添加容量。`Apache-2.0` `Go`
- [SFTPGo](https://github.com/drakkan/sftpgo) - 靈活、功能齊全且高度可配置的 SFTP 服務器，具有可選的 FTP/S 和 WebDAV 支持。`AGPL-3.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer，一個處理 Amazon S3 協議的服務器的開源實現。([源碼](https://github.com/scality/cloudserver)) `Apache-2.0` `Nodejs`


### 文件傳輸 - 點對點文件共享

**[`^ 返回頂部 ^`](#)**

- [bittorrent-tracker](https://webtorrent.io/) - 簡單、強大的 BitTorrent 跟踪器（客戶端和服務器）實現。([源碼](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [cloud-torrent](https://github.com/jpillora/cloud-torrent) - 帶有 HTTP 可檢索或流式下載文件的 Torrent Web 客戶端。`AGPL-3.0` `Go`
- [Dat Project](https://datproject.org) - 強大的分散式文件共享應用程序，由大型模塊生態系統構建。([源碼](https://github.com/datproject)) `MIT` `Nodejs`
- [exatorrent](https://github.com/varbhat/exatorrent) - 用 Go 編寫的 BitTorrent 客戶端，可以在本地運行或託管在遠程服務器上，並支持通過 HTTP 流式傳輸。`GPL-3.0` `Go`
- [FilePizza](https://file.pizza/) - 在您的瀏覽器中進行點對點文件傳輸。([源代碼](https://github.com/kern/filepizza)) `BSD-3-Clause` `Nodejs`
- [instant.io](https://github.com/webtorrent/instant.io) - 通過 WebTorrent 流式傳輸文件。([Demo](https://instant.io)) `MIT` `Nodejs`
- [Magnetico](https://github.com/boramalper/magnetico) - Magnetico 是第一個專為最終用戶設計的自治（自託管）BitTorrent DHT 搜索引擎套件。`AGPL-3.0` `Python`
- [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - 索引所有流行種子網站的搜索引擎。`麻省理工學院``長生不老藥`
- [Opentracker](https://erdgeist.org/arts/software/opentracker/) - 開放且免費的 bittorrent 追踪器。它旨在最大限度地減少資源使用，並旨在在您的 wlan 路由器上運行。([源代碼](https://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
- [peerflix-server](https://github.com/asapach/peerflix-server) - 下載種子文件並提供直接鏈接下載或直接鏈接流。`麻省理工學院` `Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 免費的跨平台 bittorrent 客戶端，具有用於遠程訪問的功能豐富的 Web UI。([源代碼](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [rartracker](https://github.com/swetorrentking/rartracker) - 完整的私人比特流跟踪器。`WTFPL` `PHP`
- [發送](https://github.com/timvisee/send) - 簡單、私密、端到端的加密臨時文件共享，最初由 Mozilla 構建。([客戶端](https://github.com/timvisee/send#clients)) `MPL-2.0` `Nodejs`
- [Torrents.csv](https://codeberg.org/heretic/torrents-csv-server) - 一個自託管的種子搜索引擎。`GPL-3.0` `Rust`
- [傳輸](https://transmissionbt.com/) - 快速、簡單、免費的 Bittorrent 客戶端。([源代碼](https://github.com/transmission/transmission)) `GPL-3.0` `C`


### 文件傳輸 - 單擊和拖放上傳

**[`^ 返回頂部 ^`](#)**

- [ass](https://github.com/tycrek/ass) - 卓越的自託管 ShareX 服務器。適用於 ShareX (Windows)、Flameshot (Linux) 和 MagicCap（Linux、macOS）等客戶端。`ISC` `Nodejs`
- [Chibisafe](https://lolisafe.moe/) - 超快的文件上傳器和用節點編寫的超棒的掩體。([源碼](https://github.com/weebdev/chibisafe)) `MIT` `Nodejs`
- [Coquelicot](https://coquelicot.potager.org/) - Coquelicot 是一個專注於保護用戶隱私的“一鍵式”文件共享網絡應用程序。([源代碼](https://coquelicot.potager.org/dist/coquelicot-0.9.6.tar.gz)) `AGPL-3.0` `Ruby`
- [elixire](https://elixi.re) - 簡單而先進的截圖上傳和鏈接縮短服務。([源代碼](https://gitlab.com/elixire/elixire), [客戶端](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [文件共享](https://github.com/axeloz/filesharing) - 基於唯一和臨時鏈接的開源和自託管文件共享應用程序。`GPL-3.0` `PHP`
- [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter 是一款自託管軟件，可讓您輕鬆通過 Internet 共享文件。([演示](https://fileshelter.demo.poupon.io/)) `GPL-3.0` `C++`
- [FireShare](https://github.com/rockmanvnx6/FireShare) - 全棧、pub-sub、實時安全文件共享系統。([Demo](https://auspham.dev/FireShare)) `MIT` `Nodejs`
- [Gokapi](https://github.com/Forceu/gokapi) - 用於共享文件的輕量級服務器，在設定的下載量或天數後過期。與已停產的 Firefox Send 類似，不同之處在於僅允許管理員上傳文件。`GPL-3.0` `Go`
- [goploader](https://github.com/Depado/goploader) - 通過服務器端加密輕鬆共享文件，符合 curl/httpie/wget。`麻省理工學院``去`
- [GoSƐ](https://github.com/stv0g/gose) - GoSƐ 是一個專注於可擴展性和簡單性的現代文件上傳器。它僅依賴於 S3 存儲後端，因此無需額外的數據庫或緩存即可水平擴展。([Demo](https://gose.0l.de)) `Apache-2.0` `Go/Typescript`
- [image-uploader](https://github.com/daggy1234/image-uploader) - 一個與 shareX 兼容的圖片上傳器，具有 Web 界面和 REST API 以提高速度。`AGPL-3.0` `生鏽`
- [imgpush](https://github.com/hauxir/imgpush) - imgpush 是一個自託管的文件上傳服務，可以很容易地集成到其他 webapps 中。`麻省理工學院``Python`
- [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - Jirafeau 是一個允許以簡單方式上傳文件並提供唯一鏈接的網站。([Demo](http://jirafeau.net/)) `AGPL-3.0` `PHP`
- [Kleeja](https://kleeja.net/) - 文件上傳/共享應用程序，自 2007 年以來被成千上萬的網站管理員使用。([Source Code](https://github.com/kleeja-official/kleeja)) `GPL-2.0` `PHP`
- [linx-server](https://github.com/ZizzyDizzyMC/linx-server) - 具有 API、自動到期、刪除密鑰和網絡種子支持的簡單文件共享和 pastebin。([Demo](https://put.icu/)) `GPL-3.0` `Go`
- [lufi](https://framagit.org/fiat-tux/hat-softwares/lufi) - 讓我們上傳那個文件，客戶端加密。([Demo](https://demo.lufi.io), [Source Code](https://framagit.org/fiat-tux/hat-softwares/lufi/tree/master)) `AGPL-3.0` ` Perl`
- [lutim](https://github.com/ldidry/lutim) - 讓我們上傳那張圖片。`AGPL-3.0` `Perl`
- [OnionShare](https://github.com/micahflee/onionshare) - 安全匿名地共享任何大小的文件。`GPL-2.0` `Python`
- [PicoShare](https://pico.rocks) - 用於共享圖像和其他文件的簡約、易於託管的服務。([Demo](https://demo.pico.rocks), [Source Code](https://github.com/mtlynch/picoshare)) `AGPL-3.0` `Go`
- [PictShare](https://www.pictshare.net/) - PictShare 是一種多語言、開源的圖像託管服務，具有簡單的調整大小和上傳 API。([源代碼](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP`
- [Plik](https://github.com/root-gg/plik) - Plik 是一個可擴展且友好的臨時文件上傳系統。([Demo](https://plik.root.gg/)) `MIT` `Go`
- [Pomf](https://github.com/Pomf/Pomf) - 簡單的文件上傳和共享，現已關閉的站點 Pomf.se 的來源。`麻省理工學院` `PHP`
- [ProjectSend](https://www.projectsend.org/) - 上傳文件並將它們分配給您創建的特定客戶端。將這些文件的訪問權限授予您的客戶。([源碼](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 簡單的開源自託管文件共享解決方案，具有強大的 up-/download-resume 和密碼保護。`BSD-2-Clause` `Nodejs`
- [Pste](https://dev.pste.pw/) - 一個簡單的文件託管應用程序，靈感來自 pomf.se 和 teknik.io。([源代碼](https://github.com/FoxDev/pste)) `GPL-3.0` `Python`
- [QuickShare](https://github.com/ihexxa/quickshare) - 不同設備之間快速簡單的文件共享。([演示](https://hexxa-quickshare.herokuapp.com/)) `LGPL-3.0` `Go`
- [分享](https://github.com/MrDemonWolf/share) - 簡單而高級的上傳器 - 使用管理員的審核工具上傳文件、圖像和文本。可用於朋友和家人或只為您。與 ShareX 等集成。`麻省理工學院` `Nodejs`
- [Sharry](https://github.com/eikek/sharry) - 通過互聯網在經過身份驗證的用戶和匿名用戶（兩種方式）之間輕鬆共享文件，並具有可恢復的上傳和下載。`GPL-3.0` `Scala/Java`
- [transfer.sh](https://transfer.sh) - 從命令行輕鬆共享文件。([源碼](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`
- [Uguu](https://uguu.se/) - 存儲文件並在 X 時間後刪除。([源代碼](https://github.com/nokonoko/uguu)) `MIT` `PHP`
- [Void](https://github.com/AlphaNecron/Void) - 用於 ShareX 的輕量級、快速和優雅的文件託管服務，帶有 Web UI 和 REST API。([源代碼](https://github.com/AlphaNecron/Void/)) `MIT` `Nodejs`
- [Web-File-Uploader](https://v2.femto.pw/) - 一個讓人們上傳和共享圖像和文件的簡單工具。([源碼](https://github.com/femto-apps/web-file-uploader)) `MIT` `Nodejs`
- [XBackBone](https://github.com/SergiX44/XBackBone) - 一個簡單、快速、輕量級的文件管理器，集成了即時共享工具，例如 ShareX（一個免費的開源 Windows 屏幕截圖實用程序）。`AGPL-3.0` `PHP`
- [YouTransfer](https://www.youtransfer.io) - YouTransfer 是一個簡單而優雅的自託管文件傳輸和共享解決方案。([源碼](https://github.com/YouTransfer/YouTransfer)) `Apache-2.0` `Nodejs`
- [Zipline](https://zipline.diced.me/) - 一個輕量級、快速和可靠的文件共享服務器，通常與 ShareX 一起使用，提供基於反應的 Web UI 和快速 API。([源碼](https://github.com/diced/zipline)) `MIT` `Nodejs`


### 文件傳輸 - 基於 Web 的文件管理器

**[`^ 返回頂部 ^`](#)**

- [Apaxy](https://oupala.github.io/apaxy/) - 為增強瀏覽 Web 目錄的體驗而構建的主題，使用 mod_autoindex Apache 模塊和一些 CSS 來覆蓋目錄列表的默認樣式。([源代碼](https://github.com/oupala/apaxy)) `GPL-3.0` `HTML`
- [DirectoryLister](https://www.directorylister.com/) - 基於 PHP 的簡單目錄列表器，列出一個目錄及其所有子目錄，並允許您在其中導航。([源碼](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- [explorer](https://soyuka.github.io/explorer/) - 高度可配置的目錄列表。([源碼](https://github.com/soyuka/explorer)) `MIT` `Nodejs`
- [filebrowser](https://filebrowser.org/) - 帶有 Material Design Web 界面的 Web 文件瀏覽器。([源代碼](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go`
- [FileGator](https://filegator.io/) - FileGator 是一個功能強大的多用戶文件管理器，具有單頁前端。([Demo](https://demo.filegator.io), [Source Code](https://github.com/filegator/filegator)) `MIT` `PHP`
- [Filestash](https://www.filestash.app/) - 一個網絡文件管理器，可讓您在任何位置管理數據：FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox 或 Google Drive。([Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Go`
- [goBrowser](https://github.com/xataz/gobrowser) - 簡單的 http 文件瀏覽器。`GPL-3.0` `Go`
- [Gossa](https://github.com/pldubouilh/gossa) - Gossa 是一個輕量級且簡單的文件網絡服務器。`麻省理工學院``去`
- [h5ai](https://larsjung.de/h5ai/) - 適用於 HTTP Web 服務器的現代文件索引器，專注於您的文件。目錄以一種吸引人的方式顯示，並且通過不同的視圖、麵包屑和樹形概覽來增強對目錄的瀏覽。([Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
- [IFM](https://github.com/misterunknown/ifm) - 單一腳本文件管理器。`麻省理工學院` `PHP`
- [miniserve](https://github.com/svenstaro/miniserve) - 通過 HTTP 提供文件和目錄的 CLI 工具。`麻省理工學院``銹`
- [ResourceSpace](https://www.resourcespace.com) - ResourceSpace 開源數字資產管理軟件是一種簡單、快速、免費的方式來組織您的數字資產。([Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [s3server](https://github.com/jessfraz/s3server) - 簡單的 HTTP 接口，用於索引和瀏覽公共 S3 或 Google Cloud Storage 存儲桶中的文件。`麻省理工學院``去`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 簡單的靜態文件服務器，帶有 webui 來管理文件。`麻省理工學院` `Nodejs`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces 是一個離線、跨平台的文件管理器和組織器，也可以用作筆記應用程序。應用程序的 WebDAV 版本可以安裝在 WebDAV 服務器之上，例如 Nextcloud 或 ownCloud。([Demo](https://demo.tagspaces.com), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Javascript`
- [updog](https://github.com/sc0tfree/updog) - Updog 是 Python 的 SimpleHTTPServer 的替代品。它允許通過 HTTP/S 上傳和下載，可以設置臨時 SSL 證書並使用 http 基本身份驗證。`麻省理工學院``Python`


### 遊戲

**[`^ 返回頂部 ^`](#)**

遊戲、遊戲服務器和控制面板。

- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 適用於您的瀏覽器的極簡主義文字冒險遊戲。([演示](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `HTML5`
- [elevatorsaga](https://play.elevatorsaga.com/) - 電梯編程遊戲。([源代碼](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
- [EmuLinkerSF](https://emulinker.org) - EmuLinkerSF 是一個開源的 Kaillera 服務器。Kaillera 是一個客戶端/服務器系統，任何模擬器都可以實現它來啟用 Internet 上的網絡遊戲。([源代碼](https://github.com/God-Weapon/EmuLinkerSF)) `GPL-2.0` `Java`
- [Hextris](https://github.com/Hextris/hextris) - 受俄羅斯方塊啟發的快節奏 HTML5 益智遊戲。([演示](https://hextris.github.io/hextris)) `GPL-3.0` `HTML5`
- [綠龍傳奇](https://github.com/lotgd/core) - 綠龍傳奇是由 Eric Stevens 和 JT Traub 最初開發的文本角色扮演遊戲，是對經典的翻拍和致敬Seth Able Robinson 的 BBS Door 遊戲，《紅龍傳奇》。([演示](http://lotgd.net/)) `AGPL-3.0` `PHP`
- [Lila](https://lichess.org/) - 為 lichess.org 提供支持的永遠免費、無廣告和開源的國際象棋服務器，帶有官方 iOS 和 Android 客戶端應用程序。([源代碼](https://github.com/ornicar/lila)) `AGPL-3.0` `Scala`
- [Mindustry](https://mindustrygame.github.io/) - 類似異星工廠的塔防遊戲。建立生產鏈以聚集更多資源，並建立復雜的設施。([源代碼](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [Minetest](https://www.minetest.net/) - 一個開源體素遊戲引擎。玩我們的眾多遊戲之一，根據自己的喜好修改遊戲，製作自己的遊戲，或在多人服務器上玩。([源代碼](https://github.com/minetest/minetest)) `LGPL-2.1/CC-BY-SA-3.0/Other` `C++`
- [MTA:SA](https://mtasa.com/) `⚠` - Multi Theft Auto (MTA) 是一個軟件項目，它為 Rockstar North 的俠盜獵車手系列遊戲添加了網絡遊戲功能，其中沒有此功能最初發現。([源代碼](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [Net64+](https://net64-mod.github.io) `⚠` - Net64 aka SM64O 允許在在線多人模式下玩超級馬里奧 64。Net64+ 是該程序的官方延續，並具有集成的服務器列表。([源碼](https://github.com/Tarnadas/net64plus-server/), [客戶端](https://github.com/Tarnadas/net64plus/))`MIT``Nodejs`
- [node-virtual-gamepads](https://github.com/jehervy/node-virtual-gamepads) - 將您的智能手機變成遠程 Linux 操作系統機器的遊戲控制器、鍵盤或觸摸板。`MIT` `Nodejs/CoffeScript`
- [piqueserver](https://github.com/piqueserver/piqueserver) - openspades 服務器，可破壞體素世界中的第一人稱射擊遊戲。([客戶端](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人遊戲。`麻省理工學院``Python`
- [QuakeJS](https://github.com/begleysm/quakejs) - QuakeJS 是 ioquake3 到 Javascript 的一個端口，可以在瀏覽器中播放。`麻省理工學院` `Nodejs`
- [Quizmaster](https://github.com/nymanjens/quizmaster) - 用於進行測驗的網絡應用程序，包括供玩家輸入答案的頁面。`Apache-2.0` `Scala`
- [RconCli](https://github.com/gorcon/rcon-cli) - 使用 RCON 協議在遠程 Valve Source 專用服務器上執行查詢的 CLI。`麻省理工學院``去`
- [SourceBans++](https://sbpp.github.io) - 在 Source 引擎上運行的遊戲的管理、禁令和通信管理系統。([源代碼](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Teeworlds](https://www.teeworlds.com) - 開源 2D 復古多人射擊遊戲。([源代碼](https://github.com/teeworlds/teeworlds)) `BSD-3-Clause/Other` `C++`
- [韋諾之戰](https://github.com/wesnoth/wesnoth) - 韋諾之戰是一款開源的回合製戰術策略遊戲，具有高度幻想主題，具有單人遊戲和在線/熱門多人遊戲戰鬥。`GPL-2.0` `C++`
- [Wordle](https://reactle.vercel.app/) - 一個開源 Wordle 遊戲。在六次嘗試中猜出 Wordle。每個猜測必須是一個有效的五個字母的單詞。([源代碼](https://github.com/cwackerfuss/react-wordle)) `MIT` `Nodejs`
- [Zero-K](https://zero-k.info/) - Springrts 引擎上的開源。Zero-K 是一款傳統的實時戰略遊戲，通過地形操縱、物理和大量獨特單位來關注玩家的創造力——同時保持平衡以支持競爭性遊戲。([源代碼](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 網關和終端共享

**[`^ 返回頂部 ^`](#)**

- [asciinema](https://github.com/asciinema/asciinema-server) - 用於託管 asciicast 的 Web 應用程序。([Demo](https://asciinema.org/)) `Apache-2.0` `Elixir/Docker`
- [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One 是一個基於 HTML5 Web 的終端模擬器和 SSH 客戶端。([源代碼](https://github.com/liftoff/GateOne)) `AGPL-3.0` `Python`
- [Guacamole](https://guacamole.apache.org) - Guacamole 是一個無客戶端遠程桌面網關。它支持 VNC 和 RDP 等標準協議。([源代碼](https://github.com/glyptodon/)) `Apache-2.0` `Java/C`
- [Neko](https://neko.m1k1o.net) - 在 Docker 中運行的自託管虛擬瀏覽器（rabb.it 克隆）。([源代碼](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [oneye](https://oneye-project.org/) - 使用任何瀏覽器從任何地方訪問您的數據的雲軟件。([Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)) `AGPL-3.0` `PHP`
- [OS.js](https://www.os-js.org/) - 具有成熟的窗口管理器、應用程序 API、GUI 工具包和文件系統抽象的瀏覽器桌面實現。([Demo](https://demo.os-js.org/), [Source Code](https://github.com/os-js/OS.js)) `BSD-2-Clause` `Nodejs `
- [ShellHub](https://www.shellhub.io) - ShellHub 是現代 SSH 服務器，用於通過命令行（使用任何 SSH 客戶端）或基於 Web 的用戶界面遠程訪問 linux 設備，旨在替代 sshd。將 ShellHub 視為邊緣和雲計算的集中式 SSH。([源代碼](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Go/Other`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty 是為 Web 設計的 SSH 和 Telnet 連接器。`AGPL-3.0` `Go/Docker`
- [Teleport](https://goteleport.com/) - SSH、Kubernetes、Web 應用程序和數據庫的證書頒發機構和訪問平面。([源代碼](https://github.com/gravitational/teleport)) `Apache-2.0` `Go`
- [tmate](https://tmate.io/) - 即時終端分享。([源代碼](https://github.com/tmate-io/tmate)) `ISC` `C`


###家譜

**[`^ 返回頂部 ^`](#)**

- [Genea.app](https://genea.app/) - Genea 是一種隱私設計和開源工具，任何人都可以使用它來創作或編輯他們的家譜。數據以 GEDCOM 格式存儲，所有處理都在瀏覽器中完成。([源代碼](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb 是一個用 OCaml 編寫的開源家譜軟件。它帶有一個 Web 界面，可以離線使用或作為 Web 服務使用。([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [webtrees](https://www.webtrees.net) - Webtrees 是網絡領先的在線協作家譜應用程序。([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPL -3.0``PHP`


### 群件

**[`^ 返回頂部 ^`](#)**

- [BlueMind](https://www.bluemind.net/en/) - 具有電子郵件、日曆、地址簿、交換主動同步、交換 MAPI 協議支持的群件。([源代碼](https://forge.bluemind.net/stash/projects/BM/repos/bluemind-public/browse)) `AGPL-3.0` `Java`
- [Citadel](https://www.citadel.org/doku.php) - 群件，包括電子郵件、日曆/日程安排、地址簿、論壇、郵件列表、IM、wiki 和博客引擎、RSS 聚合等。([源代碼](https://www.citadel.org/source.html)) `GPL-3.0` `C`
- [Corteza](https://cortezaproject.org) - CRM 包括統一的工作空間、企業消息傳遞和低代碼環境，用於快速安全地交付基於記錄的管理解決方案。([Demo](https://latest.cortezaproject.org), [Source Code](https://github.com/cortezaproject/corteza-server)) `Apache-2.0` `Go`
- [Cozy Cloud](https://cozy.io) - 個人云，您可以在其中管理和同步您的聯繫人、文件和日曆，並通過一個充滿社區貢獻的應用商店管理您的預算。([源碼](https://github.com/cozy)) `GPL-3.0` `Nodejs`
- [egroupware](https://www.egroupware.org/) - 軟件套件，包括日曆、地址簿、記事本、項目管理工具、客戶關係管理工具 (CRM)、知識管理工具、wiki 和 CMS。([源碼](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [EspoCRM](https://www.espocrm.com/) - 前端設計為單頁應用程序和 REST API 的 CRM。([Demo](https://demo.espocrm.com/), [Source Code](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- [Group Office](https://www.group-office.com) - Group-Office 是一個企業CRM和群件工具。與同事和客戶在線共享項目、日曆、文件和電子郵件。([源代碼](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Horde](https://www.horde.org/) - Horde 項目是關於創建基於 PHP 和 Horde 框架的高質量開源應用程序和庫。([Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)) `GPL-2.0` `PHP`
- [HRCloud2](https://github.com/zelon88/HRCloud2) - 功能齊全的家庭託管雲驅動器、個人助理、應用程序啟動器、文件轉換器、流媒體、共享工具等。`GPL-3.0` `PHP`
- [Kolab](https://kolab.org/) - Kolab 社區是一個統一的通信和協作系統。([源代碼](https://git.kolab.org/)) `GPL-2.0/LGPL-2.1/GPL-3.0` `C++/Python/PHP`
- [Kopano](https://kopano.com/) - 群件套件，包括電子郵件、日曆、任務、待辦事項和筆記。具有現代 WebApp、DeskApp 和通過 Z-Push/ActiveSync 進行的移動訪問。([Demo](https://demo.kopano.com), [Source Code](https://stash.kopano.io)) `AGPL-3.0` `C/Python/PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings 提供視頻會議、即時通訊、白板、協同文檔編輯等群件工具，使用 Red5 Streaming Server 的 API 功能進行 Remoting 和 Streaming . ([源代碼](https://openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- [SOGo](https://sogo.nu/) - SOGo 提供多種訪問日曆和消息數據的方式。CalDAV、CardDAV、GroupDAV 以及 ActiveSync，包括本機 Outlook 兼容性和 Web 界面。([Demo](https://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)) `LGPL-2.1` `Objective-C`
- [SuiteCRM](https://suitecrm.com) - 屢獲殊榮的企業級開源 CRM。([源代碼](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- [Tine 2.0](https://www.tine20.org) - 聯繫人、日曆、任務、WebDAV、ActiveSync、VOIP、郵件客戶端、CRM、銷售、項目、Timetracker。([Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)) `AGPL-3.0/Other` `PHP`
- [Tracim](https://github.com/tracim/tracim) - 團隊協作的協作平台：文件、線程、筆記、議程等。`AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - 電子郵件、日曆、具有 Web 界面和大量集成的協作服務器。([源代碼](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 人力資源管理 (HRM)

**[`^ 返回頂部 ^`](#)**

- [admidio](https://www.admidio.org/) - Admidio 是一個免費的開源用戶管理系統，用於組織和團體的網站。該系統具有靈活的角色模型，因此可以反映您組織的結構和權限。([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP`
- [IceHrm](https://icehrm.com/) - IceHrm 員工管理系統允許公司集中機密的員工信息。([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm)) `Apache-2.0` `PHP`
- [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM 是一個全面的 HRM 系統，可捕獲任何企業所需的所有基本功能。([源代碼](https://sourceforge.net/projects/orangehrm/)) `GPL-2.0` `PHP`
- [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo 是一個 HRM 系統，可以輕鬆配置以滿足您的組織需求。([源代碼](https://github.com/sapplica/sentrifugo)) `GPL-3.0` `PHP`
- [TimeOff.Management](https://timeoff.management) - 適用於中小型企業的簡單而強大的缺勤管理軟件。([Demo](https://app.timeoff.management), [Source Code](https://github.com/timeoff-management/timeoff-management-application)) `MIT` `Nodejs`


### 物聯網 (IoT)

**[`^ 返回頂部 ^`](#)**

- [DeviceHive](https://www.devicehive.com/) - 具有廣泛集成選項的開源物聯網平台。([Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java`
- [Domoticz](https://www.domoticz.com/) - 家庭自動化系統，可讓您監控和配置各種設備，如：燈、開關、各種傳感器/儀表，如溫度、雨、風、紫外線、電火花、煤氣, 水等等。([源代碼](https://github.com/domoticz/domoticz), [客戶端](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++`
- [FHEM](https://fhem.de/fhem.html) - FHEM 用於自動化家庭中的常見任務，例如開關燈和供暖。它還可用於記錄溫度或功耗等事件。您可以通過網絡或智能手機前端、telnet 或 TCP/IP 直接控制它。([源代碼](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [Gladys](https://gladysassistant.com/) - Gladys 是隱私優先的開源家庭助理。([源代碼](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs`
- [家庭助手](https://home-assistant.io/) - 開源家庭自動化平台。([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/core)) `Apache-2.0` `Python`
- [Node RED](https://nodered.org/) - 基於瀏覽器的流程編輯器，可幫助您連接硬件設備、API 和在線服務以創建物聯網解決方案。([源碼](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- [openHAB](https://www.openhab.org) - 用於家庭自動化的供應商和技術無關的開源軟件。([源代碼](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 100% 開源物聯網平台 - 物聯網資產管理、流程規則和 WHEN-THEN 規則、數據可視化、邊緣網關。([Demo](https://demo.openremote.io/), [Source Code](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [SIP 灌溉控制](https://dan-in-ca.github.io/SIP/) - 灑水/灌溉控制的開源軟件。([源代碼](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [Thingsboard](https://thingsboard.io/) - 開源物聯網平台 - 設備管理、數據收集、處理和可視化。([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java`
- [Thingspeak](https://thingspeak.com/) - 開源“物聯網”應用程序和 API，使用 HTTP 從事物中存儲和檢索數據。([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL-3.0` `Ruby`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings 是 Web of Things 的開源實現，包括 WebThings Gateway 和 WebThings Framework。([源碼](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 知識管理工具

**[`^ 返回頂部 ^`](#)**

- [Mindmaps](https://github.com/drichard/mindmaps) - 開源、離線能力、思維導圖應用程序。([演示](https://www.mindmaps.app)) `AGPL-3.0` `HTML5`
- [My Mind](https://github.com/ondras/my-mind) - 用於創建和管理思維導圖的 Web 應用程序。([演示](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
- [Weaviate](https://weaviate.io/) - 集成了可擴展機器學習模型（GraphQL 和 RESTful API）的雲原生實時矢量搜索引擎。([Demo](https://github.com/semi-technologies/semantic-search-through-wikipedia-with-weaviate/), [源代碼](https://github.com/semi-technologies/weaviate) , [客戶端](https://weaviate.io/developers/weaviate/current/client-libraries/index.html)) `BSD-3-Clause` `Go`


### 學習和課程

**[`^ 返回頂部 ^`](#)**

- [Canvas LMS](https://www.canvaslms.com/) - Canvas 是值得信賴的開源學習管理系統 (LMS)，它正在徹底改變我們的教育方式。([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - Chamilo LMS 允許您創建一個虛擬校園，以提供在線或半在線培訓。([源代碼](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [edX](https://www.edx.org/) - Open edX 平台是支持 edX.org 的開源代碼。([源代碼](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://www.gibbonedu.org/) - 靈活的開源學校管理平台，旨在讓教師、學生、家長和領導的生活更美好。([源代碼](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [ILIAS](https://www.ilias.de) - ILIAS 是一個學習管理系統，可以應付任何你扔給它的東西。([Demo](https://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [Mahara](https://mahara.org/) - 開源全功能網絡應用程序，用於構建學生電子檔案袋。([源代碼](https://github.com/MaharaProject/mahara)) `GPL-3.0` `PHP`
- [Moodle](https://moodle.org/) - Moodle 是一個學習和課程平台，擁有全球最大的開源社區之一。([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass 是一種先進的電子學習解決方案，可以增強教學和學習過程。([Demo](https://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT 是一個基於網絡的學習管理系統，用於教學、教育、評估和交流。([Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [RELATE](https://documen.tician.de/relate/) - RELATE 是一個基於網絡的課件包，包括以下功能：靈活的規則、統計、多課程支持、課程日曆。([源代碼](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS，用於學校管理的免費學生信息系統。([Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- [Sakai](https://www.sakaiproject.org/) - Sakai 項目為教學、學習、研究和其他協作提供了一個靈活且功能豐富的環境。([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECL-2.0` `Java`
- [Vocascan](https://vocascan.com/) - 高度可配置的詞彙訓練器。([源代碼](https://github.com/vocascan/vocascan-server), [客戶端](https://github.com/vocascan/vocascan-desktop)) `Apache-2.0` `Nodejs`


### 地圖和全球定位系統 (GPS)

**[`^ 返回頂部 ^`](#)**

_另見：[awesome-gis](https://github.com/sshuair/awesome-gis)_

- [Geo2tz](https://github.com/noandrea/geo2tz) - 從地理坐標（緯度、經度）獲取時區。`麻省理工學院` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 使用 OpenStreetMap 的快速路由庫和服務器。([源碼](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [Hauk](https://github.com/bilde2910/Hauk) - 易於設置的位置共享平台，可讓您臨時與任何人實時共享您的位置。([演示](https://github.com/bilde2910/Hauk#demo-server)) `Apache-2.0` `PHP`
- [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - 共享自定義 OSM 地圖的工具。支持帶註釋的標記、多邊形、線條、多格式導入/導出、多層、短鏈接。([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
- [Nominatim](https://nominatim.org/) - 在 OpenStreetMap 數據上進行反向地理編碼（地址 -> 坐標）的服務器應用程序。([源代碼](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [開源路由機 (OSRM)](http://project-osrm.org/) - 高性能路由引擎，旨在在 OpenStreetMap 數據上運行並提供 HTTP API、C++ 庫接口和 Nodejs 包裝器。([Demo](https://map.project-osrm.org/), [Source Code](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++ `
- [OpenGTS](http://www.opengts.org/) - 入門級車隊跟踪系統。支持各種跟踪設備和協議。帶有豐富的網絡界面和報告功能。([Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache-2.0` `Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 創建免費可編輯世界地圖的合作項目。([源代碼](https://github.com/openstreetmap/openstreetmap-website), [客戶端](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基於 OpenStreetMap 數據並使用已發布的 GTFS 格式數據來建議使用當地公共交通系統的路線的多式聯運旅行計劃軟件。([源代碼](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [Orion](https://github.com/LINKIWI/orion-web) - 強大的符合 OwnTracks API 的網絡位置數據可視化前端。([Demo](https://linkiwi.github.io/orion-web/)) `MIT` `Python/Nodejs`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - 存儲和訪問由 [OwnTracks](https://owntracks.org/) 位置跟踪應用程序發布的數據。`GPL-2.0` `C/Lua`
- [TileServer GL](https://tileserver.readthedocs.io/) - 具有 GL 樣式的矢量和柵格地圖。Mapbox GL Native 的服務器端渲染。Mapbox GL JS、Android、iOS、Leaflet、OpenLayers、GIS 通過 WMTS 等的地圖瓦片服務器（[源代碼](https://github.com/maptiler/tileserver-gl)）`BSD-2-Clause` `Nodejs`
- [TileServer PHP](https://www.maptiler.com/server/) - 提供來自任何 PHP 主機的地圖圖塊。([源代碼](https://github.com/maptiler/tileserver-php)) `BSD-2-Clause` `PHP`
- [Traccar](https://www.traccar.org/) - 用於跟踪 GPS 位置的 Java 應用程序。支持大量跟踪設備和協議，擁有 Android 和 iOS 應用程序。有一個網絡界面來查看您的旅行。([Demo](https://demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- [uMap](https://umap.openstreetmap.fr/en/) - 在一分鐘內創建帶有 OpenStreetMap 圖層的地圖並將它們嵌入到您的站點中。([源碼](https://github.com/umap-project/umap)) `WTFPL` `Python`
- [μlogger](https://github.com/bfabiszewski/ulogger-server) - 實時收集用戶的地理位置並在網站上顯示他們的 GPS 軌跡。([演示](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### 媒體流

**[`^ 返回頂部 ^`](#)**

**請訪問 [媒體流 - 音頻流](#media-streaming---audio-streaming)、[媒體流 - 多媒體流](#media-streaming---mutimedia-streaming)、[媒體流 - 視頻流](#media-streaming---視頻流)**

_另見：[流媒體系統列表 - 維基百科](https://en.wikipedia.org/wiki/List_of_streaming_media_systems)，[流媒體系統比較 - 維基百科](https://en.wikipedia.org/wiki/比較_of_streaming_media_systems)_


### 媒體流 - 音頻流

**[`^ 返回頂部 ^`](#)**

- [Airsonic Advanced](https://github.com/airsonic-advanced/airsonic-advanced/) - 基於 Airsonic 的基於 Web 的開源媒體流媒體和點唱機，具有多項關鍵性能和功能增強。`GPL-3.0` `Java`
- [Amp ache](https://ampache.org/) - 基於 Web 的音頻/視頻流應用程序。([Demo](https://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audioserve](https://github.com/izderadicka/audioserve) - 簡單的個人服務器，用於提供目錄中的音頻文件（有聲讀物、音樂、播客......）。專注於簡單性並支持客戶端之間的播放位置同步。`麻省理工學院``銹`
- [AzuraCast](https://www.azuracast.com/) - 現代且可訪問的自託管網絡廣播管理套件。([源代碼](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `PHP`
- [Beets](https://beets.io/) - 音樂庫管理器和 MusicBrainz 標記器（命令行和 Web 界面）。([源代碼](https://github.com/beetbox/beets)) `MIT` `Python`
- [Black Candy](https://github.com/aidewoode/black_candy) - 使用 Rails 和 Stimulus 構建的音樂流媒體服務器。`麻省理工學院``紅寶石`
- [Compactd](https://github.com/compactd/compactd) - 支持添加內容的遠程音樂播放器。`麻省理工學院` `Nodejs`
- [euterpe](https://listen-to-euterpe.eu) - 帶有 RESTful API 和 Web 界面的自託管音樂流媒體服務器。([Demo](https://listen-to-euterpe.eu/demo), [Source Code](https://github.com/ironsmile/euterpe)) `GPL-3.0` `Go`
- [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - 與來自 Youtube 和 Soundcloud 的朋友分享音樂。([Demo](https://friends-radio.herokuapp.com/)) `MIT` `Nodejs`
- [Funkwhale](https://funkwhale.audio/) - 現代、基於網絡、歡樂、多用戶和免費的音樂服務器。([Demo](https://demo.funkwhale.audio/), [Source Code](https://code.eliotberriot.com/funkwhale/funkwhale)) `BSD-3-Clause` `Python/Django`
- [GNU FM](https://gnu.io/fm/) - 運行音樂社區網站，替代 last.fm。([源代碼](https://git.savannah.gnu.org/cgit/librefm.git/)) `AGPL-3.0` `PHP`
- [gonic](https://github.com/sentriz/gonic) - 輕量級音樂流媒體服務器。亞音速兼容。`GPL-3.0` `Go`
- [Groove Basin](https://github.com/andrewrk/groovebasin) - 具有受 Amarok 1.4 啟發的基於 Web 的用戶界面的音樂播放器服務器。`麻省理工學院` `Nodejs`
- [koel](https://koel.dev/) - 可以工作的個人音樂流媒體服務器。([Demo](https://demo.koel.dev/), [Source Code](https://github.com/koel/koel)) `MIT` `PHP`
- [KooZic](https://koozic.net/) - 具有強大播放列表功能和亞音速兼容性的音樂服務器。([Demo](https://demo.koozic.net/public), [Source Code](https://github.com/DocMarty84/koozic)) `LGPL-3.0/MIT` `Python`
- [LibreTime](https://libretime.org) - 簡單的開源平台，可讓您在網絡上廣播流媒體廣播（[Airtime](https://github.com/sourcefabric/Airtime) 的分支）。([源代碼](https://github.com/LibreTime/libretime)) `AGPL-3.0` `PHP`
- [LMS](https://github.com/epoupon/lms) - 使用網絡界面訪問您的自託管音樂。([演示](https://lms.demo.poupon.io/)) `GPL-3.0` `C++`
- [moOde Audio](https://moodeaudio.org/) - 為美妙的 Raspberry Pi 系列單板計算機提供發燒友品質的音樂播放。([源碼](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Moped](https://github.com/martijnboland/moped) - Mopidy 音樂服務器的響應式 HTML5 + Javascript 客戶端。`麻省理工學院` `HTML5`
- [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Mopidy 音樂服務器的 Web 客戶端。`Apache-2.0` `HTML5`
- [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - 專為派對設計的 Mopidy 網絡擴展！讓您的客人管理聲音。`Apache-2.0` `Python`
- [Mopidy](https://docs.mopidy.com/) - 可擴展的音樂服務器。提供 mpd API 的超集，以及與 Spotify、SoundCloud 等第三方服務的集成。（[源代碼](https://github.com/mopidy/mopidy)）`Apache-2.0``Python`
- [mpd](https://www.musicpd.org/) - 遠程播放音樂、串流音樂、處理和組織播放列表的守護進程。許多客戶可用。([源代碼](https://github.com/MusicPlayerDaemon/MPD), [客戶端](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 帶有 GUI 管理工具的音樂流媒體服務器。在 Mac、Windows 和 Linux 上運行。([源碼](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- [musikcube](https://musikcube.com/) - 帶有 Linux/macOS/Windows/Android 客戶端的流式音頻服務器。([源代碼](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++`
- [Navidrome 音樂服務器](https://www.navidrome.org) - 現代音樂服務器和流媒體，與 Subsonic/Airsonic 兼容。([Demo](https://www.navidrome.org/demo), [Source Code](https://github.com/navidrome/navidrome), [Clients](https://www.navidrome.org/ docs/overview/#apps)) `GPL-3.0` `Go/Javascript`
- [Polaris](https://github.com/agersant/polaris) - 針對大型音樂收藏、易用性和高性能優化的音樂瀏覽和流媒體應用程序。`麻省理工學院``銹`
- [Raveberry](https://github.com/raveberry/raveberry) - 專注於參與的多用戶音樂服務器。([演示](https://demo.raveberry.party/)) `LGPL-3.0` `Python`
- [Snapcast](https://github.com/badaix/snapcast) - 同步多房間音頻服務器。`GPL-3.0` `C++`
- [Stretto](https://github.com/benkaiser/stretto) - 帶有 Youtube/Soundcloud 導入和 iTunes/Spotify 發現功能的音樂播放器。([Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic 服務器 API 的 Python 實現。`AGPL-3.0` `Python`
- [Volumio](https://volumio.org/) - 一個免費和開源的 Linux 發行版，專為音樂播放而設計和微調。([源碼](https://github.com/volumio/Volumio2)) `GPL-3.0` `Nodejs`
- [ympd](https://www.ympd.org/) - 用 C 語言編寫的獨立 MPD Web GUI，利用 Websockets 和 Bootstrap/JS。([源代碼](https://github.com/notandy/ympd)) `GPL-2.0` `C`


### 媒體流 - 多媒體流

**[`^ 返回頂部 ^`](#)**

- [Dim](https://github.com/Dusk-Labs/dim) - Dim 是一個受黑暗勢力推動的自託管媒體管理器。通過最少的設置，Dim 將組織和美化您的媒體收藏，讓您隨時隨地訪問和播放它們。`GPL-2.0` `Rust`
- [Gerbera](https://gerbera.io/) - Gerbera 是一個 UPnP 媒體服務器。它允許您在整個家庭網絡中流式傳輸您的數字媒體，並在各種 UPnP 兼容設備上收聽/觀看。([源代碼](https://github.com/gerbera/gerbera)) `GPL-2.0` `C++`
- [homehost](https://github.com/ridhwaans/homehost) `⚠` - 自託管 React + Redux 應用程序，可流式傳輸您的媒體收藏（音樂、電影、書籍、播客、漫畫等）。`麻省理工學院` `Nodejs`
- [Icecast 2](https://icecast.org) - 流式音頻/視頻服務器，可用於創建互聯網廣播電台或私人點唱機以及介於兩者之間的許多東西。([源代碼](https://gitlab.xiph.org/xiph/icecast-server), [客戶端](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 用於音頻、視頻、書籍、漫畫和照片的媒體服務器，具有時尚的界面和強大的轉碼功能。幾乎所有現代平台都有客戶端，包括 Roku、Android TV、iOS 和 Kodi。([Demo](https://demo.jellyfin.org/stable), [Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- [Karaoke Forever](https://www.karaoke-forever.com) - 舉辦精彩的卡拉 OK 派對，每個人都可以輕鬆地從手機的網絡瀏覽器中查找和排隊歌曲。該播放器也是基於瀏覽器的，支持 MP3+G、MP4 和 WebGL 可視化。([源代碼](https://www.karaoke-forever.com/repo)) `ISC` `Nodejs`
- [LBRY](https://lbry.com/) - 是一個安全、開放和社區運營的數字市場，旨在取代 Youtube 和亞馬遜。([Demo](https://lbry.tv/), [Source Code](https://github.com/lbryio/lbry.com), [Clients](https://github.com/lbryio/lbry -桌面））`麻省理工學院``PHP`
- [MistServer](https://mistserver.org/) - 適用於任何流媒體環境的流媒體服務器。([源代碼](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - NymphCast 是一種 Chromecast 替代方案，可將您選擇的支持 Linux 的硬件轉換為電視或有源揚聲器的音頻和視頻源。([源代碼](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Podify](https://www.podify.org/) - 允許您從 youtube-dl 支持的任何來源下載視頻和音頻，並使用您喜歡的播客應用訂閱和觀看這些下載。([源代碼](https://github.com/podify-org/podify/)) `GPL-3.0` `Ruby`
- [ReadyMedia](https://sourceforge.net/projects/minidlna/) - 簡單的媒體服務器軟件，旨在完全兼容 DLNA/UPnP-AV 客戶端。以前稱為 MiniDLNA。([源代碼](https://sourceforge.net/p/minidlna/git/ci/master/tree/))​​ `GPL-2.0` `C`
- [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel 是一個 UPnP AV 媒體服務器，可讓您輕鬆共享音頻、視頻和圖片。媒體播放器軟件可以使用 Rygel 成為可以由 UPnP 或 DLNA 控制器遠程控制的 MediaRenderer。([源代碼](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- [SheetAble](https://sheetable.net) - 適用於所有音樂愛好者的自託管樂譜整理軟件。為任何類型的樂器上傳和整理您的工作表。([源代碼](https://github.com/SheetAble/SheetAble)) `AGPL-3.0` `Go`
- [Stash](https://stashapp.cc) - 用於成人媒體存儲的基於網絡的圖書館組織者和播放器，具有自動標記和元數據抓取支持。([源代碼](https://github.com/stashapp/stash)) `AGPL-3.0` `Go`
- [üWave](https://u-wave.net/) `⚠` - üWave 是一個自託管的協作收聽平台。用戶輪流播放來自各種媒體資源（如 YouTube 和 SoundCloud）的媒體——歌曲、談話、遊戲視頻或其他任何內容。([Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### 媒體流 - 視頻流

**[`^ 返回頂部 ^`](#)**

- [Bluecherry](https://www.bluecherrydvr.com/) - 支持 IP 和模擬攝像機的閉路電視 (CCTV) 軟件應用程序。([源代碼](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- [CyTube](https://github.com/calzoneman/sync) - CyTube 是一個為任意數量的頻道提供媒體同步、聊天等功能的網絡應用程序。([Demo](https://cytu.be)) `MIT` `Nodejs`
- [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - 完全響應式界面，可在您的 HTPC 上管理您喜愛的所有媒體。`麻省理工學院``Python`
- [Invidious](https://github.com/iv-org/invidious) - `⚠` Invidious 是 YouTube 的替代前端。([演示](https://docs.invidious.io/instances/)) `AGPL-3.0` `Crystal`
- [Kerberos.io](https://kerberos.io) - Kerberos.io 是一個視頻監控解決方案，它適用於任何攝像頭和每台基於 Linux 的機器（Raspberry Pi、Docker、Kubernetes 集群）。([Demo](https://demo.kerberos.io/), [Source Code](https://github.com/kerberos-io/kerberos-docker)) `MIT` `C++`
- [MediaCMS](https://mediacms.io) - MediaCMS 是一個現代的、功能齊全的開源視頻和媒體 CMS，用 Python/Django/React 編寫，具有 REST API。([源代碼](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [Myflix](https://github.com/farfalleflickan/Myflix) `⚠` - 自託管、超輕量級的 Netflix 替代方案。`麻省理工學院``殼牌`
- [Oblecto](https://github.com/robinp7720/Oblecto) `⚠` - 帶有響應式 Vue.js 前端的電影和電視節目媒體服務器。它具有強大的轉碼支持以及與朋友共享庫的聯合功能。`AGPL-3.0` `Nodejs`
- [Oddworks](https://gitlab.com/oddnetworks/oddworks/core) - Oddworks 是一個開源視頻分發平台，旨在通過 Roku、Apple iOS/tvOS、Google Android 和亞馬遜 FireTV。`麻省理工學院` `Nodejs`
- [Olaris](https://gitlab.com/olaris/olaris-server) - Olaris 是一個開源、社區驅動的媒體管理器和轉碼服務器。`GPL-3.0` `Go`
- [開放流媒體平台](https://openstreamingplatform.com) - 用於直播和點播視頻流的自託管替代 Twitch 和 Youtube Live。([源碼](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- [OvenMediaEngine](https://ovenmediaengine.com) - OvenMediaEngine 是一個可自我託管的開源流媒體服務器，具有亞秒級延遲。([Demo](https://demo.ovenplayer.com), [Source Code](https://github.com/AirenSoft/OvenMediaEngine)) `GPL-3.0` `C++`
- [Owncast](https://github.com/owncast/owncast) - Owncast 是一個開源的、自託管的、去中心化的、單用戶實時視頻流和聊天服務器，用於運行您自己的實時流，其風格類似於大型主流選擇。`麻省理工學院``去`
- [PeerTube](https://joinpeertube.org/en/) - 直接在網絡瀏覽器中使用 P2P (BitTorrent) 的去中心化視頻流平台。([源代碼](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Radium](https://github.com/Zibbp/Radium) - 利用 HLS 的 VOD 功能同步流和視頻播放。為電影之夜而開發，但有許多用例。([Demo](https://radium-demo.herokuapp.com)) `MIT` `Nodejs/Docker`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 自託管 torrent 視頻流服務/torrent 客戶端，允許在瀏覽器或 Chromecast/AppleTV/Smart TV 中搜索和播放來自 torrent 的視頻。`麻省理工學院` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer 允許您在沒有流媒體提供商的情況下在您的網站上進行 h.264 實時視頻流式傳輸。([源碼](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [ShinobiCE](https://gitlab.com/Shinobi-Systems/ShinobiCE) - 用 Node 編寫的開源 CCTV 軟件，同時支持 IP 和本地攝像機。`AGPL-3.0/GPL-3.0` `Nodejs`
- [Streama](https://github.com/streamaserver/streama) - 自託管流媒體服務器。`麻省理工學院``Java`
- [SyncTube](https://github.com/RblSb/SyncTube) - 輕量級和非常簡單的設置 CyTube 替代品與朋友一起觀看視頻和聊天。([Demo](https://synctube-example.herokuapp.com/)) `MIT` `Nodejs/Haxe`
- [Tube](https://git.mills.io/prologic/tube) - 類似 Youtube 的（_無需審查和您不需要的功能！_）用 Go 編寫的視頻共享應用程序，還支持自動轉碼為 MP4 H.265 AAC、多個集合和 RSS 提要。([Demo](https://tube.mills.io)) `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 支持大多數多媒體文件以及 DVD、音頻 CD、VCD 和各種流媒體協議的跨平台多媒體播放器客戶端和服務器。([源代碼](https://github.com/videolan/vlc)) `GPL-2.0` `C`
- [Zoneminder](https://www.zoneminder.com/) - 支持 IP、USB 和模擬攝像機的閉路電視 (CCTV) 軟件應用程序。([源代碼](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP`


＃＃＃ 各種各樣的

**[`^ 返回頂部 ^`](#)**

- [2FAuth](https://github.com/Bubka/2FAuth) - 用於管理您的雙因素身份驗證 (2FA) 帳戶並生成其安全代碼的 Web 應用程序。([演示](https://demo.2fauth.app/)) `AGPL-3.0` `PHP`
- [411](https://github.com/etsy/411) - 警報管理 Web 應用程序。`麻省理工學院` `PHP`
- [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub 是一個從 GitHub 發布中​​獲取警報的簡單工具。`麻省理工學院` `Nodejs`
- [Anchr](https://anchr.io) - Anchr 是一個用於互聯網上小任務的工具箱，包括書籤收藏、URL 縮短和（加密）圖像上傳。([源代碼](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [asciiflow](https://asciiflow.com/) - 流程圖繪圖工具。([源碼](https://github.com/lewish/asciiflow)) `MIT` `Nodejs`
- [CapRover](https://caprover.com/) - 在幾分鐘內構建您自己的 PaaS。([Demo](https://captain.server.demo.caprover.com/#/login), [Source Code](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/ Nodejs`
- [changedetection.io](https://github.com/dgtlmoon/changedetection.io) - 用於及時了解網站內容更改的自託管工具。`Apache-2.0` `Python/Docker`
- [CloudBeaver](https://cloudbeaver.io/) - 數據庫自託管管理，支持PostgreSQL、MySQL、SQLite等。DBeaver 的網絡/託管版本。([源碼](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Nodejs`
- [CUPS](https://www.cups.org/) - 通用 Unix 打印系統使用 Internet 打印協議 (IPP) 支持打印到本地和網絡打印機。([源代碼](https://github.com/apple/cups)) `GPL-2.0` `C`
- [Cyber​​Chef](https://github.com/gchq/Cyber​​Chef) - 在 Web 瀏覽器中執行各種操作，例如 AES、DES 和 Blowfish 加密和解密、創建十六進制轉儲、計算哈希等等。([演示](https://gchq.github.io/Cyber​​Chef)) `Apache-2.0` `Javascript`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日記網絡應用程序，保存您每天的個人記憶。包括搜索功能和加密文件上傳。`麻省理工學院``Python`
- [Databunker](https://databunker.org/) - 基於網絡的、自託管的、符合 GDPR 的、用於個人數據或 PII 的安全數據庫。([源碼](https://github.com/securitybunker/databunker)) `MIT` `Go`
- [數字貨幣](https://github.com/Icesofty/Digital-Currency) - 創建您自己的自託管數字貨幣。([Demo](https://tonken.glitch.me/)) `GPL-3.0` `Nodejs`
- [DomainMOD](https://domainmod.org) - 用於在中央位置管理您的域和其他互聯網資產的應用程序。DomainMOD 包括一個數據倉庫框架，允許您導入 WHM/cPanel Web 服務器數據，以便您可以查看、導出和報告您的數據。([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [Firezone](https://www.firez.one/) - 開源 VPN 服務器和基於 WireGuard 的 Linux 出口防火牆，可以輕鬆管理對公司專用網絡的安全遠程訪問。Firezone 易於設置、安全、高性能和自託管。([源代碼](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Ruby`
- [Flox](https://github.com/devfake/flox) `⚠` - 自託管電影、電視劇和動漫觀看列表，採用 3 分評分系統。使用電影數據庫後端獲取信息。([演示](https://flox-demo.pyxl.dev/)) `MIT` `PHP`
- [formspree](https://formspree.io/) `⚠` - 只需將您的表單發送到我們的 URL，我們會將其轉發到您的電子郵件。無需 PHP、Javascript 或註冊。([Demo](https://test.formspree.io/), [Source Code](https://github.com/formspree/formspree)) `AGPL-3.0` `Python`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - 自託管 Google 字體的無憂方式。獲取 eot、ttf、svg、woff 和 woff2 文件 + CSS 片段。([演示](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
- [graph-vl](https://github.com/verifid/graph-vl) - 使用機器學習和 GraphQL 驗證身份文件。`麻省理工學院``Python`
- [Journal](https://github.com/inoda/journal) - 具有加密條目和共享功能的簡單日記。`麻省理工學院``紅寶石`
- [King Phisher](https://github.com/rsmusllp/king-phisher) - King Phisher 是一個通過模擬真實世界的網絡釣魚攻擊來測試和提升用戶意識的工具。`BSD-3-Clause` `Python`
- [Koillection](https://koillection.github.io/) - Koillection 是一項允許用戶管理任何類型的收藏的服務。([源代碼](https://github.com/koillection/koillection)) `MIT` `PHP`
- [Lancache](https://lancache.net) `⚠` - 局域網派對遊戲緩存變得簡單。([源碼](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [MailyGo](https://codeberg.org/jlelse/MailyGo) - MailyGo 是一個用 Go 編寫的小工具，允許通過電子郵件從靜態網站發送 HTML 表單，例如從沒有動態後端的靜態網站。`麻省理工學院``去`
- [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB 是用於現有數據庫的開源自託管 AI 層，可讓您輕鬆開發、訓練和部署最先進的機器學習模型使用標準查詢。`GPL-3.0` `Python`
- [MissionKontrol](https://www.missionkontrol.io) - 可配置的管理面板允許非技術用戶對 MySQL/PostGRES 數據庫上的數據進行 CRUD。([源代碼](https://github.com/Mission-Kontrol/MissionKontrol-rails)) `AGPL-3.0` `Ruby`
- [Monica](https://monicahq.com/) - 個人關係經理，以及一種新的 CRM 來組織與您的朋友和家人的互動。([源代碼](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP`
- [Musical Artifacts](https://musical-artifacts.com/) - 幫助編目、保存和釋放製作音樂所需的文物。([源代碼](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
- [MyPaas](https://github.com/almarklein/mypaas) - 使用 Docker、Traefik 和出色的監控運行您自己的 PaaS。`BSD 2-clause` `Python/Docker`
- [nnmm](https://github.com/Mechazawa/nnmm) - 超微型 pastebin/url minifier _microservice_。`Beerware` `PHP`
- [Noisedash](https://github.com/kaythomas0/noisedash) - 使用音頻工具和用戶可上傳的樣本生成環境噪音/聲音的自託管網絡工具。`AGPL-3.0` `Nodejs`
- [Notica](https://notica.us) - 允許您從終端向桌面或手機發送瀏覽器通知。無需安裝或註冊。([源代碼](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
- [Ombi](https://ombi.io/) - Plex/Emby 的內容請求系統，連接到 SickRage、CouchPotato、Sonarr，具有不斷增長的功能集。([Demo](https://app.ombi.io/), [Source Code](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#`
- [Orchest](https://www.orchest.io/) - 一種用於數據科學的新​​型 IDE。([Demo](https://cloud.orchest.io), [Source Code](https://github.com/orchest/orchest)) `AGPL-3.0` `Docker`
- [oTranscribe](https://github.com/oTranscribe/oTranscribe) - 免費的網絡應用程序，可以減輕轉錄採訪記錄的痛苦。([Demo](https://otranscribe.com/)) `MIT` `Javascript`
- [PassCheck](https://apacketofsweets.github.io/PassCheck/) - 具有一些方便的密碼工具的 Web 應用程序，包括密碼生成器、強度檢查器和 HaveIBeenPwned 違規檢查器。([源代碼](https://github.com/apacketofsweets/PassCheck)) `MIT` `Javascript`
- [Reactive Resume](https://rxresu.me/) - 獨一無二的簡歷生成器，牢記您的隱私。完全安全、可定制、可移植、開源且永遠免費。([Demo](https://rxresu.me/app/dashboard/), [Source Code](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- [ReleaseBell](https://releasebell.com/) - 發送已加星標的 Github 存儲庫的發布通知。([源碼](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- [revealjs](https://revealjs.com) - 使用 HTML 輕鬆創建精美演示文稿的框架。([Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 世界上最受歡迎的免費、開源廣告服務系統。以前稱為 OpenX Adserver 和 phpAdsNew。([源代碼](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0-or-later` `PHP`
- [SANE 網絡掃描](http://sane-project.org/) - 允許遠程客戶端訪問本地主機上可用的圖像採集設備（掃描儀）。([源代碼](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [string.is](https://string.is/) - 面向開發人員的開源、隱私友好型在線字符串工具包。([Demo](https://string.is/), [Source Code](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [TeslaMate](https://github.com/adriankumpf/teslamate) - 一個強大的特斯拉汽車數據記錄器。`麻省理工學院``長生不老藥`
- [Trello Burndown](https://github.com/mtricht/trello-burndown) `⚠` - Trello 板易於使用的 SCRUM 燃盡圖。`麻省理工學院` `Go/Docker`
- [ViMbAdmin](https://www.vimbadmin.net/) - 提供基於網絡的虛擬郵箱管理系統，讓郵件管理員可以輕鬆管理域、郵箱和別名。([Demo](https://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- [網絡字體庫](https://github.com/Finesse/web-fonts-repository) - 簡單的網絡字體託管。谷歌字體替代您自己的字體。`麻省理工學院` `PHP`
- [ytdl-webserver](https://github.com/Algram/ytdl-webserver) - 用於下載 youtube 視頻的 Docker-ready 網絡服務器。`麻省理工學院` `Nodejs`


### 資金、預算和管理

**[`^ 返回頂部 ^`](#)**

_另請參閱：[awesome-sysadmin/IT 資產管理](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Akaunting](https://akaunting.com/) - Akaunting 是一款免費、在線和開源的會計軟件，專為小型企業和自由職業者設計。([源代碼](https://github.com/akaunting/akaunting)) `GPL-3.0` `PHP`
- [Boodle](https://github.com/manuel-uberti/boodle) - Clojure 和 ClojureScript 中的簡單會計單頁應用程序。`EPL-1.0` `Java`
- [BTCPay Server](https://btcpayserver.org/) - 自託管比特幣和其他加密貨幣支付處理器。([Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
- [Budget App](https://github.com/paukiatwee/budgetapp) - Budget App 是一個開源的個人預算應用程序。`Apache-2.0` `Java`
- [budgetzero](https://github.com/budgetzero/budgetzero) - 免費、自託管、開源、信封預算網絡和桌面應用程序。([演示](https://app.budgetzero.io/budget)) `AGPL-3.0` `Nodejs`
- [Crater](https://github.com/bytefury/crater) - 適用於自由職業者和小型企業的免費和開源發票應用程序。([演示](https://demo.craterapp.com/)) `AAL` `PHP`
- [Dot Ledger](https://www.dotledger.com/) - 基於網絡的個人理財工具。([Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)) `Apache-2.0` `Ruby`
- [EasyQuickImport](https://github.com/karser/EasyQuickImport) `⚠` - 幫助您將交易、發票和賬單從 Excel 或 CSV 導入 QuickBooks Desktop 的工具。`麻省理工學院` `PHP`
- [Economizzer](https://www.economizzer.org/) - 一個簡單安全的系統，讓您管理個人資金並實現目標，可通過電腦、平板電腦或智能手機訪問。([Demo](https://github.com/gugoan/economizzer#live-demo), [Source Code](https://github.com/gugoan/economizzer))`MIT``PHP`
- [ExMoney](https://github.com/gaynetdinov/ex_money) - 自託管的個人理財應用程序。`ISC` `長生不老藥`
- [家庭會計工具](https://github.com/nymanjens/facto) - 為部分分攤費用的合作夥伴提供基於網絡的財務管理工具。`Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Fava 是 Beancount 的 Web 前端，一個基於文本的複式記賬系統。([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava))`MIT``Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III 是一位現代財務經理。它可以幫助您跟踪您的資金並進行預算預測。它支持信用卡，具有先進的規則引擎，可以從許多銀行導入數據。([Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP`
- [Galette](https://galette.eu/dc/) - Galette 是面向非營利組織的會員管理網絡應用程序。([源代碼](https://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 用於跟踪股票、ETF 和加密貨幣的財富管理軟件。([Demo](https://ghostfol.io/), [Source Code](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 中小型公司的資產管理和預訂。([源代碼](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [Hospital Run](https://hospitalrun.io/) - Hospital Run 是離線啟用的醫院管理軟件。([Demo](https://hospitalrun.io/demo/), [Source Code](https://github.com/HospitalRun/hospitalrun-server)) `GPL-3.0` `Nodejs`
- [Hub20](https://hub20.io/) - 以太坊和 ERC20 代幣的自託管支付處理器。([源代碼](https://gitlab.com/mushroomlabs/hub20/)) `AGPL-3.0` `Docker/Python`
- [IHateMoney](https://ihatemoney.org/) - 輕鬆管理您的分攤費用。([Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [IHateToBudget](https://github.com/bminusl/ihatetobudget) - 一個簡單的網絡應用程序，用於了解和控制您的開支。`GPL-3.0` `Docker/Python`
- [Inventaire](https://inventaire.io/welcome) - 協作資源映射器項目，但只專注於探索與 wikidata 和 ISBN 的圖書映射。([源代碼](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://inventree.readthedocs.io/en/latest/) - InvenTree 是一個開源庫存管理系統，提供直觀的零件管理和庫存控制。([源代碼](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [發票忍者](https://www.invoiceninja.org/) - 在線為客戶開具發票的強大工具。([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - 為您的小型企業管理報價、發票、付款和客戶。`麻省理工學院` `PHP`
- [Kresus](https://kresus.org/) - 開源個人理財經理。([Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)) `MIT` `Nodejs`
- [OnTrack](https://github.com/inoda/ontrack) - 一個跟踪支出和設定目標的簡單應用程序。`麻省理工學院` `Ruby/React`
- [PartKeepr](https://www.partkeepr.org) - PartKeepr 是一個電子零件庫存管理軟件。它可以幫助您跟踪可用零件並幫助您重新訂購零件。([Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)) `GPL-3.0` `PHP`
- [REI3](https://rei3.de/home_en/) - 開源、可擴展的業務管理軟件。管理任務、時間、資產等等。([Demo](https://rei3.de/demo_en/), [Source Code](https://github.com/r3-team/r3)) `MIT` `Go`
- [SilverStrike](https://silverstrike.org/) - 個人財務管理變得簡單。([Demo](https://demo.silverstrike.org/), [Source Code](https://github.com/agstrike/silverstrike)) `MIT` `Python/Django`
- [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - 資產管理系統。`麻省理工學院``Python`
- [Tabby](https://github.com/bertvandepoel/tabby) - 一種管理朋友之間共享費用的工具，例如餐廳費用或送餐費用，無需每個人都創建帳戶。包括電子郵件提醒和跟踪誰（重新）支付了什麼。`AGPL-3.0-only` `PHP`


### 監控

**[`^ 返回頂部 ^`](#)**

**請訪問 [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring), [awesome-sysadmin/Metric and Metric Collection](https://github.com/ Awesome-foss/awesome-sysadmin#metric--metric-collection)**


### 筆記和編輯

**[`^ 返回頂部 ^`](#)**

_相關：[維基](#wikis)_

- [BulletNotes](https://bulletnotes.io/) - 具有看板 (Trello) 和日曆功能的 Workflowy / Dynalist 克隆。組織一切。([源代碼](https://gitlab.com/NickBusey/BulletNotes)) `MIT` `Nodejs`
- [DailyNotes](https://github.com/m0ngr31/DailyNotes/) - 用於在 Markdown 中每天記筆記和跟踪任務的應用程序。`麻省理工學院``Python`
- [dillinger](https://dillinger.io/) - 最後一個 Markdown 編輯器。([源代碼](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- [Dnote](https://www.getdnote.com) - 一個簡單的命令行筆記本，具有多設備同步和網絡界面。([源代碼](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- [DocPHT](https://docpht.org/) - 使用 DocPHT，您可以做筆記并快速記錄任何內容，而無需使用任何數據庫。([Demo](https://demo.docpht.org/), [Source Code](https://github.com/docpht/docpht)) `MIT` `PHP`
- [draw.io](https://draw.io) - 用於製作流程圖、流程圖、組織結構圖、UML、ER 和網絡圖的圖表軟件。([源代碼](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript`
- [HedgeDoc](https://demo.hedgedoc.org/) - 所有平台上的實時協作降價筆記，以前稱為 CodiMD 和 HackMD CE。([源代碼](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `TypeScript`
- [Joplin](https://joplinapp.org/) - Joplin 是一個筆記應用程序，帶有 Markdown 編輯器和對移動和桌面平台的加密支持。運行客戶端並通過自託管 Nextcloud 或類似設備進行同步。將其視為 Evernote 的開源替代品。([源碼](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Leanote](http://leanote.org/) - Leanote，不只是記事本！開源雲記事本。([Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)) `GPL-2.0` `Go`
- [Livebook](https://livebook.dev) - 基於 Markdown 的實時協作筆記本應用程序，支持運行 Elixir 代碼片段、TeX 和美人魚圖。使用 Docker 或 Elixir 輕鬆部署。([源碼](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir`
- [Markdown 編輯](https://github.com/georgeOsdDev/markdown-edit/) - 在線 Markdown 編輯器/查看器。`麻省理工學院` `HTML5`
- [Meemo](https://meemo.minimal-space.de/) - 支持 Markdown 的個人筆記流。([源碼](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - 極簡notepad.cc 克隆。([Demo](https://notes.orga.cat/)) `Apache-2.0` `PHP`
- [MiniNote](https://github.com/muety/mininote) - 具有持久性的簡單 Markdown 筆記應用程序。`麻省理工學院` `Nodejs`
- [Notea](https://cinwell.com/notea/) - 存儲在 S3 兼容存儲上的自託管筆記應用程序。([源碼](https://github.com/QingWei-Li/notea)) `MIT` `Nodejs`
- [Notes'n'Todos](https://github.com/larspontoppidan/notesntodos) - 使用標記過濾和日期排序在 Markdown 中在線編寫筆記和待辦事項。([演示](https://lpss.dk/nnt-playground/)) `MIT` `Python`
- [Oddmuse](https://oddmuse.org/) - 一個用 Perl 編寫的簡單 wiki 引擎。不需要數據庫。([源代碼](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
- [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote 被構建為 Microsoft OneNote (T) 和 EverNote 的基於 Web 的開放替代方案。([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
- [Overleaf](https://www.overleaf.com/) - 基於 Web 的協作 LaTeX 編輯器。([源代碼](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Paperwork](https://paperwork.cloud) - 開源筆記記錄和存檔替代 Evernote、Microsoft OneNote 和 Google Keep。([源代碼](https://github.com/paperwork/paperwork)) `MIT` `PHP`
- [Plainpad](https://alextselegidis.com/get/plainpad/) - 一個現代的雲筆記應用程序，利用漸進式網絡應用程序技術的最佳功能。([演示](https://alextselegidis.com/try/plainpad/), [源代碼](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [savepad](https://github.com/shelltr/textpad) - 基於 notepad.cc 的極簡記事本。`麻省理工學院` `PHP`
- [標準筆記](https://standardnotes.com) - 簡單且私密的筆記應用。在完成更多工作的同時保護您的隱私。那是標準筆記。([Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes)) `GPL-3.0` `Ruby`
- [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes 是一個分層筆記應用程序，專注於構建大型個人知識庫。`AGPL-3.0` `Nodejs`
- [turndown](https://mixmark-io.github.io/turndown/) - 用 Ja​​vascript 編寫的 HTML 到 Markdown 轉換器。([源代碼](https://github.com/mixmark-io/turndown)) `MIT` `Javascript`
- [Turtl](https://turtl.it/) - 完全私人的個人數據庫和筆記應用程序。([源代碼](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Wreeto](https://wreeto.com) - Wreeto 是一個建立在 Ruby on Rails 框架之上的開源筆記、知識管理和 wiki 系統。([源代碼](https://github.com/chrisvel/wreeto_official)) `AGPL-3.0` `Ruby`
- [Writing](https://josephernest.github.io/writing/) - 輕量級的無干擾文本編輯器，在瀏覽器中（支持 Markdown 和 LaTeX）。寫作時沒有滯後。([源碼](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 辦公套房

**[`^ 返回頂部 ^`](#)**

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) 是一款功能強大的基於 LibreOffice 的在線辦公軟件，支持所有主要的文檔、電子表格和演示文件格式，您可以在可以集成到您自己的基礎架構中。([源代碼](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.fr/) - CryptPad 是零知識實時協作編輯器（富文本、文件、源代碼……）。([源代碼](https://github.com/xwiki-labs/cryptpad)) `AGPL-3.0` `Nodejs`
- [EtherCalc](https://ethercalc.net/) - 網絡電子表格。([源代碼](https://github.com/audreyt/ethercalc)) `CPAL-1.0/Other` `Nodejs`
- [Etherpad](https://etherpad.org/) - Etherpad 是一個高度可定制的開源在線編輯器，提供真正實時的協作編輯。([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs`
- [Grist](https://getgrist.com/) - Grist 是下一代電子表格，具有關係結構、基於公式的訪問控制以及可移植的自包含格式。Airtable 的替代品。([Demo](https://docs.getgrist.com), [Source Code](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python`
- [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - [Gobby](https://github.com/gobby/gobby/wiki)服務器，多平台協作文本編輯器。([源代碼](https://github.com/gobby/gobby)) `MIT` `C++`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 使您能夠在一個地方管理文檔、項目、團隊和客戶關係的辦公套件。([源代碼](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice 包含允許從大多數辦公套件寫入和讀取文件的庫。`LGPL-3.0` `PHP`
- [Rustpad](https://rustpad.io/) - 高效且最小化的協作代碼編輯器，自託管，無需數據庫。([源碼](https://github.com/ekzhang/rustpad)) `MIT` `Rust`
- [WebODF](https://webodf.org/) - 查看和編輯開放文檔格式 (ODF) 文件的工具和庫。([源代碼](https://github.com/webodf/WebODF)) `AGPL-3.0` `HTML5`


### 密碼管理器

**[`^ 返回頂部 ^`](#)**

- [Bitwarden](https://bitwarden.com/) `⚠` - 帶有 web 應用程序、瀏覽器擴展程序和移動應用程序的密碼管理器。([源代碼](https://github.com/bitwarden/server)) `AGPL-3.0` `C#`
- [keeweb](https://keeweb.info/) - 這個網絡應用程序是一個與 KeePass 數據庫兼容的瀏覽器和桌面密碼管理器。([源代碼](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
- [Padloc](https://padloc.app/) - 適用於個人和團隊的現代開源密碼管理器。([源代碼](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- [Passbolt](https://www.passbolt.com/) - 密碼管理器，專門用於在任何 Web 服務器上以協作方式管理密碼，使用 MySQL 數據庫後端。([源代碼](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP`
- [PassIt](https://passit.io/) - 簡單的密碼管理，具有組和用戶共享功能，但沒有管理界面。([Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)) `AGPL-3.0` `Python`
- [Passky](https://passky.org) - 簡單、現代和開源的密碼管理器，帶有網站、瀏覽器擴展、安卓和桌面應用程序。([Demo](https://vault.passky.org), [Source Code](https://github.com/Rabbit-Company/Passky-Server)) `GPL-3.0` `PHP`
- [PassWall](https://github.com/passwall/passwall-server) - 開源密碼管理器。`AGPL-3.0` `Go`
- [Psono](https://psono.com/) - 一個有前途的密碼管理器，完全適用於團隊。([Demo](https://www.psono.pw), [Source Code](https://gitlab.com/psono)) `Apache-2.0` `Python`
- [Shaark](https://github.com/MarceauKa/shaark) - 您的鏈接、故事、密碼和相冊的一站式平台。使用 Laravel 和 Vue.js 構建。`麻省理工學院` `PHP`
- [sysPass](https://www.syspass.org/) - 多用戶密碼管理系統。([Demo](https://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)) `GPL-3.0` `PHP`
- [Teampass](https://teampass.net/) - 專用於以協作方式管理密碼的密碼管理器。一個對稱密鑰用於加密所有共享/團隊密碼，並將服務器端存儲在文件和數據庫中。適用於任何服務器 Apache、MySQL 和 PHP。([源代碼](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [保險庫](https://github.com/MatrixEternal/vaults) - 具有客戶端 AES-256 加密、PBKDF2 散列、保險庫、密碼生成等功能的密碼管理器。`GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用 Rust 編寫的輕量級 Bitwarden 服務器 API 實現。`GPL-3.0` `Rust`


### 粘貼箱

**[`^ 返回頂部 ^`](#)**

- [0bin](https://github.com/Tygs/0bin) - 客戶端加密的 pastebin。([Demo](https://0bin.net/)) `WTFPL` `Python`
- [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - 各種文件的粘貼箱。([源代碼](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python`
- [bin](https://github.com/w4/bin) - 一個粘貼箱。`WTFPL/0BSD` `Rust`
- [cryptonote](https://cryptonote.me/) - 簡單的開源 Web 應用程序，允許用戶加密和共享只能讀取一次的消息。([源代碼](https://github.com/alainmeier/cryptonote)) `MIT` `Ruby`
- [dogbin](https://github.com/dogbin/dogbin) - 有史以來最性感的 pastebin 和 URL 縮短器。`麻省理工學院``科特林`
- [dpaste](https://dpaste.org/) - 帶有多個文本和代碼選項的簡單 pastebin，短 url 結果易於記憶。([源代碼](https://github.com/bartTC/dpaste)) `MIT` `Docker`
- [漂移](https://github.com/MaxLeiter/drift) - 自託管 Github Gist 克隆。([Demo](https://drift.maxleiter.com/)) `MIT` `TypeScript`
- [EdPaste](https://github.com/eahlys/EdPaste) - 用 Laravel（PHP 框架）編寫的自託管 pastebin。`麻省理工學院` `PHP`
- [ExBin](https://github.com/m1dnight/exbin) - 帶有公共/私有片段和 netcat 服務器的 pastebin。([Demo](https://exbin.call-cc.be)) `MIT` `Elixir`
- [fiche](https://github.com/solusipse/fiche) - 命令行 pastebin，你只需要 netcat。([Demo](https://termbin.com/)) `MIT` `C`
- [filite](https://github.com/raftario/filite) - 一個簡單、輕量且獨立的 pastebin、URL 縮短器和文件共享服務。([Demo](https://filite.raphaeltheriault.com)) `MIT` `Rust`
- [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper) - 一個一次性加密的零知識密碼/秘密共享應用程序，專注於簡單性和安全性。無需數據庫或複雜的設置。([Demo](https://flashpaper.io)) `MIT` `PHP`
- [Fugacious](https://fugacio.us) - 開源短期安全消息 (OSSSM)。([源代碼](https://github.com/fugacious/fugacious)) `CC0-1.0` `Ruby`
- [Hastebin](https://haste.zneix.eu/about.md) - 開源 pastebin。（這是一個延長維護的前叉）。([Demo](https://haste.zneix.eu), [Source Code](https://github.com/zneix/haste-server)) `MIT` `Nodejs`
- [LogPaste](https://github.com/mtlynch/logpaste) - 最小的 pastebin Web 應用程序，易於自託管並將數據持久保存到任何與 S3 兼容的後端。([Demo](https://logpaste.com/)) `MIT` `Go`
- [mkaczanowski pastebin](https://github.com/mkaczanowski/pastebin) - 簡單、快速、功能豐富、獨立的 pastebin 服務。`麻省理工學院``銹`
- [mojopaste](https://metacpan.org/dist/App-mojopaste) - 基於 Perl 的 pastebin。([Demo](https://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)) `Artistic-2.0` `Perl`
- [MokinToken](https://github.com/nexus-uw/mokintoken) - 使用 tweetnacl 的客戶端加密 pastebin。`Unlicense` `PHP`
- [NoteHub](https://github.com/chmllr/NoteHub) - 用於 Markdown 頁面的免費且無憂的 Pastebin。簡單、乾淨、提供密碼、生成的短鏈接。`麻省理工學院` `Nodejs`
- [paaster](https://paaster.io) - Paaster 是一個安全的默認端到端加密 pastebin，其目的是為了簡單而構建。([源代碼](https://github.com/WardPearce/paaster)) `GPL-3.0` `Docker`
- [Paste](https://phpaste.sourceforge.io/) - Paste 是從購買前使用的原始源 pastebin.com 分叉出來的。([源代碼](https://github.com/jordansamuel/PASTE)) `GPL-3.0` `PHP`
- [Pastefy](https://pastefy.ga) - 美麗、簡單且易於部署的 Pastebin 帶有可選的客戶端加密、多選項卡粘貼、API、突出顯示的編輯器等。([源代碼](https://github.com/interaapps/pastefy), [客戶端](https://github.com/topics/pastefy-addon)) `MIT` `Java`
- [pasty](https://github.com/lus/pasty) - Pasty 是一個快速、輕量級的代碼粘貼服務器。([演示](https://pasty.lus.pm/)) `MIT` `Go`
- [pb](https://github.com/ptpb/pb) - 使用燒瓶構建的輕量級 pastebin（和 url 縮短器）。`GPL-3.0` `Python`
- [PrivateBin](https://privatebin.info/) - PrivateBin 是一個極簡主義的開源在線粘貼/討論板，服務器對託管數據的了解為零。([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [prologic pastebin](https://git.mills.io/prologic/pastebin) - 簡單的 pastebin 服務，帶有方便的 api 和 CLI。([Demo](https://paste.mills.io)) `MIT` `Go`
- [PurritoBin](https://github.com/PurritoBin/PurritoBin) - 超快速、簡約、加密的命令行粘貼箱，服務器不知道粘貼數據。`ISC` `C++`
- [rustypaste](https://github.com/orhun/rustypaste) - 最小的文件上傳/pastebin 服務。`麻省理工學院``銹`
- [SharpPaste](https://github.com/phonicmouse/SharpPaste) - 具有客戶端 AES-256 加密功能的跨平台 C# pastebin。`麻省理工學院` `C#/NancyFX`
- [Snibox](https://snibox.github.io/) - 具有有吸引力的面向標籤的界面的代碼片段管理器。([Demo](https://snibox-demo.herokuapp.com/), [Source Code](https://github.com/snibox/snibox)) `MIT` `Ruby`
- [Snippet Box](https://github.com/pawelmalak/snippet-box) - Snippet Box 是一個簡單的自託管應用程序，用於組織您的代碼片段。它使您可以輕鬆地創建、編輯、瀏覽和管理各種語言的片段。`麻省理工學院` `Nodejs`
- [snipt](https://github.com/nicksergeant/snipt) - 編碼員的長期記憶。共享和存儲代碼片段。`麻省理工學院``Python`
- [SocksBin](https://github.com/magnumdingusedu/socksbin) - 簡單快速的基於終端的 pastebin，帶有可選的代碼突出顯示。不需要特定的客戶端，您只需要 netcat。`GPL-3.0` `Python`
- [Spacebin](https://docs.spaceb.in) - 最後前沿的文本共享 - Golang 和 Fiber 中可靠的 Pastebin 服務器。([Demo](https://spaceb.in), [Source Code](https://github.com/spacebin-org/spirit)) `Apache-2.0` `Go`
- [Stikked](https://github.com/claudehohl/Stikked) - 高級漂亮的 pastebin。([演示](https://paste.scratchbook.ch/)) `GPL-3.0` `PHP`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 使用 Hashicorp Vault 作為秘密存儲非常簡單（部署和使用）秘密消息服務。`麻省理工學院``去`
- [wantguns/bin](https://github.com/wantguns/bin) - 在單個靜態鏈接二進製文件中提供的文本和二進製文件的最小 pastebin。([Demo](https://basedbin.fly.dev)) `GPL-3.0` `Rust`


### 個人儀表板

**[`^ 返回頂部 ^`](#)**

_相關：[監控](#monitoring)_

- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 幫助護理人員跟踪嬰兒睡眠、餵食、換尿布和俯臥時間。([Demo](https://babybuddy.herokuapp.com/)) `BSD-2-Clause` `Python`
- [儀表板](https://github.com/phntxx/dashboard) - 使用 JSON 文件組織 Web 應用程序和書籤的極簡主義主頁。`麻省理工學院` `Nodejs/Docker`
- [DashMachine](https://github.com/rmountjoy92/DashMachine) - 另一個 Web 應用程序書籤儀表板，具有有趣的功能。`GPL-3.0` `Python`
- [Dashy](https://github.com/lissy93/dashy) - 功能豐富的 homelab 主頁，YAML 配置簡單。([Demo](https://demo.dashy.to/)) `MIT` `Nodejs/Docker`
- [Flame](https://github.com/pawelmalak/flame) - Flame 是您服務器的自託管起始頁。使用內置編輯器輕鬆管理您的應用程序和書籤。`麻省理工學院` `Nodejs`
- [Habitica](https://habitica.com/) - 將您的目標視為角色扮演遊戲的習慣追踪器應用程序。以前稱為 HabitRPG。([源代碼](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-NC-SA-3.0/CC-BY-SA-3.0` `Nodejs`
- [Heimdall](https://heimdall.site/) - Heimdall 是一個優雅的解決方案，可以組織您的所有 Web 應用程序。([源碼](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [打嗝](https://designbyashw.in/test/hiccup/) - 一個漂亮的靜態主頁，可以快速訪問您的鏈接和服務。它具有內置的搜索、編輯、PWA 支持和本地存儲緩存，可輕鬆組織您的起始頁面。([源代碼](https://github.com/ashwin-pc/hiccup)) `MIT` `HTML5`
- [主頁](https://github.com/tomershvueli/homepage) - 簡單、獨立、自託管的 PHP 頁面，是您連接服務器和 Web 的窗口。`麻省理工學院` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 一個簡單的靜態主頁，用於公開您的服務器服務，具有簡單的 yaml 配置和連接檢查。`Apache-2.0` `HTML5`
- [Jmz HomeProxy](https://github.com/jmztaylor/homelab_proxy) - 一個簡單而乾淨的自託管服務儀表板。`GPL-3.0` `PHP`
- [LinkPage](https://links.zrd.sh) - LinkPage 是鏈接列表網站（如 LinkTree 和 Campsite.bio）的 FOSS 自託管替代方案。([源代碼](https://github.com/rhnvrm/linkpage)) `BSD-2-Clause` `Go`
- [Organizr](https://github.com/causefx/Organizr) - Organizr 旨在成為您的服務器前端的一站式商店。`GPL-3.0` `PHP`
- [個人管理系統](https://github.com/Volmarg/personal-management-system) - 管理個人數據（賬單、付款、工作假期、筆記等）的中心點。([Demo](http://personal-management-system.pl/)) `MIT` `PHP`
- [simple-dash](https://github.com/kutyla-philipp/simple-dash) - 一個簡單、完全響應的儀表板，用於轉發到您選擇的服務。([演示](https://kutyla-philipp.github.io/simple-dash/)) `MIT` `Javascript`
- [Smashing](https://smashing.github.io/) - Smashing 是 Dashing 的精神繼承者，是一個基於 Sinatra 的框架，可讓您構建出色的儀表板。它在電視上看起來特別棒。([源代碼](https://github.com/Smashing/smashing)) `MIT` `Ruby`
- [wger](https://wger.de/) - 基於網絡的個人鍛煉、健身和體重記錄器/跟踪器。它還可以用作簡單的健身房管理實用程序，並提供完整的 REST API。([Demo](https://wger.de/en/dashboard), [Source Code](https://github.com/wger-project/wger)) `AGPL-3.0` `Python`
- [您的 Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - 允許您記錄您的 Spotify 收聽活動並通過 Web 應用程序提供有關它們的統計信息。`麻省理工學院` `Nodejs/Docker`


### 照片和視頻庫

**[`^ 返回頂部 ^`](#)**

- [Chevereto Free](https://chevereto.com/free) - 強大而快速的圖片託管腳本，讓您在幾分鐘內創建自己的全功能圖片託管網站。([源代碼](https://github.com/Chevereto/Chevereto-Free)) `AGPL-3.0` `PHP`
- [Coppermine](https://coppermine-gallery.net/) - 與各種公告板集成的多語言照片庫。包括上傳批准和受密碼保護的相冊。([Demo](https://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- [Damselfly](https://damselfly.info) - 基於服務器的快速照片管理系統，用於大量圖像。包括人臉檢測、人臉和對象識別、強大的搜索和 EXIF 關鍵字標記。在 Linux、MacOS 和 Windows 上運行。`GPL-3.0` `C#/.NET`
- [Fussel](https://github.com/cbenning/fussel) - Fussel 是一個靜態照片庫生成器。輕鬆生成反應式畫廊並託管優化的靜態資產文件夾。`麻省理工學院``Python`
- [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css 都是 CSS。思考：簡單、可維護且易於理解的畫廊，無需使用 Javascript。([源代碼](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
- [HomeGallery](https://home-gallery.org) - 自託管的開源網絡畫廊，用於瀏覽具有標記、移動友好和人工智能驅動的圖像發現的個人照片和視頻。([Demo](https://demo.home-gallery.org), [Source Code](https://github.com/xemle/home-gallery)) `MIT` `Nodejs`
- [ImageStore](https://github.com/gregordr/ImageStore) - 自託管的 Google 照片替代品，具有非常相似的 UI。([Demo](https://gregordr.github.io/ImageStore/)) `Apache-2.0` `Nodejs/Docker`
- [Immich](https://github.com/alextran1502/immich) - 直接從您的手機自託管的照片和視頻備份解決方案。`麻省理工學院``碼頭工人`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 自託管的 Google Photos 克隆，略微關注酷圖。`麻省理工學院``Python`
- [Lychee](https://lycheeorg.github.io/) - 開源網格和基於相冊的照片管理系統。([源碼](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以運行的免費軟件媒體發布平台。您可以將其視為 Flickr、YouTube、SoundCloud 等的去中心化替代品。（[源代碼](https://savannah.gnu.org/projects/mediagoblin)）`AGPL-3.0``Python`
- [MediaHut](https://github.com/Fortyseven/MediaHut/) - 一個真正的單文件、無數據庫、插入式 PHP 媒體庫。([Demo](https://media.Network47.org/)) `MIT` `PHP`
- [Mejiro](https://github.com/dmpop/mejiro) - 一個易於使用的 PHP Web 應用程序，用於即時照片發布。`GPL-3.0` `PHP`
- [照片](https://github.com/trebonius0/Photato) - 自託管照片庫，可通過響應式 WebUI 訪問。直接使用和索引文件系統中的特定文件夾。`AGPL-3.0` `Java`
- [照片流](https://github.com/waschinski/photo-stream) - 極簡主義的自託管照片流。([Demo](https://floremotion.de/)) `MIT` `Ruby`
- [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - 最簡單的照片庫。`GPL-3.0` `PHP`
- [Photonix](https://photonix.org/) - 一個新的基於 Web 的照片管理應用程序，具有對象識別、位置感知、顏色分析和其他 ML 算法。([Demo](https://demo.photonix.org/), [Source Code](https://github.com/photonixapp/photonix)) `AGPL-3.0` `Python`
- [PhotoPrism](https://photoprism.org) - 由 Go 和 Google TensorFlow 提供支持的個人照片管理。瀏覽、組織和分享您的個人照片集，使用最新技術自動標記和查找照片。([源碼](https://github.com/photoprism/photoprism)) `MIT` `Go`
- [Photoview](https://photoview.github.io/) - 一個簡單易用的個人服務器照片庫。它是為攝影師設計的，旨在提供一種簡單快捷的目錄導航方式，包含數千張高分辨率照片。([Demo](https://photos.qpqp.dk/), [Source Code](https://github.com/photoview/photoview)) `GPL-3.0` `Go`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 一個目錄優先的照片庫網站，具有豐富的 UI，針對在低資源服務器上運行進行了優化。([源代碼](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - 網絡相冊軟件，由活躍的用戶和開發者社區構建。([Demo](https://piwigo.org/demo/), [Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [Quru 圖像服務器](https://quruimageserver.com/) - 高性能動態調整圖像服務器，提供基於目錄的訪問控制裁剪、旋轉、顏色管理和其他工具。([Demo](https://quruimageserver.com), [Source Code](https://github.com/quru/qis)) `AGPL-3.0` `Python`
- [sigal](https://github.com/saimn/sigal) - 另一個簡單的靜態畫廊生成器。`麻省理工學院``Python`
- [UberGallery](https://www.ubergallery.net) - UberGallery 是一個易於使用、易於管理的網絡照片庫。UberGallery 不需要數據庫，支持 JPEG、GIF 和 PNG 文件類型。只需上傳您的圖片，UberGallery 就會自動生成縮略圖並輸出 HTML。([源代碼](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
- [Zenphoto](https://www.zenphoto.org/) - 開源畫廊和 CMS 項目。([源碼](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 投票和事件

**[`^ 返回頂部 ^`](#)**

_相關：[預訂和調度](#booking-and-scheduling)_

- [Calagator](https://calagator.org/) - 事件聚合器。([源代碼](https://github.com/calagator/calagator)) `MIT` `Ruby`
- [ClearFlask](https://clearflask.com) - 社區反饋工具，用於管理傳入的反饋並確定公共路線圖的優先級。Canny、UserVoice、Upvoty 的替代品。([Demo](https://product.clearflask.com), [Source Code](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [Clerk](https://github.com/AppMini/Clerk) - 簡單的事件記錄器，用於跟踪發生的周期性事件、習慣等。`GPL-3.0` `PHP`
- [Croodle](https://github.com/jelhan/croodle) - Croodle 是一個端到端的加密網絡應用程序，用於安排日期或就任何主題進行投票。`麻省理工學院``Javascript`
- [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - 在線調度應用程序。([Demo](https://dudle.inf.tu-dresden.de/), [Source Code](https://github.com/kellerben/dudle)) `AGPL-3.0` `Ruby`
- [Feedka](https://github.com/drabkirn/feedka) `⚠` - 開源網絡應用程序，可以作為一個平台，從您的朋友、家人和同事那裡獲得真實、友善和建設性的反饋-工人。([演示](https://feedka.herokuapp.com)) `AGPL-3.0` `Ruby`
- [Fider](https://getfider.com) - UserVoice 的開源替代方案，用於提供客戶反饋。([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider))`MIT``Go`
- [Framadate](https://framadate.org/) - 用於計劃約會或快速輕鬆地做出決定的在線服務：進行投票，定義日期或主題選擇，將投票鏈接發送給您的朋友或同事，討論並做出決定。（[演示]（https://framadate.org/aqg259dth55iuhwm），[源代碼]（https://git.framasoft.org/framasoft/framadate））`CECILL-B``PHP`
- [Gancio](https://gancio.org/) - 當地社區的共同議程。([Demo](https://demo.gancio.org/), [Source Code](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [hitobito](https://hitobito.com/en) - 一個 Web 應用程序，用於管理具有成員、事件等的複雜組層次結構。([Demo](https://demo.hitobito.com/en/users/sign_in), [Source Code](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [JD Esurvey](https://www.jdsoft.com/jd-esurvey.html) - 開源企業調查網絡應用程序。([源代碼](https://github.com/JD-Software/JDeSurvey)) `AGPL-3.0` `Java`
- [Kyélà](https://kyela.net/) - 團體活動的參與投票。([Demo](https://kyela.net/concert/), [Source Code](https://github.com/abienvenu/Kyela)) `AGPL-3.0` `PHP`
- [LimeSurvey](https://www.limesurvey.org) - 功能豐富的開源基於網絡的投票軟件。支持廣泛的調查邏輯。([Demo](https://demo.limesurvey.org), [Source Code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://meetable.org) - 事件聚合器。([Demo](https://events.indieweb.org), [Source Code](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 一種聯合工具，可幫助您查找、創建和組織活動和群組。([Demo](https://demo.mobilizon.org/), [Source Code](https://framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir`
- [Open Event Server](https://github.com/fossasia/open-event-server) - 使組織者能夠管理從音樂會到會議和聚會的活動。`GPL-3.0` `Python`
- [PHPBack](https://www.phpback.org) - 開源反饋系統。([Demo](https://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback)) `GPL-3.0` `PHP`


＃＃＃ 代理

**[`^ 返回頂部 ^`](#)**

- [imgproxy](https://imgproxy.net/) - 快速安全的獨立服務器，用於調整和轉換遠程圖像。當您需要即時調整多個圖像的大小而不需要準備大量緩存的調整大小的圖像或每次設計更改時都重新進行調整時，它非常有用。([源碼](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker`
- [inlets](https://inlets.dev/) - 將您的本地端點公開到 Internet - 使用 Kubernetes 集成、Docker 映像和 CLI 可用。`麻省理工學院` `Go/Docker`
- [iodine](https://code.kryo.se/iodine/) - IPv4 over DNS 隧道解決方案，使您能夠啟動 socks5 代理偵聽器。([源代碼](https://github.com/yarrick/iodine)) `ISC` `C`
- [microproxy](https://github.com/thekvs/microproxy) - 輕量級非緩存 HTTP/HTTPS 代理服務器。`麻省理工學院``去`
- [Nginx 代理管理器](https://nginxproxymanager.com/) - Nginx 代理管理器是一種通過 SSL 終止來完成反向代理主機的簡單方法。([源碼](https://github.com/jc21/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- [PHP-Proxy](https://www.php-proxy.com/) - 專為快速、易於修改和支持 YouTube 等視頻網站而構建的 Web 代理腳本。([Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
- [Pomerium](https://pomerium.io) - 一個身份感知反向代理，現在已過時的 oauth_proxy 的繼任者。它在將您的請求代理到後端之前插入一個 OAuth 步驟，以便您可以安全地將您的自託管網站公開到公共 Internet。([源代碼](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- [Pound](https://www.apsis.ch/pound.html) - HTTP/HTTPS 的輕量級反向代理和負載均衡器。`GPL-2.0` `C`
- [Privoxy](https://www.privoxy.org) - 具有高級過濾功能的非緩存網絡代理，用於增強隱私、修改網頁數據和 HTTP 標頭、控制訪問以及刪除廣告和其他令人討厭的互聯網垃圾。`GPL-2.0` `C`
- [Redbird](https://github.com/OptimalBits/redbird) - 一個現代的節點反向代理，包括集群、HTTP2、LetsEncrypt 和 Docker 支持。`BSD-2-Clause` `Javascript`
- [sish](https://github.com/antoniomika/sish) - 開源 serveo/ngrok 替代方案，僅使用 SSH 提供到 localhost 的 HTTP(S)/WS(S)/TCP 隧道。`麻省理工學院``去`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 具有內置身份驗證和 Telegram-bot 的 SOCKS5 代理服務器，用於用戶管理和用戶使用數據的統計（當您按每 GB 數據付費）。它是 dockerised 並且易於安裝。`Apache-2.0` `Nodejs`
- [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine) - 輕量且資源高效的 SOCKS5 代理服務器，針對高負載進行了優化。`AGPL-3.0` `Go`
- [Squid](http://www.squid-cache.org/) - 支持 HTTP、HTTPS、FTP 等的 Web 緩存代理。它通過緩存和重用頻繁請求的網頁來減少帶寬並提高響應時間。([源代碼](https://code.launchpad.net/squid)) `GPL-2.0` `C`
- [SWAG（安全 Web 應用程序網關）]（https://github.com/linuxserver/docker-swag） - Nginx 網絡服務器和反向代理，支持 PHP，內置 Certbot（Let's Encrypt）客戶端和 fail2ban 集成。`GPL-3.0` `Docker`
- [Swiperproxy](https://swiperproxy.github.io/) - 閃電般快速的開源 Web 代理，您可以輕鬆運行和自定義。([源代碼](https://github.com/swiperproxy/swi perproxy)) `MIT` `Python`
- [Tinyproxy](https://tinyproxy.github.io/) - 輕量級 HTTP/HTTPS 代理守護進程。([源代碼](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C`
- [Traefik](https://traefik.io/) - Træfɪk 是現代 HTTP 反向代理和負載均衡器，可輕鬆部署微服務。它支持多個後端（Docker、Swarm、Mesos/Marathon 等）來自動和動態地管理其配置。([源碼](https://github.com/traefik/traefik)) `MIT` `Go`


### 稍後閱讀列表

**[`^ 返回頂部 ^`](#)**

- [Readflow](https://readflow.app) - 具有現代界面和功能的輕量級新聞閱讀器：全文搜索、自動分類、歸檔、離線支持、通知...（[Source Code](https:// github.com/ncarlier/readflow)) `MIT` `Go`
- [Wallabag](https://www.wallabag.org) - Wallabag，前身為 Poche，是一個網絡應用程序，允許您保存文章以便以後閱讀，提高了可讀性。([Demo](https://app.wallabag.it/register/), [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`


### 配方管理

**[`^ 返回頂部 ^`](#)**

- [Groceri.es](https://groceri.es/) - groceri.es 是一個基於網絡的應用程序，用於管理您的食譜並提前計劃您的膳食。groceri.es 跟踪您的菜單計劃並為您生成雜貨清單。([源代碼](https://github.com/juriansluiman/groceri.es)) `MIT` `Python`
- [kcal](https://github.com/kcal-app/kcal) - 跟踪有關食物和食譜的營養信息，設定目標，並記錄食物日記以在此過程中提供幫助。Kcal 是一個個人系統，專注於直接控制輸入和用於準備飯菜的簡單易用的食譜演示。([Demo](http://demo.kcal.cooking/login)) `MPL-2.0` `PHP`
- [Mealie](https://hay-kot.github.io/mealie/) - 受材料設計啟發的食譜管理器，具有類別和標籤管理、購物清單、膳食計劃器和站點自定義。Mealie 專注於簡單的用戶交互，讓全家人都能使用這款應用。([Demo](https://mealie-demo.hay-kot.dev/), [Source Code](https://github.com/hay-kot/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 可以直接從任何 URL 導入食譜的食譜管理員、膳食計劃組織者和購物清單管理器。([Demo](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Tandoor Recipes](https://docs.tandoor.dev/) - 使用內置模型或託管 PDF、圖像或其他文件的外部存儲提供程序來管理、標記和搜索食譜的 Django 應用程序。([Demo](https://app.tandoor.dev/), [Source Code](https://github.com/vabene1111/recipes/)) `MIT` `Python`


＃＃＃ 資源規劃

**[`^ 返回頂部 ^`](#)**

- [farmOS](https://farmos.org/) - 基於網絡的農場記錄保存應用程序。([源代碼](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP`
- [grocy](https://grocy.info/) - 冰箱之外的 ERP - grocy 是一個基於網絡的自託管雜貨和家庭管理解決方案。([Demo](https://en.demo.grocy.info/), [Source Code](https://github.com/grocy/grocy)) `MIT` `PHP`
- [Tania](https://github.com/Tanibox/tania-core) - Tania 是一個免費的開源農業管理系統，適合所有人。您可以管理您的區域、水庫、農場任務、庫存和作物生長進度。`Apache-2.0` `Go`


### 資源計劃 - 企業資源計劃

**[`^ 返回頂部 ^`](#)**

- [Dolibarr](https://www.dolibarr.org/) - Dolibarr ERP CRM 是一個現代軟件包，用於管理您的公司或基金會活動（聯繫人、供應商、發票、訂單、庫存、議程、會計...... ）。([Demo](https://www.dolibarr.org/onlinedemo.php), [Source Code](https://github.com/Dolibarr/dolibarr)) `GPL-3.0-or-later` `PHP`
- [ERPNext](https://erpnext.com) - 免費開源ERP系統。([源代碼](https://github.com/frappe/erpnext)) `GPL-3.0` `Python`
- [LedgerSMB](https://ledgersmb.org/) - 適用於中小型企業的集成會計和 ERP 系統，具有復式記賬、預算、發票、報價、項目、訂單和庫存管理、運輸等。([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` ` Perl`
- [Odoo](https://www.odoo.com) - 免費開源ERP系統。([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python`
- [OFBiz](https://ofbiz.apache.org/) - FOSS 企業資源規劃系統，具有一套足夠靈活的業務應用程序，可在任何行業中使用。([源代碼](https://svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免費開源業務解決方案。([Demo](https://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPL-3.0` `Python`


＃＃＃ 搜索引擎

**[`^ 返回頂部 ^`](#)**

- [Ambar](https://ambar.cloud) - 文檔搜索引擎（OCR、存儲和搜索）。([Demo](https://app.ambar.cloud/), [Source Code](https://github.com/RD17/ambar)) `MIT` `Nodejs/Python`
- [Gigablast](https://www.gigablast.com/) - 開源搜索引擎。([源代碼](https://github.com/gigablast/open-source-search-engine)) `Apache-2.0` `C++`
- [librengine](https://github.com/liameno/librengine) - 私人網絡搜索引擎。`GPL-3.0` `C++`
- [Jina](https://github.com/jina-ai/jina/) - 適用於任何類型數據的雲原生神經搜索框架。`Apache-2.0` `Python`
- [MeiliSearch](https://meilisearch.com) - 超相關、即時且容錯的全文搜索 API。([源碼](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust`
- [Searx](https://searx.github.io/searx/) - 尊重隱私、可破解的元搜索引擎。([Demo](https://searx.space/), [Source Code](https://github.com/searx/searx)) `AGPL-3.0` `Python`
- [sist2](https://github.com/simon987/sist2) - 閃電般的文件系統索引器和搜索工具。([演示](https://sist2.simon987.net/)) `GPL-3.0` `C`
- [Typesense](https://typesense.org) - 快速、容錯的開源搜索引擎，針對開發人員的快樂和易用性進行了優化。([源代碼](https://github.com/typesense/typesense)) `GPL-3.0` `C++`
- [Whoogle](https://github.com/benbusby/whoogle-search) `⚠` - 自託管、無廣告、尊重隱私的元搜索引擎。`麻省理工學院``Python`
- [Yacy](https://yacy.net/en/index.html) - 基於對等的去中心化搜索引擎服務器。([Demo](https://search.yacy.net/), [Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java`


### 自託管解決方案

**[`^ 返回頂部 ^`](#)**

- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - 用這個劇本和一個 Ubuntu 盒子構建一個功能齊全的家庭服務器。`MIT` `YAML/Docker`
- [Bitsii Bridge](https://gitlab.com/bitsii/Bitsii/-/wikis/home) `⚠` - 易於安裝適用於 Windows、MacOS 和 Linux 的自託管平台。取決於動態 DNS 提供商和 Let's Encrypt。([源代碼](https://gitlab.com/edgii/BBridge)) `MPL-2.0` `Java/Other`
- [Cloudbox](https://cloudbox.works) - 基於 Ansible 的解決方案，用於快速部署 Docker 容器化雲媒體服務器。([源代碼](https://github.com/Cloudbox/Cloudbox)) `GPL-3.0` `Shell/Ansible`
- [DietPi](https://dietpi.com/) - 為單板計算機優化的最小化 Debian 操作系統，讓您在家中輕鬆安裝和管理多個自託管服務。([源代碼](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 幫助您開始使用在 Docker 中運行的家庭服務器應用程序。([源代碼](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [DPlatform](https://dfabric.github.io/DPlatform-Shell/) - 輕鬆部署自託管應用程序：簡單、無膨脹、獨立安裝。([源代碼](https://github.com/DFabric/DPlatform-Shell)) `MIT` `Shell`
- [FLAP](https://www.flap.cloud) - 管理自託管服務的低維護框架。([源代碼](https://gitlab.com/flap-box/flap)) `AGPL-3.0` `Docker/Shell`
- [FreedomBone](https://freedombone.net/) - 基於 Debian 的家庭服務器配置。([源代碼](https://code.freedombone.net/bashrc/freedombone)) `AGPL-3.0` `Shell`
- [FreedomBox](https://freedomboxfoundation.org/) - 社區項目，用於開發、設計和推廣運行免費軟件的個人服務器，用於私人、個人、通信。([源代碼](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/Other`
- [HomelabOS](https://homelabos.com) - 您自己的離線優先、以隱私為中心的開源數據中心。使用幾個命令部署 100 多個服務。([源代碼](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [NextCloudPi](https://nextcloudpi.com/) - Nextcloud 預安裝和預配置，具有文本和 Web 管理界面以及自託管私有數據所需的所有工具。帶有適用於 Raspberry Pi、Odroid、Rock64、Docker 的安裝映像和適用於 Armbian/Debian 的 curl 安裝程序。([源代碼](https://github.com/nextcloud/nextcloudpi)) `GPL-2.0-or-later` `Bash/PHP`
- [OpenMediaVault](https://www.openmediavault.org/) - OpenMediaVault 是基於 Debian Linux 的下一代網絡附加存儲 (NAS) 解決方案。它包含 SSH、(S)FTP、SMB/CIFS、DAAP 媒體服務器、RSync、BitTorrent 客戶端等服務。([源代碼](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用於輕鬆安全地運行自託管應用程序的個人服務器。([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Other`
- [sovereign](https://github.com/sovereign/sovereign) - 一套 Ansible 手冊，用於構建和維護您自己的私有云：電子郵件、日曆、聯繫人、文件同步、IRC 保鏢、VPN 等。`GPL-3.0` `YAML/其他`
- [Syncloud](https://syncloud.org/) - 您自己的在線文件存儲、社交網絡或電子郵件服務器。([源碼](https://github.com/syncloud/platform)) `GPL-3.0` `Python/Other`
- [UBOS](https://ubos.net/) - 在獨立機器（個人服務器和物聯網設備）上運行的 Linux 發行版。應用程序的單命令安裝和管理 - Jenkins、Mediawiki、Owncloud、WordPress 等，以及其他功能。`GPL-3.0` `Perl/其他`
- [WikiSuite](https://wikisuite.org) - 最全面和集成的免費/自由/開源企業軟件套件。（[源代碼]（https://wikisuite.org/Source-Code））`GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0``ClearOS`
- [xsrv](https://xsrv.readthedocs.io/) - 在您自己的服務器上安裝和管理自託管服務/應用程序。([源代碼](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Shell/Ansible`
- [YunoHost](https://yunohost.org/) - 服務器操作系統旨在讓每個人都可以訪問自託管。([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Other`


＃＃＃ 軟件開發

**[`^ 返回頂部 ^`](#)**


### 軟件開發 - API 管理

**[`^ 返回頂部 ^`](#)**

- [DreamFactory](https://www.dreamfactory.com/) - 將任何 SQL/NoSQL/結構化數據轉換為 Restful API。([源碼](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP`
- [form.io](https://form.io) - 一個使用拖放表單構建器的 REST API 構建平台，並且與應用程序框架無關。包含開源和企業版。([Demo](https://portal.form.io), [Source Code](https://github.com/formio)) `MIT` `Nodejs`
- [Fusio](https://www.fusio-project.org/) - 幫助構建和管理 REST API 的開源 API 管理平台。([Demo](https://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP`
- [Hapttic](https://github.com/jsoendermann/hapttic) - 簡單的 HTTP 服務器，將所有請求轉發到 shell 腳本以處理您收到的 webhook。`Apache-2.0` `Go`
- [Hasura](https://hasura.io) - Postgres 上快速、即時的實時 GraphQL API，具有細粒度的訪問控制，還觸發數據庫事件的 webhook。([源代碼](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell`
- [Hoppscotch](https://hoppscotch.io) - 免費、快速、美觀的 API 請求生成器。([源代碼](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Vue/Nuxt`
- [Kong](https://konghq.com/kong/) - 全球最受歡迎的開源微服務API網關和平台。([源碼](https://github.com/Kong/kong)) `Apache-2.0` `Lua`
- [Lura](https://luraproject.org/) - 開源高性能 API 網關。([源代碼](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Para](https://paraio.org) - 靈活的模塊化後端框架/服務器，用於對象持久化、API 開發和身份驗證。([源代碼](https://github.com/erudika/para)) `Apache-2.0` `Java`
- [Pizzly](https://github.com/bearer/pizzly) - 開源 API 集成管理器，提供開發人員與基於 OAuth 的 API 交互所需的一切。`麻省理工學院` `Nodejs`
- [Tyk](https://tyk.io) - 快速且可擴展的開源 API 網關。Tyk 提供開箱即用的 API 管理平台，包括 API 網關、API 分析、開發人員門戶和 API 管理儀表板。([源代碼](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go`


### 軟件開發 - 錯誤跟踪器

**[`^ 返回頂部 ^`](#)**

**請訪問[票務](#ticketing)**


### 軟件開發 - 持續集成和部署

**[`^ 返回頂部 ^`](#)**

**請訪問 [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**


### 軟件開發 - 文檔生成器

**[`^ 返回頂部 ^`](#)**

_相關：[靜態站點生成器]（#static-site-generators）_

- [Docstore](https://git.haldean.org/docstore/) - 靜態文檔託管，無需任何服務器端處理，每次更改文章時無需重新編譯。克隆存儲庫並在 text/ 目錄中添加文章以開始使用。([源代碼](https://github.com/haldean/docstore)) `BSD-3-Clause` `Javascript`
- [Flatdoc](https://ricostacruz.com/flatdoc/) - 獲取 Markdown 文件並將它們呈現為完整頁面的小型 Javascript 文件。`麻省理工學院``Javascript`
- [markdown-tree](https://github.com/mil/markdown-tree) - 提供 Markdown 文件的層次結構/樹目錄。用於內置降價的小型網站。`麻省理工學院``紅寶石`
- [閱讀文檔](https://readthedocs.org/) - 託管文檔，使其完全可搜索且易於查找；使用任何主要版本控制系統導入您的文檔，包括 Mercurial、Git、Subversion 和 Bazaar。([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/readthedocs/readthedocs.org)) `MIT` `Python`


### 軟件開發 - FaaS 和無服務器

**[`^ 返回頂部 ^`](#)**

[無服務器計算 - 維基百科](https://en.wikipedia.org/wiki/Serverless_computing)

- [Appwrite](https://appwrite.io) - 適用於 Web、本地和移動開發人員的端到端后端服務器🚀。([源代碼](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `PHP`
- [fx](https://github.com/metrue/fx) - fx 是一種工具，可幫助您在自己的服務器上輕鬆實現功能即服務。`麻省理工學院``去`
- [IronFunctions](https://github.com/iron-io/functions) - [iron.io](https://www.iron.io/) 的無服務器微服務平台。`Apache-2.0` `Go`
- [LocalStack](https://localstack.cloud/) - LocalStack 是一個功能齊全的本地 AWS 雲堆棧。這包括用於無服務器計算的 Lambda。([源代碼](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Other`
- [OpenFaaS](https://www.openfaas.com/) - 為 Docker 和 Kubernetes 簡化無服務器功能。([源碼](https://github.com/openfaas/faas)) `MIT` `Go`
- [Trusted-CGI](https://github.com/reddec/trusted-cgi) - 輕量級的自託管 lambda/applications/cgi/serverless-functions 平台。`麻省理工學院``去`


### 軟件開發 - IDE 和工具

**[`^ 返回頂部 ^`](#)**

- [Appsmith](https://www.appsmith.com/) - 用於構建管理面板、CRUD 應用程序和工作流的雲或自託管開源平台。構建您需要的一切，速度提高 10 倍。([源代碼](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker`
- [Atheos](https://www.atheos.io) - 基於 Web 的 IDE 框架，佔用空間小，要求最低，來自 Codiad。([源代碼](https://github.com/Atheos/Atheos)) `MIT` `PHP`
- [Babelfish](https://github.com/bblfsh/bblfshd) - 用於源代碼解析的自託管服務器。它可以解析任何支持的語言的任何文件，從中提取抽象語法樹，並將其轉換為通用抽象語法樹，從而可以進行進一步的分析和轉換。`GPL-3.0` `Go`
- [Budibase](https://www.budibase.com) - 在幾分鐘內構建和自動化內部工具、管理面板、儀表板、CRUD 應用程序等。Budibase 是 Outsystems、Retool、Mendix、Appian 的開源替代品。([源碼](https://github.com/Budibase/budibase)) `GPL-3.0` `Nodejs`
- [代碼服務器](https://coder.com/) - 瀏覽器中的 Visual Studio Code，託管在遠程服務器上。([源碼](https://github.com/cdr/code-server)) `MIT` `Nodejs/Docker`
- [Eclipse Che](https://www.eclipse.org/che/) - 開源工作空間服務器和雲 IDE。([源碼](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- [Gitpod](https://gitpod.io/) - GitHub 和 GitLab 的在線 IDE。([Demo](https://gitpod.io/#https://github.com/awesome-selfhosted/awesome-selfhosted), [源碼](https://github.com/gitpod-io/self-託管））`EPL-2.0``Go/Docker`
- [Hakatime](https://github.com/mujx/hakatime) - 帶有分析儀表板的 WakaTime 服務器實施。`未授權``Haskell`
- [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - 使用 HttPlaceholder 快速模擬任何 web 服務。HttPlaceholder 允許您指定請求的外觀以及需要返回的響應。`麻省理工學院` `C#`
- [ICEcoder](https://icecoder.net/) - ICEcoder 是一個基於 Web IDE / 瀏覽器的代碼編輯器，它允許您直接在 Web 瀏覽器中開發網站。([Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/icecoder/ICEcoder)) `MIT` `PHP`
- [JS Bin](https://jsbin.com/) - 開源協同web開發調試工具。([源碼](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
- [Judge0 CE](https://judge0.com) - 開源 API 編譯和運行源代碼。([源代碼](https://github.com/judge0/judge0)) `GPL-3.0` `Ruby`
- [JupyterLab](https://jupyterlab.github.io/jupyterlab/) - 用於交互式和可重複計算的基於 Web 的環境。([演示](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [源代碼](https://github.com/jupyterlab/jupyterlab /)) `BSD-3-Clause` `Python/Docker`
- [Lowdefy](https://www.lowdefy.com/) - 在自託管的開源平台上使用 YAML / JSON 在幾分鐘內構建內部工具、BI 儀表板、管理面板、CRUD 應用程序和工作流。通過 Serverless、Netlify 或 Docker 連接到您的數據源、主機。([源碼](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs`
- [ML Workspace](https://github.com/ml-tooling/ml-workspace) - 用於機器學習和數據科學的基於 Web 的一體化 IDE。`Apache-2.0` `Docker`
- [Motor Admin](https://www.getmotoradmin.com/) - 無代碼管理面板和商業智能軟件 - 搜索、創建、更新和刪除數據條目，創建自定義操作並構建報告。([Demo](https://motor-admin.herokuapp.com/demo/), [Source Code](https://github.com/motor-admin/motor-admin)) `AGPL-3.0` `Ruby `
- [Regexr](https://regexr.com/) - RegExr 是一個基於 HTML/JS 的工具，用於創建、測試和學習正則表達式。([源代碼](https://github.com/gskinner/regexr)) `MIT` `Nodejs`
- [RStudio 服務器](https://www.rstudio.com/products/rstudio/#Server) - 基於 Web 瀏覽器的 R IDE。([源代碼](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- [Slingcode](https://slingcode.net/) - 單個靜態 HTML 文件中的 Web 應用程序 IDE 和計算平台。([Demo](https://slingcode.net/slingcode.html), [Source Code](https://github.com/chr15m/slingcode/)) `MIT` `HTML`
- [sourcegraph](https://sourcegraph.com) - Sourcegraph 是一個用 Go 編寫的快速、開源、功能齊全的代碼搜索和導航引擎。([源代碼](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- [ToolJet](https://tooljet.io/) - ToolJet 是 Retool 和 Mendix 的開源低代碼框架替代方案，以最少的工程工作量構建和部署內部工具。([源代碼](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs`
- [Wakapi](https://wakapi.dev/) - 用於編碼統計的跟踪工具，與 WakaTime 兼容。([源代碼](https://github.com/muety/wakapi)) `GPL-3.0` `Go`


### 軟件開發 - 本地化

**[`^ 返回頂部 ^`](#)**

- [Accent](https://www.accent.reviews/) - 開源、自託管、面向開發人員的翻譯工具。([源代碼](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir`
- [Localizer](https://localizer.dev) - 為您的產品提供免費的自託管開源眾包翻譯服務。([Demo](https://localize.todorant.com), [Source Code](https://github.com/backmeupplz/localizer-backend)) `MIT` `Nodejs/Docker`
- [Pootle](https://pootle.translatehouse.org) - 在線翻譯和本地化工具。([源代碼](https://github.com/translate/pootle)) `GPL-3.0` `Python`
- [Tolgee](https://tolgee.io) - 開發人員和翻譯人員友好的基於 Web 的本地化平台，使用戶能夠直接在他們開發的應用程序中進行翻譯。([源代碼](https://github.com/tolgee/server)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.com) - 團隊翻譯管理平台。([源代碼](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/Nodejs`
- [Weblate](https://weblate.org) - 具有緊密版本控制集成的基於 Web 的翻譯工具。([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python`
- [Zanata](http://zanata.org) - 基於網絡的翻譯平台，供翻譯人員、內容創建者和開發人員管理本地化項目。([源代碼](https://github.com/zanata/zanata-platform)) `GPL-2.0` `Java`


### 軟件開發 - 項目管理

**[`^ 返回頂部 ^`](#)**

_相關：[票務](#ticketing)、[任務管理和待辦事項](#task-management--to-do-lists)_

_另見：[awesome-sysadmin/代碼審查](https://github.com/awesome-foss/awesome-sysadmin#code-review)_

- [Bonobo Git 服務器](https://bonobogitserver.com/) - 在 Windows 的 IIS 上設置您自己的自託管 git 服務器。通過用戶友好的圖形界面管理用戶並完全控制您的存儲庫。([源代碼](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 具有 wiki 和 bug 跟踪器的分佈式版本控制系統。`BSD-2-Clause-FreeBSD` `C`
- [Git WebUI](https://github.com/alberthier/git-webui) - 用於 git 存儲庫的基於 Web 的獨立用戶界面。`Apache-2.0` `Python`
- [Gitblit](https://gitblit.github.io/gitblit/) - 用於管理、查看和服務 Git 存儲庫的純 Java 堆棧。([源代碼](https://github.com/gitblit/gitblit)) `Apache-2.0` `Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/) - 易於安裝的 GitHub 克隆，由 Scala 提供支持。([源代碼](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.io) - Gogs 的社區管理分支，輕量級代碼託管解決方案。([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
- [GitLab](https://about.gitlab.com) - 自託管 Git 存儲庫管理、代碼審查、問題跟踪、活動提要和 wiki。([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- [Gitlist](https://gitlist.org/) - 基於 Web 的 git 存儲庫瀏覽器 - GitList 允許您使用您喜歡的瀏覽器瀏覽存儲庫，查看不同修訂版下的文件、提交歷史記錄和差異。([源代碼](https://github.com/klaussilveira/gitlist)) `BSD-3-Clause` `PHP`
- [Gitolite](https://gitolite.com/gitolite/index.html) - Gitolite 允許您在中央服務器上設置 git 託管，具有細粒度的訪問控制和許多更強大的功能。([源代碼](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- [GitPrep](https://gitprep.yukikimoto.com/) - 便攜式 Github 克隆。([Demo](https://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [Source Code](https://github.com/yuki-kimoto/gitprep))`Artistic-2.0`` Perl`
- [Gogs](https://gogs.io/) - 用 Go 編寫的無痛自託管 Git 服務。([Demo](https://try.gogs.io/), [Source Code](https://github.com/gogs/gogs)) `MIT` `Go`
- [Goodwork](https://usegood.work/) - 由 Laravel 和 VueJS 提供支持的自託管項目管理和協作工具。([Demo](https://github.com/iluminar/goodwork#demo), [Source Code](https://github.com/iluminar/goodwork)) `MIT` `PHP`
- [Kallithea](https://kallithea-scm.org/) - 源代碼管理系統，支持兩個領先的版本控制系統，Mercurial 和 Git，帶有 Web 界面。([源代碼](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- [Klaus](https://github.com/jonashaag/klaus) - 簡單、易於設置的 Git Web 查看器，可正常工作。`ISC` `Python`
- [Lavagna](https://lavagna.io) - Lavagna 是專為小型團隊設計的開源問題/項目管理工具。輕量級，純Java，安裝方便，使用方便。([源代碼](https://github.com/digitalfondue/lavagna)) `GPL-3.0` `Java`
- [Lazylead](https://lazylead.org) `⚠` - 消除票務系統（Jira、GitHub、Trello）中煩人的工作。允許自動執行日常操作，例如票證字段驗證、JQL/GQL 的電子郵件通知、向您（或隊友）日曆的會議請求。([源代碼](https://github.com/dgroup/lazylead)) `MIT` `Ruby`
- [Leantime](https://leantime.io) - Leantime 是一個精益項目管理系統，適用於小型團隊和初創公司，幫助管理從構思到交付的項目。([源代碼](https://github.com/leantime/leantime)) `GPL-2.0` `PHP`
- [Microgit](https://github.com/microgit-com/microgit) - Crystal 和 Lucky 製作的 Git 託管服務。`麻省理工學院``水晶`
- [Octobox](https://octobox.io/) `⚠` - 收回對 GitHub 通知的控制權。([源代碼](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby`
- [OneDev](https://onedev.io/) - 一體化 DevOps 平台。使用 Git 管理、問題跟踪和 CI/CD。簡單而強大。([源代碼](https://code.onedev.io/projects/160)) `MIT` `Java`
- [OpenProject](https://www.openproject.org) - OpenProject 是一個基於網絡的項目管理系統。([源代碼](https://github.com/opf/openproject)) `GPL-3.0` `Ruby`
- [Pagure](https://pagure.io/pagure) - 一個輕量級、強大且靈活的以 git 為中心的鍛造，其特性為聯合和去中心化開發奠定了基礎。([Demo](https://pagure.io/)) `GPL-2.0` `Python`
- [Phproject](https://www.phproject.org/) - 高性能全功能項目管理系統。([Demo](https://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- [ProjeQtOr](https://www.projeqtor.org/) - 一個完整、成熟、多用戶的項目管理系統，具有適用於項目所有階段的廣泛功能。([Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` ` PHP`
- [Re:Backlogs](https://github.com/kaishuu0123/rebacklogs) - 由 Ruby on Rails 和 VueJS 提供支持的項目管理和協作工具。([演示](https://rebacklogs.saino.me/users/sign_up)) `MIT` `Ruby`
- [Redmine](https://www.redmine.org/) - Redmine 是一個靈活的項目管理網絡應用程序。([Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [RhodeCode](https://rhodecode.com/) - RhodeCode 是軟件開發團隊的開源平台。它統一併簡化了 Git、Subversion 和 Mercurial 的存儲庫管理。([源代碼](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [SCM 管理器](https://www.scm-manager.org/) - 通過 http 共享和管理 Git、Mercurial 和 Subversion 存儲庫的最簡單方法。([源代碼](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java`
- [Taiga](https://taiga.io/) - 基於看板和 Scrum 方法的敏捷項目管理工具。([源代碼](https://github.com/taigaio)) `AGPL-3.0` `Python`
- [Titra](https://titra.io/en/free-time-tracking-online/) - 自由職業者和小團隊的時間跟踪解決方案。([Demo](https://app.titra.io/try), [Source Code](https://github.com/kromitgmbh/titra)) `GPL-3.0` `Javascript`
- [Trac](https://trac.edgewall.org/) - Trac 是用於軟件開發項目的增強型 wiki 和問題跟踪系統。`BSD-3-Clause` `Python`
- [Tuleap](https://www.tuleap.org/) - Tuleap 是一個自由套件，用於計劃、跟踪、編碼和協作軟件項目。([源代碼](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk 社區是一個面向服務、事件驅動的可擴展開源幫助台系統，您的組織可以使用它以任何您想像的方式輕鬆地為您的客戶提供有效的支持。([Demo](https://demo.uvdesk.com/), [Source Code](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 一個敏捷（scrum）項目管理系統/工具。([Demo](https://demo.zentao.pm/user-login.html), [源代碼](https://github.com/easysoft/zentaopms)) `ZPL-1.2` `PHP`


### 軟件開發 - UX 測試

**[`^ 返回頂部 ^`](#)**

- [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - 使用 HTTP 轉儲作為響應源的 Web 服務器。`麻省理工學院``Java`
- [Selenoid](https://aerokube.com/selenoid/latest/) - 在 Docker 容器中啟動瀏覽器的輕量級 Selenium 集線器實現。([源代碼](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- [Uier](https://github.com/sjoerdvanderhoorn/Uier) - 使用 Selenium 執行測試或 UI 自動化的無代碼或低代碼用戶體驗測試編輯和管理。UIer 往往是 Applitools、Endtest、Ghost Inspector、Usetrace、Screenster 和許多其他工具的免費自我託管替代品。`Apache-2.0` `Nodejs`


### 靜態站點生成器

**[`^ 返回頂部 ^`](#)**

**請訪問 [staticsitegenerators.net](https://staticsitegenerators.net)、[staticgen.com](https://www.staticgen.com)**

### 狀態/正常運行時間頁面

**[`^ 返回頂部 ^`](#)**

**請訪問 [awesome-sysadmin/Status Pages](https://github.com/awesome-foss/awesome-sysadmin#status-pages)**

- [cState](https://github.com/cstate/cstate/) - 超高速 Hugo 的靜態頁面。簡潔的設計，最小的 JS，超輕的 HTML/CSS，高度定制，可選的管理面板，只讀 API，IE8+。最適合與 Netlify、Docker 一起使用。([Demo](https://cstate.mnts.lt/)) `MIT` `Go`
- [s.Status](https://github.com/scolastico-dev/s.Status) - s.Status 是一個用java編寫的開源服務器狀態頁面。([演示](https://status.scolasti.co/)) `MPL-2.0` `Java`
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - 類似“Uptime Robot”的自託管網站監控工具。([Demo](https://demo.uptime.kuma.pet)) `MIT` `Nodejs`


### 任務管理和待辦事項列表

**[`^ 返回頂部 ^`](#)**

_相關：[軟件開發-項目管理](#software-development---project-management)，[票務](#ticketing)_

- [Focalboard](https://www.focalboard.com/) - Trello、Notion 和 Asana 的開源、自託管替代方案。它有助於跨個人和團隊定義、組織、跟踪和管理工作。([源代碼](https://github.com/mattermost/focalboard), [客戶端](https://www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/ Apache-2.0` `Nodejs/Go`
- [Kanbana](https://github.com/SrGMC/kanbana) - 創建板以從平面降價文件跟踪用戶和項目。從 Crepido 分叉。`麻省理工學院` `Nodejs`
- [Kanboard](https://kanboard.net/) - 簡單開源的可視化任務板。([源碼](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [myTinyTodo](https://www.mytinytodo.net/) - 以 AJAX 風格管理您的待辦事項列表的簡單方法。使用 PHP、jQuery、SQLite/MySQL。符合 GTD。([Demo](https://www.mytinytodo.net/demo/), [Source Code](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 單頁極簡看板；緊湊，可讀性強，使用快速。`BSD-2-Clause` `Javascript`
- [Planka](https://planka.app/) - 開源 Trello 替代方案。([Demo](https://plankanban.github.io/planka/#/), [Source Code](https://github.com/plankanban/planka))`MIT``Nodejs`
- [Restyaboard](https://restya.com/board/) - 開源的類似 Trello 的看板。([Demo](https://restya.com/board/demo), [Source Code](https://github.com/RestyaPlatform/board)) `OSL-3.0` `PHP`
- [Task Keeper](https://github.com/nymanjens/piga) - 高級用戶的列表編輯器，由自託管服務器提供支持。`Apache-2.0` `Scala`
- [TaskBoard](https://taskboard.matthewross.me/) - 受看板啟發的應用程序，用於跟踪需要完成的事情。([Demo](https://taskboard.matthewross.me/demo.html), [Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
- [Taskfreak](https://www.taskfreak.com/original) - 用 PHP 編寫的簡單但高效的基於 Web 的任務管理器。`GPL-3.0` `PHP`
- [Taskord](https://taskord.com) - 與創客社區一起完成社交任務。([源碼](https://gitlab.com/yo/taskord)) `MIT` `PHP`
- [tasks.php](https://github.com/lgg/tasks.php) - 使用 JSON 文本文件執行任務的簡單任務/待辦事項列表。`麻省理工學院` `PHP`
- [任務](https://github.com/m1guelpf/tasks) - 使用自定義平面文件數據庫用 PHP、jQuery 和 Bootstrap 編寫的簡單任務和註釋管理器。`MPL-2.0` `PHP`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是免費的開源軟件，可以從命令行管理您的 TODO 列表。它靈活、快速、高效且不引人注目。它完成了它的工作，然後讓你離開。([源代碼](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [thewhitetulip Tasks](https://github.com/thewhitetulip/Tasks) - 用 Go 編寫的基於看板的待辦事項列表管理器。`麻省理工學院``去`
- [todo](https://git.mills.io/prologic/todo) - 簡單的待辦事項列表管理器。([Demo](https://todo.mills.io)) `MIT` `Go`
- [todoMini](https://www.todomini.app/) - 移動友好的零功能 TODO 列表 web 應用程序。Unix哲學。([Demo](https://appmini.github.io/todoMini/?demo), [Source Code](https://github.com/appMini/todoMini)) `GPL-3.0` `PHP/Java`
- [Tracks](https://www.getontracks.org/) - 基於 Web 的應用程序可幫助您實施 David Allen 的 [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) 方法。([源代碼](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [Vikunja](https://vikunja.io/) - 用於組織生活的待辦事項應用程序。([Demo](https://try.vikunja.io/login), [Source Code](https://kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 開源的類似 Trello 的看板。([源碼](https://github.com/wekan/wekan)) `MIT` `Nodejs`


＃＃＃ 票務

**[`^ 返回頂部 ^`](#)**

_相關：[任務管理和待辦事項](#task-management--to-do-lists)、[軟件開發-項目管理](#software-development---project-management)_

- [Bugzilla](https://www.bugzilla.org/) - 最初由 Mozilla 項目開發和使用的通用 bugtracker 和測試工具。`MPL-2.0` `Perl`
- [Bumpy Booby](https://bumpy-booby.derivoile.fr/) - 簡單、響應迅速且高度可定制的 PHP 錯誤跟踪系統。([源代碼](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
- [django-todo](http://django-todo.org/) - django-todo 是一個可插入的、多用戶、多組、多列表的待辦事項和票務系統 - 一個可重用的應用程序，旨在放入任何現有的 Django 項目。([源代碼](https://github.com/shacker/django-todo)) `BSD-3-Clause` `Python/Django`
- [Erxes](https://erxes.io/install/) - 旨在幫助企業吸引更多參與客戶的營銷、銷售和客戶服務平台。([Demo](https://demo.erxes.io/), [Source Code](https://github.com/erxes/erxes)) `GPL-3.0` `Javascript`
- [Flyspray](https://www.flyspray.org/) - 簡單的基於網絡的錯誤跟踪系統。([源碼](https://github.com/Flyspray/flyspray)) `GPL-2.0` `PHP`
- [FreeScout](https://github.com/freescout-helpdesk/freescout) - Help Scout 的開源克隆：基於電子郵件的客戶支持應用程序、幫助台和共享郵箱。`AGPL-3.0` `PHP`
- [GlitchTip](https://glitchtip.com) - 開源錯誤跟踪應用程序。GlitchTip 收集您的應用報告的錯誤。([源代碼](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python`
- [Helpy](https://helpy.io) - Helpy 是一個現代的開源幫助台客戶支持應用程序。功能包括知識庫、社區討論和與電子郵件集成的支持票。([Demo](https://demo.helpy.io), [Source Code](https://github.com/helpyio/helpy)) `MIT` `Ruby`
- [HuBoard](https://github.com/huboard/huboard) `⚠` - GitHub 問題的即時項目管理（直接連接 GitHub API）。`麻省理工學院``紅寶石`
- [MantisBT](https://www.mantisbt.org/) - 自託管錯誤跟踪器，最適合軟件開發。([Demo](https://www.mantisbt.org/bugs/my_view_page.php), [Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OpenSupports](https://www.opensupports.com/) - 具有常見問題解答、角色管理、指標和預設響應功能的多語言票證系統。([Demo](https://www.opensupports.com/demo/), [Source Code](https://github.com/opensupports/opensupports)) `GPL-3.0` `PHP`
- [osTicket](https://osticket.com/) - 在一個地方管理、組織和存檔您的所有支持請求和響應。([源碼](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.de/en/) - 靈活的基於網絡的票務系統，用於客戶服務、幫助台、IT 服務管理。([Demo](https://otobo.de/en/open-source-ticketing-system/#demos), [Source Code](https://github.com/RotherOSS/otobo))`GPL-3.0` `Perl`
- [Pachno](https://pach.no/) - 將您的團隊聚集在一起，使用適合您和您的團隊並在您需要時進行調整的工具來設計、構建和交付您的項目。([源代碼](https://github.com/pachno/pachno)) `MPL-2.0` `PHP`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企業級問題跟踪系統。([源代碼](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup 問題跟踪器](https://www.roundup-tracker.org/) - 一個易於使用和安裝的問題跟踪系統，帶有命令行、Web、REST、XML-RPC 和 e-郵件接口。設計時考慮到了靈活性——不僅僅是另一個錯誤跟踪器。([源代碼](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python`
- [Sentry On-Premise](https://github.com/getsentry/onpremise) - 一個強大的錯誤跟踪平台，具有廣泛的語言支持和強大的 API。([源代碼](https://github.com/getsentry/sentry)) `BSD-3-Clause` `Python/Django`
- [SIT](https://sit.fyi/) - 與 SCM 無關、基於文件、離線優先、不可變的問題跟踪器。([源代碼](https://github.com/sit-fyi/sit)) `MIT` `Apache-2.0` `Rust`
- [Trudesk](https://trudesk.io/) - Trudesk 是一個開源幫助台/票務解決方案。([源代碼](https://github.com/polonel/trudesk)) `Apache-2.0` `Nodejs`
- [Zammad](https://zammad.org/) - 易於使用但功能強大的開源支持和票務系統。([源代碼](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby`


### 時間追踪器

**[`^ 返回頂部 ^`](#)**

- [ActivityWatch](https://activitywatch.net) - 一款自動跟踪您在設備上花費時間的應用程序。([源代碼](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Kimai](https://www.kimai.org/) - Kimai 是一個免費和開源的時間跟踪器。它跟踪工作時間並按需打印出您的活動摘要。([Demo](https://www.kimai.org/demo/), [Source Code](https://github.com/kevinpapst/kimai2/)) `MIT` `PHP`
- [TimeTagger](https://timetagger.app) - 基於交互式時間線和強大報告的開源時間跟踪器。([Demo](https://timetagger.app/app/demo), [Source Code](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`


### URL 縮短器

**[`^ 返回頂部 ^`](#)**

在託管之前，請參閱 URL 縮短器的 [缺點](https://en.wikipedia.org/wiki/URL_shortening#Shortcomings)。

- [Blink](https://docs.blink.rest) - 易於託管、集成 SSO、支持 CDN 的鏈接縮短器（+解耦分析），適用於團隊。([源代碼](https://github.com/JaneJeon/blink)) `AGPL-3.0` `Nodejs`
- [goshorly](https://git.ucode.space/Phil/goshorly) - Golang 中一個簡單的自託管鏈接縮短器，帶有 Redis <3。([Demo](https://gly.one)) `MIT` `Go`
- [Kutt](https://kutt.it) - 支持自定義域的現代 URL 縮短器。([源代碼](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs`
- [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end) `⚠` - 使用 Telegram Bot 的 URL 縮短器。([演示](https://t.me/GiveMeShortLinkBot)) `MIT` `Ruby`
- [鏈接](https://fsh.ee) - 一個最小的、支持 SQLite 的 URL 縮短器。([Demo](https://demo.fsh.ee), [Source Code](https://git.fsh.ee/i/link)) `GPL-3.0` `Go`
- [liteshort](https://github.com/132ikl/liteshort) - 用戶友好、實際上是輕量級且可配置的 URL 縮短器。([Demo](https://ls.ikl.sh)) `MIT` `Python`
- [Lstu](https://github.com/ldidry/lstu) - _讓我們縮短那個 Url_ - 輕量級 URL 縮短器。`WTFPL` `Perl`
- [Polr](https://project.polr.me/) - 現代、簡約、模塊化和輕量級的 URL 縮短器。([源代碼](https://github.com/Cydrobolt/polr)) `GPL-2.0` `PHP`
- [reduc.io](https://github.com/ziyasal/reducio) - 使用 Scala 編寫的 URL 縮短服務，使用 Akka-Http 和 Redis。`麻省理工學院``斯卡拉`
- [ReducePy](https://github.com/abdullahselek/ReducePy) - 使用 Tornado 和 Redis 的 URL 縮短服務在 Docker 和 Kubernetes 上運行。`麻省理工學院``Python`
- [schort](https://github.com/sqozz/schort) - 沒有登錄，沒有 javascript，只有短鏈接。([Demo](https://s.wx0.de)) `CC0-1.0` `Python`
- [Shlink](https://shlink.io) - 帶有 REST API 和命令行界面的 URL 縮短器。包括官方漸進式 Web 應用程序和 docker 圖像。([源碼](https://github.com/shlinkio/shlink), [客戶端](https://shlink.io/apps)) `MIT` `PHP`
- [shorturl](https://git.mills.io/prologic/shorturl) - 帶有非常小的 URL 的簡單 URL 縮短器。([Demo](https://url.mills.io)) `MIT` `Go`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL 縮短器，公共或私有（有帳戶）。極簡主義和輕量級。沒有依賴關係。([演示](https://u.azlux.fr)) `MIT` `PHP`
- [Simply Shorten](https://gitlab.com/daganczukp/simply-shorten) - 一個簡單的 URL 縮短器，它只是縮短鏈接。`麻省理工學院``Java`
- [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - 糟糕的 url 縮短器、表情符號和 AI 驅動。`麻省理工學院` `Nodejs`
- [YOURLS](https://yourls.org/) - YOURLS 是一組 PHP 腳本，可讓您運行自己的 URL Shortener。功能包括密碼保護、URL 定制、書籤、統計、API、插件、jsonp。([源代碼](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### VPN

**[`^ 返回頂部 ^`](#)**

**請訪問[awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**


### 網絡服務器

**[`^ 返回頂部 ^`](#)**

**請訪問[awesome-sysadmin/Web](https://github.com/awesome-foss/awesome-sysadmin#web)**


### 維基

**[`^ 返回頂部 ^`](#)**

_相關：[軟件開發 - 文檔生成器](#software-development---documentation-generators)_

_另請參閱：[Wikimatrix](https://www.wikimatrix.org/)、[Wiki Engines - WikiIndex](https://wikiindex.org/Category:Wiki_Engine)、[Wiki 軟件列表 - Wikipedia](https: //en.wikipedia.org/wiki/List_of_wiki_software), [wiki 軟件比較 - 維基百科](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [BookStack](https://www.bookstackapp.com/) - BookStack 是一個用於組織和存儲信息的簡單、自託管、易於使用的平台。它允許將文檔存儲在類似時尚的書籍中。([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/BookStackApp/BookStack)) `MIT` `PHP`
- [Cowyo](https://github.com/schollz/cowyo) - Cowyo 是一個功能豐富的極簡主義維基。([Demo](https://cowyo.com)) `MIT` `Go`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 具有復雜功能的 Wiki 系統，用於簡單集成和一流的界面。用風格存儲你的知識：使用 django 模型。([演示](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [Documize](https://documize.com) - Modern Docs + Wiki 軟件，內置工作流程，單個二進制可執行文件，只需帶 MySQL/Percona。([源代碼](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 易於使用、輕量級、符合標準的 wiki 引擎，語法簡單，允許在 wiki 之外讀取數據。所有數據都存儲在普通文件中，因此不需要數據庫。([源代碼](https://github.com/splitbrain/dokuwiki)) `GPL-2.0` `PHP`
- [Gitit](https://github.com/jgm/gitit) - 將頁面和上傳文件存儲在 git 存儲庫中的 Wiki 程序，然後可以使用 VCS 命令行工具或 wiki 的 Web 界面對其進行修改。`GPL-2.0` `Haskell`
- [Gollum](https://github.com/gollum/gollum) - 簡單的、由 Git 驅動的 wiki，具有良好的 API 和本地前端。`麻省理工學院``紅寶石`
- [jingo](https://github.com/claudioc/jingo) - 為 node.js 編寫的基於 Git 的 wiki 引擎，具有不錯的設計、搜索功能和良好的排版。`麻省理工學院` `Nodejs`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki 是一個免費的開源 wiki 軟件包，用 PHP 編寫。它是維基百科和其他維基媒體項目的平台，每月有數億人使用。([Demo](https://en.wikipedia.org/wiki/Main_Page), [Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- [MoinMoin](https://moinmo.in/) - 高級、易於使用和可擴展的 WikiEngine，擁有龐大的用戶社區。([源代碼](https://github.com/moinwiki/moin-1.9)) `GPL-2.0` `Python`
- [大綱](https://www.getoutline.com/) `⚠` - 一個開放、可擴展的 wiki，適合您的團隊。([源代碼](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - 包含在單個 PHP 文件中的完整的 markdown 驅動的 wiki。([演示](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- [PineDocs](https://github.com/xy2z/PineDocs) - 用於瀏覽文件的簡單、快速、可定制和輕量級的站點。`GPL-3.0` `PHP`
- [PmWiki](https://www.pmwiki.org) - 用於協作創建和維護網站的基於 Wiki 的系統。`GPL-3.0` `PHP`
- [Raneto](http://raneto.com/) - Raneto 是一個開源知識庫平台，它使用靜態 Markdown 文件來支持您的知識庫。`麻省理工學院` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可重複使用的非線性個人網絡筆記本。([源代碼](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org) - 具有最多內置功能的 Wiki CMS 組件。([Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/))​​ `LGPL-2.1` `PHP`
- [TWiki](https://twiki.org/) - TWiki 是基於 Perl 的結構化 wiki 應用程序，通常用於運行協作平台、知識或文檔管理系統、知識庫或團隊門戶。([Demo](https://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL-1.0` `Perl`
- [WackoWiki](https://wackowiki.org/) - WackoWiki 是一個輕量且易於安裝的多語言 Wiki 引擎。([源代碼](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki.js](https://wiki.js.org/) - 使用 Git 和 Markdown 的現代、輕量級和強大的 wiki 應用程序。([Demo](https://docs.requarks.io)) `AGPL-3.0` `Nodejs`
- [wiki](https://git.mills.io/prologic/wiki) - 基於簡單 Markdown 的 wiki 引擎。([Demo](https://wiki.mills.io)) `MIT` `Go`
- [WiKiss](https://wikiss.tuxfamily.org/) - Wiki，易於使用和安裝。([源代碼](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [Wikmd](https://github.com/Linbreux/wikmd) - 使用 Markdown 和 Git 的現代而簡單的基於文件的 wiki。`麻省理工學院``Python`
- [XWiki](https://www.xwiki.org) - 第二代 wiki，允許用戶使用強大的基於擴展的架構擴展其功能。([Demo](https://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java`
- [Zim](https://zim-wiki.org/) - 用於維護 wiki 頁面集合的圖形文本編輯器。每個頁面都可以包含指向其他頁面的鏈接、簡單的格式和圖像。([源代碼](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python`


--------------------

## 許可證列表

**[`^ 返回頂部 ^`](#)**

- `0BSD` - [BSD 零條款許可證](https://opensource.org/licenses/0BSD)
- `AAL` - [署名保證許可證](https://opensource.org/licenses/AAL)
- `AGPL-3.0` - [GNU Affero 通用公共許可證 3.0](https://www.gnu.org/licenses/agpl-3.0)
- `AGPL-3.0-only` - [僅限 GNU Affero 通用公共許可證 3.0](https://spdx.org/licenses/AGPL-3.0-only.html)
- `Apache-2.0` - [Apache，2.0 版](https://www.apache.org/licenses/)
- `APSL-2.0` - [Apple 公共源代碼許可證，版本 2.0](https://opensource.org/licenses/APSL-2.0)
- `Artistic-2.0` - [藝術許可版本 2.0](https://opensource.org/licenses/Artistic-2.0)
- `Beerware` - [Beerware 許可證](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://opensource.org/licenses/BSD-2-Clause)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD 許可證](https://www.freebsd.org/copyright/freebsd-license.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://opensource.org/licenses/BSD-3-Clause)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 國際許可](https://creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - [公共領域](https://creativecommons.org/about/cc0/)
- `CDDL-1.0` - [通用開發和分發許可證](https://opensource.org/licenses/CDDL-1.0)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [通用公共署名許可版本 1.0](https://opensource.org/licenses/CPAL-1.0)
- `ECL-2.0` - [教育社區許可證，版本 2.0](https://opensource.org/licenses/ECL-2.0)
- `EPL-1.0` - [Eclipse 公共許可證，版本 1.0](https://www.eclipse.org/legal/epl-v10.html)
- `EPL-2.0` - [Eclipse 公共許可證，版本 2.0](https://www.eclipse.org/legal/epl-v20.html)
- `EUPL-1.2` - [歐盟公共許可證 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-11-12)
- `GFDL-1.1-only` - [GNU 自由文檔許可證 v1.1](https://spdx.org/licenses/GFDL-1.1-only.html)
- `GFDL-1.1-or-later` - [GNU 自由文檔許可證 v1.1](https://spdx.org/licenses/GFDL-1.1-or-later.html)
- `GFDL-1.2-only` - [GNU 自由文檔許可證 v1.2](https://spdx.org/licenses/GFDL-1.2-only.html)
- `GFDL-1.2-or-later` - [GNU 自由文檔許可證 v1.2](https://spdx.org/licenses/GFDL-1.2-or-later.html)
- `GFDL-1.3-only` - [GNU 自由文檔許可證 v1.3](https://spdx.org/licenses/GFDL-1.3-only.html)
- `GFDL-1.3-or-later` - [GNU 自由文檔許可證 v1.3](https://spdx.org/licenses/GFDL-1.3-or-later.html)
- `GPL-1.0` - [GNU 通用公共許可證](https://www.gnu.org/licenses/gpl-1.0)
- `GPL-2.0` - [GNU 通用公共許可證 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- `GPL-2.0-or-later` - [GNU 通用公共許可證 v2.0 或更高版本](https://spdx.org/licenses/GPL-2.0-or-later.html)
- `GPL-3.0-only` - [僅限 GNU 通用公共許可證 v3.0](https://spdx.org/licenses/GPL-3.0-only.html)
- `GPL-3.0-or-later` - [GNU 通用公共許可證 v3.0 或更高版本](https://spdx.org/licenses/GPL-3.0-or-later.html)
- `GPL-3.0` - [GNU 通用公共許可證 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
- `IPL-1.0` - [IBM 公共許可證](https://opensource.org/licenses/IPL-1.0)
- `ISC` - [互聯網系統聯盟許可證](https://www.isc.org/downloads/software-support-policy/isc-license/)
- `LIL-1.0` - [Lil 許可證 v1](https://www.lillicense.org/v1.html)
- `LGPL-2.1` - [較小的通用公共許可證 2.1](https://opensource.org/licenses/LGPL-2.1)
- `LGPL-3.0` - [較小的通用公共許可證 3.0](https://opensource.org/licenses/LGPL-3.0)
- `MIT` - [MIT 許可證](https://opensource.org/licenses/MIT)
- `MPL-1.1` - [Mozilla 公共許可證版本 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
- `MPL-2.0` - [Mozilla 公共許可證](https://www.mozilla.org/MPL/2.0/index.txt)
- `OSL-3.0` - [開放軟件許可證 3.0](https://opensource.org/licenses/osl-3.0.php)
- `Sendmail` - [Sendmail 許可證](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
- `Unlicense` - [The Unlicense](https://unlicense.org/)
- `WTFPL` - [你想做什麼就做什麼公共許可證]（http://www.wtfpl.net/about/）
- `Zlib` - [Zlib/libpng 許可證](https://opensource.org/licenses/Zlib)
- `ZPL-1.2` - [Zope 公共許可證 1.2](http://zpl.pub/page/zplv12)
- `ZPL-2.0` - [Zope 公共許可證 2.0](https://opensource.org/licenses/ZPL-2.0)

--------------------

##反特徵

- `⚠ ` - 依賴於用戶無法控制的專有服務

--------------------

＃＃ 外部鏈接

**[`^ 返回頂部 ^`](#)**

- [很棒的大數據](https://github.com/0xnr/awesome-bigdata) - 很棒的大數據框架、資源和其他很棒的精選列表。
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - 以主題為中心的高質量公共數據源列表。
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 非常棒的開源系統管理員資源的精選列表。
- 以某種形式針對隱私和去中心化的軟件列表：[PRISM Break](https://prism-break.org/en/)、[privacytools.io](https://www.privacytools.io/)、 [另類互聯網](https://redecentralize.github.io/alternative-internet/)、[Libre Projects](https://libreprojects.net/)
- [Easy Indie App](https://easyindie.app) - 只需點擊幾下即可自託管的應用程序。
- 動態域名服務：[Afraid.org](https://freedns.afraid.org/domain/registry/)、[Pagekite](https://pagekite.net/)
- 社區/論壇：[/r/selfhosted](https://www.reddit.com/r/selfhosted)、[IndieWeb](https://indieweb.org/)
- 鏡像：[GitHub.com](https://github.com/awesome-selfhosted/awesome-selfhosted)、[Gitlab.com](https://gitlab.com/awesome-selfhosted/awesome-selfhosted)
- [跟踪 Awesome Selfhosted](https://www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - 獲取 awesome-selfhosted 的最新更新。

--------------------

## 貢獻

貢獻指南可以在 [.github/CONTRIBUTING.md](.github/CONTRIBUTING.md) 中找到。

## 作者

作者列表可以在 [AUTHORS.md](AUTHORS.md) 中找到。

＃＃ 執照

此列表在 [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) 許可下。