# Snavigation - 基于 IMSYY 的个人导航

<p align="center">
  <!-- 创建日期 --><img alt="GitHub Created At" src="https://img.shields.io/github/created-at/xyz66882/Snavigation-?logo=github&label=%E5%88%9B%E5%BB%BA%E6%97%A5%E6%9C%9F">
  <!-- 下载量 --><a href="https://github.com/xyz66882/Snavigation-/releases"><img src="https://img.shields.io/github/downloads/xyz66882/Snavigation-/total?logo=github&label=%E4%B8%8B%E8%BD%BD%E9%87%8F"></a>
  <!-- 贡献者 --><a href="https://github.com/xyz66882/Snavigation-/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/xyz66882/Snavigation-?logo=github&label=%E8%B4%A1%E7%8C%AE%E8%80%85"></a>
  <!-- 最新版本 --><a href="https://github.com/xyz66882/Snavigation-/releases/"><img src="https://img.shields.io/github/release/xyz66882/Snavigation-?logo=github&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%AC%A1"></a>
  <!-- 问题数 --><a href="https://github.com/xyz66882/Snavigation-/issues"><img src="https://img.shields.io/github/issues-raw/xyz66882/Snavigation-?logo=github&label=%E9%97%AE%E9%A2%98"></a>
  <!-- 讨论数 --><a href="https://github.com/xyz66882/Snavigation-/discussions"><img src="https://img.shields.io/github/discussions/xyz66882/Snavigation-?logo=github&label=%E8%AE%A8%E8%AE%BA"></a>
  <!-- 仓库大小 --><a href="https://github.com/xyz66882/Snavigation-"><img src="https://img.shields.io/github/repo-size/xyz66882/Snavigation-?logo=github&label=%E4%BB%93%E5%BA%93%E5%A4%A7%E5%B0%8F"></a>
</p>

> 由 [Fuzhihao](https://github.com/xiaohao8) 修改而来  
> 演示网站：[Suosu](https://suosu.ct.ws/)  

---

## 🌟 功能说明

- **心知天气 vs 高德地图 API**  
  - 心知天气需自行注册并申请密钥  
  - 高德地图提供免费密钥（由 AI 分配）  

- **核心改进**  
  - 修复天气加载问题，无需刷新即可更换壁纸  
  - 移除强制刷新建议（原需 `Ctrl + F5`）  
  - 支持本地化资源（JS/CSS/IE 重定向脚本）  
  - 壁纸链接放宽 + 变暗开关控制  

---

## 🔑 心知天气 API 密钥获取

1. 访问 [心知天气官网](https://www.seniverse.com) 注册账号  
2. 在控制台创建 **免费版项目**  
3. 复制生成的私钥（Key）  
4. 打开 `main.js` 文件，填写 Key 到对应位置  

---

## 🛠 更新日志

### ✅ 1.0 版本
- 修复原版天气无法加载问题  
- 无需刷新即可更换壁纸  

### ✅ 2.0 版本
- 壁纸链接限制放宽  
- 新增壁纸变暗开关功能  

### ✅ 3.0 版本
- 将网络依赖的 JS/CSS 资源本地化  
- 修复 IE 浏览器重定向问题（改用本地文件夹）  

---

## 📦 使用建议

- **安全提示**：建议对 `main.js` 进行 JavaScript 混淆处理，防止 API Key 泄露  
- **自定义修改**：未修改部分可自行调整（如样式、功能扩展等）  
- **部署方式**：纯静态网站，解压后直接使用  

---

## 📌 其他信息

- **原作者**：[xiaohao8](https://github.com/xiaohao8)  
- **文档更新时间**：2025-06-24  






![无标题](https://github.com/user-attachments/assets/4db14c40-0e1d-4a81-9ef0-d809154e8d7a)
