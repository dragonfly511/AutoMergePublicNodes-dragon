# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-19 07:44:51 |
| 运行耗时 | 266.0s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 102303 |
| 去重后节点 | 35242 |
| TCP 可达 | 3000 |
| 真实可用 | 189 |
| Verified 输出 | 11 |
| Global 输出 | 190 |
| All 输出 | 35242 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 96.0 |
| probe | 86.8 |
| real_test | 33.6 |
| china_check | 21.1 |
| write_verified | 0.0 |
| generate | 17.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59164 |
| vmess | 17951 |
| trojan | 11599 |
| shadowsocks | 11376 |
| hysteria2 | 1739 |
| shadowsocksr | 182 |
| http | 136 |
| socks | 109 |
| hysteria | 19 |
| tuic | 16 |
| anytls | 12 |

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
| 88.68 | hysteria2 | 218.5 | 3.0 | 22.72 | 14.89 | 0.0 | 12.27 | 19.8 | dragon | 66.94.121.46 |
| 87.79 | trojan | 243.2 | 1.2 | 22.15 | 14.95 | 4.53 | 10.0 | 19.8 | dragon | 167.88.61.20 |
| 87.43 | shadowsocks | 259.5 | 10.8 | 21.77 | 14.6 | 2.13 | 13.63 | 19.8 | dragon | 137.184.89.151 |
| 87.29 | trojan | 242.0 | 8.2 | 22.18 | 14.69 | 3.59 | 10.0 | 19.8 | dragon | 167.88.61.193 |
| 87.26 | shadowsocks | 217.3 | 2.5 | 22.75 | 14.91 | 2.11 | 13.63 | 19.8 | dragon | 169.197.142.68 |
| 85.98 | shadowsocks | 355.7 | 3.0 | 19.54 | 14.89 | 4.2 | 13.63 | 19.8 | dragon | 23.150.152.38 |
| 85.18 | shadowsocks | 217.3 | 12.4 | 22.75 | 14.54 | 3.46 | 13.63 | 19.8 | dragon | 149.22.95.183 |
| 84.54 | trojan | 295.6 | 0.1 | 20.94 | 14.99 | 4.56 | 10.0 | 19.8 | dragon | 66.163.112.242 |
| 84.22 | trojan | 299.8 | 0.6 | 20.84 | 14.98 | 8.67 | 10.0 | 19.8 | dragon | 66.163.112.171 |
| 82.55 | trojan | 416.0 | 8.2 | 18.15 | 14.69 | 9.26 | 10.0 | 19.8 | dragon | 66.163.122.26 |
| 81.71 | hysteria2 | 231.2 | 2.4 | 22.43 | 14.91 | 0.0 | 12.27 | 19.8 | dragon | 8.209.247.109 |
| 81.32 | shadowsocks | 284.8 | 20.8 | 21.18 | 14.22 | 0.74 | 13.63 | 19.8 | dragon | 173.244.56.6 |
| 81.26 | shadowsocks | 344.2 | 9.6 | 19.81 | 14.64 | 1.84 | 13.63 | 19.8 | dragon | 216.106.178.169 |
| 80.88 | hysteria2 | 376.2 | 0.1 | 19.07 | 15.0 | 0.0 | 12.27 | 19.8 | dragon | 206.189.229.48 |
| 80.81 | trojan | 376.1 | 0.7 | 19.07 | 14.97 | 9.88 | 10.0 | 19.8 | dragon | 170.101.101.53 |
| 80.64 | shadowsocks | 355.1 | 8.3 | 19.56 | 14.69 | 1.75 | 13.63 | 19.8 | dragon | 156.146.38.167 |
| 80.46 | shadowsocks | 356.7 | 0.1 | 19.52 | 14.99 | 1.74 | 13.63 | 19.8 | dragon | 156.146.38.168 |
| 80.12 | trojan | 582.5 | 0.5 | 14.29 | 14.98 | 10.0 | 10.0 | 19.8 | dragon | 69.164.240.85 |
| 79.79 | shadowsocks | 427.2 | 10.1 | 17.89 | 14.62 | 1.87 | 13.63 | 19.8 | dragon | 167.88.62.203 |
| 79.6 | trojan | 270.2 | 206.2 | 21.52 | 7.27 | 4.66 | 10.0 | 19.8 | dragon | 167.88.61.175 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.995 | 0.919 | 186 | 10000 | prefer |
| mheidari-all | 0.519 | 1.0 | 5 | 14200 | observe |
| dragon3 | 0.511 | 0.526 | 19 | 100 | observe |
| dragon2 | 0.335 | 1.0 | 1 | 10000 | observe |
| ermaozi | 0.331 | 1.0 | 2 | 494 | observe |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 8472 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 168 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11797 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5689 | observe |
| barry-far-vless | 0.255 | None | 0 | 5975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4507 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| 204 | ProxyError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 11 | - |
| global | False | 154 | 190 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
