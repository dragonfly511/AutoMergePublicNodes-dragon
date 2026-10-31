# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 10:14:43 |
| 运行耗时 | 258.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 91128 |
| 去重后节点 | 33558 |
| TCP 可达 | 3000 |
| 真实可用 | 185 |
| Verified 输出 | 55 |
| Global 输出 | 187 |
| All 输出 | 33558 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 92.4 |
| probe | 75.9 |
| real_test | 49.3 |
| china_check | 23.4 |
| write_verified | 0.0 |
| generate | 11.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54412 |
| vmess | 13778 |
| trojan | 11805 |
| shadowsocks | 9032 |
| hysteria2 | 1508 |
| http | 338 |
| shadowsocksr | 165 |
| socks | 51 |
| tuic | 14 |
| anytls | 13 |
| hysteria | 12 |

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
| 83.8 | trojan | 262.9 | 0.7 | 21.69 | 14.97 | 5.56 | 11.67 | 13.42 | dragon | 66.23.203.21 |
| 80.56 | trojan | 303.7 | 0.3 | 20.75 | 14.99 | 10.0 | 11.67 | 13.42 | dragon | 167.88.61.20 |
| 79.62 | shadowsocks | 281.8 | 0.7 | 21.25 | 14.97 | 2.34 | 13.27 | 13.42 | dragon | 185.215.132.9 |
| 79.52 | shadowsocks | 256.9 | 0.1 | 21.83 | 15.0 | 0.0 | 13.27 | 13.42 | dragon | 156.146.38.169 |
| 79.23 | hysteria2 | 260.9 | 0.5 | 21.74 | 14.98 | 0.0 | 10.59 | 13.42 | dragon | 129.213.91.185 |
| 78.9 | trojan | 315.0 | 0.4 | 20.49 | 14.98 | 5.93 | 11.67 | 13.42 | dragon | 216.106.186.33 |
| 78.88 | shadowsocks | 283.4 | 0.8 | 21.22 | 14.97 | 0.0 | 13.27 | 13.42 | dragon | 156.146.38.168 |
| 78.54 | shadowsocks | 299.1 | 0.2 | 20.85 | 14.99 | 1.01 | 13.27 | 13.42 | dragon | 37.19.198.244 |
| 78.54 | hysteria2 | 333.8 | 3.0 | 20.05 | 14.89 | 1.71 | 10.59 | 13.42 | dragon | 66.94.121.46 |
| 78.42 | shadowsocks | 303.7 | 0.5 | 20.75 | 14.98 | 0.0 | 13.27 | 13.42 | dragon | 156.146.38.170 |
| 77.87 | shadowsocks | 294.0 | 0.6 | 20.97 | 14.98 | 0.0 | 13.27 | 16.4 | Au1rxx-base64 | 198.98.53.130 |
| 77.86 | shadowsocks | 328.1 | 0.3 | 20.18 | 14.99 | 0.0 | 13.27 | 13.42 | dragon | 156.146.38.167 |
| 77.76 | shadowsocks | 309.4 | 1.5 | 20.62 | 14.95 | 0.0 | 13.27 | 13.42 | dragon | 45.86.51.18 |
| 76.89 | hysteria2 | 243.1 | 3.8 | 22.15 | 14.86 | 3.22 | 10.59 | 13.42 | dragon | 179.255.103.55 |
| 76.49 | shadowsocks | 290.5 | 1.0 | 21.05 | 14.96 | 1.51 | 13.27 | 13.42 | dragon | 173.244.56.9 |
| 76.32 | shadowsocks | 291.4 | 0.6 | 21.03 | 14.98 | 1.11 | 13.27 | 13.42 | dragon | 37.19.198.243 |
| 76.0 | shadowsocks | 341.1 | 0.4 | 19.88 | 14.99 | 0.0 | 13.27 | 13.42 | dragon | 185.230.230.18 |
| 75.54 | shadowsocks | 435.5 | 0.7 | 17.7 | 14.97 | 1.08 | 13.27 | 13.42 | dragon | 37.19.198.160 |
| 74.99 | shadowsocks | 329.0 | 0.9 | 20.16 | 14.97 | 0.84 | 13.27 | 13.42 | dragon | 193.151.160.18 |
| 74.63 | trojan | 311.2 | 0.9 | 20.57 | 14.97 | 6.35 | 11.67 | 13.42 | dragon | 66.163.112.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.911 | 0.836 | 146 | 10000 | prefer |
| mheidari-all | 0.843 | 0.778 | 36 | 14723 | prefer |
| Au1rxx-base64 | 0.729 | 0.667 | 42 | 1751 | prefer |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 2848 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi | 0.28 | 1.0 | 1 | 622 | observe |
| Surfboard-tg-mixed | 0.262 | 0.15 | 20 | 7861 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10586 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5698 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 34 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| speed | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 96 | 55 | - |
| global | False | 260 | 187 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
