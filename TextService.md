### 由文本服务实现的接口

接口																|描述
-|-
[ITfTextInputProcessor](TextService/ITfTextInputProcessor.md)	|文本输入处理器，激活和停用文本服务。
[ITfThreadMgrEventSink](TextService/ITfThreadMgrEventSink.md)	|线程管理器事件接收器，主要捕获焦点事件。
[ITfTextEditSink](TextService/ITfTextEditSink.md)				|编辑会话完成消息接收器，当编辑会话完成时，TSF管理器调用此接口。
[ITfLangBarItem](TextService/ITfLangBarItem.md)					|语言栏项信息，由语言栏管理器用来获取有关语言栏项的详细信息。
[ITfLangBarItemButton](TextService/ITfLangBarItemButton.md)		|语言栏按钮项信息，由语言栏管理器用来获取有关语言栏上的按钮项的信息。