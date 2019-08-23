# JS代码段

## 点击空白处隐藏弹窗

```js
$(document).mouseup(function(e){
  var _con = $(' 目标区域 ');   // 设置目标区域
  if(!_con.is(e.target) && _con.has(e.target).length === 0){ //判断是否是目标区域或者是否是目标区域的子元素
    // your code...   // 功能代码
  }
});
```

