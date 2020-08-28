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

主题文件夹本身也有一个_config.yaml，按需配置即可:
```yaml
    menu:
    Home: /
    Archives: archives
    cate: cate
    page:   // 只有 archives是自动生成的,其他需要手动配置
        归档: archives
        专题: categories
        友链: friendlinks
        关于: life
        搜索: search

    sidePic: https://tva1.sinaimg.cn/large/007S8ZIlgy1ggdmi6yapmj30dw0zk0wm.jpg // 主题图
    avatar: https://tva1.sinaimg.cn/large/007S8ZIlgy1ggdmr1k3k0j305k05k74j.jpg // 头像

    excerpt_link: 继续阅读
    excerpt: 200 // 提取字数

    social:
        twitter: true
        github: true
        weibo: false
        yuque: true
        rss: true

    twitter:
        username:  用户名

    github:
        username:  用户名

    weibo:
        username: 用户名

    yuque:
        username:  用户名

    # https://www.leancloud.cn/
    valine: 如果需要评论,则需要取leancloud注册并获取以下key
        appId:
        appKey:

    # https://web.umeng.com/
    umeng: 友盟项目id

```
## 创建几个关键页面

### 搜索页
```bash
    $ hexo new page search // 对应生成source/search/index.md
```
然后如下设置:
```
    ---
    title: 站内搜索
    date: 2020-07-24 14:14:06
    hideDate: true
    comments: false
    layout: "search"
    ---
```

### 专题页
```bash
    $ hexo new page categories // 对应生成source/categories/index.md
```
然后如下设置:
```
    ---
    title: 专题阅读
    date: 2020-07-05 15:59:28
    layout: "cate"
    comments: false
    ---
```

### 搜索页
```bash
    $ hexo new page search // 对应生成source/search/index.md
```
然后如下设置:
```
    ---
    title: 站内搜索
    date: 2020-07-24 14:14:06
    hideDate: true
    comments: false
    layout: "search"
    ---
```
## 404页面
``` bash
    $ hexo new page 404 // 对应生成source/404/index.md
```

然后如下设置:
```
    ---
    title: 404 - 没有目标页面
    date: 2020-07-05 15:11:10
    comments: false
    permalink: /404  // 注意这里
    ---
    <style>.meta{display:none!important;}</style>

    检查下url是否拼写错误？或者看看其他文章?
```


## 优化点
Hexo-theme-greyshade:
* 样式优化 ✔️
* 去除所有不必要的js ✔️
* 去除所有不必要的社交逻辑 ✔️
* 缓存js到localstorage ✔️
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

![请作者喝咖啡](https://tva1.sinaimg.cn/large/007S8ZIlgy1ghx3hwqq1sj308c07uglx.jpg)