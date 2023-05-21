### 由TSF管理器实现的接口

接口																		|描述
-|-
[ITfInputProcessorProfiles](TSFmanager/ITfInputProcessorProfiles.md)	|文本服务语言配置操作，注册输入法。
[ITfThreadMgr](TSFmanager/ITfThreadMgr.md)								|线程管理器，主要用于安装事件接收器和获取文档管理器。
[ITfSource](TSFmanager/ITfSource.md)									|事件安装器，用于安装事件接收器。
[ITfDocumentMgr](TSFmanager/ITfDocumentMgr.md)							|文档管理器，主要用来创建和管理上下文。
[ITfEditRecord](TSFmanager/ITfEditRecord.md)							|编辑记录，用来确定编辑会话期间更改的内容。
[IEnumTfRanges](TSFmanager/IEnumTfRanges.md)							|范围枚举器，枚举范围对象。