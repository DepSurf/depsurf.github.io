# Struct: <code>fman_mac</code>

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
struct fman_mac {
    struct dtsec_regs * regs;
    u64 addr;
    phy_interface_t phy_if;
    u16 max_speed;
    void * dev_id;
    fman_mac_exception_cb * exception_cb;
    fman_mac_exception_cb * event_cb;
    u8 num_of_ind_addr_in_regs;
    struct eth_hash_t * multicast_addr_hash;
    struct eth_hash_t * unicast_addr_hash;
    u8 mac_id;
    u32 exceptions;
    bool ptp_tsu_enabled;
    bool en_tsu_err_exception;
    struct dtsec_cfg * dtsec_drv_param;
    void * fm;
    struct fman_rev_info fm_rev_info;
    bool basex_if;
    struct phy_device * tbiphy;
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
struct fman_mac {
    struct dtsec_regs * regs;
    u64 addr;
    phy_interface_t phy_if;
    u16 max_speed;
    void * dev_id;
    fman_mac_exception_cb * exception_cb;
    fman_mac_exception_cb * event_cb;
    u8 num_of_ind_addr_in_regs;
    struct eth_hash_t * multicast_addr_hash;
    struct eth_hash_t * unicast_addr_hash;
    u8 mac_id;
    u32 exceptions;
    bool ptp_tsu_enabled;
    bool en_tsu_err_exception;
    struct dtsec_cfg * dtsec_drv_param;
    void * fm;
    struct fman_rev_info fm_rev_info;
    bool basex_if;
    struct phy_device * tbiphy;
}
```
</details>
</li>
</ul>
