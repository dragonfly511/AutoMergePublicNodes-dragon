# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-20 20:38:35 |
| 运行耗时 | 272.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102672 |
| 去重后节点 | 35842 |
| TCP 可达 | 3000 |
| 真实可用 | 184 |
| Verified 输出 | 11 |
| Global 输出 | 185 |
| All 输出 | 35842 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.6 |
| tcp | 92.1 |
| probe | 97.6 |
| real_test | 34.2 |
| china_check | 19.5 |
| write_verified | 0.0 |
| generate | 18.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58516 |
| vmess | 18052 |
| trojan | 11982 |
| shadowsocks | 11818 |
| hysteria2 | 1788 |
| shadowsocksr | 176 |
| http | 167 |
| socks | 120 |
| hysteria | 25 |
| tuic | 16 |
| anytls | 12 |

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
| 93.22 | hysteria2 | 244.4 | 8.0 | 22.12 | 14.7 | 10.0 | 9.64 | 17.76 | dragon | 206.189.229.48 |
| 92.62 | shadowsocks | 235.3 | 1.7 | 22.33 | 14.93 | 10.0 | 12.1 | 17.76 | dragon | 185.230.230.18 |
| 92.09 | shadowsocks | 248.0 | 8.3 | 22.04 | 14.69 | 10.0 | 12.1 | 17.76 | dragon | 193.151.163.18 |
| 91.56 | hysteria2 | 328.2 | 0.6 | 20.18 | 14.98 | 10.0 | 9.64 | 17.76 | dragon | 34.24.25.1 |
| 90.68 | shadowsocks | 311.5 | 6.6 | 20.57 | 14.75 | 10.0 | 12.1 | 17.76 | dragon | 149.40.57.138 |
| 90.56 | shadowsocks | 320.8 | 1.3 | 20.35 | 14.95 | 9.9 | 12.1 | 17.76 | dragon | 149.40.57.134 |
| 90.32 | shadowsocks | 306.8 | 0.4 | 20.68 | 14.98 | 10.0 | 12.1 | 17.76 | dragon | 193.151.160.18 |
| 90.01 | shadowsocks | 239.0 | 2.4 | 22.24 | 14.91 | 10.0 | 12.1 | 17.76 | dragon | 37.19.198.160 |
| 89.93 | shadowsocks | 339.6 | 4.4 | 19.92 | 14.83 | 9.82 | 12.1 | 17.76 | dragon | 216.106.178.169 |
| 89.85 | shadowsocks | 307.7 | 1.0 | 20.65 | 14.96 | 10.0 | 12.1 | 17.76 | dragon | 193.151.160.9 |
| 88.96 | shadowsocks | 301.5 | 2.9 | 20.8 | 14.89 | 10.0 | 12.1 | 17.76 | dragon | 156.146.38.170 |
| 87.18 | shadowsocks | 245.4 | 7.6 | 22.1 | 14.72 | 10.0 | 12.1 | 17.76 | dragon | 172.111.38.72 |
| 86.44 | shadowsocks | 237.1 | 0.6 | 22.29 | 14.98 | 3.81 | 12.1 | 17.76 | dragon | 45.86.51.18 |
| 85.46 | shadowsocks | 313.2 | 2.0 | 20.53 | 14.93 | 9.46 | 12.1 | 17.76 | dragon | 95.215.201.18 |
| 84.91 | shadowsocks | 398.0 | 1.3 | 18.56 | 14.95 | 9.91 | 12.1 | 17.76 | dragon | 38.121.43.18 |
| 84.76 | hysteria2 | 364.5 | 0.2 | 19.34 | 14.99 | 9.73 | 9.64 | 17.76 | dragon | 62.210.124.146 |
| 84.49 | shadowsocks | 358.7 | 0.7 | 19.48 | 14.97 | 9.61 | 12.1 | 17.76 | dragon | 23.150.152.38 |
| 84.19 | shadowsocks | 398.4 | 3.0 | 18.56 | 14.89 | 9.72 | 12.1 | 17.76 | dragon | 38.121.43.225 |
| 83.8 | shadowsocks | 346.3 | 1.3 | 19.76 | 14.95 | 9.35 | 12.1 | 17.76 | dragon | 173.244.56.9 |
| 83.51 | shadowsocks | 347.6 | 7.9 | 19.73 | 14.7 | 9.37 | 12.1 | 17.76 | dragon | 169.197.142.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | 0.822 | 169 | 10000 | prefer |
| dragon3 | 0.897 | 0.923 | 26 | 100 | prefer |
| Surfboard-tg-mixed | 0.757 | 0.812 | 16 | 8704 | prefer |
| dragon2 | 0.689 | 0.619 | 21 | 10000 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 14341 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5045 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5734 | observe |
| barry-far-vless | 0.255 | None | 0 | 5776 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4518 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 22 |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 8 | 11 | - |
| global | False | 206 | 185 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
