# AutoNodes 每日报告

生成时间：2026-11-17 21:11:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 102368 |
| 去重后节点数 | 35031 |
| TCP 可达数 | 3000 |
| 真测通过数 | 214 |
| verified 输出数 | 19 |
| global 输出数 | 215 |
| all 输出数 | 35031 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.0 |
| fetch | 9.0 |
| generate | 18.3 |
| geo | 1.6 |
| probe | 95.1 |
| real_test | 38.9 |
| tcp | 91.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 188 | 175 | 13 | 93.1% |
| vless | 34 | 28 | 6 | 82.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 2 |
| 204:TimeoutError | 2 |
| cn-block:TimeoutError | 2 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6662 |
| ConnectionRefusedError | 976 |
| OSError | 243 |
| gaierror | 199 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.992 | prefer | 203 | 0.916 | 10000 |
| dragon2 | 0.749 | prefer | 13 | 0.923 | 10000 |
| Surfboard-tg-mixed | 0.48 | observe | 4 | 1.0 | 8416 |
| tg-LonUp_M | 0.456 | observe | 7 | 0.857 | 171 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 14572 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| dragon3 | 0.324 | observe | 4 | 0.75 | 100 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4928 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2790 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 430 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 425 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 308 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 161 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.75 | 3 | 1 | 4 |
| tg-LonUp_M | 0.857 | 6 | 1 | 7 |
| dragon | 0.916 | 186 | 17 | 203 |
| dragon2 | 0.923 | 12 | 1 | 13 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14572 | yes | 5.27 | 0 |
| SoliSpirit-all | 11534 | yes | 3.74 | 0 |
| dragon | 10000 | yes | 8.26 | 0 |
| dragon2 | 10000 | yes | 5.81 | 0 |
| Surfboard-tg-mixed | 8416 | yes | 5.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.9 | 0 |
| barry-far-vless | 6032 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 5789 | yes | 3.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 4928 | yes | 2.13 | 0 |
| mahdibland-V2RayAggregator | 4601 | yes | 3.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 4 |
| cn-block | 3 |
| geo | 1 |
