#HTML+CSS部分
####1、CSS 隐藏元素的方法有哪些？（5种）
>* 将opacity 设为 0;
>* 将 visibility 设为 hidden;
>* 将 display 设为 none ;
>* 将 position 设为 absolute 然后将位置设到不可见区域;
>* Clip-path,通过裁剪的方法实现隐藏;

#####参考文档
>* [CSS隐藏元素的5种方法](http://www.cnblogs.com/cythia/p/5981306.html)
>* [css3的clip-path属性介绍](http://www.haorooms.com/post/css3_clip-path)
>* [CSS3 clip-path polygon图形构建与动画变换二三事](http://www.zhangxinxu.com/wordpress/2015/03/css3-clip-path-polygon-shape-transition-animation/)
>* [CSS中的基本图形和路径(clip-path_入门 精通 教程)](http://www.w3cplus.com/blog/tags/431.html)

####2.用css实现垂直水平居中的几种方法（6种）---[参考文档](http://blog.csdn.net/baidu_24024601/article/details/51131368)
>* **1、用inline-block和vertical-align来实现居中：**这种方法适合于未知宽度高度的情况下;
>* **2、用相对绝对定位和负边距实现上下左右居中：**高度和宽度已知;
>* **3、利用绝对定位来实现居中：**适合高度，宽度已知的情况。
>* **4、使用table-cell，inline-block实现水平垂直居中：**适合高度宽度未知的情况
>* **5、使用css3中的transform来时实现水平垂直居中：**适合高度宽度未知的情况
>* **6、使用Flexbox来实现水平垂直居中:**适合宽度高度未知情况，但是要注意兼容性

#####其他参考文档：
>* [张鑫旭对CSS vertical-align的一些理解与认识](http://www.zhangxinxu.com/wordpress/2010/05/%E6%88%91%E5%AF%B9css-vertical-align%E7%9A%84%E4%B8%80%E4%BA%9B%E7%90%86%E8%A7%A3%E4%B8%8E%E8%AE%A4%E8%AF%86%EF%BC%88%E4%B8%80%EF%BC%89/)
>* [css居中那些事](http://blog.csdn.net/a7282787/article/details/51034440)
>* [ 利用vertical-align:middle实现在整个页面居中](http://blog.csdn.net/wyzlwyzl/article/details/17734077)
