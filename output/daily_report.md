# AutoNodes 每日报告

生成时间：2026-10-23 12:11:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/90 |
| 原始节点数 | 105776 |
| 去重后节点数 | 34793 |
| TCP 可达数 | 3000 |
| 真测通过数 | 267 |
| verified 输出数 | 131 |
| global 输出数 | 274 |
| all 输出数 | 34793 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.8 |
| fetch | 9.4 |
| generate | 17.9 |
| geo | 1.6 |
| probe | 93.9 |
| real_test | 59.6 |
| tcp | 90.5 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 105 | 102 | 3 | 97.1% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 59 | 49 | 10 | 83.1% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 14 | 10 | 4 | 71.4% |
| vless | 144 | 96 | 48 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 34 |
| geo:ClientOSError | 7 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 4 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6552 |
| ConnectionRefusedError | 1060 |
| OSError | 236 |
| gaierror | 234 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.986 | prefer | 103 | 0.971 | 609 |
| Au1rxx-base64 | 0.863 | prefer | 124 | 0.806 | 1538 |
| mheidari-all | 0.734 | prefer | 50 | 0.66 | 23755 |
| Surfboard-tg-mixed | 0.718 | prefer | 45 | 0.644 | 6855 |
| dragon | 0.401 | observe | 7 | 0.571 | 10000 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 83 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 3871 |
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
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 495 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 386 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 381 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 130 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| dragon | 0.571 | 4 | 3 | 7 |
| Surfboard-tg-mixed | 0.644 | 29 | 16 | 45 |
| mheidari-all | 0.66 | 33 | 17 | 50 |
| Au1rxx-base64 | 0.806 | 100 | 24 | 124 |
| ermaozi | 0.971 | 100 | 3 | 103 |
| zhangkai | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23755 | yes | 6.65 | 0 |
| SoliSpirit-all | 10293 | yes | 4.28 | 0 |
| dragon | 10000 | yes | 8.92 | 0 |
| Epodonios-all | 7492 | yes | 4.89 | 0 |
| Surfboard-tg-mixed | 6855 | yes | 4.09 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.73 | 0 |
| barry-far-vless | 5662 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5326 | yes | 3.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 4.52 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 3.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 34 |
| cn-block | 11 |
| 204 | 10 |
| geo | 7 |
| speed | 4 |
