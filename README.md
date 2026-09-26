# J4125 + i210 精简 OpenWrt 固件 (OpenClash + WireGuard)

专为 **Intel J4125 + Intel i210 千兆网卡** 软路由/工控机打造的超轻量固件。

### 特性
- **极致精简**：无多余臃肿插件，仅保留 **OpenClash** 与 **WireGuard**。
- **硬件适配**：原生编译 `kmod-igb`（i210）、AES-NI 硬件加解密支持。
- **大容量分区**：根分区分配 1024MB，Clash 内核与规则库随意更新不爆空间。
- **引导方式**：默认支持 UEFI (EFI) 与传统 Legacy BIOS 启动。
