# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 06:20:08 |
| 运行耗时 | 303.7s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 101936 |
| 去重后节点 | 33986 |
| TCP 可达 | 3000 |
| 真实可用 | 289 |
| Verified 输出 | 20 |
| Global 输出 | 293 |
| All 输出 | 33986 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.5 |
| tcp | 91.5 |
| probe | 96.3 |
| real_test | 65.3 |
| china_check | 21.9 |
| write_verified | 0.0 |
| generate | 18.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60031 |
| vmess | 17264 |
| trojan | 11880 |
| shadowsocks | 10519 |
| hysteria2 | 1753 |
| http | 187 |
| shadowsocksr | 151 |
| socks | 82 |
| hysteria | 34 |
| anytls | 20 |
| tuic | 15 |

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
| 83.48 | hysteria2 | 284.0 | 2.0 | 21.2 | 14.92 | 0.13 | 13.12 | 16.9 | dragon2 | 66.94.121.46 |
| 82.51 | shadowsocks | 186.5 | 2.0 | 23.46 | 14.92 | 0.0 | 13.85 | 14.28 | dragon | 149.22.95.183 |
| 80.27 | shadowsocks | 231.3 | 6.2 | 22.42 | 14.77 | 0.0 | 13.85 | 16.9 | dragon2 | 169.197.142.68 |
| 79.67 | vless | 321.1 | 0.6 | 20.35 | 14.98 | 0.0 | 9.12 | 16.9 | dragon2 | 107.173.237.146 |
| 79.31 | shadowsocks | 266.1 | 25.1 | 21.62 | 14.06 | 0.0 | 13.85 | 14.28 | dragon | 137.184.89.151 |
| 78.62 | shadowsocks | 241.8 | 1.8 | 22.18 | 14.93 | 0.0 | 13.85 | 16.9 | dragon2 | 23.150.152.38 |
| 78.54 | shadowsocks | 342.6 | 0.3 | 19.85 | 14.99 | 6.49 | 13.85 | 14.28 | dragon | 149.22.87.240 |
| 78.32 | hysteria2 | 294.8 | 5.5 | 20.95 | 14.8 | 0.0 | 13.12 | 12.12 | mheidari-all | 88.216.195.188 |
| 78.31 | shadowsocks | 317.5 | 1.8 | 20.43 | 14.93 | 0.0 | 13.85 | 16.9 | dragon2 | 173.244.56.6 |
| 78.28 | shadowsocks | 328.7 | 7.1 | 20.17 | 14.73 | 0.0 | 13.85 | 16.9 | dragon2 | 103.11.76.248 |
| 77.67 | hysteria2 | 219.6 | 0.1 | 22.69 | 15.0 | 0.0 | 13.12 | 16.9 | dragon2 | 8.209.247.109 |
| 76.62 | shadowsocks | 277.2 | 1.2 | 21.36 | 14.96 | 0.0 | 13.85 | 14.28 | dragon | 173.244.56.9 |
| 76.47 | shadowsocks | 275.3 | 0.9 | 21.41 | 14.97 | 0.0 | 13.85 | 14.28 | dragon | 95.215.201.18 |
| 75.21 | shadowsocks | 364.0 | 1.2 | 19.35 | 14.96 | 0.0 | 13.85 | 16.9 | dragon2 | 38.121.43.231 |
| 75.0 | shadowsocks | 365.4 | 1.2 | 19.32 | 14.95 | 0.0 | 13.85 | 16.9 | dragon2 | 38.121.43.18 |
| 74.72 | shadowsocks | 416.6 | 3.7 | 18.13 | 14.86 | 1.12 | 13.85 | 15.64 | dragon3 | 38.64.138.135 |
| 74.63 | shadowsocks | 441.3 | 4.1 | 17.56 | 14.84 | 6.87 | 13.85 | 14.28 | dragon | 38.22.17.219 |
| 74.25 | shadowsocks | 366.0 | 1.5 | 19.31 | 14.95 | 0.0 | 13.85 | 16.9 | dragon2 | 167.88.63.99 |
| 74.06 | shadowsocks | 366.5 | 3.2 | 19.29 | 14.88 | 0.0 | 13.85 | 16.9 | dragon2 | 172.111.36.123 |
| 73.95 | shadowsocks | 419.6 | 1.8 | 18.06 | 14.93 | 1.13 | 13.85 | 15.64 | dragon3 | 149.40.57.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.944 | 124 | 10000 | prefer |
| dragon2 | 0.798 | 0.72 | 214 | 10000 | prefer |
| mheidari-all | 0.606 | 0.889 | 9 | 13634 | observe |
| dragon3 | 0.553 | 1.0 | 8 | 100 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8637 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2768 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11015 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6148 | observe |
| barry-far-vless | 0.255 | None | 0 | 6359 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4540 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 46 |
| 204 | ProxyError | - | 7 |
| cn-block | TimeoutError | - | 6 |
| 204 | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 20 | - |
| global | False | 300 | 293 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
