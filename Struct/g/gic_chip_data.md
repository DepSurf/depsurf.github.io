# Struct: <code>gic_chip_data</code>

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
struct gic_chip_data {
    struct irq_chip chip;
    union gic_base dist_base;
    union gic_base cpu_base;
    void * raw_dist_base;
    void * raw_cpu_base;
    u32 percpu_offset;
    u32[32] saved_spi_enable;
    u32[32] saved_spi_active;
    u32[64] saved_spi_conf;
    u32[255] saved_spi_target;
    u32 * saved_ppi_enable;
    u32 * saved_ppi_active;
    u32 * saved_ppi_conf;
    struct irq_domain * domain;
    unsigned int gic_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gic_chip_data {
    struct irq_chip chip;
    union gic_base dist_base;
    union gic_base cpu_base;
    void * raw_dist_base;
    void * raw_cpu_base;
    u32 percpu_offset;
    u32[32] saved_spi_enable;
    u32[32] saved_spi_active;
    u32[64] saved_spi_conf;
    u32[255] saved_spi_target;
    u32 * saved_ppi_enable;
    u32 * saved_ppi_active;
    u32 * saved_ppi_conf;
    struct irq_domain * domain;
    unsigned int gic_irqs;
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
struct gic_chip_data {
    struct irq_chip chip;
    union gic_base dist_base;
    union gic_base cpu_base;
    void * raw_dist_base;
    void * raw_cpu_base;
    u32 percpu_offset;
    u32[32] saved_spi_enable;
    u32[32] saved_spi_active;
    u32[64] saved_spi_conf;
    u32[255] saved_spi_target;
    u32 * saved_ppi_enable;
    u32 * saved_ppi_active;
    u32 * saved_ppi_conf;
    struct irq_domain * domain;
    unsigned int gic_irqs;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct gic_chip_data {
    struct irq_chip chip;
    union gic_base dist_base;
    union gic_base cpu_base;
    void * raw_dist_base;
    void * raw_cpu_base;
    u32 percpu_offset;
    u32[32] saved_spi_enable;
    u32[32] saved_spi_active;
    u32[64] saved_spi_conf;
    u32[255] saved_spi_target;
    u32 * saved_ppi_enable;
    u32 * saved_ppi_active;
    u32 * saved_ppi_conf;
    struct irq_domain * domain;
    unsigned int gic_irqs;
}
```
</details>
</li>
</ul>
