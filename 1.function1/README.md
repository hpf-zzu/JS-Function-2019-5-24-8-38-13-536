## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：将一个字符串逆序输出。

```
function reverseString(message){
  // wirte your code here
  var stack = [];
				for(var len = message.length,i = len; i >= 0; i --){
					stack.push(message[i]);
				}
				return stack.join('');
}
reverseString('hello'); // should return 'olleh'
```
