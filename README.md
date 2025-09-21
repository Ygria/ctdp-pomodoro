# ctdp-pomodoro

如果你喜欢这个项目，请随手给我点个小星星谢谢✨～
<img width="1282" height="276" alt="image" src="https://github.com/user-attachments/assets/7a08fa44-9c6d-4ad7-88b0-a685eeac4fa3" />



基于知乎大佬 [@edmond](https://www.zhihu.com/people/mount_cristo) 理论做的 ADHD 专用番茄钟 Obsidian 插件，电脑、手机端均可使用。

网页版：https://pomodoro.ygria.site/

参考原理网址 [# 如何提高自制力？](https://www.zhihu.com/question/19888447/answer/1930799480401293785)

1. 延迟启动，现在就开始很有难度，但是预约几分钟后开始就没什么心理压力，用一个动作来给自己心理暗示开始
2. 神圣座位和“下必为例”，一旦确定了每次任务的规则，就要确保遵守，可以修改规则，但也就让单个任务的含金量变低
3. 链条。用连续打卡的激励➕断卡清零来双重保证任务完成
4. 小步迭代，直到完美。准备做一个类似于文明里的科技树，根据任务成就来解锁加点。

# CTDP 番茄钟 v1.0



![CTDP Logo](https://img.shields.io/badge/CTDP-番茄钟-tomato?style=for-the-badge&logo=clock)

**跨平台ADHD友好的番茄钟应用**

[![Version](https://img.shields.io/badge/version-v1.0.0-blue.svg)](https://github.com/Ygria/ctdp-pomodoro/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Obsidian%20%7C%20Web%20%7C%20Android-lightgrey.svg)](#平台支持)

[🚀 立即使用](#快速开始) · [📱 下载安装](#下载安装) · [📖 使用文档](#使用文档) · [🐛 问题反馈](https://github.com/Ygria/ctdp-pomodoro/issues)

</div>

## ✨ 项目简介

**CTDP 番茄钟**是一个专为ADHD人群设计的跨平台时间管理应用，基于知乎大佬[@edmond](https://www.zhihu.com/people/mount_cristo)的专注理论开发。支持Obsidian插件、Web浏览器和Android移动端，通过科学的任务管理和技能成长系统，帮助用户建立良好的专注习惯。

### 🎯 设计理念

基于ADHD专注四大原则：

1. **🕐 延迟启动** - 预约机制降低开始任务的心理压力
2. **🎪 神圣座位** - 严格的任务规则确保执行质量  
3. **⛓️ 链条激励** - 连续打卡激励 + 断卡清零的双重保证
4. **🌱 小步迭代** - 技能树系统引导持续成长

### 🌟 核心特色

- **🍅 智能番茄钟** - 预约→专注→反馈的完整流程
- **📋 任务管理** - 9种分组、计时/开关任务、规则追踪
- **🌟 技能成长树** - 基于任务成就的条件解锁系统
- **📊 数据统计** - 可视化图表、执行分析、成长追踪
- **🔔 跨平台通知** - 三平台适配的智能提醒系统
- **☁️ 数据同步** - 统一接口的多端数据管理

### 🏆 功能亮点

| 功能模块 | 核心能力 | 特色优势 |
|---------|---------|---------|
| 📋 **任务管理** | 9种任务分组、双类型任务、规则历史 | ADHD友好的任务设计 |
| 🍅 **番茄钟** | 预约缓冲、精准计时、暂停统计 | 降低开始阻力，提高完成率 |
| 🌟 **技能树** | 条件解锁、进度追踪、成就激励 | 游戏化成长，长期动力 |
| 📊 **数据分析** | 日历视图、统计图表、效率分析 | 科学量化，持续改进 |
| 🔔 **通知系统** | 三平台适配、智能提醒、操作按钮 | 及时反馈，不错过重要时刻 |
| 🔄 **跨平台** | 数据同步、一致体验、灵活部署 | 随时随地，无缝切换 |

## 🚀 快速开始

### 在线体验
- 🌐 **Web版本**: [在线试用](https://your-domain.com) - 无需安装，浏览器即用
- 📱 **移动端**: 扫描二维码下载APK

### 本地安装
- 🔌 **Obsidian插件**: 适合笔记重度用户
- 📱 **Android应用**: 原生移动体验

## 📱 下载安装

### 🔄 自动发布

项目采用GitHub Actions自动构建发布，每次打tag都会自动生成多平台安装包：

- **Obsidian插件包**: `obsidian-ctdp.zip`
- **示例仓库**: `obsidian-sample-vault.zip` 
- **Android APK**: `ctdp-pomodoro-{version}.apk`

### 📥 下载方式

#### 方式一：GitHub Releases (推荐)

1. 访问 [Releases页面](https://github.com/Ygria/ctdp-pomodoro/releases)
2. 选择最新版本 `v1.0.x`
3. 根据需要下载对应文件：
   - **Obsidian插件**: `obsidian-ctdp.zip`
   - **示例仓库**: `obsidian-sample-vault.zip`
   - **Android应用**: `ctdp-pomodoro-v1.0.x.apk`

#### 方式二：直接链接

```bash
# 最新版本下载链接
wget https://github.com/Ygria/ctdp-pomodoro/releases/latest/download/obsidian-ctdp.zip
wget https://github.com/Ygria/ctdp-pomodoro/releases/latest/download/ctdp-pomodoro-v1.0.0.apk
```

## 🔧 安装指南

### 📋 Obsidian插件安装

#### 方法一：手动安装 (推荐)

1. **下载插件包**
   ```bash
   # 下载最新版本
   curl -LO https://github.com/Ygria/ctdp-pomodoro/releases/latest/download/obsidian-ctdp.zip
   ```

2. **解压安装**
   - 解压 `obsidian-ctdp.zip` 到你的仓库插件目录
   - 路径: `{你的仓库}/.obsidian/plugins/obsidian-ctdp/`
   
3. **启用插件**
   - 打开Obsidian → 设置⚙️ → 社区插件
   - 关闭"安全模式"
   - 刷新已安装插件列表
   - 找到"CTDP 番茄钟"并启用

4. **开始使用**
   - 点击左侧工具栏的🍅图标
   - 或使用命令面板搜索"CTDP"

#### 方法二：示例仓库体验

1. **下载示例仓库**
   ```bash
   curl -LO https://github.com/Ygria/ctdp-pomodoro/releases/latest/download/obsidian-sample-vault.zip
   ```

2. **解压并使用**
   - 解压到任意目录
   - 用Obsidian打开解压后的文件夹
   - 插件已预配置，可直接体验

#### 故障排除

**插件不显示？**
- 确认文件结构正确：
  ```
  .obsidian/plugins/obsidian-ctdp/
  ├── main.js
  ├── styles.css
  └── manifest.json
  ```

**启用失败？**
- 检查Obsidian版本 ≥ 0.15.0
- 确认已关闭安全模式
- 重启Obsidian后再试

### 🌐 Web版本使用

访问地址：

https://pomodoro.ygria.site/


#### Web版特性

- ✅ **免安装**: 浏览器直接访问
- ✅ **通知支持**: 浏览器原生通知 + Toast提示
- ✅ **数据持久化**: localStorage自动保存
- ✅ **PWA支持**: 可添加到主屏幕
- ✅ **响应式设计**: 适配桌面和移动设备

### 📱 Android APK安装

#### 安装前准备

1. **设备要求**
   - Android 7.0+ (API Level 24+)
   - 存储空间 ≥ 50MB

2. **开启未知来源**
   - 设置 → 安全 → 未知来源应用
   - 或安装时按提示开启

#### 安装步骤

1. **下载APK**
   ```bash
   # 手机浏览器下载
   https://github.com/Ygria/ctdp-pomodoro/releases/latest/download/ctdp-pomodoro-v1.0.0.apk
   ```

2. **安装应用**
   - 点击下载的APK文件
   - 按照提示完成安装
   - 首次启动会请求通知权限

3. **权限配置**
   - **通知权限**: 必需，用于番茄钟提醒
   - **震动权限**: 可选，增强提醒效果
   - **网络权限**: 可选，用于数据同步

#### Android版特性

- ✅ **原生体验**: Capacitor包装的原生应用
- ✅ **系统通知**: 原生通知栏提醒
- ✅ **震动反馈**: 任务完成震动提示
- ✅ **后台运行**: 支持后台计时
- ✅ **手势操作**: 触控友好的交互设计

#### APK签名验证

为了安全，可以验证APK签名：

```bash
# 使用keytool验证
keytool -printcert -jarfile ctdp-pomodoro-v1.0.0.apk

# 检查签名信息
jarsigner -verify -verbose -certs ctdp-pomodoro-v1.0.0.apk
```

#### 常见问题

**安装失败？**
- 检查设备存储空间
- 确认已开启未知来源
- 尝试重新下载APK

**通知不显示？**
- 检查应用通知权限
- 确认系统勿扰模式设置
- 重启应用后再试

## 📖 使用文档

### 🎯 基础使用流程

#### 1. 创建第一个任务

1. **点击"+"按钮**创建新任务
2. **填写任务信息**：
   - 任务名称: "学习TypeScript"
   - 任务类型: Timer (25分钟)
   - 任务分组: "科技"
   - 任务图标: 📚
3. **设置执行规则**: "专注学习，不查看手机"
4. **配置时间**:
   - 预约时长: 5分钟
   - 执行时长: 25分钟
5. **保存任务**

#### 2. 开始番茄钟

1. **选择任务**点击"开始"按钮
2. **预约阶段**: 5分钟准备时间
   - 整理桌面、准备材料
   - 调整心态、明确目标
3. **专注阶段**: 25分钟执行时间
   - 按照任务规则专注执行
   - 可暂停但会记录次数
4. **完成阶段**: 填写执行反馈
   - 选择心情: 😊 专注
   - 填写感想: "学习顺利，理解了泛型概念"
   - 评分: ⭐⭐⭐⭐⭐

#### 3. 查看统计数据

1. **访问统计页面**
2. **查看执行记录**:
   - 任务完成情况
   - 时长分布统计
   - 效率趋势分析
3. **分析成长数据**:
   - 连胜记录
   - 技能解锁进度
   - 成就里程碑

### 🌟 高级功能使用

#### 技能树系统

1. **创建技能**:
   - 技能名称: "专注大师"
   - 技能描述: "能够持续专注25分钟以上"
   - 解锁条件: 完成"学习"类任务 ≥ 10次

2. **条件配置**:
   ```
   AND条件组:
   - 任务完成次数 ≥ 10次
   - 累计专注时长 ≥ 5小时
   - 平均评分 ≥ 4分
   ```

3. **进度追踪**:
   - 实时查看解锁进度
   - 各项条件完成状态
   - 预估解锁时间

#### 数据导出导入

1. **导出数据**:
   ```javascript
   // 在浏览器控制台执行
   const data = localStorage.getItem('ctdp-data');
   const blob = new Blob([data], {type: 'application/json'});
   const url = URL.createObjectURL(blob);
   // 下载数据文件
   ```

2. **导入数据**:
   ```javascript
   // 读取数据文件并导入
   const importData = JSON.parse(fileContent);
   localStorage.setItem('ctdp-data', JSON.stringify(importData));
   ```

### 🔧 自定义配置

#### 全局设置

1. **用户偏好**:
   - 用户名: 个性化称呼
   - 默认时长: 25分钟 (可调整)
   - 完成动画: 开启庆祝效果
   - 通知设置: 声音、震动等

2. **任务模板**:
   ```json
   {
     "name": "深度学习模板",
     "type": "timer",
     "duration": 45,
     "rules": "专注学习，定期做笔记",
     "taskGroup": "科技"
   }
   ```

#### 通知自定义

1. **Obsidian环境**:
   - 自定义Notice样式
   - 状态栏显示偏好
   - 音效选择

2. **Web环境**:
   - 浏览器通知权限
   - Toast显示位置
   - 页面标题更新

3. **Android环境**:
   - 通知频道设置
   - 震动模式选择
   - 勿扰时间配置

### 📊 数据分析指南

#### 效率分析

1. **完成率统计**:
   - 日完成率趋势
   - 周期性分析
   - 任务类型对比

2. **时长分析**:
   - 专注时长分布
   - 暂停频率统计
   - 效率峰值时段

3. **质量评估**:
   - 满意度评分趋势
   - 心情状态分析
   - 规则遵守情况

#### 成长追踪

1. **连胜记录**:
   - 当前连胜天数
   - 历史最佳记录
   - 连胜中断分析

2. **技能进度**:
   - 已解锁技能数
   - 正在进行的技能
   - 预期解锁时间

3. **成就系统**:
   - 里程碑达成
   - 成就徽章收集
   - 成长轨迹回顾



### 问题反馈

- 🐛 **Bug报告**: [Issues](https://github.com/Ygria/ctdp-pomodoro/issues)
- 💡 **功能建议**: [Discussions](https://github.com/Ygria/ctdp-pomodoro/discussions)
- 📖 **文档改进**: 直接提交PR

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

## 🙏 致谢

- [@edmond](https://www.zhihu.com/people/mount_cristo) - ADHD专注理论提供者
- [Obsidian](https://obsidian.md) - 优秀的笔记平台
- [Radix UI](https://radix-ui.com) - 无障碍UI组件库
- [Capacitor](https://capacitorjs.com) - 跨平台应用框架

## 📱 平台支持

| 平台 | 状态 | 版本 | 特性 |
|------|------|------|------|
| 🔌 Obsidian | ✅ 已发布 | v1.0.0 | 插件集成、文件存储 |
| 🌐 Web | ✅ 已发布 | v1.0.0 | 在线使用、PWA支持 |
| 📱 Android | ✅ 已发布 | v1.0.0 | 原生体验、系统通知 |
| 🍎 iOS | 🔄 计划中 | - | 原生开发中 |
| 🖥️ 桌面版 | 🔄 计划中 | - | Electron包装 |

---

<div align="center">

**🍅 开始你的专注之旅吧！**

[立即下载](https://github.com/Ygria/ctdp-pomodoro/releases) · [在线体验](#) · [查看文档](#使用文档)

*如果这个项目对你有帮助，请考虑给我们一个⭐*

</div>


