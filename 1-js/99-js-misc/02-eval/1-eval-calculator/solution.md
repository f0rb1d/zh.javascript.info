<<<<<<< HEAD
让我们用 `eval` 函数来计算数学表达式：
=======
Let's use `eval` to calculate the maths expression:
>>>>>>> ec21af8aef6930388c06ee4cd8f8f6769f9d305b

```js demo run
let expr = prompt("Type an arithmetic expression?", '2*3+2');

alert( eval(expr) );
```

<<<<<<< HEAD
不过，用户也可以输入文本或者代码。

安全起见，我们可以用 [regular expression](info:regular-expressions) 来检查 `eval` 函数以限制用户只能输入算数表达式，这样输入的内容只能包含数字和运算符。
=======
The user can input any text or code though.

To make things safe, and limit it to arithmetics only, we can check the `expr` using a [regular expression](info:regular-expressions), so that it only may contain digits and operators.
>>>>>>> ec21af8aef6930388c06ee4cd8f8f6769f9d305b