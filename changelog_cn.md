# changelog

- language: zh-CN
- Author: ZEROK

## v0.0.1

- Update time：2025-12-01

## v0.0.2

- Update time：2025-12-04
- Added: 添加了前端访问log的功能，支持log下载，支持loglevel设置
- Added: 添加了event事件，系统操作及用户操作都会记录下来，用户可以通过前端查看event事件
- Added: 添加USB设备虚拟化配置功能,用户可以自行添加虚拟化设置并切换使用
- Added: 添加了系统时区设置功能，范围为UTC-12:00~UTC+14:00

## v0.0.3

- Update time：2025-12-08
- Added: 添加了网页修改服务起的https的功能
- Fixed: 优化了ws的连接，更稳定更优秀
- Fixed: 修复了ota时tag大小写问题，统一小写v
- Security: 优化了登录流程，登录界面可以显示因什么问题导致登录失败，添加了2FA登录功能
