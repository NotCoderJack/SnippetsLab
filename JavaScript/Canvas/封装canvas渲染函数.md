### `canvas`
`canvas`作用在页面的固定区域，与其他任务关联不大。所以可以将`canvas`处理操作分离出来

```
function drawCanvas() {
  let c = document.getElementById('canvas-i');
  
  function supportCanvas(ele) {
    return !! ele.getContext();
  }
  function drawRect() {
    // 画正方形
    draw();
  }
  function drawTrai() {
    // 画三角形
    draw();
  }
  if (supportCanvas(c)) {
    let ctx = c.getContext('2d');
    
  }
}
```
