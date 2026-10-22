# 人工成本与人效分析项目

本仓库用于沉淀人效分析、人工成本管理驾驶舱及 K 车间 3D 数字架构的演示成果、部署入口与后续工作。

## 在线入口

| 项目 | 地址 | 访问范围 | 当前版本 |
| --- | --- | --- | --- |
| 人效分析系统 Demo | https://renxiao-demo.ronbay.top | 公开 | v3 |
| 人工成本与人效管理驾驶舱 · 优化版 | https://ronbay-workforce-cockpit-v2.hris-ronbay.chatgpt.site | 指定成员 | v4 |
| K 车间 3D 数字架构 | https://k-workshop-3d-twin.hris-ronbay.chatgpt.site | 公开 | v3 |

部署信息最后核对时间：2026-10-22（Asia/Shanghai）。详细说明见 [SERVERS.md](SERVERS.md)。

## 文档

- [CHANGELOG.md](CHANGELOG.md)：已完成修改与版本记录
- [SERVERS.md](SERVERS.md)：线上地址、访问范围和维护说明
- [TODO.md](TODO.md)：上线前及后续迭代事项

## 目录说明

- `dist/`：人效分析系统 Demo 当前静态站点
- `sites/ronbay-workforce-cockpit-v2/`：人工成本与人效管理驾驶舱优化版
- `sites/k-workshop-3d/`：K 车间 3D 数字架构
- `output/`：汇报材料与离线交付件
- `outputs/`：数据导入模板
- `spreadsheet-build/`：导入模板生成脚本及校验样例

> 仓库内页面目前主要用于交互演示。正式生产化前请完成真实数据源、权限、审计和运维能力接入，详见待办清单。
