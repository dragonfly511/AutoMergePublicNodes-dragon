# AutoNodes 每日报告

生成时间：2026-11-14 22:41:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 102956 |
| 去重后节点数 | 34505 |
| TCP 可达数 | 3000 |
| 真测通过数 | 206 |
| verified 输出数 | 13 |
| global 输出数 | 206 |
| all 输出数 | 34505 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.4 |
| fetch | 7.7 |
| generate | 14.9 |
| geo | 1.6 |
| probe | 86.8 |
| real_test | 26.9 |
| tcp | 89.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 120 | 117 | 3 | 97.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 72 | 70 | 2 | 97.2% |
| vless | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 7 |
| 204:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6640 |
| ConnectionRefusedError | 994 |
| OSError | 238 |
| gaierror | 222 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 191 | 0.974 | 10000 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 13757 |
| dragon2 | 0.465 | observe | 7 | 0.714 | 10000 |
| dragon3 | 0.443 | observe | 5 | 1.0 | 100 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11640 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6319 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 424 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 419 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| dragon2 | 0.714 | 5 | 2 | 7 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| dragon | 0.974 | 186 | 5 | 191 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13757 | yes | 4.77 | 0 |
| SoliSpirit-all | 11640 | yes | 1.11 | 0 |
| dragon | 10000 | yes | 7.04 | 0 |
| dragon2 | 10000 | yes | 3.78 | 0 |
| Surfboard-tg-mixed | 9013 | yes | 3.15 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.0 | 0 |
| barry-far-vless | 6499 | yes | 1.82 | 0 |
| Surfboard-tg-vless | 6319 | yes | 2.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 1.62 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 1.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 7 |
| 204 | 1 |
| cn-block | 1 |
| speed | 1 |
