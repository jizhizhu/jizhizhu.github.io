---
layout: page
title: 关于
permalink: about.html
image: /public/images/desert.jpg
order: 5
---

{% if site.author.photo %}
![{{ site.author.name }}]({{ site.author.photo | prepend: site.cdnurl }}){:.me}
{% endif %}


这里是jizhizhu的blog。

## 联系我

laixin123@gmail.com 

## 致谢

我的博客使用 Jekyll 搭建，源码托管在 [Github](https://github.com/jizhizhu/jizhizhu.github.io){:target="_blank"}。
感谢 [饮冰先生](https://github.com/myanbin/myanbin.github.io){:target="_blank"} 以及[魔王不造反](https://github.com/biezhi/blog){:target="_blank"},我的博客就是基于他们的版本改造而来。



<!-- Add Disqus Comments -->
{% if site.disqus %}
{% include disqus.html %}
{% endif %}