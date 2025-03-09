# Struct: <code>lruvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    struct zone * zone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int refaults;
    long unsigned int flags;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct lru_gen_struct lrugen;
    struct lru_gen_mm_state mm_state;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct lru_gen_folio lrugen;
    struct lru_gen_mm_state mm_state;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    spinlock_t lru_lock;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    atomic_long_t nonresident_age;
    long unsigned int[2] refaults;
    long unsigned int flags;
    struct lru_gen_folio lrugen;
    struct lru_gen_mm_state mm_state;
    struct pglist_data * pgdat;
    struct zswap_lruvec_state zswap_lruvec_state;
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
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
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
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lruvec {
    struct list_head[5] lists;
    struct zone_reclaim_stat reclaim_stat;
    atomic_long_t inactive_age;
    long unsigned int refaults;
    struct pglist_data * pgdat;
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
<code>atomic_long_t inactive_age</code>
</li>
<li>
<b>Field added. </b>
<code>struct pglist_data * pgdat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct zone * zone</code>
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
<code>long unsigned int refaults</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int anon_cost</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int file_cost</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t nonresident_age</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct zone_reclaim_stat reclaim_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t inactive_age</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t lru_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int refaults</code> ➡️ <code>long unsigned int[2] refaults</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lru_gen_struct lrugen</code>
</li>
<li>
<b>Field added. </b>
<code>struct lru_gen_mm_state mm_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct lru_gen_struct lrugen</code> ➡️ <code>struct lru_gen_folio lrugen</code>
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
<code>struct zswap_lruvec_state zswap_lruvec_state</code>
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
