# AutoNodes 每日报告

生成时间：2026-10-31 10:15:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 3/92 |
| 原始节点数 | 91128 |
| 去重后节点数 | 33558 |
| TCP 可达数 | 3000 |
| 真测通过数 | 185 |
| verified 输出数 | 55 |
| global 输出数 | 187 |
| all 输出数 | 33558 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.4 |
| fetch | 5.1 |
| generate | 11.0 |
| geo | 1.4 |
| probe | 75.9 |
| real_test | 49.3 |
| tcp | 92.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 11 | 3 | 78.6% |
| shadowsocks | 108 | 92 | 16 | 85.2% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 72 | 57 | 15 | 79.2% |
| vless | 57 | 25 | 32 | 43.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 34 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 3 |
| speed:ClientOSError | 1 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6202 |
| ConnectionRefusedError | 978 |
| OSError | 251 |
| gaierror | 150 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.911 | prefer | 146 | 0.836 | 10000 |
| mheidari-all | 0.843 | prefer | 36 | 0.778 | 14723 |
| Au1rxx-base64 | 0.729 | prefer | 42 | 0.667 | 1751 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 2848 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi | 0.28 | observe | 1 | 1.0 | 622 |
| Surfboard-tg-mixed | 0.262 | observe | 20 | 0.15 | 7861 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10586 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 497 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 388 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 383 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 132 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.15 | 3 | 17 | 20 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| Au1rxx-base64 | 0.667 | 28 | 14 | 42 |
| mheidari-all | 0.778 | 28 | 8 | 36 |
| dragon | 0.836 | 122 | 24 | 146 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14723 | yes | 2.98 | 0 |
| SoliSpirit-all | 10586 | yes | 3.01 | 0 |
| dragon | 10000 | yes | 4.05 | 0 |
| Surfboard-tg-mixed | 7861 | yes | 2.75 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.75 | 0 |
| barry-far-vless | 5895 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 5698 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 0.43 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.72 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.29 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 34 |
| geo | 16 |
| 204 | 11 |
| cn-block | 3 |
| speed | 2 |
