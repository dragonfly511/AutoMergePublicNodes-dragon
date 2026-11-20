# AutoNodes 每日报告

生成时间：2026-11-20 07:36:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102563 |
| 去重后节点数 | 35640 |
| TCP 可达数 | 3000 |
| 真测通过数 | 196 |
| verified 输出数 | 8 |
| global 输出数 | 206 |
| all 输出数 | 35640 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 6.1 |
| generate | 10.7 |
| geo | 1.4 |
| probe | 72.1 |
| real_test | 70.1 |
| tcp | 88.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 12 | 8 | 4 | 66.7% |
| shadowsocks | 117 | 95 | 22 | 81.2% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 8 | 6 | 2 | 75.0% |
| vless | 180 | 87 | 93 | 48.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 70 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 10 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 6 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6396 |
| ConnectionRefusedError | 1027 |
| gaierror | 366 |
| OSError | 359 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.888 | prefer | 24 | 0.833 | 10000 |
| dragon2 | 0.681 | observe | 271 | 0.601 | 10000 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 8500 |
| dragon3 | 0.457 | observe | 14 | 0.571 | 100 |
| mheidari-all | 0.373 | observe | 5 | 0.6 | 14360 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4935 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2728 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11813 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5726 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 435 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 430 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 313 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.571 | 8 | 6 | 14 |
| mheidari-all | 0.6 | 3 | 2 | 5 |
| dragon2 | 0.601 | 163 | 108 | 271 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| dragon | 0.833 | 20 | 4 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14360 | yes | 4.11 | 0 |
| SoliSpirit-all | 11813 | yes | 3.05 | 0 |
| dragon | 10000 | yes | 5.47 | 0 |
| dragon2 | 10000 | yes | 3.5 | 0 |
| Surfboard-tg-mixed | 8500 | yes | 2.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.48 | 0 |
| barry-far-vless | 6117 | yes | 1.58 | 0 |
| Surfboard-tg-vless | 5726 | yes | 2.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4935 | yes | 1.45 | 0 |
| mahdibland-V2RayAggregator | 4501 | yes | 1.01 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 70 |
| 204 | 26 |
| cn-block | 22 |
| geo | 2 |
| speed | 2 |
