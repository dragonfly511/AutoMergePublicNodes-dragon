# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 09:46:09 |
| 运行耗时 | 321.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 91126 |
| 去重后节点 | 33552 |
| TCP 可达 | 3000 |
| 真实可用 | 258 |
| Verified 输出 | 96 |
| Global 输出 | 260 |
| All 输出 | 33552 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.6 |
| tcp | 92.2 |
| probe | 101.2 |
| real_test | 69.8 |
| china_check | 30.6 |
| write_verified | 0.0 |
| generate | 17.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54418 |
| vmess | 13764 |
| trojan | 11810 |
| shadowsocks | 9038 |
| hysteria2 | 1503 |
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
| 86.61 | http | 314.9 | 14.5 | 20.49 | 14.46 | 0.0 | 14.44 | 19.72 | ermaozi | 23.133.176.14 |
| 86.54 | http | 313.6 | 3.3 | 20.52 | 14.88 | 0.0 | 14.44 | 19.72 | ermaozi | 172.64.68.89 |
| 85.35 | http | 305.8 | 1.3 | 20.7 | 14.95 | 0.0 | 14.44 | 19.72 | ermaozi | 38.95.111.226 |
| 84.53 | http | 362.7 | 11.3 | 19.38 | 14.58 | 0.0 | 14.44 | 19.72 | ermaozi | 38.247.141.135 |
| 83.51 | http | 301.0 | 2.9 | 20.81 | 14.89 | 0.0 | 14.44 | 19.72 | ermaozi | 44.248.167.117 |
| 80.68 | http | 413.9 | 1.2 | 18.2 | 14.96 | 0.0 | 14.44 | 19.72 | ermaozi | 12.202.180.10 |
| 79.17 | http | 430.9 | 2.9 | 17.8 | 14.89 | 0.0 | 14.44 | 19.72 | ermaozi | 167.88.60.242 |
| 78.76 | http | 568.0 | 7.1 | 14.63 | 14.74 | 0.0 | 14.44 | 19.72 | ermaozi | 121.127.34.82 |
| 76.88 | vless | 233.8 | 0.5 | 22.37 | 14.98 | 0.0 | 9.97 | 14.68 | mheidari-all | 43.173.78.139 |
| 76.77 | vless | 274.9 | 1.0 | 21.42 | 14.96 | 0.0 | 9.97 | 14.68 | mheidari-all | 67.220.73.204 |
| 76.08 | http | 632.7 | 1.8 | 13.13 | 14.93 | 0.0 | 14.44 | 19.72 | ermaozi | 12.202.180.118 |
| 75.86 | http | 509.1 | 2.3 | 15.99 | 14.91 | 0.0 | 14.44 | 19.72 | ermaozi | 206.223.161.47 |
| 75.49 | hysteria2 | 223.8 | 1.3 | 22.6 | 14.95 | 3.06 | 12.86 | 8.02 | dragon | 179.255.103.55 |
| 74.87 | vless | 317.9 | 7.6 | 20.42 | 14.71 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 69.48.201.136 |
| 74.75 | http | 391.2 | 2.6 | 18.72 | 14.9 | 0.0 | 14.44 | 19.72 | ermaozi | 162.244.227.36 |
| 74.71 | http | 641.8 | 0.9 | 12.92 | 14.97 | 0.0 | 14.44 | 19.72 | ermaozi | 68.235.56.59 |
| 74.31 | http | 495.3 | 2.3 | 16.31 | 14.91 | 0.0 | 14.44 | 19.72 | ermaozi | 206.223.183.21 |
| 73.84 | vless | 473.0 | 1.7 | 16.83 | 14.94 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 169.40.42.90 |
| 73.78 | vless | 291.8 | 1.1 | 21.02 | 14.96 | 0.0 | 9.97 | 14.68 | mheidari-all | 141.193.154.234 |
| 73.78 | hysteria2 | 323.0 | 8.5 | 20.3 | 14.68 | 0.0 | 12.86 | 8.02 | dragon | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 0.989 | 94 | 622 | prefer |
| Au1rxx-base64 | 0.82 | 0.761 | 46 | 1751 | prefer |
| mheidari-all | 0.707 | 0.63 | 108 | 14723 | prefer |
| dragon | 0.671 | 0.733 | 15 | 10000 | observe |
| DeltaKronecker-all | 0.612 | 0.625 | 16 | 2848 | observe |
| Surfboard-tg-mixed | 0.547 | 0.466 | 88 | 7861 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10575 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5698 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 46 |
| geo | ClientOSError | - | 45 |
| 204 | TimeoutError | - | 7 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 131 | 96 | - |
| global | False | 274 | 260 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
