#opacity 

这是一个图片的轮播显示插件，动画过程基于透明度的过度 兼容大部分主流浏览器 包括IE(5,7,8,9,10,11)

忌 ：目前一个页面只能调用一次此方法

此方法有三个参数：

    1, W : 设置整个轮播图的宽度 默认（100%）

    2, H : 设置整个轮播图的高度 默认（100%）

    3, speed : 设置轮播的时间，默认 （3000）

    4, isloop : 是否循环m播放，默认 （false）//如果设置该属性那么轮播到最后一个时停止播放

    5，iscarousel : s是否开启自动播放模式，默认（true）
		 
		 
调用方式：
		 
	$("#carousel-big a").carousel({
      W : '100%',
      H : 320,
      speed : 3000,
      isloop : false,
      iscarousel : true
  });
