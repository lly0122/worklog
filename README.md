# Worklogs

# **2016**

### *Date: 2 - 29 (一)*

#### Plan:

- 完善大转盘编辑、预览页面

  `> 调试细节问题，下午与后端调试接口数据`
  
#### Mark:

- 上午调试大转盘抽奖发现百分比控制的元素大小或距离会有小数上的偏差，类似于 `rem` 产生的 [小像素问题](http://taobaofed.org/blog/2015/11/04/mobile-rem-problem/){:target="_blank"}。

- 下午调试大转盘指针在指向抽奖结果那格区域的随机摆动角度，并没有与后端调试接口数据，后端还是一片混乱，各种报错，无法调试状态。

- [大转盘抽奖](http://monine.github.io/study/public/lottery_dzp.html){:target="_blank"}

### *Date: 2 - 26 (五)*

#### Plan:

- 预览页面大转盘抽奖功能

  `> 实现用户点击抽奖按钮之后，调用接口获得抽奖结果数据并且大转盘保持转动，直到抽奖结果返回再停止转动。`
  
  `> 保证大转盘转动动画效果流畅自然`

#### Mark:

- 上午调休两个小时

### *Date: 2 - 25 (四)*

#### Plan:

- 抽奖功能完善 

  `> 根据后端接口数据调整 JS 代码`
  
- 5.4.0 版本发布

#### Mark:

- 因为版本发布加班到凌晨 12 点

- 军哥介绍了一个替代 [f5](http://getf5.com/) 的前端开发工具 [Puer](http://leeluolee.github.io/2014/10/24/use-puer-helpus-developer-frontend)

  `> Puer 是一个可以实时编辑刷新的前端服务器`

- 阅读了一些关于 [js 内存泄漏](http://www.ibm.com/developerworks/cn/web/wa-jsmemory) 的相关知识
