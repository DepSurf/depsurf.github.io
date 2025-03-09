# Struct: <code>ib_ucontext</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    int closing;
    struct mutex uobjects_lock;
    struct list_head uobjects;
    struct rw_semaphore cleanup_rwsem;
    enum rdma_remove_reason cleanup_reason;
    struct pid * tgid;
    struct rb_root_cached umem_tree;
    struct rw_semaphore umem_rwsem;
    void (*)(struct ib_umem *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier mn;
    atomic_t notifier_count;
    struct list_head no_private_counters;
    int odp_mrs_count;
    struct ib_rdmacg_object cg_obj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    int closing;
    struct mutex uobjects_lock;
    struct list_head uobjects;
    struct rw_semaphore cleanup_rwsem;
    enum rdma_remove_reason cleanup_reason;
    struct pid * tgid;
    struct rb_root_cached umem_tree;
    struct rw_semaphore umem_rwsem;
    void (*)(struct ib_umem *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier mn;
    atomic_t notifier_count;
    struct list_head no_private_counters;
    int odp_mrs_count;
    struct ib_rdmacg_object cg_obj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    struct mutex per_mm_list_lock;
    struct list_head per_mm_list;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    struct mutex per_mm_list_lock;
    struct list_head per_mm_list;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
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
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
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
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    bool closing;
    bool cleanup_retryable;
    struct ib_rdmacg_object cg_obj;
    struct rdma_restrack_entry res;
    struct xarray mmap_xa;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ib_ucontext {
    struct ib_device * device;
    struct ib_uverbs_file * ufile;
    int closing;
    struct mutex uobjects_lock;
    struct list_head uobjects;
    struct rw_semaphore cleanup_rwsem;
    enum rdma_remove_reason cleanup_reason;
    struct pid * tgid;
    struct rb_root_cached umem_tree;
    struct rw_semaphore umem_rwsem;
    void (*)(struct ib_umem *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier mn;
    atomic_t notifier_count;
    struct list_head no_private_counters;
    int odp_mrs_count;
    struct ib_rdmacg_object cg_obj;
}
```
</details>
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
<code>bool cleanup_retryable</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex per_mm_list_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head per_mm_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_restrack_entry res</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex uobjects_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head uobjects</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore cleanup_rwsem</code>
</li>
<li>
<b>Field removed. </b>
<code>enum rdma_remove_reason cleanup_reason</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pid * tgid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_root_cached umem_tree</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore umem_rwsem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mmu_notifier mn</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t notifier_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head no_private_counters</code>
</li>
<li>
<b>Field removed. </b>
<code>int odp_mrs_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>int closing</code> ➡️ <code>bool closing</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_umem *, long unsigned int, long unsigned int) invalidate_range</code> ➡️ <code>void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xarray mmap_xa</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex per_mm_list_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head per_mm_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool closing</code>
</li>
<li>
<b>Field removed. </b>
<code>bool cleanup_retryable</code>
</li>
</ul>
</details>
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
