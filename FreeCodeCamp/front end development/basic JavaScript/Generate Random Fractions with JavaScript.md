计算机的行为只有两种：确定性和随机性。当你一步步地闯关来到这里就是确定行为，当你随意点了个链接就来到这里就是随机行为。

而随机数最适合用来创建这种随机行为。

Math.random()用来生成一个在0(包括0)到1(不包括1)之间的随机小数，因此Math.random()可能返回0但绝不会返回1。

提示
随后的函数都会在return执行前调用，所以我们可以直接返回Math.random()的值。

任务
更改myFunction 来生成一个随机数取代 0。

```javascript
function myFunction() {

  // 请把你的代码写在这条注释以下

  
  return Math.random();

  // 请把你的代码写在这条注释以上
}

```
