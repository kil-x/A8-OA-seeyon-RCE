# A8-OA-seeyon-RCE
A8-OA-seeyon-RCE
致远 OA A8 无需认证 Getshell 漏洞

致远互联旗下致远 A8+协同管理软件，存在远程 Getshell 漏洞。作为中国协同管理软件及云服务领先厂商，致远 A8+协同管理软件在国内拥有央企、大型公司都有广大的应用。

验证版本： 
A8+V7.0 SP3、A8+ V6.1 SP2 
（V6.1 SP1 验证尚不存在，其他版本未验证） 

触发条件：没有限制。 

上述版本存在Getshell 漏洞。系统某处在无需登录情况下可直接上传任意文件，攻击者一旦上传精心构造的后门文件即可 Getshell，获得目标服务器的权限。目前利用代码已在野外公开，官方提供的补丁程序仍然可利
用。

缓解措施：
1.通过 ACL 禁止外网对“/seeyon/htmlofficeservlet”路径的访问。 
2、官方补丁 
请尽快联系致远官方，索要官方补丁程序。

test123456.jsp名称由来为FILENAME=qfTdqfTdqfTdVaxJeAJQBRl3dExQyYOdNAlfeaxsdGhiyYlTcATdN1liN4KXwiVGzfT2dEg6解密以后，加密方式不详，可能为oa内置加密方式,,有懂加密方式的欢迎一起交流学习。

Thanks
----
* ray
