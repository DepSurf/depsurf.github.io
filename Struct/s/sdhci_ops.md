# Struct: <code>sdhci_ops</code>

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
struct sdhci_ops {
    u32 (*)(struct sdhci_host *, int) read_l;
    u16 (*)(struct sdhci_host *, int) read_w;
    u8 (*)(struct sdhci_host *, int) read_b;
    void (*)(struct sdhci_host *, u32, int) write_l;
    void (*)(struct sdhci_host *, u16, int) write_w;
    void (*)(struct sdhci_host *, u8, int) write_b;
    void (*)(struct sdhci_host *, unsigned int) set_clock;
    void (*)(struct sdhci_host *, unsigned char, short unsigned int) set_power;
    u32 (*)(struct sdhci_host *, u32) irq;
    int (*)(struct sdhci_host *) set_dma_mask;
    int (*)(struct sdhci_host *) enable_dma;
    unsigned int (*)(struct sdhci_host *) get_max_clock;
    unsigned int (*)(struct sdhci_host *) get_min_clock;
    unsigned int (*)(struct sdhci_host *) get_timeout_clock;
    unsigned int (*)(struct sdhci_host *) get_max_timeout_count;
    void (*)(struct sdhci_host *, struct mmc_command *) set_timeout;
    void (*)(struct sdhci_host *, int) set_bus_width;
    void (*)(struct sdhci_host *, u8) platform_send_init_74_clocks;
    unsigned int (*)(struct sdhci_host *) get_ro;
    void (*)(struct sdhci_host *, u8) reset;
    int (*)(struct sdhci_host *, u32) platform_execute_tuning;
    void (*)(struct sdhci_host *, unsigned int) set_uhs_signaling;
    void (*)(struct sdhci_host *) hw_reset;
    void (*)(struct sdhci_host *, u32) adma_workaround;
    void (*)(struct sdhci_host *) card_event;
    void (*)(struct sdhci_host *) voltage_switch;
    void (*)(struct sdhci_host *, void * *, dma_addr_t, int, unsigned int) adma_write_desc;
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
struct sdhci_ops {
    u32 (*)(struct sdhci_host *, int) read_l;
    u16 (*)(struct sdhci_host *, int) read_w;
    u8 (*)(struct sdhci_host *, int) read_b;
    void (*)(struct sdhci_host *, u32, int) write_l;
    void (*)(struct sdhci_host *, u16, int) write_w;
    void (*)(struct sdhci_host *, u8, int) write_b;
    void (*)(struct sdhci_host *, unsigned int) set_clock;
    void (*)(struct sdhci_host *, unsigned char, short unsigned int) set_power;
    u32 (*)(struct sdhci_host *, u32) irq;
    int (*)(struct sdhci_host *) set_dma_mask;
    int (*)(struct sdhci_host *) enable_dma;
    unsigned int (*)(struct sdhci_host *) get_max_clock;
    unsigned int (*)(struct sdhci_host *) get_min_clock;
    unsigned int (*)(struct sdhci_host *) get_timeout_clock;
    unsigned int (*)(struct sdhci_host *) get_max_timeout_count;
    void (*)(struct sdhci_host *, struct mmc_command *) set_timeout;
    void (*)(struct sdhci_host *, int) set_bus_width;
    void (*)(struct sdhci_host *, u8) platform_send_init_74_clocks;
    unsigned int (*)(struct sdhci_host *) get_ro;
    void (*)(struct sdhci_host *, u8) reset;
    int (*)(struct sdhci_host *, u32) platform_execute_tuning;
    void (*)(struct sdhci_host *, unsigned int) set_uhs_signaling;
    void (*)(struct sdhci_host *) hw_reset;
    void (*)(struct sdhci_host *, u32) adma_workaround;
    void (*)(struct sdhci_host *) card_event;
    void (*)(struct sdhci_host *) voltage_switch;
    void (*)(struct sdhci_host *, void * *, dma_addr_t, int, unsigned int) adma_write_desc;
}
```
</details>
</li>
</ul>
