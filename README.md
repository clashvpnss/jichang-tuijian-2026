# 机场选购与排错知识库

科学上网客户端的报错排查、机场选购判断，以及线路与协议术语的原理说明。
共 **266 条问答** 与 **10 个术语词条**，全部为纯文本，可直接搜索、可 fork、可提 issue 补充。

## 这份资料解决什么问题

- 节点全部超时、订阅导入失败、Clash 报错找不到原因
- 流媒体或 AI 服务打不开，不知道是节点问题还是 IP 问题
- 买机场时看不懂「IPLC 专线」「BGP 中转」「倍率」「原生 IP」到底指什么
- 想判断一份机场评测或榜单值不值得信

## 目录

### 报错排查与选购问答

| 分类 | 条数 |
| --- | --- |
| [📖 机场基础概念与黑话入门](faq/01-%E5%9F%BA%E7%A1%80%E6%A6%82%E5%BF%B5.md) | 10 |
| [⚠️ 客户端报错与玄学断网](faq/02-%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%8A%A5%E9%94%99.md) | 10 |
| [🎬 流媒体与特定服务风控](faq/03-%E6%B5%81%E5%AA%92%E4%BD%93%E4%B8%8E%E9%A3%8E%E6%8E%A7.md) | 8 |
| [🌐 极端网络与运营商封锁](faq/04-%E7%BD%91%E7%BB%9C%E5%B0%81%E9%94%81.md) | 6 |
| [💳 订阅、账户与支付长尾问题](faq/05-%E8%AE%A2%E9%98%85%E4%B8%8E%E6%94%AF%E4%BB%98.md) | 8 |
| [🔀 分流规则、DNS 泄漏与进阶配置](faq/06-%E5%88%86%E6%B5%81%E4%B8%8EDNS.md) | 8 |
| [📱 设备兼容性与特殊场景](faq/07-%E8%AE%BE%E5%A4%87%E5%85%BC%E5%AE%B9.md) | 6 |
| [⚙️ 协议底层技术与软路由](faq/08-%E5%8D%8F%E8%AE%AE%E4%B8%8E%E8%BD%AF%E8%B7%AF%E7%94%B1.md) | 48 |
| [💼 高级客户端与外贸专属](faq/09-%E9%AB%98%E7%BA%A7%E5%AE%A2%E6%88%B7%E7%AB%AF.md) | 96 |
| [🧭 选购决策与费用](faq/10-%E9%80%89%E8%B4%AD%E5%86%B3%E7%AD%96.md) | 20 |
| [🛰️ 线路类型与 IP 属性](faq/11-%E7%BA%BF%E8%B7%AF%E4%B8%8EIP.md) | 15 |
| [💳 流量、倍率与付费周期](faq/12-%E6%B5%81%E9%87%8F%E4%B8%8E%E8%AE%A1%E8%B4%B9.md) | 9 |
| [🛡️ 运营风险与故障应对](faq/13-%E8%BF%90%E8%90%A5%E9%A3%8E%E9%99%A9.md) | 8 |
| [🔍 怎么判断评测与榜单](faq/14-%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E8%AF%84%E6%B5%8B.md) | 14 |

### 术语词条

- [什么是 BGP网络？边界网关协议 深度解析](glossary/bgp.md)
- [什么是 CN2 GIA线路？中国电信最高端跨境网络 深度解析](glossary/cn2-gia.md)
- [什么是 机房IP (IDC IP)？数据中心提供的IP地址 深度解析](glossary/data-center-ip.md)
- [什么是 直连线路？未经中转的国际网络连接 深度解析](glossary/direct-connection.md)
- [什么是 IPLC专线？国际私有计算机网络专线 深度解析](glossary/iplc.md)
- [什么是 Netflix流媒体解锁？原生IP解锁区域限制 深度解析](glossary/netflix-unlock.md)
- [什么是 住宅IP？分配给普通家庭宽带的IP 深度解析](glossary/residential-ip.md)
- [什么是 Shadowsocks (SS)？初代科学上网协议 深度解析](glossary/shadowsocks.md)
- [什么是 Trojan协议？抗封锁代理协议 深度解析](glossary/trojan.md)
- [什么是 Vmess协议？V2ray核心协议 深度解析](glossary/vmess.md)

## 关于准确性

这份资料的原则和来源站点一致：

- **不提供实测数据。** 这里没有延迟、带宽、丢包率的测试数值，也没有测速截图——那类结果依赖测试时间、本地带宽和当时负载，无法复现。
- **区分厂商说法与判断依据。** 涉及具体服务时，标明哪些是运营方公示、哪些无法核实。
- **给方法而不是结论。** 例如线路类型可以用 `BestTrace`/`mtr` 路由追踪自行验证，解锁状态可以用开源脚本 [RegionRestrictionCheck](https://github.com/lmc999/RegionRestrictionCheck) 自测。

发现错误或有补充，欢迎提 issue 或 PR。

## 相关链接

- 网页版问答库（支持检索与标签筛选）：https://www.clashmetahub.com/troubleshoot/
- 测速方法论：https://www.clashmetahub.com/speedtest/
- 选购指南：https://www.clashmetahub.com/guides/
- 术语词典：https://www.clashmetahub.com/wiki/

## 利益披露

维护本仓库的 [机场推荐导航](https://www.clashmetahub.com) 通过联盟推广链接获得佣金。
因此本站并非无利益立场的第三方——这也是这份资料只陈述可核实信息、
并把厂商说法与自身推断分开标注的原因。判断权在你。

## 许可

内容以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 发布，转载请注明来源。
