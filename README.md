# Lenovo-ThinkPad-L14-Gen1-i5-10210U-Hackintosh
EFI of Lenovo-ThinkPad-L14-Gen1-i5-10210U

The EFI of ThinkPad-L14-Gen1

CPU: i5-10210U

Network Card：BCM94352Z



## 2022-06-02

开启原生电源管理（已禁用MSR 0XE2 如未禁用请自行勾选电源管理相关参数）

OpenCore 7.7 ==> 0.8-release

AppleALC ==> 1.7.1

WhateverGreen ==> 1.5.8

Lilu ==> 1.6.0

VirtualSMC ==> 1.2.9



## 2022-01-31

解决无法收到最新系统更新的问题（使用RestrictEvents.kext）

## 2022-01-30

更新opencore -> 7.7

## 2021-11-15

更新引导，可升级至macOS 12；

更换alcid，可开启环境音降低功能；

推荐使用 **QTOpenCoreConfig**

[ic005k/QtOpenCoreConfig: OpenCore Auxiliary Tools OpenCore Configurator OCAT (github.com)](https://github.com/ic005k/QtOpenCoreConfig)
