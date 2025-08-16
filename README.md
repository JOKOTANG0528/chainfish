# ChainFish Platform - 部署说明

## 项目概述
ChainFish是一个现代化的Web3去中心化数字资产交易平台，具有完整的前端界面和用户体验。

## 技术栈
- React 19.1.0
- Vite 6.3.5
- Tailwind CSS
- Shadcn/UI
- Lucide Icons
- React Router

## 部署方式

### 1. Vercel部署
1. 访问 https://vercel.com
2. 导入项目或上传dist文件夹
3. 设置构建命令：`pnpm run build`
4. 设置输出目录：`dist`
5. 点击部署

### 2. Netlify部署
1. 访问 https://netlify.com
2. 拖拽dist文件夹到部署区域
3. 或连接Git仓库自动部署

### 3. Cloudflare Pages部署
1. 访问 https://dash.cloudflare.com
2. 进入Pages页面
3. 上传dist文件夹内容
4. 配置自定义域名（可选）

### 4. GitHub Pages部署
1. 将dist文件夹内容推送到GitHub仓库的gh-pages分支
2. 在仓库设置中启用GitHub Pages
3. 选择gh-pages分支作为源

## 本地开发
```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm run dev

# 构建生产版本
pnpm run build

# 预览构建结果
pnpm run preview
```

## 功能特性
- 🎨 现代化Web3设计风格
- 🌙 深色/浅色主题切换
- 📱 完全响应式设计
- 🌍 国际化支持架构
- 💰 佣金系统集成
- 🔗 Web3钱包连接
- 📊 用户仪表板和数据可视化

## 项目结构
```
dist/                 # 构建输出目录（用于部署）
├── index.html       # 主页面
├── assets/          # 静态资源
│   ├── index-*.css  # 样式文件
│   └── index-*.js   # JavaScript文件
└── ...              # 其他资源文件
```

## 部署注意事项
1. 确保服务器支持SPA（单页应用）路由
2. 配置正确的MIME类型
3. 启用HTTPS（推荐）
4. 配置适当的缓存策略

## 联系信息
如有问题，请联系开发团队。

---
构建时间：2024年8月16日
版本：1.0.0

