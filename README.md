### whitestormjs
---
https://github.com/WhitestormJS/whs.js

```
npm install whs@beta

```

```
<script src="js/three.min.js"></script>
<script src="js/whs.min.js"></script>
```

```js
const app = new WHS.App([
  new WHS.ElementModule(),
  new WHS.SceneModule(),
  new WHS.DefineModule('camera', new WHS.PerspectiveCamera({
    position: new THREE.Vector3(0, 0, 50)
  })),
  new WHS.RenderingModule({bgColor: 0x162129}),
  new WHS.ResizeModule()
]);
app.start();

```


