---
home: true
modules:
  - BannerBrand
  - Blog
  - MdContent
  - Footer
bannerBrand:
  bgImage: '/bg.svg'
  title: ZavacのWorld
  description: 编程路漫漫。
  tagline: 那些杀不死我的，还不如直接杀死我。
  buttons:
    - { text: 介绍, link: '/docs/guide/introduce' }
    - {
        text: Default Style,
        link: '/docs/style-default-api/introduce',
        type: 'plain',
      }
  socialLinks:
    - { icon: 'LogoGithub', link: 'https://github.com/Amoryu/amoryu.github.io' }
blog:
  socialLinks:
    - { icon: 'LogoGithub', link: 'https://github.com/recoluan' }
isShowTitleInHome: true
actionText: About
actionLink: /views/other/about
---
## 快速开始

**npx**

```bash
# 初始化，并选择 2.x
npx @vuepress-reco/theme-cli init
```

**npm**

```bash
# 初始化，并选择 2.x
npm install @vuepress-reco/theme-cli@1.0.7 -g
theme-cli init
```

**yarn**

```bash
# 初始化，并选择 2.x
yarn global add @vuepress-reco/theme-cli@1.0.7
theme-cli init
```
