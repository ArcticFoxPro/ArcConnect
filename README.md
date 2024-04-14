<div align="center" style="margin-top: 60px;margin-bottom: 20px;">
<img src="images/ArcConnect.png" width = "50%" />
</div>

<h1 align="center">狐云山脉</h1>

<div align="center">

[新特性](#新特性) | [Bug 修复](#bug-修复) | [优化](#优化) | [其他更改](#其它更改) | [关于](#关于)

搜索问题请使用 `Ctrl` + `F`（Windows）或 `Cmd` + `F`（macOS）

</div> 

> “QQ”“腾讯 QQ”“腾讯”“微信”“WeChat”是深圳市腾讯计算机系统有限公司和/或其关联公司的商标。此仓库对“QQ”“腾讯 QQ”“腾讯”“微信”“WeChat”的使用旨在注明和指向对应主体，并非表示对“QQ”、“腾讯 QQ”、“腾讯”、“微信”、“WeChat”商标的注册和拥有。

> Android™ 是 Google LLC 的商标。

> Apple®、iPhone®、iPad®、Mac®、iMac®、Apple Watch®、AppleVision™、Apple Vision Pro™、iPadOS®、macOS®、visionOS™、watchOS® 是 Apple Inc. 的商标或注册商标。iOS 是 Cisco 的商标或注册商标。

## 跟进信息

### 新特性

<div align="center">

| 编号 | 平台 | 描述 | 状态 | 备注 |
| :-: | :-: |  :-: | :-: | :-: |
| ArcF1 | Android | 手势导航提示条（小白条）真沉浸 | 已上线 | Android QQ 9.0.25，仅部分场景生效 |
| ArcF2 | Android | ShortCuts（桌面图标长按菜单） | 已上线 | Android QQ 9.0.25 |
| ArcF3 | Android | 系统通知快捷回复（RemoteInput API）| Xiaomi HyperOS 适配受阻，小米三方应用外部支持和相关技术部门正在分析此问题 |在多个中国大陆 Android OEM 定制系统测试时，发现在基于 Android 14 的 Xiaomi HyperOS 设备和部分基于 Android 13 的 Xiaomi HyperOS 设备上调用 RemoteInput API 时，存在系统直接向 RemoteInput 返回 `null` 的问题，与 Android 预期逻辑和结果不符。|
| ArcF4 | Android | 边到边（edge-to-edge）软键盘动画（WindowInsetsAnimation API）| 跟进中 | Android QQ 9.0.35 腾讯频道帖子详情页回复输入框已适配 |
| ArcF5 | Android | 文件预览界面提供保存到 Android 系统公有目录按钮 | 跟进中| |

</div>

### Bug 修复

<div align="center">

| 编号 | 平台 | 描述 | 状态 | 备注 |
| :-: | :-: | :-: | :-: | :-: |
| ArcB1 | Android · Xiaomi HyperOS | 将 QQ 缩小为小米自由小窗情况下，小米小窗底部导航提示条与 QQ 底部导航栏重叠 | 未明确 | 修复方案可参考：[Fix navigation bar insets for HyperOS Freeform (#1176) · LibChecker/LibChecker@25354dc](https://github.com/LibChecker/LibChecker/commit/25354dc31e25302d81ccaf5752d4ae72ae8cbbb0) |

</div>

### 优化

<div align="center">

| 编号 | 平台 | 描述 | 状态 | 备注 |
| :-: | :-: | :-: | :-: | :-: |
| ArcE1 | 待补充 | 待补充 | 待补充 | 待补充 |

</div>

### 其它更改

<div align="center">

| 编号 | 平台 | 描述 | 状态 | 备注 |
| :-: | :-: | :-: | :-: | :-: |
| ArcO1 | 待补充 | 待补充 | 待补充 | 待补充 |

</div>

## 关于

狐云山脉 - ArcConnect 旨在记录和呈现移动端 QQ 的一系列可预见的新特性、Bug 修复、优化和其它更改。

狐云山脉为纯个人项目，与腾讯公司无任何关联。狐云山脉无意也不可能替代 QQ 反馈体系。当您遇到任何 QQ 自身问题时，您应始终前往 `QQ` - `设置` - `关于QQ与帮助` - `反馈` 处反馈。

狐云山脉可能会避免展示无障碍问题，若需反馈无障碍问题，您应始终前往 `QQ` - `设置` - `关于QQ与帮助` - `反馈` 处反馈。