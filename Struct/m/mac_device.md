# Struct: <code>mac_device</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct mac_device {
    struct resource * res;
    u8[6] addr;
    struct fman_port *[2] port;
    u32 if_support;
    struct phy_device * phy_dev;
    phy_interface_t phy_if;
    struct device_node * phy_node;
    bool autoneg_pause;
    bool rx_pause_req;
    bool tx_pause_req;
    bool rx_pause_active;
    bool tx_pause_active;
    bool promisc;
    bool allmulti;
    int (*)(struct mac_device *) init;
    int (*)(struct mac_device *) start;
    int (*)(struct mac_device *) stop;
    void (*)(struct mac_device *) adjust_link;
    int (*)(struct fman_mac *, bool) set_promisc;
    int (*)(struct fman_mac *, enet_addr_t *) change_addr;
    int (*)(struct fman_mac *, bool) set_allmulti;
    int (*)(struct fman_mac *, bool) set_tstamp;
    int (*)(struct net_device *, struct mac_device *) set_multi;
    int (*)(struct fman_mac *, bool) set_rx_pause;
    int (*)(struct fman_mac *, u8, u16, u16) set_tx_pause;
    int (*)(struct fman_mac *, enum fman_mac_exceptions, bool) set_exception;
    int (*)(struct fman_mac *, enet_addr_t *) add_hash_mac_addr;
    int (*)(struct fman_mac *, enet_addr_t *) remove_hash_mac_addr;
    struct fman_mac * fman_mac;
    struct mac_priv_s * priv;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct mac_device {
    struct resource * res;
    u8[6] addr;
    struct fman_port *[2] port;
    u32 if_support;
    struct phy_device * phy_dev;
    phy_interface_t phy_if;
    struct device_node * phy_node;
    bool autoneg_pause;
    bool rx_pause_req;
    bool tx_pause_req;
    bool rx_pause_active;
    bool tx_pause_active;
    bool promisc;
    bool allmulti;
    int (*)(struct mac_device *) init;
    int (*)(struct mac_device *) start;
    int (*)(struct mac_device *) stop;
    void (*)(struct mac_device *) adjust_link;
    int (*)(struct fman_mac *, bool) set_promisc;
    int (*)(struct fman_mac *, enet_addr_t *) change_addr;
    int (*)(struct fman_mac *, bool) set_allmulti;
    int (*)(struct fman_mac *, bool) set_tstamp;
    int (*)(struct net_device *, struct mac_device *) set_multi;
    int (*)(struct fman_mac *, bool) set_rx_pause;
    int (*)(struct fman_mac *, u8, u16, u16) set_tx_pause;
    int (*)(struct fman_mac *, enum fman_mac_exceptions, bool) set_exception;
    int (*)(struct fman_mac *, enet_addr_t *) add_hash_mac_addr;
    int (*)(struct fman_mac *, enet_addr_t *) remove_hash_mac_addr;
    struct fman_mac * fman_mac;
    struct mac_priv_s * priv;
}
```
</details>
</li>
</ul>
