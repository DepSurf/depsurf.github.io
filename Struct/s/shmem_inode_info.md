# Struct: <code>shmem_inode_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct shared_policy policy;
    struct list_head swaplist;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    long unsigned int fallocend;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    long unsigned int fallocend;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct timespec64 i_crtime;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    long unsigned int fallocend;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct timespec64 i_crtime;
    unsigned int fsflags;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    long unsigned int fallocend;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct timespec64 i_crtime;
    unsigned int fsflags;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct offset_ctx dir_offsets;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct timespec64 i_crtime;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    long unsigned int fallocend;
    unsigned int fsflags;
    atomic_t stop_eviction;
    struct dquot *[3] i_dquot;
    struct inode vfs_inode;
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
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
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
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct shmem_inode_info {
    spinlock_t lock;
    unsigned int seals;
    long unsigned int flags;
    long unsigned int alloced;
    long unsigned int swapped;
    struct list_head shrinklist;
    struct list_head swaplist;
    struct shared_policy policy;
    struct simple_xattrs xattrs;
    atomic_t stop_eviction;
    struct inode vfs_inode;
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
<code>struct list_head shrinklist</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t stop_eviction</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int fallocend</code>
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
<code>struct timespec64 i_crtime</code>
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
<code>unsigned int fsflags</code>
</li>
</ul>
</details>
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
<code>struct offset_ctx dir_offsets</code>
</li>
<li>
<b>Field added. </b>
<code>struct dquot *[3] i_dquot</code>
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
