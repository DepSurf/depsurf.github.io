# Struct: <code>bgmac</code>

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
struct bgmac {
    struct (anon) plat;
    struct (anon) bcma;
    struct device * dev;
    struct device * dma_dev;
    u32 feature_flags;
    struct net_device * net_dev;
    struct napi_struct napi;
    struct mii_bus * mii_bus;
    struct bgmac_dma_ring[4] tx_ring;
    struct bgmac_dma_ring[1] rx_ring;
    bool stats_grabbed;
    u32[43] mib_tx_regs;
    u32[31] mib_rx_regs;
    int irq;
    u32 int_mask;
    int mac_speed;
    int mac_duplex;
    u8 phyaddr;
    bool has_robosw;
    bool loopback;
    u32 (*)(struct bgmac *, u16) read;
    void (*)(struct bgmac *, u16, u32) write;
    u32 (*)(struct bgmac *, u16) idm_read;
    void (*)(struct bgmac *, u16, u32) idm_write;
    bool (*)(struct bgmac *) clk_enabled;
    void (*)(struct bgmac *, u32) clk_enable;
    void (*)(struct bgmac *, u32, u32, u32) cco_ctl_maskset;
    u32 (*)(struct bgmac *) get_bus_clock;
    void (*)(struct bgmac *, u16, u32, u32) cmn_maskset32;
    int (*)(struct bgmac *) phy_connect;
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
struct bgmac {
    struct (anon) plat;
    struct (anon) bcma;
    struct device * dev;
    struct device * dma_dev;
    u32 feature_flags;
    struct net_device * net_dev;
    struct napi_struct napi;
    struct mii_bus * mii_bus;
    struct bgmac_dma_ring[4] tx_ring;
    struct bgmac_dma_ring[1] rx_ring;
    bool stats_grabbed;
    u32[43] mib_tx_regs;
    u32[31] mib_rx_regs;
    int irq;
    u32 int_mask;
    int mac_speed;
    int mac_duplex;
    u8 phyaddr;
    bool has_robosw;
    bool loopback;
    u32 (*)(struct bgmac *, u16) read;
    void (*)(struct bgmac *, u16, u32) write;
    u32 (*)(struct bgmac *, u16) idm_read;
    void (*)(struct bgmac *, u16, u32) idm_write;
    bool (*)(struct bgmac *) clk_enabled;
    void (*)(struct bgmac *, u32) clk_enable;
    void (*)(struct bgmac *, u32, u32, u32) cco_ctl_maskset;
    u32 (*)(struct bgmac *) get_bus_clock;
    void (*)(struct bgmac *, u16, u32, u32) cmn_maskset32;
    int (*)(struct bgmac *) phy_connect;
}
```
</details>
</li>
</ul>
