# 五角星的绘制原理
![image](https://github.com/jessalin737/js-demo-css-canvas/blob/master/SRS24J%40%601QAAN4TZBM~%24B%7DN.png)
* 如上图所示先根据规律绘制出在大圆R上的点，小圆r上的点，每个点之间的间隔是72度，利用for循环先绘制出这些点
# 密码强度校验的具体逻辑
一、密码长度：

* 5 分: 小于等于4 个字符
* 10 分: 5 到7 字符
* 25 分: 大于等于8 个字符

二、字母：

* 0 分: 没有字母
* 10 分: 全都是小（大）写字母
* 20 分: 大小写混合字母

三、数字:

* 0 分: 没有数字
* 10 分: 1 个数字
* 20 分: 大于1 个数字

四、符号:

* 0 分: 没有符号
* 10 分: 1 个符号
* 25 分: 大于1 个符号

五、奖励:

* 2 分: 字母和数字
* 3 分: 字母、数字和符号
* 5 分: 大小写字母、数字和符号

1.2 方案1等级划分
根据密码评分，将密码划分成以下7个等级：
>= 90: 非常安全（VERY_SECURE）
>= 80: 安全（SECURE）
>= 70: 非常强（VERY_STRONG）
>= 60: 强（STRONG）
>= 50: 一般（AVERAGE）
>= 25: 弱（WEAK）
>= 0:  非常弱（ VERY_WEAK）
