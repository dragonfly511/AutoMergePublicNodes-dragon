# AutoNodes 每日报告

生成时间：2026-11-18 20:48:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102775 |
| 去重后节点数 | 35212 |
| TCP 可达数 | 3000 |
| 真测通过数 | 153 |
| verified 输出数 | 13 |
| global 输出数 | 154 |
| all 输出数 | 35212 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.1 |
| fetch | 9.2 |
| generate | 18.7 |
| geo | 1.6 |
| probe | 100.0 |
| real_test | 41.7 |
| tcp | 90.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 140 | 128 | 12 | 91.4% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 24 | 16 | 8 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| cn-block:ClientOSError | 2 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6540 |
| ConnectionRefusedError | 1006 |
| gaierror | 284 |
| OSError | 242 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.99 | prefer | 153 | 0.915 | 10000 |
| Surfboard-tg-mixed | 0.556 | observe | 12 | 0.667 | 8521 |
| dragon3 | 0.398 | observe | 10 | 0.6 | 100 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11959 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5794 |
| barry-far-vless | 0.255 | observe | 0 | None | 5945 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 432 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 427 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 310 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 163 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.6 | 6 | 4 | 10 |
| Surfboard-tg-mixed | 0.667 | 8 | 4 | 12 |
| dragon | 0.915 | 140 | 13 | 153 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14408 | yes | 6.07 | 0 |
| SoliSpirit-all | 11959 | yes | 4.27 | 0 |
| dragon | 10000 | yes | 8.67 | 0 |
| dragon2 | 10000 | yes | 4.8 | 0 |
| Surfboard-tg-mixed | 8521 | yes | 3.53 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.35 | 0 |
| barry-far-vless | 5945 | yes | 1.91 | 0 |
| Surfboard-tg-vless | 5794 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4458 | yes | 1.74 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 27 to 13 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 15 |
| cn-block | 3 |
| 204 | 3 |
