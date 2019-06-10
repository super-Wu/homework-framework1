# homework-framework1
写一个可以浏览多张照片的幻灯片插件

功能：
* 可以翻页
* 可以点击弹开

这个简单的作业可以让大家进入状态。
请你尝试用尽量简单的代码和可扩展的结构来编写。
下一讲我会选择几个同学的作业来点评。

##插件参数

* placeholder: 0,//非连续滚动时每次的滑动距离，可以自定义，如果没有自定义则根
* dir: 'left',//滚动方向，left & top
* container: 'div',//外层对象
* inner: 'img',//内部元素
* speed: 1000,//非连续滚动速度
* delayTime: 0,//滚动间隔
* continuous: false,//是否连续
* num: 1,//非连续一次滚动的数量
* viewer: true,//是否点击预览图片
