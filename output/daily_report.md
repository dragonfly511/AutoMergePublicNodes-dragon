# AutoNodes 每日报告

生成时间：2026-11-11 19:49:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 102998 |
| 去重后节点数 | 34661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 195 |
| verified 输出数 | 14 |
| global 输出数 | 198 |
| all 输出数 | 34661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.7 |
| fetch | 9.0 |
| generate | 17.8 |
| geo | 1.5 |
| probe | 95.1 |
| real_test | 41.3 |
| tcp | 89.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 156 | 142 | 14 | 91.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 60 | 36 | 24 | 60.0% |
| vless | 7 | 3 | 4 | 42.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 16 |
| test_one_timeout:15.0s | 15 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6580 |
| ConnectionRefusedError | 1048 |
| OSError | 248 |
| gaierror | 163 |
| ConnectionResetError | 2 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | prefer | 197 | 0.822 | 10000 |
| dragon2 | 0.811 | prefer | 24 | 0.75 | 10000 |
| dragon3 | 0.471 | observe | 9 | 0.778 | 100 |
| mheidari-all | 0.465 | observe | 7 | 0.714 | 14491 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8393 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4981 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2629 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11151 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 417 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 412 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 161 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 148 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.714 | 5 | 2 | 7 |
| dragon2 | 0.75 | 18 | 6 | 24 |
| dragon3 | 0.778 | 7 | 2 | 9 |
| dragon | 0.822 | 162 | 35 | 197 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14491 | yes | 4.98 | 0 |
| SoliSpirit-all | 11151 | yes | 2.72 | 0 |
| dragon | 10000 | yes | 8.38 | 0 |
| dragon2 | 10000 | yes | 6.47 | 0 |
| Surfboard-tg-mixed | 8393 | yes | 3.61 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.53 | 0 |
| barry-far-vless | 6516 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 6306 | yes | 4.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4981 | yes | 1.33 | 0 |
| mahdibland-V2RayAggregator | 4589 | yes | 0.29 | 0 |

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
| 204 | 18 |
| test_one_timeout | 15 |
| cn-block | 8 |
| speed | 5 |
| geo | 1 |
