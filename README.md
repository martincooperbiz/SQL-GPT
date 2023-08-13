
# SQL_GPT: SQL 生成工具

## 简介

SQL_GPT 是一款强大的工具，它能够通过简单的文字描述，自动生成符合要求的 SQL 查询语句。无论您是在快速生成复杂查询还是与数据库进行交互，SQL_GPT 都能够显著提升您的效率和工作流程。

## 功能与特性

### 自动化 SQL 查询生成

SQL_GPT 可以根据用户提供的文字描述，智能地生成符合要求的 SQL 查询语句。这让您不再需要深入了解 SQL 语法，只需简单地用自然语言描述您的查询需求。

### 错误修正与建议

如果生成的 SQL 查询存在问题，不用担心！SQL_GPT 会分析错误信息，并为您提供修正建议，帮助您快速排除问题，保证您的查询语句准确无误。

### 数据库连接与交互

SQL_GPT 支持配置真实的数据库连接信息，这使得您能够直接在工具内部执行生成的 SQL 查询，并与数据库进行实时交互。无需切换环境，一切尽在掌握。

### 多数据库支持

不论您使用的是 MySQL、PostgreSQL 还是 Microsoft SQL Server，SQL_GPT 都能够与多种主流数据库系统兼容。这为不同项目的使用提供了更大的灵活性。

### 用户友好界面

SQL_GPT 提供了直观的用户界面，无论您是初学者还是经验丰富的专业人士，都能够轻松上手。简单直观的操作界面，让您的工作更加高效。

## 功能列表

- [x] **自动生成 SQL 查询：** 只需简单的文字描述，工具将自动生成符合要求的 SQL 查询语句。
- [x] **错误修正建议：** 在查询存在错误时，工具会提供智能的修正建议，助您快速解决问题。
- [x] **数据库连接管理：** 轻松配置和管理多个数据库连接，直接在工具内执行生成的 SQL 查询。
- [x] **多数据库兼容：** 工具兼容多种主流数据库系统，适用于不同项目的需求。
- [x] **代理访问支持：** 针对特定场景，您可以通过系统代理来访问 GPT 服务。
- [x] **多 API KEY 轮询：** 您可以设置多个备选 API KEY 来访问 GPT，提升稳定性。
- [ ] **数据自动可视化分析：** 在通过数据库操作完数据之后，通过对数据进行分析来展示数据的基础信息。

## 快速入门指南

要开始使用 SQL_GPT，只需按照以下简单步骤进行操作：

1. **安装所需依赖：** 确保您的环境中已安装 Python 3.x，并执行以下命令安装所需依赖包：

    ```bash
    pip install requirements.txt
    ```

2. **配置数据库连接：** 在工具中配置您的数据库连接信息，包括主机名、用户名、密码等，以便进行数据库交互。

3. **生成 SQL 查询：** 在工具的用户界面中，用自然语言描述您的查询需求。SQL_GPT 将会智能地生成相应的 SQL 查询语句。

## 使用示例

**输入描述：** 我希望查找年龄超过 25 岁的用户。

**生成的 SQL 查询：**
```sql
SELECT * FROM users WHERE age > 25;
```

## Star历史

[![Star History Chart](https://api.star-history.com/svg?repos=CL-lau/SQL-GPT&type=Date)](https://star-history.com/#CL-lau/SQL-GPT&Date)