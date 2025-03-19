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

| 一级分类           | 二级分类     | 项目标题           | 项目简介                            | 项目地址                                         | 教程                                     |
| ------------------ | ------------ | ------------------ | ----------------------------------- | ------------------------------------------------ | ---------------------------------------- |
| 01、AI应用生态     | AI应用工具   | LanguageTool       | 30+语种语法校验及实时纠错工具       | https://github.com/languagetool-org/languagetool | https://zhuanlan.zhihu.com/p/28636492929 |
|                    |              | Zammad             | 免费打造支持多渠道接入的客服系统    | https://github.com/zammad/zammad                 | https://zhuanlan.zhihu.com/p/30899947205 |
|                    | 部署与优化   | kimi-free-api      | 利用NAS白嫖API打造AI助理            | https://github.com/LLM-Red-Team/kimi-free-api    | https://zhuanlan.zhihu.com/p/30656476376 |
|                    |              | 独角数卡           | 搭建自动售货商城实现自动发货        | https://github.com/apocalypsor/dujiaoka          | https://zhuanlan.zhihu.com/p/30380053677 |
|                    | 辅助开发工具 | 2Fauth             | 整合管理多平台二步验证验证码        | https://github.com/Bubka/2FAuth                  | https://zhuanlan.zhihu.com/p/30421625897 |
|                    |              | Penpot             | 跨平台原型设计及团队协作工具        | https://github.com/penpot/penpot-docs            | https://zhuanlan.zhihu.com/p/28926566755 |
| 02、智能开发与部署 | 镜像管理     | Yacht              | 可视化管理Docker容器的工具          | https://github.com/selfhostedpro/yacht           | https://zhuanlan.zhihu.com/p/30655894884 |
|                    | 开发环境     | Windows in Docker  | 用Docker在绿联NAS里装Windows系统    | https://github.com/dockur/windows                | https://zhuanlan.zhihu.com/p/30085619296 |
|                    | 自动化体系   | dailycheckin       | 支持多平台自动签到及茅台预约        | https://github.com/sitoi/dailycheckin            | https://zhuanlan.zhihu.com/p/30580352333 |
| 03、数据与知识管理 | 协作与共享   | O2OA开源OA系统     | 解决企业流程及数据安全管理问题      | https://www.o2oa.net/                            | https://zhuanlan.zhihu.com/p/30089593468 |
|                    | 智能处理     | MT Photos          | 相册管理，支持搜图、分类、共享      | mt-photos官网                                    | https://zhuanlan.zhihu.com/p/29162667081 |
|                    |              | PhotoStructure     | 智能整理照片，支持多格式访问        | https://hub.docker.com/r/photostructure/server   | https://zhuanlan.zhihu.com/p/30688995020 |
| 04、多媒体处理中心 | 视频处理     | DouyinLiveRecorder | 全网主流平台直播自动录播工具        | https://github.com/ihmily/DouyinLiveRecorder     | https://zhuanlan.zhihu.com/p/30337694551 |
|                    | 图像处理     | Darktable          | 在NAS部署修图工具实现专业修图       | https://www.darktable.org/                       | https://zhuanlan.zhihu.com/p/30386654437 |
|                    |              | Image-Matting      | AI自动抠图，支持多场景和批量处理    | https://github.com/ihmily/Image-Matting          | https://zhuanlan.zhihu.com/p/30240516610 |
| 05、运维监控体系   | 资源监控     | Diun               | 实时监控Docker镜像更新并通知        | https://github.com/crazy-max/diun                | https://zhuanlan.zhihu.com/p/29681815454 |
|                    |              | HertzBeat          | 实时监控告警，设备集中管理          | https://gitee.com/dromara/hertzbeat              | https://zhuanlan.zhihu.com/p/28925636833 |
|                    |              | kener              | 实时监控服务并可自定义监控墙        | https://github.com/rajnandan1/kener              | https://zhuanlan.zhihu.com/p/29374447746 |
| 06、企业协作平台   | 文档协作     | 魔豆文库           | 让NAS变文档库并支持多格式预览       | https://github.com/mnt-ltd/moredoc               | https://zhuanlan.zhihu.com/p/30900193400 |
|                    | 项目管理     | Wallos             | 管理周期账单及提醒的自托管系统      | https://github.com/bellamy/wallos                | https://zhuanlan.zhihu.com/p/31069090279 |
| 08、家庭与物联网   | 家庭娱乐     | RetroArch-web      | NAS部署网页版游戏模拟器畅玩经典游戏 | https://github.com/libretro/RetroArch            | https://zhuanlan.zhihu.com/p/31046508367 |
|                    | 生活服务     | Hammond            | 支持多车多用户的车辆记账系统        | https://github.com/akhilrex/hammond              | https://zhuanlan.zhihu.com/p/31046030759 |
| 09、效率工具集合   | 办公辅助     | Claper             | 实现PPT演讲弹幕投票等互动功能       | https://github.com/claperco/claper               | https://zhuanlan.zhihu.com/p/31081591862 |
|                    | 时间管理     | Traggo             | 标签化时间追踪统计神器              | https://github.com/traggo/server                 | https://zhuanlan.zhihu.com/p/30483352420 |
|                    | 信息聚合     | notnav             | 基于Notion的智能导航站项目          | https://github.com/TWO-ICE/notnav                | https://zhuanlan.zhihu.com/p/18382795073 |
| 10、基础服务架构   | 网络服务     | MyIP               | 网络诊断工具，集多功能于一体        | https://github.com/jason5ng32/myip               | https://zhuanlan.zhihu.com/p/30579748111 |
|                    |              | 卷王考试系统       | 支持问卷考试自动化的NAS系统         | https://github.com/xianyu-one/surveyking         | https://zhuanlan.zhihu.com/p/30481345905 |
|                    |              | 翼龙面板汉化版     | 支持多游戏一键开服及管理            | https://github.com/pterodactyl-china/panel       | https://zhuanlan.zhihu.com/p/30481011234 |

## 🤝 如何贡献
1. Fork 本仓库
2. 按格式添加新项目到 `projects.yaml`
3. 提交 Pull Request
4. 通过审核后合并到主分支

**格式要求**：
```yaml
- category: "01、AI应用生态"
  subcategory: "AI工具"
  name: "LanguageTool"
  description: "多语言语法校验工具"
  repo: "https://github.com/languagetool-org/languagetool"
  tutorial: "https://zhuanlan.zhihu.com/p/28636492929"
```

## 📜 许可协议
本项目采用 [MIT License](LICENSE)，欢迎自由使用和二次开发。

