## 矩形
* API
  * `fillRect(beginX,beginY,width,height)`
  * `clearRect(beginX,beginY,width,height)`
```js
var myCanvas = document.getElementsByTagName('canvas')[0]
var ctx = myCanvas.getContext('2d')
ctx.fillStyle = '#000000'
ctx.fillRect(0,0,200,200)
```