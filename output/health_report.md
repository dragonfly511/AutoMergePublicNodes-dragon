# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-10 19:56:37 |
| 运行耗时 | 258.3s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 102872 |
| 去重后节点 | 34243 |
| TCP 可达 | 3000 |
| 真实可用 | 222 |
| Verified 输出 | 13 |
| Global 输出 | 225 |
| All 输出 | 34243 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.6 |
| tcp | 91.8 |
| probe | 78.6 |
| real_test | 47.4 |
| china_check | 18.6 |
| write_verified | 0.0 |
| generate | 13.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61523 |
| vmess | 17515 |
| trojan | 11148 |
| shadowsocks | 10289 |
| hysteria2 | 1842 |
| http | 279 |
| shadowsocksr | 154 |
| socks | 55 |
| hysteria | 30 |
| anytls | 19 |
| tuic | 18 |

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
| 96.52 | shadowsocks | 230.0 | 2.3 | 22.45 | 14.91 | 10.0 | 13.66 | 20.0 | dragon | 95.215.201.18 |
| 95.78 | trojan | 203.9 | 5.1 | 23.06 | 14.81 | 7.33 | 13.08 | 20.0 | dragon | 66.163.112.171 |
| 95.45 | trojan | 211.6 | 17.0 | 22.88 | 14.36 | 7.63 | 13.08 | 20.0 | dragon | 66.163.112.31 |
| 94.07 | trojan | 202.9 | 1.1 | 23.08 | 14.96 | 7.34 | 13.08 | 20.0 | dragon | 66.163.112.142 |
| 94.03 | trojan | 233.1 | 5.3 | 22.38 | 14.8 | 8.27 | 13.08 | 20.0 | dragon | 167.88.61.193 |
| 93.61 | trojan | 201.4 | 1.4 | 23.12 | 14.95 | 7.34 | 13.08 | 20.0 | dragon | 66.163.112.121 |
| 92.88 | trojan | 233.2 | 2.1 | 22.38 | 14.92 | 10.0 | 13.08 | 20.0 | dragon | 167.88.61.85 |
| 92.76 | trojan | 210.2 | 2.9 | 22.91 | 14.89 | 7.62 | 13.08 | 20.0 | dragon | 66.163.112.242 |
| 91.6 | trojan | 208.3 | 1.9 | 22.96 | 14.93 | 7.59 | 13.08 | 20.0 | dragon | 66.163.112.13 |
| 90.91 | trojan | 204.3 | 1.6 | 23.05 | 14.94 | 7.33 | 13.08 | 20.0 | dragon | 66.163.112.76 |
| 90.59 | trojan | 227.2 | 18.8 | 22.52 | 14.29 | 8.37 | 13.08 | 20.0 | dragon | 167.88.61.198 |
| 90.21 | trojan | 232.7 | 5.0 | 22.39 | 14.81 | 8.06 | 13.08 | 20.0 | dragon | 167.88.61.20 |
| 88.8 | trojan | 270.3 | 0.6 | 21.52 | 14.98 | 4.96 | 13.08 | 20.0 | dragon | 167.88.61.52 |
| 88.74 | trojan | 420.0 | 2.6 | 18.06 | 14.9 | 8.34 | 13.08 | 20.0 | dragon | 66.23.203.21 |
| 87.18 | shadowsocks | 199.0 | 3.9 | 23.17 | 14.85 | 0.0 | 13.66 | 20.0 | dragon | 137.184.89.151 |
| 87.04 | trojan | 456.2 | 7.7 | 17.22 | 14.71 | 7.38 | 13.08 | 20.0 | dragon | 66.163.112.147 |
| 86.81 | shadowsocks | 217.9 | 2.1 | 22.73 | 14.92 | 0.0 | 13.66 | 20.0 | dragon | 169.197.142.68 |
| 86.58 | trojan | 382.5 | 21.4 | 18.92 | 14.2 | 10.0 | 13.08 | 20.0 | dragon | 169.197.140.214 |
| 86.55 | shadowsocks | 228.4 | 2.7 | 22.49 | 14.9 | 0.0 | 13.66 | 20.0 | dragon | 23.150.152.38 |
| 86.36 | trojan | 394.1 | 25.1 | 18.66 | 14.06 | 10.0 | 13.08 | 20.0 | dragon | 169.197.140.224 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.961 | 0.885 | 217 | 10000 | prefer |
| dragon2 | 0.745 | 0.765 | 17 | 10000 | prefer |
| Surfboard-tg-mixed | 0.583 | 0.643 | 14 | 8562 | observe |
| mheidari-all | 0.529 | 0.857 | 7 | 14274 | observe |
| dragon3 | 0.404 | 1.0 | 4 | 100 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4955 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2620 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11116 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6459 | observe |
| barry-far-vless | 0.255 | None | 0 | 6491 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4667 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 11 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 13 | - |
| global | False | 265 | 225 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
