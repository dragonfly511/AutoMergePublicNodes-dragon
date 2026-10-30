# AutoNodes 每日报告

生成时间：2026-10-30 01:58:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/90 |
| 原始节点数 | 109307 |
| 去重后节点数 | 35026 |
| TCP 可达数 | 3000 |
| 真测通过数 | 287 |
| verified 输出数 | 131 |
| global 输出数 | 291 |
| all 输出数 | 35026 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 35.6 |
| fetch | 6.9 |
| generate | 13.5 |
| geo | 1.6 |
| probe | 78.3 |
| real_test | 76.2 |
| tcp | 99.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 78 | 74 | 4 | 94.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 28 | 26 | 2 | 92.9% |
| vless | 306 | 151 | 155 | 49.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 99 |
| geo:ClientOSError | 30 |
| speed:ClientOSError | 18 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7221 |
| ConnectionRefusedError | 1129 |
| gaierror | 237 |
| OSError | 237 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 53 | 1.0 | 10000 |
| ermaozi | 0.975 | prefer | 20 | 1.0 | 515 |
| Au1rxx-base64 | 0.921 | prefer | 93 | 0.86 | 1706 |
| Surfboard-tg-mixed | 0.718 | prefer | 45 | 0.644 | 7758 |
| mheidari-all | 0.525 | observe | 234 | 0.444 | 33573 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10429 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.131 | observe | 1 | 0.0 | 0 | 97 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.444 | 104 | 130 | 234 |
| Surfboard-tg-mixed | 0.644 | 29 | 16 | 45 |
| Au1rxx-base64 | 0.86 | 80 | 13 | 93 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| ermaozi | 1.0 | 20 | 0 | 20 |
| dragon | 1.0 | 53 | 0 | 53 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33573 | yes | 4.72 | 0 |
| SoliSpirit-all | 10429 | yes | 2.74 | 0 |
| dragon | 10000 | yes | 6.09 | 0 |
| Surfboard-tg-mixed | 7758 | yes | 3.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.22 | 0 |
| barry-far-vless | 6001 | yes | 1.7 | 0 |
| Surfboard-tg-vless | 5789 | yes | 2.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.37 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 1.26 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.22 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 99 |
| geo | 30 |
| speed | 18 |
| 204 | 10 |
| cn-block | 5 |
