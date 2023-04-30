[![en](https://img.shields.io/badge/lang-en-red.svg)](./README.en.md)

# 🍅 懒番茄

一款免费、现代和开源的计时器 Mac 桌面端应用。

[![](https://img.shields.io/badge/%E9%93%BE%E6%8E%A5-%E7%82%B9%E6%88%91%E4%B8%8B%E8%BD%BD-brightgreen)](https://github.com/Penggeor/lai-todo/releases/download/1.0.0/LAI.TODO_0.1.0_aarch64.dmg)

![显示工作部分的应用程序屏幕截图。](./public/assets/img/ProductImg_Default.png)

## 它是什么？

*懒番茄*是一款运行在客户端中的番茄钟应用。 它可以帮助您管理时间，这样您就可以做更多的工作而不是看可爱猫咪的视频 😿

## 你得到什么

这是此应用程序包含的功能列表。

### ⏰ **多种计时器样式**

- (12:34) _traditional_ <br>
  对于那些想确切知道喝咖啡休息时间还剩多少时间的人来说，具有秒精度的经典方法
- (12 分钟）_approximate_ <br>
  这个以分钟精度显示时间，因此您知道还剩多少时间，但您的眼睛不会盯着计数器，因为它不会每秒都在变化
- (50%) _percentage_ <br>
  信息量更少，这个可以让您远离计算“在剩余的 12 分 34 秒内我能做什么？”的分心。

### 💡 **友好、专注和干净的用户界面**

**这只是必需品**：中间的计时器和底部的控件。 其他一切都可以关闭：

- 在顶部快速浏览您的日程安排
- 智能待办事项清单
- 颜色编码的部分
- 背景中的彩色进度条

### 📑 **灵活的时间表**

- 单独调整会话长度或使用内置预设之一
- 设置长时间停顿的频率
- **跟踪超出计时器的时间**，不像其他计时器在时间到期时停止

### 🎵 **多种方式通知您**

- 完成一个部分时播放声音
- 桌面通知，这样你就不必一直检查你的浏览器

### ⚙ **很多选项**

- 按照您想要的方式设置您的日程安排
- 切换日程视图、进度条或待办事项列表
- 启用/禁用音频和/或桌面通知
- 更改显示的计划项目数
- 使用键盘控制你的计时器
- 深色和浅色主题
- ……未来还会有更多！

### ✅ **清洁待办事项**

- 为工作、暂停和长时间暂停部分设置单独的任务
- 仅在计时器运行时显示与您最相关的任务
- 在每个会话结束时自动删除已完成的任务
- 记住你跨会话的任务

### ✨ **其他值得拥有的功能**

- 记住您的设置
- 这是一个 _PWA_（渐进式 Web 应用程序）：速度很快，您可以通过浏览器安装它！
- 精美流畅的动画
- 设置向导让你开始
- 翻译成 5 种语言

### ✔ **超级轻量**

仅仅 5.6M。

### 👋 **开放开发**

任何人都可以查看源代码、提出问题（功能请求、错误报告）甚至提交他们自己的改进！

## 🖼 更多截图

![设置面板的显示部分](./public/assets/img/ProductImg_Settings.png)

![打开待办事项面板的传统计时器](./public/assets/img/ProductImg_TodoOpen.png)

## 🏗 如果您是开发人员

这是一个欢迎贡献的开源项目。 在打开问题、讨论或请求请求之前，请检查 [**贡献指南**](./CONTRIBUTING.md)！

### ❤ 技术，使用的包

- [**NuxtJS**](https://nuxtjs.org/)（ [**VueJS**](https://vuejs.org/)）
  - [`vue-i18n`](https://kazupon.github.io/vue-i18n/) 用于本地化
  - [`nuxt/google-fonts`](https://github.com/nuxt-community/google-fonts-module) 支持谷歌字体
  - [`Pinia`](https://pinia.vuejs.org/) 用于状态管理
- [**Tailwind CSS**](https://tailwindcss.com/)
- [Tabler Icons](https://tabler-icons.io/) 通过 [`vue-tabler-icons`](https://github.com/alex-oleshkevich/vue-tabler-icons)
- [Workbox](https://github.com/GoogleChrome/workbox) 作为 PWA service worker
- [`conventional-changelog/standard-version`](https://github.com/conventional-changelog/standard-version) 用于从[常规提交](https://www.conventionalcommits.org/en) 自动生成变更日志 /v1.0.0/)
- [Tauri](https://tauri.app/) 作为桌面的底层。

### 🛠 自己构建或运行应用程序

```狂欢
# 安装依赖
$ yarn install

# 启动应用，并且支持热重载
$ yarn tauri:dev

# 生成应用
$ yarn tauri:build
```

## ☕ 支持项目

如果您喜欢这个项目或者对您有帮助，请考虑 Star 🌟。 使用该应用程序时，您不会因为这样做而烦恼！
