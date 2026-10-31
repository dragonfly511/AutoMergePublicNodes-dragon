# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 21:49:23 |
| 运行耗时 | 265.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 90795 |
| 去重后节点 | 33147 |
| TCP 可达 | 3000 |
| 真实可用 | 224 |
| Verified 输出 | 32 |
| Global 输出 | 228 |
| All 输出 | 33147 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.5 |
| tcp | 83.6 |
| probe | 90.7 |
| real_test | 45.1 |
| china_check | 18.6 |
| write_verified | 0.0 |
| generate | 17.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53374 |
| vmess | 13907 |
| trojan | 12520 |
| shadowsocks | 9128 |
| hysteria2 | 1456 |
| shadowsocksr | 163 |
| http | 162 |
| socks | 48 |
| anytls | 14 |
| tuic | 12 |
| hysteria | 11 |

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
| 89.88 | hysteria2 | 231.6 | 5.5 | 22.42 | 14.79 | 5.42 | 10.71 | 18.04 | dragon | 129.213.91.185 |
| 88.68 | trojan | 247.7 | 2.8 | 22.04 | 14.9 | 9.8 | 9.4 | 18.04 | dragon | 66.163.122.7 |
| 86.59 | trojan | 249.1 | 9.5 | 22.01 | 14.64 | 10.0 | 9.4 | 18.04 | dragon | 66.163.122.113 |
| 86.55 | trojan | 251.1 | 9.5 | 21.97 | 14.64 | 10.0 | 9.4 | 18.04 | dragon | 66.163.122.81 |
| 86.45 | shadowsocks | 325.5 | 3.8 | 20.24 | 14.86 | 4.99 | 12.82 | 18.04 | dragon | 15.204.246.132 |
| 86.4 | shadowsocks | 284.1 | 0.9 | 21.2 | 14.97 | 5.79 | 12.82 | 18.04 | dragon | 185.215.132.9 |
| 86.24 | trojan | 261.8 | 2.1 | 21.72 | 14.92 | 9.66 | 9.4 | 18.04 | dragon | 216.152.155.176 |
| 86.19 | trojan | 261.9 | 3.3 | 21.71 | 14.88 | 9.66 | 9.4 | 18.04 | dragon | 216.152.155.54 |
| 86.12 | trojan | 268.8 | 1.0 | 21.56 | 14.96 | 9.66 | 9.4 | 18.04 | dragon | 216.152.155.23 |
| 85.34 | shadowsocks | 297.1 | 1.6 | 20.9 | 14.94 | 5.79 | 12.82 | 18.04 | dragon | 185.215.132.18 |
| 85.28 | shadowsocks | 291.1 | 1.6 | 21.04 | 14.94 | 3.06 | 12.82 | 18.04 | dragon | 193.151.160.9 |
| 84.06 | trojan | 281.4 | 1.0 | 21.26 | 14.96 | 7.9 | 9.4 | 18.04 | dragon | 170.101.101.67 |
| 84.04 | shadowsocks | 239.4 | 1.5 | 22.24 | 14.94 | 0.0 | 12.82 | 18.04 | dragon | 37.19.198.244 |
| 83.64 | shadowsocks | 257.1 | 1.5 | 21.83 | 14.95 | 0.0 | 12.82 | 18.04 | dragon | 37.19.198.160 |
| 83.56 | shadowsocks | 237.9 | 1.8 | 22.27 | 14.93 | 0.0 | 12.82 | 18.04 | dragon | 185.230.230.18 |
| 83.5 | trojan | 306.3 | 3.7 | 20.69 | 14.86 | 9.65 | 9.4 | 18.04 | dragon | 169.197.140.214 |
| 83.31 | hysteria2 | 200.3 | 0.9 | 23.14 | 14.97 | 2.45 | 10.71 | 18.04 | dragon | 88.216.195.188 |
| 83.23 | shadowsocks | 238.5 | 10.3 | 22.26 | 14.61 | 0.0 | 12.82 | 18.04 | dragon | 45.86.51.18 |
| 83.22 | trojan | 356.9 | 1.1 | 19.52 | 14.96 | 9.66 | 9.4 | 18.04 | dragon | 216.152.156.65 |
| 83.05 | shadowsocks | 239.8 | 1.1 | 22.23 | 14.96 | 0.0 | 12.82 | 18.04 | dragon | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.936 | 202 | 10000 | prefer |
| Au1rxx-base64 | 0.864 | 0.812 | 32 | 1751 | prefer |
| mheidari-all | 0.446 | 0.8 | 5 | 14850 | observe |
| Surfboard-tg-mixed | 0.421 | 0.667 | 6 | 7936 | observe |
| peasoft-NoMoreWalls | 0.264 | 1.0 | 1 | 227 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10505 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5636 | observe |
| barry-far-vless | 0.255 | None | 0 | 5849 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 52 | 32 | - |
| global | False | 171 | 228 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
