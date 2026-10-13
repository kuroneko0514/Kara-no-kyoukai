# 空之境界 角色卡在线资源与前端仓库

本仓库为 SillyTavern 角色卡《空之境界》的线上静态资源库与远程 UI 托管中心。

## 目录结构

* `/ui/status_bar.html` : 讲谈社文库风格状态栏前端页面（支持热更新）
* `/立绘/` : 各角色立绘与头像库
  * 各角色子文件夹下统一包含 `头像.jpg` 以及序号命名的 `1.jpg`, `2.jpg` ... 立绘

## CDN 访问规则 (基于 jsDelivr)

* **状态栏 UI 直链**:
  `https://testingcf.jsdelivr.net/gh/kuroneko0514/Kara-no-kyoukai@main/ui/status_bar.html`
* **角色头像直链**:
  `https://testingcf.jsdelivr.net/gh/kuroneko0514/Kara-no-kyoukai@main/立绘/{角色名}/头像.jpg`
* **角色立绘直链**:
  `https://testingcf.jsdelivr.net/gh/kuroneko0514/Kara-no-kyoukai@main/立绘/{角色名}/{序号}.jpg`
