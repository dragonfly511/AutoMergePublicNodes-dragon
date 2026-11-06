# AutoNodes 每日报告

生成时间：2026-11-06 18:35:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/109 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/95 |
| 原始节点数 | 102557 |
| 去重后节点数 | 34617 |
| TCP 可达数 | 3000 |
| 真测通过数 | 79 |
| verified 输出数 | 4 |
| global 输出数 | 82 |
| all 输出数 | 34617 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.4 |
| fetch | 9.2 |
| generate | 17.9 |
| geo | 1.5 |
| probe | 91.3 |
| real_test | 34.9 |
| tcp | 89.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 46 | 39 | 7 | 84.8% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 47 | 26 | 21 | 55.3% |
| vless | 3 | 2 | 1 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 9 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 3 |
| cn-block:TimeoutError | 2 |
| geo:ProxyError | 1 |
| 204:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6932 |
| ConnectionRefusedError | 1080 |
| OSError | 234 |
| gaierror | 132 |
| ConnectionResetError | 2 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.905 | prefer | 38 | 0.842 | 10000 |
| dragon | 0.697 | observe | 58 | 0.621 | 10000 |
| mheidari-all | 0.507 | observe | 8 | 0.75 | 14184 |
| Surfboard-tg-mixed | 0.352 | observe | 6 | 0.5 | 8758 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10962 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 403 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 398 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 147 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 134 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.5 | 3 | 3 | 6 |
| dragon | 0.621 | 36 | 22 | 58 |
| mheidari-all | 0.75 | 6 | 2 | 8 |
| dragon2 | 0.842 | 32 | 6 | 38 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14184 | yes | 6.33 | 0 |
| SoliSpirit-all | 10962 | yes | 4.48 | 0 |
| dragon | 10000 | yes | 8.36 | 0 |
| dragon2 | 10000 | yes | 3.56 | 0 |
| Surfboard-tg-mixed | 8758 | yes | 5.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.9 | 0 |
| barry-far-vless | 6479 | yes | 2.84 | 0 |
| Surfboard-tg-vless | 6135 | yes | 4.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 2.72 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 3.23 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 10 |
| cn-block | 6 |
| speed | 4 |
| geo | 1 |
