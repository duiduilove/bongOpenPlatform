bong 开放平台
================

![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/cover.png?raw=true)

# 介绍

bong 开放平台可以提供接口，在用户授权的状况下提供用户的运动和睡眠数据给开发者，开发者可以向bong团队申请开发资格。

# 关于bong
bong是一款健康运动手环,详情请参见[bong](https://bong.cn/)官方主页.





# 目录

- [介绍](#介绍)
- [关于bong](#关于bong)
- [目录](#目录)
- [开发资格申请](#开发资格申请)
- [开发环境](#开发环境)
- [成为bong开发者你可以获得](#成为bong开发者你可以获得)
- [开放平台案例](#开放平台案例)
	- [bong时之战](#bong时之战)
- [开发文档](#开发文档)
	- [接口定义](#接口定义)
		- [UserData](#UserData)
		- [SleepBlock](#SleepBlock)
		- [bongBlock](#bongBlock)
		- [nobongBlock](#nobongBlock)		
- [版权声明](#版权申明)


# 开发资格申请

因为现在开放平台还处于内部测试阶段，感兴趣的开发者请直接添加微信bong开发者俱乐部，和我们聊聊你的想法。

````
比如下面的话题，但不限于下面话题：

- 申请理由：`比如，你想开发什么样的bong插件？为什么想开发这个插件？`
- 你做过的最hacker的事情：`比如，我开发过xxx APP，我自制过四轴直升飞机...`
````

现阶段，没有啥挑选原则，有爱的hacker们速度入。

![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/qrcode.jpg?raw=true)

]
# 开发环境
开放平台现在开放的是app内置的插件区域，插件区域以html5的形式通过用户授权来展现。


![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/setting1.jpg?raw=true)


![image](https://github.com/Ginshell/bongOpenPlatform/blob/master/documents/Setting2.jpg?raw=true)


# 成为bong开发者你可以获得...

- 每次bong有了重大的硬件软件更新你会最先获得通知，甚至可能我们会邮寄一个测试中的手环给你，帮助你完成插件的开发工作。

- 你可以通过用户使用你的插件获得一些**活跃点** [*活跃点有啥用？*](#活跃点有啥用)
  
  *tips: 你的插件能够帮助用户动得越多睡得越好，你获得的活跃点就会越多哦。* 
  
- 想玩软硬结合的Hacker，无需找硬件工程师配合了，申请成为bong开发者即可。


# 活跃点有啥用
- bong的活跃点可以用于 bong Shop 购买商品，包括 bong 、bong相关配件、bong售后服务等。
- 一个活跃点暂定约为1人民币。
- **注意：** 内测期间所有活跃点在正式推出后将清零 

# 如何获得活跃点
  如果用户不参加任何开发者的应用，他们也可以获得一些活跃点。用户使用bong，本身可获得的活跃点基本换算规则如下：
   <table class="table table-bordered table-striped table-condensed">
<tr>
<td> 单位 </td>
<td> 数量 </td>
<td> 活跃点 </td>
<td> 备注 </td>
</tr>

<tr>
<td> bong时间 </td>
<td> 10分钟 </td>
<td> 1 </td>
<td> 每积累10分钟，获得1个活跃点 </td>
</tr>

</table>


# 开放平台案例
## bong时之战

  [bong时之战](https://github.com/Ginshell/bongOpenPlatform/wiki/bong%E6%97%B6%E4%B9%8B%E6%88%98)是bong团队几位工程师为bong做的小插件。通过团队合作运动，用户们完成累积bong的时间达到目标值的目标。
  
  为了激励bong时之战开发者，现阶段bong提供给**bong时之战**开发者额外的10%优惠。
 
  **注意：** *优惠政策解释权归杭州攻壳科技有限公司所有，会根据市场的反馈作调整*
  
 <table class="table table-bordered table-striped table-condensed">
<tr>
<td> 单位 </td>
<td> 数量 </td>
<td> 活跃点 </td>
<td> 开发者优惠 </td>
<td> 备注 </td>
</tr>

<tr>
<td> bong时间 </td>
<td> 10分钟 </td>
<td> 1 </td>
<td> 10% </td>
<td> 每积累10分钟，获得1×(1+10%)的活跃点 </td>
</tr>

</table>

任务中所有的用户完成的bong时间对应的活跃点，都归开发者所有，**开发者有权利根据自己设计的小游戏的特性来自由分配这些点数**。

比如，在bong时之战这个案例中，开发者制定如下规则，成功完成任务的小组，可以获得55个活跃点。没有成功完成任务的小组，不能获得任何活跃点。

假设有2个小组参与了这个小游戏，其中：

- A小组，成功完成了任务。获得55个活跃点。（比不参加任务多获得55-42=13个活跃点)
- B小组，任务失败。总共运动了300分钟，获得0个活跃点。（比不参加任务少获得30个活跃点)

开发者可以获得

<table class="table table-bordered table-striped table-condensed">
<tr>
<td>  </td>
<td> 开发者总共获得 </td>
<td> 开发者分给用户 </td>
<td> 开发者最后获利 </td>
</tr>

<tr>
<td> 成功完成任务小组 </td>
<td> 42×(1+10%)=46.2 </td>
<td> 55 </td>
<td> -8.8 </td>
</tr>

<tr>
<td> 任务失败小组 </td>
<td> 30×(1+10%)=33 </td>
<td> 0 </td>
<td> 33 </td>
</tr>

<tr>
<td> 总计 </td>
<td> 79.2 </td>
<td> 55  </td>
<td> 24.2 </td>
</tr>

</table>
你的插件越有趣，越能帮助用户获得活跃点，就会有更多用户使用哦~

-------

当然，以上只是我们举的例子，各位Hacker们，快快开动你的智慧来玩转bong开放平台吧。

-----

# 开发文档

## 接口定义

> **注意** 现阶段bong主要采集的是睡眠数据和运动数据。在开发者获得用户的允许的情况下，可以获得**用户基本数据**、**睡眠数据**、**运动数据**、**不活跃数据**、**bong时间**四个大类目的基本数据，并根据自己的需要进行整合。

-------------
### **UserData** 
用户基本数据主要涵盖的是用户的一些基本情况
#### **UserId**
用户的ID
#### **UserName**
在bong使用的用户昵称
#### **Gender**
用户的性别
#### **BornYear**
用户的出生年
#### **SportTarget**
用户给自己设定的热量消耗目标
#### **SleepTarget**
用户给自己设定的睡眠长度目标
#### **isTied**
用户是否连接了bong手环

------------

### **SleepBlock**
bong开放平台能够提供某个用户的某一段睡眠，根据用户的ID和睡眠时间即可获得。

#### **ID**
一段睡眠的ID
#### **userId**
一段睡眠所属于的用户
#### **StartTime**
获取一段睡眠开始的时间
#### **EndTime**
获取一段睡眠结束的时间
#### **DSNum**
这一段睡眠的深睡眠总长
#### **LSNum**
这一段睡眠的浅睡眠总长
#### **WakeNum**
这一段睡眠的清醒时间总长
#### **WakeTimes**
这一段睡眠中间一共清醒过几次
##### **Score**
按照bong睡眠专家提供的睡眠分析方法，对这一段睡眠进行质量评分


-----------
### **bongBlock** 
bong开放平台能够提供某个用户的某一段运动，根据用户的ID和运动时间即可获得。

#### **userId**
这一段运动所属于的用户
#### **ID**
一段运动的ID
#### **StartTime**
获取开始的时间
#### **EndTime**
获取结束的时间
#### **subType**
这一段运动的综合类型
#### **calories**
消耗的能量
#### **steps**
一共走了多少步
#### **distance**
一共走了多远
#### **speed**
行走的速度



-----------

### **nobongBlock** 
bong开放平台能够提供某个用户的某一段非bong状态的情况，根据用户的ID和时间即可获得。

#### **userId**
这一段非bong所属于的用户
#### **ID**
一段非bong的ID
#### **StartTime**
获取开始的时间
#### **EndTime**
获取结束的时间
#### **subType**
这一段运动的综合类型
#### **calories**
消耗的能量
#### **steps**
一共走了多少步
#### **distance**
一共走了多远
#### **speed**
行走的速度
#### **actTime**
这一段的活跃时间
#### **nonActTime**
这一段的非活跃时间



-----------


版权声明
---------------



文档由bong团队提供，版权归杭州攻壳科技有限公司所有 
