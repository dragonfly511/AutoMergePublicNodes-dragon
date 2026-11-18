# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-18 07:48:05 |
| 运行耗时 | 245.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101649 |
| 去重后节点 | 35043 |
| TCP 可达 | 3000 |
| 真实可用 | 205 |
| Verified 输出 | 27 |
| Global 输出 | 207 |
| All 输出 | 35043 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 96.1 |
| probe | 71.2 |
| real_test | 39.4 |
| china_check | 19.9 |
| write_verified | 0.0 |
| generate | 11.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59399 |
| vmess | 17944 |
| trojan | 11134 |
| shadowsocks | 11043 |
| hysteria2 | 1714 |
| shadowsocksr | 157 |
| http | 134 |
| socks | 84 |
| hysteria | 16 |
| tuic | 13 |
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
| 89.36 | vless | 335.0 | 0.1 | 20.02 | 15.0 | 10.0 | 12.08 | 19.84 | dragon | 69.48.201.136 |
| 89.02 | shadowsocks | 246.0 | 0.3 | 22.08 | 14.99 | 2.22 | 13.89 | 19.84 | dragon | 156.146.38.169 |
| 87.83 | shadowsocks | 298.3 | 0.1 | 20.87 | 15.0 | 2.23 | 13.89 | 19.84 | dragon | 156.146.38.168 |
| 87.07 | shadowsocks | 247.0 | 1.9 | 22.06 | 14.93 | 2.13 | 13.89 | 19.84 | dragon | 216.106.178.169 |
| 85.92 | shadowsocks | 300.5 | 1.0 | 20.82 | 14.96 | 2.06 | 13.89 | 19.84 | dragon | 185.230.230.18 |
| 85.83 | shadowsocks | 304.4 | 7.4 | 20.73 | 14.72 | 2.15 | 13.89 | 19.84 | dragon | 167.88.62.203 |
| 85.69 | shadowsocks | 318.9 | 2.3 | 20.4 | 14.91 | 2.32 | 13.89 | 19.84 | dragon | 38.64.138.135 |
| 85.59 | shadowsocks | 288.8 | 1.7 | 21.09 | 14.94 | 2.51 | 13.89 | 19.84 | dragon | 172.111.36.123 |
| 85.55 | shadowsocks | 249.6 | 1.2 | 22.0 | 14.96 | 1.98 | 13.89 | 19.84 | dragon | 38.145.220.193 |
| 85.36 | shadowsocks | 381.0 | 0.5 | 18.96 | 14.98 | 2.19 | 13.89 | 19.84 | dragon | 167.88.62.56 |
| 84.37 | shadowsocks | 312.9 | 6.6 | 20.53 | 14.75 | 2.03 | 13.89 | 19.84 | dragon | 172.111.38.72 |
| 84.33 | shadowsocks | 328.4 | 2.1 | 20.18 | 14.92 | 0.0 | 13.89 | 19.84 | dragon | 67.220.73.178 |
| 84.33 | shadowsocks | 348.9 | 0.1 | 19.7 | 15.0 | 2.49 | 13.89 | 19.84 | dragon | 38.22.17.219 |
| 84.09 | shadowsocks | 244.2 | 0.2 | 22.13 | 14.99 | 2.24 | 13.89 | 19.84 | dragon | 156.146.38.170 |
| 83.98 | hysteria2 | 380.2 | 2.8 | 18.98 | 14.9 | 0.0 | 12.86 | 19.84 | dragon | 66.94.121.46 |
| 83.96 | shadowsocks | 318.1 | 4.4 | 20.42 | 14.83 | 2.34 | 13.89 | 19.84 | dragon | 193.151.160.18 |
| 83.93 | shadowsocks | 347.1 | 0.4 | 19.74 | 14.98 | 2.46 | 13.89 | 19.84 | dragon | 38.22.17.139 |
| 83.85 | shadowsocks | 350.2 | 0.2 | 19.67 | 14.99 | 2.34 | 13.89 | 19.84 | dragon | 167.88.63.39 |
| 83.8 | shadowsocks | 355.3 | 1.8 | 19.55 | 14.93 | 2.31 | 13.89 | 19.84 | dragon | 38.22.17.129 |
| 83.71 | shadowsocks | 319.1 | 0.5 | 20.39 | 14.98 | 2.41 | 13.89 | 19.84 | dragon | 193.151.160.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.968 | 0.892 | 195 | 10000 | prefer |
| dragon2 | 0.804 | 0.741 | 27 | 10000 | prefer |
| tg-LonUp_M | 0.484 | 1.0 | 6 | 166 | observe |
| mheidari-all | 0.349 | 0.667 | 3 | 14456 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| dragon3 | 0.315 | 1.0 | 2 | 100 | observe |
| ermaozi | 0.275 | 1.0 | 1 | 502 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4928 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2790 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11512 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 5907 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4458 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 23 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 19 | 27 | - |
| global | False | 215 | 207 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
