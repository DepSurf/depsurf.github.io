# Struct: <code>mmci_host</code>

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
struct mmci_host {
    phys_addr_t phybase;
    void * base;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_command stop_abort;
    struct mmc_data * data;
    struct mmc_host * mmc;
    struct clk * clk;
    u8 singleirq;
    struct reset_control * rst;
    spinlock_t lock;
    unsigned int mclk;
    unsigned int clock_cache;
    unsigned int cclk;
    u32 pwr_reg;
    u32 pwr_reg_add;
    u32 clk_reg;
    u32 clk_reg_add;
    u32 datactrl_reg;
    u32 busy_status;
    u32 mask1_reg;
    u8 vqmmc_enabled;
    struct mmci_platform_data * plat;
    struct mmci_host_ops * ops;
    struct variant_data * variant;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_opendrain;
    u8 hw_designer;
    u8 hw_revision;
    struct timer_list timer;
    unsigned int oldstat;
    struct sg_mapping_iter sg_miter;
    unsigned int size;
    int (*)(struct mmci_host *, u32, int) get_rx_fifocnt;
    u8 use_dma;
    u8 dma_in_progress;
    void * dma_priv;
    s32 next_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmci_host {
    phys_addr_t phybase;
    void * base;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_command stop_abort;
    struct mmc_data * data;
    struct mmc_host * mmc;
    struct clk * clk;
    u8 singleirq;
    struct reset_control * rst;
    spinlock_t lock;
    unsigned int mclk;
    unsigned int clock_cache;
    unsigned int cclk;
    u32 pwr_reg;
    u32 pwr_reg_add;
    u32 clk_reg;
    u32 clk_reg_add;
    u32 datactrl_reg;
    u32 busy_status;
    u32 mask1_reg;
    u8 vqmmc_enabled;
    struct mmci_platform_data * plat;
    struct mmci_host_ops * ops;
    struct variant_data * variant;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_opendrain;
    u8 hw_designer;
    u8 hw_revision;
    struct timer_list timer;
    unsigned int oldstat;
    struct sg_mapping_iter sg_miter;
    unsigned int size;
    int (*)(struct mmci_host *, u32, int) get_rx_fifocnt;
    u8 use_dma;
    u8 dma_in_progress;
    void * dma_priv;
    s32 next_cookie;
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
struct mmci_host {
    phys_addr_t phybase;
    void * base;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_command stop_abort;
    struct mmc_data * data;
    struct mmc_host * mmc;
    struct clk * clk;
    u8 singleirq;
    struct reset_control * rst;
    spinlock_t lock;
    unsigned int mclk;
    unsigned int clock_cache;
    unsigned int cclk;
    u32 pwr_reg;
    u32 pwr_reg_add;
    u32 clk_reg;
    u32 clk_reg_add;
    u32 datactrl_reg;
    u32 busy_status;
    u32 mask1_reg;
    u8 vqmmc_enabled;
    struct mmci_platform_data * plat;
    struct mmci_host_ops * ops;
    struct variant_data * variant;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_opendrain;
    u8 hw_designer;
    u8 hw_revision;
    struct timer_list timer;
    unsigned int oldstat;
    struct sg_mapping_iter sg_miter;
    unsigned int size;
    int (*)(struct mmci_host *, u32, int) get_rx_fifocnt;
    u8 use_dma;
    u8 dma_in_progress;
    void * dma_priv;
    s32 next_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mmci_host {
    phys_addr_t phybase;
    void * base;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_command stop_abort;
    struct mmc_data * data;
    struct mmc_host * mmc;
    struct clk * clk;
    u8 singleirq;
    struct reset_control * rst;
    spinlock_t lock;
    unsigned int mclk;
    unsigned int clock_cache;
    unsigned int cclk;
    u32 pwr_reg;
    u32 pwr_reg_add;
    u32 clk_reg;
    u32 clk_reg_add;
    u32 datactrl_reg;
    u32 busy_status;
    u32 mask1_reg;
    u8 vqmmc_enabled;
    struct mmci_platform_data * plat;
    struct mmci_host_ops * ops;
    struct variant_data * variant;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_opendrain;
    u8 hw_designer;
    u8 hw_revision;
    struct timer_list timer;
    unsigned int oldstat;
    struct sg_mapping_iter sg_miter;
    unsigned int size;
    int (*)(struct mmci_host *, u32, int) get_rx_fifocnt;
    u8 use_dma;
    u8 dma_in_progress;
    void * dma_priv;
    s32 next_cookie;
}
```
</details>
</li>
</ul>
