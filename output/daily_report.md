# AutoNodes 每日报告

生成时间：2026-11-24 00:11:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/1 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 100323 |
| 去重后节点数 | 35158 |
| TCP 可达数 | 3000 |
| 真测通过数 | 265 |
| verified 输出数 | 11 |
| global 输出数 | 269 |
| all 输出数 | 35158 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.0 |
| fetch | 9.1 |
| generate | 18.8 |
| geo | 1.9 |
| probe | 94.8 |
| real_test | 46.6 |
| tcp | 100.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 186 | 176 | 10 | 94.6% |
| socks | 9 | 8 | 1 | 88.9% |
| trojan | 73 | 70 | 3 | 95.9% |
| vless | 20 | 7 | 13 | 35.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| geo:ClientOSError | 3 |
| 204:ProxyError | 2 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7205 |
| ConnectionRefusedError | 1081 |
| gaierror | 275 |
| OSError | 244 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 265 | 0.943 | 10000 |
| Surfboard-tg-mixed | 0.446 | observe | 5 | 0.8 | 8626 |
| mheidari-all | 0.446 | observe | 5 | 0.8 | 15543 |
| dragon2 | 0.421 | observe | 6 | 0.667 | 10000 |
| SoliSpirit-all | 0.349 | observe | 3 | 0.667 | 11809 |
| ermaozi-get_subscribe | 0.324 | observe | 2 | 1.0 | 330 |
| dragon3 | 0.296 | observe | 9 | 0.444 | 100 |
| ermaozi | 0.272 | observe | 1 | 1.0 | 420 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 88 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5064 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 442 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 437 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 320 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 186 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |
| downweight | xiaoji235-airport-v2ray-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.2 | 1 | 4 | 5 |
| dragon3 | 0.444 | 4 | 5 | 9 |
| SoliSpirit-all | 0.667 | 2 | 1 | 3 |
| dragon2 | 0.667 | 4 | 2 | 6 |
| mheidari-all | 0.8 | 4 | 1 | 5 |
| Surfboard-tg-mixed | 0.8 | 4 | 1 | 5 |
| dragon | 0.943 | 250 | 15 | 265 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15543 | yes | 6.37 | 0 |
| SoliSpirit-all | 11809 | yes | 3.52 | 0 |
| dragon | 10000 | yes | 8.15 | 0 |
| dragon2 | 10000 | yes | 5.38 | 0 |
| Surfboard-tg-mixed | 8626 | yes | 3.78 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.14 | 0 |
| barry-far-vless | 5847 | yes | 2.8 | 0 |
| Surfboard-tg-vless | 5667 | yes | 4.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 5064 | yes | 1.34 | 0 |
| mahdibland-V2RayAggregator | 4514 | yes | 2.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| cn-block | 6 |
| speed | 4 |
| 204 | 3 |
| geo | 3 |
