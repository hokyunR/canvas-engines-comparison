# Canvas Engines Comparison

KonvaJS(canvas), PixiJS(2d webgl), ThreeJS(3d webgl)의 CPU 사용률 비교

## 환경

모델명: MacBook Pro  
모델 식별자: MacBookPro17,1  
칩: Apple M1  
총 코어 개수: 8(4 성능 및 4 효율)  
메모리: 16 GB

## 결과

박스 개수에 따른 CPU 사용률

|         | 10    | 2000   |
| ------- | ----- | ------ |
| Konva   | 28.6% | 53.3%  |
| PixiJS  | 49.1% | 63.1%  |
| ThreeJS | 44.0% | 125.3% |

## 실행 방법

```
$ yarn install
$ yarn build
$ yarn start
```

## Engine list

- Up to 2000 different rectangles moving on a canvas with various speed
- Different choice of libraries used to render the scene :

|                                                            | module kb                                                  |
| ---------------------------------------------------------- | ---------------------------------------------------------- |
| [PixiJS](https://www.pixijs.com)                           | ![](https://badgen.net/bundlephobia/min/pixi.js)           |
| [Mesh.js](https://github.com/mesh-js/mesh.js)              | ![](https://badgen.net/bundlephobia/min/@mesh.js/core)     |
| [P5.js](https://p5js.org)                                  | ![](https://badgen.net/bundlephobia/min/p5)                |
| [ZRender](https://github.com/ecomfe/zrender)               | ![](https://badgen.net/bundlephobia/min/zrender)           |
| [Two.js](https://two.js.org/)                              | ![](https://badgen.net/bundlephobia/min/two.js)            |
| [Konva.js](https://konvajs.org/)                           | ![](https://badgen.net/bundlephobia/min/konva)             |
| [CanvasKit](https://skia.org/docs/user/modules/canvaskit/) | ![](https://badgen.net/bundlephobia/min/canvaskit-wasm)    |
| [Pencil.js](https://pencil.js.org/)                        | ![](https://badgen.net/bundlephobia/min/pencil.js)         |
| [Paper.js](http://paperjs.org/)                            | ![](https://badgen.net/bundlephobia/min/paper)             |
| [Fabric.js](http://fabricjs.com/)                          | ![](https://badgen.net/bundlephobia/min/fabric)            |
| [Three JS](https://threejs.org/)                           | ![](https://badgen.net/bundlephobia/min/three)             |
| [Scrawl-canvas](https://scrawl-v8.rikweb.org.uk/)          | ![](https://badgen.net/bundlephobia/min/scrawl-canvas)     |
| [Pts](https://github.com/williamngan/pts)                  | ![](https://badgen.net/bundlephobia/min/pts)               |
| [EaselJS](https://github.com/CreateJS/EaselJS)             | ![](https://badgen.net/bundlephobia/min/@createjs/easeljs) |
| [SVG.js](https://github.com/svgdotjs/svg.js)               | ![](https://badgen.net/bundlephobia/min/@svgdotjs/svg.js)  |
