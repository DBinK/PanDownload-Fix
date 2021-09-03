# 下载失败，出现错误

---

出现下载错误的原因有很多，出错时会在软件底部和日志里输出错误信息，可根据错误信息进行排查

常见错误：

①校验失败

文件已下载完成，但是有损坏，这个主要是百度服务器的问题，请尝试[修改下载方式](../document/settings.md)重新下载，或者使用[其他方法](../faq/slow.md)下载

> 如果是视频文件出现校验失败一般不会影响观看，可以把下载好的文件重命名，再把下载任务删除（注意！直接删除任务会把已经下载好的文件一起删除）
>
> 压缩文件出现损坏可以尝试修复，如果修复失败只能重新下载

②user is not authorized, hitcode:117，The response status is not successful. status=403

账号被限速，解决方法参考：[http://pandownload.net/faq/slow.html](../faq/slow.md)

③lua 调用失败

说明使用的 lua 扩展出错了，可以先尝试更新到该扩展的最新版本重试，如果该扩展的最新版本仍然报错，请配上日志联系该扩展的作者进行修复。(`默认`通道的扩展脚本由本站进行维护,其他扩展脚本请自行找到扩展作者)