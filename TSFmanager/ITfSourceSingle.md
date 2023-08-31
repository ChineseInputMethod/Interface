### [ITfSourceSingle](https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nn-msctf-itfsourcesingle)

单一事件安装器，与ITfSource的不同之处在于，ITfSourceSingle安装的事件接收器一次仅支持一个事件接收器。

方法						|描述
-|-
[AdviseSingleSink][1]	|当参数是IID_ITfFunctionProvider时，将客户端注册为函数提供程序。

[1]: https://learn.microsoft.com/zh-cn/windows/win32/api/msctf/nf-msctf-itfsourcesingle-advisesinglesink