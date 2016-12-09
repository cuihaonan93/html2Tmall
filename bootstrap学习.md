# 使用Bootstrap
1、因为bootstrap用到了html5的特性，为了正常使用，需要在最开头加上
<!DOCTYPE html>

2、接着导入js和css
Bootstrap需要JQuery才能正常工作，所以需要导入jquery.min.js
接着是 Bootstrap的css，里面定义了各种样式
最后是 Bootstrap的js，用于产生交互效果，比如关闭警告框
注：顺序不要搞错了，否则有一些效果会出不来。
首先是JQuery
然后是Bootstrap css
最后是Bootstrap js
引用代码：
```html
<script src="http://how2j.cn/study/js/jquery/2.0.0/jquery.min.js"></script>
<link href="http://how2j.cn/study/css/bootstrap/3.3.6/bootstrap.min.css" rel="stylesheet">
<script src="http://how2j.cn/study/js/bootstrap/3.3.6/bootstrap.min.js"></script>
```

3、简单使用
接着就是出现BootStrap的效果，使用是非常简单的，只需要套用 bootstrap css中定义的class即可。
如按钮，增加class btn btn-success 就能有bootstrap的效果了
```html
<script src="http://how2j.cn/study/js/jquery/2.0.0/jquery.min.js"></script>
<link href="http://how2j.cn/study/css/bootstrap/3.3.6/bootstrap.min.css" rel="stylesheet">
<script src="http://how2j.cn/study/js/bootstrap/3.3.6/bootstrap.min.js"></script>

<button class="btn btn-success">按钮</button>
```
