h5video
----
此项目为了解决H5视频在手机端不能全屏播放以及去除滚动条的问题，在网上找了很多资料，最终解决该问题，

需要注意的是
---
安卓手机不能自动播放，苹果手机通过添加以下代码可以自动播放</br>
document.addEventListener("WeixinJSBridgeReady", function (){</br>
    video.play();</br>
}, false);</br></br>

其他问题可自己测试，视频来源于网络，如侵权联系删除
