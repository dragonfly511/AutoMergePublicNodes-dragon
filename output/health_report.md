# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-09 22:36:56 |
| 运行耗时 | 276.8s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101701 |
| 去重后节点 | 34165 |
| TCP 可达 | 3000 |
| 真实可用 | 162 |
| Verified 输出 | 10 |
| Global 输出 | 163 |
| All 输出 | 34165 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.6 |
| tcp | 92.4 |
| probe | 91.6 |
| real_test | 40.8 |
| china_check | 23.1 |
| write_verified | 0.0 |
| generate | 18.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60379 |
| vmess | 17299 |
| trojan | 11611 |
| shadowsocks | 10252 |
| hysteria2 | 1805 |
| shadowsocksr | 149 |
| http | 91 |
| socks | 53 |
| tuic | 23 |
| hysteria | 23 |
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
| 95.67 | trojan | 245.2 | 3.0 | 22.1 | 14.89 | 10.0 | 13.18 | 20.0 | dragon | 66.163.122.46 |
| 91.85 | shadowsocks | 240.0 | 15.6 | 22.22 | 14.41 | 5.08 | 14.14 | 20.0 | dragon | 37.19.198.160 |
| 91.74 | trojan | 282.1 | 4.8 | 21.25 | 14.82 | 5.13 | 13.18 | 20.0 | dragon | 170.101.101.67 |
| 91.12 | trojan | 253.0 | 39.4 | 21.92 | 13.52 | 10.0 | 13.18 | 20.0 | dragon | 66.163.122.113 |
| 90.34 | shadowsocks | 261.3 | 8.8 | 21.73 | 14.67 | 4.97 | 14.14 | 20.0 | dragon | 198.98.53.130 |
| 89.99 | trojan | 339.3 | 1.9 | 19.92 | 14.93 | 9.35 | 13.18 | 20.0 | dragon | 66.163.112.242 |
| 89.33 | trojan | 309.3 | 1.6 | 20.62 | 14.94 | 4.93 | 13.18 | 20.0 | dragon | 169.197.140.214 |
| 88.59 | shadowsocks | 260.2 | 1.6 | 21.76 | 14.94 | 1.75 | 14.14 | 20.0 | dragon | 37.19.198.244 |
| 87.46 | shadowsocks | 304.3 | 4.1 | 20.73 | 14.84 | 1.75 | 14.14 | 20.0 | dragon | 37.19.198.243 |
| 87.21 | trojan | 273.5 | 0.4 | 21.45 | 14.98 | 5.1 | 13.18 | 20.0 | dragon | 170.101.101.131 |
| 87.17 | shadowsocks | 225.7 | 0.4 | 22.55 | 14.98 | 0.0 | 14.14 | 20.0 | dragon | 45.86.51.18 |
| 86.54 | shadowsocks | 250.1 | 2.5 | 21.99 | 14.91 | 0.0 | 14.14 | 20.0 | dragon | 185.230.230.18 |
| 85.95 | shadowsocks | 275.7 | 2.8 | 21.4 | 14.89 | 1.4 | 14.14 | 20.0 | dragon | 156.146.38.170 |
| 85.78 | shadowsocks | 281.4 | 3.1 | 21.26 | 14.88 | 0.0 | 14.14 | 20.0 | dragon | 172.111.38.72 |
| 85.57 | shadowsocks | 286.3 | 6.0 | 21.15 | 14.78 | 0.0 | 14.14 | 20.0 | dragon | 193.151.163.18 |
| 84.71 | shadowsocks | 329.8 | 1.3 | 20.14 | 14.95 | 0.0 | 14.14 | 20.0 | dragon | 193.151.160.18 |
| 84.57 | shadowsocks | 287.4 | 0.8 | 21.12 | 14.97 | 1.4 | 14.14 | 20.0 | dragon | 156.146.38.167 |
| 84.37 | shadowsocks | 326.8 | 1.7 | 20.21 | 14.94 | 0.0 | 14.14 | 20.0 | dragon | 193.151.160.9 |
| 84.34 | shadowsocks | 337.7 | 6.9 | 19.96 | 14.74 | 0.0 | 14.14 | 20.0 | dragon | 67.220.73.178 |
| 84.03 | shadowsocks | 354.8 | 4.8 | 19.57 | 14.82 | 0.0 | 14.14 | 20.0 | dragon | 158.51.121.221 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.993 | 0.919 | 136 | 10000 | prefer |
| dragon2 | 0.896 | 0.833 | 36 | 10000 | prefer |
| mheidari-all | 0.465 | 0.714 | 7 | 14061 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| dragon3 | 0.259 | 1.0 | 1 | 100 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2754 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11213 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6133 | observe |
| barry-far-vless | 0.255 | None | 0 | 6103 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4583 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| speed | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 10 | - |
| global | False | 170 | 163 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
