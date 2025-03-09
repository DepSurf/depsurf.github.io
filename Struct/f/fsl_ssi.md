# Struct: <code>fsl_ssi</code>

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
struct fsl_ssi {
    struct regmap * regs;
    int irq;
    struct snd_soc_dai_driver cpu_dai_drv;
    unsigned int dai_fmt;
    u8 streams;
    u8 i2s_net;
    bool synchronous;
    bool use_dma;
    bool use_dual_fifo;
    bool has_ipg_clk_name;
    unsigned int fifo_depth;
    unsigned int slot_width;
    unsigned int slots;
    struct fsl_ssi_regvals[2] regvals;
    struct clk * clk;
    struct clk * baudclk;
    unsigned int baudclk_streams;
    u32 regcache_sfcsr;
    u32 regcache_sacnt;
    struct snd_dmaengine_dai_dma_data dma_params_tx;
    struct snd_dmaengine_dai_dma_data dma_params_rx;
    dma_addr_t ssi_phys;
    struct imx_pcm_fiq_params fiq_params;
    struct platform_device * card_pdev;
    char[32] card_name;
    u32 card_idx;
    struct fsl_ssi_dbg dbg_stats;
    const struct fsl_ssi_soc_data * soc;
    struct device * dev;
    u32 fifo_watermark;
    u32 dma_maxburst;
    struct mutex ac97_reg_lock;
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
struct fsl_ssi {
    struct regmap * regs;
    int irq;
    struct snd_soc_dai_driver cpu_dai_drv;
    unsigned int dai_fmt;
    u8 streams;
    u8 i2s_net;
    bool synchronous;
    bool use_dma;
    bool use_dual_fifo;
    bool has_ipg_clk_name;
    unsigned int fifo_depth;
    unsigned int slot_width;
    unsigned int slots;
    struct fsl_ssi_regvals[2] regvals;
    struct clk * clk;
    struct clk * baudclk;
    unsigned int baudclk_streams;
    u32 regcache_sfcsr;
    u32 regcache_sacnt;
    struct snd_dmaengine_dai_dma_data dma_params_tx;
    struct snd_dmaengine_dai_dma_data dma_params_rx;
    dma_addr_t ssi_phys;
    struct imx_pcm_fiq_params fiq_params;
    struct platform_device * card_pdev;
    char[32] card_name;
    u32 card_idx;
    struct fsl_ssi_dbg dbg_stats;
    const struct fsl_ssi_soc_data * soc;
    struct device * dev;
    u32 fifo_watermark;
    u32 dma_maxburst;
    struct mutex ac97_reg_lock;
}
```
</details>
</li>
</ul>
