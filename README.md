# 不折腾文档

[![Built with Rspress](https://img.shields.io/badge/Built%20with-Rspress-blue)](https://rspress.dev/)

这里是不折腾文档站的 Rspress 版本

## 📚 主要内容

本文档站涵盖了以下核心项目的详细文档：

1. **Sub Store** - 适用于 QX、Loon、Surge、Stash 和 Shadowrocket 的高级订阅管理器
2. **Script Hub** - 支持多平台的高级脚本转换器
3. **BoxJs** - 跨平台脚本运行环境
4. **PagerMaid-Pyro** - Telegram 人形自走 Bot 解决方案

## 🚀 项目结构

```
.
├── docs/
│   ├── public/
│   │   ├── project/
│   │   │   ├── sub-store/
│   │   │   ├── script-hub/
│   │   │   ├── boxjs/
│   │   │   └── pagermaid/
│   │   └── _meta.json
│   ├── rspress.config.ts
│   ├── package.json
│   └── tsconfig.json
```

- `docs/` 目录存放所有的文档文件（`.md` 或 `.mdx`）
- `docs/public/` 用于存储静态资源文件
- `docs/project/` 存放各个项目的具体文档
- `_meta.json` 用于配置文档的导航结构

## 🛠️ 常用命令

所有命令都需要在项目根目录下运行：

| 命令                   | 功能描述                                       |
| :-------------------- | :-------------------------------------------- |
| `pnpm install`         | 安装项目依赖                                   |
| `pnpm dev`         | 启动本地开发服务器                             |
| `pnpm build`       | 构建生产环境版本                               |
| `pnpm preview`     | 本地预览生产环境构建版本                       |

## 🔗 相关链接

- [Telegram 群组](https://t.me/zhetengsha_group)
- [Telegram 频道](https://t.me/zhetengsha)

## 👥 贡献者

本文档由 [@atiskimiasa](https://t.me/atiskimiasa) 编写，[@xream](https://t.me/xream) 提供指导。

## 📖 了解更多

- [Rspress 文档](https://rspress.dev/)
- [Rspack 文档](https://www.rspack.dev/)
