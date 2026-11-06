# AutoNodes 每日报告

生成时间：2026-11-06 07:06:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 4/91 |
| 原始节点数 | 92780 |
| 去重后节点数 | 34555 |
| TCP 可达数 | 3000 |
| 真测通过数 | 108 |
| verified 输出数 | 6 |
| global 输出数 | 108 |
| all 输出数 | 34555 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.5 |
| fetch | 6.2 |
| generate | 12.2 |
| geo | 1.6 |
| probe | 74.0 |
| real_test | 31.7 |
| tcp | 90.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 45 | 45 | 0 | 100.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 67 | 47 | 20 | 70.1% |
| vless | 10 | 4 | 6 | 40.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 16 |
| test_one_timeout:15.0s | 5 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 3 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6790 |
| ConnectionRefusedError | 1065 |
| OSError | 230 |
| gaierror | 145 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.876 | prefer | 29 | 0.828 | 1751 |
| dragon | 0.818 | prefer | 78 | 0.744 | 10000 |
| mheidari-all | 0.805 | prefer | 16 | 0.875 | 14233 |
| Surfboard-tg-mixed | 0.734 | prefer | 14 | 0.857 | 8762 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10891 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi | 0.153 | observe | 1 | 0.0 | 0 | 639 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 402 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 397 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 146 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 133 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.0 | 0 | 1 | 1 |
| dragon | 0.744 | 58 | 20 | 78 |
| Au1rxx-base64 | 0.828 | 24 | 5 | 29 |
| Surfboard-tg-mixed | 0.857 | 12 | 2 | 14 |
| mheidari-all | 0.875 | 14 | 2 | 16 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14233 | yes | 2.76 | 0 |
| SoliSpirit-all | 10891 | yes | 3.46 | 0 |
| dragon | 10000 | yes | 5.21 | 0 |
| Surfboard-tg-mixed | 8762 | yes | 3.3 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.87 | 0 |
| barry-far-vless | 6478 | yes | 1.09 | 0 |
| Surfboard-tg-vless | 6268 | yes | 2.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 0.93 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 2.08 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 17 |
| test_one_timeout | 5 |
| cn-block | 4 |
| speed | 3 |
| geo | 1 |
