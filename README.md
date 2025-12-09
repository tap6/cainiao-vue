# Cainiao Vue 项目

## 项目截图

![项目截图](./screenshot.png)

## 项目简介
Cainiao Vue 是一个基于 Vue.js 的前端项目，旨在提供一个简单易用的开发模板。项目使用 Vue 2.x 版本，并集成了 Vue Router 和 Vuex。

## 目录结构
```
.
├── build/                  # 构建相关配置
├── config/                # 环境配置文件
├── src/                   # 源代码目录
│   ├── assets/            # 静态资源
│   ├── components/        # 公共组件
│   ├── router/            # 路由配置
│   ├── styles/            # 样式文件
│   ├── utils/             # 工具函数
│   ├── views/             # 页面视图
├── static/                # 静态文件
├── index.html             # 入口 HTML 文件
├── package.json           # 项目依赖和脚本
└── README.md              # 项目说明文件
```

## 安装依赖
确保您已安装 Node.js（版本 >= 16.x）：

```bash
npm install
```

## 启动开发服务器
运行以下命令启动开发服务器：

```bash
npm run dev
```

开发服务器默认运行在 `http://localhost:8080`。

## 构建生产版本
使用以下命令构建生产版本：

```bash
npm run build
```

构建完成后，生成的文件位于 `dist/` 目录。

## 代码检查
运行以下命令检查代码：

```bash
npm run lint
```

## 常见问题
### 1. Node.js 版本兼容性
本项目推荐使用 Node.js 16.x 或更高版本。如果您遇到依赖安装问题，请尝试以下命令：

```bash
npm install --legacy-peer-deps
```

### 2. node-sass 编译失败
本项目已将 `node-sass` 替换为 `sass`，以解决编译问题。

## 贡献
欢迎提交 Issue 或 Pull Request！

## 许可证
[MIT](LICENSE)