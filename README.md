# JustMySocks 购买与配置全指南：省心稳定的科学上网方案

JustMySocks 是知名 VPS 服务商 BandwagonHost（搬瓦工）官方推出的代理服务。对于许多需要访问国际互联网的用户来说，它是一个非常有名的选择。

在开始教程之前，我们先客观地评价一下这项服务，方便你判断它是否适合你。

### 客观评价：它适合你吗？

实话说，**JustMySocks 绝不是市面上价格最便宜的方案。**

相比于购买廉价 VPS 自行搭建（可能低至 $2-3/月）或者某些小型机场，JustMySocks 的起步价（$5.88/月）稍显昂贵。但是，它为中国大陆用户提供了一种**高度可靠、极度省心**的解决方案。

* **核心优势**：官方承诺 IP 被封自动更换。你不需要懂技术，不需要担心 IP 被墙后如果不换 IP 就废了的问题，也不用折腾复杂的服务器脚本。
* **适用人群**：适合对稳定性要求较高，追求“开箱即用”，且**不愿意花费时间进行技术维护**的用户。如果你只想安安静静地上网，不想学习复杂的 Linux 命令或处理服务器故障，这是一个非常稳妥的方案。

---

### 第一部分：购买教程

1.  **访问官网**
    打开 JustMySocks 官网地址：[👉点此直达官网](https://c.shangshu.xyz/jms)
    
    *(如果界面是英文，可以点击右上角的 "English" 切换为中文)*
![01](https://github.com/user-attachments/assets/71ee45d8-95f3-4e0e-a814-bbc324b676df)

3.  **注册账户**
    点击右上角的 **“注册”**。页面可能会显示Cloudflare的验证，耐心等待加载完毕。
![05](https://github.com/user-attachments/assets/c46045ae-7098-4460-bae8-36272e6e9f36)

    填写你的个人邮箱、省份、国家，并设置登录密码。
    * **注意**：请务必填写真实邮箱，用于接收验证码和重要的服务通知。
    * 勾选“我已详阅并同意服务条款”，点击 **“注册”**。
![02](https://github.com/user-attachments/assets/169a8dc9-de41-4154-80bd-f5e6361e23bf)

4.  **激活邮箱**
    登录你的注册邮箱，找到官方发来的验证邮件，点击其中的链接完成账户激活。
![04](https://github.com/user-attachments/assets/5c111274-6613-4dab-8066-30a9dd820551)

5.  **选择套餐**
    登录后台后，点击菜单栏的 **服务** -> **订购新服务**。
    ![07](https://github.com/user-attachments/assets/ff0af415-3404-4661-bec8-190274a039ba)

    页面会列出多个套餐。对于大多数个人用户，**LA 500** 套餐（每月 500G 流量，CN2 GIA 线路）通常已经足够使用。如果您的用量较大，可以考虑更高的套餐。
    选择相应的套餐，并点击该套餐下的 **“立即购买”**。
![08](https://github.com/user-attachments/assets/d16d6433-b0f5-470c-988d-a7b32be8bcb8)

7.  **配置与支付**
    * **付款周期**：你可以选择月付（$5.88/月），也可以选择年付（$58.88/年，相当于买10送2）。建议初次使用者先选择月付体验。
      ![09](https://github.com/user-attachments/assets/71935bb8-df0c-45a5-ba6b-06ca1381807d)

    * **结账**：点击“继续” -> "Checkout"。
      ![10](https://github.com/user-attachments/assets/bdcfe23d-ddd2-4f1a-b9a9-5bd3ab2e5117)

    * **支付方式**：支持 **Alipay (支付宝)** 和 UnionPay (银联)。这对国内用户非常友好。选择 Alipay，勾选同意条款，点击“完成订购”，手机扫码支付即可。
![11](https://github.com/user-attachments/assets/588ff659-b8e1-48a0-a4c9-8dd975cebf53)
![12](https://github.com/user-attachments/assets/de5d4319-1751-4790-9d05-5c55b91fce5c)

8.  **获取订阅链接 (关键步骤)**
    支付成功后，点击 **“Continue To Client Area”** 返回客户区。
    ![13](https://github.com/user-attachments/assets/6541f2c4-6ef9-4ed4-b029-2854a98cad39)

    进入 **“服务”** -> **“我的服务”**，点击你刚刚购买的套餐进入详情页。
    ![15](https://github.com/user-attachments/assets/10d423de-1ab4-4156-958a-cc1cc9070176)

    在详情页中找到 **Subscription (订阅)** 部分，复制以 `https://` 开头的 **订阅链接**。
    *(注意：这个链接包含了你的所有节点信息，请勿泄露给他人)*
![16](https://github.com/user-attachments/assets/7c5171b2-a049-4aa0-9fb1-7df0f7af60e0)

---

### 第二部分：Windows 电脑设置指南

Windows 上最常用的客户端是 **v2rayN**。

1.  **下载客户端**
    访问 GitHub 下载最新版 v2rayN：
    [https://github.com/2dust/v2rayN/releases](https://github.com/2dust/v2rayN/releases)
    *(通常下载 `v2rayN-windows-64-desktop.zip` 即可)*

2.  **安装与运行**
    下载后解压压缩包，运行文件夹内的 `v2rayN.exe`。
![16-1](https://github.com/user-attachments/assets/561b8db4-a03f-44b0-be27-791b1b7f5416)

3.  **添加订阅**
    * 在软件主界面，点击顶部菜单的 **“订阅分组”** -> **“订阅分组设置”** -> **“添加”**。
      ![17](https://github.com/user-attachments/assets/b6d16d0a-ad13-4ff6-b804-ad7a277ebc79)

    * **别名**：任意填写（如 JMS）。
    * **可选地址(url)**：粘贴第一部分复制的**订阅链接**。
    * 点击“确定”。
      ![18](https://github.com/user-attachments/assets/2c8c991c-2b28-40a4-b70b-a229091677fd)
      
4.  **更新节点**
    回到主界面，点击菜单 **“订阅分组”** -> **“更新全部订阅(不通过代理)”**。
    ![20](https://github.com/user-attachments/assets/f91c26f4-754d-446b-ae70-4fc7a55ad58e)

    此时界面应该会刷新出一系列服务器列表。可以点击菜单栏的“测试服务器延迟”，查看连接状态（延迟数字越小越快，速度数字越大越快）。
![21](https://github.com/user-attachments/assets/5607204c-d343-4017-a0d4-5c81e131ce27)

6.  **启动服务**
    * 选中一个状态较好的节点，右键 -> **“设为活动服务器”**。
  ![23](https://github.com/user-attachments/assets/5189192a-4655-436f-9cec-33ca677b1787)

    * 在软件底部状态栏，找到 **“系统代理”**，选择 **“自动配置系统代理”**。
    * **“路由”** 建议选择 **“绕过大陆”**（这样访问国内网站不走流量，访问国外网站才走代理）。
      ![23-1](https://github.com/user-attachments/assets/b51198f7-ebf4-444c-b120-5e130a64c896)

    * 现在打开浏览器，即可正常访问 Google、YouTube、X 等网站。
<img width="963" height="534" alt="image" src="https://github.com/user-attachments/assets/c4156346-6662-452c-9c1f-4cb66441bb4b" />

---

### 第三部分：Android 安卓手机设置指南

安卓端推荐使用 **v2rayNG**。

1.  **下载客户端**
    访问 GitHub 下载：
    [https://github.com/2dust/v2rayNG/releases](https://github.com/2dust/v2rayNG/releases)
    *(通常下载 `v2rayNG_x.x.x_arm64-v8a.apk`)*

2.  **配置订阅**
    * 打开 App，点击左上角的菜单图标（三道杠）-> **订阅分组设置**。
    * 点击右上角的 **+** 号。
    * **备注**：随意填写。
    * **可选地址(url)**：粘贴你的**订阅链接**。
    * 点击右上角的 **√** 保存。

3.  **连接**
    * 回到主界面，点击右上角的三点菜单 -> **“更新订阅”**。
    * 点击 **“测试全部配置真连接”**，选择一个延迟显示为绿色数字的节点。
    * 点击右下角的 **V** 字图标启动服务。当状态栏出现钥匙图标或 VPN 提示时，即表示连接成功。

---

### 第四部分：iOS (iPhone/iPad) 设置指南

由于苹果的政策限制，中国区 App Store 无法下载此类代理软件。你需要使用**非中国大陆地区（如美区、港区）的 Apple ID**。

1.  **准备工作**
    * 切换至外区 Apple ID 登录 App Store。
    * 搜索并下载 **Shadowrocket**（俗称“小火箭”）。这是一个付费软件（通常为 $2.99），也是目前 iOS 上体验最好的工具之一。

2.  **一键配置**
    * 打开 Shadowrocket，点击右上角的 **+** 号。
    * **类型**选择 **Subscribe (订阅)**。
    * 在 **URL** 栏粘贴你的**订阅链接**。
    * 点击右上角的“完成”，软件会自动加载出所有节点。

3.  **开启服务**
    * 在首页的节点列表中，点击 **“连通性测试”**。
    * 选中一个延迟较低的节点（节点前会有小黄点标记）。
    * 打开顶部的 **“未连接”** 开关。
    * 如果是首次使用，系统会弹出“添加 VPN 配置”的权限提示，点击 **Allow (允许)** 并验证密码即可。

---

### 总结

JustMySocks 的设置逻辑非常简单：**购买 -> 获取订阅链接 -> 导入客户端**。一旦设置完成，它通常能保持很长时间的稳定运行，无需频繁干预。希望这篇教程能帮你顺利连通世界。
