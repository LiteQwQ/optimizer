# CelestialOptimizer

> 本 README 由 AI 自动生成，仅供参考。

## 项目简介

CelestialOptimizer 是一个由LiteBoost团队开发的一个专为 Windows 系统设计的网络与系统优化工具，旨在提升 TCP 响应速度、降低延迟、优化多媒体体验。支持普通模式和激进模式，适合游戏、实时应用等场景。

## 功能说明

- 一键优化 TCP 参数、QoS、注册表等系统设置
- 支持普通模式（稳定兼容）和激进模式（极致低延迟）
- 可一键恢复所有优化项为系统默认

# 优化项目列表（含简要说明）

- **TCPNoDelay**：禁用Nagle算法，减少TCP延迟
- **TcpAckFrequency**：提高ACK频率，加快数据确认
- **TcpDelAckTicks**：减少延迟ACK等待时间
- **NetworkThrottlingIndex**：禁用系统网络限流
- **SystemResponsiveness**：提升系统响应速度
- **NonBestEffortLimit**：禁用QoS保留带宽
- **TcpWindowSize**：调整TCP窗口大小
- **GlobalMaxTcpWindowSize**：最大TCP窗口大小
- **TcpInitialRto**：初始重传超时时间
- **SackOpts**：选择性确认（SACK）选项
- **MaxUserPort**：最大用户端口数
- **TcpTimedWaitDelay**：TIME_WAIT状态持续时间
- **autotuninglevel**：TCP自动调优级别
- **chimney**：TCP Chimney卸载
- **rss**：接收端扩展（RSS）
- **ecncapability**：显式拥塞通知（ECN）
- **timestamps**：TCP时间戳
- **ScalingHeuristics**：窗口扩展启发式
- **MinRto**：最小重传超时
- **EcnCapability**：ECN能力
- **InitialRto**：初始重传超时
- **AutoTuningLevelLocal**：本地自动窗口调节
- **Timestamps**：TCP时间戳
- **MaxSynRetransmissions**：SYN重传次数
- **NonSackRttResiliency**：RTT重试容忍
- **ReceiveSegmentCoalescing**：接收段合并
- **Disable-NetAdapterChecksumOffload**：禁用网卡校验和卸载
- **Disable-NetAdapterLso**：禁用网卡大包卸载
- **DSCPAction**：QoS优先级标记
- **SetTimerResolution**：提升系统定时器分辨率

## 使用方法

1. 以管理员身份运行程序
2. 按提示选择优化模式或恢复设置
3. 优化完成后建议重启电脑
