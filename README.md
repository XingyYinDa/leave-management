# 员工请假管理系统（部门级轻量方案）

纯原生 HTML/CSS/JS 单文件实现，零外部依赖。局域网小服务 + 浏览器访问形态，花名册免密登录。

## 在线访问

| 内容 | 地址 |
| --- | --- |
| 交互原型（首页） | https://XingyYinDa.github.io/leave-management/ |
| 需求规格说明书 SPEC | https://XingyYinDa.github.io/leave-management/spec.html |
| 产品需求文档 PRD | https://XingyYinDa.github.io/leave-management/prd.docx（点击下载） |

## 功能覆盖（对应 PRD v1.0）

- F1 请假申请：7 种假类、半天精度、时长自动计算
- F2 审批流：单级经理审批 + 代批人机制、驳回意见必填
- F3 待办与催办：站内待办红点、超 24h 催办高亮
- F4 台账与统计：月度台账筛选、个人年度汇总、CSV 导出
- F5 花名册：免密登录、角色指派、代批设置
- F6 数据备份：一键导出全量数据（每日自动备份为 P1 加固项）

## 技术特点

- 单文件双击即运行，无构建、无依赖、无框架
- localStorage 持久化（原型演示形态；正式版为服务端集中存储）
- 白底淡蓝主色、简洁紧凑界面；桌面/移动端自适应

> 本仓库为交互原型演示，人员均为虚构演示数据。