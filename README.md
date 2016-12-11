# LoadingImageView

![来自GreendaMi.top](https://github.com/GreendaMi/LoadingImageView/blob/master/img.gif?raw=true "")

&#160; &#160; &#160; &#160; 一个类似有着加载进度的ImageView，进度用图片原本的彩色表示，没有达到的进度用黑白表示,我用来作为视频下载时的封面。

&#160; &#160; &#160; &#160;进度为0~100之间。0的时候是完全黑白。
  
  ```
  Glide.with(this).load(url).asBitmap().into(mImg);
  mImg.setProgress(p);//设置进度
  ```
  
&#160; &#160; &#160; &#160;注意添加：asBitmap()，或者手动设置bitmap。只能使用ImageView默认的ScaleType。


```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


dependencies {
	        compile 'com.github.GreendaMi:LoadingImageView:1.1'
	}
```
