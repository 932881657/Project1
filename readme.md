#  Project 1 说明文档
## 1.张天翼 19302010024
## 2.地址
github地址：https://github.com/932881657
gitpage地址：https://github.com/932881657/Project1
## 3.项目完成情况
在本次PJ1中，我完成了网页的全部基础要求和bonus需求，下主要讲解5.1与5.2的完成思路
### bonus5.1
在homepage中，需要将不同大小的图片转化为相同大小，才能使得排版更为美观，而直接使用img似乎很难做到这一点。因此我选择在原本放置图片的地方放置一个空的div，然后在css中将其大小设置为固定值，并把所需图片设置为背景图片，最后再将溢出的部分隐藏即可。
### bonus5.2
由于我在一些较为复杂的页面中使用了float，在调整页面大小时可能会出现整个div错位的问题。我采取的解决方式为把div的margin与width以百分比的形式设置，这样在调整页面大小时就可以避免移位的问题。对于适应手机的问题，我使用了meta标签以适应屏幕大小，并将出现div溢出情况的元素的display属性设置为inline-block。最后将可能会变的过于小的div设置最小宽度。经实测，网页在iphoneX与ipad上的效果均较为理想。



