# Struct: <code>iommu_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
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
struct iommu_table {
    long unsigned int it_busno;
    long unsigned int it_size;
    long unsigned int it_indirect_levels;
    long unsigned int it_level_size;
    long unsigned int it_allocated_size;
    long unsigned int it_offset;
    long unsigned int it_base;
    long unsigned int it_index;
    long unsigned int it_type;
    long unsigned int it_blocksize;
    long unsigned int poolsize;
    long unsigned int nr_pools;
    struct iommu_pool large_pool;
    struct iommu_pool[4] pools;
    long unsigned int * it_map;
    long unsigned int it_page_shift;
    struct list_head it_group_list;
    __be64 * it_userspace;
    struct iommu_table_ops * it_ops;
    struct kref it_kref;
    int it_nid;
    long unsigned int it_reserved_start;
    long unsigned int it_reserved_end;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
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
<b>Field type changed. </b>
<code>struct cal_chipset_ops * chip_ops</code> ➡️ <code>const struct cal_chipset_ops * chip_ops</code>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int it_indirect_levels</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_level_size</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_allocated_size</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_offset</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_index</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_type</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_blocksize</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int poolsize</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_pools</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_pool large_pool</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_pool[4] pools</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_page_shift</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head it_group_list</code>
</li>
<li>
<b>Field added. </b>
<code>__be64 * it_userspace</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_table_ops * it_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct kref it_kref</code>
</li>
<li>
<b>Field added. </b>
<code>int it_nid</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_reserved_start</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int it_reserved_end</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct cal_chipset_ops * chip_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int it_hint</code>
</li>
<li>
<b>Field removed. </b>
<code>void * bbar</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 tar_val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list watchdog_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t it_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int it_size</code> ➡️ <code>long unsigned int it_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char it_busno</code> ➡️ <code>long unsigned int it_busno</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_table {
    const struct cal_chipset_ops * chip_ops;
    long unsigned int it_base;
    long unsigned int it_hint;
    long unsigned int * it_map;
    void * bbar;
    u64 tar_val;
    struct timer_list watchdog_timer;
    spinlock_t it_lock;
    unsigned int it_size;
    unsigned char it_busno;
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
