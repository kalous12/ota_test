# changelog

- language: zh-CN
- Author: ZEROK

## V0.6.7

- Update time：2025-11-29
- Security: ota升级时需要验证身份，防止未授权的升级
- Fixed: 修复了ota不能使用github进行升级的问题
- Added: 添加了OTA离线镜像的校验
- Changed: 优化了ui界面
- Changed: 使用新的api进行ota升级

## V0.6.6

- Update time：2025-11-28
- Changed: 优化了ota的后端代码
- Fixed: 修复了获取ota版本号时会显示错误的问题
- Added: 添加了ota版本号获取时间，方便查看什么时候搜索过更新
- Security: ota升级需要验证身份之后才能进行，防止未授权的升级
- Removed: 移除了ota会持续保存安装包的功能，如果有最新的安装包会把原来下载的删掉
