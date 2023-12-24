# ISecureElementService-aidl

> ## Notice:
> ##### 本人菜b，持续咕咕
> ##### 编程语言啥都不会
> ##### 先开个空仓库咕一下

- 如今某些安卓设备开始使用[ 硬件安全模块(Strongbox Keymaster) ](https://developer.android.com/training/articles/keystore?hl=zh-cn#HardwareSecurityModule)来存储密钥
- 由于strongbox需要与omapi进行通信来完成设备的解密
`android.se.omapi.ISecureElementService`一般由包`com.android.se`来提供
- 但是在某些环境中我们无法运行这个apk
- 所以需要想办法摆脱ART来运行这个服务
- 比如cpp实现aidl或者使用hidl实现
- 理解不深，请不要喷，若有想法，欢迎pr/issue

> - 先开个仓库，咕咕
> - 本人初学者，咕咕
> - 总之就是持续咕咕