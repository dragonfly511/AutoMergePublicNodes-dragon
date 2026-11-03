# AutoNodes 每日报告

生成时间：2026-11-03 07:05:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/1 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 91802 |
| 去重后节点数 | 34092 |
| TCP 可达数 | 3000 |
| 真测通过数 | 81 |
| verified 输出数 | 9 |
| global 输出数 | 82 |
| all 输出数 | 34092 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.2 |
| fetch | 8.6 |
| generate | 17.2 |
| geo | 1.5 |
| probe | 95.5 |
| real_test | 36.7 |
| tcp | 91.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| hysteria2 | 16 | 12 | 4 | 75.0% |
| shadowsocks | 9 | 7 | 2 | 77.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 84 | 52 | 32 | 61.9% |
| vless | 15 | 5 | 10 | 33.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 44 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6390 |
| ConnectionRefusedError | 1003 |
| OSError | 236 |
| gaierror | 209 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 76 | 0.934 | 10000 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 8355 |
| mheidari-all | 0.349 | observe | 3 | 0.667 | 14871 |
| Au1rxx-base64 | 0.316 | observe | 15 | 0.267 | 1751 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4941 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2726 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10703 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5917 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| peasoft-NoMoreWalls | 0.04 | downweight | 29 | 0.0 | 0 | 200 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 396 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 391 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 140 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 127 | 连续死亡次数 >= 2 |
| downweight | peasoft-NoMoreWalls | 0.04 | 29 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| peasoft-NoMoreWalls | 0.0 | 0 | 29 | 29 |
| Au1rxx-base64 | 0.267 | 4 | 11 | 15 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| mheidari-all | 0.667 | 2 | 1 | 3 |
| dragon | 0.934 | 71 | 5 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14871 | yes | 6.07 | 0 |
| SoliSpirit-all | 10703 | yes | 2.5 | 0 |
| dragon | 10000 | yes | 8.0 | 0 |
| Surfboard-tg-mixed | 8355 | yes | 4.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.4 | 0 |
| barry-far-vless | 6133 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 5917 | yes | 3.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 4941 | yes | 1.06 | 0 |
| mahdibland-V2RayAggregator | 4734 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.55 | 0 |

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
| test_one_timeout | 44 |
| 204 | 3 |
| cn-block | 3 |
