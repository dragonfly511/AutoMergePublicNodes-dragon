# AutoNodes 每日报告

生成时间：2026-10-23 09:12:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/108 |
| 清理建议：禁用/降权 | 14/1 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 98553 |
| 去重后节点数 | 29489 |
| TCP 可达数 | 3000 |
| 真测通过数 | 416 |
| verified 输出数 | 146 |
| global 输出数 | 300 |
| all 输出数 | 29489 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.1 |
| fetch | 9.1 |
| generate | 15.2 |
| geo | 1.5 |
| probe | 97.4 |
| real_test | 81.6 |
| tcp | 91.7 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 105 | 101 | 4 | 96.2% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 157 | 141 | 16 | 89.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 51 | 40 | 11 | 78.4% |
| vless | 229 | 121 | 108 | 52.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 67 |
| speed:ClientOSError | 17 |
| 204:TimeoutError | 16 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6588 |
| ConnectionRefusedError | 1034 |
| OSError | 238 |
| gaierror | 226 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | prefer | 103 | 0.961 | 609 |
| Au1rxx-base64 | 0.861 | prefer | 253 | 0.802 | 1537 |
| Surfboard-tg-mixed | 0.734 | prefer | 102 | 0.657 | 6855 |
| mheidari-all | 0.597 | observe | 87 | 0.517 | 23755 |
| tg-oneclickvpnkeys | 0.272 | observe | 3 | 0.667 | 83 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| Epodonios-all | 0.255 | observe | 0 | None | 7492 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9987 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5326 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 493 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 384 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 379 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 128 | 连续死亡次数 >= 2 |
| downweight | DeltaKronecker-all | 0.243 | 11 | 0.182 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.182 | 2 | 9 | 11 |
| mheidari-all | 0.517 | 45 | 42 | 87 |
| Surfboard-tg-mixed | 0.657 | 67 | 35 | 102 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.802 | 203 | 50 | 253 |
| ermaozi | 0.961 | 99 | 4 | 103 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23755 | yes | 6.37 | 0 |
| SoliSpirit-all | 9987 | yes | 3.91 | 0 |
| Epodonios-all | 7492 | yes | 6.57 | 0 |
| Surfboard-tg-mixed | 6855 | yes | 3.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.28 | 0 |
| barry-far-vless | 5662 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 5326 | yes | 4.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 2.79 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 0.93 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 67 |
| 204 | 31 |
| speed | 17 |
| geo | 16 |
| cn-block | 10 |
