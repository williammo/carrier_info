## 3.0.5

- 修复 iOS 模块名与 pub 包名不一致的问题：podspec 重命名为 `shennong_carrier_info.podspec` 且 `s.name` 对齐包名。
- `CarrierInfoPlugin.m` 的 Swift 兼容头导入同步为 `shennong_carrier_info-Swift.h`，保证 CocoaPods 集成与 Flutter 生成的插件注册器都能正确找到模块。

## 3.0.4

- 发布为独立包 shennong_carrier_info（基于官方 carrier_info 3.0.x 定制）。
- 补充 Android `namespace` 声明，兼容 AGP 8.x 构建（原 2.0.8 缺失导致编译失败）。
- 放宽 Dart SDK 约束至 `>=3.0.0 <4.0.0`。

## 3.0.3

- Fix iOS 16.0+ CTCarrier deprecation and add new CoreTelephony features.

## 3.0.0

- 对齐官方 3.0.x 系列能力。
