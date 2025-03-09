# Struct: <code>ext4_group_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct rb_node bb_avg_fragment_size_rb;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct rb_node bb_avg_fragment_size_rb;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct rb_node bb_avg_fragment_size_rb;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    int bb_avg_fragment_size_order;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct list_head bb_avg_fragment_size_node;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    int bb_avg_fragment_size_order;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct list_head bb_avg_fragment_size_node;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    int bb_avg_fragment_size_order;
    ext4_grpblk_t bb_largest_free_order;
    ext4_group_t bb_group;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    struct list_head bb_avg_fragment_size_node;
    struct list_head bb_largest_free_order_node;
    ext4_grpblk_t[0] bb_counters;
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
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
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
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ext4_group_info {
    long unsigned int bb_state;
    struct rb_root bb_free_root;
    ext4_grpblk_t bb_first_free;
    ext4_grpblk_t bb_free;
    ext4_grpblk_t bb_fragments;
    ext4_grpblk_t bb_largest_free_order;
    struct list_head bb_prealloc_list;
    struct rw_semaphore alloc_sem;
    ext4_grpblk_t[0] bb_counters;
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ext4_group_t bb_group</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_node bb_avg_fragment_size_rb</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bb_largest_free_order_node</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int bb_avg_fragment_size_order</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bb_avg_fragment_size_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_node bb_avg_fragment_size_rb</code>
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
