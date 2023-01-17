---
doc_type: hypothesis-highlights
url: >-
  https://github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md
---

# datawhalechina/daily-interview: Datawhale成员整理的面经，内容包括机器学习，CV，NLP，推荐，开发等，欢迎大家star

## Metadata
- Author: [github.com]()
- Title: datawhalechina/daily-interview: Datawhale成员整理的面经，内容包括机器学习，CV，NLP，推荐，开发等，欢迎大家star
- Reference: https://github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md
- Category: #article

## Page Notes
## Highlights
- 查询 DNS，检查域名是否在缓存中 — [Updated on 2022-02-27 15:30:50](https://hyp.is/7SkYcJeeEeyrCt-hXUJkcA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation
    - Annotation: 检查浏览器dns缓存、系统、host文件缓存。都没有找到则向本地dns服务器发送请求。由本地dns服务器在缓存中查找没有的话，迭代的向顶级域名、根域名、主域名服务器查找ip。
- 避免历史错误连接的建立，减少通信双方不必要的资源消耗 — [Updated on 2022-02-27 15:33:32](https://hyp.is/kPtT0pefEeyrDiM7oq0oPQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 无法避免历史错误连接的初始化，浪费接收方的资源 — [Updated on 2022-02-27 15:33:49](https://hyp.is/mqQTxJefEeyYpdexMKafjA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 点对点单播，不支持多播、广播 — [Updated on 2022-02-27 15:44:37](https://hyp.is/HWDqopehEey07rfiaEyH0A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 流量控制和拥塞控制 — [Updated on 2022-02-27 15:44:40](https://hyp.is/Huj3opehEey63tMh5ADEcg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 无连接的协议，提供无连接服务 — [Updated on 2022-02-27 15:44:48](https://hyp.is/I9dSpJehEey5Ui8tNp0NJg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- TPDU是 UDP报文或用户数据报 — [Updated on 2022-02-27 15:44:56](https://hyp.is/KDjumJehEeyoa8sU7WfMOg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 数据单元TPDU是 TCP报文 — [Updated on 2022-02-27 15:45:00](https://hyp.is/KslmppehEey3XtdY9B_sSQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 应用数据被分割成 TCP 认为最适合发送的数据块 — [Updated on 2022-02-27 15:45:11](https://hyp.is/MYZTAJehEey5WmdmhK2Eyg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- TCP 给发送的每一个包进行编号，接收方对数据包进行排序，把有序数据传送给应用层 — [Updated on 2022-02-27 15:45:19](https://hyp.is/Ndx7jJehEeyj9nsczHYEyw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 校验和 — [Updated on 2022-02-27 15:45:36](https://hyp.is/QHezcpehEeyfbUPb0Ftz_A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- TCP 将丢弃这个报文段和不确认收到此报文段 — [Updated on 2022-02-27 15:45:38](https://hyp.is/QV70CJehEeyuKrMKiagsxw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 能提示发送方降低发送的速率，防止包丢失 — [Updated on 2022-02-27 15:46:19](https://hyp.is/WeEc6pehEey31xc9Flg_xw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 滑动窗口协议 — [Updated on 2022-02-27 15:46:23](https://hyp.is/XJn3VJehEey2Zt-I-Hnh9Q/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 网络拥塞时，减少数据的发送 — [Updated on 2022-02-27 15:46:27](https://hyp.is/XnbXzJehEeyYqUfKUcE4qw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 如果不能及时收到一个确认，将重发这个报文段。 — [Updated on 2022-02-27 15:46:42](https://hyp.is/Z8RprJehEeyobXurSqOU1w/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- ARQ协议 — [Updated on 2022-02-27 15:46:45](https://hyp.is/ablMoJehEey1EnukG30Fjw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 发送窗口的上限为接受窗口和拥塞窗口中的较小值 — [Updated on 2022-02-27 15:47:50](https://hyp.is/kGLkdJehEeyvCGObAOd0uA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 只有当发送方发送并收到确认之后 — [Updated on 2022-02-27 15:47:55](https://hyp.is/kuURkJehEey5XK9Mf7TGzQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- ​ 	Cookie是服务器发送到用户浏览器并保存在本地的一小块数据 — [Updated on 2022-02-27 16:36:48](https://hyp.is/Z4hC6peoEeya7GOtRhMZvQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 同一服务器再发起请求时被携带并发送到服务器上 — [Updated on 2022-02-27 16:36:58](https://hyp.is/bVe6FpeoEeyofltKUV5hVw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 两个请求是否来自同一浏览器，如保持用户的登录状态 — [Updated on 2022-02-27 16:37:07](https://hyp.is/cndn5JeoEey37E9BjCyskQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- ​ 	Session 代表着服务器和客户端一次会话的过程 — [Updated on 2022-02-27 16:37:18](https://hyp.is/eSafnJeoEeyoQAtSq1MRIw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 这样，当用户在应用程序的 Web 页之间跳转时，存储在 Session 对象中的变量将不会丢失 — [Updated on 2022-02-27 16:37:26](https://hyp.is/fj1z6JeoEeyz-tPZWVi1fw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 当客户端关闭会话，或者 Session 超时失效时会话结束。 — [Updated on 2022-02-27 16:37:32](https://hyp.is/gcSUppeoEeyz23-DyV0nuA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- Cookie 保存在客户端（浏览器），Session 保存在服务器端； — [Updated on 2022-02-27 16:37:36](https://hyp.is/hB7M-JeoEey5V_9Z00hL1A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 作用范围不同 — [Updated on 2022-02-27 16:37:42](https://hyp.is/hzysypeoEey68o920ghsbQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 存取方式不同 — [Updated on 2022-02-27 16:37:43](https://hyp.is/iGAy3peoEey1JD-Hp2jQ_g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 有效期不同 — [Updated on 2022-02-27 16:37:47](https://hyp.is/irmSMpeoEeyffldbzqOXcA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 隐私策略不同 — [Updated on 2022-02-27 16:37:51](https://hyp.is/jOTcQpeoEeypcTePm51_5A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 存储大小不同 — [Updated on 2022-02-27 16:37:56](https://hyp.is/j-2IMJeoEeyws38e2lcO8A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- HTTP报文有请求报文和响应报文两种 — [Updated on 2022-02-27 16:38:37](https://hyp.is/qHQf1peoEeyz3G8n4Pb3fg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 请求报文：从客户向服务器发送请求报文；响应报文：从服务端到客户的回答 — [Updated on 2022-02-27 16:44:58](https://hyp.is/iyF-HpepEey3dQOdoCsOOg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- WWW服务器传输超文本到本地浏览器的传输协议 — [Updated on 2022-02-27 16:45:34](https://hyp.is/oLgCDJepEeypFLs9lj6vbw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 以安全为目标的HTTP通道，简单讲是HTTP的安全版，即HTTP下加入SSL层 — [Updated on 2022-02-27 16:45:46](https://hyp.is/p_X7HpepEeyykZfBzu4ssQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 客户使用HTTPS的URL访问Web服务器，要求与Web服务器建立SSL连接 — [Updated on 2022-02-27 16:45:56](https://hyp.is/rhvHbJepEeypFQcdGLcLAg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 会将网站的证书信息（证书中包含公钥）传送一份给客户端 — [Updated on 2022-02-27 16:46:02](https://hyp.is/sXaEVpepEey690-T4OTn0A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 客户端的浏览器与Web服务器开始协商SSL连接的安全等级，也就是信息加密的等级 — [Updated on 2022-02-27 16:46:14](https://hyp.is/uGuVdpepEeyzZs_yPcB_Tw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 根据双方同意的安全等级，建立会话密钥，然后利用网站的公钥将会话密钥加密，并传送给网站 — [Updated on 2022-02-27 16:46:24](https://hyp.is/vmzm-pepEey2fK-6SZw71g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- Web服务器利用自己的私钥解密出会话密钥 — [Updated on 2022-02-27 16:46:28](https://hyp.is/wVW14JepEeypad_L8z2rAw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- Web服务器利用会话密钥加密与客户端之间的通信 — [Updated on 2022-02-27 16:46:34](https://hyp.is/xLz47JepEeyr5gNIajbXcA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- HTTPS协议需要到ca申请证书 — [Updated on 2022-02-27 16:48:45](https://hyp.is/EwGC8peqEeyr3XfGGZXe0g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- HTTP是超文本传输协议，信息是明文传输，HTTPS则是具有安全性的SSL加密传输协议 — [Updated on 2022-02-27 16:48:53](https://hyp.is/F6eMKpeqEey4NJeKltMR-g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 用的端口也不一样，前者是80，后者是443 — [Updated on 2022-02-27 16:48:58](https://hyp.is/GqVJipeqEeyoSXesNZY8VQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- HTTP的连接很简单，是无状态的 — [Updated on 2022-02-27 16:49:04](https://hyp.is/Hb1yAJeqEeyYugth32n5-A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 加密传输、身份认证的网络协议，比HTTP协议安全 — [Updated on 2022-02-27 16:49:09](https://hyp.is/IOsPjJeqEey_4TtADBgbrg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 本地域名解析服务系统 — [Updated on 2022-02-27 16:56:14](https://hyp.is/HkjCoJerEeykEX-dxWMkwA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 根域名解析服务器 — [Updated on 2022-02-27 16:56:21](https://hyp.is/IpgLQJerEey1Ee82CVqWxA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- gTLD（通用顶级域名）域名解析服务器 — [Updated on 2022-02-27 16:56:29](https://hyp.is/JwffUperEeyrMF8QBajbIg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- Name Server服务器 — [Updated on 2022-02-27 16:56:36](https://hyp.is/K6zmQperEeymIafWKPk2GA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- IP地址给本地服务器 — [Updated on 2022-02-27 16:56:43](https://hyp.is/L8OFTJerEeyS-ZcCgy1Ozg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 本地域名服务器缓存解析结果； — [Updated on 2022-02-27 16:56:45](https://hyp.is/MMKodJerEeyzb4slly_hVw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 返回解析结果给用户。 — [Updated on 2022-02-27 16:56:47](https://hyp.is/MfwP8JerEeykEpP90URclg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 就先在其 ARP高速缓存中查看有无主机B的IP地址 — [Updated on 2022-02-27 16:59:36](https://hyp.is/lnSq0perEey_41v9s5HHaQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 再将此硬件地址写入MAC帧 — [Updated on 2022-02-27 16:59:40](https://hyp.is/mWAfQperEey6-8NxiSVHMg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- MAC帧发往此硬件地址 — [Updated on 2022-02-27 16:59:43](https://hyp.is/mwzjeperEey5dacKkQvlEg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 广播发送 — [Updated on 2022-02-27 16:59:50](https://hyp.is/nygooperEeyoh8NQ-Puopg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- ARP响应分组后 — [Updated on 2022-02-27 16:59:59](https://hyp.is/pIUn0perEey5dq_RctS4aA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- IP地址到硬件地址的映射写入ARP高速缓存。 — [Updated on 2022-02-27 17:00:02](https://hyp.is/plVCLJerEeyYvsvfAtg21g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 目标MAC地址是否是本接口的MAC — [Updated on 2022-02-27 17:00:12](https://hyp.is/q-pkGperEeyS-usCB8-Mrg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 是则解封装并将IP包移动到路由器内部 — [Updated on 2022-02-27 17:00:20](https://hyp.is/sMV4sperEey1Ks9VDPhXRw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- ICMP（互联网控制消息协议）错误消息 — [Updated on 2022-02-27 17:00:30](https://hyp.is/txbNaperEey0Ayc6nOAClg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 则将数据路由到相应的出口，再封装帧头帧尾； — [Updated on 2022-02-27 17:00:42](https://hyp.is/vhzyuperEeyfAi_tSKgnzQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 32位（4字节） — [Updated on 2022-02-27 17:00:50](https://hyp.is/wt6EEperEeymJYdla_1QQA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 128位（16字节） — [Updated on 2022-02-27 17:00:53](https://hyp.is/xGYaIJerEeyYv8cGXNmbaQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 小数表示的二进制数 — [Updated on 2022-02-27 17:00:57](https://hyp.is/xwAh9JerEeya9bfBmO5NBA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

-  IPv6地址是以十六进制表示的二进制数 — [Updated on 2022-02-27 17:01:01](https://hyp.is/yXKtbJerEey0K39h8j6fLA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 576个字节 — [Updated on 2022-02-27 17:01:08](https://hyp.is/zYa7RperEeyHkIudva_PyQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 碎片可选 — [Updated on 2022-02-27 17:04:00](https://hyp.is/GouVEJesEeya9h91FjKwlg/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation
    - Annotation: 碎片指的是，将ip包进行拆分。通过网络后重新组装。IPV6尽量避免碎片化。
- 有 20-60 个字节的可变长度 — [Updated on 2022-02-27 17:05:20](https://hyp.is/ZAS-fpesEeyrMo9Zf-u-2A/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- Pv6有40 个字节的固定长度 — [Updated on 2022-02-27 17:05:22](https://hyp.is/ZTHfZpesEey5dwMwExgFxA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 对称加密具有更高的加解密速度 — [Updated on 2022-02-27 17:05:35](https://hyp.is/bNEwZJesEeyqoK88jf8B7g/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 公钥负责加密，私钥负责解密 — [Updated on 2022-02-27 17:05:46](https://hyp.is/czmnBpesEey6_oN8o5wk9Q/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 浏览器检查CA证书是不是由可以信赖的CA机构颁发的 — [Updated on 2022-02-27 17:06:09](https://hyp.is/gQO8CpesEeypfePSssJCBA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 确认证书有效和此证书是此网站的 — [Updated on 2022-02-27 17:06:16](https://hyp.is/hVkvTJesEey6op-h_Z_SUw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 如果是，客户端使用公钥加密了一个随机对称密钥，包括加密的URL一起发送到服务器 — [Updated on 2022-02-27 17:06:25](https://hyp.is/ikQWtpesEeyoCT8kpqxOIQ/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 然后用这把对称加密的钥匙给你请求的URL链接解密 — [Updated on 2022-02-27 17:06:35](https://hyp.is/kIqldpesEeyz5wPKa9pSQA/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation

- 用你发的对称钥匙给你请求的网页加密 — [Updated on 2022-02-27 17:06:42](https://hyp.is/lOF4wJesEeyoTQdr_RHiPw/github.com/datawhalechina/daily-interview/blob/master/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md) — Group: #self-notation




