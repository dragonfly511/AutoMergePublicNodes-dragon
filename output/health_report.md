# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-12 20:13:21 |
| 运行耗时 | 236.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 103598 |
| 去重后节点 | 34704 |
| TCP 可达 | 3000 |
| 真实可用 | 228 |
| Verified 输出 | 14 |
| Global 输出 | 229 |
| All 输出 | 34704 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 84.0 |
| probe | 69.0 |
| real_test | 41.3 |
| china_check | 24.2 |
| write_verified | 0.0 |
| generate | 10.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61644 |
| vmess | 17629 |
| trojan | 11566 |
| shadowsocks | 10544 |
| hysteria2 | 1695 |
| http | 252 |
| shadowsocksr | 144 |
| socks | 55 |
| hysteria | 34 |
| tuic | 19 |
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
| 92.62 | trojan | 264.3 | 0.9 | 21.66 | 14.97 | 9.18 | 12.79 | 19.24 | dragon | 167.88.61.85 |
| 92.59 | trojan | 260.5 | 0.5 | 21.75 | 14.98 | 9.18 | 12.79 | 19.24 | dragon | 167.88.61.193 |
| 92.46 | trojan | 271.5 | 1.8 | 21.49 | 14.93 | 9.19 | 12.79 | 19.24 | dragon | 167.88.61.20 |
| 91.58 | trojan | 263.0 | 6.5 | 21.69 | 14.76 | 9.2 | 12.79 | 19.24 | dragon | 167.88.61.52 |
| 91.33 | trojan | 297.8 | 0.4 | 20.88 | 14.99 | 9.13 | 12.79 | 19.24 | dragon | 66.163.112.121 |
| 91.31 | trojan | 295.3 | 0.2 | 20.94 | 14.99 | 9.14 | 12.79 | 19.24 | dragon | 66.163.112.242 |
| 91.17 | trojan | 293.5 | 7.2 | 20.98 | 14.73 | 9.12 | 12.79 | 19.24 | dragon | 66.163.112.142 |
| 91.12 | trojan | 290.7 | 0.5 | 21.05 | 14.98 | 9.13 | 12.79 | 19.24 | dragon | 66.163.112.31 |
| 89.66 | trojan | 285.1 | 0.9 | 21.18 | 14.97 | 7.24 | 12.79 | 19.24 | dragon | 66.163.112.147 |
| 89.19 | trojan | 283.8 | 0.3 | 21.21 | 14.99 | 6.66 | 12.79 | 19.24 | dragon | 66.163.112.13 |
| 88.5 | trojan | 272.0 | 6.1 | 21.48 | 14.77 | 9.18 | 12.79 | 19.24 | dragon | 167.88.61.175 |
| 87.4 | shadowsocks | 257.7 | 41.7 | 21.81 | 13.43 | 5.86 | 13.56 | 19.24 | dragon | 38.143.66.146 |
| 86.32 | shadowsocks | 342.0 | 1.0 | 19.86 | 14.96 | 5.52 | 13.56 | 19.24 | dragon | 169.197.142.68 |
| 85.03 | trojan | 287.3 | 1.9 | 21.13 | 14.93 | 7.19 | 12.79 | 19.24 | dragon | 66.163.112.76 |
| 84.69 | trojan | 450.0 | 0.9 | 17.36 | 14.97 | 8.89 | 12.79 | 19.24 | dragon | 66.23.203.21 |
| 84.11 | shadowsocks | 219.0 | 6.0 | 22.71 | 14.78 | 9.2 | 13.56 | 7.96 | dragon3 | 38.145.220.193 |
| 82.82 | trojan | 474.4 | 1.1 | 16.8 | 14.96 | 8.56 | 12.79 | 19.24 | dragon | 169.197.140.218 |
| 82.66 | trojan | 476.0 | 2.6 | 16.76 | 14.9 | 8.57 | 12.79 | 19.24 | dragon | 169.197.140.245 |
| 82.62 | hysteria2 | 264.8 | 1.3 | 21.65 | 14.95 | 7.06 | 12.19 | 19.2 | dragon2 | 8.209.247.109 |
| 82.56 | trojan | 481.1 | 7.3 | 16.64 | 14.73 | 8.57 | 12.79 | 19.24 | dragon | 169.197.140.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.982 | 0.908 | 131 | 10000 | prefer |
| dragon | 0.792 | 0.715 | 123 | 10000 | prefer |
| dragon3 | 0.658 | 0.857 | 14 | 100 | observe |
| mheidari-all | 0.465 | 0.714 | 7 | 14228 | observe |
| Surfboard-tg-mixed | 0.373 | 0.6 | 5 | 8770 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4998 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11515 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6332 | observe |
| barry-far-vless | 0.255 | None | 0 | 6555 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4618 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 23 |
| test_one_timeout | 15.0s | - | 15 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 14 | - |
| global | False | 295 | 229 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
