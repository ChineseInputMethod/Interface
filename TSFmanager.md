### 由TSF管理器实现的接口

接口																		|描述
-|-
[ITfInputProcessorProfiles](TSFmanager/ITfInputProcessorProfiles.md)	|文本服务语言配置操作，注册输入法。
[ITfThreadMgr](TSFmanager/ITfThreadMgr.md)								|线程管理器，主要用于安装事件接收器和获取文档管理器。
[ITfSource](TSFmanager/ITfSource.md)									|事件安装器，用于安装事件接收器。
[ITfDocumentMgr](TSFmanager/ITfDocumentMgr.md)							|文档管理器，主要用来创建和管理上下文。
[ITfEditRecord](TSFmanager/ITfEditRecord.md)							|编辑记录，用来确定编辑会话期间更改的内容。
[IEnumTfRanges](TSFmanager/IEnumTfRanges.md)							|范围枚举器，枚举文本范围对象。
[ITfContext](TSFmanager/ITfContext.md)									|上下文，用来创建和管理编辑上下文。
[ITfInsertAtSelection](TSFmanager/ITfInsertAtSelection.md)				|在选定位置插入内容，用于在上下文中插入文本或嵌入对象。
[ITfRange](TSFmanager/ITfRange.md)										|文本范围，用来引用和操作给定上下文中的文本。
[ITfCategoryMgr](TSFmanager/ITfCategoryMgr.md)							|类别管理器，为输入法注册类别。
[ITfKeystrokeMgr](TSFmanager/ITfKeystrokeMgr.md)						|按键管理器，主要用来安装键盘事件接收器和注册保留键。
[ITfCompartmentMgr](TSFmanager/ITfCompartmentMgr.md)					|公共缓冲池管理器，用于管理客户端之间的共享数据。
[ITfCompartment](TSFmanager/ITfCompartment.md)							|公共缓冲池，用于获取和设置公共缓冲池中的数据以及安装ITfCompartmentEventSink公共缓冲池事件接收器。
[ITfContextComposition](TSFmanager/ITfContextComposition.md)			|上下文输入组合，用于创建ITfComposition输入组合。
[ITfComposition](TSFmanager/ITfContextComposition.md)					|输入组合，用于终止ITfComposition输入组合和操作输入组合的ITfRange文本范围。