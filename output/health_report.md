# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 18:35:12 |
| 运行耗时 | 262.7s |
| 订阅源总数 | 109 |
| 健康订阅源 | 89 |
| 原始节点 | 102557 |
| 去重后节点 | 34617 |
| TCP 可达 | 3000 |
| 真实可用 | 79 |
| Verified 输出 | 4 |
| Global 输出 | 82 |
| All 输出 | 34617 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.5 |
| tcp | 89.3 |
| probe | 91.3 |
| real_test | 34.9 |
| china_check | 18.4 |
| write_verified | 0.0 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60416 |
| vmess | 17701 |
| trojan | 12103 |
| shadowsocks | 10006 |
| hysteria2 | 1820 |
| http | 202 |
| shadowsocksr | 156 |
| socks | 84 |
| hysteria | 34 |
| anytls | 20 |
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
| 85.52 | trojan | 290.7 | 8.0 | 21.05 | 14.7 | 10.0 | 10.43 | 16.36 | dragon | 66.163.112.121 |
| 85.48 | trojan | 333.5 | 1.2 | 20.06 | 14.95 | 10.0 | 10.43 | 16.36 | dragon | 66.163.112.242 |
| 85.46 | trojan | 342.6 | 0.8 | 19.85 | 14.97 | 10.0 | 10.43 | 16.36 | dragon | 66.163.112.31 |
| 85.25 | trojan | 298.1 | 0.6 | 20.88 | 14.98 | 10.0 | 10.43 | 16.36 | dragon | 66.163.112.142 |
| 83.02 | shadowsocks | 238.3 | 2.3 | 22.26 | 14.91 | 0.0 | 14.68 | 16.36 | dragon | 38.145.220.193 |
| 81.98 | shadowsocks | 359.5 | 4.0 | 19.46 | 14.85 | 8.43 | 14.68 | 16.36 | dragon | 156.146.38.167 |
| 80.99 | trojan | 416.0 | 0.2 | 18.15 | 14.99 | 9.87 | 10.43 | 16.36 | dragon | 216.238.80.100 |
| 80.86 | trojan | 419.9 | 11.7 | 18.06 | 14.56 | 9.8 | 10.43 | 16.36 | dragon | 66.23.203.21 |
| 80.56 | hysteria2 | 319.6 | 1.4 | 20.38 | 14.95 | 0.0 | 12.19 | 16.1 | mheidari-all | 88.216.195.188 |
| 80.41 | trojan | 430.5 | 6.4 | 17.81 | 14.76 | 9.87 | 10.43 | 16.36 | dragon | 169.197.140.224 |
| 80.23 | trojan | 447.6 | 6.7 | 17.42 | 14.75 | 10.0 | 10.43 | 16.36 | dragon | 169.197.140.171 |
| 79.99 | trojan | 441.8 | 16.6 | 17.55 | 14.38 | 10.0 | 10.43 | 16.36 | dragon | 169.197.140.169 |
| 79.72 | shadowsocks | 283.0 | 2.3 | 21.23 | 14.91 | 0.0 | 14.68 | 16.36 | dragon | 103.11.76.248 |
| 79.72 | trojan | 438.2 | 6.6 | 17.63 | 14.75 | 10.0 | 10.43 | 16.36 | dragon | 169.197.140.214 |
| 78.91 | trojan | 429.5 | 24.1 | 17.84 | 14.1 | 10.0 | 10.43 | 16.36 | dragon | 169.197.140.218 |
| 78.58 | hysteria2 | 211.7 | 0.7 | 22.88 | 14.98 | 0.0 | 12.19 | 16.36 | dragon | 8.209.247.109 |
| 78.15 | trojan | 531.1 | 2.1 | 15.48 | 14.92 | 9.87 | 10.43 | 16.36 | dragon | 169.197.140.245 |
| 78.13 | shadowsocks | 212.5 | 10.8 | 22.86 | 14.59 | 0.0 | 14.68 | 10.0 | dragon2 | 149.22.95.183 |
| 77.86 | trojan | 260.7 | 6.2 | 21.74 | 14.77 | 10.0 | 10.43 | 16.36 | dragon | 23.106.44.14 |
| 74.58 | trojan | 572.7 | 0.3 | 14.52 | 14.99 | 9.05 | 10.43 | 16.36 | dragon | 45.63.30.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.905 | 0.842 | 38 | 10000 | prefer |
| dragon | 0.697 | 0.621 | 58 | 10000 | observe |
| mheidari-all | 0.507 | 0.75 | 8 | 14184 | observe |
| Surfboard-tg-mixed | 0.352 | 0.5 | 6 | 8758 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2768 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10962 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6135 | observe |
| barry-far-vless | 0.255 | None | 0 | 6479 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 9 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 6 | 4 | - |
| global | False | 108 | 82 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
