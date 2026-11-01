# AutoNodes 每日报告

生成时间：2026-11-01 06:32:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/108 |
| 清理建议：禁用/降权 | 13/1 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 90500 |
| 去重后节点数 | 33136 |
| TCP 可达数 | 3000 |
| 真测通过数 | 134 |
| verified 输出数 | 38 |
| global 输出数 | 136 |
| all 输出数 | 33136 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 37.1 |
| fetch | 8.6 |
| generate | 17.1 |
| geo | 1.7 |
| probe | 95.1 |
| real_test | 26.3 |
| tcp | 84.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| hysteria2 | 20 | 15 | 5 | 75.0% |
| shadowsocks | 13 | 11 | 2 | 84.6% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 80 | 76 | 4 | 95.0% |
| vless | 36 | 29 | 7 | 80.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5967 |
| ConnectionRefusedError | 981 |
| OSError | 240 |
| gaierror | 198 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.998 | prefer | 96 | 0.927 | 10000 |
| Au1rxx-base64 | 0.956 | prefer | 33 | 0.909 | 1751 |
| mheidari-all | 0.698 | observe | 13 | 0.846 | 14747 |
| Surfboard-tg-mixed | 0.4 | observe | 4 | 0.75 | 7809 |
| ermaozi-get_subscribe | 0.277 | observe | 1 | 1.0 | 558 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10495 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.153 | downweight | 5 | 0.0 | 0 | 6752 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 391 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 386 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 135 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 122 | 连续死亡次数 >= 2 |
| downweight | xiaoji235-airport-v2ray-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 5 | 5 |
| Surfboard-tg-mixed | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.846 | 11 | 2 | 13 |
| Au1rxx-base64 | 0.909 | 30 | 3 | 33 |
| dragon | 0.927 | 89 | 7 | 96 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14747 | yes | 4.15 | 0 |
| SoliSpirit-all | 10495 | yes | 2.13 | 0 |
| dragon | 10000 | yes | 7.92 | 0 |
| Surfboard-tg-mixed | 7809 | yes | 4.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.04 | 0 |
| barry-far-vless | 5805 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 5637 | yes | 3.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4680 | yes | 3.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 3 |
| cn-block | 3 |
| geo | 2 |
