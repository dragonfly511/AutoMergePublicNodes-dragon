# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-02 21:54:19 |
| 运行耗时 | 277.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 91771 |
| 去重后节点 | 34032 |
| TCP 可达 | 3000 |
| 真实可用 | 111 |
| Verified 输出 | 7 |
| Global 输出 | 112 |
| All 输出 | 34032 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.5 |
| tcp | 90.9 |
| probe | 96.7 |
| real_test | 45.2 |
| china_check | 17.7 |
| write_verified | 0.0 |
| generate | 17.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54660 |
| vmess | 14078 |
| trojan | 11874 |
| shadowsocks | 9133 |
| hysteria2 | 1558 |
| http | 165 |
| shadowsocksr | 154 |
| socks | 72 |
| anytls | 37 |
| hysteria | 26 |
| tuic | 14 |

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
| 95.53 | trojan | 310.0 | 0.3 | 20.6 | 14.99 | 9.95 | 13.62 | 19.54 | dragon | 66.163.114.114 |
| 94.27 | trojan | 255.0 | 3.6 | 21.87 | 14.87 | 7.87 | 13.62 | 19.54 | dragon | 216.152.155.54 |
| 93.86 | trojan | 295.6 | 19.0 | 20.93 | 14.29 | 9.98 | 13.62 | 19.54 | dragon | 170.101.101.53 |
| 93.65 | trojan | 363.2 | 0.8 | 19.37 | 14.97 | 9.91 | 13.62 | 19.54 | dragon | 170.101.101.211 |
| 93.61 | trojan | 259.7 | 1.3 | 21.77 | 14.95 | 7.23 | 13.62 | 19.54 | dragon | 66.163.114.132 |
| 93.48 | trojan | 267.5 | 1.9 | 21.58 | 14.93 | 9.31 | 13.62 | 19.54 | dragon | 216.152.155.131 |
| 92.85 | trojan | 279.8 | 0.3 | 21.3 | 14.99 | 9.89 | 13.62 | 19.54 | dragon | 38.102.234.153 |
| 92.66 | trojan | 257.4 | 0.9 | 21.82 | 14.96 | 7.22 | 13.62 | 19.54 | dragon | 66.163.114.166 |
| 92.49 | trojan | 304.9 | 2.0 | 20.72 | 14.93 | 9.91 | 13.62 | 19.54 | dragon | 216.152.156.42 |
| 92.28 | trojan | 301.7 | 3.9 | 20.79 | 14.85 | 8.15 | 13.62 | 19.54 | dragon | 216.152.156.65 |
| 92.14 | trojan | 294.9 | 2.2 | 20.95 | 14.92 | 9.2 | 13.62 | 19.54 | dragon | 170.101.101.67 |
| 90.68 | trojan | 308.1 | 0.8 | 20.65 | 14.97 | 9.33 | 13.62 | 19.54 | dragon | 167.88.61.20 |
| 90.57 | trojan | 307.9 | 0.5 | 20.65 | 14.98 | 8.95 | 13.62 | 19.54 | dragon | 66.163.112.142 |
| 90.47 | trojan | 243.8 | 1.9 | 22.13 | 14.93 | 8.88 | 13.62 | 19.54 | dragon | 216.152.155.158 |
| 90.3 | trojan | 347.5 | 3.1 | 19.73 | 14.88 | 7.22 | 13.62 | 19.54 | dragon | 216.152.155.23 |
| 90.29 | trojan | 322.8 | 4.6 | 20.31 | 14.83 | 9.49 | 13.62 | 19.54 | dragon | 216.152.155.176 |
| 90.02 | trojan | 317.2 | 1.9 | 20.44 | 14.93 | 4.51 | 13.62 | 19.54 | dragon | 66.23.203.21 |
| 90.0 | trojan | 295.3 | 2.6 | 20.94 | 14.9 | 7.75 | 13.62 | 19.54 | dragon | resources.findlocaljobnetworkandbuildcommunityconnections.com |
| 89.88 | trojan | 266.3 | 3.2 | 21.61 | 14.88 | 8.77 | 13.62 | 19.54 | dragon | 216.152.155.59 |
| 89.88 | trojan | 358.2 | 6.4 | 19.49 | 14.76 | 9.89 | 13.62 | 19.54 | dragon | 169.197.140.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.981 | 0.91 | 89 | 10000 | prefer |
| Au1rxx-base64 | 0.695 | 0.633 | 30 | 1751 | observe |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 8355 | observe |
| mheidari-all | 0.401 | 0.571 | 7 | 14971 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4941 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2726 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10678 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5917 | observe |
| barry-far-vless | 0.255 | None | 0 | 6131 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4726 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 38 | 7 | - |
| global | False | 219 | 112 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
