# icooc
仿慕课手机宣传

#实现思路
1、采用BEM开发模式
2、布局主要为了relative+absolute+float
3、采用动画css3+js
4、通过监听滚动条高度判断页面的位置，设置对应的动画
5、通过onmouseover和onmouseout事件监听鼠标在导航之间移动，设置nav-tip元素位置样式滑动效果
6、通过onclick事件判断鼠标点击的导航项，设置滚轮高度移动的相应位置，判断滚动位置设置相应的导航项和侧边导航项，从而实现双向定位
