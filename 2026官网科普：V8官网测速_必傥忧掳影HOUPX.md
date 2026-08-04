V8官网测速【Q-——333307——】V8官网测速【 辋芷《888yx●vip》 】
V8官网测速【Q-——333307——】V8官网测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是否想过拥有一个完全属于自己的博客，却苦于服务器成本和维护麻烦？GitHub Pages 免费托管 + Hexo 极速建站的组合，正是开发者最青睐的解决方案。本文为你梳理从环境配置到一键部署的全流程，建议收藏。

 为什么选择 Hexo + GitHub Pages？

- 零成本：代码托管在 GitHub，无需购买服务器
- 极速访问：依托 GitHub CDN，国内访问速度尚可（可绑定自定义域名）
- 高度可定制：支持主题更换、插件扩展，Markdown 写作体验极佳
- SEO 友好：生成的纯静态页面，更适合百度等搜索引擎抓取

 第一步：环境准备

在开始前，请确保本地已安装 Node.js（建议 v18+）和 Git。打开终端，输入以下命令验证：

```bash
node -v && git --version
```

 第二步：安装并初始化 Hexo

```bash
npm install -g hexo-cli
hexo init my-blog && cd my-blog
npm install
```

完成后，运行 `hexo s` 即可在 http://localhost:4000 预览默认博客。

 第三步：连接 GitHub 仓库

1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`
2. 修改根目录 `_config.yml`，在末尾填入：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

 第四步：一键部署

安装部署插件，然后生成并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

浏览器访问 `你的用户名.github.io`，博客已上线！

 进阶优化建议

- 绑定域名：在仓库 Settings 中配置 CNAME 记录，提升品牌辨识度
- 更换主题：推荐 NexT 或 Butterfly，在 GitHub 搜索关键词即可找到
- 添加百度统计：在主题配置中填入百度统计 ID，了解访客行为

---

互动引导：你在搭建博客时最卡在哪一步？是环境配置还是部署失败？欢迎在评论区留言，我看到会逐一回复。如果这篇文章有帮助，点赞和转发将鼓励我继续输出更多实战教程！

关注我，获取更多关于前端开发、效率工具的开源干货。下期预告：如何用 Vercel 白嫖部署 API 服务？

相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/2026%E6%9D%83%E5%A8%81%E7%9B%98%E7%82%B9%EF%BC%9AV8%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95_%E6%80%9D%E7%9B%9F%E5%A5%94%E9%A2%87%E5%B1%8EDKESY.md

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />

相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/39a5aac979acbb1930b3e9192b589bb0924c0309

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/%E4%BF%9D%E5%A7%86%E5%AE%9E%E6%93%8D%E6%94%BB%E7%95%A5%EF%BC%9AV8%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E7%9B%BC%E6%88%BF%E9%B2%81%E6%A3%95%E6%BD%9ERYAUW.md

<img src="https://i.postimg.cc/nzw2jbGZ/V8-00006.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/commit/837d9b049e7a6d1d4c7a384224160c8b335941c8

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
