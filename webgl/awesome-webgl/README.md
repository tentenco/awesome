# Awesome WebGL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="webgl_logo.png" align="right" width="175">](https://www.khronos.org/webgl/)

這是一個很棒的 WebGL 庫、資源等的精選列表。

## 什麼是 WebGL

WebGL（Web 圖形庫）是一種 JavaScript API，用於在內部渲染交互式 3D 計算機圖形和 2D 圖形
任何不使用插件的兼容網絡瀏覽器。WebGL 已完全集成到所有 Web 標準中
瀏覽器允許 GPU 加速使用物理和圖像處理以及作為網頁畫布一部分的效果。

WebGL 元素可以與其他 HTML 元素混合，並與頁面或頁面背景的其他部分合成。
WebGL 程序由用 JavaScript 編寫的控制代碼和在計算機圖形上執行的著色器代碼組成
處理單元 (GPU)。

＃＃ 內容
* [WebGL](#webgl)
* [WebGL 2](#webgl-2)
* [網絡虛擬現實](#webvr)
* [庫](#libraries)
* [社區](#community)

## WebGL

> 所有與 WebGL 打交道的事情

### WebGL 子類別
* [文章](#articles)
* [博客系列](#blog-series)
* [書籍](#books)
* [錯誤報告](#bug-reporting)
* [GLSL 編輯器](#glsl-editors)
* [參考文獻](#references)
* [會談](#talks)
* [工具/調試](#toolsdebugging)
  * [Chrome 特定工具/調試器](#chrome-specific-toolsdebugger)
  * [Firefox 特定工具/調試器](#firefox-specific-toolsdebugger)
* [教程](#tutorials)
* [視頻](#videos)

### 文章

> WebGL 文章和/或博客文章（非教程）

* [上下文丟失和預加載](https://medium.com/@mattdesl/non-intrusive-webgl-cebd176c281d#.gyc6h9mr5) - 當您遇到可怕的上下文丟失時如何管理 WebGL。
* [WebGL Off the Main Thread](https://hacks.mozilla.org/2016/01/webgl-off-the-main-thread/) - 如何在 WebGL 中使用 Web Workers。
* [優化場景以獲得更好的 WebGL 性能](https://www.soft8soft.com/docs/manual/en/introduction/Optimizing-WebGL-performance.html) - 經證明適用於創建基於 WebGL 的交互的優化技術.
* [WebGL 的第一步](https://dev.to/aralroca/first-steps-in-webgl-385c) - 通過繪製三角形了解什麼是 WebGL 及其工作原理。

### 博客系列

> WebGL 主題博客系列

* [Codeflow](http://codeflow.org/tags/webgl.html) - 許多關於不同技巧和技術的博客。
* [實時渲染](http://www.realtimerendering.com/blog/tag/webgl/) - 這是《實時渲染》一書的博客。
* [WebGL 最佳實踐](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/WebGL_best_practices) - Mozilla 的官方最佳實踐集。
* [WebGL Insights](http://webglinsights.blogspot.com/) - 這是 _WebGL Insights_ 一書的博客。
* [WebGL 月](https://github.com/lesnitsky/webgl-month) – 一個月的每日 WebGL 教程。

### 書籍

> 關於 WebGL 的熱門書籍

* [交互式計算機圖形：使用 WebGL 的自上而下方法](https://www.amazon.com/Interactive-Computer-Graphics-Top-Down-Approach/dp/0133574849) **Edward Angel** 和 * *Dave Shreiner** - 適合計算機科學與工程專業的本科生，具有良好編程技能的其他學科的學生，以及對使用最新版本的 WebGL 的計算機動畫和圖形感興趣的專業人士。
* [Professional WebGL Programming](https://www.amazon.com/Professional-WebGL-Programming-Developing-Graphics/dp/1119968860) 作者 **Andreas Anyuru** - 關於開發硬件加速 3D 你需要知道的一切使用 WebGL 的圖形。
* [Programming 3D Applications with HTML5 and WebGL](https://www.amazon.com/Programming-Applications-HTML5-WebGL-Visualization/dp/1449362966) by **Tony Parisi** - 創建高性能，視覺震撼Web 的 3D 應用程序，使用 HTML5 和相關技術，例如 CSS3 和 WebGL——新興的 Web 圖形標準。
* [WebGL 初學者指南](https://www.amazon.com/WebGL-Beginners-Guide-Diego-Cantor/dp/184969172X) 作者：**Diego Cantor** 和 **Brandon Jones** - 適用於 JavaScript 開發人員想通過 WebGL 涉足 3D 網絡開發。
* [WebGL Hotshot](https://www.amazon.com/WebGL-Hotshot-Mitch-Williams-ebook/dp/B00KLAJ65Y) by **Mitch Williams** - 適用於希望擴展 3D 圖形概念知識的網頁設計師並拓寬您現有的技能組合。
* [WebGL Insights](https://github.com/WebGLInsights/WebGLInsights.github.io/releases/download/v1.0/WebGL.Insights.-.Patrick.Cozzi.pdf) 作者：**Patrick Cozzi** -通過匯集經驗豐富的 WebGL 引擎和應用程序開發人員、GPU 供應商、瀏覽器開發人員、研究人員和教育工作者的貢獻，為中級和高級 WebGL 開發人員展示真實世界的技術。
  * [本書的個人站點](http://www.webglinsights.com/)
* [WebGL 編程指南：使用 WebGL 進行交互式 3D 圖形編程](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) **Kouichi Matsuda** 和 **Rodger Lea ** - WebGL 編程指南將幫助您快速開始交互式 WebGL 3D 編程，即使您事先不了解 HTML5、JavaScript、3D 圖形、數學或 OpenGL。

### 錯誤報告

> 從長遠來看，報告錯誤對每個人都有幫助

* [Chrome 錯誤報告](https://bugs.chromium.org/p/chromium/issues/list) - Chrome 相關錯誤
* [Khronos Github 問題頁面](https://github.com/KhronosGroup/WebGL/issues) - 規範或一致性相關的錯誤
* [Mozilla BugZilla](https://bugzilla.mozilla.org) - Firefox 相關錯誤
* [WebKit Bugzilla](https://bugs.webkit.org/enter_bug.cgi?assigned_to=cmarrin%40apple.com&attachurl=&blocked=&bug_file_loc=http%3A%2F%2F&bug_severity=Normal&bug_status=NEW&comment=&component=WebGL&contenttypeentry=&contenttypemethod= autodetect&contenttypeselection=text%2Fplain&data=&dependson=&description=&flag_type-1=X&flag_type-3=X&form_name=enter_bug&keywords=&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=Mac%20OS%20X%2010.5&priority=P2&product=WebKit&hordesc&rep_platform=P2&產品=WebKit&hordesc&rep_platform= =528%2B%20%28Nightly%20build%29) - Safari 相關的錯誤

### GLSL 編輯器

> 在線 GLSL 編輯器
>
> 注意：[WebGL 必須符合 OpenGL ES 著色語言，版本 1.00](https://www.khronos.org/registry/webgl/specs/1.0.3/#4.3)
>
> [GLSL 1.00 版官方規範](https://www.khronos.org/registry/OpenGL/specs/es/2.0/GLSL_ES_Specification_1.00.pdf)
>
> [Open ES 版本 2.0.25 的官方規範](https://www.khronos.org/registry/OpenGL/specs/es/2.0/es_full_spec_2.0.pdf)

* [Fractal Lab](http://hirnsohle.de/test/fractalLab/) - 在線分形瀏覽器，讓您探索 2D 和 2D 分形。
* [GLSL Sandbox](http://glslsandbox.com) - 片段著色器的在線實時編輯器。
* [GLSLbin](http://glslb.in) - 片段著色器沙箱支持 [glslify](https://github.com/glslify/glslify)。
* [Shader Toy](https://www.shadertoy.com) - 最流行的片段著色器實時編輯器。
* [ShaderFrog](https://shaderfrog.com/) - WebGL 著色器編輯器和作曲器。
* [SHDR 編輯器](http://shdr.bkcore.com) - 實時 GLSL 著色器編輯器、查看器和驗證器。
* [ShaderExpo](https://anuraghazra.github.io/ShaderExpo/) - 無依賴性著色器編輯器，具有內聯錯誤日誌、自動完成、模型和紋理加載功能。

＃＃＃ 參考

> WebGL 參考資料

* [Google Project ANGLE](https://github.com/google/angle) - Windows 平台上 Google Chrome 和 Mozilla Firefox 的默認 WebGL 後端。
* [Khronos 官方維基](https://www.khronos.org/webgl/wiki/) - WebGL 的官方維基。
* [WebVR Community Group](https://www.w3.org/community/immersive-web/) - 其目標是幫助將高性能虛擬現實帶入開放網絡。
* [WebGL 勘誤表](https://www.khronos.org/webgl/wiki/Errata_to_the_WebGL_Specification) - 圖形驅動程序中的已知錯誤會影響一致性套件，從而影響代碼的可移植性。
* [WebGL 擴展](https://www.khronos.org/registry/webgl/extensions/) - WebGL 擴展列表
* [WebGL 參考卡](https://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf) - 用於打印的 WebGL 1.0 API 快速參考卡。
* [WebGL 源代碼](https://github.com/KhronosGroup/WebGL) - 查看和貢獻的源代碼。
* [WebGL 規格表](https://www.khronos.org/registry/webgl/specs/1.0/) - 關於 WebGL 的所有詳細信息。


### 會談

> WebGL 相關講座

* [演示列表](https://www.khronos.org/webgl/wiki/Presentations) - Khronos 提供的各種 WebGL 相關演示列表。
* [Web 上的下一代 3D 圖形](https://www.youtube.com/watch?v=K2JzIUIHIhc) - 來自 Ricardo Cabello (MrDoob) 的 Google I/O 19 演講。

### 工具/調試

> 用於開發和調試 WebGL 的工具

* [Khronos Dev Tools](https://github.com/KhronosGroup/WebGLDeveloperTools) - 有用的 WebGL 開發工具，旨在用作 ES6 模塊。
* [Spector.js](https://spector.babylonjs.com/) - 不可知的 JavaScript 框架，用於探索 WebGL 場景並對其進行故障排除。
* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - 受 gDEBugger 和 PIX 啟發的工具，旨在簡化高級 WebGL 應用程序的開發。
* [WebGl Playground](http://jessevdk.github.io/webgl-play/) - 該編輯器讓您可以同時處理 JavaScript 代碼和 GLSL 頂點/片段著色器（如果有的話）方便的方式。一切都按照您的意願進行了組織、格式化和突出顯示。
* [WebGL 報告](http://webglreport.com/?v=1) - 查看您的瀏覽器對 WebGL 支持的詳細信息的方法。
* [WebGL 支持統計](http://webglstats.com/) - 交互式儀表板顯示不同瀏覽器和設備對 WebGL 功能的支持。
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - 嘗試加載 WebGL 支持的每種紋理格式之一，旨在快速顯示您的瀏覽器/設備支持哪些格式。
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - 用於跟踪和調查復雜 Web 應用程序的庫、工具和可視化工具集。

#### Chrome 特定工具/調試器

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools 擴展，可幫助您在瀏覽器中實時編輯著色器。
* [Spector.js 擴展](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - 輕鬆探索 WebGL 和 WebGL2 場景並排除故障。
* [Webgl Insight](https://github.com/3Dparallax/insight) - Chrome 擴展 WebGL 調試工具包，提供多種功能。

#### Firefox 特定工具/調試器

* [Canvas Debugger](https://hacks.mozilla.org/2014/03/introducing-the-canvas-debugger-in-firefox-developer-tools/) - 如何使用 Firefox 的開發者工具調試 WebGL 著色器的快速教程.
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - Firefox 所有調試器工具的官方列表。
* [Shader Editor](https://hacks.mozilla.org/2013/11/live-editing-webgl-shaders-with-firefox-developer-tools/) - 快速教程如何使用 Firefox 的開發者工具調試 WebGL 著色器.

###教程

> 在線 WebGL 教程（非視頻）

* [Directional Shadow Mapping](http://chinedufn.com/webgl-shadow-mapping-tutorial/) - 實時定向光影映射背後的概念。
* [入門教程](https://www.khronos.org/webgl/wiki/Tutorial) - Khronos 的教程如何啟動和運行 WebGL。
* [WebGL 入門](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL) - Mozilla 基金會 WebGL 入門指南。
* [Learn WebGL](https://www.tutorialspoint.com/webgl/index.htm) - Tutorials Point 系列文章，讓您熟悉 WebGL 術語。
* [學習 WebGL](http://learningwebgl.com/blog/?page_id=1217) - 來自_WebGL Up and Running_作者的教程。
* [使用 Blendmap 進行多紋理處理](http://chinedufn.com/webgl-multitexture-blend-map-tutorial/) - 如何使用 blendmap 對地形進行多紋理處理。
* [通過廣告牌的粒子效果](http://chinedufn.com/webgl-particle-effect-billboard-tutorial/) - 通過應用稱為廣告牌的技術創建粒子效果。
* [The Book of Shaders](https://thebookofshaders.com/) - 循序漸進地指導片段著色器抽象而復雜的世界。
* [WebGL Academy](http://www.webglacademy.com/) - 簡化的在線 IDE，具有自動縮進、HTML、Javascript、GLSL 和 Python 語法突出顯示。您可以運行您的代碼並下載您的項目。
* [WebGL 基礎知識](https://webglfundamentals.org/) - 包含代碼示例和現場演示的在線教程系列。
* [WebGL Workshop](http://webgl-workshop.com/) - 交互式研討會讓您開始使用 WebGL。

### 視頻

> WebGL 相關視頻

* [WebGL 編程簡介](https://www.youtube.com/watch?v=tgVLb6fOVVc&feature=youtu.be) - SIGGRAPH 大學對 WebGL 的 3 小時概述。
* [WebGL 教程 - YouTube](https://www.youtube.com/playlist?list=PLjcVFFANLS5zH_PeKC6I8p0Pt1hzph_rt) - 來自 YouTube 上 Indigo Code 的一系列講座式視頻教程。

## WebGL 2

> 有關即將推出的 WebGL 2 規範的信息
>
> 一般與 WebGL 有關的任何內容都可以在 [WebGL](#WebGL) 部分找到

### WebGL 2 子類別
* [文章](#articles-1)
* [參考文獻](#references-1)
* [教程](#tutorials-1)
* [視頻](#videos-1)

### 文章

> WebGL 2 文章和/或博客文章（非教程）

* [WebGL 2 新增功能](https://webgl2fundamentals.org/webgl/lessons/webgl2-whats-new.html) - 查看 WebGL 2 中添加的新功能。
* [WebGL 2.0 的新功能](https://blog.tojicode.com/2013/09/whats-coming-in-webgl-20.html) - 查看 WebGL 2 即將推出的功能。
* [WebGL 2 SIGGRAPH Asia 2015](https://docs.google.com/presentation/d/1Orx0GB0cQcYhHk​​YsaEcoo5js3c5-pv7ahPniIRIzzfg/edit#slide=id.p) - Zhenyao Mo、Ken Russell 在 SIGGRAPH Asia 2015 期間的演講。
* [WebGL 2 Lands in Firefox](https://hacks.mozilla.org/2017/01/webgl-2-lands-in-firefox/) - 從 Firefox 51 開始支持 WebGL 2 的信息。
* [WebGL 2 基礎知識](http://www.realtimerendering.com/blog/webgl-2-basics/) - 關於 WebGL 2 入門的博文。
* [WebGL 2 新功能](http://www.realtimerendering.com/blog/webgl-2-new-features/) - 關於 WebGL 2 的新功能和酷炫功能的博客文章。

＃＃＃ 參考

> WebGL 2 參考資料

* [WebGL 2 規格表（編輯草案）](https://www.khronos.org/registry/webgl/specs/latest/2.0/) - 關於 WebGL 2 的所有詳細信息。
* [WebGL 2 參考卡](https://www.khronos.org/files/webgl20-reference-guide.pdf) - 用於打印的 WebGL 2.0 API 快速參考卡。
* [WebGL 2 兼容圖表](https://caniuse.com/#feat=webgl2) - 顯示當前支持 WebGL 2 的瀏覽器的圖表

###教程
* [WebGL 2 Fundamentals](https://webgl2fundamentals.org/)- 包含代碼示例和現場演示的在線教程系列。
* [WebGL 2 Samples](http://webglsamples.org/WebGL2Samples/) - 許多不同的 WebGL 2 工作的重要來源以及非常好的評論。
* [WebGL 2 示例](https://github.com/tsherif/webgl2examples) - 在原始 WebGL 2 中實現的渲染算法。

### 視頻

> WebGL 相關視頻

* [Fun with WebGL 2.0](https://www.youtube.com/playlist?list=PLMinhigDWz6emRKVkVIEAaePW7vtIkaIF) - WebGL 2 入門視頻教程系列，仍在積極添加視頻。
* [WebGL 2.0 現已推出：您需要了解的內容](https://www.youtube.com/watch?v=Xf65duJ_QFs) - Khronos 網絡研討會 2017 年 4 月。
    * [幻燈片](https://www.khronos.org/assets/uploads/developers/library/2017-webgl-webinar/Khronos-Webinar-WebGL-20-is-here_What-you-need-to-know_Apr17.pdf )

## 網絡虛擬現實

> 關於新的和即將到來的 WebVR 生態系統的不同部分的信息
>
> 所有項目都與更多的開發人員相關，而較少涉及在哪裡可以找到 WebVR 內容作為娛樂

### WebVR 子類別

* [文章](#articles-2)
* [博客系列](#blog-series-1)
* [平台](#platforms)
* [參考文獻](#references-2)

### 文章

> WebVR 文章和/或博客文章（非教程）

### 博客系列

> 維護了以 WebVR 為重點的主題的博客系列

* [Mozilla VR 博客](https://blog.mozvr.com/) - 來自 Firefox 製造商的專注於 WebVR 的博客。

### 平台

> WebVR 設計的平台來體驗

* [JanusVR](https://janusvr.com/) - 網頁作為通過門戶互連的協作 3D 網絡空間。

＃＃＃ 參考

> WebVR 參考資料

* [瀏覽器支持](https://webvr.rocks/) - 顯示瀏覽器、耳機和操作系統的支持。
* [Mozilla VR](https://mixedreality.mozilla.org/) - Mozilla 的官方 WebVR 頁面。
* [VR 用戶體驗](https://www.uxofvr.com/) - 幫助在 WebVR 中創建良好用戶體驗的精選資源列表。
* [WebXR 設備 API](https://immersive-web.github.io/webxr/) - WebXR 的 W3C 草案 API。
* [WebVR 規範](https://w3c.github.io/webvr/) - 官方 W3C WebVR 規範（舊版）。
  * [如何閱讀 WebVR 規範](https://dassur.ma/things/reading-specs/)

## 庫

> [關於不同庫的更多詳細信息可以在庫目錄中找到。](https://github.com/sjfricke/awesome-webgl/tree/master/Libraries)

### 二維
* [p2.js](https://github.com/schteppe/p2.js) - 用 Ja​​vaScript 編寫的 2D 剛體物理引擎。
* [Phaser](https://phaser.io/) - 用於 Canvas 和 WebGL 的開源 HTML5 2D 遊戲框架，支持移動網絡瀏覽器。
* [PixiJS](http://www.pixijs.com/) - 基於 WebGL 的強大的 2D Javascript 渲染器。
* [Planck.js](https://github.com/shakiba/planck.js) - 用於跨平台 HTML5 遊戲開發的 2D 物理引擎。
* [Stage.js](https://github.com/shakiba/stage.js) - 用於跨平台 HTML5 遊戲開發的 2D 庫。

### 計算 (GPGPU)

＃＃＃＃ 計算機視覺
* [GammaCV](https://gammacv.com) - 用於瀏覽器的 WebGL 加速計算機視覺庫。

＃＃＃＃ 粒子
* [現象](https://github.com/vaneenige/phenomenon) - 非常小的低級 WebGL 庫，提供提供高性能體驗的要素。

### 地圖和可視化
* [Cesium](https://cesiumjs.org/) - 世界級 3D 地球儀和地圖的開源庫。
* [Deck.gl](http://deck.gl/) - 用於 React 的 WebGL 覆蓋套件，提供一組高性能數據可視化覆蓋。
* [Luma.gl](https://luma.gl/) - WebGL2 驅動的框架，用於 GPU 驅動的數據可視化和計算。
* [xeogl](http://xeogl.org/) - WebGL 上的數據驅動 3D 可視化引擎。

＃＃＃ 數學
* [glMatrix](http://glmatrix.net/) - 用於高性能 WebGL 應用程序的 Javascript 矩陣和向量庫。
* [Sylvester](http://sylvester.jcoglan.com/) - Sylvester 是一個用於 JavaScript 的矢量、矩陣和幾何庫。
* [TWGL](http://twgljs.org/) - 唯一目的是使 WebGL API 的使用不那麼冗長。

### 渲染
* [GLBoost](https://github.com/emadurandal/GLBoost) - 3D 圖形極客的渲染庫。
* [GrimoireGL](https://grimoire.gl/) - Web 工程師和 CG 工程師之間的橋樑。
* [Hilo3d](https://github.com/hiloteam/Hilo3d) - 用於 3D 遊戲的 WebGL 渲染引擎。

###物理
* [Ammo.js](https://github.com/kripken/ammo.js/) - 使用 Emscripten 將 Bullet 物理引擎直接移植到 JavaScript。
* [Cannon.js](http://schteppe.github.io/cannon.js/) - 用於網絡的輕量級和簡單的 3D 物理引擎。

### WebGL 2
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - 最小的 WebGL 2-only 渲染庫。

### 網絡虛擬現實
* [A-Frame](https://aframe.io/) - 用於構建虛擬現實體驗的 Web 框架。
  * [Awesome-AFrame](https://github.com/aframevr/awesome-aframe)
* [全息圖](https://hologram.cool/) - 桌面應用程序，讓您無需先前的編碼知識即可以交互方式創建 WebVR 和原型。
* [LÖVR](https://lovr.org/) - 使用 Lua 創建 VR 的簡單框架。
* [React 360](https://facebook.github.io/react-360/) - 使用 React 構建 VR 網站和交互式 360 度體驗。
* [Primrose](https://github.com/capnmidnight/Primrose/) - 在您的瀏覽器中快速構建 VR 應用程序原型。

＃＃＃ 其他
* [Babylon.js](https://www.babylonjs.com/) - 用於使用 HTML5、WebGL 和 Web Audio 構建 3D 遊戲的完整 JavaScript 框架。
* [Blend4Web](https://www.blend4web.com/en/) - 互聯網上交互式 3D 可視化工具。
* [ClayGL](http://claygl.xyz/) - 用於構建可擴展的 Web3D 應用程序的 WebGL 圖形庫。
* [CopperLicht](https://www.ambiera.com/copperlicht/index.html) - 用於創建遊戲和 3D 應用程序的 JavaScript 庫和 WebGL 3D 引擎。
* [GLGE](http://www.glge.org/) - 旨在簡化 WebGL 使用的 Javascript 庫。
* [Lightgl.js](https://github.com/evanw/lightgl.js) - 輕量級和明確的庫來幫助原型。
* [OSG.js](https://cedricpinson.github.io/osgjs-website/) - 基於 OpenSceneGraph 概念與 WebGL 交互的 WebGL 框架。
* [Pex-gl](http://vorg.github.io/pex/) - Plask/Node.js 和 WebGL 中用於計算思維的 JavaScript 庫。
* [PlayCanvas](https://playcanvas.com/) - 構建互動體驗的遊戲引擎平台。
* [Pocket.gl](https://github.com/gportelli/pocket.gl) - 完全可定制的 webgl 著色器沙箱，可嵌入到您的頁面中。
* [Regl](http://regl.party/) - 輕型聲明和無狀態庫，WebGL 的功能抽象。
* [Scene.js](http://scenejs.org/) - 用於高細節 3D 可視化的可擴展的基於 WebGL 的引擎。
* [Three.js](https://threejs.org/) - 旨在創建一個易於使用、輕量級的 3D 庫。
* [Turbulenz](https://github.com/turbulenz/turbulenz_engine) - 模塊化 3D 和 2D 遊戲框架，用於為瀏覽器、桌面和移動設備製作 HTML5 驅動的遊戲。
* [Verge3D](https://www.soft8soft.com/verge3d/) - 一個藝術家友好的工具包，用於創建 3D 網絡體驗。
* [Whitestorm.js](https://whs.io/) - 用於開發具有物理特性的 3D 網絡應用程序的框架。

＃＃ 社區
* [堆棧溢出](https://stackoverflow.com/questions/tagged/webgl)
* [Reddit](https://www.reddit.com/r/webgl/)
* [臉書](https://www.facebook.com/groups/webgl/about/)
* [推特](https://twitter.com/webgl)
* [Freenode IRC](http://webchat.freenode.net/?channels=webgl)
* [Khronos 論壇](https://community.khronos.org/c/other-standards/webgl)
* [谷歌群組](https://groups.google.com/forum/#!forum/webgl-dev-list)
* [谷歌加](https://plus.google.com/communities/114915309361980512257)
* [公共郵件列表](https://www.khronos.org/webgl/public-mailing-list/)
* [WebVR Slack](http://webvr-slack.herokuapp.com/)
* [WebVR 公共郵件列表](https://lists.w3.org/Archives/Public/public-webvr/)
* 活躍的聚會小組
  * [加利福尼亞州舊金山](https://www.meetup.com/WebGL-Developers-Meetup/)
  * [加利福尼亞州山景城](https://www.meetup.com/Silicon-Valley-HTML5-WebGL-Meetup/)
  * [英國倫敦](https://www.meetup.com/WebGL-Workshop-London/)
  * [紐約州紐約市](https://www.meetup.com/NYC-WebGL-Developers/)

## 相關列表

> 類似的很棒的列表

* [awesome](https://github.com/sindresorhus/awesome) - 精選的精選列表。
* [awesome-opengl](https://github.com/eug/awesome-opengl) - 很棒的 OpenGL 庫、調試器和資源的精選列表。靈感來自 awesome-... 東西。
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - 精選的 Vulkan 項目和生態系統列表。
* [gamedev](https://github.com/ellisonleao/magictools) - 關於遊戲開發的精彩列表。
* [glTF](https://github.com/KhronosGroup/glTF) - 專為網絡設計的運行時 3D 資產交付。
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - 圖形編程資源列表。

## 貢獻
有關詳細信息，請參閱 [CONTRIBUTING](https://github.com/sjfricke/awesome-webgl/blob/master/CONTRIBUTING.md)。

## 測試
感謝 [awesome_bot](https://github.com/dkhamsing/awesome_bot) 的 Travis CI 測試自動化！

＃＃ 執照

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允許的範圍內，[Spencer Fricke](https://github.com/sjfricke) 已放棄該作品的所有版權和相關或鄰接權。