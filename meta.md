                                                <meta >形式
1.   <meta name="format-detection" content="telephone=no">
    format-detection：格式检测，用来检测html里的一些格式的，关于meta的format-detection属性是有以下几个设置：
  <meta name="format-detection" content="telephone=no">  /*在ipone下禁止把数字转化为拨号链接*/
  <meta name="format-detection" content="email=no">  /*禁止作为邮箱地址*/
  <meta name="format-detection" content="adress=no" > /*禁止跳转到地图*/



2.   针对移动端优化的站点的内容
 <meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=0,minimum-         scale=1.0,maximum-scale=1.0,minimal-ui" />
   viewport是什么？
答：移动设备上的viewport是浏览器（也可能是一个app中的webview）用来显示网页的那部分区域
   layout viewport:是网页布局的区域，有时候浏览器窗口没有办法显示出layout viewport的全貌，但它确实加载出来了，这时滚动条就出现了         
   visual viewport：是显示在屏幕上的网页区域，设备自己的宽度
 viewport的属性及方法：
           width:设置layout viewport的宽度，为一个正整数（device-width指比例为100%时屏幕宽度的CSS像素数值）
           initial-scale:设置页面的初始缩放值，为一个数字，可以带小数
           user-scalable:是否允许用户进行缩放，值为：no或0(不允许)，yes或1（允许）
           minimum-scale:允许用户的最小缩放值，可以带小数
           maximum-scale:允许用户的最大缩放值，为一个数字，可以带小数
           minimal-ui:网页在加载时可以隐藏顶部的地址栏与底部的导航栏
3.    <meta name="apple-mobile-web-app-capable" content="yes">    代表是否会启动webapp功能，会删除默认的苹果工具栏和菜单栏
4.<meta name="apple-mobile-web-app-status-bar-style" content="black">  作用：控制状态栏显示样式  
         当启动webapp功能时，显示手机信号、时间、电池的顶部导航栏的颜色。默认值为default（白色），可以定为black   （黑色）和black-translucent（灰色半透明）。这个主要是根据实际的页面设计的主体         
           






