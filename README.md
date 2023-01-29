# Css-Animation
Css 动画
###### 1.animation-name 设置一个动画的名字，名字可以是自定义的
###### 2.animation-duration 设置动画的持续时间，两个单位s  ms
###### 3.animation-delay  动画的延迟时间  也可以是负数，为负数时回抵消animation-duration的时间
###### 4.animation-iteration-count  设置动画重复的次数，默认时1无限次是infinite
###### 5.animation-timing-function 动画运动形式
值：（1）linear 动画从头到尾的速度都是相同的
（2）ease 默认。动画以低速开始，然后加快，在结束前变慢
（3）ease-in  动画以低速开始
（4）ease-out  动画以低速结束
（5）ease-in-out 动画以低速开始和结束
（6）cubic-bezier(n,n,n,n) 在 cubic-bezier 函数中自己的值。可能的值是从 0 到 1 的数值
###### 6.animation-fill-mode  规定动画播放之前或者之后动画是不是可见
值：
（1）forwards 在动画结束后，动画应用最后的属性
（2）backwards 动画将在animation-delay定义期间启动动画的第一次迭代的关键帧中定义的属性
###### 7.animation-direction 定义是否应该轮流反向播放动画   alternate 一次正向一次反向 reverse永远都是反向  normal默认