# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-28 08:10:09 |
| 运行耗时 | 207.5s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 97827 |
| 去重后节点 | 32967 |
| TCP 可达 | 3000 |
| 真实可用 | 124 |
| Verified 输出 | 24 |
| Global 输出 | 254 |
| All 输出 | 32967 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.0 |
| tcp | 74.0 |
| probe | 65.6 |
| real_test | 29.3 |
| china_check | 21.5 |
| generate | 10.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56353 |
| vmess | 20166 |
| shadowsocks | 11057 |
| trojan | 7874 |
| hysteria2 | 1884 |
| shadowsocksr | 155 |
| http | 148 |
| socks | 103 |
| anytls | 40 |
| hysteria | 32 |
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
| 93.99 | hysteria2 | 324.1 | 5.0 | 20.28 | 14.81 | 10.0 | 12.86 | 17.98 | dragon | 172.87.24.53 |
| 92.61 | hysteria2 | 270.5 | 21.4 | 21.52 | 14.2 | 10.0 | 12.86 | 17.98 | dragon | 66.94.121.46 |
| 92.02 | shadowsocks | 206.6 | 5.5 | 23.0 | 14.8 | 8.05 | 12.19 | 17.98 | dragon | 149.22.95.183 |
| 90.59 | shadowsocks | 314.2 | 2.1 | 20.5 | 14.92 | 9.5 | 12.19 | 17.98 | dragon | 23.150.152.38 |
| 90.05 | hysteria2 | 350.0 | 5.2 | 19.68 | 14.8 | 10.0 | 12.86 | 17.98 | dragon | 206.189.229.48 |
| 88.28 | shadowsocks | 275.2 | 1.5 | 21.41 | 14.95 | 9.32 | 12.19 | 17.98 | dragon | 173.244.56.9 |
| 87.07 | shadowsocks | 225.5 | 0.4 | 22.56 | 14.98 | 9.43 | 12.19 | 17.98 | dragon | 216.105.168.18 |
| 86.64 | shadowsocks | 275.0 | 0.5 | 21.41 | 14.98 | 7.75 | 12.19 | 17.98 | dragon | 173.244.56.6 |
| 86.24 | shadowsocks | 262.8 | 0.1 | 21.69 | 14.99 | 9.36 | 12.19 | 17.98 | dragon | 95.215.201.18 |
| 86.04 | shadowsocks | 323.7 | 0.6 | 20.29 | 14.98 | 9.14 | 12.19 | 17.98 | dragon | 156.146.38.169 |
| 85.55 | shadowsocks | 317.5 | 1.5 | 20.43 | 14.94 | 9.14 | 12.19 | 17.98 | dragon | 156.146.38.168 |
| 85.39 | shadowsocks | 314.0 | 0.2 | 20.51 | 14.99 | 9.35 | 12.19 | 17.98 | dragon | 216.106.178.169 |
| 85.31 | shadowsocks | 327.3 | 1.7 | 20.2 | 14.94 | 9.33 | 12.19 | 17.98 | dragon | 67.220.73.178 |
| 84.64 | shadowsocks | 384.2 | 0.1 | 18.88 | 15.0 | 9.12 | 12.19 | 17.98 | dragon | 156.146.38.170 |
| 83.65 | shadowsocks | 375.4 | 0.3 | 19.09 | 14.99 | 9.48 | 12.19 | 17.98 | dragon | 38.91.100.39 |
| 83.63 | shadowsocks | 396.7 | 0.8 | 18.6 | 14.97 | 9.33 | 12.19 | 17.98 | dragon | 38.128.66.32 |
| 83.58 | shadowsocks | 403.9 | 0.7 | 18.43 | 14.97 | 9.36 | 12.19 | 17.98 | dragon | 38.64.138.135 |
| 83.43 | shadowsocks | 378.8 | 0.6 | 19.01 | 14.98 | 9.35 | 12.19 | 17.98 | dragon | 37.19.198.243 |
| 83.21 | shadowsocks | 390.5 | 0.7 | 18.74 | 14.97 | 9.36 | 12.19 | 17.98 | dragon | 37.19.198.236 |
| 82.86 | shadowsocks | 373.2 | 0.4 | 19.14 | 14.99 | 9.51 | 12.19 | 17.98 | dragon | 172.111.38.72 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.962 | 106 | 10000 | prefer |
| Surfboard-tg-mixed | 0.629 | 1.0 | 8 | 8437 | observe |
| tg-LonUp_M | 0.625 | 1.0 | 10 | 157 | observe |
| dragon2 | 0.606 | 0.889 | 9 | 9895 | observe |
| dragon3 | 0.324 | 0.75 | 4 | 100 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 357 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11621 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5299 | observe |
| barry-far-vless | 0.255 | None | 0 | 5482 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4526 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 5 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 24 | 10 | 0.5 |
| global | True | 254 | 126 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
