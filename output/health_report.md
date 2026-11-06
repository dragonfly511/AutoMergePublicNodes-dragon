# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 19:39:16 |
| 运行耗时 | 299.7s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102663 |
| 去重后节点 | 34652 |
| TCP 可达 | 3000 |
| 真实可用 | 312 |
| Verified 输出 | 14 |
| Global 输出 | 300 |
| All 输出 | 34652 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 89.8 |
| probe | 96.5 |
| real_test | 66.8 |
| china_check | 17.9 |
| write_verified | 0.0 |
| generate | 18.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60429 |
| vmess | 17740 |
| trojan | 12130 |
| shadowsocks | 10039 |
| hysteria2 | 1814 |
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
| 87.21 | shadowsocks | 259.2 | 0.5 | 21.78 | 14.98 | 7.05 | 14.0 | 14.4 | dragon | 156.146.38.167 |
| 85.96 | shadowsocks | 253.7 | 11.7 | 21.9 | 14.56 | 0.0 | 14.0 | 19.5 | dragon3 | 156.146.38.168 |
| 85.91 | shadowsocks | 259.6 | 9.6 | 21.77 | 14.64 | 0.0 | 14.0 | 19.5 | dragon3 | 156.146.38.170 |
| 85.62 | shadowsocks | 259.9 | 3.6 | 21.76 | 14.86 | 0.0 | 14.0 | 19.5 | dragon3 | 67.220.73.178 |
| 85.35 | shadowsocks | 276.1 | 14.3 | 21.39 | 14.46 | 0.0 | 14.0 | 19.5 | dragon3 | 37.19.198.243 |
| 84.79 | shadowsocks | 291.9 | 6.1 | 21.02 | 14.77 | 0.0 | 14.0 | 19.5 | dragon3 | 216.106.178.169 |
| 84.43 | shadowsocks | 281.2 | 22.5 | 21.27 | 14.16 | 0.0 | 14.0 | 19.5 | dragon3 | 45.86.51.18 |
| 84.1 | shadowsocks | 285.7 | 15.0 | 21.16 | 14.44 | 0.0 | 14.0 | 19.5 | dragon3 | 37.19.198.236 |
| 83.66 | shadowsocks | 267.8 | 1.2 | 21.58 | 14.96 | 0.0 | 14.0 | 19.5 | dragon3 | 185.230.230.18 |
| 83.11 | shadowsocks | 263.2 | 11.4 | 21.68 | 14.57 | 0.0 | 14.0 | 16.86 | dragon2 | 37.19.198.244 |
| 82.63 | shadowsocks | 334.5 | 10.9 | 20.04 | 14.59 | 0.0 | 14.0 | 19.5 | dragon3 | 149.40.57.133 |
| 82.37 | shadowsocks | 277.5 | 1.7 | 21.35 | 14.94 | 0.0 | 14.0 | 19.5 | dragon3 | 172.111.38.72 |
| 82.21 | vless | 265.4 | 3.0 | 21.63 | 14.89 | 0.0 | 9.25 | 16.86 | dragon2 | 195.123.235.183 |
| 81.94 | shadowsocks | 353.2 | 17.7 | 19.6 | 14.34 | 0.0 | 14.0 | 19.5 | dragon3 | 38.64.138.135 |
| 81.85 | shadowsocks | 295.7 | 2.2 | 20.93 | 14.92 | 0.0 | 14.0 | 19.5 | dragon3 | 38.128.66.32 |
| 81.27 | shadowsocks | 244.8 | 6.5 | 22.11 | 14.76 | 0.0 | 14.0 | 14.4 | dragon | 198.98.53.130 |
| 81.14 | shadowsocks | 352.9 | 12.4 | 19.61 | 14.53 | 0.0 | 14.0 | 19.5 | dragon3 | 149.40.57.138 |
| 81.04 | shadowsocks | 308.2 | 16.0 | 20.64 | 14.4 | 0.0 | 14.0 | 19.5 | dragon3 | 167.88.62.203 |
| 80.49 | vless | 356.5 | 3.9 | 19.53 | 14.85 | 0.0 | 9.25 | 16.86 | dragon2 | 159.89.87.21 |
| 80.15 | vless | 279.0 | 1.2 | 21.32 | 14.95 | 0.0 | 9.25 | 16.86 | dragon2 | 216.227.161.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.845 | 0.767 | 339 | 10000 | prefer |
| dragon3 | 0.782 | 0.794 | 34 | 100 | prefer |
| dragon | 0.714 | 0.917 | 12 | 10000 | prefer |
| mheidari-all | 0.606 | 0.889 | 9 | 14184 | observe |
| Surfboard-tg-mixed | 0.519 | 1.0 | 5 | 8758 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 179 | observe |
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
| test_one_timeout | 15.0s | - | 56 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 14 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
