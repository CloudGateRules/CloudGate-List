# CloudGate-List
>注意:<code>2017-02-08 GMT 9:00</code>之前Fork都需要重新删除掉再Fork,因为新增了USERAGENT模块和General模块,可以自定义,缺少会报错的!!!或者自己在Fork里面上传这两个模块!
## 关于提交规则:
>禁止提交(色情/政治/无法打开/赌博/邪教/Shadowsocks站点),不符合的将会进行删除,提交后会自动进行扫描websitetitle or statuscode除包含以上内容外的都可以提交!
## 关于如何使用:
>简单的描述一下,首先你需要Fork一下本项目,当然你也可以使用其他人的规则列表!<br>
>紧接着你可以访问以下地址下载属于你的自定义规则或者修改规则列表文件如:<br>
>本参数全局均可使用,无论是Basic还是Advanced or Cloud规则<br>
><code>https://{项目地址}/{目录}/{规则}.php?List=https://raw.githubusercontent.com/{Github用户名}/CloudGate-List/master/Rule/</code>
<br>
><code>https://async.be/Rule/Basic/Surge.php?List=https://raw.githubusercontent.com/lhie1/CloudGate-List/master/Rule/</code>
<br>
>可以在参数的结尾用'&'符连接其他参数,参数不区分顺序,所有规则都可以使用'List'功能!<br>
>禁止添加"大文件"即524288字节(512KB)以上的,所有大文件将会被拒绝!<br>
>规则列表的格式不同于规则格式,如下列格式:<br>
>Proxy(Advanced/Basic):<code>DOMAIN,0rz.tw or DOMAIN-SUFFIX,0rz.tw</code><br>
>DIRECT:<code>DOMAIN,126.net or DOMAIN-SUFFIX,126.net</code><br>
>Default(Apple):<code>DOMAIN,apple.com or DOMAIN-SUFFIX,apple.com</code><br>
>IPCIDR:<code>91.108.56.0/22,Proxy or 91.108.56.0/22,DIRECT or 91.108.56.0/22,REJECT</code><br>
>KEYWORD:<code>aka,Proxy or aka,DIRECT or aka,REJECT</code><br>
>Other:<code>GEOIP,CN,DIRECT | FINAL,Proxy</code><br>
>Rewrite:<code>^http://burpsuite.site https://burpsuite.site 302</code><br>
>REJECT:<code>DOMAIN,128.net or DOMAIN-SUFFIX,128.net</code><br>
>还有很多我就不一一举例子了,常用的就是这些!...<br>
