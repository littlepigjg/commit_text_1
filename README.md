# 登录页面项目

一个基于 React + TypeScript + Tailwind CSS 的现代化登录页面。

## 功能特性

- 🎨 **美观的界面设计**
  - 渐变背景（蓝色到紫色）
  - 卡片式登录框带阴影效果
  - 响应式布局，支持移动端

- ✅ **完整的表单功能**
  - 邮箱输入框（带图标和格式验证）
  - 密码输入框（带图标和长度验证）
  - 登录按钮带加载状态动画
  - 表单验证反馈

- 🔐 **社交登录选项**
  - Google 登录按钮
  - Facebook 登录按钮

- 🔗 **其他功能链接**
  - 忘记密码链接
  - 注册账户链接

## 技术栈

- **框架**: React 18 + TypeScript
- **构建工具**: Vite 6
- **样式**: Tailwind CSS 3
- **路由**: React Router DOM

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

访问 http://localhost:5173 查看页面。

### 构建生产版本

```bash
npm run build
```

## 测试账户

用于测试登录功能：

- **邮箱**: admin@example.com
- **密码**: 123456

## 项目结构

```
├── public/           # 静态资源
├── src/
│   ├── pages/        # 页面组件
│   │   └── Login.tsx # 登录页面
│   ├── App.tsx       # 应用入口
│   ├── main.tsx      # 主入口文件
│   └── index.css     # 全局样式
├── package.json      # 项目依赖
├── vite.config.ts    # Vite 配置
├── tailwind.config.js # Tailwind 配置
└── tsconfig.json     # TypeScript 配置
```

## 开发说明

登录页面包含以下核心功能：

1. **表单验证**：邮箱格式验证、密码长度验证（至少6位）
2. **状态管理**：使用 React useState 管理表单数据、错误信息、加载状态和消息提示
3. **模拟登录**：前端模拟登录逻辑，测试账户为 admin@example.com / 123456
4. **响应式设计**：使用 Tailwind CSS 实现移动端适配
