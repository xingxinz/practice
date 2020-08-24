# practice
1.求输出
var output = [];
    
    for (var i = 0; i < 10; i++) {
      output.push(() => console.log(i))
    }
    
    output.forEach(task => task());

2.如何判断Array类型
arr.splice(0)
Arr.length

3.promise1 = promise0.then(succ, fail)
返回值类型

4.function flat(arr) {
}
数组展平
flat([1, [2, 3, [4]]]) = [1, 2, 3, 4]

5.实现bind
实现bind

Function.prototype.bind = function (self, ...args) {
// 实现
}
