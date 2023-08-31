### 由TSF管理器实现的接口

接口																			|描述
-|-
[ITfInputProcessorProfiles](TSFmanager/ITfInputProcessorProfiles.md)		|文本服务语言配置操作，注册输入法。
[ITfInputProcessorProfileMgr](TSFmanager/ITfInputProcessorProfileMgr.md)	|文本服务语言配置管理器，管理键盘布局和文本服务，建议使用此接口注册输入法。
[ITfThreadMgr](TSFmanager/ITfThreadMgr.md)									|线程管理器，主要用于安装事件接收器和获取文档管理器。
[ITfSource](TSFmanager/ITfSource.md)										|事件安装器，用于安装事件接收器。
[ITfDocumentMgr](TSFmanager/ITfDocumentMgr.md)								|文档管理器，主要用来创建和管理上下文。
[ITfEditRecord](TSFmanager/ITfEditRecord.md)								|编辑记录，用来确定编辑会话期间更改的内容。
[IEnumTfRanges](TSFmanager/IEnumTfRanges.md)								|范围枚举器，枚举文本范围对象。
[ITfContext](TSFmanager/ITfContext.md)										|上下文，用来创建和管理编辑上下文。
[ITfInsertAtSelection](TSFmanager/ITfInsertAtSelection.md)					|在选定位置插入内容，用于在上下文中插入文本或嵌入对象。
[ITfRange](TSFmanager/ITfRange.md)											|文本范围，用来引用和操作给定上下文中的文本。
[ITfCategoryMgr](TSFmanager/ITfCategoryMgr.md)								|类别管理器，为输入法注册类别。
[ITfKeystrokeMgr](TSFmanager/ITfKeystrokeMgr.md)							|按键管理器，主要用来安装键盘事件接收器和注册保留键。
[ITfCompartmentMgr](TSFmanager/ITfCompartmentMgr.md)						|公共缓冲池管理器，用于管理客户端之间的共享数据。
[ITfCompartment](TSFmanager/ITfCompartment.md)								|公共缓冲池，用于获取和设置公共缓冲池中的数据以及安装ITfCompartmentEventSink公共缓冲池事件接收器。
[ITfContextComposition](TSFmanager/ITfContextComposition.md)				|上下文输入组合，用于创建ITfComposition输入组合。
[ITfComposition](TSFmanager/ITfComposition.md)								|输入组合，用于终止ITfComposition输入组合和操作输入组合的ITfRange文本范围。
[ITfProperty](TSFmanager/ITfProperty.md)									|属性设置，由客户端(应用程序或文本服务)用来修改显示属性。
[ITfContextView](TSFmanager/ITfContextView.md)								|上下文视图对象，由客户端(应用程序或文本服务)用来获取上下文视图的信息。
[IEnumTfProperties](TSFmanager/IEnumTfProperties.md)						|属性对象枚举器，用于枚举文档属性。
[ITfReadOnlyProperty](TSFmanager/ITfReadOnlyProperty.md)					|只读属性，ITfProperty继承此接口。
[ITfDisplayAttributeMgr](TSFmanager/ITfDisplayAttributeMgr.md)				|显示属性管理器，由应用程序用来获取和枚举显示属性。
[ITfSourceSingle](TSFmanager/ITfSourceSingle.md)							|单一事件安装器，与ITfSource的不同之处在于，ITfSourceSingle安装的事件接收器一次仅支持一个事件接收器。