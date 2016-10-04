# gltf-test
List of glTF loader in some WebGL libraries.

| Model                                         | Screenshot                                              |[Three.js r79(basic loader)](https://github.com/mrdoob/three.js/blob/dev/examples/js/loaders/GLTFLoader.js) |[Three.js r79(advance loader)](https://github.com/mrdoob/three.js/tree/dev/examples/js/loaders/gltf)     |[Three.js r82dev(new loader)](https://github.com/richtr/three.js/blob/feature/GLTFLoader/examples/js/loaders/GLTFLoader.js)|[Babylon.js 2.5-alpha](https://github.com/BabylonJS/Babylon.js/tree/master/loaders/glTF)                   |[Cesium.js 1.24](https://github.com/AnalyticalGraphicsInc/cesium/)                         |[xeoEngine 2016.08.16](https://github.com/xeolabs/xeoengine/tree/master/src/importing/gltf)          |[GLBoost 2016.08.20](https://github.com/emadurandal/GLBoost/blob/master/src/js/middle_level/loader/GLTFLoader.js) |
|-----------------------------------------------|---------------------------------------------------------|------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
|[Box](sampleModels/Box)                        |![](sampleModels/Box/screenshot/screenshot.png)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/Box/)                   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/Box/)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/Box/)              |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/Box/)                  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/Box/)         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/Box/)                |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/Box/)                               |
|[Box Textured](sampleModels/BoxTextured)       |![](sampleModels/BoxTextured/screenshot/screenshot.png)  |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/BoxTextured/)           |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/BoxTextured/)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/BoxTextured/)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/BoxTextured/)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/BoxTextured/) |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/BoxTextured/)        |:x: [Sample](https://cx20.github.io/gltf-test/examples/glboost/BoxTextured/) has texture problem                  |
|[Duck](sampleModels/Duck)                      |![](sampleModels/Duck/screenshot/screenshot.png)         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/Duck/)                  |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/Duck/) has blackout problem       |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/Duck/)             |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/Duck/)                 |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/Duck/)        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/Duck/)               |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/Duck/)                              |
|[Box Animated](sampleModels/BoxAnimated)       |![](sampleModels/BoxAnimated/screenshot/screenshot.gif)  |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/BoxAnimated/) animation not support    |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/BoxAnimated/) has blackout problem|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/BoxAnimated/)      |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/BoxAnimated/)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/BoxAnimated/) |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/BoxAnimated/) animation not support |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/BoxAnimated/)                       |
|[Rigged Simple](sampleModels/RiggedSimple)     |![](sampleModels/RiggedSimple/screenshot/screenshot.gif) |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/RiggedSimple/) animation not support   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/RiggedSimple/)     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/RiggedSimple/)     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/RiggedSimple/)         |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/RiggedSimple/)|:x: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/RiggedSimple/) animation not support|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/glboost/RiggedSimple/)                      |
|[Rigged Figure](sampleModels/RiggedFigure)     |![](sampleModels/RiggedFigure/screenshot/screenshot.gif) |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/RiggedFigure/) animation not support   |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/RiggedFigure/)     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/RiggedFigure/)     |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/RiggedFigure/) animation not work     |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/RiggedFigure/)|:x: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/RiggedFigure/) animation not support|:x: [Sample](https://cx20.github.io/gltf-test/examples/glboost/RiggedFigure/) has nightmare dragon problem        |
|[Monster](sampleModels/Monster)                |![](sampleModels/Monster/screenshot/screenshot.gif)      |:x: [Sample](https://cx20.github.io/gltf-test/examples/threejs_basic/Monster/) animation not support        |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_advance/Monster/)          |:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/threejs_new/Monster/)          |:x: [Sample](https://cx20.github.io/gltf-test/examples/babylonjs/Monster/) has nightmare dragon problem|:white_check_mark: [Sample](https://cx20.github.io/gltf-test/examples/cesium/Monster/)     |:x: [Sample](https://cx20.github.io/gltf-test/examples/xeoengine/Monster/) animation not support     |:x: [Sample](https://cx20.github.io/gltf-test/examples/glboost/Monster/) has nightmare dragon problem             |
