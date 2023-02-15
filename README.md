
1
<?xml version="1.0" encoding="UTF-8" ?>
2
<!DOCTYPE html>
3
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
4
<head>
5
<meta content='width=device-width, initial-scale=1' name='viewport'/>
6
<b:include data='blog' name='all-head-content'/>
7
<b:if cond='data:blog.pageType == &quot;index&quot;'>
8
<title><data:blog.pageTitle/></title>
9
<b:else/>
10
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
11
<title><data:blog.pageName/></title>
12
</b:if></b:if>
13
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
14
<title>Page Not Found - <data:blog.title/></title>
15
</b:if>
16
<include expiration='7d' path='*.css'/>
17
<include expiration='7d' path='*.js'/>
18
<include expiration='3d' path='*.gif'/>
19
<include expiration='3d' path='*.jpeg'/>
20
<include expiration='3d' path='*.jpg'/>
21
<include expiration='3d' path='*.png'/>
22
<link expr:href='data:blog.url' rel='dns-prefetch'/>
23
<link href='https://www.google-analytics.com/' rel='dns-prefetch'/>
24
<link href='https://pagead2.googlesyndication.com/' rel='dns-prefetch'/>
25
<link href='https://www.facebook.com/' rel='dns-prefetch'/>
26
<link href='https://static.xx.fbcdn.net/' rel='dns-prefetch'/>
27
<link href='https://www.googletagservices.com/' rel='dns-prefetch'/>
28
<link href='https://apis.google.com/' rel='dns-prefetch'/>
29
<link href='https://ajax.googleapis.com/' rel='dns-prefetch'/>
30
<link href='https://fonts.gstatic.com/' rel='dns-prefetch'/>
31
<link href='https://maxcdn.bootstrapcdn.com/' rel='dns-prefetch'/>
32
<link href='https://www.blogger.com' rel='dns-prefetch'/>
33
<link href='https://fonts.googleapis.com/' rel='dns-prefetch'/>
34
<link href='https://1.bp.blogspot.com/' rel='dns-prefetch'/>
35
<link href='https://2.bp.blogspot.com/' rel='dns-prefetch'/>
36
<link href='https://3.bp.blogspot.com/' rel='dns-prefetch'/>
37
<link href='https://4.bp.blogspot.com/' rel='dns-prefetch'/>
38
<link href='https://googleads.g.doubleclick.net/' rel='dns-prefetch'/>
39
<link href='https://secure.rating-widget.com' rel='dns-prefetch'/>
40
​
41
<b:skin><![CDATA[
42
/*
43
Theme Name      :  Moview
44
Theme Designer  :  MS Design
45
Designer URL    :  http://msdesignbd.com
46
Publisher       :  Template Market
47
Publisher URL   :  http://templatemark.com
48
====================================================================
