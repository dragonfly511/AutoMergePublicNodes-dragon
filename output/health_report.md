# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 22:06:38 |
| 运行耗时 | 243.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101697 |
| 去重后节点 | 34659 |
| TCP 可达 | 3000 |
| 真实可用 | 44 |
| Verified 输出 | 12 |
| Global 输出 | 174 |
| All 输出 | 34659 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.6 |
| tcp | 84.0 |
| probe | 94.6 |
| real_test | 18.1 |
| china_check | 18.1 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59287 |
| vmess | 17415 |
| trojan | 12432 |
| shadowsocks | 10397 |
| hysteria2 | 1775 |
| shadowsocksr | 151 |
| http | 94 |
| socks | 82 |
| hysteria | 25 |
| anytls | 22 |
| tuic | 17 |

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
| 88.54 | shadowsocks | 352.2 | 28.0 | 19.62 | 13.95 | 6.09 | 14.1 | 19.28 | dragon | 15.204.233.41 |
| 83.39 | shadowsocks | 336.4 | 1.3 | 19.99 | 14.95 | 9.49 | 14.1 | 10.96 | dragon3 | 167.17.67.171 |
| 83.25 | shadowsocks | 300.7 | 0.9 | 20.82 | 14.96 | 5.76 | 14.1 | 19.28 | dragon | 95.215.201.18 |
| 82.53 | hysteria2 | 304.9 | 0.6 | 20.72 | 14.98 | 0.0 | 12.19 | 19.28 | dragon | 66.94.121.46 |
| 81.95 | trojan | 259.4 | 29.4 | 21.77 | 13.9 | 10.0 | 5.0 | 19.28 | dragon | 38.60.157.143 |
| 81.72 | shadowsocks | 482.0 | 1.3 | 16.62 | 14.95 | 8.14 | 14.1 | 19.28 | dragon | 23.166.88.127 |
| 80.63 | shadowsocks | 441.0 | 0.5 | 17.57 | 14.98 | 5.78 | 14.1 | 19.28 | dragon | 185.176.204.18 |
| 80.3 | shadowsocks | 304.7 | 4.2 | 20.72 | 14.84 | 9.2 | 14.1 | 10.96 | dragon3 | 23.150.152.38 |
| 80.06 | shadowsocks | 523.6 | 0.2 | 15.66 | 14.99 | 7.82 | 14.1 | 19.28 | dragon | 185.226.172.8 |
| 79.99 | shadowsocks | 320.2 | 1.5 | 20.36 | 14.94 | 9.12 | 14.1 | 10.96 | dragon3 | 149.22.95.183 |
| 79.89 | trojan | 390.4 | 3.3 | 18.74 | 14.87 | 10.0 | 5.0 | 19.28 | dragon | 149.248.50.252 |
| 79.89 | shadowsocks | 546.9 | 0.6 | 15.12 | 14.98 | 8.01 | 14.1 | 19.28 | dragon | 62.93.179.97 |
| 78.93 | shadowsocks | 348.8 | 3.2 | 19.7 | 14.88 | 9.14 | 14.1 | 10.96 | dragon3 | 137.184.89.151 |
| 78.76 | vless | 507.0 | 2.0 | 16.04 | 14.93 | 8.28 | 11.16 | 19.28 | dragon | 15.204.97.195 |
| 78.63 | shadowsocks | 485.5 | 2.1 | 16.54 | 14.92 | 5.66 | 14.1 | 19.28 | dragon | 82.38.31.212 |
| 78.61 | shadowsocks | 596.9 | 7.3 | 13.96 | 14.73 | 8.12 | 14.1 | 19.28 | dragon | 82.38.31.35 |
| 78.41 | hysteria2 | 231.8 | 8.8 | 22.41 | 14.67 | 0.0 | 12.19 | 10.14 | mheidari-all | 88.216.195.188 |
| 78.11 | shadowsocks | 396.6 | 10.9 | 18.6 | 14.59 | 9.49 | 14.1 | 10.96 | dragon3 | 167.88.62.203 |
| 78.03 | shadowsocks | 314.5 | 3.3 | 20.5 | 14.88 | 9.14 | 14.1 | 10.96 | dragon3 | 169.197.142.68 |
| 77.75 | hysteria2 | 362.8 | 40.1 | 19.38 | 13.5 | 6.5 | 12.19 | 12.58 | dragon2 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.83 | 0.773 | 22 | 10000 | prefer |
| dragon3 | 0.731 | 0.75 | 20 | 100 | prefer |
| mheidari-all | 0.606 | 0.889 | 9 | 14235 | observe |
| dragon2 | 0.4 | 0.75 | 4 | 10000 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4866 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11058 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5923 | observe |
| barry-far-vless | 0.255 | None | 0 | 6134 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4529 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 12 | 4 | 0.5 |
| global | True | 174 | 44 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
