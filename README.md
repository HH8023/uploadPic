##手机上传图片（前台）

>此demo是前台HTML去调用手机中的摄像头拍照和手机相册中去选择图片


>然后去生成base64位的string


<h6>图片上传给服务器：</h6>
>   &nbsp;图片压缩完成，但是压缩后的图片不是File，，而是一个base64编码，于是乎两个选择：
>   1、以String的形式将base64编码上传给服务器，服务器转存base64为img图片；(压缩之后直接上传base64给后台，实现简单)
>   2、前端将base64转为File图片类型，上传给服务器。(前端自己转存base64位file图片，这个对与前端压力比较大)
>如需要使用node.js代码到服务器，



***
<h5>整理资料参考于</h5>
>[https://my.oschina.net/zyxchuxin/blog/700381](https://my.oschina.net/zyxchuxin/blog/700381)
<h4>在此表示感谢</h4>
>有一个比较好一点的还没有总结出来，先上[链接](http://code.ciaoca.com/javascript/exif-js/)，之后可以完善。

















