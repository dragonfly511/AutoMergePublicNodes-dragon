# AutoNodes 每日报告

生成时间：2026-11-22 19:58:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102619 |
| 去重后节点数 | 35104 |
| TCP 可达数 | 3000 |
| 真测通过数 | 276 |
| verified 输出数 | 2 |
| global 输出数 | 278 |
| all 输出数 | 35104 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 43.7 |
| fetch | 8.9 |
| generate | 18.2 |
| geo | 1.8 |
| probe | 95.3 |
| real_test | 61.1 |
| tcp | 93.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 225 | 203 | 22 | 90.2% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 17 | 6 | 11 | 35.3% |
| vless | 106 | 54 | 52 | 50.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 49 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 12 |
| 204:ClientOSError | 4 |
| 204:TimeoutError | 4 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:TimeoutError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6706 |
| ConnectionRefusedError | 1093 |
| gaierror | 355 |
| OSError | 247 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | prefer | 192 | 0.901 | 10000 |
| dragon2 | 0.65 | observe | 149 | 0.57 | 10000 |
| dragon3 | 0.517 | observe | 7 | 1.0 | 100 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 14491 |
| ermaozi-get_subscribe | 0.413 | observe | 4 | 1.0 | 318 |
| Surfboard-tg-mixed | 0.385 | observe | 8 | 0.5 | 8739 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.275 | observe | 3 | 0.667 | 167 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5069 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2671 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 440 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 435 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 318 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 184 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 171 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.5 | 4 | 4 | 8 |
| dragon2 | 0.57 | 85 | 64 | 149 |
| tg-LonUp_M | 0.667 | 2 | 1 | 3 |
| dragon | 0.901 | 173 | 19 | 192 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 3 | 0 | 3 |
| ermaozi-get_subscribe | 1.0 | 4 | 0 | 4 |
| dragon3 | 1.0 | 7 | 0 | 7 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14491 | yes | 4.85 | 0 |
| SoliSpirit-all | 12183 | yes | 3.92 | 0 |
| dragon | 10000 | yes | 8.4 | 0 |
| dragon2 | 10000 | yes | 5.16 | 0 |
| Surfboard-tg-mixed | 8739 | yes | 3.47 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.87 | 0 |
| barry-far-vless | 5881 | yes | 1.56 | 0 |
| Surfboard-tg-vless | 5664 | yes | 3.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 5069 | yes | 1.79 | 0 |
| mahdibland-V2RayAggregator | 4512 | yes | 2.59 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 49 |
| 204 | 20 |
| cn-block | 14 |
| geo | 4 |
| speed | 1 |
