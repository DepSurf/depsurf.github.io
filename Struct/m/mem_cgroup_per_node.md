# Struct: <code>mem_cgroup_per_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct mem_cgroup_per_zone[5] zoneinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    long unsigned int[5] lru_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[28] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[30] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[30] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[33] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[38] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct batched_lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[39] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stats_percpu * lruvec_stats_percpu;
    struct lruvec_stats lruvec_stats;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stats_percpu * lruvec_stats_percpu;
    struct lruvec_stats lruvec_stats;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stats_percpu * lruvec_stats_percpu;
    struct lruvec_stats lruvec_stats;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stats_percpu * lruvec_stats_percpu;
    struct lruvec_stats lruvec_stats;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stats_percpu * lruvec_stats_percpu;
    struct lruvec_stats lruvec_stats;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter iter;
    struct shrinker_info * shrinker_info;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    struct mem_cgroup * memcg;
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
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[15] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[15] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[15] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[15] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
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
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mem_cgroup_per_node {
    struct lruvec lruvec;
    struct lruvec_stat * lruvec_stat_local;
    struct lruvec_stat * lruvec_stat_cpu;
    atomic_long_t[32] lruvec_stat;
    long unsigned int[25] lru_zone_size;
    struct mem_cgroup_reclaim_iter[13] iter;
    struct memcg_shrinker_map * shrinker_map;
    struct rb_node tree_node;
    long unsigned int usage_in_excess;
    bool on_tree;
    bool congested;
    struct mem_cgroup * memcg;
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
<code>struct lruvec lruvec</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[5] lru_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup_reclaim_iter[13] iter</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_node tree_node</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int usage_in_excess</code>
</li>
<li>
<b>Field added. </b>
<code>bool on_tree</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mem_cgroup_per_zone[5] zoneinfo</code>
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
<code>long unsigned int[25] lru_zone_size</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[5] lru_size</code>
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
<code>struct lruvec_stat * lruvec_stat</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lruvec_stat * lruvec_stat_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>bool congested</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct lruvec_stat * lruvec_stat</code> ➡️ <code>atomic_long_t[28] lruvec_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct memcg_shrinker_map * shrinker_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[28] lruvec_stat</code> ➡️ <code>atomic_long_t[30] lruvec_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lruvec_stat * lruvec_stat_local</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[30] lruvec_stat</code> ➡️ <code>atomic_long_t[32] lruvec_stat</code>
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
<code>bool congested</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[32] lruvec_stat</code> ➡️ <code>atomic_long_t[33] lruvec_stat</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mem_cgroup_reclaim_iter[13] iter</code> ➡️ <code>struct mem_cgroup_reclaim_iter iter</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[33] lruvec_stat</code> ➡️ <code>atomic_long_t[38] lruvec_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct shrinker_info * shrinker_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct memcg_shrinker_map * shrinker_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct lruvec_stat * lruvec_stat_cpu</code> ➡️ <code>struct batched_lruvec_stat * lruvec_stat_cpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[38] lruvec_stat</code> ➡️ <code>atomic_long_t[39] lruvec_stat</code>
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
<code>struct lruvec_stats_percpu * lruvec_stats_percpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct lruvec_stats lruvec_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lruvec_stat * lruvec_stat_local</code>
</li>
<li>
<b>Field removed. </b>
<code>struct batched_lruvec_stat * lruvec_stat_cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t[39] lruvec_stat</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[25] lru_zone_size</code> ➡️ <code>long unsigned int[15] lru_zone_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[25] lru_zone_size</code> ➡️ <code>long unsigned int[15] lru_zone_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[25] lru_zone_size</code> ➡️ <code>long unsigned int[15] lru_zone_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[25] lru_zone_size</code> ➡️ <code>long unsigned int[15] lru_zone_size</code>
</li>
</ul>
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
