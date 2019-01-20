---
layout: post
title:  "Twitter @HuazhongUST 的开发思路"
date:   2019-01-19 06:16:22 +0800
categories: education
---

前几天发现Twitter上并没有母校的账号，于是准备注册一个，然后爬新闻发上去。爬虫是利用[beautifulsoup4](https://pypi.org/project/beautifulsoup4/)做网页解析，代码已经发布到[Github](https://github.com/liruqi/sina/)。

爬到内容之后，发布到Twitter有点麻烦。这几年Twitter API的限制越来越多，我尝试在开发者平台创建应用，需要人工审核，几天后被[无情拒绝](https://twitter.com/HuazhongUST/status/1085415385179086852)。于是尝试用IFTTT从[Telegram频道](https://t.me/HuazhongUST)同步到Twitter上。因为Telegram的API非常友好和方便。

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
