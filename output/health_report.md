# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-19 20:54:14 |
| 运行耗时 | 265.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 103275 |
| 去重后节点 | 35550 |
| TCP 可达 | 3000 |
| 真实可用 | 163 |
| Verified 输出 | 13 |
| Global 输出 | 172 |
| All 输出 | 35550 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 93.4 |
| probe | 77.2 |
| real_test | 51.7 |
| china_check | 20.9 |
| write_verified | 0.0 |
| generate | 14.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60234 |
| vmess | 17887 |
| shadowsocks | 11537 |
| trojan | 11461 |
| hysteria2 | 1729 |
| shadowsocksr | 178 |
| http | 128 |
| socks | 72 |
| hysteria | 22 |
| tuic | 16 |
| anytls | 11 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 94.07 | trojan | 252.5 | 5.6 | 21.93 | 14.79 | 9.83 | 10.12 | 19.9 | dragon | 66.163.122.26 |
| 92.3 | shadowsocks | 245.7 | 2.6 | 22.09 | 14.9 | 5.2 | 14.71 | 19.9 | dragon | 45.86.51.18 |
| 92.1 | shadowsocks | 247.9 | 7.0 | 22.04 | 14.74 | 5.21 | 14.71 | 19.9 | dragon | 185.230.230.18 |
| 91.88 | shadowsocks | 256.4 | 4.9 | 21.84 | 14.82 | 5.11 | 14.71 | 19.9 | dragon | 193.151.163.18 |
| 90.77 | shadowsocks | 315.8 | 4.0 | 20.47 | 14.85 | 5.34 | 14.71 | 19.9 | dragon | 149.40.57.138 |
| 90.55 | shadowsocks | 304.9 | 1.4 | 20.72 | 14.95 | 4.97 | 14.71 | 19.9 | dragon | 193.151.160.18 |
| 90.2 | shadowsocks | 305.1 | 4.1 | 20.72 | 14.84 | 4.96 | 14.71 | 19.9 | dragon | 193.151.160.9 |
| 89.95 | shadowsocks | 347.7 | 6.9 | 19.73 | 14.74 | 5.37 | 14.71 | 19.9 | dragon | 38.91.100.39 |
| 89.85 | hysteria2 | 238.8 | 1.3 | 22.25 | 14.95 | 0.0 | 13.75 | 19.9 | dragon | 206.189.229.48 |
| 89.41 | trojan | 437.8 | 6.7 | 17.64 | 14.75 | 10.0 | 10.12 | 19.9 | dragon | 69.164.240.85 |
| 88.99 | shadowsocks | 337.5 | 1.9 | 19.96 | 14.93 | 5.14 | 14.71 | 19.9 | dragon | 167.88.62.203 |
| 88.69 | shadowsocks | 410.1 | 5.0 | 18.28 | 14.81 | 5.49 | 14.71 | 19.9 | dragon | 15.204.247.206 |
| 87.81 | hysteria2 | 327.8 | 0.7 | 20.19 | 14.97 | 0.0 | 13.75 | 19.9 | dragon | 34.24.25.1 |
| 86.93 | shadowsocks | 371.8 | 1.4 | 19.17 | 14.95 | 2.7 | 14.71 | 19.9 | dragon | 149.40.57.133 |
| 86.26 | shadowsocks | 358.9 | 3.3 | 19.47 | 14.88 | 5.27 | 14.71 | 19.9 | dragon | 149.40.57.134 |
| 85.73 | shadowsocks | 426.2 | 1.5 | 17.91 | 14.94 | 5.06 | 14.71 | 19.9 | dragon | 51.222.141.125 |
| 84.57 | shadowsocks | 314.6 | 4.3 | 20.49 | 14.84 | 4.84 | 14.71 | 19.9 | dragon | 95.215.201.18 |
| 84.14 | shadowsocks | 338.4 | 4.8 | 19.95 | 14.82 | 4.16 | 14.71 | 19.9 | dragon | 23.150.152.38 |
| 83.84 | shadowsocks | 355.5 | 2.3 | 19.55 | 14.91 | 4.79 | 14.71 | 19.9 | dragon | 169.197.142.68 |
| 83.76 | shadowsocks | 340.7 | 0.3 | 19.89 | 14.99 | 4.3 | 14.71 | 19.9 | dragon | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.989 | 0.95 | 20 | 10000 | prefer |
| dragon3 | 0.871 | 0.893 | 28 | 100 | prefer |
| dragon | 0.739 | 0.661 | 168 | 10000 | prefer |
| Surfboard-tg-mixed | 0.547 | 0.778 | 9 | 8602 | observe |
| tg-LonUp_M | 0.407 | 1.0 | 4 | 179 | observe |
| mheidari-all | 0.391 | 1.0 | 2 | 14706 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4935 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2728 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12076 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5937 | observe |
| barry-far-vless | 0.255 | None | 0 | 5868 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4507 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 39 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 7 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 11 | 13 | - |
| global | False | 190 | 172 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
