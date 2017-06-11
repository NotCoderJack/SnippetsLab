## 判断文档加载完毕
使用canvas应该首先判断文档是否加载完成, 所以可以进行下面的操作
```
window.addEventListener('load', , false); 
function drawCanvas () { 
  drawer()//  此处渲染canvas
}
```
