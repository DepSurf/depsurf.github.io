# Struct: <code>omap_hsmmc_host</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct omap_hsmmc_host {
    struct device * dev;
    struct mmc_host * mmc;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct clk * fclk;
    struct clk * dbclk;
    struct regulator * pbias;
    bool pbias_enabled;
    void * base;
    int vqmmc_enabled;
    resource_size_t mapbase;
    spinlock_t irq_lock;
    unsigned int dma_len;
    unsigned int dma_sg_idx;
    unsigned char bus_mode;
    unsigned char power_mode;
    int suspended;
    u32 con;
    u32 hctl;
    u32 sysctl;
    u32 capa;
    int irq;
    int wake_irq;
    int use_dma;
    int dma_ch;
    struct dma_chan * tx_chan;
    struct dma_chan * rx_chan;
    int response_busy;
    int context_loss;
    int reqs_blocked;
    int req_in_progress;
    long unsigned int clk_rate;
    unsigned int flags;
    struct omap_hsmmc_next next_data;
    struct omap_hsmmc_platform_data * pdata;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct omap_hsmmc_host {
    struct device * dev;
    struct mmc_host * mmc;
    struct mmc_request * mrq;
    struct mmc_command * cmd;
    struct mmc_data * data;
    struct clk * fclk;
    struct clk * dbclk;
    struct regulator * pbias;
    bool pbias_enabled;
    void * base;
    int vqmmc_enabled;
    resource_size_t mapbase;
    spinlock_t irq_lock;
    unsigned int dma_len;
    unsigned int dma_sg_idx;
    unsigned char bus_mode;
    unsigned char power_mode;
    int suspended;
    u32 con;
    u32 hctl;
    u32 sysctl;
    u32 capa;
    int irq;
    int wake_irq;
    int use_dma;
    int dma_ch;
    struct dma_chan * tx_chan;
    struct dma_chan * rx_chan;
    int response_busy;
    int context_loss;
    int reqs_blocked;
    int req_in_progress;
    long unsigned int clk_rate;
    unsigned int flags;
    struct omap_hsmmc_next next_data;
    struct omap_hsmmc_platform_data * pdata;
}
```
</details>
</li>
</ul>
