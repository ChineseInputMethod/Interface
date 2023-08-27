### [ITfComposition](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfcomposition)

输入组合，用于终止ITfComposition输入组合和操作输入组合的ITfRange文本范围。

方法					|描述
-|-
[EndComposition][1]	|终止ITfComposition输入组合。（官方文档说，随后由上下文的所有者释放ITfComposition输入组合）
[GetRange][2]		|获取一个范围对象，该对象包含合成所涵盖的文本。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcomposition-endcomposition
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcomposition-getrange