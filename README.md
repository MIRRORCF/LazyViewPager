# LazyViewPager
修改V4包的源码，禁止ViewPager懒加载，用法和ViewPager一样。然后考虑到会配合TabLayout和Indicator使用，这里使用的是Flyco大神写的一个开源库https://github.com/H07000223/FlycoTabLayout，这里把SlidingTabLayout改写了，能直接配合使用。

使用条件：
1.如果要配合TabLayout和Indicator，必须依赖com.flyco.tablayout:FlycoTabLayout_Lib:2.1.2@aar开源库

使用步骤：
和平时使用ViewPager一样，具体看Demo。

效果看下图
![156465.gif](https://upload-images.jianshu.io/upload_images/7632909-64ce012dbd9acef1.gif?imageMogr2/auto-orient/strip)

最后，附上源码链接https://github.com/MIRRORCF/LazyViewPager/
（ps:有问题请在下方留言）

