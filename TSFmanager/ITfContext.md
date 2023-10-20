### [ITfContext](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfcontext)

上下文，用来创建和管理编辑上下文。

方法						|描述
-|-
[RequestEditSession][1]	|请求编辑会话，获取对文档文本和属性的访问权限。
[GetActiveView][2]		|获取上下文的活动视图。
[EnumProperties][3]		|获取文档属性枚举器。
[GetDocumentMgr][4]		|获取包含上下文的文档管理器。
[GetSelection][5]		|获取文档中的选定内容。
[GetStart][6]			|获取位于文档开头的文本范围。
[GetProperty][7]		|获取文本属性。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-requesteditsession
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-getactiveview
[3]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-enumproperties
[4]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-getdocumentmgr
[5]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-getselection
[6]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-getstart
[7]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcontext-getproperty