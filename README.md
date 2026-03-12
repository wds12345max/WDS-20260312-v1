# 瑜伽 App 开发项目
🧘‍♀️ 专业瑜伽教学与社区平台移动端应用

## 项目介绍
为瑜伽爱好者提供系统化的课程学习、社区交流、个性化练习计划的移动端应用，支持 iOS 和 Android 双平台。

## 技术栈
### 前端
- 跨端框架：Flutter / React Native
- 状态管理：Provider / Redux
- UI 组件库：自定义设计系统
### 后端
- 语言：Java / Go / Node.js
- 框架：Spring Boot / Gin / NestJS
- 数据库：MySQL + Redis
### 基础设施
- 云服务：阿里云 / AWS
- 部署：Docker + Kubernetes
- CI/CD：GitHub Actions

## 目录结构
```
yoga-app-dev/
├── docs/                  # 文档目录
│   ├── requirements/      # 需求文档（PRD、需求池）
│   ├── design/            # 设计文档（UI设计、架构设计）
│   └── api/               # API 接口文档
├── frontend/              # 前端代码（移动端应用）
├── backend/               # 后端服务代码
├── database/              # 数据库相关
│   ├── migrations/        # 数据库迁移脚本
│   └── seeds/             # 初始化数据脚本
└── logs/                  # 学习 & 踩坑日志记录
```

## 开发规范
### Git 提交规范
- `feat:` 新功能
- `fix:` 修复 bug
- `docs:` 文档更新
- `style:` 代码格式调整
- `refactor:` 代码重构
- `test:` 测试相关
- `chore:` 构建/工具等变动

### 分支管理
- `main`：主分支，生产环境代码
- `develop`：开发分支，日常开发在此分支进行
- `feature/xxx`：功能分支，新功能开发
- `hotfix/xxx`：热修复分支，线上问题紧急修复

## 快速开始
### 前端开发
```bash
cd frontend
# 安装依赖
flutter pub get
# 运行开发环境
flutter run
```

### 后端开发
```bash
cd backend
# 启动服务
mvn spring-boot:run
# 或
go run main.go
```

## 项目成员
- 产品：德胜
- 开发：OpenClaw 辅助开发

## 更新日志
- 2026-03-12：项目初始化，完成标准化目录结构搭建
