# Hello Three.js 之 Hello world!

> [Demo查看](http://codeffe.com/demo/hello-threejs/hello-world.html)

![Hello world](./images/hello-world.png)

## Threejs介绍

threejs 最早是 [Ricardo Cabello(一个西班牙小伙)](https://github.com/mrdoob) 在 GitHub上发布的一个基于webgl的3D图形库。

当然,除了Threejs还有其他类似3D图形库比如:

- [Babylon.js](https://github.com/BabylonJS/Babylon.js)
- [PhiloGL](https://github.com/senchalabs/philogl)
- [GLGE](https://github.com/supereggbert/GLGE)
- [scenejs](https://github.com/xeolabs/scenejs)
- [osgjs](https://github.com/cedricpinson/osgjs)
- [c3dl](https://github.com/senchalabs/c3dl)

**threejs带来了什么？**

3D绘图通常来说是比较复杂带工作，用到glsl到很多知识，用js直接调用操作，非常复杂且低效，

这个时候 threejs出现了，使用threejs封装好到功能，可以很方便快速到创造一些简单到场景。

下面我们就来试着写第一个hello world!

## 准备工作

新建空白 html 页面，引入 three.js，及页面元素准备。

```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Hello world</title>
  <script type="text/javascript" src="js/three.js"></script>
</head>
<body>
    <canvas id="mainCanvas"></canvas>

    <script type="text/javascript">
      // ...code
    </script>
</body>
</html>
```

## 基本概念介绍

一个典型的Three.js程序至少要包括:

- 渲染器（Renderer）---- 渲染器将和Canvas元素进行绑定
- 场景（Scene）---- 我们创建的物体都添加到场景中，相当于一个大容器
- 照相机（Camera）---- 这里相当于一个透视投影的三维坐标系
- 在场景中创建的物体

创建一个形状的代码如下：

```
var renderer = new THREE.WebGLRenderer({
  canvas: document.getElementById('mainCanvas')
});

renderer.setClearColor(0x000000); // black

// 创建场景
var scene = new THREE.Scene();

// 创建相机
var camera = new THREE.PerspectiveCamera(45, 4 / 3, 1, 1000);
camera.position.set(0, 0, 5);
scene.add(camera); // 记得把相机添加到场景

// 创建一个长方形
var cube = new THREE.Mesh(new THREE.CubeGeometry(1, 2, 3),
        new THREE.MeshBasicMaterial({
            color: 0xff0000
        })
);
scene.add(cube);

// 渲染器最终渲染
renderer.render(scene, camera);
```

现实中会有光源照射物体，产生光影效果，这里也可以添加 light。

```
var renderer = new THREE.WebGLRenderer({
    canvas: document.getElementById('mainCanvas')
});

renderer.setClearColor(0xffcc00);
renderer.setPixelRatio(window.devicePixelRatio);
renderer.setSize(window.innerWidth, window.innerHeight);

// scene
var scene = new THREE.Scene();

// 添加环境光
var light = new THREE.AmbientLight(0xffffff, 0.4);
scene.add(light);

// 添加点光源
var light2 = new THREE.PointLight(0xffffff, 0.7);
scene.add(light2);

// camera
var camera = new THREE.PerspectiveCamera(35, window.innerWidth / window.innerHeight, 0.1, 3000);
// camera.position.set(0, 0, 5);

var geometry = new THREE.CubeGeometry(200, 200, 200);
// var material = new THREE.MeshBasicMaterial();
var material = new THREE.MeshLambertMaterial({color: 0xffffee});
var mesh = new THREE.Mesh(geometry, material);

mesh.position.set(0, 0, -1000);

scene.add(mesh);

//
requestAnimationFrame(render)

function render() {
    mesh.rotation.x += 0.01;
    mesh.rotation.y += 0.02;
    // render
    renderer.render(scene, camera);
    requestAnimationFrame(render)
}
```

## 总结

Threejs开发过程初步可归纳为

1、设置照相机 `camera = new THREE.Camera();` 用于观察物体 2、设置场景 `scene = new THREE.Scene()` 用于承载物体 3、建立物体 `geometry = new THREE.CubeGeometry(200, 200, 200);` 4、创建网格 `mesh = new THREE.Mesh(geometry, material)` 5、渲染呈现 `renderer.render(scene, camera)`

当然还有灯光、动画、材质、控制场景内物体等其他内容，在此不赘述，后续逐步学习。

以上，如果使用过flash或者maya等软件等话，相信对以上场景、相机、渲染、灯光等会比较容易理解。 在这里可以联想为在3D软件里创建一个物体，当然软件所有操作及效果是需要我们用代码来实现。

--------------------------------------------------------------------------------

> [查看视频教程地址](https://www.youtube.com/watch?v=biZgx45Mzqo&list=PL08jItIqOb2qyMOhtEUoLh100KpccQiRf&index=2)
