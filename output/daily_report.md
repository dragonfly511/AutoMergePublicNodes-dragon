# AutoNodes 每日报告

生成时间：2026-11-05 07:07:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 92244 |
| 去重后节点数 | 34070 |
| TCP 可达数 | 3000 |
| 真测通过数 | 190 |
| verified 输出数 | 14 |
| global 输出数 | 191 |
| all 输出数 | 34070 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.4 |
| fetch | 6.7 |
| generate | 13.1 |
| geo | 1.6 |
| probe | 75.0 |
| real_test | 50.8 |
| tcp | 92.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 108 | 102 | 6 | 94.4% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 81 | 67 | 14 | 82.7% |
| vless | 21 | 7 | 14 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| 204:ProxyError | 11 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 3 |
| cn-block:TimeoutError | 2 |
| geo:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6453 |
| ConnectionRefusedError | 1035 |
| OSError | 231 |
| gaierror | 156 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.969 | prefer | 187 | 0.893 | 10000 |
| mheidari-all | 0.568 | observe | 8 | 0.875 | 14576 |
| Au1rxx-base64 | 0.552 | observe | 25 | 0.48 | 1751 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8675 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 351 |
| chromego_merge | 0.264 | observe | 1 | 1.0 | 228 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 400 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 395 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 144 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 131 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Au1rxx-base64 | 0.48 | 12 | 13 | 25 |
| mheidari-all | 0.875 | 7 | 1 | 8 |
| dragon | 0.893 | 167 | 20 | 187 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| chromego_merge | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14576 | yes | 3.66 | 0 |
| SoliSpirit-all | 10857 | yes | 2.0 | 0 |
| dragon | 10000 | yes | 5.95 | 0 |
| Surfboard-tg-mixed | 8675 | yes | 2.87 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.53 | 0 |
| barry-far-vless | 6243 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 6030 | yes | 3.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 2.38 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 14 |
| test_one_timeout | 14 |
| cn-block | 5 |
| geo | 1 |
| speed | 1 |
