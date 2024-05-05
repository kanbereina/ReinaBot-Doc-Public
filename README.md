# 小桜帆（ReinaBot）2.0  公开文档
## 机器人介绍  
<p align="center">
  <img src="https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/Mahoro.png" width="200" height="200" alt="小桜帆">
</p>

<div align="center">

# 小桜帆

<!-- prettier-ignore-start -->
<!-- markdownlint-disable-next-line MD036 -->
_✨ “鹿乃”主题机器人 ✨_  
<!-- prettier-ignore-end -->

</div>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.10+-blue?logo=python&logoColor=edb641" alt="python">
  <a href="https://nonebot.dev/">
    <img src="https://img.shields.io/badge/nonebot-FFFFFF?logo=sourcehut&logoColor=ea5353&style=flat" alt="nonebot">
  </a>
  <a href="https://onebot.dev/">
    <img src="https://img.shields.io/badge/OneBot-v11-black?style=social&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABABAMAAABYR2ztAAAAIVBMVEUAAAAAAAADAwMHBwceHh4UFBQNDQ0ZGRkoKCgvLy8iIiLWSdWYAAAAAXRSTlMAQObYZgAAAQVJREFUSMftlM0RgjAQhV+0ATYK6i1Xb+iMd0qgBEqgBEuwBOxU2QDKsjvojQPvkJ/ZL5sXkgWrFirK4MibYUdE3OR2nEpuKz1/q8CdNxNQgthZCXYVLjyoDQftaKuniHHWRnPh2GCUetR2/9HsMAXyUT4/3UHwtQT2AggSCGKeSAsFnxBIOuAggdh3AKTL7pDuCyABcMb0aQP7aM4AnAbc/wHwA5D2wDHTTe56gIIOUA/4YYV2e1sg713PXdZJAuncdZMAGkAukU9OAn40O849+0ornPwT93rphWF0mgAbauUrEOthlX8Zu7P5A6kZyKCJy75hhw1Mgr9RAUvX7A3csGqZegEdniCx30c3agAAAABJRU5ErkJggg==" alt="onebot">
  </a>
  <br>
  <a href="https://pd.qq.com/s/afw60mpz9">
    <img src="https://img.shields.io/badge/QQ%E9%A2%91%E9%81%93-鹿乃ちゃんの斑比森林-5492ff?style=flat-square" alt="QQ Channel">
  </a>
</p>

<div align="center">

<!-- prettier-ignore-start -->
<!-- markdownlint-disable-next-line MD036 -->
形象：**鹿乃桜帆**
<br>
画师：**@chimi_choco**
<!-- prettier-ignore-end -->

</div>

### 重要事项
> **小桜帆**是**非开源**的机器人，源码不对外开放，
> <br>
> 目前**仅核心开发人员**可对源码进行修改&测试，但**小桜帆**的文档是**公开可见的**）

### 历史
> **小桜帆**正式诞生于**2023年8-9月份**，
> <br>
> ~~（这一时期[鹿乃](https://zh.wikipedia.org/wiki/%E9%B9%BF%E4%B9%83)因为**某些原因***渐渐开始淡化音乐）~~
> <br>
> 之后，由于[go-cqhttp的兴衰](https://github.com/Mrs4s/go-cqhttp/issues/2471)，**小桜帆**作为QQ官方频道机器人诞生。
> <br>
> <br>
> 如今，由于QQ频道的屡次改版，
> <br>
> **小桜帆开发团队**已经丧失对频道方向的开发工作的信心，决定让**小桜帆**适配***OneBotV11***协议。
> <br>
> ~~（**小桜帆**的鹿态功能完成，发布第一个正式版本时，鹿乃已经重新回归音乐舞台上了。）~~
> <br>
> <br>
> ~~**好耶！！！！！！！！！！！！！！！！！！！！！！！！！！**~~

<br>
<br>
<br>

## 机器人功能

<p align="center">
  <img src="https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/Stereohonic.jpg" width="100" height="100" alt="鹿态">
</p>

<div align="center">

## 鹿态

<!-- prettier-ignore-start -->
<!-- markdownlint-disable-next-line MD036 -->
✨ 鹿乃动态推送 ✨ 
<!-- prettier-ignore-end -->

</div>

### 特点

- [x] 便于后期开发维护
- [x] Pydantic模型重构
- [x] httpx&连接池
- [x] 网络请求智能管理 
- [x] 定时任务智能管理

#### 推送功能支持

- [x] Twitter实时推送
- [x] Twitch直播推送
- [x] FanBox投稿推送
- [ ] YouTube投稿推送
- [ ] B站推送
- [ ] 微博推送

#### 推送设定支持

- [x] 全局推送选项设定
- [x] 群聊独立推送选项设定

### 预览

#### -- Twitter --
![推特示例1](https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/twitter1.png)

#### -- Twitch --
![推趣示例1](https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/twitch1.png)

![推趣示例2](https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/twitch2.png)

#### -- FanBox --
![饭盒示例1](https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/fanbox1.png)
![饭盒示例2](https://github.com/kanbereina/ReinaBot-Doc-Pubic/blob/main/doc/fanbox2.png)

<br>
<br>
<br>

## 赞助
[爱发电 - 连接创作者与粉丝的赞助平台](https://afdian.net/a/KanbeReina)

## 特别鸣谢
**@芝士（Cheeseke）** - 提供机器人服务器&开发支持
<br>
**@小黑lb233** - 参与小桜帆的部分开发工作
<br>
**@雁部令夏** - ~~我谢我自己~~
