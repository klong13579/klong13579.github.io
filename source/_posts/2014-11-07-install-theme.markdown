---
layout: post
title: "install-theme"
date: 2014-11-07 17:28:14 +0800
comments: true
categories: octopress
---

##How to install octopress theme

```html octopress
cd octopress
git clone git@github.com:tommy351/Octopress-Theme-Slash.git .themes/slash
rake install['slash']
rake generate
```
{% blockquote %}
 这个主要是显示名人名言， Stay hungrey, Stay foolish 
																									---- Steve jobs
{% endblockquote %}

{% pullquote %}
这个是用来做简要说明，醒目。Surround your paragraph with the pull quote tags. Then when you come to
the text you want to pull, {" surround it like this "} and that's all there is to it.
{% endpullquote %}

{% img http://placekitten.com/890/280 %}
{% img left http://placekitten.com/320/250 Place Kitten #2 %}
{% img right http://placekitten.com/300/500 150 250 Place Kitten #3 %}
{% img right http://placekitten.com/300/500 150 250 'Place Kitten #4' 'An image of a very cute kitten' %}

{% img images/email.png %}
{% img images/touxiang.jpg %}
