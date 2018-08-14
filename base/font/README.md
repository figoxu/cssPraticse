
# 通过ttf生成otf
```
brew install fontforge
fontforge -script genOtf.pe 汉仪伊宁隶简.ttf
```

# 字蛛压缩字体文件
http://font-spider.org/#install
```
brew reinstall node
cnpm install font-spider -g
font-spider ./*.html
```
页面依赖的字体将会自动压缩好，原 .ttf 字体会备份