# AutoNodes 每日报告

生成时间：2026-11-03 19:43:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 93456 |
| 去重后节点数 | 34229 |
| TCP 可达数 | 3000 |
| 真测通过数 | 173 |
| verified 输出数 | 11 |
| global 输出数 | 174 |
| all 输出数 | 34229 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.6 |
| fetch | 4.8 |
| generate | 10.6 |
| geo | 1.4 |
| probe | 71.4 |
| real_test | 38.8 |
| tcp | 97.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 128 | 118 | 10 | 92.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 50 | 34 | 16 | 68.0% |
| vless | 8 | 4 | 4 | 50.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| 204:TimeoutError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6795 |
| ConnectionRefusedError | 987 |
| OSError | 234 |
| gaierror | 135 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.939 | prefer | 190 | 0.863 | 10000 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 6752 |
| Au1rxx-base64 | 0.42 | observe | 9 | 0.556 | 1751 |
| Surfboard-tg-mixed | 0.259 | observe | 3 | 0.333 | 8613 |
| mheidari-all | 0.259 | observe | 3 | 0.333 | 15211 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5017 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10863 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6089 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 397 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 392 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 141 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 128 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.333 | 1 | 2 | 3 |
| Au1rxx-base64 | 0.556 | 5 | 4 | 9 |
| dragon | 0.863 | 164 | 26 | 190 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15211 | yes | 2.91 | 0 |
| SoliSpirit-all | 10863 | yes | 1.66 | 0 |
| dragon | 10000 | yes | 4.33 | 0 |
| Surfboard-tg-mixed | 8613 | yes | 2.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.16 | 0 |
| barry-far-vless | 6302 | yes | 0.27 | 0 |
| Surfboard-tg-vless | 6089 | yes | 1.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5017 | yes | 0.71 | 0 |
| mahdibland-V2RayAggregator | 4753 | yes | 1.62 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 17 |
| test_one_timeout | 13 |
| cn-block | 3 |
| geo | 1 |
