# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-24 10:11:25 |
| 运行耗时 | 251.1s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 99167 |
| 去重后节点 | 34154 |
| TCP 可达 | 3000 |
| 真实可用 | 56 |
| Verified 输出 | 18 |
| Global 输出 | 269 |
| All 输出 | 34154 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.7 |
| tcp | 94.0 |
| probe | 90.2 |
| real_test | 24.0 |
| china_check | 18.7 |
| write_verified | 0.0 |
| generate | 15.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58068 |
| vmess | 19540 |
| shadowsocks | 10645 |
| trojan | 8383 |
| hysteria2 | 1911 |
| http | 209 |
| shadowsocksr | 191 |
| socks | 130 |
| anytls | 42 |
| hysteria | 32 |
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
| 97.11 | trojan | 217.8 | 4.6 | 22.74 | 14.83 | 7.84 | 14.2 | 20.0 | dragon | 167.88.61.52 |
| 96.67 | trojan | 237.3 | 1.4 | 22.28 | 14.95 | 7.74 | 14.2 | 20.0 | dragon | 167.88.61.175 |
| 95.67 | shadowsocks | 228.8 | 1.9 | 22.48 | 14.93 | 8.2 | 14.12 | 20.0 | dragon | 173.244.56.9 |
| 94.77 | trojan | 218.9 | 0.0 | 22.71 | 15.0 | 5.36 | 14.2 | 20.0 | dragon | 167.88.61.193 |
| 94.52 | trojan | 222.1 | 0.8 | 22.64 | 14.97 | 5.21 | 14.2 | 20.0 | dragon | 167.88.61.198 |
| 94.45 | trojan | 221.8 | 2.7 | 22.64 | 14.9 | 5.21 | 14.2 | 20.0 | dragon | 167.88.61.20 |
| 90.09 | trojan | 218.4 | 1.8 | 22.72 | 14.93 | 5.18 | 14.2 | 20.0 | dragon | 167.88.61.85 |
| 85.61 | shadowsocks | 313.8 | 0.8 | 20.51 | 14.97 | 7.38 | 14.12 | 20.0 | dragon | 149.22.87.204 |
| 84.88 | hysteria2 | 236.2 | 0.6 | 22.31 | 14.98 | 1.91 | 12.69 | 20.0 | dragon | 8.209.247.109 |
| 82.94 | hysteria2 | 456.6 | 0.5 | 17.21 | 14.98 | 6.14 | 12.69 | 20.0 | dragon | 152.67.115.203 |
| 82.04 | shadowsocks | 456.3 | 0.3 | 17.22 | 14.99 | 6.82 | 14.12 | 20.0 | dragon | 38.91.107.19 |
| 81.97 | hysteria2 | 382.9 | 1.0 | 18.91 | 14.96 | 3.18 | 12.69 | 20.0 | dragon | 34.24.25.1 |
| 81.92 | trojan | 531.2 | 1.4 | 15.48 | 14.95 | 5.67 | 14.2 | 20.0 | dragon | 69.164.240.85 |
| 80.18 | shadowsocks | 362.0 | 3.1 | 19.4 | 14.88 | 7.01 | 14.12 | 20.0 | dragon | 169.197.140.247 |
| 80.17 | shadowsocks | 589.8 | 0.1 | 14.12 | 15.0 | 9.33 | 14.12 | 20.0 | dragon | 23.166.88.189 |
| 79.78 | shadowsocks | 595.3 | 0.3 | 14.0 | 14.99 | 9.24 | 14.12 | 20.0 | dragon | 62.93.179.117 |
| 79.54 | shadowsocks | 596.9 | 18.6 | 13.96 | 14.3 | 6.83 | 14.12 | 20.0 | dragon | 15.204.247.244 |
| 79.5 | shadowsocks | 622.8 | 2.4 | 13.36 | 14.91 | 9.49 | 14.12 | 20.0 | dragon | 216.172.144.199 |
| 79.46 | trojan | 464.4 | 4.6 | 17.03 | 14.83 | 0.0 | 14.2 | 20.0 | dragon | 66.23.203.21 |
| 78.28 | shadowsocks | 479.7 | 0.4 | 16.67 | 14.99 | 8.76 | 14.12 | 20.0 | dragon | 43.160.213.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.7 | 0.623 | 77 | 10000 | prefer |
| Surfboard-tg-mixed | 0.593 | 1.0 | 7 | 8220 | observe |
| ermaozi | 0.567 | 1.0 | 8 | 460 | observe |
| mheidari-all | 0.391 | 1.0 | 2 | 15386 | observe |
| dragon2 | 0.335 | 1.0 | 1 | 10000 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 167 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5064 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11363 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5327 | observe |
| barry-far-vless | 0.255 | None | 0 | 5849 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4587 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 18 |
| test_one_timeout | 15.0s | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 11 | 18 | - |
| global | True | 269 | 57 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
