<img src="https://raw.githubusercontent.com/AL-1S-QQBOT/koishi-plugin-ba-plugin/main/logo2.png" width = "130" height = "176" align=right />

<div align="left">

# BlueArchive—碧蓝档案工具箱

[![npm](https://img.shields.io/npm/v/koishi-plugin-ba-plugin?style=flat-square)](https://www.npmjs.com/package/koishi-plugin-ba-plugin)
[![npm downloads](https://img.shields.io/npm/dm/koishi-plugin-ba-plugin)](https://www.npmjs.com/package/koishi-plugin-ba-plugin)
![node version](https://img.shields.io/badge/node-%3E%3D18-green)
![GitHub top language](https://img.shields.io/github/languages/top/AL-1S-QQBOT/koishi-plugin-ba-plugin?logo=github)

</div>

## 🔗 快速链接
- 体验插件功能：与我们的[![QQ官方机器人AL_1S](https://img.shields.io/badge/QQ官方机器人-AL_1S-blue)](https://qun.qq.com/qunpro/robot/qunshare?robot_uin=2854197266&robot_appid=102062652&biz_type=0)交互。

## ✨ 项目介绍

#### 1.0版本亮点
- 🤖 适配官方bot，自动更新json数据
- 🚧 全面重构旧功能
- 🛠️ 优化和修复已知问题

#### ⚙️ 技术架构
- 本项目是 [koishi](https://github.com/koishijs/koishi) 机器人框架的一个插件，需在 koishi 中使用。

## 🌈 目前功能

- [x] Aronabot的攻略图 
- [x] 角色好感升级所需计算
- [x] 玩家升级计算 
- [x] 国服总力站档线及排名查询 
- [x] 抽官方漫画 
- [x] 抽卡模拟器
- [x] bawiki推图攻略 
- [x] 数据自动更新
- [ ] 活动日程
- [ ] 学生生日查询
- [ ] 功能权限管理

## 🛠️ 使用

#### 📦 安装部署
```bash
npm install koishi-plugin-ba-plugin
```
---
## 🙏 感谢

感谢以下开发者的贡献

<a href="https://github.com/AL-1S-QQBOT/koishi-plugin-ba-plugin/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AL-1S-QQBOT/koishi-plugin-ba-plugin&max=200&columns=14" />
</a>

同时，也感谢以下项目的支持
                         
- 交互和功能设计灵感：[arona](https://github.com/diyigemt/arona)
和[NoneBot-Plugin-BAWiki](https://github.com/lgc-NB2Dev/nonebot-plugin-bawiki)
- 数据库：[ba-wiki](https://github.com/lgc-NB2Dev/bawiki-data)
- 档线数据：[什亭之匣](https://arona.icu/)

## ❤️ 贡献

欢迎任何 Issues/Pull Requests！只需要将你的更改提交到此项目即可喵

### 如何贡献

你可以通过查看 Issue 或帮助审核 PR 来贡献。任何 Issue 或 PR 都欢迎参与。当然，这些只是建议，你可以以任何方式进行贡献。

如果想要添加新的功能，请先通过 Issue 讨论。

## ⭐ Star

> [!TIP]
> 如果本项目对您产生了帮助，或者您期待着本项目的未来发展，请给项目 Star，这是我们维护这个开源项目的动力喵

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=AL-1S-QQBOT/koishi-plugin-ba-plugin&type=Date)](https://star-history.com/#AL-1S-QQBOT/koishi-plugin-ba-plugin&Date)

</div>

## 📃更新日志
<details>
<summary>点我查看更新日志详情</summary>

### 1.1.4 & 1.1.5
  - 其他小修小补
  - 更新关卡的日服地图为28
  - 补全`关卡`指令的本地化

### 1.1.2 & 1.1.3
  - 更新数据
  - koishi版本号填错咪
  - 其他小修小补

### 1.1.1
  - 更新数据
  - 概率可随fes池更新
  - ~~废弃攒钻功能~~

### 1.1.0
  - 继承自1.1.0-beta.3
  - 修复已知问题

### 1.1.0-beta.x
  - 修复好感计算器问题
  - 修复本地化路径
  - 修复抽卡模拟器问题
  - 修复配置项错误

### 1.1.0-alpha.x
  - 新增使用QQ频道中转来发送md图
  - 新增大决战档线
  - 增加抽卡粒子效果
  - 实现本地化功能
  - 实现学生匹配系统数据热更新，重启插件即可更新（之前需要重启koishi）
  - 完善自动更新，现在可在控制台选择更新模式
  - 修改错误数据
  - 修改配置项位置
  - 适配多md模板
  - 修复已知错误，提高稳定性
  - ~~废弃使用对象存储来发图~~

### 1.0.1
  - 尝试修复inject报错
  - 修改错误数据

### 1.0.0-rc.x
  - 继承自1.0.0-beta.11 应该没啥大问题了（）
  - 咪

### 1.0.0-beta.x
  - 增加千里眼指令
  - 增加选择canvas渲染模式
  - 修复自动更新问题，抽卡数据实现热更新
  - 修复已知学生匹配算法bug
  - 修复已知总力获取功能的bug
  - 修改canvas坐标
  - 修复渲染bug
  - 修杂七杂八的bug

### 1.0.0-alpha.x
  - 废弃大部分旧代码和架构，修改目录结构，封装了常用功能，
  - 重构抽卡模拟器（v3）
  - 重构攻略系统（v3）
  - 重构好感计算（v3）
  - 新增活动获取（v1）
  - 独立并重构抽漫画功能（v2）
  - 新增上学的关卡攻略（v1）
  - 新增总力获取（beta）
  - 新增自动数据更新（beta）
  - 新增本地数据更新（beta）
  - ~~暂时废弃攒钻功能~~
  - ~~废弃抽表情功能，转移至[emojihub-bili](https://www.npmjs.com/package/koishi-plugin-emojihub-bili?activeTab=readme)~~
  - ~~废弃抽群u功能~~
  - ~~废弃千里眼快速调用~~


---

### 0.10.2
  - 更新了aronabot的api

### 0.10.1
  - 修复了渲染图图标错误的bug

### 0.10.0
  - *添加了puppeteer依赖*
  - *添加了将好感计算、攒钻、升级的输出转图片的功能，并支持自定义样式，提供了三个样式*
  - 添加了自定义模糊匹配回复文本
  - 优化调用，可发送“千里眼”直接返回国际服千里眼图
  - 例行更新数据
  - 早苗的计算功能改动：
    - 好感计算修改了微量的文字
    - 攒钻更新到日服最近的运动会二期复刻活动，更新了计算代码，增加了日期检测，防倒算，以及缺少信息的报错
  - ~~早苗关闭了总力模拟功能~~



### 0.9.75-rc
  - *添加了抽卡功能开关*
  - 减少了攻略系统别名（[issue](https://github.com/Alin-sky/koishi-plugin-ba-plugin/issues/10)）
  - 添加了自定义撤回时间
  - [e佬](https://github.com/erurusion)修复koishi数据库更新引起的bug
  - 例行更新数据

### 0.9.6-rc
  - *添加了抽卡功能群组黑名单*

### 0.9.5-rc
  - *[早苗](https://github.com/Sanaene)佬发布的新功能好感计算和等级计算*

### 0.9.0-beta1
  - *[早苗](https://github.com/Sanaene)佬更新了攒钻*
  - 例行数据更新

### 0.9.0-beta
  - *重构了攻略系统*
  - 摸了一个暑假的鱼

### 0.9.0-Alpha
  - *接入了[Arona](https://github.com/diyigemt/arona)的公开数据*
  - 例行更新数据
  - 略微优化了旧代码
  - 其他小修小补
   
### 0.8.4
  - 例行更新数据
  - 其他小修补

### 0.8.3
  - 修复了抽群u的bug
  - 修复了并发请求图片url超出服务器负载的的bug

### 0.8.2
  - 添加了泳装兔子队的数据

### 0.8.1
  - 修复了Alpha版本的路径问题
  - 其他小修小补和优化

### 0.8.0(Alpha)
  - *添加了群u[エルル](https://github.com/erurusion)的新抽卡模拟器，比阿林的强十倍甚至⑨倍*
  - 其他小修小补

### 0.7.5（未定位合并转发显示问题）
  - *添加了随机表情和随机漫画*
  - 添加了新角色实莉的卡池和角评
  - 修复了抽卡模拟器不能添加角色的bug
  - 修复了0.7.1已知的bug
  - 其他小修小补


### 0.7.1（未定位合并转发显示问题）
  - 添加了up角色名称输入限制
  - 修复了抽卡模拟器抽up池子的一些bug
  - 优化控制台
  - 其他小修小补


### 0.7.0
  - *部分重构了抽卡函数，添加了up功能，支持自定义up角色，修复了未实现的保底功能*
  - 修改了攒钻算法的触发
  - *可以在koishi控制台切换图源服务器*
  - *可以在控制台定义up池角色*
  - 修复评测图源服务器刷新问题
  - 其他小修小补

### 0.6.1
  - 给评测系统添加了切换图源服务器的功能，并添加了“阿林云”

### 0.6.0
  - *添加了群u[早苗](https://github.com/Sanaene)佬的青辉石计算器*
  - *更换了角色评分的数据至6.0*
  - 添加了新角色的卡池和评测
  - 其他小修小补

### 0.5.0
  - *使抽卡模拟器的抽卡结果合并转发，减少刷屏*
  - 其他小修小补

### 0.4.3
  - *使总力记录拆分并合并转发，解决了长消息被风控无法发送的问题*
  - *新增了攻略功能，引用bawiki的攻略图，集成了常用攻略*
  - 其他小修小补

### 0.4.0、0.4.1、0.4.2
  - **这几个版本未正确构建和导入库。下载后无法启用，如果强行更改版本号会损坏koishi。若安装了请前往数据文件夹的node_modules目录，找到本插件安装lodashi，如果koishi炸了请参考论坛的解决方案**

### 0.3.3
  - 修0.3.2开发中的bug

### 0.3.2
  - *更新玲纱数据*
  - *添加了礼物查询*
  - 尝试合并转发功能
  - 修复已知bug，小修小补

### 0.3.1 
  - 添加了保底算法
  - 修复已知bug
  - 其他小修小补

### 0.3.0
  - *添加了群友[早苗](https://github.com/Sanaene)大佬的总力战模拟插件，tql*
  - *添加了两个服的十连抽卡功能，但未添加保底算法*
  - 修改了抽卡模拟器部分学生头像无法显示的问题

### 0.1.3和0.1.4
  - 修复抽卡模拟器不能显示图片的问题，将学生头像图片集成于插件
  - 评测系统中添加了学生名字
  - 摸了一整个五一的鱼（
  
### 0.1.1
  - 缩小了返回图片大小

### 0.1.0
  - 发包！拥有角色评测图功能、抽卡模拟功能

</details>

## 🍻 支持

[爱发电](https://afdian.com/a/alin-sky)，感谢大家的赞助咪😽
