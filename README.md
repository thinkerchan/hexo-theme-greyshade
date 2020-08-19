# hexo-theme-greyshade
## 前言
greyshade这个主题最早是在[屈光宇大神](https://imququ.com/)的博客看到的，最初是基于Octpress开发的一套主题，当然在其他博客系统中得到了迁移, 也包括了HEXO

不过原作者对hexo-theme-greyshade的修改都是六七年前的事情了，基于他的基础，我微重构了下。虽然从极致程度上自然没有屈神优化得好。不过由于本人强迫症，把比较多不需要的东西都删了。样式上也接近屈神用的样式，速度上还是快了挺多的，有兴趣的可以安装。也可以看看运行的[效果](https://thinkerchan.com/)

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
Hexo-theme-greyshade优化点:
* 样式优化 ✔️
* 去除所有不必要的js ✔️
* 去除所有不必要的社交逻辑 ✔️
* ~~缓存js到localstorage~~ (站内js几乎没有,不需要处理)
* 添加搜索 ✔️(站内搜索) // 需要hexo new page search 设置layout: search
* 添加rss ✔️
* 文章页内的前进后退按钮 ✔️
* 图片base64
    * 头像 ✔️
    * 社交icon ✔️
* 归档页 ✔️
* 表格样式修复 ✔️
* 引入第三方评论 ✔️(valine+leancloud)
* 响应式修复 ✔️
    * 底部导航条样式 ✔️
    * 顶部页面入口 ✔️
* 简单统计 ✔️
* CNZZ统计 ✔️
* 专题文章分类(cate) ✔️  // 需要hexo new page catagories， 设置layout: cate
* 新增页面参数 hideDate ✔️ // 隐藏发表日期


## 其他
如果这个主题和教程对你有帮助, 点个star就是坠吼的。当然微信请我喝杯咖啡也很excited的。

![请作者喝咖啡](https://tva1.sinaimg.cn/large/007S8ZIlly1ghvz0177exj30j40hyth5.jpg)