# AutoNodes 每日报告

生成时间：2026-11-10 07:35:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 101909 |
| 去重后节点数 | 34014 |
| TCP 可达数 | 3000 |
| 真测通过数 | 265 |
| verified 输出数 | 12 |
| global 输出数 | 265 |
| all 输出数 | 34014 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.9 |
| fetch | 6.8 |
| generate | 13.6 |
| geo | 1.5 |
| probe | 73.8 |
| real_test | 36.3 |
| tcp | 95.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 199 | 182 | 17 | 91.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 76 | 67 | 9 | 88.2% |
| vless | 3 | 2 | 1 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6925 |
| ConnectionRefusedError | 1023 |
| OSError | 238 |
| gaierror | 135 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 262 | 0.935 | 10000 |
| dragon2 | 0.622 | observe | 22 | 0.545 | 10000 |
| mheidari-all | 0.446 | observe | 5 | 0.8 | 13900 |
| dragon3 | 0.362 | observe | 3 | 1.0 | 100 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8228 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2754 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11021 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6133 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 414 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 158 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 145 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| peasoft-NoMoreWalls | 0.5 | 1 | 1 | 2 |
| dragon2 | 0.545 | 12 | 10 | 22 |
| mheidari-all | 0.8 | 4 | 1 | 5 |
| dragon | 0.935 | 245 | 17 | 262 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13900 | yes | 4.43 | 0 |
| SoliSpirit-all | 11021 | yes | 2.85 | 0 |
| dragon | 10000 | yes | 6.24 | 0 |
| dragon2 | 10000 | yes | 2.88 | 0 |
| Surfboard-tg-mixed | 8228 | yes | 4.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 6344 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 6133 | yes | 2.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.35 | 0 |
| mahdibland-V2RayAggregator | 4583 | yes | 2.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 4 |
| cn-block | 2 |
| geo | 2 |
| speed | 2 |
