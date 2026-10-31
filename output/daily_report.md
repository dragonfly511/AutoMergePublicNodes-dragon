# AutoNodes 每日报告

生成时间：2026-10-31 09:46:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 3/92 |
| 原始节点数 | 91126 |
| 去重后节点数 | 33552 |
| TCP 可达数 | 3000 |
| 真测通过数 | 258 |
| verified 输出数 | 96 |
| global 输出数 | 260 |
| all 输出数 | 33552 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.6 |
| fetch | 9.0 |
| generate | 17.2 |
| geo | 1.6 |
| probe | 101.2 |
| real_test | 69.8 |
| tcp | 92.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 94 | 92 | 2 | 97.9% |
| hysteria2 | 15 | 11 | 4 | 73.3% |
| shadowsocks | 50 | 45 | 5 | 90.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 34 | 27 | 7 | 79.4% |
| vless | 177 | 83 | 94 | 46.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 46 |
| geo:ClientOSError | 45 |
| 204:TimeoutError | 7 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:TimeoutError | 3 |
| speed:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6114 |
| ConnectionRefusedError | 997 |
| OSError | 253 |
| gaierror | 222 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 94 | 0.989 | 622 |
| Au1rxx-base64 | 0.82 | prefer | 46 | 0.761 | 1751 |
| mheidari-all | 0.707 | prefer | 108 | 0.63 | 14723 |
| dragon | 0.671 | observe | 15 | 0.733 | 10000 |
| DeltaKronecker-all | 0.612 | observe | 16 | 0.625 | 2848 |
| Surfboard-tg-mixed | 0.547 | observe | 88 | 0.466 | 7861 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10575 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.132 | observe | 1 | 0.0 | 0 | 108 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 496 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 387 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 382 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 131 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.466 | 41 | 47 | 88 |
| DeltaKronecker-all | 0.625 | 10 | 6 | 16 |
| mheidari-all | 0.63 | 68 | 40 | 108 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| dragon | 0.733 | 11 | 4 | 15 |
| Au1rxx-base64 | 0.761 | 35 | 11 | 46 |
| ermaozi | 0.989 | 93 | 1 | 94 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14723 | yes | 6.23 | 0 |
| SoliSpirit-all | 10575 | yes | 2.6 | 0 |
| dragon | 10000 | yes | 8.13 | 0 |
| Surfboard-tg-mixed | 7861 | yes | 3.94 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.02 | 0 |
| barry-far-vless | 5895 | yes | 0.56 | 0 |
| Surfboard-tg-vless | 5698 | yes | 4.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 1.09 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 3.22 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 46 |
| geo | 45 |
| 204 | 15 |
| cn-block | 4 |
| speed | 2 |
