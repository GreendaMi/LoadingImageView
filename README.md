# LoadingImageView

  一个类似有着加载进度的ImageView，进度用图片原本的彩色表示，没有达到的进度用黑白表示。进度为0~100之间。
  
  ```
  Glide.with(this).load(url).asBitmap().into(mImg);
  mImg.setProgress(p);//设置进度
  ```
  
  注意添加：asBitmap()，或者手动设置bitmap。只能使用ImageView默认的ScaleType。
