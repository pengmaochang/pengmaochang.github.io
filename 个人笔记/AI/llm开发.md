---
layout:       post
title:        "使用指南"
author:       "彭彭"
header-img: "img/image4.png"
tags:
    - github
---

# 发表笔记
# MD笔记
1. 前往post路径
2. 新增一个以时间开头的md文件
3. 在开头添加下列注释：
   ```
    ---
    layout:     post
    title:      "如何看待微信屏蔽快的打车事件？"
    subtitle:   "恰有小感。"
    date:       2014-12-13
    author:     "Peng"
    header-img: "img/post-bg-kuaidi.jpg"
    tags:
        - 知乎
        - 产品
    ---
   ```
4. 有图片的，直接在编写是黏贴，会默认把图片放到当前路径下
5. 全部编写完毕后，需要把图片剪切到img文件夹，并更新md里的路径：ctrl+f，把`](/`替换成`](/img/`
6. 提交代码即可
   
# HTML笔记
1. 前往post路径
2. 获取html文件，例如在md中右键打印为html
3. 删掉最头的html文件声明`<!DOCTYPE html>`
4. 增加上述的文章注释
5. 修改图片的连接：ctrl+f，把`file:////`替换成空

# 新增目录
1. 在post以外的路径，新增md或html文件，做法和上述相同