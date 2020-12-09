# 黑苹果 OC/Clover 引导配置

for i7 8700K / TUF Z370-PLUS GAMING / Vega 56

- [OpenCore 配置](https://github.com/arvinxx/Hackintosh)
- [Clover 配置(已归档)](https://github.com/arvinxx/Hackintosh/tree/clover)

## 硬件

| 硬件            | 配置                                           |
| --------------- | ---------------------------------------------- |
| CPU             | Intel Core i7-8700K\@3.70GHz 六核               |
| 主板            | 华硕 Asus TUF Z370-PLUS GAMING (Z370 芯片组)   |
| 显卡            | 蓝主石 Sapphire AMD Radeon RX Vega56 8GB       |
| 内存            | 芝奇 32GB (16GB\*2) DDR4 3600MHz               |
| 网卡 & 蓝牙     | 博通 Broadcom BCM94360 双天线                  |
| SSD 1 (macOS)   | 三星 Samsung SSD 970 Plus 2TB(2TB/固态硬盘)    |
| SSD 2 (windows) | 三星 Samsung SSD 960 EVO 250GB(250GB/固态硬盘) |
| HDD             | 西部数据 2TB( ST2000DM006-2DM164)              |

## 支持状态

### macOS Catalina

![catalina](https://gw.alipayobjects.com/zos/antfincdn/gOgujHJa4Z/7326082b-61bd-4577-a670-d3d3ff713b5e.png)

| 特性       | 支持状态 | 备注              |
| ---------- | -------- | ----------------- |
| 变频/睿频  | ✅       |
| 硬件加速   | ✅       |
| 内建声卡   | ✅       |
| Wifi       | ✅       | BCM943xx 系列免驱 |
| 蓝牙       | ✅       | BCM943xx 系列免驱 |
| USB 3.X    | ✅       |
| 睡眠与唤醒 | ✅       |
| HiDPI      | ✅       |
| 自动更新   | ✅       |

存在问题:

- 键盘存在双击现象,需要重启后才会消失
