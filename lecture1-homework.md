# 第1课 课后作业

## 第1题 ZKP 三色演示
证明依然是零知识的，如果选择任意节点不相邻的两个节点进行验证

如果选取到不相邻节点间，他们可以颜色相同也可以颜色不相同，这说明不相邻节点间颜色并不能提高置信度。

要提高置信度，只有选取到相邻节点。

## 第2题 DLOG 的 ZKP
null

## 第3题 zkmessage.xyz
解释为什么你需要生成并保存一个“秘密值” ？

用以证明身份，和区块链中的私钥一个意思

用白话写出 ZK 中正在证明的陈述？

必须选择至少1人与你作为同组的成员，用其在社交平台上公开的公钥+个人公钥对消息进行加密，使加密后的消息不能确定是组中谁生成的消息

从不同的浏览器或计算机登录到相同的 zkmessage 帐户。 解释为什么 zkmessage 不能像大多数社交应用程序一样，只使用简单的“用户名/密码” 。

首先无法修改密码，随机性差、安全性降
