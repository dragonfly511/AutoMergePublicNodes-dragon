# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 09:12:13 |
| 运行耗时 | 314.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 91 |
| 原始节点 | 98553 |
| 去重后节点 | 29489 |
| TCP 可达 | 3000 |
| 真实可用 | 416 |
| Verified 输出 | 146 |
| Global 输出 | 300 |
| All 输出 | 29489 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 91.7 |
| probe | 97.4 |
| real_test | 81.6 |
| china_check | 18.1 |
| write_verified | 0.1 |
| generate | 15.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57489 |
| vmess | 16899 |
| shadowsocks | 12204 |
| trojan | 10023 |
| hysteria2 | 1332 |
| http | 339 |
| shadowsocksr | 165 |
| socks | 54 |
| anytls | 25 |
| hysteria | 17 |
| tuic | 6 |

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
| 94.72 | vless | 217.8 | 2.8 | 22.74 | 14.9 | 10.0 | 9.02 | 18.06 | Au1rxx-base64 | 154.29.145.196 |
| 94.58 | shadowsocks | 259.1 | 5.6 | 21.78 | 14.79 | 10.0 | 13.95 | 18.06 | Au1rxx-base64 | 149.22.95.183 |
| 94.35 | vless | 232.3 | 2.5 | 22.4 | 14.9 | 9.97 | 9.02 | 18.06 | Au1rxx-base64 | 45.32.69.110 |
| 94.27 | vless | 199.7 | 5.7 | 23.15 | 14.79 | 9.45 | 9.02 | 18.06 | Au1rxx-base64 | 216.167.126.97 |
| 94.22 | vless | 237.3 | 3.3 | 22.29 | 14.88 | 9.97 | 9.02 | 18.06 | Au1rxx-base64 | 144.202.126.147 |
| 93.76 | shadowsocks | 273.3 | 0.7 | 21.45 | 14.98 | 10.0 | 13.95 | 18.06 | Au1rxx-base64 | 173.244.56.9 |
| 92.42 | vless | 311.2 | 5.4 | 20.57 | 14.8 | 9.97 | 9.02 | 18.06 | Au1rxx-base64 | 45.76.172.197 |
| 92.37 | vless | 208.1 | 4.1 | 22.96 | 14.85 | 7.48 | 9.02 | 18.06 | Au1rxx-base64 | 172.236.227.60 |
| 91.16 | trojan | 240.1 | 0.3 | 22.22 | 14.99 | 7.8 | 10.59 | 18.06 | Au1rxx-base64 | 216.106.186.32 |
| 90.65 | shadowsocks | 291.9 | 1.3 | 21.02 | 14.95 | 10.0 | 13.95 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 90.61 | shadowsocks | 293.2 | 7.3 | 20.99 | 14.73 | 10.0 | 13.95 | 18.06 | Au1rxx-base64 | 156.146.38.167 |
| 90.44 | hysteria2 | 336.2 | 1.0 | 19.99 | 14.96 | 9.32 | 13.33 | 18.06 | Au1rxx-base64 | 129.213.91.185 |
| 90.19 | vless | 412.7 | 0.6 | 18.22 | 14.98 | 9.91 | 9.02 | 18.06 | Au1rxx-base64 | 51.81.203.63 |
| 89.93 | vless | 229.9 | 0.3 | 22.46 | 14.99 | 5.4 | 9.02 | 18.06 | Au1rxx-base64 | 15.204.97.209 |
| 89.84 | shadowsocks | 299.1 | 0.6 | 20.86 | 14.98 | 9.62 | 13.95 | 18.06 | Au1rxx-base64 | 156.146.38.170 |
| 89.74 | vless | 222.0 | 4.0 | 22.64 | 14.85 | 5.17 | 9.02 | 18.06 | Au1rxx-base64 | 154.12.38.202 |
| 89.27 | http | 194.9 | 0.4 | 23.27 | 14.99 | 0.0 | 14.29 | 19.72 | ermaozi | 138.199.35.196 |
| 89.25 | http | 193.3 | 1.7 | 23.3 | 14.94 | 0.0 | 14.29 | 19.72 | ermaozi | 138.199.35.213 |
| 89.17 | http | 198.2 | 0.8 | 23.19 | 14.97 | 0.0 | 14.29 | 19.72 | ermaozi | 138.199.35.215 |
| 89.15 | http | 195.9 | 2.6 | 23.24 | 14.9 | 0.0 | 14.29 | 19.72 | ermaozi | 138.199.35.208 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | 0.961 | 103 | 609 | prefer |
| Au1rxx-base64 | 0.861 | 0.802 | 253 | 1537 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.657 | 102 | 6855 | prefer |
| mheidari-all | 0.597 | 0.517 | 87 | 23755 | observe |
| tg-oneclickvpnkeys | 0.272 | 0.667 | 3 | 83 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7492 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9987 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5326 | observe |
| barry-far-vless | 0.255 | None | 0 | 5662 | observe |
| dragon | 0.255 | None | 0 | 3000 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4230 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 67 |
| speed | ClientOSError | - | 17 |
| 204 | TimeoutError | - | 16 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 160 | 146 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
