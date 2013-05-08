jQuery-full-screen-gallery HTML5
全屏幻灯组图浏览
==========================

  由于经常拍照，对于高清大照片，总觉得电脑屏幕太小看着不太爽，想放大看细节也不太方便，既然HTML5支持全屏了，那为何不用呢？
  于是写了这么一个小东东，只为满足自己看高清大图的需求。
  
  特点：
  在支持HTML5 fullscreen API的浏览器上自动全屏显示
  支持双击缩放图片，可方便的查看原片的画质
  支持键盘翻页
  
  
HTML：
  
  ```html

<div id="container">
<a href="http://my.dili360.com/attachments/201007/22/152134_1279811418WI0X.jpg"  rel="fullScreenGallery" title="那一年荷花开满池塘">
<img src="http://my.dili360.com/attachments/201007/22/152134_12798105832520.jpg.thumb.jpg" width="200">
</a>
<a href="http://my.dili360.com/attachments/201007/22/152134_12798113192wX1.jpg"  rel="fullScreenGallery" title="那一年荷花开满池塘">
<img src="http://my.dili360.com/attachments/201007/22/152134_12798105832520.jpg.thumb.jpg" width="200">
</a>
</div>
  ```

为A链接 链接增加 rel="fullScreenGallery" 属性，href为大图的地址。

JS调用:

  ```html

<script type="text/javascript">
  $('#container a[rel="fullScreenGallery"]').fullScreenGallery();
</script>
  ```


  
