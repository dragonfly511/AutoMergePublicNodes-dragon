# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-02 06:33:39 |
| 运行耗时 | 301.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 92989 |
| 去重后节点 | 34103 |
| TCP 可达 | 3000 |
| 真实可用 | 217 |
| Verified 输出 | 38 |
| Global 输出 | 219 |
| All 输出 | 34103 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 91.3 |
| probe | 93.2 |
| real_test | 38.2 |
| china_check | 50.7 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55284 |
| vmess | 14007 |
| trojan | 12595 |
| shadowsocks | 9057 |
| hysteria2 | 1560 |
| http | 202 |
| shadowsocksr | 152 |
| socks | 79 |
| anytls | 27 |
| tuic | 15 |
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
| 95.08 | trojan | 181.8 | 2.2 | 23.57 | 14.92 | 9.95 | 13.64 | 16.5 | dragon | 167.88.61.20 |
| 94.02 | trojan | 184.4 | 3.6 | 23.51 | 14.87 | 10.0 | 13.64 | 16.5 | dragon | 167.88.61.193 |
| 93.58 | trojan | 245.2 | 9.9 | 22.1 | 14.63 | 9.21 | 13.64 | 16.5 | dragon | resources.findlocaljobnetworkandbuildcommunityconnections.com |
| 92.78 | trojan | 252.4 | 3.7 | 21.93 | 14.86 | 8.35 | 13.64 | 16.5 | dragon | blog.findlocaljobnetworkandbuildcommunityconnections.com |
| 92.59 | trojan | 243.6 | 3.0 | 22.14 | 14.89 | 9.67 | 13.64 | 16.5 | dragon | 66.163.112.142 |
| 91.46 | trojan | 311.0 | 1.4 | 20.58 | 14.95 | 9.94 | 13.64 | 16.5 | dragon | 66.163.114.114 |
| 91.16 | trojan | 235.6 | 1.4 | 22.32 | 14.95 | 10.0 | 13.64 | 16.5 | dragon | 66.163.112.31 |
| 91.01 | trojan | 182.6 | 3.2 | 23.55 | 14.88 | 9.94 | 13.64 | 16.5 | dragon | 167.88.61.175 |
| 90.66 | trojan | 251.6 | 2.4 | 21.95 | 14.91 | 8.76 | 13.64 | 16.5 | dragon | 66.163.112.121 |
| 90.27 | trojan | 249.6 | 3.3 | 22.0 | 14.88 | 8.75 | 13.64 | 16.5 | dragon | 66.163.112.76 |
| 90.23 | trojan | 286.8 | 3.0 | 21.14 | 14.89 | 8.75 | 13.64 | 16.5 | dragon | 66.163.112.13 |
| 89.81 | trojan | 241.7 | 0.4 | 22.18 | 14.99 | 10.0 | 13.64 | 16.5 | dragon | 216.106.186.33 |
| 89.38 | trojan | 248.7 | 0.9 | 22.02 | 14.97 | 9.75 | 13.64 | 16.5 | dragon | 216.106.186.82 |
| 89.03 | trojan | 242.6 | 4.5 | 22.16 | 14.83 | 9.4 | 13.64 | 16.5 | dragon | www.findlocaljobnetworkandbuildcommunityconnections.com |
| 89.02 | trojan | 269.1 | 9.4 | 21.55 | 14.65 | 8.65 | 13.64 | 16.5 | dragon | 66.163.114.166 |
| 89.01 | trojan | 244.1 | 11.1 | 22.13 | 14.59 | 9.65 | 13.64 | 16.5 | dragon | 216.106.186.46 |
| 89.01 | trojan | 249.1 | 0.3 | 22.01 | 14.99 | 9.37 | 13.64 | 16.5 | dragon | 216.106.186.32 |
| 88.94 | trojan | 268.3 | 10.3 | 21.57 | 14.61 | 8.65 | 13.64 | 16.5 | dragon | 66.163.114.132 |
| 85.42 | trojan | 227.6 | 219.6 | 22.51 | 6.77 | 10.0 | 13.64 | 16.5 | dragon | 38.102.234.153 |
| 83.88 | trojan | 380.0 | 0.5 | 18.98 | 14.98 | 6.61 | 13.64 | 16.5 | dragon | 66.23.203.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | 0.9 | 201 | 10000 | prefer |
| Au1rxx-base64 | 0.919 | 0.871 | 31 | 1751 | prefer |
| mheidari-all | 0.557 | 1.0 | 6 | 15216 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| Surfboard-tg-mixed | 0.284 | 0.333 | 6 | 8273 | observe |
| ermaozi-get_subscribe | 0.277 | 1.0 | 1 | 547 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10657 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6036 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4726 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| geo | ClientOSError | - | 4 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| speed | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 38 | 17 | 0.5 |
| global | False | 116 | 219 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
