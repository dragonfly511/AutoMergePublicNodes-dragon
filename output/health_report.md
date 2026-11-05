# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 20:11:30 |
| 运行耗时 | 244.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 92601 |
| 去重后节点 | 34217 |
| TCP 可达 | 3000 |
| 真实可用 | 150 |
| Verified 输出 | 11 |
| Global 输出 | 151 |
| All 输出 | 34217 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 93.2 |
| probe | 72.4 |
| real_test | 40.8 |
| china_check | 20.7 |
| write_verified | 0.0 |
| generate | 11.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56174 |
| vmess | 14333 |
| trojan | 10493 |
| shadowsocks | 9504 |
| hysteria2 | 1607 |
| http | 190 |
| shadowsocksr | 149 |
| socks | 88 |
| hysteria | 33 |
| tuic | 16 |
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
| 95.82 | trojan | 253.5 | 6.8 | 21.91 | 14.74 | 10.0 | 12.29 | 19.38 | dragon | 216.152.155.158 |
| 93.78 | trojan | 283.2 | 6.9 | 21.22 | 14.74 | 8.65 | 12.29 | 19.38 | dragon | 216.152.155.131 |
| 91.79 | trojan | 336.1 | 1.8 | 20.0 | 14.93 | 10.0 | 12.29 | 19.38 | dragon | 66.23.203.21 |
| 91.04 | shadowsocks | 280.1 | 13.7 | 21.29 | 14.49 | 10.0 | 14.05 | 19.38 | dragon | 38.145.220.193 |
| 89.52 | shadowsocks | 238.5 | 0.0 | 22.26 | 15.0 | 2.83 | 14.05 | 19.38 | dragon | 156.146.38.170 |
| 89.05 | shadowsocks | 335.4 | 8.4 | 20.01 | 14.69 | 10.0 | 14.05 | 19.38 | dragon | 103.11.76.248 |
| 88.77 | trojan | 309.1 | 5.9 | 20.62 | 14.78 | 8.34 | 12.29 | 19.38 | dragon | 66.163.112.171 |
| 88.1 | trojan | 353.9 | 3.9 | 19.59 | 14.85 | 7.19 | 12.29 | 19.38 | dragon | 216.152.155.54 |
| 87.71 | trojan | 312.9 | 3.3 | 20.54 | 14.88 | 8.38 | 12.29 | 19.38 | dragon | 66.163.112.13 |
| 87.71 | trojan | 330.8 | 5.0 | 20.12 | 14.81 | 8.03 | 12.29 | 19.38 | dragon | 66.163.112.147 |
| 87.64 | shadowsocks | 256.4 | 9.6 | 21.84 | 14.64 | 3.29 | 14.05 | 19.38 | dragon | 156.146.38.168 |
| 87.53 | trojan | 306.1 | 4.2 | 20.69 | 14.84 | 8.35 | 12.29 | 19.38 | dragon | 216.106.186.82 |
| 87.31 | trojan | 330.4 | 0.5 | 20.13 | 14.98 | 8.36 | 12.29 | 19.38 | dragon | 66.163.112.76 |
| 87.27 | trojan | 309.2 | 8.3 | 20.62 | 14.69 | 7.19 | 12.29 | 19.38 | dragon | 66.163.112.142 |
| 87.15 | trojan | 361.9 | 5.2 | 19.4 | 14.81 | 8.02 | 12.29 | 19.38 | dragon | 169.197.140.171 |
| 87.05 | trojan | 363.5 | 2.0 | 19.36 | 14.92 | 8.31 | 12.29 | 19.38 | dragon | 216.238.80.100 |
| 86.04 | trojan | 307.0 | 1.7 | 20.67 | 14.94 | 6.41 | 12.29 | 19.38 | dragon | 66.163.112.242 |
| 86.01 | trojan | 300.6 | 1.1 | 20.82 | 14.96 | 5.34 | 12.29 | 19.38 | dragon | 66.163.112.31 |
| 85.98 | trojan | 354.2 | 23.2 | 19.58 | 14.13 | 7.67 | 12.29 | 19.38 | dragon | 169.197.140.245 |
| 85.82 | shadowsocks | 309.8 | 1.1 | 20.61 | 14.96 | 1.82 | 14.05 | 19.38 | dragon | 185.230.230.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.89 | 0.814 | 156 | 10000 | prefer |
| Au1rxx-base64 | 0.635 | 0.571 | 21 | 1751 | observe |
| mheidari-all | 0.529 | 0.857 | 7 | 14461 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| Surfboard-tg-mixed | 0.32 | 0.5 | 4 | 8690 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 177 | observe |
| peasoft-NoMoreWalls | 0.259 | 1.0 | 1 | 96 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10977 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6358 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 18 |
| test_one_timeout | 15.0s | - | 12 |
| geo | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 11 | - |
| global | False | 191 | 151 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
