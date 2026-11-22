# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-22 07:11:28 |
| 运行耗时 | 204.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 103594 |
| 去重后节点 | 34972 |
| TCP 可达 | 3000 |
| 真实可用 | 46 |
| Verified 输出 | 4 |
| Global 输出 | 47 |
| All 输出 | 34972 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 75.7 |
| probe | 68.3 |
| real_test | 25.2 |
| china_check | 16.9 |
| write_verified | 0.0 |
| generate | 11.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60266 |
| vmess | 17931 |
| shadowsocks | 11644 |
| trojan | 11476 |
| hysteria2 | 1775 |
| shadowsocksr | 165 |
| socks | 160 |
| http | 110 |
| hysteria | 31 |
| tuic | 22 |
| anytls | 14 |

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
| 93.3 | vless | 259.9 | 0.3 | 21.76 | 14.99 | 7.92 | 12.89 | 18.74 | dragon | 184.107.179.150 |
| 84.73 | shadowsocks | 569.8 | 0.4 | 14.59 | 14.99 | 8.91 | 12.0 | 18.74 | dragon | 158.51.121.221 |
| 80.41 | vless | 327.6 | 2.4 | 20.19 | 14.91 | 8.28 | 12.89 | 18.74 | dragon | 154.12.49.239 |
| 79.61 | vless | 370.6 | 2.1 | 19.2 | 14.92 | 7.73 | 12.89 | 18.74 | dragon | 216.106.185.158 |
| 79.13 | hysteria2 | 320.2 | 7.0 | 20.37 | 14.74 | 0.89 | 11.25 | 18.74 | dragon | 66.94.121.46 |
| 78.93 | vless | 483.8 | 63.1 | 16.58 | 12.63 | 4.14 | 12.89 | 18.74 | dragon | 152.228.139.33 |
| 76.82 | vless | 562.3 | 0.3 | 14.76 | 14.99 | 4.25 | 12.89 | 18.74 | dragon | 172.237.14.205 |
| 76.65 | vless | 548.5 | 5.7 | 15.08 | 14.79 | 6.19 | 12.89 | 18.74 | dragon | 172.235.40.143 |
| 76.04 | hysteria2 | 340.3 | 0.8 | 19.9 | 14.97 | 6.98 | 11.25 | 8.92 | dragon2 | 62.210.124.146 |
| 75.82 | vless | 513.3 | 0.4 | 15.9 | 14.98 | 4.08 | 12.89 | 18.74 | dragon | 157.180.98.124 |
| 75.62 | hysteria2 | 480.6 | 7.3 | 16.65 | 14.72 | 1.02 | 11.25 | 18.74 | dragon | 5.129.235.85 |
| 74.8 | vless | 556.0 | 2.1 | 14.91 | 14.92 | 3.98 | 12.89 | 18.74 | dragon | 139.162.91.137 |
| 73.71 | hysteria2 | 559.7 | 45.3 | 14.82 | 13.3 | 7.05 | 11.25 | 18.74 | dragon | germanyafterpool.fun |
| 73.58 | hysteria2 | 338.2 | 1.0 | 19.95 | 14.96 | 0.0 | 11.25 | 8.42 | mheidari-all | 34.24.25.1 |
| 72.42 | hysteria2 | 345.2 | 0.7 | 19.79 | 14.97 | 0.19 | 11.25 | 18.74 | dragon | 8.209.247.109 |
| 71.71 | vless | 564.6 | 1.0 | 14.71 | 14.96 | 4.0 | 12.89 | 18.74 | dragon | 172.105.197.24 |
| 71.51 | vless | 568.3 | 3.9 | 14.62 | 14.85 | 4.06 | 12.89 | 18.74 | dragon | 172.105.212.91 |
| 71.5 | vless | 570.7 | 0.3 | 14.57 | 14.99 | 4.03 | 12.89 | 18.74 | dragon | 139.162.101.74 |
| 70.77 | vless | 603.2 | 0.4 | 13.81 | 14.98 | 3.98 | 12.89 | 18.74 | dragon | 139.162.91.200 |
| 70.2 | vless | 623.5 | 0.5 | 13.34 | 14.98 | 3.97 | 12.89 | 18.74 | dragon | 139.162.91.224 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.757 | 0.812 | 16 | 10000 | prefer |
| dragon | 0.609 | 0.531 | 49 | 10000 | observe |
| Surfboard-tg-mixed | 0.519 | 1.0 | 5 | 8778 | observe |
| mheidari-all | 0.48 | 1.0 | 4 | 14453 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi-get_subscribe | 0.282 | 0.667 | 3 | 327 | observe |
| zhangkai | 0.256 | 1.0 | 1 | 27 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5030 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12093 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5942 | observe |
| barry-far-vless | 0.255 | None | 0 | 6124 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4512 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 5 | 4 | - |
| global | False | 76 | 47 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
