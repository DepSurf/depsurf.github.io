# Struct: <code>apic_chip_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg cfg;
    cpumask_var_t domain;
    cpumask_var_t old_domain;
    u8 move_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg cfg;
    cpumask_var_t domain;
    cpumask_var_t old_domain;
    u8 move_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg cfg;
    cpumask_var_t domain;
    cpumask_var_t old_domain;
    u8 move_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg cfg;
    cpumask_var_t domain;
    cpumask_var_t old_domain;
    u8 move_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct irq_cfg hw_irq_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int vector</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int prev_vector</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int prev_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int irq</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node clist</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_managed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int can_reserve</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int has_reserved</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_cfg cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>cpumask_var_t domain</code>
</li>
<li>
<b>Field removed. </b>
<code>cpumask_var_t old_domain</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 move_in_progress</code> ➡️ <code>unsigned int move_in_progress</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct apic_chip_data {
    struct irq_cfg hw_irq_cfg;
    unsigned int vector;
    unsigned int prev_vector;
    unsigned int cpu;
    unsigned int prev_cpu;
    unsigned int irq;
    struct hlist_node clist;
    unsigned int move_in_progress;
    unsigned int is_managed;
    unsigned int can_reserve;
    unsigned int has_reserved;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
