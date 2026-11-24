# AutoNodes 每日报告

生成时间：2026-11-24 22:42:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 98281 |
| 去重后节点数 | 33853 |
| TCP 可达数 | 3000 |
| 真测通过数 | 68 |
| verified 输出数 | 18 |
| global 输出数 | 269 |
| all 输出数 | 33853 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.9 |
| fetch | 8.7 |
| generate | 17.9 |
| geo | 1.6 |
| probe | 99.2 |
| real_test | 35.9 |
| tcp | 88.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 2 | 2 | 50.0% |
| hysteria2 | 8 | 8 | 0 | 100.0% |
| shadowsocks | 34 | 29 | 5 | 85.3% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 44 | 28 | 16 | 63.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6914 |
| ConnectionRefusedError | 1118 |
| OSError | 274 |
| gaierror | 251 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.858 | prefer | 70 | 0.786 | 10000 |
| Surfboard-tg-mixed | 0.421 | observe | 6 | 0.667 | 8239 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 14970 |
| dragon3 | 0.389 | observe | 7 | 0.714 | 100 |
| ermaozi | 0.27 | observe | 1 | 1.0 | 366 |
| dragon2 | 0.259 | observe | 3 | 0.333 | 9953 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11536 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5468 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 444 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 439 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 322 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 188 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon2 | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.667 | 4 | 2 | 6 |
| dragon3 | 0.714 | 5 | 2 | 7 |
| dragon | 0.786 | 55 | 15 | 70 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14970 | yes | 4.86 | 0 |
| SoliSpirit-all | 11536 | yes | 3.15 | 0 |
| dragon | 10000 | yes | 8.09 | 0 |
| dragon2 | 9953 | yes | 5.13 | 0 |
| Surfboard-tg-mixed | 8239 | yes | 4.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.35 | 0 |
| barry-far-vless | 5508 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 5468 | yes | 3.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.57 | 0 |
| mahdibland-V2RayAggregator | 4546 | yes | 3.02 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 7 |
| cn-block | 4 |
