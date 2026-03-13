# DECO7230 VR Construction Design App
## VR建筑设计与模拟应用

---

### About This Project / 关于这个项目

This is a VR application prototyping project I developed during the DECO7230 course at The University of Queensland. The project explores how VR technology can be applied to architectural design, allowing users to interact with buildings in an immersive environment.

这是我在昆士兰大学DECO7230课程期间开发的VR应用原型项目。该项目探索了如何将VR技术应用于建筑设计，让用户能够在沉浸式环境中与建筑进行交互。

---

### Project Evolution / 项目演进

#### Prototype 1: Paper Prototype
**Focus: Light Adjustment Interactions**

I started with a low-fidelity paper prototype to test the core concept. I created a paper-based terrain and wooden house model, then used a phone flashlight to simulate sunlight. Users could interact by moving the terrain or rotating a sun path board to adjust lighting angles.

Through testing with 4 volunteers, I found that moving the terrain was more intuitive than moving the sun board. This valuable feedback guided my later development.

我从一个低保真的纸质原型开始测试核心概念。我创建了纸质地形和木质房屋模型，用手机手电筒模拟阳光。用户可以通过移动地形或旋转太阳轨道板来调整光照角度。

通过对4名志愿者的测试，我发现移动地形比移动太阳板更直观。这个有价值的反馈指导了我后来的开发。

---

#### Prototype 2: Unity VR Implementation
**Focus: Zooming Interaction**

In Prototype 2, I implemented the application in Unity with Meta XR SDK. The main new feature is the **zooming interaction** - users can use a two-handed gesture to zoom in/out of the entire VR world. I also kept the sunlight adjustment and house placement interactions from the previous version.

The testing results showed that users were generally satisfied with the zooming interaction, though they needed some guidance to learn the gesture.

在Prototype 2中，我使用Meta XR SDK在Unity中实现了应用。主要新功能是**缩放交互**——用户可以使用双手手势来放大/缩小整个VR世界。我还保留了之前版本的阳光调整和房屋放置交互。

测试结果表明，用户对缩放交互总体上是满意的，尽管他们需要一些指导来学习这个手势。

---

#### Prototype 3: Wristband Menu System
**Focus: Optimization & New Interactions**

Based on feedback from Prototype 2, I added a **wristband menu system** on the user's left hand. This includes 7 buttons that allow users to:
- Select different house models
- Adjust sunlight direction with buttons (alternative to grabbing)
- View zooming gesture introduction
- Exit or restart the application

Testing showed that the wristband was quite intuitive - users could understand how to use it without guidance because it follows real-world design patterns.

根据Prototype 2的反馈，我在用户左手上添加了**腕带菜单系统**。这包括7个按钮，允许用户：
- 选择不同的房屋模型
- 用按钮调整阳光方向（替代抓取）
- 查看缩放手势介绍
- 退出或重启应用

测试表明，腕带相当直观——用户无需指导就能理解如何使用，因为它遵循现实世界的设计模式。

---

### File Structure / 文件结构

```
DECO7230/
├── Prototype 1/              # Paper prototype and testing
│   ├── storyboard/           # Design storyboards
│   ├── studio photo/         # Development process photos
│   └── data analytics.ipynb  # Test results analysis
│
├── Prototype 2/              # Unity VR implementation
│   ├── Screenshot in Unity/  # App screenshots
│   └── data analytics.ipynb  # Test results analysis
│
├── Prototype 3/              # Final prototype with wristband
│   ├── Screenshots/          # App screenshots
│   └── data analytics.ipynb  # Test results analysis
│
└── photo/                    # Project photos
```

---

### What's Included / 上传内容

This repository includes the following files suitable for a GitHub portfolio:

| Category | Description |
|----------|-------------|
| **Process Documentation** | Storyboards, screenshots, UI drafts showing design evolution |
| **Analysis** | `data analytics.ipynb` files with test results and visualizations |
| **Project Photos** | Development and testing photos |

### What's Excluded / 排除内容

Due to GitHub's file size limits and copyright concerns, the following are **NOT** included:

| Category | Reason |
|----------|--------|
| Unity Project | Too large, can be regenerated |
| Videos (~1GB) | Use external links (YouTube/Google Drive) |
| APK (130MB) | Use Itch.io or Google Drive |
| Course Materials | Copyright issues |

For the complete experience with videos and APK, please check the Google Drive links mentioned in my Statement of Delivery documents.

---

### Key Features / 主要功能

1. **Sunlight Adjustment** - Grab and move the sun model to change lighting angles
2. **Zooming** - Two-handed gesture to scale the VR world
3. **House Placement** - Grab and move buildings on the terrain
4. **Wristband Menu** - Button-based interaction for house selection and more

---

### Reflection / 反思

Through this project, I learned a lot about VR development and user testing. The most important thing I realized is that **optimization is an integral part of implementation**. Even with good interaction designs, continuous testing and improvement are essential for a good user experience.

I also learned that using **real-world design patterns** (like the wristband) can significantly reduce the learning curve for users. When participants tried the wristband menu, they could intuitively understand how to use it without any guidance.

通过这个项目，我学到了很多关于VR开发和用户测试的知识。我最重要的体会是**优化是实现的重要组成部分**。即使有好的交互设计，持续的测试和改进对于良好的用户体验也是必不可少的。

我还了解到，使用**现实世界的设计模式**（比如腕带）可以显著降低用户的学习曲线。当参与者尝试腕带菜单时，他们能够直观地理解如何使用它，无需任何指导。

---

### Contact / 联系方式

- **Name:** Jiepeng Huang (黄捷鹏)
- **Student ID:** 47352580
- **Course:** DECO7230 - Extended Reality (XR) Development
- **University:** The University of Queensland

---

*Last updated: March 2026*
