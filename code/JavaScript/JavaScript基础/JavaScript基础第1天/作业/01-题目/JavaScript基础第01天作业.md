# 一、每日作业-JavaScript第01天

## 客观题

https://ks.wjx.top/vm/YXyjrAe.aspx# 
或者扫码来做题

 <img src="images/qrcode.jpg">

## 简答题

1. 请说出变量的使用场景？

~~~ 存储

~~~

2. 请说出基本数据类型有哪5种？

~~~ number string boolean undefined null 

~~~

3. 请说出模板字符串使用方法？

~~~
	
~~~

4. 下面代码输入结果是？ （） 

```javascript
   const  num = 10
   console.log( num + 11) // 21
   console.log( num + '11') // '1011'
   console.log( num +  +'11') // 21
```

5. 下面代码输入结果是？ （）

```javascript
const  num = 10
console.log( typeof num + '11') // string
console.log( typeof (num + '11')) // string
console.log( typeof (num +  +'11')) // number
```

## 编程题

### 获取用户信息

- 题目描述

  依次询问并获取用户的姓名、年龄、性别，收集数据之后在控制台依次打印出来。

  具体表现如下图：


<img src="images/图片1.png">

<img src="images/图片4.png">

- 题目提示
  - 通过prompt来弹出提示框，收集用户信息
  - 通过变量保存数据

### 增加年龄

- 题目描述

  1、询问用户年龄，用户输入年龄后，把用户输入的年龄增加5岁

  2、增加5岁后，通过弹出框提示用户 “ 据我估计，五年后，你可能XX岁了”

  <img src="images/图片5.png">

  <img src="images/图片6.png">

- 题目提示

  - 通过prompt来弹出提示框，收集用户信息
  - 通过变量保存数据
  - 转换数据类型(需要预习第二天的数据类型转换哟)

### 计算银行卡余额案例

- 题目描述

  1、用户输入总的银行卡金额，依次输入本月花费的电费，水费，网费。

  2、页面打印一个表格，计算出本月银行卡还剩下的余额。

  <img src="images/111.gif">


- 题目提示

  - 思路：

    1.我们需要5个变量：银行卡总额、水费、电费、网费、银行卡余额

    2.银行卡余额= 银行卡总额 – 水费 –电费  - 网费  

    3.第一步准备5个变量接受输入的数据

    4.第二步计算银行卡余额 

    5.第三步页面打印生成表格，里面填充数据即可。

    6.当然可以提前把html页面搭好。

关于pink老师抖音，领取学习路线图、面试宝典以及八大学科的基础视频哦~~

<img src="images/pink.jpg">

23123