# 开发顺序
|阶段|交付|验收|
|---|---|---|
|P0|Rust workspace、CLI、配置、日志、CI|cargo test、dry-run|
|P1|调度、checkpoint、预算、模型接口|可中断恢复、成本记录|
|P2|文件/Git/终端工具与审批|权限拒绝和故障注入|
|P3|Claude方案→GPT实现→独立审核|端到端任务|
|P4|项目知识、决策与经验检索|来源可追溯|
|P5|有界Loop、评测、按需MoA|回归通过、预算不超|
|P6|InDesign CLI适配|Windows实机生成及回读|
|P7研究|SFT/DPO、本地路由模型|基线对照评测|
每阶段独立演示，未经实测不得标记Stable。
