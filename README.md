# ThreeKingdoms
Android手机平台应用开发课程期中项目作业

# Project Design 

### 应用的主界面由三个Fragment组成，同时含有抽屉导航。

三个fragment分别是 三国志， 群英会，风云录

### 三国志 

展示一些群英会的战斗记录，战斗记录可来自不用用户，不需要提供注册登录，只要下载安装了本App，并且能够联网就能使用。用户只要刷新“三国志”的界面就能看到最新的一些对决记录。

### 群英会

选择本地英雄进行对决，首先用户需要绑定自己的英雌，开始与系统的英雄对决，系统出战的英雄由随机产生。用户每次对决结束的对决记录都会被发送到云端存储（或者本地存储），而在“”三国志”的界面就可以看到用户对决的记录。

为了进行对决，需要一些英雄的属性来决定如何对决：

属性：

血槽指数（1-100）

攻击能力（一次伤害能减少对方多少血槽）

士兵数量：

粮草：

级别：

游戏逻辑：



### 风云录

卡片式布局，点击卡片会跳转到该任务的相信信息界面。

卡片有简单的图片加英雄名字构成，上面是图片，下面是名字。

UI优化：考虑背景和配色方案。


### 人物详情界面：


# Get Start

ThreeKingdoms/app/src/main/java/com/example/jiamoufang/threekingdoms/

```
  -- activities	//所有活动
    -- HeroDetailsActivity.java
  -- adapter  //所有适配器
    -- HeroAdapter.java
  -- fragment	 //三个Fragment
    -- HerosListFragment.java	
    -- HerosPKFragment.java
    -- HitHeroFragment.java
  -- heros	 //人物英雄类
   -- Hero.java
  -- MainActivity.java
```





