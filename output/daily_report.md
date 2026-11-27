# AutoNodes 每日报告

生成时间：2026-11-27 21:33:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 98609 |
| 去重后节点数 | 33554 |
| TCP 可达数 | 3000 |
| 真测通过数 | 251 |
| verified 输出数 | 24 |
| global 输出数 | 254 |
| all 输出数 | 33554 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.0 |
| fetch | 6.6 |
| generate | 13.1 |
| geo | 1.8 |
| probe | 82.4 |
| real_test | 53.2 |
| tcp | 87.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 276 | 225 | 51 | 81.5% |
| socks | 12 | 10 | 2 | 83.3% |
| trojan | 4 | 4 | 0 | 100.0% |
| vless | 11 | 9 | 2 | 81.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 36 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7094 |
| ConnectionRefusedError | 1042 |
| OSError | 260 |
| gaierror | 245 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | prefer | 274 | 0.821 | 10000 |
| dragon3 | 0.657 | observe | 11 | 1.0 | 100 |
| tg-LonUp_M | 0.591 | observe | 9 | 1.0 | 174 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 8496 |
| dragon2 | 0.446 | observe | 8 | 0.625 | 9931 |
| ermaozi | 0.385 | observe | 5 | 0.8 | 466 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 14418 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11762 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 450 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 445 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 328 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| dragon2 | 0.625 | 5 | 3 | 8 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| ermaozi | 0.8 | 4 | 1 | 5 |
| dragon | 0.821 | 225 | 49 | 274 |
| tg-LonUp_M | 1.0 | 9 | 0 | 9 |
| dragon3 | 1.0 | 11 | 0 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14418 | yes | 4.6 | 0 |
| SoliSpirit-all | 11762 | yes | 1.81 | 0 |
| dragon | 10000 | yes | 5.9 | 0 |
| dragon2 | 9931 | yes | 3.17 | 0 |
| Surfboard-tg-mixed | 8496 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.96 | 0 |
| barry-far-vless | 5607 | yes | 0.85 | 0 |
| Surfboard-tg-vless | 5391 | yes | 2.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4895 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 4459 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 36 |
| speed | 10 |
| cn-block | 7 |
| 204 | 2 |
| geo | 1 |
