# model
jquery 模拟弹出层

##### 欢迎你的到访！

这是我自已写的一个小插件，模拟alert、confirm弹出框；个人刚开始学着写插件，有什么不足的欢迎指教！

可以点这个链接看效果 [DEMO](http://zijingwang.github.io/model/)

##### 调用方法：
	$.alert(text, [title, callbackOk])
   	text —— string. Alert文本
 		title —— string. options. Alert modal 标题
 		callbackOk —— function. options. 在Alert modal下，当用户点击“Ok”按钮时，回调函数将被执行
 
 	$.confirm(text, [title, callbackOk, callbackCancel])
   	text —— string. Alert文本
 		title —— string. options. Alert modal 标题
 		callbackOk —— function. options. 在Alert modal下，当用户点击“ok”按钮时，回调函数将被执行
 		callbackCancel —— function. options. 在Alert modal下，当用户点击“cancel”按钮时，回调函数将被执行
 		
