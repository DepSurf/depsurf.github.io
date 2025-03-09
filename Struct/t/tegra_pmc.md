# Struct: <code>tegra_pmc</code>

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
struct tegra_pmc {
    struct device * dev;
    void * base;
    void * wake;
    void * aotag;
    void * scratch;
    struct clk * clk;
    struct dentry * debugfs;
    const struct tegra_pmc_soc * soc;
    bool tz_only;
    long unsigned int rate;
    enum tegra_suspend_mode suspend_mode;
    u32 cpu_good_time;
    u32 cpu_off_time;
    u32 core_osc_time;
    u32 core_pmu_time;
    u32 core_off_time;
    bool corereq_high;
    bool sysclkreq_high;
    bool combined_req;
    bool cpu_pwr_good_en;
    u32 lp0_vec_phys;
    u32 lp0_vec_size;
    long unsigned int[1] powergates_available;
    struct mutex powergates_lock;
    struct pinctrl_dev * pctl_dev;
    struct irq_domain * domain;
    struct irq_chip irq;
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
struct tegra_pmc {
    struct device * dev;
    void * base;
    void * wake;
    void * aotag;
    void * scratch;
    struct clk * clk;
    struct dentry * debugfs;
    const struct tegra_pmc_soc * soc;
    bool tz_only;
    long unsigned int rate;
    enum tegra_suspend_mode suspend_mode;
    u32 cpu_good_time;
    u32 cpu_off_time;
    u32 core_osc_time;
    u32 core_pmu_time;
    u32 core_off_time;
    bool corereq_high;
    bool sysclkreq_high;
    bool combined_req;
    bool cpu_pwr_good_en;
    u32 lp0_vec_phys;
    u32 lp0_vec_size;
    long unsigned int[1] powergates_available;
    struct mutex powergates_lock;
    struct pinctrl_dev * pctl_dev;
    struct irq_domain * domain;
    struct irq_chip irq;
}
```
</details>
</li>
</ul>
