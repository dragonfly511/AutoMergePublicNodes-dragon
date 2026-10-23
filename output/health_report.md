# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 08:41:51 |
| 运行耗时 | 287.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96124 |
| 去重后节点 | 26841 |
| TCP 可达 | 3000 |
| 真实可用 | 441 |
| Verified 输出 | 160 |
| Global 输出 | 300 |
| All 输出 | 26841 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 82.7 |
| probe | 73.0 |
| real_test | 89.9 |
| china_check | 28.0 |
| write_verified | 0.0 |
| generate | 8.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56824 |
| vmess | 17137 |
| shadowsocks | 12262 |
| trojan | 7980 |
| hysteria2 | 1336 |
| http | 339 |
| shadowsocksr | 140 |
| socks | 58 |
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
| 96.43 | hysteria2 | 270.9 | 0.2 | 21.51 | 14.99 | 9.87 | 14.0 | 17.56 | Au1rxx-base64 | 129.213.91.185 |
| 94.53 | shadowsocks | 259.2 | 0.6 | 21.78 | 14.98 | 9.98 | 14.24 | 17.56 | Au1rxx-base64 | 156.146.38.170 |
| 94.41 | shadowsocks | 266.4 | 0.1 | 21.61 | 15.0 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 156.146.38.168 |
| 93.55 | shadowsocks | 288.5 | 1.3 | 21.1 | 14.95 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 37.19.198.236 |
| 92.78 | shadowsocks | 303.2 | 0.2 | 20.76 | 14.99 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 37.19.198.244 |
| 92.61 | shadowsocks | 273.7 | 0.6 | 21.44 | 14.98 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 156.146.38.167 |
| 92.31 | shadowsocks | 300.5 | 0.4 | 20.82 | 14.99 | 9.82 | 14.24 | 17.56 | Au1rxx-base64 | 37.19.198.160 |
| 90.31 | shadowsocks | 306.6 | 0.3 | 20.68 | 14.99 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 185.230.230.18 |
| 89.41 | trojan | 354.4 | 5.4 | 19.57 | 14.8 | 10.0 | 14.06 | 17.56 | Au1rxx-base64 | 66.23.203.21 |
| 89.17 | shadowsocks | 367.2 | 0.6 | 19.28 | 14.98 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 185.215.132.9 |
| 88.8 | shadowsocks | 309.8 | 2.8 | 20.61 | 14.9 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 193.151.163.18 |
| 88.51 | shadowsocks | 308.3 | 0.8 | 20.64 | 14.97 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 149.22.95.183 |
| 87.87 | shadowsocks | 345.2 | 1.9 | 19.79 | 14.93 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 173.244.56.6 |
| 87.86 | shadowsocks | 330.7 | 1.7 | 20.12 | 14.94 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 173.244.56.9 |
| 87.7 | vless | 288.7 | 0.3 | 21.09 | 14.99 | 9.94 | 8.15 | 17.56 | Au1rxx-base64 | 45.76.172.197 |
| 87.45 | shadowsocks | 410.1 | 0.2 | 18.29 | 14.99 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 193.151.160.9 |
| 87.38 | vless | 292.4 | 0.4 | 21.01 | 14.99 | 9.95 | 8.15 | 17.56 | Au1rxx-base64 | 45.32.69.110 |
| 87.27 | trojan | 312.2 | 2.2 | 20.55 | 14.92 | 7.88 | 14.06 | 17.56 | Au1rxx-base64 | 216.106.186.32 |
| 87.27 | shadowsocks | 412.3 | 1.5 | 18.23 | 14.94 | 10.0 | 14.24 | 17.56 | Au1rxx-base64 | 193.151.160.18 |
| 87.2 | vless | 387.7 | 0.5 | 18.8 | 14.98 | 10.0 | 8.15 | 17.56 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.986 | 0.971 | 102 | 609 | prefer |
| Au1rxx-base64 | 0.903 | 0.845 | 264 | 1524 | prefer |
| Surfboard-tg-mixed | 0.744 | 0.667 | 105 | 6999 | prefer |
| mheidari-all | 0.657 | 0.579 | 76 | 23755 | observe |
| DeltaKronecker-all | 0.322 | 0.25 | 16 | 3871 | observe |
| ninja-vless | 0.279 | 0.5 | 2 | 1791 | observe |
| tg-oneclickvpnkeys | 0.272 | 0.667 | 3 | 83 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7492 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9987 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5447 | observe |
| barry-far-vless | 0.255 | None | 0 | 5662 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 70 |
| speed | ClientOSError | - | 15 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 4 |
| geo | ProxyError | - | 3 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 175 | 160 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
