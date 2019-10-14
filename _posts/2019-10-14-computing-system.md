---
layout: post
title:  "The Elements of Computing Systems"
date:   2019-10-14
excerpt: "'밑바닥부터 만드는 컴퓨팅 시스템' 으로 컴퓨팅 시스템 만들기"
project: true
tag:
- Computer Science
- Computing System
- 밑바닥부터 만드는 컴퓨팅 시스템
- The Elements of Computing Systems
- HDL
- Jack
comments: true
---

<div style="clear:left;text-align:left;"><div style="margin:0 0 15px 0;text-align:center;"><a href="http://www.yes24.com/Product/Goods/71129079" style="display:inline-block;overflow:hidden;border:solid 1px #ccc;" target="_blank"><img style="margin:-1px;vertical-align:top;" src="http://image.yes24.com/goods/71129079/M" border="0" alt="밑바닥부터 만드는 컴퓨팅 시스템 "></a></div><div><p style="line-height:1.2em;color:#333;font-size:14px;font-weight:bold;">밑바닥부터 만드는 컴퓨팅 시스템 </p><p style="margin-top:5px;line-height:1.2em;color:#666;"><a href="http://www.yes24.com/SearchCorner/Result?domain=ALL&author_yn=Y&query=&auth_no=255462" target="_blank">노암 니산</a>, <a href="http://www.yes24.com/SearchCorner/Result?domain=ALL&author_yn=Y&query=&auth_no=255463" target="_blank">시몬 쇼켄</a> 저/<a href="http://www.yes24.com/SearchCorner/Result?domain=ALL&author_yn=Y&query=&auth_no=255464" target="_blank">김진홍</a> 역</p><p style="margin-top:14px;line-height:1.5em;text-align:justify;color:#999;">“컴퓨터를 이해하는 가장 좋은 방법은 밑바닥부터 직접 만들어 보는 것이다!”MIT의 컴퓨터 과학 교재로 사용되고 있는 이 책은 단순하지만 강력한 컴퓨터 시스템을 밑바닥부터 직접 구축해 봄으로써 응용 컴퓨터과학에 대한 통합되고 뚜렷한 그림을 그릴 수 있게 해준다. 기본적인 하드웨어 플랫폼과 현대적인 소프트웨어...</p></div></div>

<iframe src="https://ghbtns.com/github-btn.html?user=sslmyo24&repo=computing-system&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>

## 소개
* Fork the [Moon repo](https://github.com/TaylanTatli/Moon/fork)
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder.
* Change repo name to `YourUserName.github.io`

## 목차

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509718/61b09a20-01d6-11e6-8da1-4202ae4d83cd.png
	https://cloud.githubusercontent.com/assets/754514/14509715/61aa9d00-01d6-11e6-81a6-c6837edf2e84.png
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=2 %}      
      
See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.      

## Site Setup
A quick checklist of the files you’ll want to edit to get up and running.    

### Site Wide Configuration
`_config.yml` is your friend. Open it up and personalize it. Most variables are self explanatory but here's an explanation of each if needed:

#### title

The title of your site... shocker!

Example `title: My Awesome Site`

#### bio

The description to show on your homepage.

#### description

The description to use for meta tags and navigation menu.

#### url

Used to generate absolute urls in `sitemap.xml`, `feed.xml`, and for generating canonical URLs in `<head>`. When developing locally either comment this out or use something like `http://localhost:4000` so all assets load properly. *Don't include a trailing `/`*.

Examples:

{% highlight yaml %}
url: http://taylantatli.me/Moon
url: http://localhost:4000
url: //cooldude.github.io
url:
{% endhighlight %}

#### reading_time

Set true to show reading time for posts. And set `words_per_minute`, default is 200.

#### logo
Your site's logo. It will show on homepage and navigation menu. Also used for twitter meta tags.

#### background
Image for background. If you don't set it, color will be used as a background.

#### Google Analytics and Webmaster Tools

Google Analytics UA and Webmaster Tool verification tags can be entered in `_config.yml`. For more information on obtaining these meta tags check [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) and [Bing Webmaster Tools](https://ssl.bing.com/webmaster/configure/verify/ownership) support.

#### MathJax
It's enabled. But if you don't want to use it. Set it false in  `_config.yml`.

#### Disqus Comments
Set your disqus shortname in `_config.yml` to use comments.

---

### Navigation Links

To set what links appear in the top navigation edit `_data/navigation.yml`. Use the following format to set the URL and title for as many links as you'd like. *External links will open in a new window.*

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

- title: Moon
  url: http://taylantatli.me/Moon
{% endhighlight %}

---

## Layouts and Content

Moon Theme use [Jekyll Compress](https://github.com/penibelst/jekyll-compress-html) to compress html output. But it can cause errors if you use "linenos" (line numbers). I suggest don't use line numbers for codes, because it won't look good with this theme, also i didn't give a proper style for them. If you insist to use line numbers, just remove `layout: compress` string from layouts. It will disable compressing.

### Feature Image

You can set feature image per post. Just add `feature: some link` to your post's front matter.

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    
 This also will be used for twitter card:

![Moon Twitter Card](https://cloud.githubusercontent.com/assets/754514/14509719/61c5751c-01d6-11e6-8c29-ce8ccad149bf.png)

### Comments
To show disqus comments for your post add `comments: true` to your post's front matter.

---

## Questions?

Found a bug or aren't quite sure how something works? By all means [file a GitHub Issue](https://github.com/TaylanTatli/Moon/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the MIT License. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer.
