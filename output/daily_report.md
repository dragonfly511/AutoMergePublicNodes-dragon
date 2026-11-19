# AutoNodes 每日报告

生成时间：2026-11-19 07:45:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102303 |
| 去重后节点数 | 35242 |
| TCP 可达数 | 3000 |
| 真测通过数 | 189 |
| verified 输出数 | 11 |
| global 输出数 | 190 |
| all 输出数 | 35242 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.1 |
| fetch | 9.1 |
| generate | 17.8 |
| geo | 1.5 |
| probe | 86.8 |
| real_test | 33.6 |
| tcp | 96.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 151 | 149 | 2 | 98.7% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 38 | 26 | 12 | 68.4% |
| vless | 15 | 4 | 11 | 26.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 8 |
| cn-block:ProxyError | 3 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7117 |
| ConnectionRefusedError | 1029 |
| OSError | 237 |
| gaierror | 157 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.995 | prefer | 186 | 0.919 | 10000 |
| mheidari-all | 0.519 | observe | 5 | 1.0 | 14200 |
| dragon3 | 0.511 | observe | 19 | 0.526 | 100 |
| dragon2 | 0.335 | observe | 1 | 1.0 | 10000 |
| ermaozi | 0.331 | observe | 2 | 1.0 | 494 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 8472 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 168 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2925 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 433 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 428 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 311 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 177 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 164 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| dragon3 | 0.526 | 10 | 9 | 19 |
| dragon | 0.919 | 171 | 15 | 186 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| dragon2 | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |
| mheidari-all | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14200 | yes | 5.79 | 0 |
| SoliSpirit-all | 11797 | yes | 5.8 | 0 |
| dragon | 10000 | yes | 7.78 | 0 |
| dragon2 | 10000 | yes | 5.34 | 0 |
| Surfboard-tg-mixed | 8472 | yes | 3.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.45 | 0 |
| barry-far-vless | 5975 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 5689 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.02 | 0 |
| mahdibland-V2RayAggregator | 4507 | yes | 1.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 10 |
| cn-block | 4 |
| speed | 1 |
