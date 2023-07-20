# JERRY的旧版Blog

这是Jerry的旧版Blog，由于Hexo的部署和修改过于繁琐，所以新版博客选择了Typecho框架，这个就留给小白作为建站的模板吧。

### 博客采用：

> - Hexo框架，版本6.3.0
> - volantis主题，版本5.7.6

### 博客优点：

> - [x] 无需服务器，支持多平台的部署
> - [x] 自带主题美化和部分主题设置，部署即用

### 博客缺点：

> - [ ] 由于资源较多，加载速度可能不太理想
> - [ ] 部分资源需要自己寻找和配置(详见 #你需要做 )

### 你需要做：

如果你想用这个博客，你需要：

1. 找个合适的平台部署，推荐：

   > - [Vercel](https://vercel.com)：免费，一个Github账号即可，但是自带域名被墙，需要自己买域名，网上的二级域名分发不行。
   > - [4everland](https://4everland.org)：精简版Vercel，免费，目前自带二级域名还能正常访问。
   > - [Render](https://render.com)：免费，自带二级域名正常访问，但是注册需要信用卡。
   > - [Railway](https://railway.app)：免费，自带二级域名正常访问，但是免费版每月只有500小时(约20天)在线时间。

2. 克隆这个仓库，并使用上面的平台部署：

   > - 具体怎么连接Github自己上网搜索。
   >
   > - 部署时，安装代码(Install Command)里写：
   >
   >   ```bash
   >   npm install hexo-renderer-marked && npm uninstall hexo-generator-index && npm install hexo-generator-index-pin-top
   >   ```
   >
   > - 部署完成预览效果

3. 如果部署成功，你还需要：

   > - 配置首页背景图，在主题 `_config.yml` 约 `121` 行位置，自己设置一张背景图，因为原API已跑路。
   > - 配置评论，在主题 `_config.yml` 约 `477` 行位置，建议使用 [Waline](https://waline.js.org) 部署教程看文档。如果不想评论，直接删掉，没影响。

4. 友情提醒：

   > - 主题文档：https://volantis.js.org
   > - Hexo官网：https://hexo.io/zh-cn/docs/index.html
   > - 主题设置：主题目录 `_config.yml` ，东西有点多，需要花时间慢慢看，替换内容可以使用记事本搜索功能。
   > - 自定义添加的js等在 `主题文件夹\source\` 里面，HTML代码写在 `主题文件夹\layout\layout.ejs` 等ejs文件。
   > - 作者信息都存在 `根目录source\_data\author.yml` 里，文章在 `根目录source\_post` 里，独立页面就新建个页面名称文件夹，然后index.md里写内容。
   > - 删除文章直接删除文件，新建文章需要在根目录打开 `Git Bash` ，敲命令行 `hexo new 文章名` 。
   > - 首次使用 `Git Bash` 需要装好 `node.js` 和 `git` ，网上有详细装运行库方法，如果频繁报错，下载仓库里的运行库压缩包解压，再导入仓库里其它文件，如果有重复，保留仓库里的文件而不是运行库压缩包里的文件，再敲命令行 `hexo init` 。
   > - 如果要在本地预览，敲命令行 `hexo s` ，会输出预览地址 按 `Ctrl+C` 退出预览。
   > - 文章建议使用 `Typora` 写。
   > - 写完上传Github，一般会自动更新。

### 结语：

希望这个项目可以帮助小白快速搭建博客，有问题可以来 [BiliBili](https://space.bilibili.com/702028797) 找我询问(我也没有完全研究透，不保证全都知道)。

2022.10.23~2023.07.20，再见，Hexo，再见，旧时光。
