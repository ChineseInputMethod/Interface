### [ITfKeyEventSink](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfkeyeventsink)

键盘事件接收器，用于接收按键和保留键事件。

方法|描述
-|-
[OnKeyDown][1]			|输入法一般处理按键按下事件。
[OnPreservedKey][2]		|当注册的保留键被按下时，TSF管理器调用此函数。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfkeyeventsink-onkeydown
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfkeyeventsink-onpreservedkey