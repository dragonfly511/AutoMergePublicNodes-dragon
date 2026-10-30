# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 01:58:27 |
| 运行耗时 | 311.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 109307 |
| 去重后节点 | 35026 |
| TCP 可达 | 3000 |
| 真实可用 | 287 |
| Verified 输出 | 131 |
| Global 输出 | 291 |
| All 输出 | 35026 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.6 |
| tcp | 99.6 |
| probe | 78.3 |
| real_test | 76.2 |
| china_check | 35.6 |
| generate | 13.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 67812 |
| vmess | 15110 |
| trojan | 12436 |
| shadowsocks | 11299 |
| hysteria2 | 2251 |
| shadowsocksr | 165 |
| http | 143 |
| socks | 49 |
| tuic | 16 |
| anytls | 15 |
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
| 83.53 | shadowsocks | 210.3 | 0.8 | 22.91 | 14.97 | 9.33 | 12.3 | 8.02 | dragon | 173.244.56.6 |
| 83.36 | shadowsocks | 218.1 | 1.2 | 22.73 | 14.95 | 9.36 | 12.3 | 8.02 | dragon | 173.244.56.9 |
| 83.33 | http | 378.7 | 1.0 | 19.01 | 14.96 | 0.0 | 14.44 | 19.72 | ermaozi | 38.247.141.135 |
| 83.25 | http | 295.0 | 15.2 | 20.95 | 14.43 | 0.0 | 14.44 | 19.72 | ermaozi | 44.248.167.117 |
| 82.24 | shadowsocks | 261.6 | 0.9 | 21.72 | 14.97 | 9.23 | 12.3 | 8.02 | dragon | 156.146.38.167 |
| 82.12 | shadowsocks | 266.2 | 0.1 | 21.62 | 15.0 | 9.22 | 12.3 | 8.02 | dragon | 156.146.38.168 |
| 81.96 | shadowsocks | 261.7 | 0.2 | 21.72 | 14.99 | 9.24 | 12.3 | 8.02 | dragon | 156.146.38.170 |
| 81.82 | shadowsocks | 259.7 | 2.4 | 21.77 | 14.91 | 9.32 | 12.3 | 8.02 | dragon | 95.215.201.18 |
| 80.02 | trojan | 274.5 | 1.3 | 21.42 | 14.95 | 10.0 | 10.31 | 8.02 | dragon | 216.106.186.32 |
| 76.26 | vless | 353.7 | 6.2 | 19.59 | 14.77 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 195.211.98.43 |
| 76.16 | hysteria2 | 262.2 | 11.2 | 21.71 | 14.58 | 0.0 | 12.86 | 8.02 | dragon | 66.94.121.46 |
| 75.9 | trojan | 405.5 | 3.6 | 18.39 | 14.86 | 10.0 | 10.31 | 8.02 | dragon | 66.23.203.21 |
| 74.76 | vless | 298.8 | 1.1 | 20.86 | 14.96 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 185.168.208.190 |
| 73.12 | vless | 384.2 | 7.1 | 18.88 | 14.73 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 46.250.250.149 |
| 72.81 | vless | 505.0 | 4.8 | 16.09 | 14.82 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 159.89.87.21 |
| 72.78 | vless | 220.8 | 1.0 | 22.67 | 14.96 | 0.0 | 9.97 | 14.68 | mheidari-all | 169.128.83.4 |
| 72.72 | vless | 462.5 | 3.8 | 17.07 | 14.86 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 169.40.42.163 |
| 72.65 | vless | 408.0 | 2.9 | 18.33 | 14.89 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 45.76.98.127 |
| 72.34 | vless | 482.6 | 1.2 | 16.61 | 14.96 | 0.0 | 9.97 | 17.26 | Au1rxx-base64 | 31.172.69.31 |
| 72.26 | shadowsocks | 345.0 | 1.1 | 19.79 | 14.96 | 9.42 | 12.3 | 8.02 | dragon | 45.207.207.25 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 1.0 | 53 | 10000 | prefer |
| ermaozi | 0.975 | 1.0 | 20 | 515 | prefer |
| Au1rxx-base64 | 0.921 | 0.86 | 93 | 1706 | prefer |
| Surfboard-tg-mixed | 0.718 | 0.644 | 45 | 7758 | prefer |
| mheidari-all | 0.525 | 0.444 | 234 | 33573 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10429 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5789 | observe |
| barry-far-vless | 0.255 | None | 0 | 6001 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1706 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 99 |
| geo | ClientOSError | - | 30 |
| speed | ClientOSError | - | 18 |
| 204 | ProxyError | - | 4 |
| 204 | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 131 | 56 | 0.5 |
| global | False | 274 | 291 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
