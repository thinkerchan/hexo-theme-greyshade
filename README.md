# hexo-theme-greyshade
## 前言
greyshade这个主题最早是在[屈光宇大神](https://imququ.com/)的博客看到的，期初是基于Octpress开发的一套主题，当然也在不一样的博客系统中得到了迁移。hexo也自然不例外，当然从极致程度上自然没有屈神优化得好。考虑到原作者也多年未更新，遂在其基础上稍微重构了下。由于本人强迫症，把不需要的东西都删了，所以比起旧版本速度快了挺多。
## 使用
在你的hexo项目themes文件夹中执行：
```bash
 git clone https://github.com/thinkerchan/hexo-theme-greyshade.git //下载好之后将文件夹名字改成greyshade
```

然后对hexo的_config.yaml：
```yaml
theme: greyshade 
```

主题文件夹本身也有一个_config.yaml，按需配置即可

## Todo
hexo主题开发,优化点
* 去除所有不必要的js ✔️
* 去除所有不必要的社交逻辑 ✔️
* 缓存js到localstorage //主要是评论js
* 添加搜索
* 文章页内的前进后退按钮 ✔️
* 图片base64
    * 头像 ✔️
    * 社交icon 
* 归档页 ✔️
* 表格样式修复 ✔️
* 评论 ✔️
* 响应式修复
    * 底部导航条样式 ✔️
    * 顶部页面入口 ✔️
* 简单统计 ✔️