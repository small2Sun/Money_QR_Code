# 自动获取微信/支付宝的收款码（自定义金额）

#### 简单说明
通过AccessibilityService服务，实现自动化点击。

在APP输入想要的金额，启动服务后，打开微信/支付宝后，自动点击到收款码页面，自动输入想要的金额后，截图获取收款码并进行二维码转换获得对应的字符串。

额外功能：获取支付宝号，微信号。

#### 运行要求
* 需要Android 7.0 以上的版本
* 需要开启无障碍服务
* 需要截取屏幕显示的内容
* 微信/支付宝的语言是简体中文

#### 参考链接
[不root实现Android屏幕截图](https://github.com/goodbranch/ScreenCapture)
