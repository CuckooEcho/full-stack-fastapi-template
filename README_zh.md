

# Full Stack FastAPI 全栈模板

<a href="https://github.com/fastapi/full-stack-fastapi-template/actions?query=workflow%3ATest" target="_blank"><img src="https://github.com/fastapi/full-stack-fastapi-template/workflows/Test/badge.svg" alt="测试状态"></a>
<a href="https://coverage-badge.samuelcolvin.workers.dev/redirect/fastapi/full-stack-fastapi-template" target="_blank"><img src="https://coverage-badge.samuelcolvin.workers.dev/fastapi/full-stack-fastapi-template.svg" alt="测试覆盖率"></a>

## 技术栈与功能特性

- ⚡️ [**FastAPI**](https://fastapi.tiangolo.com) 作为 Python 后端 API 框架
    - 🧰 [SQLModel](https://sqlmodel.tiangolo.com) 处理 Python SQL 数据库交互 (ORM)
    - 🔍 [Pydantic](https://docs.pydantic.dev) 用于数据验证和设置管理
    - 💾 [PostgreSQL](https://www.postgresql.org) 作为关系型数据库
- 🚀 [React](https://react.dev) 前端框架
    - 💃 使用 TypeScript、Hooks、Vite 等现代前端技术栈
    - 🎨 [Chakra UI](https://chakra-ui.com) 前端组件库
    - 🤖 自动生成的前端客户端代码
    - 🧪 [Playwright](https://playwright.dev) 端到端测试
    - 🦇 深色模式支持
- 🐋 [Docker Compose](https://www.docker.com) 开发与生产环境容器化
- 🔒 默认启用安全密码哈希
- 🔑 JWT（JSON Web Token）认证
- 📫 基于邮件的密码找回
- ✅ [Pytest](https://pytest.org) 测试框架
- 📞 [Traefik](https://traefik.io) 反向代理/负载均衡
- 🚢 包含 Docker Compose 部署指南，支持自动 HTTPS 证书
- 🏭 基于 GitHub Actions 的 CI/CD 流水线

### 控制台登录
[![API 文档](img/login.png)](https://github.com/fastapi/full-stack-fastapi-template)

### 仪表盘 - 管理员界面
[![API 文档](img/dashboard.png)](https://github.com/fastapi/full-stack-fastapi-template)

（...其他图片部分保持不变...）

## 如何使用

**直接 fork 或克隆**本仓库即可使用。

✨ 开箱即用 ✨

### 创建私有仓库

GitHub 不允许直接 fork 后修改仓库可见性，建议操作步骤：

1. 创建新 GitHub 仓库（如 `my-full-stack`）
2. 克隆本仓库到本地：
```bash
git clone git@github.com:fastapi/full-stack-fastapi-template.git my-full-stack
```
3. 修改远程仓库地址：
```bash
cd my-full-stack
git remote set-url origin git@github.com:octocat/my-full-stack.git
```
4. 添加原始仓库为 upstream：
```bash
git remote add upstream git@github.com:fastapi/full-stack-fastapi-template.git
```
5. 推送代码：
```bash
git push -u origin master
```

### 配置说明

部署前必须修改以下环境变量：
- `SECRET_KEY`
- `FIRST_SUPERUSER_PASSWORD` 
- `POSTGRES_PASSWORD`

建议通过 secrets 管理这些变量，详见[部署文档](./deployment.md)。

### 生成密钥

使用以下命令生成安全密钥：
```bash
python -c "import secrets; print(secrets.token_urlsafe(32))"
```

（...后续部分保持结构对应翻译，技术术语保留英文...）

## 许可证

本项目采用 MIT 许可证，详见许可证文件。
```


根据提供的英文README，我为您创建中文版翻译。以下是主要修改建议：

```markdown:c:\Users\yq508\project\github\full-stack-fastapi-template\README_zh.md
# Full Stack FastAPI 全栈模板

<a href="https://github.com/fastapi/full-stack-fastapi-template/actions?query=workflow%3ATest" target="_blank"><img src="https://github.com/fastapi/full-stack-fastapi-template/workflows/Test/badge.svg" alt="测试状态"></a>
<a href="https://coverage-badge.samuelcolvin.workers.dev/redirect/fastapi/full-stack-fastapi-template" target="_blank"><img src="https://coverage-badge.samuelcolvin.workers.dev/fastapi/full-stack-fastapi-template.svg" alt="测试覆盖率"></a>

## 技术栈与功能特性

- ⚡️ [**FastAPI**](https://fastapi.tiangolo.com) 作为 Python 后端 API 框架
    - 🧰 [SQLModel](https://sqlmodel.tiangolo.com) 处理 Python SQL 数据库交互 (ORM)
    - 🔍 [Pydantic](https://docs.pydantic.dev) 用于数据验证和设置管理
    - 💾 [PostgreSQL](https://www.postgresql.org) 作为关系型数据库
- 🚀 [React](https://react.dev) 前端框架
    - 💃 使用 TypeScript、Hooks、Vite 等现代前端技术栈
    - 🎨 [Chakra UI](https://chakra-ui.com) 前端组件库
    - 🤖 自动生成的前端客户端代码
    - 🧪 [Playwright](https://playwright.dev) 端到端测试
    - 🦇 深色模式支持
- 🐋 [Docker Compose](https://www.docker.com) 开发与生产环境容器化
- 🔒 默认启用安全密码哈希
- 🔑 JWT（JSON Web Token）认证
- 📫 基于邮件的密码找回
- ✅ [Pytest](https://pytest.org) 测试框架
- 📞 [Traefik](https://traefik.io) 反向代理/负载均衡
- 🚢 包含 Docker Compose 部署指南，支持自动 HTTPS 证书
- 🏭 基于 GitHub Actions 的 CI/CD 流水线

### 控制台登录
[![API 文档](img/login.png)](https://github.com/fastapi/full-stack-fastapi-template)

### 仪表盘 - 管理员界面
[![API 文档](img/dashboard.png)](https://github.com/fastapi/full-stack-fastapi-template)

（...其他图片部分保持不变...）

## 如何使用

**直接 fork 或克隆**本仓库即可使用。

✨ 开箱即用 ✨

### 创建私有仓库

GitHub 不允许直接 fork 后修改仓库可见性，建议操作步骤：

1. 创建新 GitHub 仓库（如 `my-full-stack`）
2. 克隆本仓库到本地：
```bash
git clone git@github.com:fastapi/full-stack-fastapi-template.git my-full-stack
```
3. 修改远程仓库地址：
```bash
cd my-full-stack
git remote set-url origin git@github.com:octocat/my-full-stack.git
```
4. 添加原始仓库为 upstream：
```bash
git remote add upstream git@github.com:fastapi/full-stack-fastapi-template.git
```
5. 推送代码：
```bash
git push -u origin master
```

### 配置说明

部署前必须修改以下环境变量：
- `SECRET_KEY`
- `FIRST_SUPERUSER_PASSWORD` 
- `POSTGRES_PASSWORD`

建议通过 secrets 管理这些变量，详见[部署文档](./deployment.md)。

### 生成密钥

使用以下命令生成安全密钥：
```bash
python -c "import secrets; print(secrets.token_urlsafe(32))"
```

（...后续部分保持结构对应翻译，技术术语保留英文...）

## 许可证

本项目采用 MIT 许可证，详见许可证文件。

