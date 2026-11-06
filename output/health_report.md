# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 07:06:14 |
| 运行耗时 | 235.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 92780 |
| 去重后节点 | 34555 |
| TCP 可达 | 3000 |
| 真实可用 | 108 |
| Verified 输出 | 6 |
| Global 输出 | 108 |
| All 输出 | 34555 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.6 |
| tcp | 90.8 |
| probe | 74.0 |
| real_test | 31.7 |
| china_check | 18.5 |
| write_verified | 0.0 |
| generate | 12.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56346 |
| vmess | 14403 |
| trojan | 10541 |
| shadowsocks | 9231 |
| hysteria2 | 1614 |
| http | 352 |
| shadowsocksr | 145 |
| socks | 79 |
| hysteria | 35 |
| anytls | 18 |
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
| 92.47 | trojan | 209.0 | 4.9 | 22.94 | 14.82 | 10.0 | 9.41 | 17.8 | dragon | 66.163.112.121 |
| 92.42 | trojan | 202.3 | 10.0 | 23.09 | 14.62 | 10.0 | 9.41 | 17.8 | dragon | 66.163.112.142 |
| 91.76 | trojan | 212.4 | 21.5 | 22.86 | 14.19 | 10.0 | 9.41 | 17.8 | dragon | 66.163.112.31 |
| 90.0 | trojan | 322.3 | 0.9 | 20.32 | 14.97 | 10.0 | 9.41 | 17.8 | dragon | 66.163.112.242 |
| 87.18 | trojan | 334.3 | 3.7 | 20.04 | 14.86 | 10.0 | 9.41 | 17.8 | dragon | 216.106.186.82 |
| 85.72 | shadowsocks | 191.4 | 0.8 | 23.35 | 14.97 | 0.0 | 13.7 | 17.8 | dragon | 38.145.220.193 |
| 85.54 | trojan | 278.5 | 2.2 | 21.33 | 14.92 | 8.86 | 9.41 | 17.8 | dragon | 216.106.186.33 |
| 85.44 | hysteria2 | 257.3 | 10.5 | 21.82 | 14.61 | 0.0 | 13.0 | 17.8 | dragon | 66.94.121.46 |
| 85.25 | trojan | 341.2 | 5.5 | 19.88 | 14.8 | 10.0 | 9.41 | 17.8 | dragon | 216.238.80.100 |
| 85.12 | trojan | 340.0 | 1.2 | 19.91 | 14.96 | 10.0 | 9.41 | 17.8 | dragon | 216.152.155.176 |
| 84.88 | trojan | 404.5 | 1.2 | 18.42 | 14.95 | 10.0 | 9.41 | 17.8 | dragon | 66.23.203.21 |
| 84.64 | trojan | 342.6 | 9.2 | 19.85 | 14.65 | 10.0 | 9.41 | 17.8 | dragon | 216.152.155.158 |
| 84.33 | trojan | 368.0 | 3.2 | 19.26 | 14.88 | 10.0 | 9.41 | 17.8 | dragon | 169.197.140.224 |
| 84.15 | trojan | 371.8 | 4.4 | 19.17 | 14.83 | 10.0 | 9.41 | 17.8 | dragon | 169.197.140.214 |
| 83.7 | trojan | 377.2 | 12.4 | 19.05 | 14.53 | 10.0 | 9.41 | 17.8 | dragon | 169.197.140.171 |
| 83.57 | trojan | 395.4 | 5.6 | 18.63 | 14.79 | 10.0 | 9.41 | 17.8 | dragon | 216.152.155.23 |
| 83.5 | shadowsocks | 270.9 | 0.4 | 21.51 | 14.99 | 0.0 | 13.7 | 17.8 | dragon | 103.11.76.248 |
| 82.97 | trojan | 368.4 | 0.8 | 19.25 | 14.97 | 10.0 | 9.41 | 17.8 | dragon | 170.101.101.67 |
| 82.32 | trojan | 379.0 | 7.5 | 19.01 | 14.72 | 10.0 | 9.41 | 17.8 | dragon | 170.101.101.211 |
| 82.3 | trojan | 369.8 | 0.1 | 19.22 | 15.0 | 10.0 | 9.41 | 17.8 | dragon | 169.197.140.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.876 | 0.828 | 29 | 1751 | prefer |
| dragon | 0.818 | 0.744 | 78 | 10000 | prefer |
| mheidari-all | 0.805 | 0.875 | 16 | 14233 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.857 | 14 | 8762 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10891 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6268 | observe |
| barry-far-vless | 0.255 | None | 0 | 6478 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 16 |
| test_one_timeout | 15.0s | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 11 | 6 | - |
| global | False | 151 | 108 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
