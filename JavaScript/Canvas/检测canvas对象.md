### 封装判断函数
```
function supportCanvas(c) {
  return !!c.getContext();
}
```
### 使用
```
function drawApp() {
  let canvas = document.getElementById('canvas');
  if (supportCanvas(canvas)) {
    draw();
  }
}
```
