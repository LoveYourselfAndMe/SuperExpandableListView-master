修改每次点击增加条目bug,自己修改布局

下面是原作者笔记
昨天有个朋友问我有没有用过ExpandableListView，他说他们要做个类似QQ的联系人的页面，需要用到ExpandableListView，但是他们的group和child里面的数据是分开的，他想的是，刚进来的时候，加载group的数据，然后点击每个group的时候，请求child的数据，然后加载完再展开。现在网上找的一些demo都是直接加载全部的，所以让我写个demo玩玩。因为没有设计稿，我就模仿QQ的联系人做了一次demo。
下面是效果图：![image](https://github.com/MZCretin/SuperExpandableListView/blob/master/gif/ezgif.com-video-to-gif.gif)
感谢原作者