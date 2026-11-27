# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-27 21:33:03 |
| 运行耗时 | 263.8s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 98609 |
| 去重后节点 | 33554 |
| TCP 可达 | 3000 |
| 真实可用 | 251 |
| Verified 输出 | 24 |
| Global 输出 | 254 |
| All 输出 | 33554 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.8 |
| tcp | 87.7 |
| probe | 82.4 |
| real_test | 53.2 |
| china_check | 19.0 |
| write_verified | 0.0 |
| generate | 13.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56745 |
| vmess | 19949 |
| shadowsocks | 11115 |
| trojan | 8281 |
| hysteria2 | 1940 |
| http | 208 |
| shadowsocksr | 160 |
| socks | 112 |
| anytls | 56 |
| hysteria | 30 |
| tuic | 13 |

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
| 97.8 | shadowsocks | 233.2 | 1.4 | 22.38 | 14.95 | 10.0 | 14.47 | 20.0 | dragon | 156.146.38.170 |
| 96.13 | shadowsocks | 297.5 | 6.1 | 20.89 | 14.77 | 10.0 | 14.47 | 20.0 | dragon | 156.146.38.168 |
| 95.7 | shadowsocks | 279.9 | 2.7 | 21.3 | 14.9 | 10.0 | 14.47 | 20.0 | dragon | 37.19.198.236 |
| 95.56 | shadowsocks | 308.4 | 1.4 | 20.64 | 14.95 | 10.0 | 14.47 | 20.0 | dragon | 172.111.38.72 |
| 94.82 | shadowsocks | 301.9 | 1.0 | 20.79 | 14.96 | 10.0 | 14.47 | 20.0 | dragon | 185.230.230.18 |
| 94.73 | shadowsocks | 338.9 | 4.6 | 19.93 | 14.83 | 10.0 | 14.47 | 20.0 | dragon | 38.128.66.32 |
| 94.19 | trojan | 327.5 | 0.2 | 20.2 | 14.99 | 10.0 | 12.0 | 20.0 | dragon | 66.23.203.21 |
| 94.1 | shadowsocks | 342.0 | 7.0 | 19.86 | 14.74 | 10.0 | 14.47 | 20.0 | dragon | 216.106.178.169 |
| 93.26 | shadowsocks | 315.0 | 7.8 | 20.49 | 14.71 | 10.0 | 14.47 | 20.0 | dragon | 45.86.51.18 |
| 92.93 | shadowsocks | 291.5 | 2.0 | 21.03 | 14.92 | 10.0 | 14.47 | 20.0 | dragon | 95.215.201.18 |
| 92.03 | shadowsocks | 279.5 | 3.0 | 21.31 | 14.89 | 10.0 | 14.47 | 20.0 | dragon | 173.244.56.6 |
| 91.99 | shadowsocks | 289.5 | 8.2 | 21.08 | 14.69 | 10.0 | 14.47 | 20.0 | dragon | 37.19.198.160 |
| 91.87 | shadowsocks | 298.9 | 1.9 | 20.86 | 14.93 | 10.0 | 14.47 | 20.0 | dragon | 193.151.163.18 |
| 91.85 | shadowsocks | 322.2 | 1.0 | 20.32 | 14.96 | 10.0 | 14.47 | 20.0 | dragon | 23.150.152.38 |
| 91.75 | shadowsocks | 298.9 | 0.1 | 20.86 | 15.0 | 10.0 | 14.47 | 20.0 | dragon | 173.244.56.9 |
| 91.57 | shadowsocks | 305.5 | 4.5 | 20.71 | 14.83 | 10.0 | 14.47 | 20.0 | dragon | 149.22.95.183 |
| 91.53 | shadowsocks | 375.7 | 2.6 | 19.08 | 14.9 | 10.0 | 14.47 | 20.0 | dragon | 149.40.57.134 |
| 91.39 | shadowsocks | 337.7 | 4.8 | 19.96 | 14.82 | 10.0 | 14.47 | 20.0 | dragon | 193.151.160.9 |
| 91.06 | shadowsocks | 306.1 | 28.2 | 20.69 | 13.94 | 10.0 | 14.47 | 20.0 | dragon | 137.184.89.151 |
| 91.03 | shadowsocks | 379.0 | 2.5 | 19.01 | 14.91 | 10.0 | 14.47 | 20.0 | dragon | 38.91.100.39 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | 0.821 | 274 | 10000 | prefer |
| dragon3 | 0.657 | 1.0 | 11 | 100 | observe |
| tg-LonUp_M | 0.591 | 1.0 | 9 | 174 | observe |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 8496 | observe |
| dragon2 | 0.446 | 0.625 | 8 | 9931 | observe |
| ermaozi | 0.385 | 0.8 | 5 | 466 | observe |
| mheidari-all | 0.287 | 0.5 | 2 | 14418 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11762 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5391 | observe |
| barry-far-vless | 0.255 | None | 0 | 5607 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 36 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 15 | 24 | - |
| global | False | 129 | 254 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
