# Struct: <code>ahci_host_priv</code>

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
struct ahci_host_priv {
    unsigned int flags;
    u32 force_port_map;
    u32 mask_port_map;
    void * mmio;
    u32 cap;
    u32 cap2;
    u32 version;
    u32 port_map;
    u32 saved_cap;
    u32 saved_cap2;
    u32 saved_port_map;
    u32 em_loc;
    u32 em_buf_sz;
    u32 em_msg_type;
    u32 remapped_nvme;
    bool got_runtime_pm;
    struct clk *[5] clks;
    struct reset_control * rsts;
    struct regulator * * target_pwrs;
    struct regulator * ahci_regulator;
    struct regulator * phy_regulator;
    struct phy * * phys;
    unsigned int nports;
    void * plat_data;
    unsigned int irq;
    void (*)(struct ata_port *) start_engine;
    int (*)(struct ata_port *) stop_engine;
    irqreturn_t (*)(int, void *) irq_handler;
    int (*)(struct ata_host *, int) get_irq_vector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ahci_host_priv {
    unsigned int flags;
    u32 force_port_map;
    u32 mask_port_map;
    void * mmio;
    u32 cap;
    u32 cap2;
    u32 version;
    u32 port_map;
    u32 saved_cap;
    u32 saved_cap2;
    u32 saved_port_map;
    u32 em_loc;
    u32 em_buf_sz;
    u32 em_msg_type;
    u32 remapped_nvme;
    bool got_runtime_pm;
    struct clk *[5] clks;
    struct reset_control * rsts;
    struct regulator * * target_pwrs;
    struct regulator * ahci_regulator;
    struct regulator * phy_regulator;
    struct phy * * phys;
    unsigned int nports;
    void * plat_data;
    unsigned int irq;
    void (*)(struct ata_port *) start_engine;
    int (*)(struct ata_port *) stop_engine;
    irqreturn_t (*)(int, void *) irq_handler;
    int (*)(struct ata_host *, int) get_irq_vector;
}
```
</details>
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
struct ahci_host_priv {
    unsigned int flags;
    u32 force_port_map;
    u32 mask_port_map;
    void * mmio;
    u32 cap;
    u32 cap2;
    u32 version;
    u32 port_map;
    u32 saved_cap;
    u32 saved_cap2;
    u32 saved_port_map;
    u32 em_loc;
    u32 em_buf_sz;
    u32 em_msg_type;
    u32 remapped_nvme;
    bool got_runtime_pm;
    struct clk *[5] clks;
    struct reset_control * rsts;
    struct regulator * * target_pwrs;
    struct regulator * ahci_regulator;
    struct regulator * phy_regulator;
    struct phy * * phys;
    unsigned int nports;
    void * plat_data;
    unsigned int irq;
    void (*)(struct ata_port *) start_engine;
    int (*)(struct ata_port *) stop_engine;
    irqreturn_t (*)(int, void *) irq_handler;
    int (*)(struct ata_host *, int) get_irq_vector;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct ahci_host_priv {
    unsigned int flags;
    u32 force_port_map;
    u32 mask_port_map;
    void * mmio;
    u32 cap;
    u32 cap2;
    u32 version;
    u32 port_map;
    u32 saved_cap;
    u32 saved_cap2;
    u32 saved_port_map;
    u32 em_loc;
    u32 em_buf_sz;
    u32 em_msg_type;
    u32 remapped_nvme;
    bool got_runtime_pm;
    struct clk *[5] clks;
    struct reset_control * rsts;
    struct regulator * * target_pwrs;
    struct regulator * ahci_regulator;
    struct regulator * phy_regulator;
    struct phy * * phys;
    unsigned int nports;
    void * plat_data;
    unsigned int irq;
    void (*)(struct ata_port *) start_engine;
    int (*)(struct ata_port *) stop_engine;
    irqreturn_t (*)(int, void *) irq_handler;
    int (*)(struct ata_host *, int) get_irq_vector;
}
```
</details>
</li>
</ul>
