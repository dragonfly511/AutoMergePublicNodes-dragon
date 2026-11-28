# AutoNodes 每日报告

生成时间：2026-11-28 08:10:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 97827 |
| 去重后节点数 | 32967 |
| TCP 可达数 | 3000 |
| 真测通过数 | 124 |
| verified 输出数 | 24 |
| global 输出数 | 254 |
| all 输出数 | 32967 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.5 |
| fetch | 5.7 |
| generate | 10.4 |
| geo | 1.0 |
| probe | 65.6 |
| real_test | 29.3 |
| tcp | 74.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 111 | 106 | 5 | 95.5% |
| socks | 8 | 8 | 0 | 100.0% |
| trojan | 6 | 4 | 2 | 66.7% |
| vless | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 5 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6222 |
| ConnectionRefusedError | 1032 |
| gaierror | 492 |
| OSError | 403 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 106 | 0.962 | 10000 |
| Surfboard-tg-mixed | 0.629 | observe | 8 | 1.0 | 8437 |
| tg-LonUp_M | 0.625 | observe | 10 | 1.0 | 157 |
| dragon2 | 0.606 | observe | 9 | 0.889 | 9895 |
| dragon3 | 0.324 | observe | 4 | 0.75 | 100 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 357 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11621 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5299 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ShadowsocksM | 0.175 | observe | 0 | None | 0 | 4 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 451 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 446 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 329 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 182 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 2 | 2 |
| dragon3 | 0.75 | 3 | 1 | 4 |
| dragon2 | 0.889 | 8 | 1 | 9 |
| dragon | 0.962 | 102 | 4 | 106 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 8 | 0 | 8 |
| tg-LonUp_M | 1.0 | 10 | 0 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14211 | yes | 3.9 | 0 |
| SoliSpirit-all | 11621 | yes | 2.08 | 0 |
| dragon | 10000 | yes | 5.06 | 0 |
| dragon2 | 9895 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 8437 | yes | 3.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.66 | 0 |
| barry-far-vless | 5482 | yes | 0.81 | 0 |
| Surfboard-tg-vless | 5299 | yes | 2.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4895 | yes | 0.95 | 0 |
| mahdibland-V2RayAggregator | 4526 | yes | 1.35 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 251 to 124 |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 5 |
| cn-block | 2 |
| geo | 1 |
