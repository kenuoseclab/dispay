# dispay收款系统  

#### 功能特点:
dispay个人收款助手可实现收款成功后发送通知到服务器，网页可从服务器获取到付款状态从而完成操作。
可支持微信，支付宝的个人收款需求，无需支付宝微信认证，无需上传身份证及营业执照，个人收款好帮手。
特点：操作简单，收款安全，零风险，个人无需服务器。

#### 安全性：
1. dispay只监听支付宝和微信的收款信息，忽略其他消息
2. 收款金额直接到个人账户
3. dispay不调用支付宝和微信任何接口，无账号封杀风险

#### 原理简述:
1. 客户请求付款时，付款页展示个人收款二维码
2. dispay APP通过监听你支付宝和微信的收款通知，将到账金额发送到服务器
3. 付款页定时从服务器获取付款状态，通过金额区分不同的订单

#### 操作步骤:
以下涉及到3个APP，分别是支付宝，微信和dispay收款助手
1. 使用安卓手机下载安装dispay APP，注册并登陆，点击打开服务
2. 打开3个APP的通知权限，确保收到消息可在顶部弹出通知框，并在电源保护勾选，防止APP被系统杀死
3. 替换收款网页中的二维码为你自己的，并设置优惠范围
4. 验证收款

#### 项目演示

本项目演示地址： [点此测试](http://dispay.goodqp.com/)

#### 源码下载 
 
本项目源码下载： [点此下载](http://dispay.goodqp.com/)

