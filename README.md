1.Android Design Support Library

这个并不是一个第三方库，是谷歌官方出的支持库。之所以列出来除了上面说的这个APP有使用到它外，更多的是因为这个库很强大~

2. butterknife

这个库应该大家都耳熟能详了，大牛JakeWharton的作品，github上star数量超一万，可见其受欢迎程度。

这个开源库可以让我们从大量的findViewById()和setOnclicktListener()解放出来，其对性能的影响微乎其微，其自定义注解的实现都是限定为RetentionPolicy.CLASS，也就是注解到编译出.class文件为止有效，在运行时不额外消耗性能。

文／Ziv_xiao（简书作者）
原文链接：http://www.jianshu.com/p/dc8c05cf693d
著作权归作者所有，转载请联系作者获得授权，并标注“简书作者”。

3.fastjson，gson

这两个JSON序列化与反序列化库应该都熟悉的了，fastjson是阿里的，gson是Google的，基本功能都差不多，至于为什么两个库都出现在这个APP里面，应该是APP版本的各个开发者使用习惯不一样吧，也有可能是使用的一些第三方库依赖其中一种的原因。

这里要提一下的是fastjson号称是Java语言中最快的JSON库,而且有专门针对Android精简和优化的版本，体积减少了近一半。因为体积更大，为避免出现64K方法数限制而弃用fastjson的理由应该不再成立。fastjson Android版本

4.picasso

    A powerful image downloading and caching library for Android

这个是square 开源的一个强大的图片下载和缓存库。很受欢迎，许多项目都有在使用这个库。使用方式也很简单。

关于图片加载库现在比较流行的还有Glide和Fresco。
Glide
Google员工私人项目，Google很多项目在用。picasso能做到的它都能做到，并且还支持gif。我在公司的项目中也使用的是这个库。不过注意在使用这个库给ImageView加载图片的时候，ImageView设置 Tag的Id必须显示指定。

5.PullZoomView

6.SwipeBackLayout

    An Android library that help you to build app with swipe back gesture. 

一个能帮我们轻松实现右滑退出当前页面功能的库，这个库也有使用在我们公司的项目中，不过花了不少时间在处理兼容性问题上(有时间的话会把填过的坑分享出来)。

这里有必要再提一下这个库在手势处理方面使用到的ViewDragHelper，非常有用的一个工具类。

7 okhttp okio

这个库也是square开源的一个网络请求库(okhttp内部依赖okio)。据说现在已被Google使用在Android源码上了，可见其强大。

这里有一个大神张鸿洋开源的okhttp封装库okhttp-utils

8.volley

这个库也应该比较熟悉了，Google官方出的一个库，包含网络请求和图片加载缓存功能。在处理小而频繁的网络请求上有优势。

以前使用这个库一般都是添加第三方依赖，比如android-volley 。现在已经有官方Gradle依赖了 。

    compile 'com.android.volley:volley:1.0.0'
    
 9.PagerSlidingTagStrip

    Interactive paging indicator widget, compatible with the ViewPager from the Android Support Library. 

这个库使用比较也比较广泛，实现ViewPage和顶部指示器联动滑动的效果。

10.Android-PickerView

    仿iOS的PickerView控件，有时间选择和选项选择并支持一二三级联动效果 
    
11.packer-ng-plugin

    下一代Android打包工具，1000个渠道包只需要5秒
13.Logger

    Simple, pretty and powerful logger for android 

像作者说的一样，简单，漂亮，强大的一款日志打印工具。


