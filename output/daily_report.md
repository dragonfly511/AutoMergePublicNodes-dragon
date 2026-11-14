# AutoNodes 每日报告

生成时间：2026-11-14 18:24:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 3/88 |
| 原始节点数 | 103418 |
| 去重后节点数 | 34645 |
| TCP 可达数 | 3000 |
| 真测通过数 | 280 |
| verified 输出数 | 18 |
| global 输出数 | 282 |
| all 输出数 | 34645 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.2 |
| fetch | 9.2 |
| generate | 18.1 |
| geo | 1.5 |
| probe | 87.6 |
| real_test | 45.5 |
| tcp | 85.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 194 | 177 | 17 | 91.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 6 | 5 | 1 | 83.3% |
| vless | 124 | 80 | 44 | 64.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 43 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6317 |
| ConnectionRefusedError | 1008 |
| gaierror | 277 |
| OSError | 243 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.993 | prefer | 21 | 0.952 | 10000 |
| dragon3 | 0.942 | prefer | 30 | 0.967 | 100 |
| dragon2 | 0.868 | prefer | 286 | 0.79 | 10000 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 14109 |
| Surfboard-tg-mixed | 0.349 | observe | 3 | 0.667 | 8883 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 179 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.144 | observe | 1 | 0.0 | 0 | 405 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 423 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 418 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| dragon2 | 0.79 | 226 | 60 | 286 |
| dragon | 0.952 | 20 | 1 | 21 |
| dragon3 | 0.967 | 29 | 1 | 30 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14109 | yes | 5.34 | 0 |
| SoliSpirit-all | 11700 | yes | 3.67 | 0 |
| dragon | 10000 | yes | 8.48 | 0 |
| dragon2 | 10000 | yes | 4.88 | 0 |
| Surfboard-tg-mixed | 8883 | yes | 3.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.26 | 0 |
| barry-far-vless | 6457 | yes | 2.02 | 0 |
| Surfboard-tg-vless | 6276 | yes | 3.61 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 1.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 43 |
| 204 | 17 |
| cn-block | 3 |
| speed | 1 |
| geo | 1 |
