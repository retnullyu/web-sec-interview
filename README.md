 # web-sec-interview
 - [ ] 介绍一下自认为有趣的挖洞经历（或CTF经历）
 - [ ] 你平时用的比较多的漏洞是哪些？相关漏洞的原理？以及对应漏洞的修复方案？
 - [ ] xss漏洞打到后台登陆地址为内网IP,你会如何处理？
 - [ ] 说说常见的中间件解析漏洞利用方式  
 - [ ] java反序列化漏洞的原理?解决方案?
 - [ ] 如果一台服务器被入侵后,你会如何做应急响应?
 - [ ] 你平时使用哪些工具?以及对应工具的特点?
 - [ ] 如果遇到waf的情况下如何进行sql注入/上传Webshell怎么做？请写出曾经绕过WAF的经过(SQLi，XSS，上传漏洞选一) 
  - [我的WafBypass之道（SQL注入篇）] https://xz.aliyun.com/t/368
  - [我的WafBypass之道（Upload篇）] https://xz.aliyun.com/t/337
  - [ 我的WafBypass之道（Misc篇）] https://xz.aliyun.com/t/265
 - [ ] 介绍 SQL 注入漏洞成因，如何防范？注入方式有哪些？除了数据库数据，利用方式还有哪些？
 - [ ] 如何防范 XSS 漏洞，在前端如何做，在后端如何做，哪里更好，为什么？
 - [ ] 如何绕过CDN获取目标网站真实IP，谈谈你的思路？  
 - [ ] 如果给你一个网站,你的渗透测试思路是什么?
 - [ ] 谈一谈Windows系统与Linux系统提权的思路？  
 - [ ] Windows、Linux、数据库的加固降权思路，任选其一  
 - [ ] 列举出您所知道的所有开源组件高危漏洞(十个以上)  
 - [ ] 反弹 shell 的常用命令？一般常反弹哪一种 shell？为什么？
 - [ ] 描述一个你深入研究过的 CVE 或 POC。
 - [ ] CSRF 和 XSS 和 XXE 有什么区别，以及修复方式？ 
 - [ ] CSRF、SSRF和重放攻击有什么区别？ 
 - [ ] 说出至少三种业务逻辑漏洞，以及修复方式？ 
 - [ ] 发现 demo.jsp?uid=110 注入点，你有哪几种思路获取 webshell，哪种是优选？ 
 - [ ] 以下链接存在 sql 注入漏洞，对于这个变形注入，你有什么思路？ 
demo.do?DATA=AjAxNg== 
 - [ ] CMD命令行如何查询远程终端开放端口
 - [ ] 服务器为IIS+PHP+MySQL，发现root权限注入漏洞，讲讲你的渗透思路  
 - [ ] 说出XSS的三种类型，且在过滤”<>”号下如何绕过  
 - [ ] 请写出Mysql5数据库中查询库’helloworld’中’users’表所有列名的语句  
 - [ ] 下面这段代码存在漏洞吗？如果存在请说出存在什么漏洞并利用  
 
> http://www.exp.com/1.php  

> <?php  

> $s_func = $_GET[‘s_func’];

> $info = $_GET[‘info’];

> $s_func($info);

> ?>

 - [ ] 菜刀被waf拦截后要怎么处理?
 - [菜刀HTTP流量中转代理过WAF] https://xz.aliyun.com/t/2739
