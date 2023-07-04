### 由文本服务实现的接口

接口																			|描述
-|-
[ITfTextInputProcessor](TextService/ITfTextInputProcessor.md)				|文本输入处理器，激活和停用文本服务。
[ITfThreadMgrEventSink](TextService/ITfThreadMgrEventSink.md)				|线程管理器事件接收器，主要捕获焦点事件。
[ITfTextEditSink](TextService/ITfTextEditSink.md)							|编辑会话完成消息接收器，当编辑会话完成时，TSF管理器调用此接口。
[ITfLangBarItem](TextService/ITfLangBarItem.md)								|语言栏项信息，由语言栏管理器用来获取语言栏项的详细信息。
[ITfLangBarItemButton](TextService/ITfLangBarItemButton.md)					|语言栏按钮项信息，由语言栏管理器用来获取语言栏上的按钮项信息。
[ITfEditSession](TextService/ITfEditSession.md)								|编辑会话，由TSF管理器调用，用来修改上下文的文本和属性。
[ITfKeyEventSink](TextService/ITfKeyEventSink.md)							|键盘事件接收器，用于接收按键和保留键事件。
[ITfCompositionSink](TextService/ITfCompositionSink.md)						|输入组合终止消息接收器，用于在终止ITfComposition输入组合时接收通知。
[ITfDisplayAttributeProvider](TextService/ITfDisplayAttributeProvider.md)	|显示属性提供者，由TSF管理器用来枚举和获取单个显示属性信息对象。
[ITfDisplayAttributeInfo](TextService/ITfDisplayAttributeInfo.md)			|显示属性信息对象，为应用程序提供显示属性信息。
[IEnumTfDisplayAttributeInfo](TextService/IEnumTfDisplayAttributeInfo.md)	|显示属性信息对象枚举器，官方文档称此接口由TSF管理器实现。
[ITfContextKeyEventSink](TextService/ITfContextKeyEventSink.md)				|上下文键盘事件接收器，用于接收输入上下文中发生的键盘事件通知，保留的键事件和筛选的键事件不会传递到ITfContextKeyEventSink事件接收器。
[ITfTextLayoutSink](TextService/ITfTextLayoutSink.md)						|文本布局消息接收器，通过跟踪布局更改消息，实现光标跟随。