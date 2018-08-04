# 处理老方浏览器不支持css的办法
1996年之前的浏览器不支持样式
```html
<style type="text/css">
<!--
h1 {font-style:italic}
-->
</style>
```

# 样式分类
## 行内样式
```html
<h1 style="font-style:italic;"></h1>
```
## 内嵌样式
```html
<style type="text/css">
h1 {font-style:italic}
</style>
```
##  链接样式
```html
<link rel="stylesheet" href="abc.css" type="text/css" rel="stylesheet">
```

## 导入样式
```html
<!--
@import url(abc.css);
-->
```

