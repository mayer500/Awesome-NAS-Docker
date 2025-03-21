# Awesome-NAS-Docker 🚀

[![GitHub Stars](https://img.shields.io/github/stars/TWO-ICE/Awesome-NAS-Docker?style=flat-square)](https://github.com/TWO-ICE/Awesome-NAS-Docker/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

**让 NAS 和 Docker 释放无限可能！**  
精选 100+ 开源项目，覆盖 AI、开发、数据管理、家庭娱乐等场景，提供一键部署指南和深度教程。

## 🌟 项目特色
- **分类清晰**：10 大核心领域，精准匹配需求
- **开箱即用**：每项目附带 Docker 部署命令和中文教程
- **持续更新**：紧跟技术趋势，定期补充高价值工具
- **社区驱动**：欢迎提交 Issue 或 PR 共建生态


## 🚀 快速开始
1. **环境准备**  
   - 支持 Docker 的 NAS 设备（群晖/QNAP/绿联等）
   - 基础命令行操作能力（可选 Web 管理工具如 Portainer）
2. **部署示例**  
   ```bash
   # 以 Yacht 为例
   docker run -d --name=yacht \
     -v /var/run/docker.sock:/var/run/docker.sock \
     -v yacht:/config \
     -p 8000:8000 \
     selfhostedpro/yacht:latest



## 📂 项目分类

### 1、AI应用生态

#### 1.1 AI应用工具

| 项目标题     | 项目简介                         | 项目地址                                                     | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------ | -------------------------------- | ------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Zammad       | 免费打造支持多渠道接入的客服系统 | [项目地址](https://github.com/zammad/zammad)                 | [查看教程](https://zhuanlan.zhihu.com/p/30899947205) | ![Star](https://img.shields.io/github/stars/zammad/zammad?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/zammad/zammad?label) |
| LanguageTool | 30+语种语法校验及实时纠错工具    | [项目地址](https://github.com/languagetool-org/languagetool) | [查看教程](https://zhuanlan.zhihu.com/p/28636492929) | ![Star](https://img.shields.io/github/stars/languagetool-org/languagetool?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/languagetool-org/languagetool?label) |

#### 1.2 部署与优化

| 项目标题      | 项目简介                     | 项目地址                                                  | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------- | ---------------------------- | --------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 独角数卡      | 搭建自动售货商城实现自动发货 | [项目地址](https://github.com/assimon/dujiaoka)           | [查看教程](https://zhuanlan.zhihu.com/p/30380053677) | ![Star](https://img.shields.io/github/stars/assimon/dujiaoka?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/assimon/dujiaoka?label) |
| kimi-free-api | 利用NAS白嫖API打造AI助理     | [项目地址](https://github.com/LLM-Red-Team/kimi-free-api) | [查看教程](https://zhuanlan.zhihu.com/p/30656476376) | ![Star](https://img.shields.io/github/stars/LLM-Red-Team/kimi-free-api?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/LLM-Red-Team/kimi-free-api?label) |

#### 1.3 辅助开发工具

| 项目标题            | 项目简介                       | 项目地址                                            | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------------- | ------------------------------ | --------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Halo                | 无需备案搭建高颜值动态主页     | [项目地址](https://github.com/halo-dev/halo)        | [查看教程](https://zhuanlan.zhihu.com/p/31658899666) | ![Star](https://img.shields.io/github/stars/halo-dev/halo?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/halo-dev/halo?label) |
| Reference中文速查表 | 提供 170+ 技术栈速查的开发工具 | [项目地址](https://github.com/jaywcjlove/reference) | [查看教程](https://zhuanlan.zhihu.com/p/31530365403) | ![Star](https://img.shields.io/github/stars/jaywcjlove/reference?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/jaywcjlove/reference?label) |
| Penpot              | 跨平台原型设计及团队协作工具   | [项目地址](https://github.com/penpot/penpot-docs)   | [查看教程](https://zhuanlan.zhihu.com/p/28926566755) | ![Star](https://img.shields.io/github/stars/penpot/penpot-docs?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/penpot/penpot-docs?label) |
| 2Fauth              | 整合管理多平台二步验证验证码   | [项目地址](https://github.com/Bubka/2FAuth)         | [查看教程](https://zhuanlan.zhihu.com/p/30421625897) | ![Star](https://img.shields.io/github/stars/Bubka/2FAuth?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/Bubka/2FAuth?label) |

### 2、智能开发与部署

#### 2.1 开发环境

| 项目标题          | 项目简介                         | 项目地址                                      | 教程                                                 | star                                                         | 最近更新                                                     |
| ----------------- | -------------------------------- | --------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Windows in Docker | 用Docker在绿联NAS里装Windows系统 | [项目地址](https://github.com/dockur/windows) | [查看教程](https://zhuanlan.zhihu.com/p/30085619296) | ![Star](https://img.shields.io/github/stars/dockur/windows?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/dockur/windows?label) |

#### 2.2 部署工具链

| 项目标题 | 项目简介 | 项目地址 | 教程 |
| -------- | -------- | -------- | ---- |

#### 2.3 镜像管理

| 项目标题 | 项目简介                   | 项目地址                                           | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | -------------------------- | -------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Yacht    | 可视化管理Docker容器的工具 | [项目地址](https://github.com/selfhostedpro/yacht) | [查看教程](https://zhuanlan.zhihu.com/p/30655894884) | ![Star](https://img.shields.io/github/stars/selfhostedpro/yacht?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/selfhostedpro/yacht?label) |

#### 2.4 自动化体系

| 项目标题     | 项目简介                     | 项目地址                                             | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------ | ---------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Watchtower   | 自动监控升级Docker容器的工具 | [项目地址](https://github.com/containrrr/watchtower) | [查看教程](https://zhuanlan.zhihu.com/p/31658965023) | ![Star](https://img.shields.io/github/stars/containrrr/watchtower?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/containrrr/watchtower?label) |
| dailycheckin | 支持多平台自动签到及茅台预约 | [项目地址](https://github.com/sitoi/dailycheckin)    | [查看教程](https://zhuanlan.zhihu.com/p/30580352333) | ![Star](https://img.shields.io/github/stars/sitoi/dailycheckin?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/sitoi/dailycheckin?label) |

#### 2.5 微服务支持

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |

### 03、数据与知识管理

#### 3.1 存储与治理

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |

#### 3.2 分析与可视化

| 项目标题  | 项目简介                       | 项目地址                                         | 教程                                                 | star                                                         | 最近更新                                                     |
| --------- | ------------------------------ | ------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Doku      | 可视化分析管理Docker存储       | [项目地址](https://github.com/amerkurev/doku)    | [查看教程](https://zhuanlan.zhihu.com/p/31405212699) | ![Star](https://img.shields.io/github/stars/amerkurev/doku?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/amerkurev/doku?label) |
| Web-Check | 获取网站核心数据并生成分析报告 | [项目地址](https://github.com/Lissy93/web-check) | [查看教程](https://zhuanlan.zhihu.com/p/31274835903) | ![Star](https://img.shields.io/github/stars/Lissy93/web-check?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/Lissy93/web-check?label) |

#### 3.3 协作与共享

| 项目标题       | 项目简介                       | 项目地址                                           | 教程                                                 | star                                                         | 最近更新                                                     |
| -------------- | ------------------------------ | -------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| O2OA开源OA系统 | 解决企业流程及数据安全管理问题 | [项目地址](https://www.o2oa.net/)                  | [查看教程](https://zhuanlan.zhihu.com/p/30089593468) |                                                              |                                                              |
| WBO开源白板    | 支持多端协作的开源白板系统     | [项目地址](https://github.com/lovasoa/whitebophir) | [查看教程](https://zhuanlan.zhihu.com/p/31405432808) | ![Star](https://img.shields.io/github/stars/lovasoa/whitebophir?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/lovasoa/whitebophir?label) |

#### 3.4 智能处理

| 项目标题       | 项目简介                       | 项目地址                                                   | 教程                                                 | star | 最近更新 |
| -------------- | ------------------------------ | ---------------------------------------------------------- | ---------------------------------------------------- | ---- | -------- |
| MT Photos      | 相册管理，支持搜图、分类、共享 |                                                            | [查看教程](https://zhuanlan.zhihu.com/p/29162667081) |      |          |
| PhotoStructure | 智能整理照片，支持多格式访问   | [项目地址](https://hub.docker.com/r/photostructure/server) | [查看教程](https://zhuanlan.zhihu.com/p/30688995020) |      |          |
#### 3.5 归档与安全

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
### 04、多媒体处理中心

#### 4.1 视频处理

| 项目标题           | 项目简介                     | 项目地址                                                 | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------------ | ---------------------------- | -------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| DouyinLiveRecorder | 全网主流平台直播自动录播工具 | [项目地址](https://github.com/ihmily/DouyinLiveRecorder) | [查看教程](https://zhuanlan.zhihu.com/p/30337694551) | ![Star](https://img.shields.io/github/stars/ihmily/DouyinLiveRecorder?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/ihmily/DouyinLiveRecorder?label) |
#### 4.2 音频管理

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 4.3 图像处理

| 项目标题      | 项目简介                         | 项目地址                                            | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------- | -------------------------------- | --------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Darktable     | 在NAS部署修图工具实现专业修图    | [项目地址](https://www.darktable.org/)              | [查看教程](https://zhuanlan.zhihu.com/p/30386654437) |                                                              |                                                              |
| Image-Matting | AI自动抠图，支持多场景和批量处理 | [项目地址](https://github.com/ihmily/Image-Matting) | [查看教程](https://zhuanlan.zhihu.com/p/30240516610) | ![Star](https://img.shields.io/github/stars/ihmily/Image-Matting?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/ihmily/Image-Matting?label) |
#### 4.4 流媒体服务

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 4.5 传输协议

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
### 05、运维监控体系

#### 5.1 资源监控

| 项目标题  | 项目简介                     | 项目地址                                        | 教程                                                 | star                                                         | 最近更新                                                     |
| --------- | ---------------------------- | ----------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| HertzBeat | 实时监控告警，设备集中管理   | [项目地址](https://github.com/apache/hertzbeat) | [查看教程](https://zhuanlan.zhihu.com/p/28925636833) | ![Star](https://img.shields.io/github/stars/apache/hertzbeat?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/apache/hertzbeat?label) |
| Amprobe   | 实时监控Docker生态关键指标   | [项目地址](https://github.com/amuluze/amprobe)  | [查看教程](https://zhuanlan.zhihu.com/p/31529269080) | ![Star](https://img.shields.io/github/stars/amuluze/amprobe?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/amuluze/amprobe?label) |
| Diun      | 实时监控Docker镜像更新并通知 | [项目地址](https://github.com/crazy-max/diun)   | [查看教程](https://zhuanlan.zhihu.com/p/29681815454) | ![Star](https://img.shields.io/github/stars/crazy-max/diun?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/crazy-max/diun?label) |
| kener     | 实时监控服务并可自定义监控墙 | [项目地址](https://github.com/rajnandan1/kener) | [查看教程](https://zhuanlan.zhihu.com/p/29374447746) | ![Star](https://img.shields.io/github/stars/rajnandan1/kener?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/rajnandan1/kener?label) |
#### 5.2 网络治理

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 5.3 日志体系

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 5.4 自动化运维

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 5.5 安全防护

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
### 06、企业协作平台

#### 6.1 项目管理

| 项目标题 | 项目简介                       | 项目地址                                     | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | ------------------------------ | -------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Wallos   | 管理周期账单及提醒的自托管系统 | [项目地址](https://github.com/ellite/Wallos) | [查看教程](https://zhuanlan.zhihu.com/p/31069090279) | ![Star](https://img.shields.io/github/stars/ellite/Wallos?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/ellite/Wallos?label) |
#### 6.2 通讯协同

| 项目标题 | 项目简介                       | 项目地址                                       | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | ------------------------------ | ---------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Fiora    | 自建高隐私聊天系统，支持多功能 | [项目地址](https://github.com/yinxin630/fiora) | [查看教程](https://zhuanlan.zhihu.com/p/31402031159) | ![Star](https://img.shields.io/github/stars/yinxin630/fiora?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/yinxin630/fiora?label) |
#### 6.3 文档协作

| 项目标题 | 项目简介                          | 项目地址                                             | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | --------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Univer   | 企业级文档协同编辑解决方案        | [项目地址](https://github.com/dream-num/helm-charts) | [查看教程](https://zhuanlan.zhihu.com/p/31528946946) | ![Star](https://img.shields.io/github/stars/dream-num/helm-charts?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/dream-num/helm-charts?label) |
| ShowDoc  | 支持自动生成API文档的团队文档系统 | [项目地址](https://github.com/star7th/showdoc)       | [查看教程](https://zhuanlan.zhihu.com/p/31405973187) | ![Star](https://img.shields.io/github/stars/star7th/showdoc?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/star7th/showdoc?label) |
| 魔豆文库 | 让NAS变文档库并支持多格式预览     | [项目地址](https://github.com/mnt-ltd/moredoc)       | [查看教程](https://zhuanlan.zhihu.com/p/30900193400) | ![Star](https://img.shields.io/github/stars/mnt-ltd/moredoc?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/mnt-ltd/moredoc?label) |
#### 6.4 HR支持

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 6.5 客户管理

| 项目标题 | 项目简介                      | 项目地址                                       | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | ----------------------------- | ---------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Twenty   | （开源CRM系统，可自托管部署） | [项目地址](https://github.com/twentyhq/twenty) | [查看教程](https://zhuanlan.zhihu.com/p/31658707436) | ![Star](https://img.shields.io/github/stars/twentyhq/twenty?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/twentyhq/twenty?label) |
### 07、安全与隐私工具

#### 7.1 加密体系

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 7.2 身份认证

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 7.3 威胁监控

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 7.4 渗透测试

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 7.5 数据保护

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
### 08、家庭与物联网

#### 8.1 智能家居

| 项目标题  | 项目简介                   | 项目地址                                       | 教程                                                 | star                                                         | 最近更新                                                     |
| --------- | -------------------------- | ---------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| xiaomusic | 实现小爱音箱播放多源音乐   | [项目地址](https://github.com/hanxi/xiaomusic) | [查看教程](https://zhuanlan.zhihu.com/p/31658934311) | ![Star](https://img.shields.io/github/stars/hanxi/xiaomusic?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/hanxi/xiaomusic?label) |
| HomeBox   | 搭建家庭及企业物资管理系统 | [项目地址](https://github.com/hay-kot/homebox) | [查看教程](https://zhuanlan.zhihu.com/p/31281271735) | ![Star](https://img.shields.io/github/stars/hay-kot/homebox?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/hay-kot/homebox?label) |
#### 8.2 健康管理

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 8.3 家庭娱乐

| 项目标题      | 项目简介                            | 项目地址                                          | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------- | ----------------------------------- | ------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| RetroArch-web | NAS部署网页版游戏模拟器畅玩经典游戏 | [项目地址](https://github.com/libretro/RetroArch) | [查看教程](https://zhuanlan.zhihu.com/p/31046508367) | ![Star](https://img.shields.io/github/stars/libretro/RetroArch?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/libretro/RetroArch?label) |
#### 8.4 物联网中枢

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 8.5 生活服务

| 项目标题 | 项目简介                     | 项目地址                                        | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | ---------------------------- | ----------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Hammond  | 支持多车多用户的车辆记账系统 | [项目地址](https://github.com/akhilrex/hammond) | [查看教程](https://zhuanlan.zhihu.com/p/31046030759) | ![Star](https://img.shields.io/github/stars/akhilrex/hammond?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/akhilrex/hammond?label) |
### 9、效率工具集合

#### 9.1 时间管理

| 项目标题 | 项目简介                         | 项目地址                                         | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | -------------------------------- | ------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| memos    | 三端同步的碎片化知识管理工具     | [项目地址](https://github.com/usememos/memos)    | [查看教程](https://zhuanlan.zhihu.com/p/31404911847) | ![Star](https://img.shields.io/github/stars/usememos/memos?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/usememos/memos?label) |
| Kimai    | 自由职业者和小微团队工时管理工具 | [项目地址](https://github.com/kevinpapst/kimai2) | [查看教程](https://zhuanlan.zhihu.com/p/31660214954) | ![Star](https://img.shields.io/github/stars/kevinpapst/kimai2?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/kevinpapst/kimai2?label) |
| Traggo   | 标签化时间追踪统计神器           | [项目地址](https://github.com/traggo/server)     | [查看教程](https://zhuanlan.zhihu.com/p/30483352420) | ![Star](https://img.shields.io/github/stars/traggo/server?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/traggo/server?label) |
#### 9.2 文件处理

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 9.3 信息聚合

| 项目标题 | 项目简介                         | 项目地址                                        | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | -------------------------------- | ----------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Huntly   | 实现网页内容归档及多场景知识管理 | [项目地址](https://github.com/lcomplete/huntly) | [查看教程](https://zhuanlan.zhihu.com/p/31529691241) | ![Star](https://img.shields.io/github/stars/lcomplete/huntly?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/lcomplete/huntly?label) |
| notnav   | 基于Notion的智能导航站项目       | [项目地址](https://github.com/TWO-ICE/notnav)   | [查看教程](https://zhuanlan.zhihu.com/p/18382795073) | ![Star](https://img.shields.io/github/stars/TWO-ICE/notnav?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/TWO-ICE/notnav?label) |
#### 9.4 个人助手

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 9.5 办公辅助

| 项目标题 | 项目简介                      | 项目地址                                       | 教程                                                 | star                                                         | 最近更新                                                     |
| -------- | ----------------------------- | ---------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Claper   | 实现PPT演讲弹幕投票等互动功能 | [项目地址](https://github.com/claperco/claper) | [查看教程](https://zhuanlan.zhihu.com/p/31081591862) | ![Star](https://img.shields.io/github/stars/claperco/claper?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/claperco/claper?label) |
## 10、基础服务架构

#### 10.1 网络服务

| 项目标题       | 项目简介                     | 项目地址                                                     | 教程                                                 | star                                                         | 最近更新                                                     |
| -------------- | ---------------------------- | ------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 卷王考试系统   | 支持问卷考试自动化的NAS系统  | [项目地址](https://github.com/javahuang/SurveyKing)          | [查看教程](https://zhuanlan.zhihu.com/p/30481345905) | ![Star](https://img.shields.io/github/stars/javahuang/SurveyKing?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/javahuang/SurveyKing?label) |
| 幻兽帕鲁服务器 | 搭建联机稳定的游戏专属服务器 | [项目地址](https://github.com/jammsen/docker-palworld-dedicated-server) | [查看教程](https://zhuanlan.zhihu.com/p/31530044821) | ![Star](https://img.shields.io/github/stars/jammsen/docker-palworld-dedicated-server?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/jammsen/docker-palworld-dedicated-server?label) |
| 翼龙面板汉化版 | 支持多游戏一键开服及管理     | [项目地址](https://github.com/pterodactyl-china/panel)       | [查看教程](https://zhuanlan.zhihu.com/p/30481011234) | ![Star](https://img.shields.io/github/stars/pterodactyl-china/panel?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/pterodactyl-china/panel?label) |
| MyIP           | 网络诊断工具，集多功能于一体 | [项目地址](https://github.com/jason5ng32/myip)               | [查看教程](https://zhuanlan.zhihu.com/p/30579748111) | ![Star](https://img.shields.io/github/stars/jason5ng32/myip?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/jason5ng32/myip?label) |
#### 10.2 存储方案

| 项目标题      | 项目简介                      | 项目地址                                             | 教程                                                 | star                                                         | 最近更新                                                     |
| ------------- | ----------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| iStoreNAS     | 使路由变存储中心的开源系统    | [项目地址](https://github.com/istoreos/istoreos)     | [查看教程](https://zhuanlan.zhihu.com/p/31282002446) | ![Star](https://img.shields.io/github/stars/istoreos/istoreos?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/istoreos/istoreos?label) |
| Photoview     | NAS相册管理，支持RAW及多功能  | [项目地址](https://github.com/photoview/photoview)   | [查看教程](https://zhuanlan.zhihu.com/p/31400083102) | ![Star](https://img.shields.io/github/stars/photoview/photoview?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/photoview/photoview?label) |
| UmbrelOS      | 将旧设备改造成NAS的系统项目   | [项目地址](https://github.com/getumbrel/umbrel)      | [查看教程](https://zhuanlan.zhihu.com/p/31405714398) | ![Star](https://img.shields.io/github/stars/getumbrel/umbrel?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/getumbrel/umbrel?label) |
| cosmos-server | 集安全防护与容器管理的NAS系统 | [项目地址](https://github.com/azukaar/cosmos-server) | [查看教程](https://zhuanlan.zhihu.com/p/31660374984) | ![Star](https://img.shields.io/github/stars/azukaar/cosmos-server?&label=) | ![Last Commit](https://img.shields.io/github/last-commit/azukaar/cosmos-server?label) |
#### 10.3 计算资源

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 10.4 消息体系

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
#### 10.5 边缘服务

| 项目标题 | 项目简介 | 项目地址 | 教程 | star | 最近更新 |
| -------- | -------- | -------- | ---- | ---- | -------- |
|          |          |          |      |      |          |
## 🤝 如何贡献

1. Fork 本仓库
2. 按格式添加新项目到 `projects.yaml`
3. 提交 Pull Request
4. 通过审核后合并到主分支

**格式要求**：
```yaml
- category: "01、AI应用生态"
- subcategory: "AI工具"
- name: "LanguageTool"
- description: "多语言语法校验工具"
- repo: "https://github.com/languagetool-org/languagetool"
- tutorial: "https://zhuanlan.zhihu.com/p/28636492929"
```

## 📜 许可协议
本项目采用 [MIT License](LICENSE)，欢迎自由使用和二次开发。
