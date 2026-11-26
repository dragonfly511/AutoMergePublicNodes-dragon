# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-26 21:49:12 |
| 运行耗时 | 262.7s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 98761 |
| 去重后节点 | 33324 |
| TCP 可达 | 3000 |
| 真实可用 | 254 |
| Verified 输出 | 17 |
| Global 输出 | 256 |
| All 输出 | 33324 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 84.1 |
| probe | 80.9 |
| real_test | 45.5 |
| china_check | 31.2 |
| write_verified | 0.0 |
| generate | 13.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56843 |
| vmess | 20129 |
| shadowsocks | 10980 |
| trojan | 8424 |
| hysteria2 | 1933 |
| shadowsocksr | 173 |
| http | 108 |
| socks | 100 |
| anytls | 33 |
| hysteria | 22 |
| tuic | 16 |

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
| 98.09 | hysteria2 | 248.8 | 12.5 | 22.02 | 14.53 | 10.0 | 13.12 | 19.42 | dragon | 66.94.121.46 |
| 97.28 | hysteria2 | 260.4 | 24.4 | 21.75 | 14.09 | 10.0 | 13.12 | 19.42 | dragon | 172.87.24.53 |
| 95.17 | shadowsocks | 198.0 | 0.6 | 23.19 | 14.98 | 8.69 | 13.39 | 19.42 | dragon | 95.215.201.18 |
| 94.95 | shadowsocks | 200.6 | 5.6 | 23.13 | 14.79 | 8.72 | 13.39 | 19.42 | dragon | 137.184.89.151 |
| 94.23 | shadowsocks | 253.9 | 0.5 | 21.9 | 14.98 | 8.54 | 13.39 | 19.42 | dragon | 156.146.38.168 |
| 93.99 | shadowsocks | 259.9 | 3.0 | 21.76 | 14.89 | 8.53 | 13.39 | 19.42 | dragon | 156.146.38.170 |
| 93.03 | shadowsocks | 258.7 | 0.6 | 21.79 | 14.98 | 8.72 | 13.39 | 19.42 | dragon | 156.146.38.169 |
| 92.78 | shadowsocks | 294.4 | 2.2 | 20.96 | 14.92 | 8.59 | 13.39 | 19.42 | dragon | 23.150.152.38 |
| 92.52 | shadowsocks | 210.9 | 0.1 | 22.89 | 15.0 | 8.59 | 13.39 | 19.42 | dragon | 173.244.56.6 |
| 91.91 | shadowsocks | 329.6 | 3.8 | 20.15 | 14.86 | 8.59 | 13.39 | 19.42 | dragon | 169.197.142.68 |
| 89.58 | vless | 283.5 | 1.7 | 21.22 | 14.94 | 10.0 | 9.0 | 19.42 | dragon | 172.235.40.143 |
| 89.55 | trojan | 217.2 | 6.1 | 22.75 | 14.77 | 5.4 | 9.71 | 19.42 | dragon | 167.88.61.175 |
| 89.35 | trojan | 218.3 | 10.5 | 22.72 | 14.61 | 5.39 | 9.71 | 19.42 | dragon | 167.88.61.198 |
| 88.78 | vless | 212.2 | 11.0 | 22.87 | 14.59 | 10.0 | 9.0 | 19.42 | dragon | 166.0.25.92 |
| 88.44 | trojan | 266.9 | 5.0 | 21.6 | 14.81 | 5.4 | 9.71 | 19.42 | dragon | 167.88.61.52 |
| 87.04 | shadowsocks | 345.4 | 6.9 | 19.78 | 14.74 | 8.5 | 13.39 | 19.42 | dragon | 172.111.38.72 |
| 86.9 | shadowsocks | 351.7 | 14.9 | 19.64 | 14.44 | 8.67 | 13.39 | 19.42 | dragon | 185.230.230.18 |
| 86.61 | shadowsocks | 351.2 | 21.0 | 19.65 | 14.21 | 8.67 | 13.39 | 19.42 | dragon | 37.19.198.243 |
| 86.17 | shadowsocks | 389.0 | 1.9 | 18.77 | 14.93 | 8.44 | 13.39 | 19.42 | dragon | 149.40.57.134 |
| 86.06 | shadowsocks | 354.2 | 8.0 | 19.58 | 14.7 | 8.67 | 13.39 | 19.42 | dragon | 193.151.163.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | 0.9 | 251 | 10000 | prefer |
| dragon2 | 0.873 | 0.815 | 27 | 9840 | prefer |
| Surfboard-tg-mixed | 0.519 | 1.0 | 5 | 8568 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14669 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 168 | observe |
| ermaozi-get_subscribe | 0.281 | 0.667 | 3 | 314 | observe |
| peasoft-NoMoreWalls | 0.26 | 1.0 | 1 | 133 | observe |
| dragon3 | 0.259 | 1.0 | 1 | 100 | observe |
| tg-proxy_mtm | 0.258 | 1.0 | 1 | 67 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11794 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5607 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4485 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 15 | 17 | - |
| global | False | 223 | 256 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
