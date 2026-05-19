# TypeWeaver Studio

TypeWeaver Studio 是一个 AI 类型迁移与代码质量修复工作台，用来把历史 JavaScript 项目逐步迁移到 TypeScript。

## 项目能力

- 读取仓库结构、API 样本、运行时错误、测试快照和历史提交
- 推断 DTO、组件 props、service 层参数和工具函数类型
- 生成 TypeScript 类型定义、最小范围 patch 和回归测试
- 输出 PR 级迁移报告、风险等级和回滚建议

## 部署方式

这是一个静态 HTML demo，可以直接部署到 GitHub Pages、Netlify、Vercel 或任意静态托管平台。

GitHub Pages:
1. 新建公开仓库
2. 上传本项目中的 index.html
3. Settings → Pages → Deploy from branch
4. 选择 main / root
5. 保存并等待发布链接生成
