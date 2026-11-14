# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-14 06:49:36 |
| 运行耗时 | 271.6s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 103939 |
| 去重后节点 | 34517 |
| TCP 可达 | 3000 |
| 真实可用 | 82 |
| Verified 输出 | 15 |
| Global 输出 | 246 |
| All 输出 | 34517 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 92.8 |
| probe | 67.8 |
| real_test | 39.9 |
| china_check | 54.0 |
| generate | 10.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61405 |
| vmess | 17671 |
| trojan | 11690 |
| shadowsocks | 10805 |
| hysteria2 | 1751 |
| http | 291 |
| shadowsocksr | 172 |
| socks | 71 |
| hysteria | 37 |
| tuic | 25 |
| anytls | 21 |

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
| 84.11 | hysteria2 | 274.9 | 0.5 | 21.41 | 14.98 | 0.0 | 13.24 | 18.52 | dragon | 66.94.121.46 |
| 82.67 | hysteria2 | 294.7 | 1.3 | 20.96 | 14.95 | 0.0 | 13.24 | 18.52 | dragon | 206.189.229.48 |
| 82.35 | shadowsocks | 360.1 | 0.9 | 19.44 | 14.97 | 2.41 | 13.59 | 18.52 | dragon | 38.22.17.219 |
| 81.5 | hysteria2 | 401.3 | 1.1 | 18.49 | 14.96 | 0.38 | 13.24 | 18.52 | dragon | 34.24.25.1 |
| 79.03 | trojan | 302.9 | 29.3 | 20.77 | 13.9 | 10.0 | 7.5 | 18.52 | dragon | 216.106.186.32 |
| 78.03 | shadowsocks | 383.9 | 0.3 | 18.89 | 14.99 | 0.0 | 13.59 | 18.52 | dragon | 169.197.140.247 |
| 77.93 | vless | 363.0 | 1.5 | 19.38 | 14.94 | 4.18 | 10.41 | 18.52 | dragon | 69.48.201.136 |
| 77.12 | vless | 482.4 | 3.1 | 16.61 | 14.88 | 7.96 | 10.41 | 18.52 | dragon | 200.102.183.57 |
| 76.36 | shadowsocks | 289.0 | 0.7 | 21.09 | 14.97 | 0.76 | 13.59 | 18.52 | dragon | 95.215.201.18 |
| 76.06 | hysteria2 | 479.1 | 6.0 | 16.69 | 14.78 | 0.0 | 13.24 | 18.52 | dragon | 5.129.235.85 |
| 74.85 | hysteria2 | 514.0 | 2.3 | 15.88 | 14.91 | 0.0 | 13.24 | 18.52 | dragon | 130.49.161.70 |
| 72.48 | shadowsocks | 330.2 | 0.3 | 20.14 | 14.99 | 0.0 | 13.59 | 8.26 | dragon3 | 167.88.62.56 |
| 72.04 | shadowsocks | 245.2 | 2.4 | 22.1 | 14.91 | 0.0 | 13.59 | 8.26 | dragon3 | 38.145.220.193 |
| 71.74 | hysteria2 | 593.3 | 0.9 | 14.04 | 14.97 | 0.0 | 13.24 | 18.52 | dragon | 162.249.125.133 |
| 71.44 | shadowsocks | 496.8 | 1.2 | 16.28 | 14.95 | 0.0 | 13.59 | 18.52 | dragon | 193.29.139.168 |
| 71.38 | shadowsocks | 332.8 | 27.8 | 20.07 | 13.96 | 0.0 | 13.59 | 8.26 | dragon3 | 167.17.67.171 |
| 71.06 | vless | 780.8 | 9.4 | 9.7 | 14.65 | 8.56 | 10.41 | 18.52 | dragon | 104.171.135.229 |
| 71.04 | shadowsocks | 274.1 | 3.4 | 21.43 | 14.87 | 0.0 | 13.59 | 8.26 | dragon3 | 137.184.89.151 |
| 70.6 | vless | 649.5 | 0.6 | 12.74 | 14.98 | 8.31 | 10.41 | 18.52 | dragon | 91.107.247.173 |
| 70.51 | shadowsocks | 272.2 | 1.7 | 21.48 | 14.93 | 0.0 | 13.59 | 8.26 | dragon3 | 23.150.152.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.958 | 0.897 | 39 | 10000 | prefer |
| dragon | 0.734 | 0.66 | 50 | 10000 | prefer |
| dragon3 | 0.536 | 0.625 | 16 | 100 | observe |
| ermaozi | 0.335 | 1.0 | 2 | 597 | observe |
| mheidari-all | 0.287 | 0.5 | 2 | 14251 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 471 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4900 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11507 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8942 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6457 | observe |
| barry-far-vless | 0.255 | None | 0 | 6640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4551 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| speed | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 15 | 2 | 0.5 |
| global | True | 246 | 83 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
