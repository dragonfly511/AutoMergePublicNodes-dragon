# AutoNodes 每日报告

生成时间：2026-11-27 08:54:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 98416 |
| 去重后节点数 | 33308 |
| TCP 可达数 | 3000 |
| 真测通过数 | 129 |
| verified 输出数 | 15 |
| global 输出数 | 129 |
| all 输出数 | 33308 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.7 |
| fetch | 8.9 |
| generate | 17.6 |
| geo | 1.6 |
| probe | 97.2 |
| real_test | 21.5 |
| tcp | 86.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 112 | 109 | 3 | 97.3% |
| socks | 19 | 18 | 1 | 94.7% |
| trojan | 8 | 7 | 1 | 87.5% |
| vless | 6 | 4 | 2 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 5 |
| 204:TimeoutError | 2 |
| 204:ProxyError | 1 |
| geo:ClientOSError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7034 |
| ConnectionRefusedError | 1039 |
| OSError | 258 |
| gaierror | 201 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 126 | 0.952 | 10000 |
| ermaozi | 0.67 | observe | 11 | 1.0 | 422 |
| Surfboard-tg-mixed | 0.446 | observe | 5 | 0.8 | 8568 |
| dragon3 | 0.413 | observe | 6 | 0.833 | 100 |
| tg-LonUp_M | 0.365 | observe | 3 | 1.0 | 173 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 116 |
| tg-proxy_mtm | 0.258 | observe | 1 | 1.0 | 67 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4936 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.143 | observe | 1 | 0.0 | 0 | 391 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 449 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 444 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 327 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon2 | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.8 | 4 | 1 | 5 |
| dragon3 | 0.833 | 5 | 1 | 6 |
| dragon | 0.952 | 120 | 6 | 126 |
| tg-proxy_mtm | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| tg-LonUp_M | 1.0 | 3 | 0 | 3 |
| ermaozi | 1.0 | 11 | 0 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14315 | yes | 4.66 | 0 |
| SoliSpirit-all | 11572 | yes | 4.05 | 0 |
| dragon | 10000 | yes | 8.22 | 0 |
| dragon2 | 9914 | yes | 6.43 | 0 |
| Surfboard-tg-mixed | 8568 | yes | 5.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.99 | 0 |
| barry-far-vless | 5609 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 5426 | yes | 3.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 4936 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4459 | yes | 2.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 5 |
| 204 | 3 |
| geo | 1 |
| speed | 1 |
