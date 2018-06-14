# 仿QQWeb即时聊天系统功能

- 聊天室登录、退出功能。登陆时，浏览器自动向服务器发起WebSocket连接，退出时自动切断
- 登陆后，用户可查看到聊天室在线的用户列表，服务器端通过一个hashmap始终记录了当前在线的用户列表
- 登陆的用户可以点击一个在线的其他用户，并给他发送消息，消息先提交给服务器，再通过服务器转发给另一端用户
- 支持群发消息的功能，使用时，服务器会将收到的消息群发给当前在线的所有用户
- 添加好友上线提醒和下线提醒功能，当有好友上线或下线时自动通知所有其他在线用户

登陆页面：

![login](https://github.com/SorrySaury/WebChat/blob/master/images/login.png)

主页面：
![chatroom](https://github.com/SorrySaury/WebChat/blob/master/images/%E7%A7%81%E8%81%8A%E7%BE%A4%E8%81%8A.png)
