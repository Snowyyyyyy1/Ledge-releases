# Ledge Releases

[Ledge](https://github.com/Snowyyyyyy1/Ledge) 的发布仓库。安装包在 [Releases](../../releases),
应用内的更新检查也读这里。

源码仓库是私有的 —— 匿名读私有仓库的 releases 一律返回 404,与"还没发过版"无法区分,
而把 token 放进分发出去的客户端等于公开这个 token。所以产物发在这里。

## 安装

下载 `Ledge.zip`,解压后把 `Ledge.app` 拖进「应用程序」。

**首次打开需要右键点图标 →「打开」**,而不是双击。因为这个包是 ad-hoc 签名的,
没有 Apple Developer ID 证书(那需要付费会员),Gatekeeper 因此会拦一次。
选择「打开」之后,以后就可以正常双击了。

Ledge 需要**辅助功能**权限才能移动别的 App 的窗口 —— 首次启动会弹出系统授权请求。
它不会退出、也不要求重启,授权后自动就绪。

## 校验

每个版本都附带 `Ledge.zip.sha256`:

```
shasum -a 256 -c Ledge.zip.sha256
```
