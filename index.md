---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "个人编程技术分享"
  text: "小莫的个人网站"
  tagline: 小莫的个人网站, 用于记录并分享一些可能有用的东西
  actions:
    - theme: brand
      text: 小莫的博客园
      link: https://blog.aoe.top/
    - theme: alt
      text: 小莫的维基库
      link: https://wiki.aoe.top/
    - theme: alt
      text: Gloss Mod Manager
      link: https://gmm.aoe.top/
  image:
    src: "https://mod.3dmgame.com/static/upload/mod/202307/MOD64a7767d0409f.png@webp"
    alt: 'logo'


features:
  - title: 小莫网盘
    link: https://cloud.aoe.top/
    details: 网盘现已更新至 4.0 版本, 采用了全新的设计, 赞助用户可用 WebDAV 挂载、在线解压/压缩 等功能
  - title: 短链生成
    link: https://s.aoe.top/
    details: 基于 short 的一个使用 Cloudflare Pages 创建的 URL 缩短器, 可缩短你分享的链接长度
  - title: 小莫的工具箱
    link: https://tools.aoe.top/
    details: 随心制作一些便利有用的工具
  - title: 小莫的私有云盘
    link: https://pan.aoe.top/
    details: 与『小莫网盘』不一样，这个网盘只有小莫能够发布内容
  - title: 小莫的游戏库
    link: https://game.aoe.top/
    details: 是从 https://pan.aoe.top/Games/ 中分支出来的另一个游戏盘, 但由于某些问题, 该库已停止更新
  - title: 塔罗牌
    link: https://tarot.aoe.top/
    details: 生命是一个无止境的展开的过程。如果我们愿意，它也是一个不断自我发现过程
---



<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>