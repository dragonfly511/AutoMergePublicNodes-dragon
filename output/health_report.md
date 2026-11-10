# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-10 07:35:30 |
| 运行耗时 | 255.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101909 |
| 去重后节点 | 34014 |
| TCP 可达 | 3000 |
| 真实可用 | 265 |
| Verified 输出 | 12 |
| Global 输出 | 265 |
| All 输出 | 34014 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 95.5 |
| probe | 73.8 |
| real_test | 36.3 |
| china_check | 27.9 |
| write_verified | 0.0 |
| generate | 13.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60524 |
| vmess | 17290 |
| trojan | 11343 |
| shadowsocks | 10389 |
| hysteria2 | 1837 |
| http | 247 |
| shadowsocksr | 154 |
| socks | 58 |
| hysteria | 30 |
| tuic | 22 |
| anytls | 15 |

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
| 95.51 | shadowsocks | 192.7 | 0.9 | 23.32 | 14.97 | 8.31 | 13.55 | 19.86 | dragon | 95.215.201.18 |
| 93.21 | trojan | 193.6 | 0.1 | 23.3 | 14.99 | 6.31 | 11.25 | 19.86 | dragon | 66.163.112.13 |
| 93.01 | trojan | 201.1 | 0.4 | 23.12 | 14.98 | 6.3 | 11.25 | 19.86 | dragon | 66.163.112.121 |
| 92.98 | trojan | 198.8 | 0.6 | 23.18 | 14.98 | 6.21 | 11.25 | 19.86 | dragon | 66.163.112.171 |
| 92.96 | trojan | 203.5 | 1.4 | 23.07 | 14.95 | 6.33 | 11.25 | 19.86 | dragon | 66.163.112.31 |
| 92.81 | trojan | 197.0 | 0.6 | 23.22 | 14.98 | 6.0 | 11.25 | 19.86 | dragon | 66.163.112.242 |
| 92.79 | trojan | 196.8 | 2.0 | 23.22 | 14.92 | 6.04 | 11.25 | 19.86 | dragon | 66.163.112.147 |
| 89.14 | trojan | 218.9 | 1.5 | 22.71 | 14.94 | 7.88 | 11.25 | 19.86 | dragon | 167.88.61.85 |
| 88.9 | trojan | 305.8 | 4.6 | 20.7 | 14.83 | 7.57 | 11.25 | 19.86 | dragon | 216.106.186.32 |
| 88.83 | trojan | 220.1 | 1.8 | 22.68 | 14.93 | 7.61 | 11.25 | 19.86 | dragon | 167.88.61.198 |
| 88.79 | trojan | 220.4 | 1.0 | 22.68 | 14.96 | 7.54 | 11.25 | 19.86 | dragon | 167.88.61.20 |
| 88.61 | trojan | 277.2 | 0.8 | 21.36 | 14.97 | 7.61 | 11.25 | 19.86 | dragon | 66.163.114.132 |
| 88.28 | trojan | 328.8 | 1.4 | 20.17 | 14.95 | 7.55 | 11.25 | 19.86 | dragon | 167.88.61.193 |
| 87.66 | hysteria2 | 263.5 | 15.1 | 21.68 | 14.43 | 0.0 | 12.69 | 19.86 | dragon | 66.94.121.46 |
| 87.66 | trojan | 275.2 | 3.9 | 21.41 | 14.85 | 7.37 | 11.25 | 19.86 | dragon | 66.163.114.245 |
| 87.37 | shadowsocks | 340.0 | 1.0 | 19.91 | 14.96 | 7.88 | 13.55 | 19.86 | dragon | 37.19.198.244 |
| 87.13 | shadowsocks | 215.9 | 1.5 | 22.78 | 14.94 | 0.0 | 13.55 | 19.86 | dragon | 173.244.56.6 |
| 86.82 | shadowsocks | 409.0 | 1.7 | 18.31 | 14.94 | 8.28 | 13.55 | 19.86 | dragon | 149.40.57.134 |
| 86.55 | trojan | 271.1 | 0.3 | 21.5 | 14.99 | 7.54 | 11.25 | 19.86 | dragon | 66.163.114.114 |
| 86.27 | trojan | 346.5 | 2.1 | 19.76 | 14.92 | 7.37 | 11.25 | 19.86 | dragon | 216.238.80.100 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.935 | 262 | 10000 | prefer |
| dragon2 | 0.622 | 0.545 | 22 | 10000 | observe |
| mheidari-all | 0.446 | 0.8 | 5 | 13900 | observe |
| dragon3 | 0.362 | 1.0 | 3 | 100 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8228 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2754 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11021 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6133 | observe |
| barry-far-vless | 0.255 | None | 0 | 6344 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4583 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 10 | 12 | - |
| global | False | 163 | 265 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
