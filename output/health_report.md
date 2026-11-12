# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-12 07:31:33 |
| 运行耗时 | 296.8s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 103786 |
| 去重后节点 | 34510 |
| TCP 可达 | 3000 |
| 真实可用 | 293 |
| Verified 输出 | 12 |
| Global 输出 | 295 |
| All 输出 | 34510 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.5 |
| geo | 1.7 |
| tcp | 90.1 |
| probe | 95.0 |
| real_test | 50.3 |
| china_check | 31.2 |
| write_verified | 0.0 |
| generate | 19.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62298 |
| vmess | 17333 |
| trojan | 11499 |
| shadowsocks | 10354 |
| hysteria2 | 1713 |
| http | 299 |
| shadowsocksr | 160 |
| socks | 60 |
| hysteria | 36 |
| tuic | 19 |
| anytls | 15 |

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
| 89.8 | shadowsocks | 306.8 | 8.1 | 20.68 | 14.69 | 9.86 | 13.58 | 17.98 | dragon | 185.215.132.9 |
| 88.93 | shadowsocks | 232.8 | 19.5 | 22.39 | 14.27 | 5.46 | 13.58 | 17.98 | dragon | 38.128.66.32 |
| 88.26 | shadowsocks | 250.6 | 1.9 | 21.98 | 14.93 | 5.62 | 13.58 | 17.98 | dragon | 67.220.73.178 |
| 88.17 | trojan | 252.8 | 4.8 | 21.93 | 14.82 | 9.99 | 8.95 | 17.98 | dragon | 216.152.155.59 |
| 88.04 | shadowsocks | 306.9 | 5.3 | 20.67 | 14.8 | 5.51 | 13.58 | 17.98 | dragon | 167.88.62.203 |
| 88.02 | shadowsocks | 305.0 | 3.6 | 20.72 | 14.87 | 5.37 | 13.58 | 17.98 | dragon | 167.17.67.171 |
| 87.68 | shadowsocks | 306.3 | 15.7 | 20.69 | 14.41 | 5.52 | 13.58 | 17.98 | dragon | 167.88.62.56 |
| 87.26 | shadowsocks | 311.0 | 1.2 | 20.58 | 14.96 | 5.28 | 13.58 | 17.98 | dragon | 172.111.38.72 |
| 86.17 | shadowsocks | 299.0 | 1.3 | 20.86 | 14.95 | 5.12 | 13.58 | 17.98 | dragon | 149.40.57.135 |
| 85.92 | trojan | 268.1 | 2.0 | 21.57 | 14.93 | 9.99 | 8.95 | 17.98 | dragon | 216.152.155.158 |
| 85.15 | shadowsocks | 252.3 | 3.1 | 21.94 | 14.88 | 2.53 | 13.58 | 16.22 | dragon2 | 156.146.38.168 |
| 84.97 | hysteria2 | 286.9 | 9.1 | 21.14 | 14.66 | 0.0 | 12.19 | 17.98 | dragon | 206.189.229.48 |
| 84.94 | shadowsocks | 304.9 | 3.0 | 20.72 | 14.89 | 5.04 | 13.58 | 17.98 | dragon | 149.40.57.133 |
| 84.92 | trojan | 273.9 | 7.4 | 21.44 | 14.72 | 9.99 | 8.95 | 17.98 | dragon | 66.163.114.132 |
| 84.71 | shadowsocks | 254.5 | 13.7 | 21.89 | 14.49 | 2.53 | 13.58 | 16.22 | dragon2 | 156.146.38.167 |
| 84.69 | shadowsocks | 305.9 | 1.5 | 20.7 | 14.94 | 5.31 | 13.58 | 17.98 | dragon | 38.91.100.39 |
| 84.54 | shadowsocks | 271.3 | 9.8 | 21.5 | 14.63 | 4.99 | 13.58 | 17.98 | dragon | 137.184.89.151 |
| 83.9 | hysteria2 | 279.5 | 2.5 | 21.31 | 14.91 | 0.0 | 12.19 | 17.98 | dragon | 66.94.121.46 |
| 83.76 | trojan | 250.7 | 1.3 | 21.97 | 14.95 | 9.99 | 8.95 | 17.98 | dragon | 216.152.155.50 |
| 83.36 | shadowsocks | 328.0 | 0.6 | 20.18 | 14.98 | 5.21 | 13.58 | 17.98 | dragon | 169.197.140.247 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | 0.886 | 167 | 10000 | prefer |
| dragon2 | 0.96 | 0.885 | 148 | 10000 | prefer |
| mheidari-all | 0.557 | 1.0 | 6 | 14005 | observe |
| dragon3 | 0.398 | 0.6 | 10 | 100 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 167 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4981 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2629 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11526 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8783 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6596 | observe |
| barry-far-vless | 0.255 | None | 0 | 6775 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4595 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 9 |
| cn-block | ProxyError | - | 4 |
| speed | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 12 | - |
| global | False | 198 | 295 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
