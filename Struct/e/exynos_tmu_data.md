# Struct: <code>exynos_tmu_data</code>

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
struct exynos_tmu_data {
    int id;
    void * base;
    void * base_second;
    int irq;
    enum soc_type soc;
    struct work_struct irq_work;
    struct mutex lock;
    struct clk * clk;
    struct clk * clk_sec;
    struct clk * sclk;
    u32 cal_type;
    u32 efuse_value;
    u32 min_efuse_value;
    u32 max_efuse_value;
    u16 temp_error1;
    u16 temp_error2;
    u8 gain;
    u8 reference_voltage;
    struct regulator * regulator;
    struct thermal_zone_device * tzd;
    unsigned int ntrip;
    bool enabled;
    void (*)(struct exynos_tmu_data *, int, u8) tmu_set_trip_temp;
    void (*)(struct exynos_tmu_data *, int, u8, u8) tmu_set_trip_hyst;
    void (*)(struct platform_device *) tmu_initialize;
    void (*)(struct platform_device *, bool) tmu_control;
    int (*)(struct exynos_tmu_data *) tmu_read;
    void (*)(struct exynos_tmu_data *, int) tmu_set_emulation;
    void (*)(struct exynos_tmu_data *) tmu_clear_irqs;
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
struct exynos_tmu_data {
    int id;
    void * base;
    void * base_second;
    int irq;
    enum soc_type soc;
    struct work_struct irq_work;
    struct mutex lock;
    struct clk * clk;
    struct clk * clk_sec;
    struct clk * sclk;
    u32 cal_type;
    u32 efuse_value;
    u32 min_efuse_value;
    u32 max_efuse_value;
    u16 temp_error1;
    u16 temp_error2;
    u8 gain;
    u8 reference_voltage;
    struct regulator * regulator;
    struct thermal_zone_device * tzd;
    unsigned int ntrip;
    bool enabled;
    void (*)(struct exynos_tmu_data *, int, u8) tmu_set_trip_temp;
    void (*)(struct exynos_tmu_data *, int, u8, u8) tmu_set_trip_hyst;
    void (*)(struct platform_device *) tmu_initialize;
    void (*)(struct platform_device *, bool) tmu_control;
    int (*)(struct exynos_tmu_data *) tmu_read;
    void (*)(struct exynos_tmu_data *, int) tmu_set_emulation;
    void (*)(struct exynos_tmu_data *) tmu_clear_irqs;
}
```
</details>
</li>
</ul>
