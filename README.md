# ScrollViews/TableViews

下载后找不到PCH文件的,可以在 Build Settings里搜索prefix header, 然后 设置 Precompile Prefix Header 为YES; 再设置 Prefix Header 路径, 双击后,直接把左侧的PrefixHeader.pch拉进弹框里,回车就OK了. 不明白的参考http://blog.csdn.net/lg767201403/article/details/72910696 这篇博客

将自己自定义的一些控件,写成demo,有需要的朋友可以拿来参考

LGApplications/Util/LGViews     :   自定义View

LGApplications/Util/Category    :   里面都是项目中常用的,几乎每个项目必备

LGApplications/Util/LGUtil      :   一些常用的公有方法

LGApplications/Util/UIDefines.h :   常用的宏

注:       里面用到最常用的两个框架SDWebImage 和 Masonry

申明:     项目内容仅供参考,使用过程中带来任何bug,概不负责

目前比较流行的一中页面结构, 上面头部, 下面两个tableView可以左右切换 效果图如下:

![image](https://github.com/MrLee767201403/ScrollViews/blob/master/scrollViews.gif)

实现思路见我的博客:http://mp.blog.csdn.net/postedit/79421768


