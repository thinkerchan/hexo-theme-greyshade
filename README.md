# hexo-theme-greyshade
## 前言
greyshade这个主题最早是在[屈光宇大神](https://imququ.com/)的博客看到的，期初是基于Octpress开发的一套主题，当然在其他博客系统中得到了迁移, 也包括了HEXO 

不过原作者对hexo-theme-greyshade的修改都是六七年前的事情了，基于他的基础，我微重构了下。虽然从极致程度上自然没有屈神优化得好。不过由于本人强迫症，把比较多不需要的东西都删了。样式上也接近屈神用的样式，速度上还是快了挺多的，有兴趣的可以安装。也可以看看运行的[效果](https://thinkerchan.com/)

如果你对这个主题感兴趣，那就给一个star呗
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
* 缓存js到localstorage 
* 添加搜索
* 添加rss ✔️
* 文章页内的前进后退按钮 ✔️
* 图片base64
    * 头像 ✔️
    * 社交icon ✔️
* 归档页 ✔️
* 表格样式修复 ✔️
* 评论 ✔️
* 响应式修复 ✔️
    * 底部导航条样式 ✔️
    * 顶部页面入口 ✔️
* 简单统计 ✔️
* 专题文章分类(cate) ✔️  // 需要hexo new page catagories， 设置layout: cate
* 新增页面参数 hideDate ✔️ // 隐藏发表日期
