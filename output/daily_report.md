# AutoNodes 每日报告

生成时间：2026-11-22 07:11:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 103594 |
| 去重后节点数 | 34972 |
| TCP 可达数 | 3000 |
| 真测通过数 | 46 |
| verified 输出数 | 4 |
| global 输出数 | 47 |
| all 输出数 | 34972 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 16.9 |
| fetch | 5.7 |
| generate | 11.0 |
| geo | 1.4 |
| probe | 68.3 |
| real_test | 25.2 |
| tcp | 75.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 18 | 14 | 4 | 77.8% |
| socks | 7 | 6 | 1 | 85.7% |
| vless | 40 | 19 | 21 | 47.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5563 |
| ConnectionRefusedError | 1102 |
| gaierror | 476 |
| OSError | 364 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.757 | prefer | 16 | 0.812 | 10000 |
| dragon | 0.609 | observe | 49 | 0.531 | 10000 |
| Surfboard-tg-mixed | 0.519 | observe | 5 | 1.0 | 8778 |
| mheidari-all | 0.48 | observe | 4 | 1.0 | 14453 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.282 | observe | 3 | 0.667 | 327 |
| zhangkai | 0.256 | observe | 1 | 1.0 | 27 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5030 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2989 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| dragon3 | 0.108 | observe | 2 | 0.0 | 0 | 100 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 439 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 434 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 317 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 183 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.0 | 0 | 2 | 2 |
| dragon | 0.531 | 26 | 23 | 49 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| dragon2 | 0.812 | 13 | 3 | 16 |
| zhangkai | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 4 | 0 | 4 |
| Surfboard-tg-mixed | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14453 | yes | 3.64 | 0 |
| SoliSpirit-all | 12093 | yes | 2.5 | 0 |
| dragon | 10000 | yes | 5.34 | 0 |
| dragon2 | 10000 | yes | 2.79 | 0 |
| Surfboard-tg-mixed | 8778 | yes | 2.17 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.83 | 0 |
| barry-far-vless | 6124 | yes | 0.84 | 0 |
| Surfboard-tg-vless | 5942 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 5030 | yes | 0.99 | 0 |
| mahdibland-V2RayAggregator | 4512 | yes | 1.02 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 5 |
| cn-block | 3 |
| geo | 1 |
