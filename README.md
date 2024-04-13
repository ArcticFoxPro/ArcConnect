<div align="center" style="margin-top: 40px;margin-bottom: 20px;">
<img src="images/ArcConnect.png" width = "72%" />
</div>

<h1 align="center">狐云山脉</h1>

> “QQ”“腾讯 QQ”“腾讯”“微信”“WeChat”是深圳市腾讯计算机系统有限公司和/或其关联公司的商标。此仓库对“QQ”“腾讯 QQ”“腾讯”“微信”“WeChat”的使用旨在注明和指向对应主体，并非表示对“QQ”、“腾讯 QQ”、“腾讯”、“微信”、“WeChat”商标的注册和拥有。

> Android™ 是 Google LLC 的商标。

> Apple®、iPhone®、iPad®、Mac®、iMac®、Apple Watch®、AppleVision™、Apple Vision Pro™、iPadOS®、macOS®、visionOS™、watchOS® 是 Apple Inc. 的商标或注册商标。iOS 是 Cisco 的商标或注册商标。

## 介绍

## 信息

| 编号 | 描述 | 状态 | 备注 |
| --- | --- | --- | --- |
| Arc1 | 手势导航提示条（小白条）真沉浸 | 已在 Android QQ 9.0.25 版本全量上线，仅部分场景生效 ||
| Arc2 | ShortCuts（桌面图标长按菜单） | 已在 Android QQ 9.0.25 版本上线||
| Arc3 |系统通知快捷回复（RemoteInput API）|（Xiaomi HyperOS 适配受阻，小米三方应用外部支持和相关技术部门正在分析此问题）|在多个中国大陆 Android OEM 定制系统测试时，发现在基于 Android 14 的 Xiaomi HyperOS 设备和部分基于 Android 13 的 Xiaomi HyperOS 设备上调用 RemoteInput API 时，存在系统直接向 RemoteInput 返回“null”的问题，与 Android 预期逻辑和结果不符。|
| Arc4 | 边到边（edge-to-edge）软键盘动画（WindowInsetsAnimation API）|跟进中|Android QQ 9.0.35 版本 QQ 频道帖子详情页回复输入框已适配|
| Arc5 | 文件预览界面提供保存到 Android 系统公有目录按钮|跟进中||