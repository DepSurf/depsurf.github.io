# Struct: <code>paravirt_patch_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_apic_ops pv_apic_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops pv_init_ops;
    struct pv_time_ops pv_time_ops;
    struct pv_cpu_ops pv_cpu_ops;
    struct pv_irq_ops pv_irq_ops;
    struct pv_mmu_ops pv_mmu_ops;
    struct pv_lock_ops pv_lock_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_time_ops time;
}
```
</details>
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
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct pv_apic_ops pv_apic_ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pv_init_ops init</code>
</li>
<li>
<b>Field added. </b>
<code>struct pv_time_ops time</code>
</li>
<li>
<b>Field added. </b>
<code>struct pv_cpu_ops cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct pv_irq_ops irq</code>
</li>
<li>
<b>Field added. </b>
<code>struct pv_mmu_ops mmu</code>
</li>
<li>
<b>Field added. </b>
<code>struct pv_lock_ops lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_init_ops pv_init_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_time_ops pv_time_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_cpu_ops pv_cpu_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_irq_ops pv_irq_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_mmu_ops pv_mmu_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_lock_ops pv_lock_ops</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct pv_init_ops init</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_time_ops time</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct pv_init_ops init</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_cpu_ops cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_irq_ops irq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_mmu_ops mmu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_lock_ops lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct paravirt_patch_template {
    struct pv_init_ops init;
    struct pv_time_ops time;
    struct pv_cpu_ops cpu;
    struct pv_irq_ops irq;
    struct pv_mmu_ops mmu;
    struct pv_lock_ops lock;
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
