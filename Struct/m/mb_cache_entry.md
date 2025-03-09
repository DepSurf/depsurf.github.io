# Struct: <code>mb_cache_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_lru_list;
    struct mb_cache * e_cache;
    short unsigned int e_used;
    short unsigned int e_queued;
    atomic_t e_refcnt;
    struct block_device * e_bdev;
    sector_t e_block;
    struct hlist_bl_node e_block_list;
    struct (anon) e_index;
    struct hlist_bl_head * e_block_hash_p;
    struct hlist_bl_head * e_index_hash_p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    sector_t e_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    sector_t e_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    long unsigned int e_flags;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    long unsigned int e_flags;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    long unsigned int e_flags;
    u64 e_value;
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
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
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
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mb_cache_entry {
    struct list_head e_list;
    struct hlist_bl_node e_hash_list;
    atomic_t e_refcnt;
    u32 e_key;
    u32 e_referenced;
    u32 e_reusable;
    u64 e_value;
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
<code>struct list_head e_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_bl_node e_hash_list</code>
</li>
<li>
<b>Field added. </b>
<code>u32 e_key</code>
</li>
<li>
<b>Field added. </b>
<code>u32 e_referenced</code>
</li>
<li>
<b>Field added. </b>
<code>u32 e_reusable</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head e_lru_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mb_cache * e_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int e_used</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int e_queued</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * e_bdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_bl_node e_block_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) e_index</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_bl_head * e_block_hash_p</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_bl_head * e_index_hash_p</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 e_value</code>
</li>
<li>
<b>Field removed. </b>
<code>sector_t e_block</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int e_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 e_referenced</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 e_reusable</code>
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
