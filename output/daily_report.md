# AutoNodes 每日报告

生成时间：2026-11-13 19:58:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 103409 |
| 去重后节点数 | 34464 |
| TCP 可达数 | 3000 |
| 真测通过数 | 245 |
| verified 输出数 | 15 |
| global 输出数 | 246 |
| all 输出数 | 34464 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.6 |
| fetch | 7.3 |
| generate | 14.3 |
| geo | 1.5 |
| probe | 84.3 |
| real_test | 39.6 |
| tcp | 91.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 189 | 172 | 17 | 91.0% |
| socks | 1 | 1 | 0 | 100.0% |
| vless | 83 | 58 | 25 | 69.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 31 |
| 204:ProxyError | 4 |
| speed:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| cn-block:TimeoutError | 1 |
| geo:TimeoutError | 1 |
| speed:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6676 |
| ConnectionRefusedError | 984 |
| OSError | 250 |
| gaierror | 203 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | prefer | 271 | 0.849 | 10000 |
| dragon2 | 0.48 | observe | 4 | 1.0 | 10000 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 14267 |
| dragon3 | 0.413 | observe | 6 | 0.833 | 100 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| tg-LonUp_M | 0.276 | observe | 3 | 0.667 | 175 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4900 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11528 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.145 | observe | 1 | 0.0 | 0 | 442 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 421 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 416 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 165 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 152 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.667 | 2 | 1 | 3 |
| dragon3 | 0.833 | 5 | 1 | 6 |
| dragon | 0.849 | 230 | 41 | 271 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| mheidari-all | 1.0 | 3 | 0 | 3 |
| dragon2 | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14267 | yes | 4.65 | 0 |
| SoliSpirit-all | 11528 | yes | 3.65 | 0 |
| dragon | 10000 | yes | 6.97 | 0 |
| dragon2 | 10000 | yes | 4.97 | 0 |
| Surfboard-tg-mixed | 8804 | yes | 3.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.18 | 0 |
| barry-far-vless | 6409 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 6228 | yes | 2.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4900 | yes | 1.58 | 0 |
| mahdibland-V2RayAggregator | 4624 | yes | 2.14 | 0 |

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
| test_one_timeout | 31 |
| speed | 6 |
| 204 | 5 |
| cn-block | 1 |
| geo | 1 |
