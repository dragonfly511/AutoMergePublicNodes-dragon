# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 06:21:22 |
| 运行耗时 | 216.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 90738 |
| 去重后节点 | 33665 |
| TCP 可达 | 3000 |
| 真实可用 | 202 |
| Verified 输出 | 50 |
| Global 输出 | 203 |
| All 输出 | 33665 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.2 |
| tcp | 67.4 |
| probe | 63.5 |
| real_test | 43.7 |
| china_check | 25.3 |
| write_verified | 0.0 |
| generate | 10.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54536 |
| vmess | 13973 |
| trojan | 11204 |
| shadowsocks | 8939 |
| hysteria2 | 1498 |
| http | 335 |
| shadowsocksr | 159 |
| socks | 54 |
| tuic | 15 |
| anytls | 13 |
| hysteria | 12 |

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
| 93.07 | trojan | 273.9 | 0.6 | 21.44 | 14.98 | 10.0 | 14.15 | 20.0 | dragon | 66.163.122.113 |
| 92.74 | vless | 253.1 | 0.3 | 21.92 | 14.99 | 10.0 | 10.83 | 20.0 | dragon | 185.95.231.156 |
| 89.07 | hysteria2 | 211.9 | 2.9 | 22.87 | 14.89 | 5.18 | 12.63 | 20.0 | dragon | 129.213.91.185 |
| 87.53 | shadowsocks | 238.4 | 2.9 | 22.26 | 14.89 | 5.19 | 14.19 | 20.0 | dragon | 37.19.198.243 |
| 87.42 | shadowsocks | 245.4 | 1.0 | 22.1 | 14.96 | 5.17 | 14.19 | 20.0 | dragon | 37.19.198.236 |
| 87.4 | shadowsocks | 245.2 | 1.5 | 22.1 | 14.94 | 5.17 | 14.19 | 20.0 | dragon | 37.19.198.244 |
| 87.31 | trojan | 522.5 | 0.4 | 15.68 | 14.98 | 10.0 | 14.15 | 20.0 | dragon | 66.163.122.7 |
| 86.96 | shadowsocks | 243.2 | 1.6 | 22.15 | 14.94 | 5.18 | 14.19 | 20.0 | dragon | 193.151.163.18 |
| 86.88 | shadowsocks | 269.0 | 1.7 | 21.55 | 14.94 | 5.2 | 14.19 | 20.0 | dragon | 37.19.198.160 |
| 86.44 | shadowsocks | 261.7 | 2.2 | 21.72 | 14.92 | 5.11 | 14.19 | 20.0 | dragon | 45.86.51.18 |
| 86.42 | shadowsocks | 265.4 | 1.2 | 21.64 | 14.96 | 4.9 | 14.19 | 20.0 | dragon | 156.146.38.168 |
| 86.39 | shadowsocks | 263.6 | 2.2 | 21.68 | 14.92 | 5.1 | 14.19 | 20.0 | dragon | 185.230.230.18 |
| 86.09 | shadowsocks | 274.0 | 1.4 | 21.43 | 14.95 | 5.02 | 14.19 | 20.0 | dragon | 193.151.160.9 |
| 85.97 | shadowsocks | 266.5 | 9.4 | 21.61 | 14.65 | 4.94 | 14.19 | 20.0 | dragon | 156.146.38.167 |
| 85.95 | shadowsocks | 279.3 | 1.8 | 21.31 | 14.93 | 5.02 | 14.19 | 20.0 | dragon | 193.151.160.18 |
| 85.63 | hysteria2 | 285.8 | 1.5 | 21.16 | 14.94 | 6.75 | 12.63 | 20.0 | dragon | 179.255.103.55 |
| 85.33 | shadowsocks | 265.3 | 0.1 | 21.64 | 15.0 | 4.89 | 14.19 | 20.0 | dragon | 156.146.38.169 |
| 85.01 | trojan | 357.0 | 2.1 | 19.51 | 14.92 | 10.0 | 14.15 | 20.0 | dragon | 167.88.61.20 |
| 84.7 | shadowsocks | 273.0 | 10.5 | 21.46 | 14.61 | 4.94 | 14.19 | 20.0 | dragon | 156.146.38.170 |
| 84.68 | trojan | 374.7 | 0.9 | 19.1 | 14.97 | 10.0 | 14.15 | 20.0 | dragon | 167.82.64.120 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.931 | 174 | 10000 | prefer |
| Au1rxx-base64 | 0.829 | 0.778 | 27 | 1751 | prefer |
| Surfboard-tg-mixed | 0.749 | 0.923 | 13 | 7827 | prefer |
| mheidari-all | 0.48 | 1.0 | 4 | 14594 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| ermaozi | 0.28 | 1.0 | 1 | 622 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10517 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5680 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| geo | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 39 | 50 | - |
| global | False | 231 | 203 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
