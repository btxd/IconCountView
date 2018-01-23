# IconCountView
该项目是 《[HenCoder「仿写酷界面」活动](https://zhuanlan.zhihu.com/p/30075481)》点赞效果的投稿

#### 即刻点赞效果

![](http://wx1.sinaimg.cn/mw1024/7b3eaa29gy1fkmpwbyrgcg20a006o4gc.gif)


#### 2017.10.23更新
为了增强实际的应用性， 增加了当数量为0的时候， 显示文字的功能，效果如下：
![](http://wx2.sinaimg.cn/mw690/7b3eaa29gy1fksifgls9xg20a006o1ky.gif)

#### 2017.10.25更新
增加文字颜色的设置： 

![](http://wx2.sinaimg.cn/mw690/7b3eaa29gy1fkux3v9le3g20a006o7wi.gif)

### 配置
```
<com.sunbinqiang.iconcountview.IconCountView
        android:id="@+id/praise_view2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        app:count="0"
        app:checked="false"
        app:zeroText="收藏"
        app:textNormalColor="@color/text_gray"
        app:textSelectedColor="@color/text_selected"
        app:textSize="12sp"
        app:normalRes="@drawable/icon_collect_normal1"
        app:selectedRes="@drawable/icon_collect_selected1"/>
```
