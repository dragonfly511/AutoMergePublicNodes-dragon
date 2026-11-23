# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-23 07:59:12 |
| 运行耗时 | 280.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 103325 |
| 去重后节点 | 35939 |
| TCP 可达 | 3000 |
| 真实可用 | 225 |
| Verified 输出 | 16 |
| Global 输出 | 227 |
| All 输出 | 35939 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.5 |
| tcp | 96.0 |
| probe | 93.7 |
| real_test | 42.2 |
| china_check | 19.0 |
| write_verified | 0.0 |
| generate | 19.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59958 |
| vmess | 17912 |
| shadowsocks | 12068 |
| trojan | 10926 |
| hysteria2 | 1857 |
| http | 237 |
| shadowsocksr | 153 |
| socks | 140 |
| hysteria | 32 |
| anytls | 23 |
| tuic | 19 |

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
| 94.76 | shadowsocks | 259.3 | 3.1 | 21.78 | 14.88 | 9.08 | 13.48 | 19.54 | dragon | 15.204.247.244 |
| 93.79 | shadowsocks | 249.1 | 9.7 | 22.01 | 14.64 | 8.12 | 13.48 | 19.54 | dragon | 37.19.198.160 |
| 93.65 | shadowsocks | 230.4 | 10.5 | 22.45 | 14.61 | 8.07 | 13.48 | 19.54 | dragon | 45.86.51.18 |
| 93.2 | shadowsocks | 253.3 | 3.9 | 21.91 | 14.85 | 7.92 | 13.48 | 19.54 | dragon | 216.106.178.169 |
| 93.07 | shadowsocks | 242.2 | 6.5 | 22.17 | 14.76 | 8.12 | 13.48 | 19.54 | dragon | 37.19.198.243 |
| 92.86 | shadowsocks | 232.1 | 0.9 | 22.41 | 14.97 | 6.46 | 13.48 | 19.54 | dragon | 37.19.198.236 |
| 92.4 | shadowsocks | 289.1 | 7.4 | 21.09 | 14.72 | 8.07 | 13.48 | 19.54 | dragon | 185.230.230.18 |
| 92.31 | shadowsocks | 302.6 | 1.4 | 20.77 | 14.95 | 8.07 | 13.48 | 19.54 | dragon | 193.151.163.18 |
| 92.16 | shadowsocks | 311.3 | 1.3 | 20.57 | 14.95 | 8.12 | 13.48 | 19.54 | dragon | 38.91.100.39 |
| 91.76 | shadowsocks | 365.8 | 4.1 | 19.31 | 14.85 | 9.08 | 13.48 | 19.54 | dragon | 15.204.246.111 |
| 91.48 | shadowsocks | 332.7 | 1.2 | 20.08 | 14.96 | 7.92 | 13.48 | 19.54 | dragon | 149.40.57.133 |
| 91.34 | shadowsocks | 331.1 | 5.9 | 20.11 | 14.78 | 7.93 | 13.48 | 19.54 | dragon | 149.40.57.138 |
| 91.32 | shadowsocks | 255.2 | 3.9 | 21.87 | 14.85 | 9.08 | 13.48 | 19.54 | dragon | 200.102.179.179 |
| 90.91 | shadowsocks | 297.6 | 2.1 | 20.89 | 14.92 | 7.82 | 13.48 | 19.54 | dragon | 156.146.38.169 |
| 90.71 | shadowsocks | 363.0 | 1.1 | 19.38 | 14.96 | 7.85 | 13.48 | 19.54 | dragon | 193.151.160.18 |
| 90.08 | shadowsocks | 303.0 | 2.5 | 20.76 | 14.91 | 7.82 | 13.48 | 19.54 | dragon | 156.146.38.170 |
| 88.45 | shadowsocks | 249.6 | 5.7 | 22.0 | 14.79 | 8.14 | 13.48 | 19.54 | dragon | 172.111.38.72 |
| 88.28 | shadowsocks | 388.5 | 1.9 | 18.78 | 14.93 | 7.87 | 13.48 | 19.54 | dragon | 162.251.62.31 |
| 86.95 | shadowsocks | 307.0 | 2.8 | 20.67 | 14.89 | 7.66 | 13.48 | 19.54 | dragon | 95.215.201.18 |
| 86.53 | shadowsocks | 225.6 | 1.2 | 22.55 | 14.96 | 0.0 | 13.48 | 19.54 | dragon | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.967 | 0.89 | 236 | 10000 | prefer |
| dragon3 | 0.553 | 1.0 | 8 | 100 | observe |
| ermaozi | 0.496 | 1.0 | 6 | 486 | observe |
| dragon2 | 0.48 | 1.0 | 4 | 10000 | observe |
| Surfboard-tg-mixed | 0.4 | 0.75 | 4 | 8701 | observe |
| mheidari-all | 0.349 | 0.667 | 3 | 15418 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 421 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5069 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11834 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5650 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4514 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 2 | 16 | - |
| global | False | 278 | 227 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
