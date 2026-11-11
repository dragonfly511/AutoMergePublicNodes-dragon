# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-11 06:52:26 |
| 运行耗时 | 258.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102478 |
| 去重后节点 | 34701 |
| TCP 可达 | 3000 |
| 真实可用 | 249 |
| Verified 输出 | 9 |
| Global 输出 | 250 |
| All 输出 | 34701 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 91.5 |
| probe | 83.0 |
| real_test | 38.3 |
| china_check | 21.5 |
| write_verified | 0.0 |
| generate | 14.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60432 |
| vmess | 17405 |
| trojan | 11935 |
| shadowsocks | 10351 |
| hysteria2 | 1767 |
| http | 307 |
| shadowsocksr | 146 |
| socks | 70 |
| hysteria | 32 |
| tuic | 17 |
| anytls | 16 |

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
| 95.08 | shadowsocks | 253.1 | 0.4 | 21.92 | 14.99 | 9.22 | 14.23 | 19.22 | dragon | 172.111.38.72 |
| 94.27 | shadowsocks | 248.3 | 4.2 | 22.03 | 14.84 | 8.45 | 14.23 | 19.22 | dragon | 149.40.57.135 |
| 94.27 | shadowsocks | 249.4 | 1.2 | 22.0 | 14.95 | 8.37 | 14.23 | 19.22 | dragon | 149.40.57.134 |
| 93.97 | shadowsocks | 255.6 | 3.8 | 21.86 | 14.86 | 9.3 | 14.23 | 19.22 | dragon | 38.128.66.32 |
| 93.47 | shadowsocks | 288.0 | 3.2 | 21.11 | 14.88 | 8.53 | 14.23 | 19.22 | dragon | 169.197.140.247 |
| 92.44 | shadowsocks | 340.6 | 3.9 | 19.89 | 14.86 | 9.27 | 14.23 | 19.22 | dragon | 67.220.73.178 |
| 92.36 | shadowsocks | 364.2 | 0.7 | 19.35 | 14.97 | 9.26 | 14.23 | 19.22 | dragon | 66.163.125.120 |
| 91.78 | shadowsocks | 278.6 | 3.9 | 21.33 | 14.85 | 8.17 | 14.23 | 19.22 | dragon | 167.17.67.171 |
| 91.72 | shadowsocks | 397.2 | 1.9 | 18.58 | 14.93 | 9.26 | 14.23 | 19.22 | dragon | 38.91.107.19 |
| 91.0 | shadowsocks | 300.7 | 1.3 | 20.82 | 14.95 | 9.18 | 14.23 | 19.22 | dragon | 38.121.43.18 |
| 90.78 | shadowsocks | 349.4 | 1.7 | 19.69 | 14.94 | 8.28 | 14.23 | 19.22 | dragon | 167.88.62.56 |
| 90.68 | shadowsocks | 307.3 | 0.8 | 20.67 | 14.97 | 9.22 | 14.23 | 19.22 | dragon | 38.22.17.129 |
| 90.64 | shadowsocks | 300.4 | 0.3 | 20.82 | 14.99 | 9.25 | 14.23 | 19.22 | dragon | 38.22.17.139 |
| 90.28 | trojan | 307.6 | 5.9 | 20.66 | 14.78 | 9.46 | 9.44 | 19.22 | dragon | 169.197.140.171 |
| 90.15 | trojan | 302.2 | 0.6 | 20.78 | 14.98 | 8.94 | 9.44 | 19.22 | dragon | 169.197.140.224 |
| 90.08 | trojan | 265.8 | 3.8 | 21.63 | 14.86 | 9.43 | 9.44 | 19.22 | dragon | 66.163.122.113 |
| 89.93 | shadowsocks | 311.6 | 0.4 | 20.57 | 14.98 | 8.54 | 14.23 | 19.22 | dragon | 172.111.36.123 |
| 89.82 | trojan | 306.6 | 0.7 | 20.68 | 14.97 | 9.02 | 9.44 | 19.22 | dragon | 169.197.140.218 |
| 89.6 | trojan | 296.7 | 1.4 | 20.91 | 14.95 | 10.0 | 9.44 | 19.22 | dragon | 170.101.101.19 |
| 89.56 | shadowsocks | 390.8 | 14.3 | 18.73 | 14.46 | 9.26 | 14.23 | 19.22 | dragon | 38.91.107.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | 0.901 | 232 | 10000 | prefer |
| dragon2 | 0.886 | 0.824 | 34 | 10000 | prefer |
| mheidari-all | 0.529 | 0.857 | 7 | 13964 | observe |
| dragon3 | 0.404 | 1.0 | 4 | 100 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8415 | observe |
| ermaozi | 0.335 | 1.0 | 2 | 601 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4955 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2620 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11127 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6298 | observe |
| barry-far-vless | 0.255 | None | 0 | 6562 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 9 | - |
| global | False | 225 | 250 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
