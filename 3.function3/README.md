## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：按字母表顺序输出传入的参数字符串。

```
function alphabetSort(message){
  // wirte your code here
  var arr = [];
  for(var i = 0; i < message.length; i ++){
				arr.push(message[i]);
			}
			return (arr.sort().join(''));
}
alphabetSort('hello'); // should return 'ehllo'
```
