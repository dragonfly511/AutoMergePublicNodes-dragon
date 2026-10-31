# AutoNodes 每日报告

生成时间：2026-10-31 21:49:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/93 |
| 原始节点数 | 90795 |
| 去重后节点数 | 33147 |
| TCP 可达数 | 3000 |
| 真测通过数 | 224 |
| verified 输出数 | 32 |
| global 输出数 | 228 |
| all 输出数 | 33147 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.6 |
| fetch | 8.7 |
| generate | 17.3 |
| geo | 1.5 |
| probe | 90.7 |
| real_test | 45.1 |
| tcp | 83.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 155 | 143 | 12 | 92.3% |
| trojan | 49 | 49 | 0 | 100.0% |
| vless | 23 | 15 | 8 | 65.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5801 |
| ConnectionRefusedError | 953 |
| OSError | 236 |
| gaierror | 198 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 202 | 0.936 | 10000 |
| Au1rxx-base64 | 0.864 | prefer | 32 | 0.812 | 1751 |
| mheidari-all | 0.446 | observe | 5 | 0.8 | 14850 |
| Surfboard-tg-mixed | 0.421 | observe | 6 | 0.667 | 7936 |
| peasoft-NoMoreWalls | 0.264 | observe | 1 | 1.0 | 227 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10505 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5636 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 499 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 390 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 385 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 134 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.667 | 4 | 2 | 6 |
| mheidari-all | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.812 | 26 | 6 | 32 |
| dragon | 0.936 | 189 | 13 | 202 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14850 | yes | 5.1 | 0 |
| SoliSpirit-all | 10505 | yes | 6.77 | 0 |
| dragon | 10000 | yes | 7.68 | 0 |
| Surfboard-tg-mixed | 7936 | yes | 4.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.44 | 0 |
| barry-far-vless | 5849 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 5636 | yes | 4.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 2.96 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.36 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.3 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| 204 | 6 |
| cn-block | 5 |
| geo | 1 |
| speed | 1 |
