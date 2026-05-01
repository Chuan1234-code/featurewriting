文件结构说明
===========

dingchuan/
├── index.html       — 主网页文件
├── style.css        — 所有样式
└── images/          — 把图片放在这个文件夹里，文件名如下：

    federer.jpg      → Landing 页背景（费德勒照片）
    my_photo.jpg     → About 页和 Contact 页的个人照片
    work1.jpg        → 工作记录1（温布尔登）
    work2.jpg        → 工作记录2（网球媒体见面会）
    work3.jpg        → 工作记录3（WTA Finals 深圳）
    work4.jpg        → 工作记录4（亚运会）

文章图片（Portfolio 用，可以用上面的工作照，也可以换别的）：
    article1.jpg     → 文章一配图
    article2.jpg     → 文章二配图
    article3.jpg     → 文章三配图

修改文章内容：
打开 index.html，找到 "Article data" 注释，
直接修改 articles 数组里的 title / outlet / desc / body / link 即可。

修改联系方式：
在 index.html 搜索 "your@email.com" 等占位符替换成真实信息。
