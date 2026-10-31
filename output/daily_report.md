# AutoNodes 每日报告

生成时间：2026-10-31 06:21:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 3/92 |
| 原始节点数 | 90738 |
| 去重后节点数 | 33665 |
| TCP 可达数 | 3000 |
| 真测通过数 | 202 |
| verified 输出数 | 50 |
| global 输出数 | 203 |
| all 输出数 | 33665 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.3 |
| fetch | 5.5 |
| generate | 10.2 |
| geo | 1.2 |
| probe | 63.5 |
| real_test | 43.7 |
| tcp | 67.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 128 | 121 | 7 | 94.5% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 48 | 46 | 2 | 95.8% |
| vless | 28 | 18 | 10 | 64.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| geo:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| 204:TimeoutError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4981 |
| ConnectionRefusedError | 1058 |
| gaierror | 465 |
| OSError | 369 |
| SSRFBlocked | 6 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 174 | 0.931 | 10000 |
| Au1rxx-base64 | 0.829 | prefer | 27 | 0.778 | 1751 |
| Surfboard-tg-mixed | 0.749 | prefer | 13 | 0.923 | 7827 |
| mheidari-all | 0.48 | observe | 4 | 1.0 | 14594 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| ermaozi | 0.28 | observe | 1 | 1.0 | 622 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 499 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 390 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 385 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 134 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.778 | 21 | 6 | 27 |
| Surfboard-tg-mixed | 0.923 | 12 | 1 | 13 |
| dragon | 0.931 | 162 | 12 | 174 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| mheidari-all | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14594 | yes | 3.49 | 0 |
| SoliSpirit-all | 10517 | yes | 1.94 | 0 |
| dragon | 10000 | yes | 4.83 | 0 |
| Surfboard-tg-mixed | 7827 | yes | 2.46 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.28 | 0 |
| barry-far-vless | 5895 | yes | 0.47 | 0 |
| Surfboard-tg-vless | 5680 | yes | 2.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.36 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| 204 | 4 |
| geo | 3 |
| cn-block | 2 |
| speed | 1 |
