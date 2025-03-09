# Struct: <code>ext4_prealloc_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    union (anon) pa_node;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    union (anon) pa_node_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    union (anon) pa_node;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    union (anon) pa_node_lock;
    struct inode * pa_inode;
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
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
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
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ext4_prealloc_space {
    struct list_head pa_inode_list;
    struct list_head pa_group_list;
    union (anon) u;
    spinlock_t pa_lock;
    atomic_t pa_count;
    unsigned int pa_deleted;
    ext4_fsblk_t pa_pstart;
    ext4_lblk_t pa_lstart;
    ext4_grpblk_t pa_len;
    ext4_grpblk_t pa_free;
    short unsigned int pa_type;
    spinlock_t * pa_obj_lock;
    struct inode * pa_inode;
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>union (anon) pa_node</code>
</li>
<li>
<b>Field added. </b>
<code>union (anon) pa_node_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head pa_inode_list</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t * pa_obj_lock</code>
</li>
</ul>
</details>
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
