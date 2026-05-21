

# 信用卡包 (Credit Cards Manager)

一款专注于信用卡信息管理的 Android 应用，帮助您高效管理多张信用卡及各类权益活动。

[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![API](https://img.shields.io/badge/API-24%2B-yellow)](https://developer.android.com/guide/topics/manifest/uses-sdk-element#api)
[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen)](https://www.android.com)

---

## 📱 应用简介

**信用卡包** 是一款完全离线的信用卡管理工具，致力于为用户提供安全、便捷的信用卡信息管理服务。软件无需网络连接，所有数据均存储在本地，无任何广告，所有功能均可免费使用。

---

## ✨ 核心功能

### 💳 卡片管理

- **多卡管理**：支持添加和管理多张信用卡信息
- **借记卡管理**：支持信用卡与借记卡统一管理
- **卡片关联**：支持一对多关联，灵活管理主卡与附属卡
- **堆叠切换**：新增卡片堆叠切换动画，浏览体验更流畅
- **信息统计**：直观展示信用卡各类数据统计
- **智能提醒**：账单日、还款日等重要日期提醒

### 🎁 活动权益管理

- **智能创建**：一键智能创建活动，快速绑定卡片与权益
- **积分管理**：记录和管理各银行积分活动
- **立减活动**：跟踪各类消费立减优惠
- **权益管理**：统一管理信用卡各类权益活动
- **活动分类**：支持多维度分类管理不同活动类型
- **日历同步**：活动可一键添加到系统日历

### 🔒 安全隐私

- **应用锁**：支持生物识别和 PIN 码应用锁
- **完全离线**：所有数据本地存储，无需联网
- **无广告**：纯净使用体验，无任何广告干扰
- **数据安全**：用户数据完全由自己掌控
- **敏感数据加密**：敏感信息采用加密存储

### 📊 实用功能

- **桌面小部件**：支持桌面小组件（部分设备）
- **剪贴板解析**：支持剪贴板账单自动解析
- **待还管理**：待还金额管理与快捷切换
- **银行管理**：支持自定义银行排序与管理

---

## 🏗️ 软件架构

```
credit_cards_manager/
├── app/                    # 应用主模块
├── data/                   # 数据层（本地数据库）
├── domain/                 # 业务逻辑层
└── presentation/           # 界面展示层
```

采用 Clean Architecture 设计模式，分层明确，便于维护和扩展。

---

## 📥 安装指南

### 环境要求

- Android 7.0 (API 24) 及以上系统
- 设备存储空间约 50MB

### 安装步骤

1. 下载最新版本的 APK 安装包（见下方版本发布）
2. 在 Android 设备上设置中允许"安装未知来源应用"
3. 下载并运行 APK 文件完成安装

> ⚠️ **注意**：建议从本仓库或官方渠道下载 APK，请勿安装来源不明的安装包

---

## 📦 版本发布

### 最新版本

| 版本 | 发布日期 | 下载地址 | 更新说明 |
|:----:|:--------:|:--------:|:---------|
| latest | - | [Gitee 发行版](https://gitee.com/aachen0/credit_cards_manager_repo/releases) | 详见发布页面 |
| v1.5.7 | 2026-05-04 | — | 重构每日提醒功能，确保每日都能收到准确的最新提醒 |
| v1.5.6 | 2026-05-03 | — | 新增剪贴板账单解析、待还金额管理、待还款卡片快捷切换 |
| v1.5.5 | 2026-05-01 | — | 新增每日定时提醒、银行自定义排序、活动提醒 |

> 所有版本均通过 Gitee 官方发行版发布，请前往 [发行版页面](https://gitee.com/aachen0/credit_cards_manager_repo/releases) 下载最新 APK。

---

## 📖 使用指南

### 快速开始

1. **添加信用卡**：在首页点击"+"按钮，填写卡片基本信息
2. **管理活动**：在活动页面创建权益活动并关联对应信用卡
3. **设置提醒**：在设置中配置账单日和还款日提醒
4. **查看统计**：在统计页面查看各类数据汇总

### 进阶使用

- **卡片关联**：为主卡添加附属卡，统一管理
- **活动绑定**：将权益活动与对应信用卡关联
- **数据备份**：定期备份数据以防丢失

---

## 📸 应用截图

| 首页 | 活动管理 | 统计分析 | 还款提醒 |
|:---:|:-------:|:-------:|:-------:|
| ![信用卡](./images/screenshot-cards.jpg) | ![活动](./images/screenshot-activity.jpg) | ![统计](./images/screenshot-stats.jpg) | ![提醒](./images/screenshot-reminder.jpg) |

---

## 🤝 贡献指南

欢迎任何形式的贡献！

1. **Fork** 本仓库
2. 创建功能分支 (`feat_xxx` 或 `fix_xxx`)
3. 提交您的更改
4. 创建 **Pull Request**

如有 Bug 报告或功能建议，请提交 [Issue](./issues)。

---

## 📄 开源协议

本项目基于 **MIT License** 开源，详见 [LICENSE](./LICENSE) 文件。

---

## 💖 支持与捐赠

本软件完全免费且开源，如果您觉得这个项目对您有帮助，欢迎支持开发者继续维护和改进。

### 捐赠方式
| 支付宝 | 微信支付 | 拉卡拉  |
|:---:|:-------:|:-------:|
| ![支付宝](./images/alipay.jpg) | ![微信支付](./images/wxpay.png) | ![拉卡拉](./images/lakala.jpg) |


### 获取支持

> 📌 如需获取持续最新版本，请添加 QQ 群：983445378
![QQ群](./images/qq-group.jpg)

---

## 📞 联系我们

- 项目主页：https://gitee.com/aachen0/credit_cards_manager_repo
- 问题反馈：提交 [Issue](./issues)

---

## 📋 隐私政策

本应用高度重视用户隐私，详细隐私政策请查阅 [PRIVACY_POLICY.md](./docs/PRIVACY_POLICY.md)。

> **离线声明**：本应用完全离线运行，不收集任何用户数据，所有信息仅存储在本地设备。

