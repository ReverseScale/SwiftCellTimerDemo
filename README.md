# SwiftCellTimerDemo
Swift 使用 RunLoop 实现 TableView 的 Cell 上的倒计时⏳效果

![](https://img.shields.io/badge/platform-iOS-red.svg) 
![](https://img.shields.io/badge/language-Swift-orange.svg) 
![](https://img.shields.io/badge/download-1.9MB-brightgreen.svg)
![](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg) 

众所周知，关于重用的 Cell 和 Timer 一直是对死敌，只有 RunLoop 才能让他们关系稍稍缓和一些，之前有用 OC 做过，今天把这个 Swift 的奉上。

| 名称 |1.列表页 |2.展示页 |3.滑动页 |
| ------------- | ------------- | ------------- | ------------- |
| 截图 | ![](http://og1yl0w9z.bkt.clouddn.com/17-9-18/37478014.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/17-9-18/134916.jpg) | ![](http://og1yl0w9z.bkt.clouddn.com/17-9-18/68209181.jpg) |
| 描述 | 通过 storyboard 搭建基本框架 | 进入时页面效果 | 滑动页面效果 |


## Advantage 框架的优势
* 1.文件少，代码简洁
* 2.不依赖任何其他第三方库
* 3.具备较高自定义性


## Requirements 要求
* iOS 7+
* Xcode 8+


## Usage 使用方法
### 初始化方法
```
// 获取服务器当前时间
TimerUtil.sharedInstance.resetServerTime()
TimerUtil.sharedInstance.timerStart()
```

使用简单、效率高效、进程安全~~~如果你有更好的建议,希望不吝赐教!


## License 许可证
SwiftCellTimerDemo 使用 MIT 许可证，详情见 LICENSE 文件。


## Contact 联系方式:
* WeChat : WhatsXie
* Email : ReverseScale@iCloud.com
* Blog : https://reversescale.github.io
