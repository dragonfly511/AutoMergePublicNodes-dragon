# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 07:06:56 |
| 运行耗时 | 261.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 92244 |
| 去重后节点 | 34070 |
| TCP 可达 | 3000 |
| 真实可用 | 190 |
| Verified 输出 | 14 |
| Global 输出 | 191 |
| All 输出 | 34070 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.6 |
| tcp | 92.3 |
| probe | 75.0 |
| real_test | 50.8 |
| china_check | 22.4 |
| write_verified | 0.0 |
| generate | 13.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55819 |
| vmess | 14043 |
| trojan | 10804 |
| shadowsocks | 9557 |
| hysteria2 | 1634 |
| shadowsocksr | 154 |
| http | 99 |
| socks | 65 |
| hysteria | 37 |
| anytls | 17 |
| tuic | 15 |

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
| 93.02 | shadowsocks | 234.1 | 10.3 | 22.36 | 14.61 | 10.0 | 13.49 | 18.66 | dragon | 38.145.220.193 |
| 91.39 | trojan | 244.7 | 0.1 | 22.11 | 15.0 | 9.3 | 8.82 | 18.66 | dragon | 66.163.114.114 |
| 90.75 | trojan | 267.1 | 1.6 | 21.59 | 14.94 | 9.24 | 8.82 | 18.66 | dragon | 216.152.155.131 |
| 90.28 | shadowsocks | 235.5 | 0.6 | 22.33 | 14.98 | 4.82 | 13.49 | 18.66 | dragon | 156.146.38.168 |
| 90.17 | trojan | 278.2 | 10.6 | 21.34 | 14.6 | 9.25 | 8.82 | 18.66 | dragon | 216.152.155.23 |
| 90.09 | trojan | 247.4 | 6.7 | 22.05 | 14.75 | 9.31 | 8.82 | 18.66 | dragon | 66.163.114.245 |
| 89.51 | trojan | 284.4 | 15.4 | 21.19 | 14.42 | 9.92 | 8.82 | 18.66 | dragon | 216.152.155.158 |
| 89.16 | shadowsocks | 305.1 | 15.0 | 20.71 | 14.44 | 10.0 | 13.49 | 18.66 | dragon | 103.11.76.248 |
| 88.95 | trojan | 324.2 | 1.7 | 20.27 | 14.94 | 9.25 | 8.82 | 18.66 | dragon | 216.152.155.176 |
| 88.67 | shadowsocks | 240.8 | 2.7 | 22.2 | 14.9 | 3.42 | 13.49 | 18.66 | dragon | 156.146.38.170 |
| 87.98 | trojan | 241.9 | 5.5 | 22.18 | 14.79 | 6.03 | 8.82 | 18.66 | dragon | 66.163.114.126 |
| 87.64 | trojan | 302.7 | 0.5 | 20.77 | 14.98 | 9.1 | 8.82 | 18.66 | dragon | 170.101.101.211 |
| 87.35 | trojan | 242.9 | 3.1 | 22.15 | 14.88 | 8.0 | 8.82 | 18.66 | dragon | 66.163.114.45 |
| 87.29 | trojan | 290.9 | 0.0 | 21.04 | 15.0 | 9.76 | 8.82 | 18.66 | dragon | 66.163.112.121 |
| 87.28 | trojan | 279.4 | 11.2 | 21.31 | 14.58 | 6.41 | 8.82 | 18.66 | dragon | 216.152.155.59 |
| 86.91 | trojan | 291.5 | 8.7 | 21.03 | 14.67 | 6.56 | 8.82 | 18.66 | dragon | 216.152.155.54 |
| 86.58 | trojan | 289.3 | 0.8 | 21.08 | 14.97 | 9.11 | 8.82 | 18.66 | dragon | 66.163.112.76 |
| 86.51 | trojan | 290.4 | 0.4 | 21.05 | 14.98 | 9.11 | 8.82 | 18.66 | dragon | 66.163.112.13 |
| 85.74 | trojan | 287.3 | 3.2 | 21.13 | 14.88 | 8.85 | 8.82 | 18.66 | dragon | 167.88.61.20 |
| 85.49 | trojan | 287.8 | 0.1 | 21.12 | 15.0 | 9.13 | 8.82 | 18.66 | dragon | 66.163.112.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.969 | 0.893 | 187 | 10000 | prefer |
| mheidari-all | 0.568 | 0.875 | 8 | 14576 | observe |
| Au1rxx-base64 | 0.552 | 0.48 | 25 | 1751 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8675 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 351 | observe |
| chromego_merge | 0.264 | 1.0 | 1 | 228 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10857 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6243 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| 204 | ProxyError | - | 11 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 14 | - |
| global | False | 208 | 191 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
