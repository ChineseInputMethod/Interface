### [ITfCategoryMgr](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfcategorymgr)

类别管理器，为输入法管理类别。

方法							|描述
-|-
[RegisterCategory][1]		|将相应的GUID添加到Windows注册表中的指定类别。
[EnumItemsInCategory][2]	|获取一个IEnumGUID接口，该接口枚举指定类别中包含的所有GUID。
[RegisterGUID][3]			|将GUID添加到内部表，并获取GUID的原子。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcategorymgr-registercategory
[2]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcategorymgr-enumitemsincategory
[3]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfcategorymgr-registerguid