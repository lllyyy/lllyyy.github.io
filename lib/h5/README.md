
h5video
----
此项目为了解决H5视频在手机端不能全屏播放以及去除滚动条的问题，在网上找了很多资料，最终解决该问题

需要注意的是
---
安卓手机不能自动播放，苹果手机通过添加以下代码可以自动播放</br>

    document.addEventListener("WeixinJSBridgeReady", function (){
	    video.play();
    }, false);
    
同层播放在安卓手机上会出现问题播放器层级max的问题，暂未解决

其他问题可自己测试，视频来源于网络，如侵权联系删除</br>
[DEMO](https://loveviagra.xin/h5Video/index.html)
