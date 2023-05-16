### [ITfTextEditSink](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itftexteditsink)

编辑会话完成消息接收器，当编辑会话完成时，TSF管理器调用此接口。

方法|描述
-|-
[OnEndEdit][1]			|当ITfEditSession:DoEditSession()方法完成时，TSF管理器将调用此方法。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itftexteditsink-onendedit