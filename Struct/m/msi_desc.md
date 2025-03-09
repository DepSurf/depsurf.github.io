# Struct: <code>msi_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    const struct cpumask * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct cpumask * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct cpumask * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct cpumask * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct cpumask * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 msi_mask;
    u32 msix_ctrl;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    struct device_attribute * sysfs_attrs;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u16 msi_index;
    struct pci_msi_desc pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    struct device_attribute * sysfs_attrs;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u16 msi_index;
    struct pci_msi_desc pci;
    struct msi_desc_data data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    struct device_attribute * sysfs_attrs;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u16 msi_index;
    struct pci_msi_desc pci;
    struct msi_desc_data data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct msi_desc {
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    struct device_attribute * sysfs_attrs;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u16 msi_index;
    struct pci_msi_desc pci;
    struct msi_desc_data data;
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
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    const void * iommu_cookie;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msi_desc {
    struct list_head list;
    unsigned int irq;
    unsigned int nvec_used;
    struct device * dev;
    struct msi_msg msg;
    struct irq_affinity_desc * affinity;
    void (*)(struct msi_desc *, void *) write_msi_msg;
    void * write_msi_msg_data;
    u32 masked;
    struct (anon) msi_attrib;
    u8 mask_pos;
    void * mask_base;
    struct platform_msi_desc platform;
    struct fsl_mc_msi_desc fsl_mc;
    struct ti_sci_inta_msi_desc inta;
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
<b>Field added. </b>
<code>const struct cpumask * affinity</code>
</li>
<li>
<b>Field added. </b>
<code>struct fsl_mc_msi_desc fsl_mc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const struct cpumask * affinity</code> ➡️ <code>struct cpumask * affinity</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>struct cpumask * affinity</code> ➡️ <code>struct irq_affinity_desc * affinity</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct msi_desc *, void *) write_msi_msg</code>
</li>
<li>
<b>Field added. </b>
<code>void * write_msi_msg_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct ti_sci_inta_msi_desc inta</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const void * iommu_cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 msi_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u32 msix_ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 masked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_attribute * sysfs_attrs</code>
</li>
<li>
<b>Field added. </b>
<code>u16 msi_index</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_msi_desc pci</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 msi_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 msix_ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) msi_attrib</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 mask_pos</code>
</li>
<li>
<b>Field removed. </b>
<code>void * mask_base</code>
</li>
<li>
<b>Field removed. </b>
<code>struct platform_msi_desc platform</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fsl_mc_msi_desc fsl_mc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ti_sci_inta_msi_desc inta</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct msi_desc_data data</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>const void * iommu_cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
