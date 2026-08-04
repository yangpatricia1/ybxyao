V8开户平台【Q-——333307——】V8开户平台【 辋芷《888yx●vip》 】
V8开户平台【Q-——333307——】V8开户平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人拥有独立博客？其实利用 GitHub Pages 和 Hexo，你可以在半小时内搭建一个免费、高速、支持自定义域名的静态博客。本教程专为技术新手定制，全程可视化操作，手把手带你完成从环境配置到发布上线的全流程。

 第一步：环境准备与Node.js安装

首先，我们需要本地搭建 Node.js 环境（建议使用14.0及以上版本）。前往官网下载对应系统安装包，安装完成后打开终端（MacOS/Linux用户推荐iTerm2），输入 `node -v` 验证是否安装成功。接下来全局安装Git，并在GitHub官网注册账号——注意，你的用户名将直接决定博客域名地址。

 第二步：快速初始化Hexo博客项目

在桌面新建一个项目文件夹，终端进入该目录后依次运行以下命令：

```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
hexo s
```

当终端显示 `Hexo is running at http://localhost:4000` 时，浏览器访问该地址，恭喜！本地博客已成功运行。此时你会看到默认的Hello World页面，这代表框架搭建全部完成。

 第三步：部署至GitHub Pages全攻略

1. 在GitHub新建一个仓库（Repository），仓库名必须为 `你的用户名.github.io`，注意是强制规则。
2. 修改博客根目录下的 `_config.yml` 文件：找到 `deploy` 参数，修改为如下内容：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 终端执行 `npm install hexo-deployer-git --save` 安装部署插件，然后依次运行 `hexo clean`、`hexo g`、`hexo d`。等待命令行自动上传代码，浏览器访问 `https://你的用户名.github.io`，线上博客即部署完成！

 第四步：主题配置与个性化技巧

想要让博客更具个性？我们可以通过更换主题实现。推荐使用 Fluid 或 Next 主题（下载量超10万，社区维护活跃）。以Fluid为例：

- 终端执行 `git clone https://github.com/fluid-dev/hexo-theme-fluid.git themes/fluid`
- 修改 `_config.yml` 中 `theme: fluid`
- 开启主题的代码高亮、数学公式、字数统计等功能

同时建议修改博客标题、作者信息、添加关于/归档/标签页面。为了更好的SEO收录，每篇文章务必填写 `keywords` 和 `description` 属性。

 第五步：日常写作与发布流程

以后每次写新文章，只需要在 `source/_posts/` 目录下新增 `.md` 文件，文件头部加入以下格式信息：

```yaml
---
title: 文章标题
date: 2025-04-10 12:00:00
tags: [技术, 前端]
categories: 教程
keywords: GitHub,Hexo,博客搭建
description: 本文详细讲解如何使用GitHub Pages部署个人博客
---
```

然后执行 `hexo g && hexo d` 一键发布。

---

❤️ 如果你觉得这篇教程对你有帮助，请顺手点个赞并关注我 — 这会让我更有动力输出更多优质的前端技术教程！如果有任何安装或配置问题，欢迎在评论区留言，我都会逐一解答。建议大家现在就开始动手操作，每遇到一个报错，都意味着你离高手更近了一步。

💡 进阶高阶玩法：搭配腾讯云CDN加速（国内访问速度提升200%）、绑定独立域名、接入Gitalk评论插件——关注我，后续将持续连载“个人博客优化之路”系列实战文章。先收藏这篇文章，操作时随时对照查阅！

相关推荐：

https://github.com/davisgina32/bajxxs/blob/main/2026%E5%AE%98%E7%BD%91%E6%80%BB%E7%BB%93%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E5%B7%B1%E7%82%AF%E5%82%B2%E6%8D%95%E6%B9%8DICIDR.md

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />

相关推荐：

https://github.com/davisgina32/bajxxs/commit/6b99ec29b74a79e8db52e9639022f3ffc4414c48

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />
相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/%E5%BE%9C%E5%BE%89%E6%96%87%E6%B5%B7%E6%8B%BE%E6%A2%A6%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%98%A7%E4%B9%88%E7%BB%9F%E9%93%B0%E4%B9%98SSGMH.md

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />
相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/7b295cabbb1737d3529c3e9b7a05a256048cf190

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
