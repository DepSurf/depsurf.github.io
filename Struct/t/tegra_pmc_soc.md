# Struct: <code>tegra_pmc_soc</code>

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
struct tegra_pmc_soc {
    unsigned int num_powergates;
    const const char * * powergates;
    unsigned int num_cpu_powergates;
    const u8 * cpu_powergates;
    bool has_tsense_reset;
    bool has_gpu_clamps;
    bool needs_mbist_war;
    bool has_impl_33v_pwr;
    bool maybe_tz_only;
    const struct tegra_io_pad_soc * io_pads;
    unsigned int num_io_pads;
    const struct pinctrl_pin_desc * pin_descs;
    unsigned int num_pin_descs;
    const struct tegra_pmc_regs * regs;
    void (*)(struct tegra_pmc *) init;
    void (*)(struct tegra_pmc *, struct device_node *, bool) setup_irq_polarity;
    const const char * * reset_sources;
    unsigned int num_reset_sources;
    const const char * * reset_levels;
    unsigned int num_reset_levels;
    const struct tegra_wake_event * wake_events;
    unsigned int num_wake_events;
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
struct tegra_pmc_soc {
    unsigned int num_powergates;
    const const char * * powergates;
    unsigned int num_cpu_powergates;
    const u8 * cpu_powergates;
    bool has_tsense_reset;
    bool has_gpu_clamps;
    bool needs_mbist_war;
    bool has_impl_33v_pwr;
    bool maybe_tz_only;
    const struct tegra_io_pad_soc * io_pads;
    unsigned int num_io_pads;
    const struct pinctrl_pin_desc * pin_descs;
    unsigned int num_pin_descs;
    const struct tegra_pmc_regs * regs;
    void (*)(struct tegra_pmc *) init;
    void (*)(struct tegra_pmc *, struct device_node *, bool) setup_irq_polarity;
    const const char * * reset_sources;
    unsigned int num_reset_sources;
    const const char * * reset_levels;
    unsigned int num_reset_levels;
    const struct tegra_wake_event * wake_events;
    unsigned int num_wake_events;
}
```
</details>
</li>
</ul>
