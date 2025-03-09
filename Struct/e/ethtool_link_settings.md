# Struct: <code>ethtool_link_settings</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u32[8] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u32[8] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u32[8] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8[1] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8[1] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8[1] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8[1] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8[1] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8 rate_matching;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8 rate_matching;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8 master_slave_cfg;
    __u8 master_slave_state;
    __u8 rate_matching;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u8 transceiver;
    __u8[3] reserved1;
    __u32[7] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct ethtool_link_settings {
    __u32 cmd;
    __u32 speed;
    __u8 duplex;
    __u8 port;
    __u8 phy_address;
    __u8 autoneg;
    __u8 mdio_support;
    __u8 eth_tp_mdix;
    __u8 eth_tp_mdix_ctrl;
    __s8 link_mode_masks_nwords;
    __u32[8] reserved;
    __u32[0] link_mode_masks;
}
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 transceiver</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[3] reserved1</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[8] reserved</code> ➡️ <code>__u32[7] reserved</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 master_slave_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 master_slave_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[3] reserved1</code> ➡️ <code>__u8[1] reserved1</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 rate_matching</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8[1] reserved1</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
