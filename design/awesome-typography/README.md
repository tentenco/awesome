# Awesome Typography [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
關於數字排版的精選列表。

＃＃ 內容

- [規格](#specifications)
- [OpenType](#opentype)
- [JavaScript](#javascript)
- [Python](#python)
- [C](#c)
- [C++](#c-1)
- [C#](#c-2)
- [Java](#java)
- [紅寶石](#ruby)
- [去]（#去）
- [銹]（#銹）
- [PHP](#php)
- [Perl](#perl)
- [處理]（#處理）
- [Clojure](#clojure)
- [不明飛行物]（#ufo）
- [帶有 GUI 的工具](#tools-with-gui)
- [字體驗證器](#font-validator)
- [字體測試網站](#font-testing-websites)
- [雜項](#雜項)
- [字體](#fonts)
- [TrueType](#truetype)
- [書籍](#books)
- [視頻](#videos)


＃＃ 規格
- [微軟文檔](https://docs.microsoft.com/en-us/typography/opentype/spec/)
- [Apple 的文檔](https://developer.apple.com/fonts/TrueType-Reference-Manual/)
- [緊湊的字體格式
規範](https://adobe-type-tools.github.io/font-tech-notes/pdfs/5176.CFF.pdf) - 技術說明 #5176。
- [the-cff-table](https://github.com/Pomax/the-cff-table) - 關於 CFF 的 Adob​​e 技術說明 5176 和 5177 的 Markdown 轉換。
- [Adobe 的文檔](https://www.adobe.com/devnet/font.html)

## 開放式
- [OpenType：讓我們了解現代字體的實際工作原理](https://pomax.github.io/#gh-weblog-1449777175633)
- [The OpenType Cookbook](http://opentypecookbook.com) - 為字體設計師介紹 OpenType 功能。[（來源）]（https://github.com/typesupply/opentype-feature-intro）。
- [一點字體生成](https://pomax.github.io/CFF-glyphlet-fonts/) - OpenType 的簡要介紹。

## JavaScript
- [OpenType.js](https://github.com/nodebox/opentype.js) - 讀寫 OpenType 字體。
- [opentype-layout](https://github.com/Jam3/opentype-layout) - OpenType.js 的實驗性自動換行和佈局。
- [canvas-text-opentypejs-shim](https://github.com/shyiko/canvas-text-opentypejs-shim) - <canvas> 的一致文本渲染（由 OpenType.js 支持）。
- [CharacterMap](https://github.com/bluejamesbond/CharacterMap/) - 在線字符映射/字形/圖標/字體查看器。
- [字體](https://www.npmjs.com/package/font) - 從緩衝區解析 OTF/TTF 文件格式目錄以獲取元數據。
- [fontkit](https://github.com/foliojs/fontkit) - Node 和瀏覽器的高級字體引擎。
- [Minimal-font-generator](https://github.com/Pomax/Minimal-font-generator) - 字體的 Hello world。
- [simple-cff-builder](https://github.com/Pomax/simple-cff-builder) - 用於測試具有不同 Type2 字符字符串的字體的簡單 CFF 構建器。
- [ttf2woff2](https://github.com/nfroidure/ttf2woff2/) - 將 TTF 文件轉換為 WOFF2。
- [ttf2woff](https://github.com/fontello/ttf2woff) - 將 TTF 轉換為 WOFF，用於 Node.js。
- [sfnt2woff](https://github.com/laoshu133/sfnt2woff) - 將TTF或OTF轉換為WOFF，支持Node.js和瀏覽器。
- [ttf2eot](https://github.com/fontello/ttf2eot) - 將 TTF 轉換為 Node.js 的 EOT。
- [cubic2quad](https://github.com/fontello/cubic2quad) - 用二次曲線近似三次貝塞爾曲線。
- [SVG 字體創建者](https://github.com/fontello/svg-font-create) - 從單獨的圖像創建 SVG 字體。
- [node-sfnt](https://github.com/be5invis/node-sfnt) - Node.js 的 SFNT 解析器和生成器。
- [node-unicode-data](https://github.com/mathiasbynens/node-unicode-data) - JavaScript 兼容的 Unicode 數據生成器。
- [fontwr](https://github.com/raphaklaus/fontwr) - Web 項目的字體管理器。
- [開放式遊樂場](https://github.com/magalhini/open-type-playground) - 使用 CSS 進行開放式實驗的遊樂場。
- [ChromaCheck](https://github.com/RoelN/ChromaCheck) - 對瀏覽器中顏色字體支持的功能測試。
- [Font Face Observer](https://github.com/bramstein/fontfaceobserver) - 字體加載事件，簡單、小巧、高效[fontfaceobserver.com](https://fontfaceobserver.com)。
- [Web Font Loader](https://github.com/typekit/webfontloader) - Web Font Loader 在通過@font-face 使用鏈接字體時為您提供了額外的控制。
- [localFont](https://github.com/jaicab/localFont) - 在幾秒鐘內實現 localStorage 網絡字體緩存。
- [Fontello](https://github.com/fontello/fontello) - 此工具可讓您為自己的項目組合圖標網絡字體。
- [GitHub 字體預覽](https://github.com/Mottie/GitHub-userscripts/wiki/GitHub-font-preview) - 使用 OpenType.js 在 GitHub 上添加字體和字形預覽。
- [unidata](https://github.com/chbrown/unidata) - JavaScript 的 Unicode 字符數據庫。
- [UCD](https://github.com/ynakajima/ucd) - JavaScript 的 Unicode 字符數據庫。
- [字符集檢查器](https://github.com/graphicore/charset-inspector) - JavaScript 的 Unicode 字符數據庫。
- [OpenType](https://github.com/bramstein/opentype) - JavaScript 中的 OpenType 字體解析器。
- [opentype-geometry](https://github.com/nascherman/opentype-geometry) - 將文本從 OpenType 字體轉換為 three.js 3D。
- [Plumin.js](https://github.com/byte-foundry/plumin.js) - 在瀏覽器中創建和操作字體。
- [Typr.js](https://github.com/photopea/Typr.js) - 在 JavaScript 中處理字體。
- [fonteditor-core](https://github.com/kekee000/fonteditor-core) - 在 JavaScript 中讀取、寫入、轉換字體。
- [fontmin](https://github.com/ecomfe/fontmin) - 無縫縮小字體。
- [fontfacegen](https://github.com/agentk/fontfacegen) - 瀏覽器字體生成器，用於從 TTF 或 OTF 創建瀏覽器可用的字體。
- [NType](https://github.com/kevinzweerink/ntype) - 4D 型擠出機。
- [node-emoji](https://github.com/omnidan/node-emoji) - 😏 Node.js 項目的簡單表情符號支持。
- [custom-fonts-in-emails](https://github.com/ladjs/custom-fonts-in-emails) - 在電子郵件中使用自定義字體的極其簡單的方法，無需使用藝術軟件。
- [谷歌字體信息](https://github.com/thisarmy/fontsinfo) - 從谷歌字體檔案中提取信息。
- [Hyphenopoly.js](https://github.com/mnater/Hyphenopoly) - 用於客戶端連字符的 JavaScript polyfill。
- [Hyphenator.js](https://github.com/mnater/Hyphenator) - 實現 HTML 文檔的客戶端斷字的 JavaScript。
- [Hypher](https://github.com/bramstein/hypher) - 快速而小型的 JavaScript 斷字引擎。
- [Typeset.js](https://github.com/davidmerfield/Typeset) - 用於網頁排版的 HTML 預處理器（懸掛標點符號、軟連字符插入、光學邊距突出、小型大寫字母轉換和標點符號替換）。
- [Typeset](https://github.com/bramstein/typeset) - JavaScript 中的 TeX 換行算法。
- [otfcc-cubic2quad](https://github.com/caryll/otfcc-cubic2quad) - 使用 otfcc 無損地將 CFF OTF 轉換為 TTF。
- [caryll / shapeops](https://github.com/caryll/shapeops) - 布爾運算和曲線的重疊去除。
- [OpenType-SVG Workshop](https://github.com/rocallahan/svg-opentype-workshop) - OpenType-SVG Workshop Web 應用程序。
- [A-binary-parser-generator](https://github.com/Pomax/A-binary-parser-generator) - 該項目旨在創建一個工具，可以將規範文件轉換為二進制數據的解析器骨架文件，例如 OpenType 字體、PNG 圖像等。
- [font-spider](https://github.com/aui/font-spider) - 智能網絡字體壓縮和格式轉換工具。
- [Brotli.js](https://github.com/foliojs/brotli.js) Brotli 壓縮算法的 JavaScript 端口，在 WOFF2 中使用。
- [ideohint](https://github.com/caryll/ideohint) - 優化了象形文字的提示。
- [subfont](https://github.com/Munter/subfont) - 將 Google 字體子集使用的字形注入頁面的命令行工具。
- [webfont](https://github.com/itgalaxy/webfont) - 很棒的 webfont、WOFF2、WOFF、EOT、TTF 和 SVG 生成器。
- [grapheme-splitter](https://github.com/orling/grapheme-splitter) - JavaScipt 庫，可將字符串分解為單獨的用戶感知字符。
- [unicode-properties](https://github.com/foliojs/unicode-properties) - 提供對 unicode 字符屬性的快速訪問。
- [unicode-tr51-emoji](https://github.com/cameronhunter/unicode-tr51-emoji) - 從 Unicode 技術報告 #51 v1.0 – v5.0 中提取的表情符號數據。
- [fontblast](https://github.com/eugene1g/font-blast) - 給我一個圖標字體，我將為其中的所有圖標創建單獨的 SVG/PNG 文件。
- [fontplop](https://github.com/matthewgonzalez/fontplop) - 快速、簡單、免費的開源 Webfont 轉換器。
- [svgfont2svgicons](https://github.com/nfroidure/svgfont2svgicons) - 從 SVG 字體中提取 SVG 圖標。
- [glyphhanger](https://github.com/filamentgroup/glyphhanger) - 你的網絡字體實用工具帶。它顯示了網站上使用的 unicode-ranges（可選地用於字體系列或每個字體系列）。它還可以子集網絡字體。
- [Punycode.js](https://github.com/bestiejs/punycode.js) - 完全符合 RFC 3492 和 RFC 5891 的強大的 Punycode 轉換器。
- [code-point-at](https://github.com/sindresorhus/code-point-at) - ES2015 String#codePointAt() ponyfill。
- [Typefont](https://github.com/vasile-peste/Typefont) - 第一個檢測圖像中文本字體的開源庫。
- [node-fonttools](https://github.com/dfrankland/node-fonttools) - 原生綁定到 fonttools 以反編譯和編譯字體。
- [font-toolkit](https://github.com/hsiaosiyuan0/fonts) - 在 TypeScript 中處理字體文件。
- [variableFont.js](https://github.com/Monotype/variableFont.js) - 通過 OpenType.js 處理可變字體

＃＃ Python
- [fontTools](https://github.com/fonttools/fonttools) - 用於操作字體的庫，用 Python 編寫。
- [fontmake](https://github.com/googlei18n/fontmake) - 將字體從源代碼（UFO、Glyphs）編譯為二進制（OpenType、TrueType）。
- [FontReport](https://github.com/googlei18n/fontreport) - 創建包含字形圖像和字體信息的 PDF 文件的工具。
- [fontdiff](https://github.com/googlei18n/fontdiff) - 用於查找兩個字體版本之間視覺差異的工具。
- [kern-dump](https://github.com/adobe-type-tools/kern-dump) - 用於處理和分析字距調整信息的腳本 (ATypI 2013)。
- [cu2qu](https://github.com/googlei18n/cu2qu) - 三次到二次貝塞爾曲線的轉換。
- [Font Bakery](https://github.com/googlefonts/fontbakery) - 準備包含在 github.com/google/fonts 中的字體系列的工具。
- [glyphNameFormatter](https://github.com/LettError/glyphNameFormatter) - 從 unicode 名稱生成字形名稱列表。
- [woffTools](https://github.com/typesupply/woffTools) - 用於處理 WOFF 文件的庫。
- [pyftfeatfreeze](https://github.com/twardoch/fonttools-utils/tree/master/pyftfeatfreeze) - 使用 pyftfeatfreeze，您可以將一些 OpenType 功能“凍結”成字體。
- [RoboFab](https://github.com/robofab-developers/robofab) - 包含處理通常與字體和類型設計相關的數據的對象的庫。
- [pyfontaine](https://github.com/davelab6/pyfontaine) - 檢查字體文件是否支持語言/字符集的 Python 工具。
- [Glyph Nanny](https://github.com/typesupply/glyph-nanny) - 實時報告您的字形中潛在的繪圖問題。
- [Kernagic](https://github.com/hodefoting/kernagic) - 半自動字體間距工具。
- [Huerta Tipográfica Letterspacer](https://github.com/huertatipografica/HTLetterspacer) - HT Letterspacer 是一個字體間距工具。
- [OpenType-SVG 工具](https://github.com/adobe-type-tools/opentype-svg) - 用於製作 OpenType-SVG 字體的工具和示例文件。
- [boxDrawing.py](https://github.com/adobe-type-tools/box-drawing) - 基於參數繪製所有方框圖字符和塊元素的Python腳本。
- [scfbuild](https://github.com/eosrei/scfbuild/) - 從一組 SVG 源文件創建 OpenType-SVG 彩色字體。
- [color-emoji](https://github.com/googlei18n/color-emoji) - 使用 Google 顏色字體格式 (CBDT/CBLC) 構建顏色字體的工具。
- [monospacifier.py](https://github.com/cpitclaudel/monospacifier) - 將可變間距字體轉換為等寬字體（對 unicode 和縮進友好的編程很有用）。
- [edf825/SVG-OpenType-Utils](https://github.com/edf825/SVG-OpenType-Utils) - OpenType Utils 中的 SVG (!Old: 2013)。
- [圖標字體到 PNG](https://github.com/Pythonity/icon-font-to-png) - Python 腳本（和庫），用於將圖標字體（例如 Font Awesome、Octicons）中的圖標導出為 PNG 圖像。
- [合成器](https://github.com/typesupply/compositor) - 基本的 OpenType GSUB 和 GPOS 佈局引擎。
- [UFO Extractor](https://github.com/typesupply/extractor) - 用於從字體二進製文件中提取數據到 UFO 對像中的工具。
- [Noto 工具](https://github.com/googlei18n/nototools) - Noto 字體支持工具和腳本。
- [compreffor](https://github.com/googlei18n/compreffor) - FontTools 的 CFF 表子程序。
- [font-line](https://github.com/source-foundry/font-line) - OpenType 垂直度量報告和字體行間距調整工具。
- [Flat](https://xxyxyz.org/flat/) - 用於創建和操作數字藝術形式的圖書館。
- [PageBot](https://github.com/typenetwork/pagebot) - 腳本頁面佈局程序，作為 Drawbot 內部的應用程序，生成支持高質量字體的高質量印刷文檔。

＃＃ C
- [otfcc](https://github.com/caryll/otfcc) - 解析和寫入 SFNT 結構。
- [AFDKO](https://github.com/adobe-type-tools/afdko) - 適用於 OpenType 的 Adob​​e 字體開發工具包。請參閱 [AFDKO 概述](https://www.adobe.com/devnet/opentype/afdko/topic_overview.html)。
- [stb_truetype](https://github.com/nothings/stb/) - 解析、解碼和光柵化 TrueType 字體的字符。單個頭文件。
- [FreeType](https://www.freetype.org) - 用於渲染字體的免費軟件庫。
- [Raqm](https://github.com/HOST-Oman/libraqm) - 用於復雜文本佈局的庫。
- [SheenFigure](https://github.com/mta452/SheenFigure) - OpenType 規範的高級排版表的實現。
- [SheenBidi](https://github.com/mta452/SheenBidi) - SheenBidi 是世界上最複雜的最新 unicode 雙向算法的實現。
- [freetype-gl](https://github.com/rougier/freetype-gl) - 使用一個頂點緩衝區、一個紋理和 FreeType 的 OpenGL 文本。
- [WOFF](https://github.com/samboy/WOFF) - WOFF 轉換參考代碼。

## C++
- [font to svg](https://github.com/donbright/font_to_svg) - 將字體文件中的字符渲染到 SVG 路徑中。
- [LCDF Typetools](https://github.com/kohler/lcdf-typetools) - 用於操作 OpenType、PostScript Type 1 和多個主字體的實用程序。
- [HarfBuzz](https://github.com/googlei18n/harfbuzz) - HarfBuzz OpenType 文本整形引擎。
- [FontView](https://github.com/googlei18n/fontview) - 使用免費/libre/開源文本渲染堆棧顯示字體的演示應用程序：FreeType、HarfBuzz 和 Raqm。
- [文本渲染測試](https://github.com/unicode-org/text-rendering-tests) - 文本渲染測試套件。
- [FTGLES](https://github.com/cdave1/ftgles) - 適用於 iOS 設備（iPad 和 iPhone）上 OpenGL ES 的 TrueType 字體渲染庫。
- [TTFPatch](https://github.com/rmuch/ttfpatch) - Wolfram Esser 的 TTFPATCH 鏡像，經過修改以支持符合較新 OTF 規範的字體，專為現代版本的 Windows 構建。
- [stb-truetype-opengl-examples](https://github.com/0xc0dec/demos) - 使用 stb_truetype 庫和 OpenGL 3+ 在 C++11 中渲染 TrueType 字體的示例。
- [WOFF2](https://github.com/google/woff2)

＃＃ C＃
- [NRasterizer](https://github.com/vidstige/NRasterizer) - 純粹用 c# 編寫的簡單乾淨的 TrueType 字體渲染器。
- [Typography](https://github.com/LayoutFarm/Typography) - C# 字體閱讀器 (TrueType / OpenType / OpenFont)，字形佈局和渲染。
- [SixLabors.Fonts](https://github.com/SixLabors/Fonts) - 字體加載和繪圖庫。
- [SharpFont](https://github.com/MikePopoloski/SharpFont) - 純託管 TTF / OTF 閱讀器和渲染器。

## 爪哇
- [sfntly](https://github.com/googlei18n/sfntly) - 使用、編輯和創建基於 SFNT 字體的庫。
- [Emoji-Tools](https://github.com/EmojiTools/Emoji-Tools) - 多種有用的工具可幫助 Android 和 iOS/OSX 開發人員創建和修改 Emoji 字體文件。
- [Tehreer-Android](https://github.com/mta452/Tehreer-Android) - 完全控製文本相關技術的庫，例如雙向算法、開放式整形引擎、文本排版和文本渲染。

## 紅寶石
- [emoji-extractor](https://github.com/tmm1/emoji-extractor) - 從 Apple Color Emoji.ttf 中提取高分辨率表情符號 png。
- [字體](https://github.com/alyssais/font) - 命令行字體管理器。

＃＃ 去
- [字體](https://github.com/ConradIrwin/font) - 在 Golang 中解析 OpenType 字體。
- [freetype](https://github.com/golang/freetype) - Go 中的 Freetype 字體光柵化器。

## 銹
- [font-rs](https://github.com/google/font-rs) - 世界上最快的字體渲染器。
- [font-kit](https://github.com/servo/font-kit) - 一個跨平台的字體加載庫。
- [RustType](https://github.com/redox-os/rusttype) - 純 Rust 替代庫，如 FreeType。
- [Pathfinder](https://github.com/pcwalton/pathfinder) - 用於 OpenType 字體的快速、實用的 GPU 光柵化器。
- [字體工具箱](https://github.com/bodoni/font)
- [OpenType 字體解析器](https://github.com/bodoni/opentype)
- [PostScript 字體解析器](https://github.com/bodoni/postscript)
- [TrueType 字體解析器](https://github.com/bodoni/truetype)
- [freetype-rs](https://github.com/PistonDevelopers/freetype-rs) - FreeType 庫的 Rust 綁定。
- [freetype-sys](https://github.com/PistonDevelopers/freetype-sys) - FreeType 字體庫的低級綁定。
- [truetype](https://github.com/PistonDevelopers/truetype) - 用於從 TrueType 格式讀取字體的庫。

## PHP
- [PHP 字體庫](https://github.com/PhenX/php-font-lib) - 用於讀取、解析、導出和製作不同類型字體文件子集的庫。
- [JoliTypo](https://github.com/jolicode/JoliTypo) - 用於網絡的微排版固定器。
- [PHP SmartyPants](https://github.com/michelf/php-smartypants) - SmartyPants 是一個免費的網頁排版美化工具，適用於網絡作家。它可以輕鬆地將純 ASCII 標點字符轉換為“智能”印刷標點 HTML 實體。

## Perl
- [Font::TTFMetrics](https://metacpan.org/release/Font-TTFMetrics) - 快速且易於使用的真字體 (TTF) 文件解析器。

＃＃ 加工
- [Fontastic](https://github.com/andreaskoller/Fontastic) - 用於創建 TrueType 字體文件的處理庫。

## Clojure
- [opentype.clj](https://github.com/ivarref/opentype.clj) - 基於 OpenType.js 的 Clojure 簡單 API。在 JVM 上運行。

## 不明飛行物
[統一字體對象.org](http://unifiedfontobject.org)
- [ufo-spec](https://github.com/unified-font-object/ufo-spec) - 官方統一字體對象規范源文件。
- [ufoLib](https://github.com/unified-font-object/ufoLib) - 低級 UFO 讀寫器。
- [ufoNormalizer](https://github.com/unified-font-object/ufoNormalizer) - 標準化 UFO 內的 XML 和其他數據的工具。
- [ufo2ft](https://github.com/googlei18n/ufo2ft) - UFO 到 FontTools。
- [ufoJS](https://github.com/graphicore/ufoJS) - 統一字體對象的 JavaScript API。


## 帶有 GUI 的工具

### 非免費
- [Fontself](https://www.fontself.com) Adob​​e Illustrator 和 Photoshop 擴展，用於通過拖放創建矢量和位圖字體。讓字體變得簡單！
- [Robofont](http://doc.robofont.com) - 基於 UFO（僅限 Mac）。
- [字形](https://glyphsapp.com) - 字體編輯器（僅限 Mac）。
- [Prototypo](https://github.com/byte-foundry/prototypo) - 具有參數化方法的基於 Web 的字體生成器。
- [FontLab Studio](https://www.fontlab.com/font-editor/fontlab-studio/) - 字體專業人士的字體編輯器。適用於 Mac 和 Windows 的版本 5。
- [DTL OTMaster](https://www.fontmaster.nl) - 用於審查、編輯和更改具有 snft 文件結構的字體表和輪廓的高度複雜的應用程序，因為有 CFF 和 TTF 風格的 OpenType 字體、TrueType 字體和TrueType 集合字體。
- [010 Editor](http://www.sweetscape.com/010editor/) - 使用二進制模板技術的專業文本和十六進制編輯。[OpenType 模板](http://pikensoft.com/programs/OpenTypeTemplate.bt)。
- [Synalyze It!](https://www.synalysis.net) - 逆向工程和二進製文件分析變得容易。[OpenType 模板](https://www.synalysis.net/Grammars/opentype.grammar)。
- [TransType 4](https://www.fontlab.com/font-converter/transtype/) - 通用字體轉換器。

＃＃＃ 自由
- [FontForge](https://github.com/fontforge/fontforge) - 適用於 Windows、Mac OS X 和 GNU+Linux 的免費（自由）字體編輯器。
- [TruFont](https://github.com/trufont/trufont) - UFO3 字體編輯器。À l'ancienne。
- [Metapolator](https://github.com/metapolator) - 用於創建 UFO 和 Metafont 字體的基於 Web 的 GUI。
- [Birdfont](https://github.com/johanmattssonm/birdfont) - 字體編輯器，可以生成 TTF、EOT、SVG 和 BF 格式的字體。
- [Glyphr Studio](https://twitter.com/glyphrstudio) - 基於網絡的免費字體編輯器，專注於字體設計愛好者。
- [DTL OTMaster Light](https://www.fontmaster.nl/#light) - 在 dtl OTMaster 的 Light 版本中，只有文件的保存被禁用。檢查字體和導出 OpenType 佈局功能文件、be 和 ik 格式以及字符佈局 (.cha) 文件是可能的。
- [fonteditor](https://github.com/ecomfe/fonteditor) - 基於Web的TTF字體編輯器，位於[fontstore.baidu.com](http://fontstore.baidu.com/static/editor/index) -en.html)。
- [FontArk](https://fontark.net/farkwp/) FontArk 是一個創新的基於瀏覽器的字體編輯器，字體創建器（BETA），具有最通用的實時多字形編輯系統。
- [TTFEdit](https://sourceforge.net/projects/ttfedit/) - TrueType 字體編輯器。允許編輯基於矢量的字形。
- [OpenType-SVG-Font-Editor](https://github.com/Microsoft/OpenType-SVG-Font-Editor)。
- [SdfFontDesigner](https://github.com/aiekick/SdfFontDesigner) - 位圖字體生成器，基於 ttf & otf，使用 glsl 中的自定義著色器渲染

## 字體驗證器
- [Font Validator](https://github.com/HinTak/Font-Validator) - Font Validator 是一個在發布前測試字體的工具。請參閱 [Mac 安裝帖子](http://typedrawers.com/discussion/comment/16090/#Comment_16090)。
- [OpenType Sanitiser](https://github.com/khaledhosny/ots) - OpenType Sanitiser (OTS) 解析和序列化 OpenType 文件（OTF、TTF）和 WOFF 和 WOFF2 字體文件，並在運行過程中對其進行驗證和清理.
- [WOFF 驗證器](http://validator.fontbureau.com) - 在線 WOFF 驗證器。

## 字體測試網站
- [Axis-Praxis](https://www.axis-praxis.org/) - Axis-Praxis 是一個在現代瀏覽器中使用 OpenType 可變字體的網站。
- [Bulletproof Font Tester](https://bulletproof.italic.space/) - 使用字體設計師為字體設計師開發的校對工具測試本地或遠程字體。查看字距調整、OpenType 功能和語言覆蓋率。探索可變字體的變化軸並為其設置動畫。
- [Cyreal.org 字體測試頁面](http://www.cyreal.org/Font-Testing-Page/) - 字體測試頁面是一個主要用於字體設計人員“拖放”并快速測試其字體的工具字體進入瀏覽器（Impallari 測試頁面的活動分支）。
- [Font Gauntlet](https://fontgauntlet.com) - Dinamo Font Gauntlet 是一種用於校對、生成和動畫字體的工具。
- [Wakamai Fondue](https://wakamaifondue.com/) - 回答“我的字體能做什麼？”問題的工具
- [TypeNetwork TypeTools](https://typetools.typenetwork.com/) - 用於以各種方式試驗可變字體的佈局工具。

＃＃ 各種各樣的
- [TypeDrawers](http://typedrawers.com) - 字體設計、刻字和排版領域的專業人士和愛好者的討論論壇。
- [Font Squirrel Webfont Generator](https://www.fontsquirrel.com/tools/webfont-generator) - 上傳OTF或TTF字體，接收webfonts。
- [Web 類型的狀態](https://github.com/bramstein/stateofwebtype) - “我可以使用”排版。
- [UseModify](https://usemodify.com) - 開源字體。
- [ofont](https://github.com/raphaelbastide/ofont) - 字體集合的 Web 界面（由 usemodify.com 使用）
- [Git for Type Designers](https://github.com/frankrolf/git-for-type-designers)
- [designwithfontforge.com](https://github.com/fontforge/designwithfontforge.com) - 關於如何使用 FontForge 設計新字體的書籍。請參閱 [designwithfontforge.com](http://designwithfontforge.com)。
- [FontTesting Page](https://github.com/impallari/Font-Testing-Page) - 用於測試字體的網頁。
- [CSS Utility OpenType](https://github.com/kennethormandy/utility-opentype) - 用於高級排版功能的簡單 CSS 實用程序類。在 [這裡](http://utility-opentype.kennethormandy.com) 看到它。
- [Alfred 特殊字符](https://github.com/typefacts/alfred-special-characters) - Alfred 3 的 Typefacts 特殊字符工作流程。
- [Typomanie.fr 資源](http://typomanie.fr/ressources/)
- [繪製好的路徑教程](https://glyphsapp.com/tutorials/drawing-good-paths) - 畫得不好的輪廓會導致頭痛。您的信件可能看起來很混亂或根本沒有出現。如果您牢記一些基本規則，就可以避免這些困難。
- [深入了解 OpenType 功能](http://blog.ricardofilipe.com/post/deep-into-opentype-features) - 什麼是 OpenType 功能？
- [排版術語的 AZ](https://www.fontsmith.com/blog/2016/06/29/the-az-of-typographic-terms) - 圖像中的排版術語。
- [Emoj](https://github.com/sindresorhus/emoj) - 從命令行中的文本中查找相關的表情符號😮 ✨ 🙌 🐴 💥 🙈。
- [Emoji Wrap Monthly Newsletter](http://emojiwrap.com) - 表情符號和 Unicode 世界正在發生的事情的簡短摘要。
- [加密拼圖](https://github.com/2d4d/crypto_puzzles) - 加密和隱寫術作為拼圖或腦筋急轉彎的功能。[在線演示](http://rupp.de/crypto_puzzles/crypto_puzzles_web.py)。
- [FDBP](http://silnrsi.github.io/FDBP/) - 字體開發最佳實踐文檔。
- [UnicodeChecker](http://earthlingsoft.net/UnicodeChecker/) - 探索和轉換 Unicode。
- [unicodes](https://github.com/jessetane/unicodes) - 瀏覽所有的 unicodes。
- [Method of Action](http://method.ac) - Method of Action 是幫助您學習設計的工具、遊戲和文章的集合。
- [程序員的編碼和字符集](http://kunststube.net/encoding/) - 每個程序員絕對肯定需要了解編碼和字符集以處理文本。
- [Kernall](https://github.com/n8willis/kernall) - 字距和字母間距研究。
- [Type Facet](https://github.com/charlesmchen/typefacet) - 用於處理字體的 Python 腳本集合。請參閱 [TypeFacet Autokern](http://charlesmchen.github.io/typefacet/topics/autokern/index.html)
- [OpenType 功能參考](https://github.com/opensource-opentype/features) - 關於高級字體功能的文檔和其他信息
- [Typography Supply](http://typography.supply) 排版工具清單。
- [OpenType Feature Bundle](https://github.com/brew/opentype-feature-bundle) - TextMate/Sublime Text 中 OpenType 功能開發的語法高亮和片段。
- [類型工具點文件](https://github.com/benkiel/dotfiles) - 設置類型工具。
- [AGL & AGLFN](https://github.com/adobe-type-tools/agl-aglfn) - AGL / AGLFN (Adobe Glyph List / For New Fonts) 僅提供從字形名稱到 Unicode 標量值的映射。[參見規範](https://github.com/adobe-type-tools/agl-specification)。
- [OpenType Glyph 替換的可怕秘密](http://ansuz.sooke.bc.ca/entry/131)
- [I Can Variable Font](https://github.com/scribbletone/i-can-variable-font) - 製作可變字體的技巧。
- [你、我和表情符號：字符集、編碼和表情符號](https://www.smashingmagazine.com/2016/11/character-sets-encoding-emoji/)
- [Emoji Rolodex](https://www.emojicopy.com/#emojicodes) - 與表情符號相關的網站、插件和應用程序的資源豐富的鏈接。
- [OpenType_Table_Source](https://github.com/Monotype/OpenType_Table_Source) - Monotype 的 OpenType 佈局源文件格式的文檔。
- [jenskutilek/TypoLabs2016](https://github.com/jenskutilek/TypoLabs2016) - Jens Kutilek 的 TypoLabs 研討會的代碼示例。
- [W3C - 網絡上的字體](https://www.w3.org/Fonts/) - 網絡上的字體。
- [W3C - WebFonts 工作組](https://www.w3.org/Fonts/WG/)
- [Twitter 表情符號 (Twemoji)](https://github.com/twitter/twemoji) - Twemoji 庫提供對 +2k 表情符號的支持，包括膚色和性別修飾符。
- [EmojiOne](https://github.com/emojione/emojione) - EmojiOne™ 是開放的表情符號標準。
- [沒有@font-face 語法永遠不會是防彈的，也不應該是](https://calendar.perfplanet.com/2016/no-font-face-bulletproof-syntax/)
- [排版是不可能的](https://medium.engineering/typography-is-impossible-5872b0c7f891) - 實用指南，說明為什麼排版永遠不會完全符合您的要求。
- [JavaScript 存在 Unicode 問題](https://mathiasbynens.be/notes/javascript-unicode) - JavaScript 處理 Unicode 的方式……至少可以說令人驚訝。
- [homebrew-webfonttools](https://github.com/bramstein/homebrew-webfonttools) - 字體工具的 Homebrew 公式。
- [Font Falsehoods](https://github.com/RoelN/Font-Falsehoods) - 程序員相信字體的謊言。
- [Letterpress Digest](http://letterpressdigest.com) - 關於凸版印刷的新播客。
- [fontspeed](https://www.fontspeed.io) - @zachleat 關於字體加載的通訊。
- [Font-Awesome-SVG-PNG](https://github.com/encharm/Font-Awesome-SVG-PNG) - Font Awesome 拆分為不同大小的單個 SVG 和 PNG 文件以及基於 Node.js 的生成器。

## 字體
- [吉爾伯特字體](https://github.com/Fontself/TypeWithPride) - 以彩虹旗的創造者吉爾伯特貝克命名的 OpenType-SVG 字體。
- [Nanofont](https://github.com/bramstein/nanofont) - 用於測試字體格式支持的 Nano 字體（TrueType、WOFF、WOFF2）。
- [FiraSystemFontReplacement](https://github.com/jenskutilek/FiraSystemFontReplacement) - 修改版本的 Fira Sans 字體以替換 Mac OS X 10.10 和 10.11 上的默認系統字體。
- [SansBullshitSans 字體](https://github.com/RoelN/SansBullshitSans) - 每個流行語都將替換為 Comic Sans 風格的審查欄。
- [Blackout](https://github.com/RoelN/Blackout) - 一種字體可以將它們全部塗黑。
- [Compyx](https://github.com/RoelN/Compyx) - 8 位多色 OpenType 字體。
- [LapisLegit](https://github.com/RoelN/LapisLegit) - OpenType-SVG 測試字體。
- [AIFont](https://github.com/Denly/AIFont) - 生成人工智能的拳頭中文字體。
- [Noto Fonts](https://github.com/googlei18n/noto-fonts) - Noto 的目標是為所有語言提供優美的閱讀體驗。
- [Noto Emoji](https://github.com/googlei18n/noto-emoji) - 彩色和黑白 Noto 表情符號字體，以及使用它們的工具。
- [EmojiOne COLR/CPAL](https://github.com/mozilla/twemoji-colr) - COLR/CPAL 分層格式的 EmojiOne 字體。
- [EmojiOne OpenType-SVG](https://github.com/eosrei/emojione-color-font) - 使用具有多樣性和國家標誌的 EmojiOne Unicode 9.0 表情符號的彩色表情符號 OpenType-SVG 字體。
- [Twitter 彩色表情符號字體](https://github.com/eosrei/twemoji-color-font) - 彩色表情符號 OpenType-SVG 字體使用 Twitter Unicode 9.0 表情符號，具有多樣性和國家標誌。
- [Bixa Color](https://bixacolor.com) - 構建 Bixa Color，一種用於網絡的顏色字體 [pixelambacht.nl/2016/building-bixa-color/](https://pixelambacht.nl/2016/建築-bixa-color/)。
- [fontwr-fonts](https://github.com/raphaklaus/fontwr-fonts) - fontwr 的字體庫。
- [Bungee](https://github.com/djrrb/Bungee/) - 用於垂直和水平設置的彩色標牌字體。
- [Aerial Bold](http://type.aerial-bold.com/tw/) Aerial Bold 是地球上第一張地圖和字體。
- [wavefont](https://github.com/audio-lab/wavefont) 用於渲染數據的字體：波形、頻譜、圖表、條形等。
- [Adobe 可變字體原型](https://github.com/adobe-fonts/adobe-variable-font-prototype) - OpenType-CFF2 和 TrueType 格式的可變字體示例。
- [Microsoft 開源字體](https://github.com/Microsoft/fonts) - 共享 Microsoft 開源字體的中心位置。
- [Reinebow](https://github.com/xerographer/reinebow-color-font) - OpenType-SVG 彩色字體。
- [Freizer](https://github.com/xerographer/freizer-color-font) - OpenType-SVG 彩色字體。
- [Multicoloure](https://github.com/xerographer/multicoloure-font) - 基於 Multicolore 矢量字體的 OpenType-SVG 彩色字體。
- [null-ttf](https://github.com/grzegorzrolek/null-ttf) - 此字體為空。它是在 OS X 上仍然有效的最小的 TrueType 二進製文件，並且它的大部分字節都被清除了。
- [Monotype 可變字體演示](https://github.com/Monotype/Monotype_prototype_variable_fonts)
- [CFF 操作碼測試字體](https://github.com/Pomax/cff-opcode-fonts) - 用於測試 CFF 操作碼支持的 OTF 字體。
- [TestFont](https://github.com/OpenType/TestFont) - 用於測試 OpenType 實現的字體系列。
- [BuffaloGals](https://github.com/TrueTyper/BuffaloGals) - Buffalo Gals 是最早的“可變字體”之一，最初於 1992 年為 Apple TrueType GX 開發人員 CD 製作。
- [Adobe Fonts / Source Emoji](https://github.com/adobe-fonts/source-emoji) - Source Emoji 是一個開始開發的表情符號字體項目，目的是為 Unicode 聯盟提供單色代表字形供表情符號候選者使用已被 UTC（Unicode 技術委員會）接受但尚未完全批准成為官方標準的一部分。
- [Hasklig](https://github.com/i-tu/Hasklig) - 帶有等寬連字的代碼字體。
- [Firefox OS Emojis](https://github.com/mozilla/fxemoji) - 來自 Mozilla 的表情符號集可用作 SVG 和 TTF 字體。
- [Iosevka](https://github.com/be5invis/Iosevka) - 代碼的細長字體，來自代碼。
- [Raleway](https://github.com/theleagueof/raleway) - 優雅的無襯線字體，採用單薄設計。
- [Adobe NotDef](https://github.com/adobe-fonts/adobe-notdef) - 將 1,111,998 個 Unicode 代碼點映射到 2,048 個 .notdef 字形。
- [Adobe Blank](https://github.com/adobe-fonts/adobe-blank) - 將 1,111,998 個 Unicode 代碼點映射到 2,048 個無間距和無標記字形。
- [Adobe Blank 2](https://github.com/adobe-fonts/adobe-blank-2) - 基於 Adob​​e Blank，主要區別在於字形數量減少到只有兩個，這要歸功於格式化 13 'cmap' 子表。
- [寬度測試](https://github.com/adobe-fonts/width-test) - 用於測試與寬度相關的 GSUB 功能，特別是 'fwid' (Full Widths)、'hwid' (Half Widths)、'twid '（第三寬度）和 'qwid'（四分之一寬度）。
- [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) - OpenType/CFF Pan-CJK 字體集。
- [Source Han Serif](https://github.com/adobe-fonts/source-han-serif) - OpenType/CFF Pan-CJK 字體集。
- [Open Emoji](https://twitter.com/OpenEmoji) - 將為整個宇宙提供開放和免費的視覺通信技術，即表情符號。
- [Overpass](https://github.com/RedHatBrand/Overpass) - 受 Highway Gothic 啟發的開源字體系列。

更多信息，請查看 [awesome-fonts](https://github.com/brabadu/awesome-fonts)！

## 真類型
- [Truetype 字體軟件](http://luc.devroye.org/ttsoftware-index.html) - 列表（大！）和描述 [這裡](http://luc.devroye.org/ttsoftware.html)。


## 書籍
- [字體和編碼](http://shop.oreilly.com/product/9780596102425.do) - 從高級排版到 Unicode 以及介於兩者之間的所有內容 [Google 圖書預覽](https://books.google.fr/books ?id=qrElYgVLDwYC&printsec=frontcover#v=onepage&q&f=false)。
- [Unicode 解釋](http://shop.oreilly.com/product/9780596101213.do) - 將字符映射到數字有數百種不同的編碼系統，但 Unicode 承諾單一映射。[Google 圖書預覽](https://books.google.fr/books?id=lxndiWaFMvMC&printsec=frontcover#v=onepage&q&f=false)。


## 視頻
- [來自 TYPO 會議的演講](https://www.typotalks.com/videos/)
- [⌧的故事！當你的角色未定義時，你能講述你的故事嗎？！由 Persa Zula 提供](https://github.com/pzula/tales-of-notdef)


＃＃ 貢獻
➡️拉取請求！（或者打開一個問題 [這裡](https://github.com/Jolg42/awesome-typography/issues)）。


＃＃ 執照
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允許的範圍內，[Joël Galeran](https://github.com/Jolg42) 已放棄本作品的所有版權和相關或鄰接權。