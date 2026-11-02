# AutoNodes 每日报告

生成时间：2026-11-02 21:54:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 91771 |
| 去重后节点数 | 34032 |
| TCP 可达数 | 3000 |
| 真测通过数 | 111 |
| verified 输出数 | 7 |
| global 输出数 | 112 |
| all 输出数 | 34032 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.7 |
| fetch | 8.5 |
| generate | 17.3 |
| geo | 1.5 |
| probe | 96.7 |
| real_test | 45.2 |
| tcp | 90.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 14 | 8 | 6 | 57.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 74 | 70 | 4 | 94.6% |
| vless | 26 | 16 | 10 | 61.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 3 |
| geo:ClientOSError | 3 |
| cn-block:TimeoutError | 3 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6271 |
| ConnectionRefusedError | 985 |
| OSError | 236 |
| gaierror | 164 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.981 | prefer | 89 | 0.91 | 10000 |
| Au1rxx-base64 | 0.695 | observe | 30 | 0.633 | 1751 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 8355 |
| mheidari-all | 0.401 | observe | 7 | 0.571 | 14971 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4941 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2726 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10678 |
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
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 395 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 390 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 139 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 126 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.571 | 4 | 3 | 7 |
| Au1rxx-base64 | 0.633 | 19 | 11 | 30 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| dragon | 0.91 | 81 | 8 | 89 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14971 | yes | 4.82 | 0 |
| SoliSpirit-all | 10678 | yes | 2.27 | 0 |
| dragon | 10000 | yes | 7.17 | 0 |
| Surfboard-tg-mixed | 8355 | yes | 3.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 8.04 | 0 |
| barry-far-vless | 6131 | yes | 0.55 | 0 |
| Surfboard-tg-vless | 5917 | yes | 4.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4941 | yes | 1.35 | 0 |
| mahdibland-V2RayAggregator | 4726 | yes | 3.03 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.92 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 38 to 7 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 5 |
| geo | 3 |
| cn-block | 3 |
