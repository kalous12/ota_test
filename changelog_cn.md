# changelog

- language: zh-CN
- Author: ZEROK

## v0.0.5

- Update time：2025-12-19
- Added: 添加ssh的开启和关闭功能，系统默认配置ssh关闭
- Added: 添加了tailscale，用户可以通过前端添加tailscale配置并使用
- Added: 二进制文件的编译信息，编译出来的文件可以显示编译信息
- Added: 添加了peripheral子模块，将atx重构成可以加载和卸载的子模块
- Added: 优化了网络传输的配置，传输延迟降低，传输速度提升
- Changed: 调整了system分区的大小，现在为最后的定型，后续不会再更改
- Changed: 优化了系统启动速度，现在启动速度更快
- Performance: 优化视频传输，使用硬件加速对高码率的场景进行了优化
- Performance: 更新无线网卡的驱动，优化了无线网卡的传输速度
- Fixed: 修复了内存泄漏的问题
- Fixed: 修复了文件传输会导致程序奔溃的bug

## v0.0.4

- Update time：2025-12-10
- Added: 添加系统心跳灯，2秒关，400ms亮，循环
- Added：添加了按键逻辑，覆盖了三种情形，分别是短按，长按，超长按
- Added：添加了ap配网的功能，长按A键3秒，系统会自动进入ap配网模式
- Changed: 显示屏主页优化了顶端栏，有线网络和无线wifi移动到最右边
- Fixed: 修复了前端ota板本显示大小V的问题
- Security: 优化了登录流程，登录界面可以显示因什么问题导致登录失败，添加了2FA登录功能

## v0.0.3

- Update time：2025-12-08
- Added: 添加了网页修改服务起的https的功能
- Fixed: 优化了ws的连接，更稳定更优秀
- Fixed: 修复了ota时tag大小写问题，统一小写v
- Security: 优化了登录流程，登录界面可以显示因什么问题导致登录失败，添加了2FA登录功能

## v0.0.2

- Update time：2025-12-04
- Added: 添加了前端访问log的功能，支持log下载，支持loglevel设置
- Added: 添加了event事件，系统操作及用户操作都会记录下来，用户可以通过前端查看event事件
- Added: 添加USB设备虚拟化配置功能,用户可以自行添加虚拟化设置并切换使用
- Added: 添加了系统时区设置功能，范围为UTC-12:00~UTC+14:00

## v0.0.1

- Update time：2025-12-01
