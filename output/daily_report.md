# AutoNodes 每日报告

生成时间：2026-10-23 10:15:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/90 |
| 原始节点数 | 98769 |
| 去重后节点数 | 29477 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 154 |
| global 输出数 | 300 |
| all 输出数 | 29477 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 16.6 |
| fetch | 7.5 |
| generate | 13.8 |
| geo | 1.5 |
| probe | 87.9 |
| real_test | 73.3 |
| tcp | 82.2 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 106 | 102 | 4 | 96.2% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 159 | 147 | 12 | 92.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 48 | 35 | 13 | 72.9% |
| vless | 181 | 113 | 68 | 62.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 60 |
| geo:ClientOSError | 12 |
| 204:ProxyError | 6 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| cn-block:TimeoutError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6146 |
| ConnectionRefusedError | 1049 |
| gaierror | 318 |
| OSError | 237 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | prefer | 103 | 0.961 | 609 |
| Au1rxx-base64 | 0.902 | prefer | 218 | 0.844 | 1537 |
| mheidari-all | 0.761 | prefer | 67 | 0.687 | 23755 |
| Surfboard-tg-mixed | 0.757 | prefer | 97 | 0.68 | 6855 |
| dragon | 0.48 | observe | 4 | 1.0 | 3000 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 3871 |
| tg-oneclickvpnkeys | 0.361 | observe | 3 | 1.0 | 83 |
| tg-LonUp_M | 0.327 | observe | 4 | 0.75 | 166 |
| zhangkai | 0.256 | observe | 1 | 1.0 | 24 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 20 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 494 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 385 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 380 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 129 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| Surfboard-tg-mixed | 0.68 | 66 | 31 | 97 |
| mheidari-all | 0.687 | 46 | 21 | 67 |
| tg-LonUp_M | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.844 | 184 | 34 | 218 |
| ermaozi | 0.961 | 99 | 4 | 103 |
| zhangkai | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23755 | yes | 5.01 | 0 |
| SoliSpirit-all | 10291 | yes | 3.14 | 0 |
| Epodonios-all | 7492 | yes | 5.13 | 0 |
| Surfboard-tg-mixed | 6855 | yes | 3.5 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.47 | 0 |
| barry-far-vless | 5662 | yes | 0.74 | 0 |
| Surfboard-tg-vless | 5326 | yes | 3.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 0.15 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 60 |
| geo | 14 |
| 204 | 13 |
| cn-block | 10 |
| speed | 2 |
