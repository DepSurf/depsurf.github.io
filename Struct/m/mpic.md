# Struct: <code>mpic</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mpic {
    struct device_node * node;
    struct irq_domain * irqhost;
    struct irq_chip hc_irq;
    struct irq_chip hc_ipi;
    struct irq_chip hc_tm;
    struct irq_chip hc_err;
    const char * name;
    unsigned int flags;
    unsigned int isu_size;
    unsigned int isu_shift;
    unsigned int isu_mask;
    unsigned int num_sources;
    unsigned int[4] ipi_vecs;
    unsigned int[8] timer_vecs;
    unsigned int[32] err_int_vecs;
    unsigned int spurious_vec;
    enum mpic_reg_type reg_type;
    phys_addr_t paddr;
    struct mpic_reg_bank thiscpuregs;
    struct mpic_reg_bank gregs;
    struct mpic_reg_bank tmregs;
    struct mpic_reg_bank[32] cpuregs;
    struct mpic_reg_bank[32] isus;
    u32 * err_regs;
    long unsigned int * protected;
    struct msi_bitmap msi_bitmap;
    struct mpic * next;
    struct mpic_irq_save * save_data;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct mpic {
    struct device_node * node;
    struct irq_domain * irqhost;
    struct irq_chip hc_irq;
    struct irq_chip hc_ipi;
    struct irq_chip hc_tm;
    struct irq_chip hc_err;
    const char * name;
    unsigned int flags;
    unsigned int isu_size;
    unsigned int isu_shift;
    unsigned int isu_mask;
    unsigned int num_sources;
    unsigned int[4] ipi_vecs;
    unsigned int[8] timer_vecs;
    unsigned int[32] err_int_vecs;
    unsigned int spurious_vec;
    enum mpic_reg_type reg_type;
    phys_addr_t paddr;
    struct mpic_reg_bank thiscpuregs;
    struct mpic_reg_bank gregs;
    struct mpic_reg_bank tmregs;
    struct mpic_reg_bank[32] cpuregs;
    struct mpic_reg_bank[32] isus;
    u32 * err_regs;
    long unsigned int * protected;
    struct msi_bitmap msi_bitmap;
    struct mpic * next;
    struct mpic_irq_save * save_data;
}
```
</details>
</li>
</ul>
