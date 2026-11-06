# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 18:53:00 |
| 运行耗时 | 306.6s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102664 |
| 去重后节点 | 34625 |
| TCP 可达 | 3000 |
| 真实可用 | 311 |
| Verified 输出 | 13 |
| Global 输出 | 300 |
| All 输出 | 34625 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.6 |
| tcp | 89.2 |
| probe | 96.6 |
| real_test | 67.7 |
| china_check | 26.0 |
| write_verified | 0.0 |
| generate | 16.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60457 |
| vmess | 17727 |
| trojan | 12111 |
| shadowsocks | 10038 |
| hysteria2 | 1820 |
| http | 202 |
| shadowsocksr | 156 |
| socks | 84 |
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
| 85.59 | trojan | 271.1 | 16.6 | 21.5 | 14.38 | 10.0 | 8.27 | 13.94 | dragon | 216.152.155.23 |
| 84.24 | vless | 225.5 | 11.3 | 22.56 | 14.58 | 0.0 | 9.0 | 18.1 | dragon2 | 67.220.73.204 |
| 83.35 | shadowsocks | 260.1 | 0.2 | 21.76 | 14.99 | 0.0 | 12.5 | 18.1 | dragon2 | 156.146.38.168 |
| 81.29 | shadowsocks | 264.4 | 26.4 | 21.66 | 14.01 | 7.96 | 12.5 | 13.94 | dragon | 156.146.38.167 |
| 80.92 | vless | 277.1 | 1.7 | 21.36 | 14.94 | 0.0 | 9.0 | 18.1 | dragon2 | 216.227.161.95 |
| 79.69 | vless | 376.2 | 1.1 | 19.07 | 14.96 | 0.0 | 9.0 | 18.1 | dragon2 | 209.200.246.148 |
| 79.12 | hysteria2 | 216.8 | 17.2 | 22.76 | 14.36 | 0.0 | 12.86 | 10.14 | mheidari-all | 88.216.195.188 |
| 77.69 | shadowsocks | 250.8 | 45.9 | 21.97 | 13.28 | 0.0 | 12.5 | 13.94 | dragon | 198.98.53.130 |
| 77.52 | shadowsocks | 307.3 | 1.8 | 20.66 | 14.93 | 0.0 | 12.5 | 18.1 | dragon2 | 173.244.56.6 |
| 77.27 | shadowsocks | 301.6 | 1.3 | 20.8 | 14.95 | 0.0 | 12.5 | 18.1 | dragon2 | 95.215.201.18 |
| 77.15 | shadowsocks | 362.0 | 18.9 | 19.4 | 14.29 | 0.0 | 12.5 | 18.1 | dragon2 | 167.88.62.56 |
| 76.51 | vless | 214.9 | 10.4 | 22.8 | 14.61 | 0.0 | 9.0 | 18.1 | dragon2 | 108.61.119.63 |
| 76.46 | vless | 370.4 | 1.8 | 19.2 | 14.93 | 0.0 | 9.0 | 18.1 | dragon2 | 107.173.237.146 |
| 76.36 | vless | 257.6 | 1.3 | 21.81 | 14.95 | 0.0 | 9.0 | 18.1 | dragon2 | 69.48.201.136 |
| 76.05 | shadowsocks | 349.9 | 1.4 | 19.68 | 14.95 | 0.0 | 12.5 | 18.1 | dragon2 | 185.215.132.9 |
| 75.66 | hysteria2 | 469.5 | 2.3 | 16.91 | 14.91 | 0.0 | 12.86 | 18.1 | dragon2 | 130.49.161.70 |
| 75.51 | shadowsocks | 395.0 | 3.6 | 18.63 | 14.86 | 0.0 | 12.5 | 18.1 | dragon2 | 38.91.107.188 |
| 75.19 | shadowsocks | 256.4 | 4.0 | 21.84 | 14.85 | 0.0 | 12.5 | 10.0 | dragon3 | 37.19.198.243 |
| 75.08 | shadowsocks | 341.0 | 5.1 | 19.88 | 14.81 | 0.0 | 12.5 | 18.1 | dragon2 | 169.197.142.68 |
| 75.06 | shadowsocks | 329.0 | 1.9 | 20.16 | 14.93 | 0.0 | 12.5 | 18.1 | dragon2 | 23.150.152.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon3 | 0.975 | 1.0 | 32 | 100 | prefer |
| dragon2 | 0.843 | 0.765 | 336 | 10000 | prefer |
| dragon | 0.72 | 0.8 | 15 | 10000 | prefer |
| mheidari-all | 0.507 | 0.75 | 8 | 14184 | observe |
| Surfboard-tg-mixed | 0.489 | 0.833 | 6 | 8758 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2768 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10962 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6135 | observe |
| barry-far-vless | 0.255 | None | 0 | 6479 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 57 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 8 |
| cn-block | TimeoutError | - | 5 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 4 | 13 | - |
| global | False | 82 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
