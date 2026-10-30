# AutoNodes 每日报告

生成时间：2026-10-30 02:50:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 109194 |
| 去重后节点数 | 35032 |
| TCP 可达数 | 3000 |
| 真测通过数 | 230 |
| verified 输出数 | 39 |
| global 输出数 | 231 |
| all 输出数 | 35032 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.8 |
| fetch | 8.3 |
| generate | 16.1 |
| geo | 1.5 |
| probe | 92.5 |
| real_test | 45.5 |
| tcp | 104.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 147 | 140 | 7 | 95.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 51 | 49 | 2 | 96.1% |
| vless | 34 | 25 | 9 | 73.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 3 |
| geo:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7528 |
| ConnectionRefusedError | 1117 |
| OSError | 237 |
| gaierror | 174 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 200 | 0.955 | 10000 |
| Au1rxx-base64 | 0.874 | prefer | 34 | 0.824 | 1709 |
| mheidari-all | 0.586 | observe | 10 | 0.8 | 33573 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 7756 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10432 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 498 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 389 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 384 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 133 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.8 | 8 | 2 | 10 |
| Au1rxx-base64 | 0.824 | 28 | 6 | 34 |
| dragon | 0.955 | 191 | 9 | 200 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33573 | yes | 6.02 | 0 |
| SoliSpirit-all | 10432 | yes | 3.08 | 0 |
| dragon | 10000 | yes | 7.7 | 0 |
| Surfboard-tg-mixed | 7756 | yes | 4.02 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.17 | 0 |
| barry-far-vless | 5941 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 5729 | yes | 3.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.61 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 5 |
| geo | 3 |
| cn-block | 2 |
