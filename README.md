# 商城活动管理后台 Demo

基于原生 HTML、CSS、JavaScript 的可交互后台原型，使用 GitHub Pages 部署。

## 在线预览

https://beaver123-sketch.github.io/mall-campaign-admin/

## 本地预览

直接使用浏览器打开 `index.html` 即可。

## 当前包含

- 活动列表：查询、新建、编辑、复制、上下架
- 活动基础信息：时间、地区、APP、客户端配置
- 活动入口：商城首页 Banner、弹窗、商品详情入口
- 页面搭建：单页 / 多 Tab、模块添加及管理
- 页面皮肤：默认皮肤、区域定制、素材配置
- H5 手机预览
- 商品 ID 关联：不重复维护商品属性
- 促销配置 ID 关联
- 商城榜单关联
- 活动规则、多语言 Key、分享配置
- 发布管理、活动数据、操作记录

## 部署

仓库通过 `.github/workflows/deploy-pages.yml` 自动部署。

- 推送到 `main` 分支会触发部署。
- 也可以在 GitHub Actions 中手动运行 `Deploy static site to GitHub Pages`。

## 原型说明

当前为前端交互 Demo，活动及关联数据使用演示数据，配置保存在当前浏览器的 `localStorage`。尚未连接真实商品、促销、榜单 API，也不代表生产环境的权限、数据及发布校验逻辑。
