# ZTE OLT PNP Configuration Generator / 中兴 OLT PNP 配置脚本生成器

## Project Description / 项目简介

### English

**ZTE OLT PNP Configuration Generator** is a powerful tool designed specifically for broadband operation technicians to streamline the configuration process of ZTE OLT devices. This tool automates the generation of configuration scripts, significantly reducing manual effort and improving efficiency in managing optical network units (ONUs). Whether you're handling single-port setups or large-scale deployments, this tool provides a user-friendly interface and robust features to meet your needs.

#### Key Features
- **Automated Script Generation**: Generate complete configuration scripts with a single click, eliminating the need for manual command input.
- **Batch Port Configuration**: Supports batch configuration for multiple slots and ports, ideal for large-scale network deployments.  
  *Example*: Configure slots 1 and 2 with ports 1-2 and 1-3 respectively in one go.
- **Flexible VLAN Management**: Offers fixed, sequential, and random VLAN modes, with support for cross-port sequential increment.  
  *Example*: For slots 1, ports 1-2 with 64 ONUs each, VLANs can increment from 1 to 64 on port 1, then continue from 65 to 100 on port 2, looping back to 1 if needed.
- **Bandwidth and Traffic Control**: Configure DBA templates (4 types) and traffic profiles with customizable SIR and PIR settings.
- **Multicast Support**: Enable multicast with configurable VLAN settings (range: 1-4094).
- **PON Port Business Copy**: Easily replicate configurations from one PON port to multiple target ports.  
  *Example*: Copy settings from slot 1, port 1 to slot 1, ports 2-16.
- **Output Options**: Choose between full configuration, batch full configuration, ONU-only, or business-only scripts.
- **User Security**: Features user authentication, password modification, and IP location tracking for secure operation.
- **Multilingual Interface**: Supports both Chinese and English for global usability.

#### Benefits
- **Efficiency**: Saves time by automating repetitive configuration tasks.
- **Accuracy**: Reduces human errors with pre-validated inputs and automated script generation.
- **Scalability**: Handles both small and large-scale deployments with batch processing.
- **Ease of Use**: Intuitive interface designed for technicians, no advanced scripting knowledge required.

This tool is ideal for broadband operation technicians looking to simplify ZTE OLT configuration workflows. **Note**: The source code is not publicly available, but you can contact us for access or deployment details.
link:
https://www.miaolink.cn/index.php/2025/06/03/zte_pnp/
---

### 中文

**中兴 OLT PNP 配置脚本生成器** 是一款专为宽带运营技术员设计的强大工具，旨在简化中兴 OLT 设备的配置过程。该工具能够自动生成配置脚本，大幅减少手动操作，提升光网络单元（ONU）管理的效率。无论是单端口配置还是大规模部署，该工具都能通过友好的界面和强大的功能满足您的需求。

#### 核心功能
- **自动脚本生成**：一键生成完整的配置脚本，无需手动输入复杂命令。
- **批量端口配置**：支持多个槽位和端口的批量配置，适合大规模网络部署。  
  *示例*：一次性为槽位 1 的端口 1-2 和槽位 2 的端口 1-3 生成配置。
- **灵活的 VLAN 管理**：支持固定、序列和随机 VLAN 模式，支持跨端口序列递增。  
  *示例*：槽位 1 的端口 1-2 各配置 64 个 ONU，VLAN 在端口 1 上从 1 递增到 64，在端口 2 上从 65 递增到 100，超出后可循环至 1-28。
- **带宽和流量控制**：支持 4 种 DBA 模板配置，以及 SIR 和 PIR 可定制的流量模板。
- **组播支持**：支持启用组播功能，设置组播 VLAN（范围：1-4094）。
- **PON 口业务复制**：轻松将一个 PON 口的配置复制到多个目标 PON 口。  
  *示例*：将槽位 1 端口 1 的配置复制到槽位 1 的端口 2-16。
- **输出选项**：支持完整配置、批量板卡完整配置、仅 ONU 配置或仅业务配置脚本。
- **用户安全性**：提供用户认证、密码修改和 IP 归属地追踪，确保操作安全。
- **多语言界面**：支持中英文界面，满足全球用户需求。

#### 优势
- **高效**：通过自动化脚本生成，节省大量配置时间。
- **精准**：通过预验证输入和自动生成脚本，减少人为错误。
- **可扩展**：支持从小规模到大规模部署的批量处理。
- **易用**：专为技术员设计的直观界面，无需高级脚本知识。

这款工具非常适合希望简化中兴 OLT 配置流程的宽带运营技术员。**注意**：源码暂不公开，如需访问或部署详情，请联系我们。

参考链接:
https://www.miaolink.cn/index.php/2025/06/03/zte_pnp/
---
