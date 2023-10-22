# 小柒的图床   
>**所需工具**  
>- 图床选择：[GitHub](https://github.com)  
>- 图床上传【 PicGo 、 PicX（任选其一）】： [PicGo官网](https://molunerfinn.com/PicGo/) | [PicGo-GitHub](https://github.com/Molunerfinn/PicGo)  /  [PicX官网](https://picx.xpoet.cn/) | [PicX-GitHub](https://github.com/XPoet/picx)    
>- 图床加速工具【 jsDelivr 、 Statically （任选其一）】： [jsDelivr官网](https://www.jsdelivr.com/) | [jsDelivr-GitHub](https://github.com/jsdelivr/jsdelivr)  /  [Statically官网](https://statically.io/) | [Statically-GitHub](https://github.com/staticallyio/statically)     

>**GitHub加速**  

> ***访问***：  
  >-  工具&加速器：  [Watt Toolkit（原steam++）(推荐)](https://steampp.net/) | [1.1.1.1-WARP-CloudFlare-APP(推荐)](https://1.1.1.1/zh-Hans/) | [FastGitHub](https://github.com/dotnetcore/FastGithub) | [dev-sidecar](https://github.com/docmirror/dev-sidecar)
  >-  修改host：[GitHub520(推荐)](https://github.com/521xueweihan/GitHub520) | [1.1.1.1-WARP-CloudFlare-DNS(推荐)](https://1.1.1.1/zh-Hans/dns/) | [hosts@ineo6](https://github.com/ineo6/hosts) | [gitHub-hosts](https://github.com/isevenluo/github-hosts)
  >-  代理：无推荐
  >-  脚本/插件：无推荐  
        
>***下载***
  >- [脚本-GitHub增强-高速下载](https://greasyfork.org/zh-CN/scripts/412245)
  >- [GitHub-文件夹下载](https://greasyfork.org/en/scripts/434592)

>***优化***
>- [GitHub-web-IDE](https://chrome.google.com/webstore/detail/github-web-ide/adjiklnjodbiaioggfpbpkhbfcnhgkfe)
>- [目录提纲](https://chrome.google.com/webstore/detail/smart-toc/lifgeihcfpkmmlfjbailfpfhbahhibba)
>- [GitHub目录树](https://chrome.google.com/webstore/detail/gitako-github-file-tree/giljefjcheohhamkjphiebfjnlphnokk)
>- [GitHub汉化插件](https://greasyfork.org/zh-CN/scripts/407485)
>- [GitHubDesktop汉化](https://github.com/robotze/GithubDesktopZhTool)

---

## picgo项目 

**[PicGo](https://molunerfinn.com/PicGo): 一个用于快速上传图片并获取图片 URL 链接的工具**

>[PicGo-GitHub](https://github.com/Molunerfinn/PicGo) | [PicGo-官网](https://molunerfinn.com/PicGo/) | [PicGo指南](https://picgo.github.io/PicGo-Doc/) | [PicGo插件](https://github.com/PicGo/Awesome-PicGo)

### 特色功能

- 支持拖拽图片上传
- 支持快捷键上传剪贴板里第一张图片
- Windows 和 macOS 支持右键图片文件通过菜单上传 (v2.1.0+)
- 上传图片后自动复制链接到剪贴板
- 支持自定义复制到剪贴板的链接格式
- 支持修改快捷键，默认快速上传快捷键：`command+shift+p`（macOS）| `control+shift+p`（Windows\Linux)
- 支持插件系统，已有插件支持 Gitee、青云等第三方图床
  - 更多第三方插件以及使用了 PicGo 底层的应用可以在 [Awesome-PicGo](https://github.com/PicGo/Awesome-PicGo) 找到。欢迎贡献！
- 支持通过发送 HTTP 请求调用 PicGo 上传（v2.2.0+)

### 下载安装

| 下载源  | 地址/安装方式  | 平台 | 备注  |
|---|---|---|---|
| GitHub Release  | https://github.com/Molunerfinn/PicGo/releases | All | 国内下载速度可能会慢 |
| [腾讯云COS](https://cloud.tencent.com/product/cos)  | https://github.com/Molunerfinn/PicGo/releases 附在更新日志结尾 | All | 感谢 [腾讯云COS](https://cloud.tencent.com/product/cos) 提供的赞助支持 |
| [山东大学镜像站](https://mirrors.sdu.edu.cn/) | https://mirrors.sdu.edu.cn/github-release/Molunerfinn_PicGo | All | 感谢 [山东大学镜像站](https://mirrors.sdu.edu.cn/) 提供的镜像支持 |
| [Scoop](https://scoop.sh/) | `scoop bucket add extras` & `scoop install picgo` | Windows | 感谢 @huangnauh 和 @Gladtbam 的贡献 |
| [Chocolatey](https://chocolatey.org/) | `choco install picgo` | Windows | 感谢 @iYato 的贡献 |
| [Homebrew](https://brew.sh/) | `brew install picgo --cask` | macOS | 感谢 @womeimingzi11 的贡献 |
| [AUR](https://aur.archlinux.org/packages/yay) | `yay -S picgo-appimage` | Arch-Linux | 感谢 @houbaron 的贡献 |

---

## PicX项目

**[PicX](https://picx.xpoet.cn)** 是一款基于 GitHub API 开发的图床工具，提供图片上传托管、生成图片链接和常用图片工具箱服务。

>[PicX官网](https://picx.xpoet.cn) | [PicX-GitHub](https://github.com/XPoet/picx) | [PicX指南](https://picx-docs.xpoet.cn)

---

### PicX亮点 | Highlights

- 在线使用，无需下载，无需安装。
- 操作简单，文档完善，持续维护。
- 代码开源，数据安全，免费使用。

### 功能 | Features

- [x] 支持 **[拖拽](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E6%8B%96%E6%8B%BD%E5%9B%BE%E7%89%87)**、**[复制粘贴](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E5%A4%8D%E5%88%B6%E7%B2%98%E8%B4%B4)**、**[选择文件](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E9%80%89%E6%8B%A9%E6%96%87%E4%BB%B6)** 等方式进行选择图片
- [x] 支持图片 **[重命名](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E9%87%8D%E5%91%BD%E5%90%8D)**、**[哈希化](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E5%93%88%E5%B8%8C%E5%8C%96)**（确保图片名唯一）和 **[设置命名前缀](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E5%89%8D%E7%BC%80%E5%91%BD%E5%90%8D)**
- [x] 支持 **批量上传图片**、**[批量删除图片](https://picx-docs.xpoet.cn/usage-guide/management.html#%E5%88%A0%E9%99%A4-%E6%89%B9%E9%87%8F%E5%88%A0%E9%99%A4)** 和 **[批量复制图片链接](https://picx-docs.xpoet.cn/usage-guide/management.html#%E5%A4%8D%E5%88%B6-%E6%89%B9%E9%87%8F%E5%A4%8D%E5%88%B6%E9%93%BE%E6%8E%A5)**
- [x] 支持图床 **多级目录** 管理 （创建多级目录 / 查看多级目录下图片）
- [x] 支持 **[一键复制](https://picx-docs.xpoet.cn/usage-guide/upload.html#%E5%A4%8D%E5%88%B6%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5)** 图片链接和 **[自由转换 Markdown / HTML / BBCode 格式](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E6%A0%BC%E5%BC%8F%E8%AE%BE%E7%BD%AE)**
- [x] 内置 **[多种图片链接规则](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E9%80%89%E6%8B%A9%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E8%A7%84%E5%88%99)**（Staticaly、jsDelivr、ChinaJsDelivr 等）
- [x] 支持 **[自定义配置图片链接规则](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E9%85%8D%E7%BD%AE%E8%87%AA%E5%AE%9A%E4%B9%89%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E8%A7%84%E5%88%99)**
- [x] 支持 **[图片压缩](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E5%8E%8B%E7%BC%A9%E8%AE%BE%E7%BD%AE)** (内置高效压缩算法，可配置在上传前自动压缩)
- [x] 支持配置 **[图片水印](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E6%B0%B4%E5%8D%B0%E8%AE%BE%E7%BD%AE)**
- [x] 支持 **PWA**
- [x] 支持 **[暗夜模式](https://picx-docs.xpoet.cn/usage-guide/settings.html#%E4%B8%BB%E9%A2%98%E8%AE%BE%E7%BD%AE)** (自动切换 / 自由切换)
- [x] i18n（中文简体、中文繁体、英文）
- [x] 工具箱（[图片压缩](https://picx-docs.xpoet.cn/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E5%8E%8B%E7%BC%A9)、[图片转 Base64](https://picx-docs.xpoet.cn/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E8%BD%AC-base64)、[图片水印](https://picx-docs.xpoet.cn/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E6%B0%B4%E5%8D%B0)）

---

## 参考文章
- [GitHub极简教程@奔跑中的奶酪](https://www.runningcheese.com/awesome-github)
- [GitHub图床@wu529778790](https://github.com/wu529778790/image)  
- [小程序白嫖CDN图床，利用GitHub+jsDelivr 搭建免费图床（CDN图床）](https://www.cnblogs.com/rzkwz/p/17433027.html)  
- [GitHub + PicGo 搭建一个属于自己的图床](https://www.imooc.com/article/336710)
- [Cloudflare反向代理](https://github.com/gaboolic/cloudflare-reverse-proxy)
- [vercel反向代理](https://github.com/gaboolic/vercel-reverse-proxy)
