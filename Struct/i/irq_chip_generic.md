# Struct: <code>irq_chip_generic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
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
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
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
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_chip_generic {
    raw_spinlock_t lock;
    void * reg_base;
    u32 (*)(void *) reg_readl;
    void (*)(u32, void *) reg_writel;
    void (*)(struct irq_chip_generic *) suspend;
    void (*)(struct irq_chip_generic *) resume;
    unsigned int irq_base;
    unsigned int irq_cnt;
    u32 mask_cache;
    u32 type_cache;
    u32 polarity_cache;
    u32 wake_enabled;
    u32 wake_active;
    unsigned int num_ct;
    void * private;
    long unsigned int installed;
    long unsigned int unused;
    struct irq_domain * domain;
    struct list_head list;
    struct irq_chip_type[0] chip_types;
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
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
