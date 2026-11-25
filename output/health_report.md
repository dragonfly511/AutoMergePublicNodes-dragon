# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-25 21:56:17 |
| 运行耗时 | 260.5s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 98445 |
| 去重后节点 | 34215 |
| TCP 可达 | 3000 |
| 真实可用 | 244 |
| Verified 输出 | 14 |
| Global 输出 | 249 |
| All 输出 | 34215 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.6 |
| tcp | 82.6 |
| probe | 84.0 |
| real_test | 48.2 |
| china_check | 23.0 |
| write_verified | 0.0 |
| generate | 14.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57534 |
| vmess | 19725 |
| shadowsocks | 10550 |
| trojan | 8234 |
| hysteria2 | 1897 |
| shadowsocksr | 176 |
| http | 145 |
| socks | 97 |
| anytls | 39 |
| hysteria | 32 |
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
| 94.21 | shadowsocks | 267.8 | 1.9 | 21.58 | 14.93 | 9.78 | 13.4 | 18.52 | dragon | 37.19.198.236 |
| 94.1 | shadowsocks | 275.0 | 0.4 | 21.41 | 14.99 | 9.78 | 13.4 | 18.52 | dragon | 37.19.198.243 |
| 93.93 | shadowsocks | 278.1 | 2.9 | 21.34 | 14.89 | 9.78 | 13.4 | 18.52 | dragon | 37.19.198.244 |
| 93.68 | shadowsocks | 271.0 | 2.6 | 21.5 | 14.9 | 9.86 | 13.4 | 18.52 | dragon | 45.86.51.18 |
| 93.67 | shadowsocks | 270.5 | 3.9 | 21.52 | 14.86 | 9.87 | 13.4 | 18.52 | dragon | 185.230.230.18 |
| 93.64 | shadowsocks | 282.5 | 0.5 | 21.24 | 14.98 | 10.0 | 13.4 | 18.52 | dragon | 169.197.140.247 |
| 93.5 | shadowsocks | 272.5 | 10.4 | 21.47 | 14.61 | 10.0 | 13.4 | 18.52 | dragon | 172.111.38.72 |
| 93.47 | shadowsocks | 286.7 | 8.1 | 21.14 | 14.7 | 9.77 | 13.4 | 18.52 | dragon | 156.146.38.169 |
| 93.41 | shadowsocks | 279.2 | 4.8 | 21.31 | 14.82 | 9.86 | 13.4 | 18.52 | dragon | 193.151.160.9 |
| 93.41 | shadowsocks | 290.3 | 1.9 | 21.06 | 14.93 | 10.0 | 13.4 | 18.52 | dragon | 149.40.57.138 |
| 93.35 | shadowsocks | 284.9 | 3.0 | 21.18 | 14.89 | 9.86 | 13.4 | 18.52 | dragon | 193.151.160.18 |
| 93.34 | shadowsocks | 287.0 | 3.3 | 21.13 | 14.88 | 9.91 | 13.4 | 18.52 | dragon | 38.91.107.57 |
| 93.3 | shadowsocks | 285.0 | 7.9 | 21.18 | 14.7 | 10.0 | 13.4 | 18.52 | dragon | 149.40.57.135 |
| 93.21 | shadowsocks | 279.1 | 1.0 | 21.32 | 14.96 | 10.0 | 13.4 | 18.52 | dragon | 185.215.132.9 |
| 92.84 | shadowsocks | 252.7 | 1.7 | 21.93 | 14.94 | 9.8 | 13.4 | 18.52 | dragon | 67.220.73.178 |
| 92.46 | shadowsocks | 281.8 | 5.0 | 21.25 | 14.81 | 10.0 | 13.4 | 18.52 | dragon | 200.102.179.179 |
| 92.44 | shadowsocks | 284.6 | 3.4 | 21.19 | 14.87 | 9.77 | 13.4 | 18.52 | dragon | 193.151.163.18 |
| 92.33 | shadowsocks | 254.3 | 0.1 | 21.89 | 15.0 | 9.69 | 13.4 | 18.52 | dragon | 156.146.38.168 |
| 91.94 | shadowsocks | 259.2 | 1.3 | 21.78 | 14.95 | 9.75 | 13.4 | 18.52 | dragon | 156.146.38.170 |
| 91.82 | hysteria2 | 284.3 | 5.1 | 21.2 | 14.81 | 9.59 | 12.5 | 18.52 | dragon | 172.87.24.53 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.95 | 0.872 | 274 | 10000 | prefer |
| tg-LonUp_M | 0.416 | 0.833 | 6 | 173 | observe |
| dragon2 | 0.349 | 0.667 | 3 | 9790 | observe |
| ermaozi-get_subscribe | 0.307 | 0.6 | 5 | 356 | observe |
| ermaozi | 0.271 | 1.0 | 1 | 403 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11598 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5378 | observe |
| barry-far-vless | 0.255 | None | 0 | 5559 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4463 | observe |
| mheidari-all | 0.255 | None | 0 | 15044 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 5 |
| speed | ProxyError | - | 4 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 14 | - |
| global | False | 224 | 249 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
