### [ITfUIElementMgr](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfuielementmgr)

UI元素管理器，文本服务调用ITfUIElementMgr，向应用程序提供UI元素。

方法						|描述
-|-
[BeginUIElement][1]		|在显示UI之前由文本服务调用，确定是否应显示文本服务的UI。
[UpdateUIElement][2]	|必须更新UI元素时，文本服务会调用ITfUIElementMgr::UpdateUIElement方法。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfuielementmgr-beginuielement
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfuielementmgr-updateuielement