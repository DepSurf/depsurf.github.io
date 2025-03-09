# Struct: <code>ethtool_phy_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg;
    int (*)(struct phy_device *, const struct phy_plca_cfg *, struct netlink_ext_ack *) set_plca_cfg;
    int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg;
    int (*)(struct phy_device *, const struct phy_plca_cfg *, struct netlink_ext_ack *) set_plca_cfg;
    int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct ethtool_phy_ops {
    int (*)(struct phy_device *) get_sset_count;
    int (*)(struct phy_device *, u8 *) get_strings;
    int (*)(struct phy_device *, struct ethtool_stats *, u64 *) get_stats;
    int (*)(struct phy_device *, struct netlink_ext_ack *) start_cable_test;
    int (*)(struct phy_device *, struct netlink_ext_ack *, const struct phy_tdr_config *) start_cable_test_tdr;
}
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, struct phy_plca_cfg *) get_plca_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, const struct phy_plca_cfg *, struct netlink_ext_ack *) set_plca_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct phy_device *, struct phy_plca_status *) get_plca_status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
