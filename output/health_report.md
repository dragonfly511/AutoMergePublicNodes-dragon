# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 19:59:48 |
| 运行耗时 | 299.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 92735 |
| 去重后节点 | 34159 |
| TCP 可达 | 3000 |
| 真实可用 | 204 |
| Verified 输出 | 12 |
| Global 输出 | 208 |
| All 输出 | 34159 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 17.2 |
| geo | 1.7 |
| tcp | 98.7 |
| probe | 95.7 |
| real_test | 43.8 |
| china_check | 24.8 |
| write_verified | 0.0 |
| generate | 17.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56243 |
| vmess | 13958 |
| trojan | 11019 |
| shadowsocks | 9553 |
| hysteria2 | 1605 |
| shadowsocksr | 151 |
| http | 76 |
| socks | 62 |
| hysteria | 32 |
| anytls | 21 |
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
| 87.98 | trojan | 202.0 | 2.0 | 23.1 | 14.92 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.242 |
| 87.91 | trojan | 204.2 | 2.6 | 23.05 | 14.9 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.142 |
| 87.89 | trojan | 205.5 | 2.4 | 23.02 | 14.91 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.121 |
| 87.77 | trojan | 205.9 | 5.5 | 23.01 | 14.8 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.76 |
| 87.75 | shadowsocks | 191.4 | 2.0 | 23.35 | 14.92 | 0.0 | 14.34 | 19.64 | dragon | 95.215.201.18 |
| 86.61 | shadowsocks | 263.5 | 1.4 | 21.68 | 14.95 | 0.0 | 14.34 | 19.64 | dragon | 156.146.38.169 |
| 86.09 | shadowsocks | 261.1 | 2.7 | 21.73 | 14.9 | 0.0 | 14.34 | 19.64 | dragon | 156.146.38.168 |
| 86.07 | trojan | 201.3 | 0.3 | 23.12 | 14.99 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.171 |
| 85.86 | trojan | 209.0 | 1.1 | 22.94 | 14.96 | 0.0 | 12.82 | 19.64 | dragon | 66.163.112.147 |
| 85.13 | shadowsocks | 193.9 | 1.1 | 23.29 | 14.96 | 0.0 | 14.34 | 19.64 | dragon | 38.145.220.193 |
| 84.16 | shadowsocks | 363.5 | 2.3 | 19.36 | 14.91 | 0.0 | 14.34 | 19.64 | dragon | 156.146.38.167 |
| 83.8 | shadowsocks | 249.7 | 2.8 | 22.0 | 14.89 | 2.43 | 14.34 | 19.64 | dragon | 23.150.152.38 |
| 83.23 | trojan | 379.1 | 4.5 | 19.0 | 14.83 | 3.82 | 12.82 | 19.64 | dragon | 66.23.203.21 |
| 83.06 | shadowsocks | 294.4 | 1.8 | 20.96 | 14.93 | 2.69 | 14.34 | 19.64 | dragon | 169.197.142.68 |
| 82.75 | shadowsocks | 264.5 | 2.5 | 21.65 | 14.91 | 0.0 | 14.34 | 19.64 | dragon | 149.22.95.183 |
| 82.59 | hysteria2 | 267.3 | 35.3 | 21.59 | 13.68 | 0.0 | 8.68 | 19.64 | dragon | 66.94.121.46 |
| 81.19 | shadowsocks | 271.2 | 4.0 | 21.5 | 14.85 | 1.09 | 14.34 | 19.64 | dragon | 167.17.67.171 |
| 80.68 | hysteria2 | 290.4 | 2.3 | 21.06 | 14.92 | 0.0 | 8.68 | 19.64 | dragon | 88.216.195.188 |
| 80.4 | shadowsocks | 325.9 | 1.0 | 20.23 | 14.96 | 0.0 | 14.34 | 19.64 | dragon | 185.215.132.18 |
| 79.89 | shadowsocks | 330.1 | 0.3 | 20.14 | 14.99 | 0.0 | 14.34 | 19.64 | dragon | 185.215.132.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.933 | 0.856 | 216 | 10000 | prefer |
| Surfboard-tg-mixed | 0.609 | 0.75 | 12 | 8707 | observe |
| Au1rxx-base64 | 0.505 | 0.5 | 16 | 1751 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi | 0.315 | 1.0 | 2 | 83 | observe |
| mheidari-all | 0.287 | 0.5 | 2 | 15192 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10836 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6137 | observe |
| barry-far-vless | 0.255 | None | 0 | 6348 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4608 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 26 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 5 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 18 | 12 | - |
| global | False | 264 | 208 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
