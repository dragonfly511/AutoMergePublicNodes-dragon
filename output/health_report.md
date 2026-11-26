# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-26 08:42:31 |
| 运行耗时 | 227.0s |
| 订阅源总数 | 110 |
| 健康订阅源 | 88 |
| 原始节点 | 98680 |
| 去重后节点 | 33229 |
| TCP 可达 | 3000 |
| 真实可用 | 219 |
| Verified 输出 | 15 |
| Global 输出 | 223 |
| All 输出 | 33229 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.0 |
| tcp | 78.0 |
| probe | 68.7 |
| real_test | 44.0 |
| china_check | 18.8 |
| write_verified | 0.0 |
| generate | 10.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57281 |
| vmess | 20003 |
| shadowsocks | 10642 |
| trojan | 8297 |
| hysteria2 | 1953 |
| shadowsocksr | 182 |
| socks | 124 |
| http | 109 |
| anytls | 42 |
| hysteria | 31 |
| tuic | 16 |

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
| 98.71 | hysteria2 | 218.5 | 17.4 | 22.72 | 14.35 | 10.0 | 13.64 | 19.0 | dragon | 66.94.121.46 |
| 94.7 | shadowsocks | 267.4 | 2.2 | 21.59 | 14.92 | 10.0 | 13.69 | 19.0 | dragon | 137.184.89.151 |
| 94.4 | shadowsocks | 274.7 | 2.2 | 21.42 | 14.92 | 10.0 | 13.69 | 19.0 | dragon | 23.150.152.38 |
| 92.92 | shadowsocks | 265.7 | 0.5 | 21.63 | 14.98 | 10.0 | 13.69 | 19.0 | dragon | 95.215.201.18 |
| 92.86 | hysteria2 | 325.4 | 33.8 | 20.25 | 13.73 | 10.0 | 13.64 | 19.0 | dragon | 172.87.24.53 |
| 92.12 | shadowsocks | 289.3 | 0.2 | 21.08 | 14.99 | 10.0 | 13.69 | 19.0 | dragon | 169.197.142.68 |
| 91.93 | shadowsocks | 266.6 | 0.1 | 21.61 | 15.0 | 10.0 | 13.69 | 19.0 | dragon | 173.244.56.6 |
| 87.32 | shadowsocks | 283.9 | 1.9 | 21.21 | 14.93 | 7.99 | 13.69 | 19.0 | dragon | 38.143.66.146 |
| 87.13 | shadowsocks | 413.7 | 0.1 | 18.2 | 14.99 | 10.0 | 13.69 | 19.0 | dragon | 156.146.38.170 |
| 86.64 | shadowsocks | 379.2 | 0.8 | 19.0 | 14.97 | 10.0 | 13.69 | 19.0 | dragon | 172.111.38.72 |
| 86.64 | shadowsocks | 382.4 | 0.1 | 18.93 | 15.0 | 10.0 | 13.69 | 19.0 | dragon | 37.19.198.160 |
| 86.56 | trojan | 265.6 | 6.4 | 21.63 | 14.76 | 6.22 | 9.71 | 19.0 | dragon | 167.88.61.52 |
| 86.34 | shadowsocks | 391.1 | 0.2 | 18.72 | 14.99 | 10.0 | 13.69 | 19.0 | dragon | 37.19.198.236 |
| 86.22 | shadowsocks | 322.7 | 2.8 | 20.31 | 14.9 | 9.71 | 13.69 | 19.0 | dragon | 149.22.87.241 |
| 86.22 | shadowsocks | 393.4 | 0.9 | 18.67 | 14.97 | 10.0 | 13.69 | 19.0 | dragon | 37.19.198.243 |
| 86.11 | shadowsocks | 327.9 | 0.0 | 20.19 | 15.0 | 10.0 | 13.69 | 19.0 | dragon | 156.146.38.168 |
| 86.06 | shadowsocks | 333.3 | 0.1 | 20.06 | 15.0 | 9.71 | 13.69 | 19.0 | dragon | 149.22.87.240 |
| 85.93 | shadowsocks | 393.4 | 1.8 | 18.67 | 14.93 | 10.0 | 13.69 | 19.0 | dragon | 45.86.51.18 |
| 85.84 | shadowsocks | 322.1 | 0.9 | 20.32 | 14.97 | 7.35 | 13.69 | 19.0 | dragon | 67.220.73.178 |
| 85.7 | shadowsocks | 406.6 | 16.5 | 18.37 | 14.38 | 10.0 | 13.69 | 19.0 | dragon | 216.106.178.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.971 | 0.895 | 228 | 10000 | prefer |
| Surfboard-tg-mixed | 0.529 | 0.857 | 7 | 8442 | observe |
| dragon2 | 0.465 | 0.714 | 7 | 9795 | observe |
| dragon3 | 0.413 | 0.667 | 9 | 100 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14817 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11584 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5447 | observe |
| barry-far-vless | 0.255 | None | 0 | 5694 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4485 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 17 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 3 |
| 204 | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 15 | - |
| global | False | 249 | 223 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
