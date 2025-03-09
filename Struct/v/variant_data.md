# Struct: <code>variant_data</code>

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
struct variant_data {
    unsigned int clkreg;
    unsigned int clkreg_enable;
    unsigned int clkreg_8bit_bus_enable;
    unsigned int clkreg_neg_edge_enable;
    unsigned int cmdreg_cpsm_enable;
    unsigned int cmdreg_lrsp_crc;
    unsigned int cmdreg_srsp_crc;
    unsigned int cmdreg_srsp;
    unsigned int cmdreg_stop;
    unsigned int datalength_bits;
    unsigned int fifosize;
    unsigned int fifohalfsize;
    unsigned int data_cmd_enable;
    unsigned int datactrl_mask_ddrmode;
    unsigned int datactrl_mask_sdio;
    unsigned int datactrl_blocksz;
    u8 datactrl_first;
    u8 datacnt_useless;
    u8 st_sdio;
    u8 st_clkdiv;
    u8 stm32_clkdiv;
    u32 pwrreg_powerup;
    u32 f_max;
    u8 signal_direction;
    u8 pwrreg_clkgate;
    u8 busy_detect;
    u32 busy_dpsm_flag;
    u32 busy_detect_flag;
    u32 busy_detect_mask;
    u8 pwrreg_nopower;
    u8 explicit_mclk_control;
    u8 qcom_fifo;
    u8 qcom_dml;
    u8 reversed_irq_handling;
    u8 mmcimask1;
    unsigned int irq_pio_mask;
    u32 start_err;
    u32 opendrain;
    u8 dma_lli;
    u32 stm32_idmabsize_mask;
    void (*)(struct mmci_host *) init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct variant_data {
    unsigned int clkreg;
    unsigned int clkreg_enable;
    unsigned int clkreg_8bit_bus_enable;
    unsigned int clkreg_neg_edge_enable;
    unsigned int cmdreg_cpsm_enable;
    unsigned int cmdreg_lrsp_crc;
    unsigned int cmdreg_srsp_crc;
    unsigned int cmdreg_srsp;
    unsigned int cmdreg_stop;
    unsigned int datalength_bits;
    unsigned int fifosize;
    unsigned int fifohalfsize;
    unsigned int data_cmd_enable;
    unsigned int datactrl_mask_ddrmode;
    unsigned int datactrl_mask_sdio;
    unsigned int datactrl_blocksz;
    u8 datactrl_first;
    u8 datacnt_useless;
    u8 st_sdio;
    u8 st_clkdiv;
    u8 stm32_clkdiv;
    u32 pwrreg_powerup;
    u32 f_max;
    u8 signal_direction;
    u8 pwrreg_clkgate;
    u8 busy_detect;
    u32 busy_dpsm_flag;
    u32 busy_detect_flag;
    u32 busy_detect_mask;
    u8 pwrreg_nopower;
    u8 explicit_mclk_control;
    u8 qcom_fifo;
    u8 qcom_dml;
    u8 reversed_irq_handling;
    u8 mmcimask1;
    unsigned int irq_pio_mask;
    u32 start_err;
    u32 opendrain;
    u8 dma_lli;
    u32 stm32_idmabsize_mask;
    void (*)(struct mmci_host *) init;
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
struct variant_data {
    unsigned int clkreg;
    unsigned int clkreg_enable;
    unsigned int clkreg_8bit_bus_enable;
    unsigned int clkreg_neg_edge_enable;
    unsigned int cmdreg_cpsm_enable;
    unsigned int cmdreg_lrsp_crc;
    unsigned int cmdreg_srsp_crc;
    unsigned int cmdreg_srsp;
    unsigned int cmdreg_stop;
    unsigned int datalength_bits;
    unsigned int fifosize;
    unsigned int fifohalfsize;
    unsigned int data_cmd_enable;
    unsigned int datactrl_mask_ddrmode;
    unsigned int datactrl_mask_sdio;
    unsigned int datactrl_blocksz;
    u8 datactrl_first;
    u8 datacnt_useless;
    u8 st_sdio;
    u8 st_clkdiv;
    u8 stm32_clkdiv;
    u32 pwrreg_powerup;
    u32 f_max;
    u8 signal_direction;
    u8 pwrreg_clkgate;
    u8 busy_detect;
    u32 busy_dpsm_flag;
    u32 busy_detect_flag;
    u32 busy_detect_mask;
    u8 pwrreg_nopower;
    u8 explicit_mclk_control;
    u8 qcom_fifo;
    u8 qcom_dml;
    u8 reversed_irq_handling;
    u8 mmcimask1;
    unsigned int irq_pio_mask;
    u32 start_err;
    u32 opendrain;
    u8 dma_lli;
    u32 stm32_idmabsize_mask;
    void (*)(struct mmci_host *) init;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct variant_data {
    unsigned int clkreg;
    unsigned int clkreg_enable;
    unsigned int clkreg_8bit_bus_enable;
    unsigned int clkreg_neg_edge_enable;
    unsigned int cmdreg_cpsm_enable;
    unsigned int cmdreg_lrsp_crc;
    unsigned int cmdreg_srsp_crc;
    unsigned int cmdreg_srsp;
    unsigned int cmdreg_stop;
    unsigned int datalength_bits;
    unsigned int fifosize;
    unsigned int fifohalfsize;
    unsigned int data_cmd_enable;
    unsigned int datactrl_mask_ddrmode;
    unsigned int datactrl_mask_sdio;
    unsigned int datactrl_blocksz;
    u8 datactrl_first;
    u8 datacnt_useless;
    u8 st_sdio;
    u8 st_clkdiv;
    u8 stm32_clkdiv;
    u32 pwrreg_powerup;
    u32 f_max;
    u8 signal_direction;
    u8 pwrreg_clkgate;
    u8 busy_detect;
    u32 busy_dpsm_flag;
    u32 busy_detect_flag;
    u32 busy_detect_mask;
    u8 pwrreg_nopower;
    u8 explicit_mclk_control;
    u8 qcom_fifo;
    u8 qcom_dml;
    u8 reversed_irq_handling;
    u8 mmcimask1;
    unsigned int irq_pio_mask;
    u32 start_err;
    u32 opendrain;
    u8 dma_lli;
    u32 stm32_idmabsize_mask;
    void (*)(struct mmci_host *) init;
}
```
</details>
</li>
</ul>
