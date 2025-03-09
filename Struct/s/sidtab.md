# Struct: <code>sidtab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    struct sidtab_node * * htable;
    unsigned int nel;
    unsigned int next_sid;
    unsigned char shutdown;
    struct sidtab_node *[3] cache;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    atomic_t count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    atomic_t[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    atomic_t count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    atomic_t[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    bool frozen;
    spinlock_t lock;
    u32 cache_free_slots;
    struct list_head cache_lru_list;
    spinlock_t cache_lock;
    struct sidtab_isid_entry[27] isids;
    struct hlist_head[512] context_to_sid;
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
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[3] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
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
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sidtab {
    union sidtab_entry_inner[4] roots;
    u32 count;
    struct sidtab_convert_params * convert;
    spinlock_t lock;
    u32[3] rcache;
    struct sidtab_isid_entry[27] isids;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>union sidtab_entry_inner[4] roots</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t count</code>
</li>
<li>
<b>Field added. </b>
<code>struct sidtab_convert_params * convert</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t[3] rcache</code>
</li>
<li>
<b>Field added. </b>
<code>struct sidtab_isid_entry[27] isids</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sidtab_node * * htable</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nel</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int next_sid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char shutdown</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sidtab_node *[3] cache</code>
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
<b>Field type changed. </b>
<code>atomic_t count</code> ➡️ <code>u32 count</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t[3] rcache</code> ➡️ <code>u32[3] rcache</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 cache_free_slots</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head cache_lru_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t cache_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head[512] context_to_sid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32[3] rcache</code>
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
<code>bool frozen</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>union sidtab_entry_inner[4] roots</code> ➡️ <code>union sidtab_entry_inner[3] roots</code>
</li>
</ul>
</details>
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
