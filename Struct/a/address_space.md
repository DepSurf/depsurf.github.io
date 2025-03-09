# Struct: <code>address_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root page_tree;
    spinlock_t tree_lock;
    atomic_t i_mmap_writable;
    struct rb_root i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrshadows;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root page_tree;
    spinlock_t tree_lock;
    atomic_t i_mmap_writable;
    struct rb_root i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root page_tree;
    spinlock_t tree_lock;
    atomic_t i_mmap_writable;
    struct rb_root i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    gfp_t gfp_mask;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root page_tree;
    spinlock_t tree_lock;
    atomic_t i_mmap_writable;
    struct rb_root i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    gfp_t gfp_mask;
    struct list_head private_list;
    void * private_data;
    errseq_t wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root page_tree;
    spinlock_t tree_lock;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    gfp_t gfp_mask;
    struct list_head private_list;
    void * private_data;
    errseq_t wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct radix_tree_root i_pages;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    spinlock_t private_lock;
    gfp_t gfp_mask;
    struct list_head private_list;
    void * private_data;
    errseq_t wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    struct rw_semaphore invalidate_lock;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    struct rw_semaphore invalidate_lock;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    struct rw_semaphore invalidate_lock;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    struct rw_semaphore invalidate_lock;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    struct rw_semaphore i_mmap_rwsem;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    struct rw_semaphore invalidate_lock;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    long unsigned int nrpages;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    struct rw_semaphore i_mmap_rwsem;
    errseq_t wb_err;
    spinlock_t i_private_lock;
    struct list_head i_private_list;
    void * i_private_data;
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
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
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
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct address_space {
    struct inode * host;
    struct xarray i_pages;
    gfp_t gfp_mask;
    atomic_t i_mmap_writable;
    struct rb_root_cached i_mmap;
    struct rw_semaphore i_mmap_rwsem;
    long unsigned int nrpages;
    long unsigned int nrexceptional;
    long unsigned int writeback_index;
    const struct address_space_operations * a_ops;
    long unsigned int flags;
    errseq_t wb_err;
    spinlock_t private_lock;
    struct list_head private_list;
    void * private_data;
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
<code>long unsigned int nrexceptional</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int nrshadows</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>errseq_t wb_err</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct rb_root i_mmap</code> ➡️ <code>struct rb_root_cached i_mmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct radix_tree_root i_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>struct radix_tree_root page_tree</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t tree_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root i_pages</code> ➡️ <code>struct xarray i_pages</code>
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
<code>long unsigned int nrexceptional</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rw_semaphore invalidate_lock</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t i_private_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head i_private_list</code>
</li>
<li>
<b>Field added. </b>
<code>void * i_private_data</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t private_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head private_list</code>
</li>
<li>
<b>Field removed. </b>
<code>void * private_data</code>
</li>
</ul>
</details>
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
