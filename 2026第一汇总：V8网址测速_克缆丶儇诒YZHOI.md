V8网址测速【Q-——333307——】V8网址测速【 辋芷《888yx●vip》 】
V8网址测速【Q-——333307——】V8网址测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

还在羡慕别人拥有自己的技术博客？其实，利用GitHub Pages和Hexo，你也能在半小时内搭建一个免费、高速、可自定义的博客站点。今天，我就手把手带大家完成从环境配置到部署上线的全过程。

 为什么要用 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 上，无需购买服务器和域名。
- 访问速度快：国内访问速度尚可，且支持绑定自定义域名。
- 版本管理：所有文章和配置都存储在 Git 仓库中，历史记录一目了然。
- 生态丰富：Hexo 拥有海量主题和插件，可以轻松定制页面风格和功能。

 第一步：环境准备

在开始之前，请确保你的电脑上已经安装了 Node.js（建议 14+ 版本）、Git 以及一个代码编辑器（如 VS Code）。安装完成后，打开终端，使用 npm 全局安装 Hexo 命令行工具：

```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目

在你想存放博客的目录下，执行以下命令初始化一个名为 `myblog` 的文件夹：

```bash
hexo init myblog
cd myblog
npm install
```

初始化完成后，你会看到 `_config.yml`（站点配置文件）、`source`（存放文章和页面）以及 `themes`（主题文件夹）。

 第三步：创建文章并预览

在 `source/_posts` 目录下，新建一个 Markdown 文件，例如 `hello-world.md`，并写入一些内容。然后在终端运行：

```bash
hexo generate
hexo server
```

浏览器访问 `http://localhost:4000` 即可预览博客效果。

 第四步：部署到 GitHub Pages

1. 在 GitHub 上新建一个仓库，仓库名必须为 `你的用户名.github.io`。
2. 修改 `_config.yml` 文件中的 `deploy` 配置项，填入你的仓库地址。
3. 安装部署插件 `hexo-deployer-git`，然后执行：

```bash
npm install hexo-deployer-git --save
hexo deploy
```

等待几分钟，访问 `https://你的用户名.github.io` 就能看到你的博客上线了！

 第五步：绑定自定义域名（可选）

如果你有自己的域名，可以在仓库 Settings 的 Pages 设置中，将自定义域名填入，并在 DNS 服务商处添加一条 CNAME 记录指向你的 GitHub 地址。

 遇到问题怎么办？

部署过程中常见的 `Deployer not found` 或端口占用问题，通常是因为插件未安装或环境变量配置错误。欢迎在评论区留言你的问题，我会第一时间为你解答。

搭建博客只是第一步，坚持写作才是关键。如果你觉得这篇教程对你有帮助，不妨点个赞、转发给身边需要的朋友，也欢迎在评论区分享你的博客地址，我们一起交流进步！

相关推荐：

https://github.com/nguyenmark0/dznovc/blob/main/2026%E7%A7%91%E6%8A%80%E8%A7%A3%E6%9E%90%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E7%99%BB%E5%BD%95_%E6%B4%BE%E6%88%91%E6%BA%90%E7%A8%8D%E5%BA%A6FSERY.md

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />

相关推荐：

https://github.com/nguyenmark0/dznovc/commit/9af07bcb56d88a59a3f09b309fed08b633b7c79f

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/%E7%A1%AC%E6%A0%B8%E5%85%A8%E9%98%B6%E6%94%BB%E7%95%A5%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E5%AE%A2%E6%9C%8D_%E9%99%A9%E9%93%B0%E5%88%BA%E8%8D%A3%E6%8E%A0FZSAU.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/commit/93b2c878658515de512acb4266224b04d23be7e8

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
