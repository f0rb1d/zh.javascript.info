importance: 4

---

# 许多天之前是该月的哪一天？

写一个函数 `getDateAgo(date, days)`，返回特定日期 `date` 往前 `days` 天数后，是当月的哪一天。

举个例子，今天是 20 号，那么 `getDateAgo(new Date(), 1)` 应该是 19 号，`getDateAgo(new Date(), 2)` 应该是 18 号。

<<<<<<< HEAD:1-js/05-data-types/10-date/4-get-date-ago/task.md
跨月、年也应该是正确输出：
=======
Should work reliably for `days=365` or more:
>>>>>>> ec21af8aef6930388c06ee4cd8f8f6769f9d305b:1-js/05-data-types/11-date/4-get-date-ago/task.md

```js
let date = new Date(2015, 0, 2);

alert( getDateAgo(date, 1) ); // 1, (1 Jan 2015)
alert( getDateAgo(date, 2) ); // 31, (31 Dec 2014)
alert( getDateAgo(date, 365) ); // 2, (2 Jan 2014)
```

另：函数不能修改给定的 `date` 值。