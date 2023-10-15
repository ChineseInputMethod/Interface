### [ITfRange](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfrange)

文本范围，用来操作给定上下文中的文本。

方法						|描述
-|-
[SetText][1]			|替换文本范围涵盖的内容。
[Collapse][2]			|折叠起始或结束定位点到另一端。
[CompareStart][3]		|将此文本范围的起始定位点位置与其他区域中的定位点进行比较
[CompareEnd][4]			|将此文本范围的结束定位点位置与其他区域中的定位点进行比较。
[ShiftEndToRange][5]	|将此范围的结束定位点移动到另一个范围内的定位点。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfrange-settext
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfrange-collapse
[3]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfrange-comparestart
[4]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfrange-compareend
[5]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfrange-shiftendtorange