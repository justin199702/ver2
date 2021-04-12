# contactbook 聯絡簿專案

<a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/vue-2.6.10-brightgreen.svg" alt="vue">
  </a>
  <a href="https://github.com/ElemeFE/element">
    <img src="https://img.shields.io/badge/element--ui-2.8.2-brightgreen.svg" alt="element-ui">
  </a>
  <a href="https://github.com/lin-xin/vue-manage-system/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
  </a>
  <a href="https://github.com/lin-xin/vue-manage-system/releases">
    <img src="https://img.shields.io/github/release/lin-xin/vue-manage-system.svg" alt="GitHub release">
  </a>
  <a href="https://lin-xin.gitee.io/example/work/#/donate">
    <img src="https://img.shields.io/badge/%24-donate-ff69b4.svg" alt="donate">
  </a>

[專案設計文件](https://drive.google.com/drive/folders/1EGB_Yxj2owYqmkdckAvwbDZMXeWc9N5h?usp=sharing)
---
## 版本紀錄
2019\.04\.06\. 目前專案已設立，首頁開始製作

2019.04.07 流程圖大致完成，僅剩學生管理

---
## 功能流程
- 首頁
  - 登入頁面
  - 班級管理(預設)
  - 公告管理
  - 出勤管理
  - 訊息系統(以上為第一線老師可用，與APP相同)
  - 教師管理
  - 學生管理
  - 成績管理
  - 繳費管理

---




基于 Vue3 + Element Plus 的后台管理系统解决方案。[线上地址](https://lin-xin.gitee.io/example/work/)

> Vue2 版本请看 [tag-V4.2.0](https://github.com/lin-xin/vue-manage-system/tree/V4.2.0)

> React + Ant Design 的版本正在开发中，仓库地址：[react-manage-system](https://github.com/lin-xin/react-manage-system)

[English document](https://github.com/lin-xin/manage-system/blob/master/README_EN.md)

## 项目截图

### 登录

![Image text](https://github.com/lin-xin/manage-system/raw/master/screenshots/wms3.png)

### 首页

![Image text](https://github.com/lin-xin/manage-system/raw/master/screenshots/wms1.png)

## 赞赏

请作者喝杯咖啡吧！(微信号：linxin_20)

![微信扫一扫](https://lin-xin.gitee.io/images/weixin.jpg)

## 前言

该方案作为一套多功能的后台框架模板，适用于绝大部分的后台管理系统（Web Management System）开发。基于 Vue3，使用 vue-cli3 脚手架，引用 Element Plus 组件库，方便开发快速简洁好看的组件。分离颜色样式，支持手动切换主题色，而且很方便使用自定义主题色。

## 功能

-   [x] Element Plus
-   [x] 登录/注销
-   [x] Dashboard
-   [x] 表格
-   [x] Tab 选项卡
-   [x] 表单
-   [x] 图表 :bar_chart:
-   [ ] 富文本编辑器
-   [ ] markdown 编辑器
-   [x] 图片拖拽/裁剪上传
-   [ ] 支持切换主题色 :sparkles:
-   [ ] 列表拖拽排序
-   [x] 权限测试
-   [x] 404 / 403
-   [x] 三级菜单
-   [x] 自定义图标
-   [ ] 可拖拽弹窗
-   [x] 国际化

## 安装步骤

```
git clone https://github.com/lin-xin/vue-manage-system.git      // 把模板下载到本地
cd vue-manage-system    // 进入模板目录
npm install         // 安装项目依赖，等待安装完成之后，安装失败可用 cnpm 或 yarn

// 开启服务器，浏览器访问 http://localhost:8080
npm run serve

// 执行构建命令，生成的dist文件夹放在服务器下即可访问
npm run build


## License

[MIT](https://github.com/lin-xin/vue-manage-system/blob/master/LICENSE)
