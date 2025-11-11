# Market System 文档中心

欢迎来到 Market System 文档中心！这里包含了系统的完整文档。

适合新兴交易所！同时支持内部交易数据和外部数据源融合。

| 文档 | 说明 |
|------|------|
| [混合模式概述](hybrid-mode/README.md) | 了解混合模式的核心概念 |
| [快速入门](hybrid-mode/quickstart.md) | 5分钟体验混合模式 |
| [使用指南](hybrid-mode/guide.md) | 详细的配置和使用说明 |
| [架构设计](hybrid-mode/architecture.md) | 混合模式的技术架构 |
| [功能总结](hybrid-mode/summary.md) | 已实现功能和开发计划 |

## 文档结构

```
docs/
├── README.md                    #  文档导航（本文档）
├── getting-started.md           #  快速入门
├── architecture.md              #  系统架构
├── api-reference.md             #  API 参考
├── deployment.md                #  部署指南
├── performance.md               #  性能优化
├── monitoring.md                #  监控告警
├── development-setup.md         #  开发环境
├── contributing.md              #  贡献指南
├── faq.md                       #  常见问题
└── hybrid-mode/                 #  混合模式专题
    ├── README.md                # 混合模式概述
    ├── quickstart.md            # 快速入门
    ├── guide.md                 # 使用指南
    ├── architecture.md          # 架构设计
    └── summary.md               # 功能总结

- 当前版本：v1.0
- 最后更新：2025-11-11
- Go 版本：1.21+
- go-zero 版本：1.6.1

##  核心特性

- 微服务架构（基于 go-zero）
- 高性能实时数据采集
- 多交易所支持
- 混合模式（内外部数据融合）
- K线实时聚合
- WebSocket 推送
- RESTful API
- Docker 部署

