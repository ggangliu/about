# 挑夹棋 AI 评测环境

[TOC]

## 编译器服务器配置

CPU: Intel Xeon E5-2640 2.5GHzz * 4 (in Hyper-V)

Memory: 4.00 GB

OS: Windows 7 Service Pack 1 x64

| 编译器 ID | 名称 | IDE | IDE 模式 | 命令行参数 |
|-------------|---------------|----------|----------|--------------|
| gcc51c11    | TDM-GCC 5.1.0 | -- | -- | `gcc -O2 -s -Wall -o foo.exe foo.c -lm -Wl,--stack=134217728 -std=c11 -m32` |
| gcc49c11 | TDM-GCC 4.9.2 | Dev C++ | Release, 32-Bit | `gcc -O2 -s -Wall -o foo.exe foo.c -lm -Wl,--stack=134217728 -std=c11 -m32` |

## 对局服务器配置

CPU: Intel Xeon E5-2640 2.5GHz * 20 (in Hyper-V)

Memory: 20.00 GB

OS: Windows 7 Service Pack 1 x64
