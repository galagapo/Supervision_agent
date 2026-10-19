# Supervision_agent

监管报送配置 Agent 学习及实践项目。

## 当前目标

实现一个监管报送配置 Agent Demo，使开发人员能够通过自然语言描述：

- 监管平台信息
- 接口信息
- 上传规则
- 目标报文字段

Agent 根据输入生成配置建议，并逐步完成监管报送配置。

## 当前阶段

阶段 0：建立基础工程，完成数据模型和基础 Tool。

## 项目结构

- `src/regulatory_agent/schemas.py`：Pydantic 数据模型
- `src/regulatory_agent/tools.py`：Agent 可调用工具
- `src/regulatory_agent/main.py`：程序入口
- `tests/`：测试代码
- `docs/`：设计文档
