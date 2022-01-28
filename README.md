# css3dphoto（3d相册）
## 总结：
##### transform：translate(x,y) rotate(180deg) scale() ... 顺序对最后的效果有影响，需要根据需求安排位移和其他属性的顺序；
##### 实现暂停动画效果：animation-play-state:paused; 经常和鼠标经过等其他配合使用；
##### 实现动画走回来，而不是跳回来：animation-direction:alternate; ；
##### 实现动画结束后，停在结束位置：animation-fill-mode:forwards; ；
##### 实现打字机动画效果：steps() 指定时间函数的间隔步长，用来分几步完成动画，有了 steps() 就不要写 ease 或 linear ；
##### 实现大数据热点图时，不要用 scale ，会把阴影放大；
##### 3D透视 perspective 和 3D呈现 transform-style:preserve-3d; 需要写在被观察盒子的父级盒子里面；
