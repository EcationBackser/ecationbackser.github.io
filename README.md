# BNPBlog

## 【公告】停止对 BNPStore 的维护
<i>Nov 27th, 2021</i>

一切来的太快。今天（2021年11月27日），BNPSoft将暂停对 BNPStore（BNPStore for Chinese）的维护。日程安排如下：

2021年11月27日：作出停止维护的计划，并删除在官网上对 BNPStore 的链接。
2021年11月30日：停止对网站客服的维护。
2021年12月10日：停止对网站支付接口的维护。
2021年12月30日：用户将无法访问控制台。
2022年01月01日：网站关停。



## 【公告】云业务——BNPAir正式启用！
<i>Nov 27th, 2021</i>

BNPAir是BNPSoft开发的一款快传业务。我们秉承“网络投递新时代”的想法，制作了这个服务。

### 如何？
您只需要访问 https://air.bnpo.xyz/，然后点击 “选择文件”，接着选择“提交”按钮。您的文件就会被我们存储到内部服务器中。

### 怎样获取？
要访问或下载这些文件也很简单。在上传完文件后，我们会将您重定向到 upload.php。该页面会显示您文件的信息，以及文件是否被成功上传。成功上传代码显示“100”，否之显示“400”。同时，若遇其它错误，我们将会显示不同的错误码。

这里，我们将会给出所有您可能遇到的错误码，以对应。

· 错误码：ERR: FI_TOO_BIG；释义：文件过大。

· 错误码：ERR: FI_PART_UL；释义：仅部分文件被上传。

· 错误码：ERR: FI_NO_UL；释义：文件因不明原因未被上传。

· 错误码：ERR: FI_UNKNOWN_SIZE；文件大小不明。
