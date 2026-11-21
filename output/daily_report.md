# AutoNodes 每日报告

生成时间：2026-11-21 07:31:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102434 |
| 去重后节点数 | 35244 |
| TCP 可达数 | 3000 |
| 真测通过数 | 134 |
| verified 输出数 | 8 |
| global 输出数 | 138 |
| all 输出数 | 35244 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.6 |
| fetch | 9.0 |
| generate | 18.5 |
| geo | 1.6 |
| probe | 101.9 |
| real_test | 50.2 |
| tcp | 94.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 151 | 106 | 45 | 70.2% |
| socks | 8 | 7 | 1 | 87.5% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 13 | 12 | 1 | 92.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 42 |
| cn-block:ClientOSError | 3 |
| cn-block:TimeoutError | 3 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6552 |
| ConnectionRefusedError | 1047 |
| gaierror | 325 |
| OSError | 237 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.809 | prefer | 168 | 0.732 | 10000 |
| Surfboard-tg-mixed | 0.643 | observe | 10 | 0.9 | 8565 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 14439 |
| dragon3 | 0.37 | observe | 5 | 0.8 | 100 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5045 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11789 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5496 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 437 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 432 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 315 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| dragon | 0.732 | 123 | 45 | 168 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| dragon3 | 0.8 | 4 | 1 | 5 |
| Surfboard-tg-mixed | 0.9 | 9 | 1 | 10 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14439 | yes | 5.05 | 0 |
| SoliSpirit-all | 11789 | yes | 2.66 | 0 |
| dragon | 10000 | yes | 8.61 | 0 |
| dragon2 | 10000 | yes | 5.36 | 0 |
| Surfboard-tg-mixed | 8565 | yes | 3.84 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.41 | 0 |
| barry-far-vless | 5914 | yes | 1.17 | 0 |
| Surfboard-tg-vless | 5496 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5045 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4482 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 42 |
| cn-block | 6 |
| 204 | 1 |
