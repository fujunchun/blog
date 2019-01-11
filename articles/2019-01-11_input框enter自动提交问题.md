当表单中只存在一个input框时，使用enter键，会使表单自动提交，这是浏览器默认行为

解决方案：
1. 新增一个input，使其隐藏
2. 监听事件, `keypress`，在回调中判断键值，如果是enter键，则return false
