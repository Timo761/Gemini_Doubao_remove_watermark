# [分享] 自用 AI 去水印/下载全能助手 (Gemini + 豆包)

> 💡 **简介**
> 写了一个油猴脚本，主要解决平时用 Gemini 和豆包时的痛点。
> 开源在 GitHub，欢迎大家试用。

## ✨ 主要功能
* ✅ **Gemini**: 自动去除图片水印，还原纯净图片
* ✅ **豆包**: 支持批量下载对话内容，方便存档

---

## 🚀 安装方法 (二选一)

### 方式 A：自动安装 (推荐)
如果你的浏览器已安装 **Tampermonkey (油猴)** 插件，点击下方按钮即可一键安装/更新：

[![点击安装](https://img.shields.io/badge/点击安装脚本-v2.0-success?style=for-the-badge&logo=tampermonkey)](https://github.com/gdz-web/Gemini_Doubao_remove_watermark/raw/refs/heads/main/remove.user.js)

[📂 GitHub 源码仓库传送门](https://github.com/gdz-web/Gemini_Doubao_remove_watermark)

---

### 方式 B：手动安装
如果你无法访问 GitHub，或者更喜欢手动操作，请按照以下步骤进行：

**1. 下载脚本文件**
点击下载：[remove.txt|attachment](upload://fe4X0JmodFUX2Bg2TmpXqu7F61w.txt) (1.0 MB)

**2. 修改文件名**
下载后，请将文件后缀名从 `.txt` 修改为 `.js` (即文件名改为 `remove.js`)。

**3. 导入油猴插件**
* 打开浏览器 -> 右上角三个点 `...` -> **扩展** -> **管理扩展**。
* 确保你已启用 Tampermonkey (油猴)。
    <img width="541" height="442" alt="image" src="https://github.com/user-attachments/assets/ed181d30-07b4-4801-898f-3d85e0966a5c" />
* 点击油猴扩展的 **“详细信息”** -> **“扩展选项”** (或者直接点击浏览器工具栏的油猴图标 -> 管理面板)。
    *(注：这里进入油猴的管理后台即可)*
   <img width="562" height="163" alt="image" src="https://github.com/user-attachments/assets/22d3f87c-a862-4e3a-8cd6-7ab915bf34cd" />

* 点击 **“实用工具”** 标签页 -> 在“导入”区域点击 **“选择文件”**。
* 选择刚才改名好的 `remove.js`。
   <img width="519" height="443" alt="image" src="https://github.com/user-attachments/assets/0ec86704-2757-48a9-b848-8fad9517e34d" />

* 跳转后点击 **“安装”** 即可。

---

## 🖼️ 效果展示

安装后打开 Gemini 或豆包，即可体验无水印下载及批量导出功能。

### 1. 豆包展示
**界面预览：**
<img width="697" height="718" alt="image" src="https://github.com/user-attachments/assets/7e7f19cb-d621-491b-aab2-18807f00ff99" />


**下载效果：**
<img width="826" height="439" alt="image" src="https://github.com/user-attachments/assets/1a1e7413-cffa-41c1-b6ad-01ae1b2e97d7" />


### 2. Gemini 展示
无需手动操作，显示的图片即为无水印版本，下载亦无水印。

**对比展示：**
<img width="818" height="520" alt="image" src="https://github.com/user-attachments/assets/e3998815-3688-4058-8fb4-43f2c0934b3a" />


---
如有问题，欢迎在评论区反馈！
