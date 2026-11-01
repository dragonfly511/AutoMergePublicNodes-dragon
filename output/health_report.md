# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 06:32:17 |
| 运行耗时 | 269.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 90 |
| 原始节点 | 90500 |
| 去重后节点 | 33136 |
| TCP 可达 | 3000 |
| 真实可用 | 134 |
| Verified 输出 | 38 |
| Global 输出 | 136 |
| All 输出 | 33136 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 84.0 |
| probe | 95.1 |
| real_test | 26.3 |
| china_check | 37.1 |
| write_verified | 0.0 |
| generate | 17.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53433 |
| vmess | 13872 |
| trojan | 12332 |
| shadowsocks | 8948 |
| hysteria2 | 1511 |
| http | 158 |
| shadowsocksr | 154 |
| socks | 50 |
| anytls | 19 |
| tuic | 12 |
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
| 96.26 | trojan | 243.4 | 6.6 | 22.14 | 14.75 | 7.16 | 14.71 | 20.0 | dragon | 216.106.186.33 |
| 94.29 | trojan | 241.3 | 2.9 | 22.19 | 14.89 | 10.0 | 14.71 | 20.0 | dragon | 66.163.112.13 |
| 93.87 | trojan | 240.8 | 0.9 | 22.2 | 14.97 | 10.0 | 14.71 | 20.0 | dragon | 66.163.112.121 |
| 93.39 | trojan | 266.8 | 0.6 | 21.6 | 14.98 | 10.0 | 14.71 | 20.0 | dragon | 66.163.114.114 |
| 92.46 | trojan | 239.7 | 0.9 | 22.23 | 14.97 | 3.05 | 14.71 | 20.0 | dragon | 216.106.186.32 |
| 89.53 | trojan | 261.8 | 0.2 | 21.72 | 14.99 | 3.61 | 14.71 | 20.0 | dragon | 66.163.112.142 |
| 89.38 | trojan | 173.9 | 0.1 | 23.75 | 15.0 | 3.42 | 14.71 | 20.0 | dragon | 167.88.61.193 |
| 88.86 | trojan | 381.9 | 0.3 | 18.94 | 14.99 | 10.0 | 14.71 | 20.0 | dragon | 216.152.156.65 |
| 88.73 | hysteria2 | 333.3 | 1.4 | 20.06 | 14.95 | 5.88 | 12.5 | 20.0 | dragon | 129.213.91.185 |
| 88.61 | trojan | 292.9 | 0.1 | 21.0 | 15.0 | 3.81 | 14.71 | 20.0 | dragon | 66.163.114.126 |
| 88.49 | trojan | 259.3 | 37.2 | 21.78 | 13.61 | 6.39 | 14.71 | 20.0 | dragon | 38.102.234.153 |
| 88.4 | trojan | 326.6 | 0.6 | 20.22 | 14.98 | 10.0 | 14.71 | 20.0 | dragon | 216.152.155.54 |
| 88.28 | trojan | 267.2 | 0.5 | 21.59 | 14.98 | 10.0 | 14.71 | 20.0 | dragon | 66.163.114.132 |
| 88.1 | trojan | 307.8 | 0.0 | 20.65 | 15.0 | 3.95 | 14.71 | 20.0 | dragon | 66.163.114.45 |
| 88.04 | trojan | 328.6 | 0.9 | 20.17 | 14.97 | 10.0 | 14.71 | 20.0 | dragon | 216.152.155.176 |
| 87.4 | trojan | 257.4 | 1.0 | 21.82 | 14.96 | 3.61 | 14.71 | 20.0 | dragon | 66.163.112.171 |
| 87.23 | trojan | 327.6 | 3.3 | 20.2 | 14.88 | 10.0 | 14.71 | 20.0 | dragon | 216.152.155.23 |
| 87.19 | trojan | 274.6 | 0.2 | 21.42 | 14.99 | 3.81 | 14.71 | 20.0 | dragon | 66.163.114.166 |
| 87.0 | trojan | 280.8 | 2.4 | 21.28 | 14.91 | 3.6 | 14.71 | 20.0 | dragon | 66.163.112.242 |
| 86.96 | trojan | 274.0 | 0.4 | 21.43 | 14.99 | 3.68 | 14.71 | 20.0 | dragon | 66.163.114.106 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.998 | 0.927 | 96 | 10000 | prefer |
| Au1rxx-base64 | 0.956 | 0.909 | 33 | 1751 | prefer |
| mheidari-all | 0.698 | 0.846 | 13 | 14747 | observe |
| Surfboard-tg-mixed | 0.4 | 0.75 | 4 | 7809 | observe |
| ermaozi-get_subscribe | 0.277 | 1.0 | 1 | 558 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10495 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5637 | observe |
| barry-far-vless | 0.255 | None | 0 | 5805 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4680 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 32 | 38 | - |
| global | False | 228 | 136 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
