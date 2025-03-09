# Struct: <code>ext4_allocation_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    ext4_group_t ac_last_optimal_group;
    __u32 ac_groups_considered;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    ext4_group_t ac_last_optimal_group;
    __u32 ac_groups_considered;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    ext4_group_t ac_last_optimal_group;
    __u32 ac_groups_considered;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u32 ac_groups_considered;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    ext4_grpblk_t ac_orig_goal_len;
    __u32 ac_groups_considered;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16[5] ac_cX_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    ext4_grpblk_t ac_orig_goal_len;
    __u32 ac_flags;
    __u16 ac_groups_scanned;
    __u16 ac_groups_linear_remaining;
    __u16 ac_found;
    __u16[5] ac_cX_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
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
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
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
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ext4_allocation_context {
    struct inode * ac_inode;
    struct super_block * ac_sb;
    struct ext4_free_extent ac_o_ex;
    struct ext4_free_extent ac_g_ex;
    struct ext4_free_extent ac_b_ex;
    struct ext4_free_extent ac_f_ex;
    __u16 ac_groups_scanned;
    __u16 ac_found;
    __u16 ac_tail;
    __u16 ac_buddy;
    __u16 ac_flags;
    __u8 ac_status;
    __u8 ac_criteria;
    __u8 ac_2order;
    __u8 ac_op;
    struct page * ac_bitmap_page;
    struct page * ac_buddy_page;
    struct ext4_prealloc_space * ac_pa;
    struct ext4_locality_group * ac_lg;
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
<code>ext4_group_t ac_last_optimal_group</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 ac_groups_considered</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 ac_groups_linear_remaining</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 ac_flags</code> ➡️ <code>__u32 ac_flags</code>
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
<b>Field removed. </b>
<code>ext4_group_t ac_last_optimal_group</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ext4_grpblk_t ac_orig_goal_len</code>
</li>
<li>
<b>Field added. </b>
<code>__u16[5] ac_cX_found</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__u32 ac_groups_considered</code>
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
