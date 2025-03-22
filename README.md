# 合租平台

这是一个基于Next.js和React开发的会员账号合租平台，允许用户发布和查找各类会员账号的合租需求。

## 功能特点

- 用户可以发布各类会员账号的合租需求
- 按类别浏览不同类型的合租信息
- 查看合租详情并联系发布者
- 响应式设计，支持移动端和桌面端

## 技术栈

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- MongoDB (计划中)
- NextAuth.js (计划中)

## 快速开始

### 环境要求

- Node.js 18.x 或更高版本
- npm 或 yarn

### 安装步骤

1. 克隆项目

```bash
git clone https://github.com/yourusername/hezu.git
cd hezu
```

2. 安装依赖

```bash
npm install
# 或者
yarn
```

3. 运行开发服务器

```bash
npm run dev
# 或者
yarn dev
```

4. 在浏览器中打开 [http://localhost:3000](http://localhost:3000)

## 项目结构

```
hezu/
├── app/                  # Next.js App Router
│   ├── components/       # 共享组件
│   ├── api/              # API 路由
│   ├── models/           # 数据模型
│   ├── lib/              # 工具函数
│   └── ...               # 页面路由
├── public/               # 静态资源
├── README.md             # 项目文档
├── package.json          # 项目依赖
└── ...                   # 其他配置文件
```

## 开发计划

- [ ] 用户注册和登录功能
- [ ] 发布合租需求的表单提交
- [ ] 合租详情页面
- [ ] 消息通知系统
- [ ] 支付集成
- [ ] 用户评价系统

## 贡献指南

1. Fork 这个仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开一个 Pull Request

## 许可证

MIT 许可证 