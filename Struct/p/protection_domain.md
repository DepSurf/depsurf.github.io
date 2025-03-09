# Struct: <code>protection_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
    void * priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool updated;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    u16 id;
    atomic64_t pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    u16 id;
    atomic64_t pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    int nid;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head dev_list;
    struct iommu_domain domain;
    struct amd_io_pgtable iop;
    spinlock_t lock;
    u16 id;
    int glx;
    int nid;
    u64 * gcr3_tbl;
    long unsigned int flags;
    bool dirty_tracking;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
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
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
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
<code>void * priv</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool updated</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex api_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>int mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 * pt_root</code> ➡️ <code>atomic64_t pt_root</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct amd_io_pgtable iop</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic64_t pt_root</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int nid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool dirty_tracking</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct protection_domain {
    struct list_head list;
    struct list_head dev_list;
    struct iommu_domain domain;
    spinlock_t lock;
    struct mutex api_lock;
    u16 id;
    int mode;
    u64 * pt_root;
    int glx;
    u64 * gcr3_tbl;
    long unsigned int flags;
    unsigned int dev_cnt;
    unsigned int[32] dev_iommu;
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
