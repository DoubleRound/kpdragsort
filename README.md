# kpdragsort

页面列表拖动排序

#用法
注意：必须在列表载入完成之后调用

1.不带参数调用
```js
$(list).kpdragsort();
```

2.带参数调用
```js
$(list).kpdragsort({
    // 拖动结束
    onEnd : function(/**Event*/evt) {

    }
});
```

3.可以根据自己的需求不同自定义回调函数如onStart
