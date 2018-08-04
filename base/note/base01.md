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

# 选择器
## 标记选择器
```html
<style type="text/css">
h1 {font-style:italic}
</style>
<h1>hello world</h1>

```
## 类别选择器
```html
<style type="text/css">
.title {font-style:italic}
</style>
<h1 class="title">hello world</h1>
```

## ID选择器
```html
<style type="text/css">
#title {font-style:italic}
</style>
<h1 id="title">hello world</h1>
```

## 多个选择器说明，用逗号隔开
```html
<style type="text/css">
h1,h2,h3 {font-style:italic}
</style>
<h1>hello world</h1>
```
## 嵌套使用
```html
<style type="text/css">
/*p下面的b标签*/
p b {font-style:italic}
</style>
```
## CSS继承
* 子容器会默认继承父容器的样式
* 当存在冲突时，以子容器的样式配置为标准



