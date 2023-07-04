### 接口

- [由TSF管理器实现的接口](TSFmanager.md)

- [由语言栏实现的接口](LanguageBar.md)

- [由文本服务实现的接口](TextService.md)

>索引

接口|指称|实现
-|-|-
IAnchor|片段标签|TSF管理器
IEnumITfCompositionView|输入组合查看对象枚举器|
IEnumTfCandidates|候选文字串对象枚举器|
IEnumTfContexts|上下文枚举器|
IEnumTfContextViews
[IEnumTfDisplayAttributeInfo](TextService/IEnumTfDisplayAttributeInfo.md)|显示属性信息对象枚举器|文本服务
IEnumTfDocumentMgrs文档管理器对象枚举器
IEnumTfFunctionProviders功能提供者对象枚举器
IEnumTfLangBarItems语言栏项枚举器
IEnumTfLanguageProfiles语言配置枚举器
IEnumTfLatticeElements单元格枚举器
IEnumTfProperties属性对象枚举器
IEnumTfPropertyValue属性值枚举器
[IEnumTfRanges](TSFmanager/IEnumTfRanges.md)|文本范围枚举器|TSF管理器
ISoftKbd
ITextStoreACP|ACP式文本操作
ITextStoreACP2
ITextStoreACPServices|ACP式文本服务
ITextStoreACPSink|ACP式文本操作事件接收器
ITextStoreAnchor文本存储片段标签
ITextStoreAnchorSink文本存储片段标签事件接收器
ITfActiveLanguageProfileNotifySink语言配置激活消息接收器
ITfCandidateList候选列表对象
ITfCandidateString候选文字串对象
[ITfCategoryMgr](TSFmanager/ITfCategoryMgr.md)|类别管理器|TSF管理器
ITfCleanupContextDurationSink上下文清除后消息接收器
ITfCleanupContextSink上下文清除中消息接收器
ITfClientId获取客户端标识符
[ITfCompartment](TSFmanager/ITfCompartment.md)|公共缓冲池|TSF管理器
ITfCompartmentEventSink公共缓冲池事件接收器
[ITfCompartmentMgr](TSFmanager/ITfCompartmentMgr.md)|公共缓冲池管理器|TSF管理器
[ITfComposition](TSFmanager/ITfComposition.md)|输入组合|TSF管理器
[ITfCompositionSink](TextService/ITfCompositionSink.md)|输入组合终止消息接收器|文本服务
ITfCompositionView输入组合查看对象
ITfConfigureSystemKeystrokeFeed按键处理管理
[ITfContext](TSFmanager/ITfContext.md)|上下文|TSF管理器
[ITfContextComposition](TSFmanager/ITfContextComposition.md)|上下文输入组合|TSF管理器
[ITfContextKeyEventSink](TextService/ITfContextKeyEventSink.md)|上下文键盘事件接收器|文本服务
ITfContextOwner上下文所有者
ITfContextOwnerCompositionServices上下文所有者输入组合服务
ITfContextOwnerCompositionSink上下文所有者输入组合消息接收器
ITfContextOwnerServices上下文所有者服务
[ITfContextView](TSFmanager/ITfContextView.md)|上下文视图对象|TSF管理器
ITfCreatePropertyStore创建属性存储
[ITfDisplayAttributeInfo](TextService/ITfDisplayAttributeInfo.md)|显示属性信息|文本服务
ITfDisplayAttributeMgr显示属性管理器
ITfDisplayAttributeNotifySink显示属性消息接收器
[ITfDisplayAttributeProvider](TextService/ITfDisplayAttributeProvider.md)|显示属性提供者|文本服务
[ITfDocumentMgr](TSFmanager/ITfDocumentMgr.md)|文档管理器|TSF管理器
[ITfEditRecord](TSFmanager/ITfEditRecord.md)|编辑记录|TSF管理器
[ITfEditSession](TextService/ITfEditSession.md)|编辑会话|文本服务
ITfEditTransactionSink编辑事务消息接收器
ITfFnAdviseText文本消息接收器
ITfFnBalloon气泡项更新
ITfFnConfigure文本服务自配选项设置对话框
ITfFnConfigureRegisterWord候选文字注册对话框
ITfFnGetLinguisticAlternates
ITfFnGetPreferredTouchKeyboardLayout
ITfFnGetSAPIObject获取语音应用编程接口对象
ITfFnLMInternal
ITfFnLMProcessor语言模型处理器
ITfFnPlayBack语音数据控制
ITfFnPropertyUIStatus属性UI状态控制
ITfFnReconversion文本恢复功能
ITfFnSearchCandidateProvider
ITfFnShowHelp文本服务自配帮助信息
ITfFunction扩展功能对象
ITfFunctionProvider扩展功能提供者
ITfIntegratableCandidateListUIElement
[ITfInputProcessorProfiles](TSFmanager/ITfInputProcessorProfiles.md)|文本服务语言配置操作|TSF管理器
ITfInputProcessorProfilesEx设置文本服务语言配置的显示名称
ITfInputProcessorProfileSubstituteLayout文本服务配置的键盘布局操作
ITfInputScope定向输入识别类型
[ITfInsertAtSelection](TSFmanager/ITfInsertAtSelection.md)|在选定位置插入内容|TSF管理器
[ITfKeyEventSink](TextService/ITfKeyEventSink.md)|键盘事件接收器|文本服务
[ITfKeystrokeMgr](TSFmanager/ITfKeystrokeMgr.md)|按键管理器|TSF管理器
ITfKeyTraceEventSink按键跟踪事件接收器
ITfLangBarEventSink语言栏事件接收器
[ITfLangBarItem](TextService/ITfLangBarItem.md)|语言栏项信息|文本服务
ITfLangBarItemBalloon语言栏气泡项信息
ITfLangBarItemBitmap语言栏位图项信息
ITfLangBarItemBitmapButton语言栏位图按钮项信息
[ITfLangBarItemButton](TextService/ITfLangBarItemButton.md)|语言栏按钮项信息|文本服务
[ITfLangBarItemMgr](LanguageBar/ITfLangBarItemMgr.md)|语言栏项管理器|语言栏
[ITfLangBarItemSink](LanguageBar/ITfLangBarItemSink.md)|语言栏项消息接收器|语言栏
ITfLangBarMgr语言栏管理器
ITfLanguageProfileNotifySink语言配置消息接收器
ITfLMLattice提供语音栅格属性
[ITfMenu](LanguageBar/ITfMenu.md)|语言栏菜单扩展|语言栏
ITfMessagePump消息抽取
ITfMouseSink鼠标事件消息接收器
ITfMouseTracker鼠标事件消息接收器管理
ITfMouseTrackerACP|ACP应用程序鼠标事件消息接收器管理
ITfMSAAControl微软辅助功能应用控制
ITfPersistentPropertyLoaderACP属性的异步载入
ITfPreservedKeyNotifySink按键保护消息接收器
[ITfProperty](TSFmanager/ITfProperty.md)|属性设置|TSF管理器
ITfPropertyStore属性存储
ITfQueryEmbedded询问可否嵌入
[ITfRange](TSFmanager/ITfRange.md)|文本范围|TSF管理器
ITfRangeACP|为ACP应用程序使用的文本范围
ITfRangeBackup文本范围备份
ITfReadOnlyProperty只读属性
ITfReverseConversion
ITfReverseConversionList
ITfReverseConversionMgr
[ITfSource](TSFmanager/ITfSource.md)|事件安装器|TSF管理器
ITfSourceSingle单一事件安装器
ITfSpeechUIServer语音用户界面服务器
ITfStatusSink文档状态消息接收器
ITfSystemDeviceTypeLangBarItem系统驱动类型语言栏项目应用
ITfSystemLangBarItem系统语言栏项应用扩展
ITfSystemLangBarItemSink系统语言栏项扩展槽
[ITfTextEditSink](TextService/ITfTextEditSink.md)|编辑会话完成消息接收器|文本服务
[ITfTextInputProcessor](TextService/ITfTextInputProcessor.md)|文本输入处理器|文本服务
[ITfTextLayoutSink](TextService/ITfTextLayoutSink.md)|文本布局消息接收器|文本服务
ITfThreadFocusSink线程输入焦点消息接收器
[ITfThreadMgr](TSFmanager/ITfThreadMgr.md)|线程管理器|TSF管理器
ITfThreadMgr2
[ITfThreadMgrEventSink](TextService/ITfThreadMgrEventSink.md)|线程管理器事件接收器|文本服务
ITfThreadMgrEx
ITfToolTipUIElement
ITfTransitoryExtensionSink
ITfTransitoryExtensionUIElement
ITfUIElement
ITfUIElementMgr
ITfUIElementSink
IUIManagerEventSink