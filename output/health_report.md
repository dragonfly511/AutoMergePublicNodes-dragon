# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-03 19:43:34 |
| 运行耗时 | 246.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 93456 |
| 去重后节点 | 34229 |
| TCP 可达 | 3000 |
| 真实可用 | 173 |
| Verified 输出 | 11 |
| Global 输出 | 174 |
| All 输出 | 34229 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 97.3 |
| probe | 71.4 |
| real_test | 38.8 |
| china_check | 22.6 |
| write_verified | 0.0 |
| generate | 10.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55787 |
| vmess | 14234 |
| trojan | 12084 |
| shadowsocks | 9281 |
| hysteria2 | 1680 |
| shadowsocksr | 152 |
| http | 91 |
| socks | 79 |
| hysteria | 30 |
| anytls | 23 |
| tuic | 15 |

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
| 89.96 | shadowsocks | 315.0 | 0.7 | 20.48 | 14.97 | 8.26 | 10.91 | 20.0 | dragon | 45.86.51.18 |
| 87.99 | shadowsocks | 295.6 | 11.0 | 20.94 | 14.59 | 7.29 | 10.91 | 20.0 | dragon | 37.19.198.244 |
| 87.44 | hysteria2 | 220.1 | 1.8 | 22.68 | 14.93 | 0.0 | 10.83 | 20.0 | dragon | 88.216.195.188 |
| 86.08 | trojan | 279.8 | 14.4 | 21.3 | 14.46 | 4.56 | 9.24 | 20.0 | dragon | 216.152.155.54 |
| 85.23 | trojan | 280.6 | 3.0 | 21.28 | 14.89 | 3.57 | 9.24 | 20.0 | dragon | 216.152.155.131 |
| 85.14 | trojan | 333.6 | 0.2 | 20.06 | 14.99 | 3.55 | 9.24 | 20.0 | dragon | 66.163.114.132 |
| 84.45 | shadowsocks | 294.1 | 0.3 | 20.97 | 14.99 | 5.55 | 10.91 | 20.0 | dragon | 149.22.95.183 |
| 83.87 | shadowsocks | 250.8 | 0.2 | 21.97 | 14.99 | 0.0 | 10.91 | 20.0 | dragon | 156.146.38.169 |
| 83.49 | trojan | 279.2 | 4.2 | 21.31 | 14.84 | 3.67 | 9.24 | 20.0 | dragon | 216.152.155.59 |
| 83.21 | shadowsocks | 284.0 | 4.1 | 21.2 | 14.85 | 0.65 | 10.91 | 20.0 | dragon | 37.19.198.243 |
| 82.98 | shadowsocks | 253.7 | 3.8 | 21.9 | 14.86 | 0.0 | 10.91 | 20.0 | dragon | 156.146.38.170 |
| 82.81 | shadowsocks | 269.8 | 2.3 | 21.53 | 14.91 | 0.0 | 10.91 | 20.0 | dragon | 156.146.38.168 |
| 82.78 | trojan | 372.7 | 2.1 | 19.15 | 14.92 | 4.55 | 9.24 | 20.0 | dragon | 170.101.101.67 |
| 82.71 | trojan | 367.5 | 9.0 | 19.27 | 14.66 | 4.54 | 9.24 | 20.0 | dragon | 216.152.155.176 |
| 82.66 | shadowsocks | 300.5 | 2.0 | 20.82 | 14.93 | 0.0 | 10.91 | 20.0 | dragon | 156.146.38.167 |
| 82.23 | hysteria2 | 266.4 | 19.5 | 21.61 | 14.27 | 0.0 | 10.83 | 20.0 | dragon | 66.94.121.46 |
| 82.16 | shadowsocks | 308.1 | 3.2 | 20.65 | 14.88 | 0.0 | 10.91 | 20.0 | dragon | 37.19.198.160 |
| 82.1 | trojan | 320.1 | 0.4 | 20.37 | 14.98 | 4.37 | 9.24 | 20.0 | dragon | 66.163.112.142 |
| 81.25 | trojan | 309.3 | 5.3 | 20.62 | 14.8 | 7.3 | 9.24 | 20.0 | dragon | 167.88.61.198 |
| 81.21 | trojan | 322.3 | 7.9 | 20.32 | 14.7 | 4.63 | 9.24 | 20.0 | dragon | 167.88.61.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.939 | 0.863 | 190 | 10000 | prefer |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 6752 | observe |
| Au1rxx-base64 | 0.42 | 0.556 | 9 | 1751 | observe |
| Surfboard-tg-mixed | 0.259 | 0.333 | 3 | 8613 | observe |
| mheidari-all | 0.259 | 0.333 | 3 | 15211 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5017 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10863 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6089 | observe |
| barry-far-vless | 0.255 | None | 0 | 6302 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4753 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 9 | 11 | - |
| global | False | 82 | 174 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
