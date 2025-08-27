本项目是基于**纯静态**的网址导航网站 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 制作的 [Hugo](https://gohugo.io/) 主题，是一个基于 Hugo 的静态响应式网址导航主题。<br/>

## 主题开源地址

[**GitHub**](https://github.com/shenweiyan/WebStack-Hugo) | [**Gitee**](https://gitee.com/shenweiyan/WebStack-Hugo) | [**GitCode**](https://gitcode.com/shenweiyan/WebStack-Hugo)

## 主题演示地址

- 站点：<https://shenweiyan.github.io/WebStack-Demo/>
- 源码：<https://github.com/shenweiyan/WebStack-Demo>


## 特色功能

这是 Hugo 版 WebStack 主题。可以借助下面的平台直接托管部署，无需服务器。
- [Webify](https://webify.cloudbase.net/) | [Netlify](https://app.netlify.com/) | [Cloudflare Pages](https://pages.cloudflare.com) | [Vercel](https://vercel.com) | [Github Pages](https://pages.github.com/)
1. fork本项目
2. 打开 Cloudflare Dashboard → 计算 (Workers) → 创建
3. 点击Pages → 导入现有 Git 存储库 → 授权 GitHub 并选中刚才 Fork 的仓库
4. 项目名称 webstack
    生产分支 main
    构建设置
    框架预设 Hugo
    构建输出目录public
5. 导航的各个信息都集成在 data/webstack.yml 文件中  
    图标在themes/WebStack-Hugo/static/assets/images/logos 文件中 
6.保存部署    