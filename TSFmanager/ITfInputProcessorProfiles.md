### [ITfInputProcessorProfiles](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfinputprocessorprofiles)

文本服务语言配置，用来操作一个或多个文本服务的语言配置文件。

方法|描述
-|-
[Register][1]						|注册输入法。
[AddLanguageProfile][2]				|设置语言属性。
[GetCurrentLanguage][3]				|获取当前活动语言的标识符。
[GetDefaultLanguageProfile][4]		|获取特定语言的默认配置文件。
[RemoveLanguageProfile][5]			|删除语言配置文件。
[EnableLanguageProfile][6]			|启用或禁用当前用户的语言配置文件。
[EnableLanguageProfileByDefault][7]	|默认情况下，为所有用户启用或禁用语言配置文件。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-register
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-addlanguageprofile
[3]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-getcurrentlanguage
[4]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-getdefaultlanguageprofile
[5]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-removelanguageprofile
[6]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-enablelanguageprofile
[7]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfinputprocessorprofiles-enablelanguageprofilebydefault