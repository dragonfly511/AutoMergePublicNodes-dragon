# AutoNodes 每日报告

生成时间：2026-11-23 07:59:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 103325 |
| 去重后节点数 | 35939 |
| TCP 可达数 | 3000 |
| 真测通过数 | 225 |
| verified 输出数 | 16 |
| global 输出数 | 227 |
| all 输出数 | 35939 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.0 |
| fetch | 8.9 |
| generate | 19.1 |
| geo | 1.5 |
| probe | 93.7 |
| real_test | 42.2 |
| tcp | 96.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 201 | 190 | 11 | 94.5% |
| socks | 10 | 9 | 1 | 90.0% |
| trojan | 2 | 2 | 0 | 100.0% |
| vless | 36 | 22 | 14 | 61.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| speed:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6807 |
| ConnectionRefusedError | 1073 |
| gaierror | 309 |
| OSError | 250 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.967 | prefer | 236 | 0.89 | 10000 |
| dragon3 | 0.553 | observe | 8 | 1.0 | 100 |
| ermaozi | 0.496 | observe | 6 | 1.0 | 486 |
| dragon2 | 0.48 | observe | 4 | 1.0 | 10000 |
| Surfboard-tg-mixed | 0.4 | observe | 4 | 0.75 | 8701 |
| mheidari-all | 0.349 | observe | 3 | 0.667 | 15418 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 421 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5069 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 441 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 436 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 319 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 185 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.75 | 3 | 1 | 4 |
| dragon | 0.89 | 210 | 26 | 236 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| dragon2 | 1.0 | 4 | 0 | 4 |
| ermaozi | 1.0 | 6 | 0 | 6 |
| dragon3 | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15418 | yes | 6.36 | 0 |
| SoliSpirit-all | 11834 | yes | 2.31 | 0 |
| dragon | 10000 | yes | 8.21 | 0 |
| dragon2 | 10000 | yes | 4.29 | 0 |
| Surfboard-tg-mixed | 8701 | yes | 3.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.55 | 0 |
| barry-far-vless | 5831 | yes | 1.92 | 0 |
| Surfboard-tg-vless | 5650 | yes | 3.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 5069 | yes | 1.33 | 0 |
| mahdibland-V2RayAggregator | 4514 | yes | 1.69 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 4 |
| cn-block | 3 |
| speed | 1 |
