# [Awesome-threejs](https://github.com/zyj1022/awesome-threejs/)

搜集並學習threejs的相關知識總結、Demo、 網站、書籍等，歡迎有興趣的小夥伴一起交流學習。

## [Threejs](https://threejs.org)

three.js是以webgl為基礎的庫，封裝了一些3D渲染需求中重要的工具方法與渲染循環。WebGL門檻相對較高,Three.js對WebGL提供的介面進行了非常好的封裝，簡化了很多細節，大大降低了學習成本。查看[官方實例](https://threejs.org/examples/)

## 基礎入門

### 問-學-記

個人學習過程中的疑問記錄及demoDemo，小白入門開始教程之Hello Threejs。

- [x] [什麼是WebGL?](./docs/what-webgl.md)
- [x] [開始第一個Hello world](./docs/hello-world.md)
- [x] [三維空間中觀察物體的方法--照相機](./docs/hello-camera.md)
- [x] [創建各種幾何形狀](./docs/hello-geometry.md)
- [x] [光影之謎](./docs/hello-light.md)
- [x] [給創建的物體賦予材質](./docs/hello-material.md)
- [x] [讓物體動起來](./docs/hello-tween.md)
- [x] [運動3D物體的性能監測](./docs/hello-stats.md)
- [x] [載入外部3D模型](./docs/hello-loader.md)
- [x] [有趣的著色器](./docs/hello-shaders.md)
- [x] [創建自己的全景圖](./docs/hello-cubemap.md)
- [x] [obj、mtl文件格式詳解](./docs/hello-obj-mtl.md)

## 進階教程

- [x] [理解光源的應用](./docs/hello-light-pro.md)
- [ ] 粒子效果點雲
- [ ] 使用二元操作組合網格
- [ ] 幾何體的合併與組合
- [ ] 攝像機控制器
- [ ] 變形動畫與骨骼動畫
- [ ] 場景內物體的物理效果
- [ ] 自定義著色器與後期處理
- [x] [OpenGL GLSL 基礎語法和函數](./docs/glsl/glsl-syntax.md)
- [x] [GLSL 中文手冊](./docs/glsl/glsl-cookbook.md)

### 踩坑經驗

分享記錄遇到的坑及解決方案

> 以下經驗來自[快樂小球球](https://zhuanlan.zhihu.com/p/25483816)

- 圖片尺寸必須以2的n次方<=1024，如果圖片不是2的整數倍數，引擎會自動壓縮到2的整數倍數，在chrome控制台中會出提示，粗看沒事，但在iphone6Plus下會卡到微信閃退.
- 用webpack打包模型文件，用各種載入器中的 prase 直接解析即可。模型在 webpack 中以 raw 載入

  ```
  module: {
    loaders: [
      {test: /\.dae$/, loader: 'raw'},
      ...
    ]
  }
  ```

## Shader 相關資料

- [LearnOpenGL-CN](https://learnopengl-cn.readthedocs.io/zh/latest/)
- [The Book of Shaders](https://thebookofshaders.com/?lan=ch)--一本關於 Fragment Shaders（片段著色器）的入門指南
- [The Book of Shaders Editor](http://editor.thebookofshaders.com)- Shaders 在線編輯器
- [Inigo Quilez](http://www.iquilezles.org/www/index.htm) - 有關電腦圖形學、著色器的部落格程式碼示例
- [Introducing Shaders](https://openframeworks.cc/ofBook/chapters/shaders.html)
- [pixelshaders](http://pixelshaders.com/) - 基礎程式碼示例

### shader 效果

用如上 **[Shaders 在線編輯器](http://editor.thebookofshaders.com)** 可以查看效果 [這裡查看效果程式碼](./docs/glsl/glsl_shaders.md)

### 網上收集資料

- [Three.js Fundamentals starting lesson](https://threejsfundamentals.org/threejs/lessons/threejs-fundamentals.html) 官網推薦入門教程
- [圖解WebGL&Three.js工作原理](https://www.cnblogs.com/wanbo/p/6754066.html)
- [three.js editor使用影片教程](https://www.youtube.com/watch?v=rqn-KPnh3hM)
- [youtube入門影片教程](https://www.youtube.com/watch?v=biZgx45Mzqo&list=PL08jItIqOb2qyMOhtEUoLh100KpccQiRf&index=2)
- [Three.js 中文文檔](http://techbrood.com/threejs/docs/)
- [ThreeJS快速入門](https://zhuanlan.zhihu.com/p/23272116)
- [learningthreejs-系列部落格](http://learningthreejs.com)
- [webgl 入門教程](https://codepen.io/rachsmith/post/beginning-with-3d-webgl-pt-1-the-scene)
- [使用 D3 + webgl 製作地球儀](http://www.delimited.io/blog/2015/5/16/interactive-webgl-globes-with-threejs-and-d3)
- [使用 header-tracker 和 webRTC](http://learningthreejs.com/blog/2013/03/12/move-a-cube-with-your-head/)
- [Intro to WebGL with Three.js](http://davidscottlyons.com/threejs/presentations/frontporch14/#slide-0)
- [Google+ 關於 threejs 的文章發布](https://plus.google.com/+ThreejsOrg)

## Threejs 相關的庫

- [tween lite](https://greensock.com/)
- [dat.gui: 一個輕量級的視覺化庫供開發者調試變數使用](https://github.com/dataarts/dat.gui)
- [csg.js: 封裝了幾何體合併、取交集、取非交集的方法](http://evanw.github.io/csg.js/docs/)
- [headtraker](https://github.com/auduno/headtrackr)
- [html_gl](https://github.com/PixelsCommander/HTML-GL)
- [threex](http://www.threejsgames.com/extensions/)
- [ar.js](https://github.com/then/promise)

## 貼圖素材

- [3dwarehouse](https://3dwarehouse.sketchup.com)
- [行星素材](http://planetpixelemporium.com/earth.html)
- [Clara.io 3D素材](https://clara.io/library)
- [Shadertoy 著色器](https://www.shadertoy.com)
- [各種著色器 demo 文章](http://www.iquilezles.org/www/index.htm)

## 在線 網站

- [marpi.pl](https://demo.marpi.pl) - 很多牛X的Demo
- [Altered Qualia](http://alteredqualia.com/) - 也是很棒的Demo
- [CESIUM 3D 地球](http://cesiumjs.org/index.html)

### 在線DEMO

- [三種方法創建3D粒子效果](https://varun.ca/three-js-particles)
- [three-seed](https://github.com/edwinwebb/three-seed/) - three.js starter project with ES6 and Webpack
- [The Aviator](https://tympanus.net/codrops/2016/04/26/the-aviator-animating-basic-3d-scene-threejs/) - the-aviator-animating-basic-3d-scene-threejs
- [Infinite Tubes](https://tympanus.net/codrops/2017/05/09/infinite-tubes-with-three-js/)
- [Decorative WebGL Backgrounds](https://tympanus.net/codrops/2017/11/28/decorative-webgl-backgrounds/)
- [egraether - Demos](http://egraether.com)
- [David Lyons - 3D Artist](http://davidscottlyons.com)
- [83個含註釋Demo](https://stemkoski.github.io/Three.js/)
- [workshop](http://workshop.chromeexperiments.com)
- [Three Bird](http://codepen.io/Yakudoo/pen/LVyJXw?editors=0010)
- [Crystals](http://codepen.io/aglosson/pen/rVyRGm?editors=0010)
- [three.js-editor](https://threejs.org/editor/)
- [星空](http://charliehoey.com/threejs-demos/our-galactic-neighborhood.html)
- [3D投影](https://threejs.org/examples/#webgl_materials_cubemap)
- [voxelpainter](https://threejs.org/examples/webgl_interactive_voxelpainter.html)
- [tunnel-effect](http://learningthreejs.com/blog/2012/01/11/tunnel-effect/)
- [Altered earth](http://alteredqualia.com/xg/examples/earth_bathymetry.html)

## 相關書籍資料

收集整理學習資料。

- [《threejs-intro》](http://davidscottlyons.com/threejs-intro/#slide-1)----很棒的入門示例
- 《WebGL編程指南》
- 《Three.js開發指南》-- [在線Demo案例](http://www.skyliu.top/three-js/)
- [《Three.js入門指南》](http://www.ituring.com.cn/book/1272)--[書例程式碼](http://zhangwenli.com/ThreeExample.js/)
- [Three.js入門教程](http://www.cnblogs.com/yiyezhai/category/447410.html) -- 這是對國外一份教程的翻譯，一共六篇文章。講解不多，更多的是展示各個基本功能怎麼用。更適合有一些圖形基礎的同學

## 同類庫探索

![b4w](./docs/images/b4w.png) ![p5.js](./docs/images/p5.png)

- [blend4web](https://github.com/TriumphLLC/Blend4Web)

  - [Demo案例 - 仿機械革命源計劃-私人定製](http://zyj1022.github.io/demos/blend4web/index.html)

- [P5.js](https://p5js.org/zh-Hans/) - [基礎教程](./docs/hello-p5.md)

  - [p5.js Web Editor](https://editor.p5js.org) - p5在線編輯器
  - [OpenProcessing](https://www.openprocessing.org/) - 各種 demo
  - wangyasai-[亞賽大人](https://github.com/wangyasai),很多好玩的效果，👍.

    - [Speed-Line](https://wangyasai.github.io/Speed-Line/) - 漫畫必備超燃速度線
    - [Play-a-ball](https://wangyasai.github.io/Play-a-ball/) - 抽象球體生成器
    - [Awesome Masoic](https://wangyasai.github.io/Awesome-Masoic) - 動態馬賽克背景生成器
    - [Perlin Noise](https://wangyasai.github.io/Perlin-Noise/) - 等高線神器
    - [Stars-Emmision](https://wangyasai.github.io/Stars-Emmision/) - 萬箭齊發毫髮無傷背景生成器
    - [Particles-Emission](https://wangyasai.github.io/Particles-Emission/) - 粒子循環運動神器
