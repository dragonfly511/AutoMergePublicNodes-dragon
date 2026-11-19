# AutoNodes 每日报告

生成时间：2026-11-19 20:54:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 103275 |
| 去重后节点数 | 35550 |
| TCP 可达数 | 3000 |
| 真测通过数 | 163 |
| verified 输出数 | 13 |
| global 输出数 | 172 |
| all 输出数 | 35550 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.9 |
| fetch | 6.6 |
| generate | 14.0 |
| geo | 1.5 |
| probe | 77.2 |
| real_test | 51.7 |
| tcp | 93.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 192 | 142 | 50 | 74.0% |
| socks | 6 | 6 | 0 | 100.0% |
| trojan | 17 | 6 | 11 | 35.3% |
| vless | 7 | 6 | 1 | 85.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 39 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 7 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6792 |
| ConnectionRefusedError | 1066 |
| OSError | 237 |
| gaierror | 211 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.989 | prefer | 20 | 0.95 | 10000 |
| dragon3 | 0.871 | prefer | 28 | 0.893 | 100 |
| dragon | 0.739 | prefer | 168 | 0.661 | 10000 |
| Surfboard-tg-mixed | 0.547 | observe | 9 | 0.778 | 8602 |
| tg-LonUp_M | 0.407 | observe | 4 | 1.0 | 179 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 14706 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4935 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2728 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 434 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 429 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 312 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 165 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.661 | 111 | 57 | 168 |
| Surfboard-tg-mixed | 0.778 | 7 | 2 | 9 |
| dragon3 | 0.893 | 25 | 3 | 28 |
| dragon2 | 0.95 | 19 | 1 | 20 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |
| tg-LonUp_M | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14706 | yes | 5.96 | 0 |
| SoliSpirit-all | 12076 | yes | 3.99 | 0 |
| dragon | 10000 | yes | 4.87 | 0 |
| dragon2 | 10000 | yes | 5.17 | 0 |
| Surfboard-tg-mixed | 8602 | yes | 3.07 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 5937 | yes | 2.45 | 0 |
| barry-far-vless | 5868 | yes | 1.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4935 | yes | 1.11 | 0 |
| mahdibland-V2RayAggregator | 4507 | yes | 1.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 39 |
| cn-block | 13 |
| 204 | 8 |
| geo | 2 |
| speed | 1 |
