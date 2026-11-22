# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-22 19:57:40 |
| 运行耗时 | 322.7s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 102619 |
| 去重后节点 | 35104 |
| TCP 可达 | 3000 |
| 真实可用 | 276 |
| Verified 输出 | 2 |
| Global 输出 | 278 |
| All 输出 | 35104 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.8 |
| tcp | 93.7 |
| probe | 95.3 |
| real_test | 61.1 |
| china_check | 43.7 |
| write_verified | 0.0 |
| generate | 18.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59214 |
| vmess | 18181 |
| shadowsocks | 11772 |
| trojan | 11152 |
| hysteria2 | 1790 |
| socks | 151 |
| shadowsocksr | 151 |
| http | 140 |
| hysteria | 32 |
| tuic | 21 |
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
| 78.86 | vless | 261.7 | 3.8 | 21.72 | 14.86 | 0.0 | 7.14 | 15.14 | dragon2 | 169.40.42.163 |
| 76.67 | shadowsocks | 236.4 | 1.7 | 22.3 | 14.94 | 0.0 | 11.25 | 12.18 | dragon | 37.19.198.244 |
| 76.31 | shadowsocks | 230.9 | 1.2 | 22.43 | 14.95 | 0.0 | 11.25 | 12.18 | dragon | 45.86.51.18 |
| 76.21 | shadowsocks | 231.9 | 3.6 | 22.41 | 14.87 | 0.0 | 11.25 | 12.18 | dragon | 185.230.230.18 |
| 75.78 | shadowsocks | 305.1 | 0.4 | 20.72 | 14.98 | 1.15 | 11.25 | 12.18 | dragon | 149.40.57.138 |
| 75.54 | hysteria2 | 333.7 | 3.1 | 20.05 | 14.89 | 0.0 | 12.0 | 9.6 | mheidari-all | 34.24.25.1 |
| 75.48 | shadowsocks | 267.3 | 1.1 | 21.59 | 14.96 | 0.0 | 11.25 | 12.18 | dragon | 193.151.163.18 |
| 75.21 | shadowsocks | 338.9 | 0.4 | 19.93 | 14.98 | 1.37 | 11.25 | 12.18 | dragon | 158.51.121.221 |
| 74.96 | shadowsocks | 310.9 | 2.9 | 20.58 | 14.89 | 1.17 | 11.25 | 12.18 | dragon | 193.151.160.9 |
| 74.85 | shadowsocks | 230.1 | 0.8 | 22.45 | 14.97 | 0.0 | 11.25 | 12.18 | dragon | 37.19.198.243 |
| 74.62 | shadowsocks | 300.0 | 1.4 | 20.83 | 14.95 | 0.0 | 11.25 | 12.18 | dragon | 193.151.160.18 |
| 74.6 | shadowsocks | 306.6 | 0.4 | 20.68 | 14.99 | 0.0 | 11.25 | 12.18 | dragon | 38.91.107.57 |
| 74.43 | shadowsocks | 313.1 | 0.8 | 20.53 | 14.97 | 0.0 | 11.25 | 12.18 | dragon | 149.40.57.135 |
| 74.24 | shadowsocks | 311.4 | 7.0 | 20.57 | 14.74 | 0.0 | 11.25 | 12.18 | dragon | 38.91.100.39 |
| 74.18 | shadowsocks | 323.6 | 1.0 | 20.29 | 14.96 | 0.0 | 11.25 | 12.18 | dragon | 38.128.66.32 |
| 74.09 | shadowsocks | 235.4 | 1.4 | 22.33 | 14.95 | 0.0 | 11.25 | 12.18 | dragon | 37.19.198.236 |
| 74.09 | shadowsocks | 328.2 | 0.4 | 20.18 | 14.98 | 0.0 | 11.25 | 12.18 | dragon | 15.204.233.41 |
| 74.02 | shadowsocks | 299.8 | 6.8 | 20.84 | 14.75 | 0.0 | 11.25 | 12.18 | dragon | 37.19.198.160 |
| 73.83 | shadowsocks | 328.1 | 7.4 | 20.18 | 14.72 | 0.0 | 11.25 | 12.18 | dragon | 216.106.178.169 |
| 73.41 | shadowsocks | 356.2 | 1.4 | 19.53 | 14.95 | 0.0 | 11.25 | 12.18 | dragon | 149.40.57.134 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | 0.901 | 192 | 10000 | prefer |
| dragon2 | 0.65 | 0.57 | 149 | 10000 | observe |
| dragon3 | 0.517 | 1.0 | 7 | 100 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 14491 | observe |
| ermaozi-get_subscribe | 0.413 | 1.0 | 4 | 318 | observe |
| Surfboard-tg-mixed | 0.385 | 0.5 | 8 | 8739 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.275 | 0.667 | 3 | 167 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5069 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12183 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5664 | observe |
| barry-far-vless | 0.255 | None | 0 | 5881 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4512 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 49 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 4 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 4 | 2 | - |
| global | False | 47 | 278 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
