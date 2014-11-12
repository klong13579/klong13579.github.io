---
layout: post
title: "markdown 语法示例"
date: 2014-11-06 16:51:43 +0800
comments: true 
description: What is octopress and how create and deploy your blog in github pages
categories: Octopress
---
这篇博客是参考[http://markdown.tw/#p][id]<br>
[id]: http://markdown.tw/#p "markdown"
你妈的，找啦这么久原来是这样添加文内容的，靠，你妹
这篇文章展示啦octopress博客中的各种文档形式。
This is a regular paragraph.
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>		return shell_exec("echo $input | $markdown_script");fdfdsfdsjafdsjlfjldskjafljdslajfljdsljfldsjlafjlkdsjafkljdsklfjlkdsjflksjdlakfjdsklfjsdalkj

	this is what
***
1.	Bird
2.  McHale
5.  Parish
1   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.
***
1986\. What a great season.

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

<div class="footer">
        &copy; 2004 Foo Corporation
</div>
需要换行请用"<br\>"<br> 
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

[google]: http://google.com/        "Google"
[yahoo]:  http://search.yahoo.com/  "Yahoo Search"
[msn]:    http://search.msn.com/    "MSN Search"

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

un*frigging*believable
unfriggingbelievable

Use the `printf()` function.
``There is a literal backtick (`) here.``
A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``
Please don't use any `<blink>` tags.
`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

![Alt][id]
[id]: images/email.png  "Optional title attribute"
{% img  images/bird_32_gray.png %}
{% img  images/email.png  %}

<http://example.com/><br>
<klong13579@126.com>

\*fdsfsdaf asterisks\*
<table>
    <tr>
        <td>Foo</td>
    </tr>
		<tr>
        <td>Foo</td>
    </tr>
</table>
Test Code in blog
```python helloworld
int main()
{
 cout<<"hello world"<<endl;
};
```

This is another regular paragraph.
