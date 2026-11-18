# 总体架构
User → Task Intake → Planner → Rust Scheduler → Model/Tool Adapters → Evaluation → Artifacts & Knowledge。
横切模块：Permission Gate、Budget Manager、Workspace、Event Log、Checkpoint、Trace。
Rust/Tokio + SQLite 单机起步；先用本地文件与全文检索，不预建分布式服务。
工具接口应定义 schema、权限、超时、结果、补偿动作；并非每种操作都能回滚。
