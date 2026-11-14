# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-14 18:23:58 |
| 运行耗时 | 272.6s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 103418 |
| 去重后节点 | 34645 |
| TCP 可达 | 3000 |
| 真实可用 | 280 |
| Verified 输出 | 18 |
| Global 输出 | 282 |
| All 输出 | 34645 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.5 |
| tcp | 85.5 |
| probe | 87.6 |
| real_test | 45.5 |
| china_check | 25.2 |
| write_verified | 0.0 |
| generate | 18.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60845 |
| vmess | 17697 |
| trojan | 11800 |
| shadowsocks | 10792 |
| hysteria2 | 1760 |
| shadowsocksr | 183 |
| http | 182 |
| socks | 75 |
| anytls | 33 |
| hysteria | 27 |
| tuic | 24 |

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
| 84.05 | shadowsocks | 298.5 | 3.3 | 20.87 | 14.88 | 0.0 | 13.64 | 19.16 | dragon2 | 15.204.247.206 |
| 83.01 | vless | 240.9 | 2.6 | 22.2 | 14.9 | 0.0 | 6.75 | 19.16 | dragon2 | 159.89.87.21 |
| 81.5 | hysteria2 | 249.1 | 17.7 | 22.01 | 14.34 | 0.0 | 11.47 | 14.68 | dragon | 206.189.229.48 |
| 81.35 | shadowsocks | 303.7 | 2.7 | 20.75 | 14.9 | 0.0 | 13.64 | 19.16 | dragon2 | 185.215.132.18 |
| 80.06 | shadowsocks | 302.8 | 0.3 | 20.77 | 14.99 | 4.96 | 13.64 | 14.68 | dragon | 95.215.201.18 |
| 80.03 | shadowsocks | 359.8 | 1.3 | 19.45 | 14.95 | 0.0 | 13.64 | 19.16 | dragon2 | 172.111.36.123 |
| 80.02 | hysteria2 | 335.6 | 8.4 | 20.01 | 14.69 | 4.19 | 11.47 | 14.68 | dragon | 34.24.25.1 |
| 79.92 | shadowsocks | 353.7 | 8.3 | 19.59 | 14.69 | 0.0 | 13.64 | 19.16 | dragon2 | 38.121.43.231 |
| 79.89 | shadowsocks | 378.8 | 0.4 | 19.01 | 14.98 | 5.86 | 13.64 | 14.68 | dragon | 38.22.17.219 |
| 79.58 | shadowsocks | 380.1 | 1.3 | 18.98 | 14.95 | 0.0 | 13.64 | 19.16 | dragon2 | 167.88.63.39 |
| 79.2 | shadowsocks | 300.8 | 6.9 | 20.81 | 14.74 | 0.0 | 13.64 | 19.16 | dragon2 | 38.145.220.193 |
| 79.2 | shadowsocks | 387.0 | 4.3 | 18.82 | 14.84 | 0.0 | 13.64 | 19.16 | dragon2 | 38.22.17.129 |
| 79.1 | hysteria2 | 324.9 | 25.3 | 20.26 | 14.05 | 3.34 | 11.47 | 14.68 | dragon | 66.94.121.46 |
| 79.1 | shadowsocks | 387.8 | 4.5 | 18.8 | 14.83 | 0.0 | 13.64 | 19.16 | dragon2 | 38.22.17.139 |
| 78.87 | shadowsocks | 385.9 | 1.8 | 18.85 | 14.93 | 0.0 | 13.64 | 19.16 | dragon2 | 167.88.63.99 |
| 78.86 | shadowsocks | 307.7 | 1.1 | 20.66 | 14.96 | 0.0 | 13.64 | 19.16 | dragon2 | 23.150.152.38 |
| 77.96 | shadowsocks | 332.7 | 0.1 | 20.08 | 15.0 | 0.0 | 13.64 | 19.16 | dragon2 | 51.222.136.236 |
| 77.7 | shadowsocks | 359.0 | 1.8 | 19.47 | 14.93 | 0.0 | 13.64 | 19.16 | dragon2 | 51.222.12.127 |
| 77.62 | vless | 261.3 | 0.6 | 21.73 | 14.98 | 0.0 | 6.75 | 19.16 | dragon2 | 216.227.161.95 |
| 77.22 | shadowsocks | 352.6 | 0.6 | 19.62 | 14.98 | 0.0 | 13.64 | 19.16 | dragon2 | 169.197.142.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.993 | 0.952 | 21 | 10000 | prefer |
| dragon3 | 0.942 | 0.967 | 30 | 100 | prefer |
| dragon2 | 0.868 | 0.79 | 286 | 10000 | prefer |
| mheidari-all | 0.4 | 0.75 | 4 | 14109 | observe |
| Surfboard-tg-mixed | 0.349 | 0.667 | 3 | 8883 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 179 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4966 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11700 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6276 | observe |
| barry-far-vless | 0.255 | None | 0 | 6457 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4551 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 43 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 15 | 18 | - |
| global | False | 246 | 282 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
