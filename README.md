# 🛡️ ShizukuGuard

> **一款基于 Shizuku/Root 的轻量化安卓底层主动防御系统（EDR）。**
> 纯本地运行，极致轻巧，专治现代无头间谍软件与高级恶意行为。

## 📖 项目介绍

**ShizukuGuard** 是一款适用于安卓平台的深度安全防护项目。本项目为**纯成品仓库**（不包含源码），旨在弥补当前市面上常规安全软件（如重度依赖特征库的工具）在面对现代高级间谍软件时的防御空缺。

## 🏗️ 软件架构

*   **UI 层**：通过纯 HTML 结合丰富的 CSS 动画构建，极致轻量，无需加载臃肿的图片资源。
*   **底层驱动**：基于 `Shizuku` 或 `Root` 权限实现高维度的拦截、冻结与物理清除。
*   **数据处理**：完全本地化分析。无自建服务器，不收集任何用户隐私；仅通过知名威胁情报黑名单库获取恶意链接/僵尸网络 IP 等核心数据。

## 🚀 安装与授权教程

1.  **准备环境**：下载并安装 [Shizuku](https://shizuku.rikka.app/)，配置其运行环境。
2.  **授予权限**：安装并打开 ShizukuGuard，根据提示授予 Shizuku 权限。
    *   *注：如果您需要最完整的底层防护体验，可以额外授予 Root 权限。请放心，本软件无任何信息收集行为。*
    *   *⚠️ 进阶玩法：如果您觉得配置 Shizuku 过于繁琐，可以直接使用 **游龙工具的“安全护盾”** 中的内置 Shizuku 赋予我们权限（推荐组合：游龙工具 + ShizukuGuard）。*
    *   *请注意：Root 仅作为 Shizuku 的辅助增强，即便有了 Root，依然需要 Shizuku 作为基础通讯桥梁。*
3.  **启动防护**：赋予软件所需的权限并启动防护服务。如果为了防止恶意软件恶意卸载，建议开启“设备管理员”功能。

## 💡 使用说明与建议

1.  **按需开启**：您可以根据自身使用习惯适度调整防护级别。如果您经常从不明网站下载文件，强烈建议开启最高级别防护。
2.  **与游龙工具搭配使用**：
    *   我们与游龙工具有着本质的定位差异。游龙工具专精于防御“无障碍锁机/勒索病毒”，而我们是**通用型主动防御（主打防间谍、防盗版数据窃取）**。
    *   建议两者同时使用。**我们已将游龙工具加入白名单**，绝不会随意拦截它。
    *   *注意：游龙工具的“摇一摇/音量键”触发急救时会持续 kill 所有软件，这可能导致 ShizukuGuard 暂时停止防护。如果您遭遇锁机，10秒内未触发主动防护，请使用游龙的物理急救功能。*
3.  **作者的话**：本人对游龙工具及其作者抱有极大的敬意。如游龙工具的作者看到了本项目，欢迎随时联系交流！

## 🌟 开发初衷

我看到了游龙工具在防锁机领域的强大能力，但在实际测试中发现，面对现代间谍软件，其过于依赖特征库/病毒库的短板较为明显。因此，我开发了这款软件作为补充。

ShizukuGuard 的锁机防护能力不及游龙工具，但它的长处在于“通用型主动防御”，希望能弥补这块市场欠缺，让更多人免受间谍软件的侵害。

如果这个项目帮到了你，请不吝点亮一颗 **Star ⭐**！GitHub 上有同步项目，也欢迎推荐给身边的人。如果使用人数够多，我会考虑建立交流群。

## ⚖️ 项目许可证与免责声明

*   **闭源声明**：本项目为完全闭源项目，不使用任何开源许可证。
*   **权利保留**：作者保留对该项目的所有权利。未经允许，请勿用于商业用途或二次打包分发。
*   **无担保声明**：本项目不对更新做任何保证（按现状提供）。
详细内容：
ShizukuGuard Custom Proprietary License (Version 1.0)
ShizukuGuard 自定义专有软件许可协议（第一版）

Copyright (c) 2026 TSS-ARO. All Rights Reserved.
版权所有 (c) 2026 TSS-ARO。保留所有权利。

【中文版】

1. 授权范围 (Grant of License)
本软件（ShizukuGuard，包含编译后的 APK 文件及相关文档）的版权所有者仅授予您个人的、非排他性的、不可转让的、非商业性质的许可，允许您下载、安装并运行本软件的官方未修改版本，用于个人设备的安全防护。

2. 严格禁止的行为 (Restrictions)
未经版权所有者明确的书面许可，严禁实施以下行为：
- 商业使用：不得将本软件用于任何商业目的，包括但不限于捆绑销售、企业级分发、或者通过本软件直接/间接获利。
- 逆向工程与修改：不得对本软件进行反编译、反汇编、逆向工程、修改或创建衍生作品。
- 二次分发：不得以任何形式（包括但不限于网盘分享、应用商店上架、打包进第三方 ROM 等）重新分发、出租、出售本软件的安装包。

3. 免责声明 (Disclaimer of Warranty & Liability)
本软件按“现状”提供，不提供任何明示或暗示的担保，包括但不限于对适销性、特定用途适用性的担保。
鉴于本软件涉及底层的 Shizuku/Root 权限及高危操作（如强制卸载、系统级冻结等），使用本软件存在导致设备功能异常、数据丢失甚至系统崩溃的风险。
您必须自行承担使用本软件的全部风险。在任何情况下，版权所有者均不对因使用或无法使用本软件而产生的任何直接、间接、附带或特殊的损害（包括但不限于设备变砖、数据损坏、财产损失）承担任何法律责任。

4. 权利保留 (Reservation of Rights)
本许可证未明确授予您的所有权利，均由版权所有者保留。版权所有者保留随时更改本软件功能、停止更新或修改本协议的权利。

5. 违约终止 (Termination)
一旦您违反本协议中的任何条款，本授权即刻自动终止。您必须立即停止使用本软件并从所有设备中彻底删除。

====================================================================

【English Version】

1. Grant of License
The copyright holder of this software (ShizukuGuard, including the compiled APK and documentation) grants you a personal, non-exclusive, non-transferable, non-commercial license to download, install, and run the official unmodified version of this software for personal device security protection.

2. Restrictions
Without the express written permission of the copyright holder, you are strictly prohibited from:
- Commercial Use: Using this software for any commercial purposes, including bundling, enterprise distribution, or directly/indirectly profiting from it.
- Reverse Engineering & Modification: Decompiling, disassembling, reverse engineering, modifying, or creating derivative works of this software.
- Redistribution: Redistributing, renting, or selling the software package in any form (including but not limited to cloud sharing, app store publishing, or bundling into custom ROMs).

3. Disclaimer of Warranty & Liability
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.
Given that this software involves low-level Shizuku/Root permissions and high-risk operations, using it carries the risk of device malfunction, data loss, or system crash. YOU ASSUME THE ENTIRE RISK OF USING THIS SOFTWARE. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING FROM THE USE OR INABILITY TO USE THIS SOFTWARE.

4. Reservation of Rights
All rights not expressly granted to you in this license are reserved by the copyright holder. The copyright holder reserves the right to change features, stop updating, or modify this agreement at any time.

5. Termination
This license terminates automatically if you violate any term of this agreement. You must immediately cease using the software and delete it from all devices.