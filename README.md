<p align="center">
    <img alt="logo" src="./doc/imgs/小石榴.png" width="100" />
</p>
<h1 align="center" style="margin: 20px 30px 0px 30px; font-weight: bold;">XiaoShiLiu</h1>

---
<p align="center">
    <b>基于 Express + Vue 前后端分离仿小红书项目</b>
</p>

<p align="center"><a href="https://github.com/ZTMYO/XiaoShiLiu">简体中文</a>|<a href="doc/i18n/README_En.md">English</a>|<a href="doc/i18n/README_zh-Hant.md">繁體中文</a>

<p align="center">
    <a href="https://github.com/ZTMYO/XiaoShiLiu/stargazers">
        <img src="https://img.shields.io/github/stars/ZTMYO/XiaoShiLiu?style=flat&logo=github&color=brightgreen&label=Stars">
    </a>
    <a href="https://github.com/ZTMYO/XiaoShiLiu/network/members">
        <img src="https://img.shields.io/github/forks/ZTMYO/XiaoShiLiu?style=round-square&color=brightgreen&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiBmaWxsPSJub25lIj4KPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik01IDUuMzcydi44NzhjMCAuNDE0LjMzNi43NS43NS43NWg0LjVhLjc1Ljc1IDAgMCAwIC43NS0uNzV2LS44NzhhMi4yNSAyLjI1IDAgMSAxIDEuNSAwdi44NzhhMi4yNSAyLjI1IDAgMCAxLTIuMjUgMi4yNWgtMS41djIuMTI4YTIuMjUxIDIuMjUxIDAgMSAxLTEuNSAwVjguNWgtMS41QTIuMjUgMi4yNSAwIDAgMSAzLjUgNi4yNXYtLjg3OGEyLjI1IDIuMjUgMCAxIDEgMS41IDBaTTUgMy4yNWEuNzUuNzUgMCAxIDAtMS41IDAgLjc1Ljc1IDAgMCAwIDEuNSAwWm02Ljc1Ljc1YS43NS43NSAwIDEgMCAwLTEuNS43NS43NSAwIDAgMCAwIDEuNVptLTMgOC43NWEuNzUuNzUgMCAxIDAtMS41IDAgLjc1Ljc1IDAgMCAwIDEuNSAwWiI+PC9wYXRoPgo8L3N2Zz4=">
    </a>
    <a href="https://github.com/ZTMYO/XiaoShiLiu">
        <img src="https://img.shields.io/badge/XiaoShiLiu-v1.3.2-brightgreen.svg?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjMyIiBoZWlnaHQ9IjMyIj4KPHBhdGggZD0iTTAgMCBDNC4yMzMwMTEyMSAyLjgyMjAwNzQ3IDcuMTcxNTk2NjQgNS45NTIyODk5MiA4LjgxMjUgMTAuODc1IEM5LjE4MDc2MjI0IDE2LjQ5MDk5OTE2IDkuMDI4MDYwMDcgMjAuMDUxNjU5ODkgNS44MTI1IDI0Ljg3NSBDMS44ODAxNjE5MSAyOC44NTAzMTQ0NiAtMS4zMzIwOTg0OSAzMC43NTMzMzQzMyAtNyAzMS4xMjUgQy0xMS43MTg5MjIyMyAzMS4wMzg1NzI4NSAtMTUuMjAxOTI2NjkgMjkuODM5MTA3NjUgLTE4LjYzMjgxMjUgMjYuNDQ1MzEyNSBDLTIyLjQ1Nzc0Mjg2IDIyLjA1MjEwNjc3IC0yMy41MDQ5MDc2NCAxOC43NDI5NTY4OSAtMjMuMzk4NDM3NSAxMi45Mjk2ODc1IEMtMjIuOTEyNTgwNTggOC4xOTcwODExNiAtMjAuNjcwMDc0MTQgNS4wOTQ1OTE5MSAtMTcuMTg3NSAyLjA2MjUgQy0xMS43NzQzMTUyMyAtMS44ODQ2MTM5IC02LjE5MjU0NDY4IC0yLjE4NTYwNDAxIDAgMCBaIE0tNy4xODc1IDQuODc1IEMtOC4xNzc1IDUuNTM1IC05LjE2NzUgNi4xOTUgLTEwLjE4NzUgNi44NzUgQy0xMC4xODc1IDcuNTM1IC0xMC4xODc1IDguMTk1IC0xMC4xODc1IDguODc1IEMtMTAuODA2MjUgOS4xNDMxMjUgLTExLjQyNSA5LjQxMTI1IC0xMi4wNjI1IDkuNjg3NSBDLTE0LjQ4NzAyMzMgMTAuODMwNTY4NDggLTE0LjQ4NzAyMzMgMTAuODMwNTY4NDggLTE2LjE4NzUgMTMuODc1IEMtMTYuNTc3NjM3MTYgMTUuODY0Njk5NSAtMTYuOTE5NTI2NDkgMTcuODY1MTk4NjkgLTE3LjE4NzUgMTkuODc1IEMtMTYuMTk3NSAyMC4zNyAtMTYuMTk3NSAyMC4zNyAtMTUuMTg3NSAyMC44NzUgQy0xNC40NjU5MDU3NiAyMi41MTg2MzEzNCAtMTMuNzkzOTg1NzkgMjQuMTg1NTAzODYgLTEzLjE4NzUgMjUuODc1IEMtMTIuNTI3NSAyNS44NzUgLTExLjg2NzUgMjUuODc1IC0xMS4xODc1IDI1Ljg3NSBDLTEwLjg1NzUgMjYuODY1IC0xMC41Mjc1IDI3Ljg1NSAtMTAuMTg3NSAyOC44NzUgQy05LjUyNzUgMjcuODg1IC04Ljg2NzUgMjYuODk1IC04LjE4NzUgMjUuODc1IEMtNi44Njc1IDI1Ljg3NSAtNS41NDc1IDI1Ljg3NSAtNC4xODc1IDI1Ljg3NSBDLTMuODU3NSAyNi44NjUgLTMuNTI3NSAyNy44NTUgLTMuMTg3NSAyOC44NzUgQy0zLjE4NzUgMjcuODg1IC0zLjE4NzUgMjYuODk1IC0zLjE4NzUgMjUuODc1IEMtMi4xOTc1IDI1LjU0NSAtMS4yMDc1IDI1LjIxNSAtMC4xODc1IDI0Ljg3NSBDMC40MDMyMDAxNCAyMi45Mjg5NjcyNiAwLjQwMzIwMDE0IDIyLjkyODk2NzI2IDAuODEyNSAyMC44NzUgQzEuNDcyNSAyMC4yMTUgMi4xMzI1IDE5LjU1NSAyLjgxMjUgMTguODc1IEMxLjU3OTU5MDMxIDEzLjExMDE4NTAyIDEuNTc5NTkwMzEgMTMuMTEwMTg1MDIgLTIuMTg3NSA4Ljg3NSBDLTIuODQ3NSA4Ljg3NSAtMy41MDc1IDguODc1IC00LjE4NzUgOC44NzUgQy00LjE4NzUgNy44ODUgLTQuMTg3NSA2Ljg5NSAtNC4xODc1IDUuODc1IEMtNS4xNzc1IDUuNTQ1IC02LjE2NzUgNS4yMTUgLTcuMTg3NSA0Ljg3NSBaIE0tMTguMTg3NSAxOS44NzUgQy0xOC4xODc1IDIyLjg3NSAtMTguMTg3NSAyMi44NzUgLTE4LjE4NzUgMjIuODc1IFogTTIuODEyNSAxOS44NzUgQzMuMTQyNSAyMC44NjUgMy40NzI1IDIxLjg1NSAzLjgxMjUgMjIuODc1IEMzLjgxMjUgMjEuODg1IDMuODEyNSAyMC44OTUgMy44MTI1IDE5Ljg3NSBDMy40ODI1IDE5Ljg3NSAzLjE1MjUgMTkuODc1IDIuODEyNSAxOS44NzUgWiAiIGZpbGw9IiNGQ0ZDRkMiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIzLjE4NzUsMS4xMjUpIi8+CjxwYXRoIGQ9Ik0wIDAgQzIuMDYyNSAwLjQzNzUgMi4wNjI1IDAuNDM3NSA0IDEgQzQgMS45OSA0IDIuOTggNCA0IEM0Ljk5IDQuMzMgNS45OCA0LjY2IDcgNSBDMy43ODU0ODczMSA2LjYwNzI1NjM1IDAuNTYzODc0NjQgNi4wNTc0ODE4NSAtMyA2IEMtMS4xMjUgMS4xMjUgLTEuMTI1IDEuMTI1IDAgMCBaICIgZmlsbD0iI0U5RTlFOSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTUsMjYpIi8+Cjwvc3ZnPgo=">
    </a>
    <a href="https://github.com/ZTMYO/XiaoShiLiu/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/ZTMYO/XiaoShiLiu?color=8ebc06">
    </a>
</p>
<p align="center">
    <img src="https://img.shields.io/static/v1?message=Vue&color=4f4f4f&logo=Vue.js&logoColor=4FC08D&label=">
    <img
        src="https://img.shields.io/static/v1?&message=JavaScript&color=4f4f4f&logo=JavaScript&logoColor=F7DF1E&label=">
    </a>
</p>


> **声明**  
> 本项目基于 [GPLv3 协议](./LICENSE)，免费开源，仅供学习交流，禁止转卖，谨防受骗。如需商用请保留版权信息，确保合法合规使用，运营风险自负，与作者无关。

---

> 📁 **项目结构说明**：本项目包含完整的前后端代码，前端位于 `vue3-project/` 目录，后端位于 `express-project/` 目录。详细结构请查看 [项目结构文档](./doc/PROJECT_STRUCTURE.md)。

## 项目展示

### PC端界面

<table>
  <tr>
    <td><img src="./doc/imgs/1.png" alt="PC端界面1" width="300"/></td>
    <td><img src="./doc/imgs/2.png" alt="PC端界面2" width="300"/></td>
    <td><img src="./doc/imgs/3.png" alt="PC端界面3" width="300"/></td>
  </tr>
  <tr>
    <td><img src="./doc/imgs/4.png" alt="PC端界面4" width="300"/></td>
    <td><img src="./doc/imgs/5.png" alt="PC端界面5" width="300"/></td>
    <td><img src="./doc/imgs/6.png" alt="PC端界面6" width="300"/></td>
  </tr>
  <tr>
    <td><img src="./doc/imgs/7.png" alt="PC端界面7" width="300"/></td>
    <td><img src="./doc/imgs/8.png" alt="PC端界面8" width="300"/></td>
    <td><img src="./doc/imgs/9.png" alt="PC端界面9" width="300"/></td>
  </tr>
  <tr>
    <td><img src="./doc/imgs/10.png" alt="PC端界面10" width="300"/></td>
    <td><img src="./doc/imgs/11.png" alt="PC端界面11" width="300"/></td>
    <td><img src="./doc/imgs/12.png" alt="PC端界面12" width="300"/></td>
  </tr>
  <tr>
    <td><img src="./doc/imgs/13.png" alt="PC端界面13" width="300"/></td>
    <td><img src="./doc/imgs/14.png" alt="PC端界面14" width="300"/></td>
    <td><img src="./doc/imgs/15.png" alt="PC端界面15" width="300"/></td>
  </tr>
    <tr>
    <td><img src="./doc/imgs/16.png" alt="PC端界面16" width="300"/></td>
    <td><img src="./doc/imgs/17.png" alt="PC端界面17" width="300"/></td>
    <td><img src="./doc/imgs/18.png" alt="PC端界面18" width="300"/></td>
  </tr>
</table>


## 项目文档

| 文档 | 说明 |
|------|------|
| [部署指南](./doc/DEPLOYMENT.md) | 部署配置和环境搭建说明 |
| [项目结构](./doc/PROJECT_STRUCTURE.md) | 项目目录结构架构说明 |
| [数据库设计](./doc/DATABASE_DESIGN.md) | 数据库表结构设计文档 |
| [API接口文档](./doc/API_DOCS.md) | 后端API接口说明和示例 |

## 项目亮点

- **工程化：** 环境配置、代码规范、构建与产物优化的完整流程
- **业务能力：** 鉴权流程、路由守卫、状态管理与接口封装
- **体验优化：** 骨架屏、懒加载、预加载、无障碍与响应式适配
- **组件与分层：** 可复用组件拆分、按领域分组与别名引入
- **后台管理：** 基础CRUD、数据管理与配置面板，支持后续扩展权限与统计
- **快速部署：** 基于 Docker 的一键部署方案，支持多环境配置与自动化部署

## 技术栈

> 💡点击可展开查看详细内容
<details>
<summary><b>前端技术</b></summary>

- **Vue.js 3** - 前端框架（Composition API）
- **Vue Router 4** - 路由管理
- **Pinia** - 状态管理
- **Vite** - 构建工具和开发服务器
- **Axios** - HTTP客户端
- **VueUse** - Vue组合式工具库
- **CropperJS** - 图片裁剪
- **Vue3 Emoji Picker** - 表情选择器
- **svg-captcha** - 验证码生成器
</details>
