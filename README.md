# 🛠️ EternalWrt Build Toolkit

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%20by-EternalWrt-blue?style=for-the-badge&logo=github" alt="EternalWrt">
  <img src="https://img.shields.io/badge/Upstream-ImmortalWrt-orange?style=for-the-badge" alt="Upstream">
  <img src="https://img.shields.io/badge/License-GPL--2.0-green?style=for-the-badge" alt="License">
</p>

> **为 EternalWrt 生态打造的标准化构建与开发工具集。**
> 本项目旨在通过自动化脚本简化固件编译环境的搭建、LuCI 插件开发及固件底层定制流程。

---

## 📂 工具清单 (Tools Inventory)

本项目集成的核心自动化脚本均同步自上游仓库，确保构建流程的标准化：

| 脚本名称 | 功能说明 | 来源 |
| :--- | :--- | :--- |
| 🛡️ `init_build_environment.sh` | **环境一键部署**：自动化安装编译所需的依赖包及交叉编译链。 | ImmortalWrt |
| 🌍 `convert_translation.sh` | **语言本地化**：处理 LuCI 插件的多语言 PO/Mo 文件转换。 | ImmortalWrt |
| 🔑 `create_acl_for_luci.sh` | **权限控制生成**：为自定义 LuCI 界面自动生成访问控制列表 (ACL)。 | ImmortalWrt |
| 🛰️ `create_ucitrack_for_luci.sh` | **配置服务追踪**：自动关联 UCI 配置与系统服务，实现动态联动。 | ImmortalWrt |
| ⚡ `modify-firmware.sh` | **固件二次定制**：对现成固件进行分区调整、属性修改或预装包植入。 | ImmortalWrt |
| 🔓 `xiaomi_ssh_calc_pwd.sh` | **小米 SSH 算号**：基于 SN 序列号计算小米系列路由器的 SSH 默认密码。 | ImmortalWrt |

---

## 🤝 致谢与溯源 (Acknowledgments)
本项目中的核心自动化脚本及构建逻辑深度参考并引用了 ImmortalWrt 项目及其附属工具集。

我们衷心感谢 ImmortalWrt 团队及其所有贡献者为开源固件社区提供的卓越工具。
