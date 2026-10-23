# AutoNodes 每日报告

生成时间：2026-10-23 08:42:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 96124 |
| 去重后节点数 | 26841 |
| TCP 可达数 | 3000 |
| 真测通过数 | 441 |
| verified 输出数 | 160 |
| global 输出数 | 300 |
| all 输出数 | 26841 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.0 |
| fetch | 4.1 |
| generate | 8.6 |
| geo | 1.4 |
| probe | 73.0 |
| real_test | 89.9 |
| tcp | 82.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 104 | 100 | 4 | 96.2% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 155 | 145 | 10 | 93.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 49 | 35 | 14 | 71.4% |
| vless | 244 | 147 | 97 | 60.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 70 |
| speed:ClientOSError | 15 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 4 |
| 204:TimeoutError | 4 |
| geo:ProxyError | 3 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6661 |
| ConnectionRefusedError | 1023 |
| OSError | 237 |
| gaierror | 153 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.986 | prefer | 102 | 0.971 | 609 |
| Au1rxx-base64 | 0.903 | prefer | 264 | 0.845 | 1524 |
| Surfboard-tg-mixed | 0.744 | prefer | 105 | 0.667 | 6999 |
| mheidari-all | 0.657 | observe | 76 | 0.579 | 23755 |
| DeltaKronecker-all | 0.322 | observe | 16 | 0.25 | 3871 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| tg-oneclickvpnkeys | 0.272 | observe | 3 | 0.667 | 83 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.134 | observe | 1 | 0.0 | 0 | 163 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 492 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 383 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 378 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 127 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 4 | 12 | 16 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.579 | 44 | 32 | 76 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.667 | 70 | 35 | 105 |
| Au1rxx-base64 | 0.845 | 223 | 41 | 264 |
| ermaozi | 0.971 | 99 | 3 | 102 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23755 | yes | 3.22 | 0 |
| SoliSpirit-all | 9987 | yes | 2.74 | 0 |
| Epodonios-all | 7492 | yes | 3.46 | 0 |
| Surfboard-tg-mixed | 6999 | yes | 2.78 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.67 | 0 |
| barry-far-vless | 5662 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5447 | yes | 2.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 1.83 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 70 |
| geo | 20 |
| speed | 16 |
| 204 | 15 |
| cn-block | 6 |
