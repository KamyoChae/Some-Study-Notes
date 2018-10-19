生成随机小数很棒，但随机数更有用的地方在于生成随机整数。

- 用 Math.random() 生成一个随机小数。
- 把这个随机小数乘以 20。
- 用 Math.floor() 向下取整 获得它最近的整数。
记住 Math.random() 永远不会返回 1。同时因为我们是在用 Math.floor() 向下取整，所以最终我们获得的结果不可能有 20。这确保了我们获得了一个在0到19之间的整数。

把操作连缀起来，代码类似于下面：

Math.floor(Math.random() * 20);

我们先调用 Math.random()，把它的结果乘以20，然后把上一步的结果传给 Math.floor()，最终通过向下取整获得最近的整数。

任务
生成一个 0 到 9之间的随机整数。

```javascript
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function myFunction() {

  // 请把你的代码写在这条注释以下

  return Math.floor(Math.random() * 10) ;
}

```