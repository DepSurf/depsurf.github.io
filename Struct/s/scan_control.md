# Struct: <code>scan_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int may_thrash;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    enum zone_type reclaim_idx;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int may_thrash;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    enum zone_type reclaim_idx;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int may_thrash;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    enum zone_type reclaim_idx;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    enum zone_type reclaim_idx;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    gfp_t gfp_mask;
    int order;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    int priority;
    enum zone_type reclaim_idx;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int may_shrinkslab;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    unsigned int no_demotion;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    unsigned int no_demotion;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int proactive;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    unsigned int no_demotion;
    unsigned int memcgs_need_aging;
    long unsigned int last_reclaimed;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int proactive;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    unsigned int no_demotion;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    long unsigned int anon_cost;
    long unsigned int file_cost;
    unsigned int may_deactivate;
    unsigned int force_deactivate;
    unsigned int skipped_deactivate;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int proactive;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    unsigned int cache_trim_mode;
    unsigned int file_is_tiny;
    unsigned int no_demotion;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
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
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
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
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scan_control {
    long unsigned int nr_to_reclaim;
    nodemask_t * nodemask;
    struct mem_cgroup * target_mem_cgroup;
    unsigned int may_writepage;
    unsigned int may_unmap;
    unsigned int may_swap;
    unsigned int memcg_low_reclaim;
    unsigned int memcg_low_skipped;
    unsigned int hibernation_mode;
    unsigned int compaction_ready;
    s8 order;
    s8 priority;
    s8 reclaim_idx;
    gfp_t gfp_mask;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    struct (anon) nr;
    struct reclaim_state reclaim_state;
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
<code>enum zone_type reclaim_idx</code>
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
<code>unsigned int memcg_low_reclaim</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int memcg_low_skipped</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int may_thrash</code>
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
<code>struct (anon) nr</code>
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
<code>unsigned int may_shrinkslab</code>
</li>
<li>
<b>Field type changed. </b>
<code>int order</code> ➡️ <code>s8 order</code>
</li>
<li>
<b>Field type changed. </b>
<code>int priority</code> ➡️ <code>s8 priority</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum zone_type reclaim_idx</code> ➡️ <code>s8 reclaim_idx</code>
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
<code>struct reclaim_state reclaim_state</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int may_shrinkslab</code>
</li>
</ul>
</details>
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
<code>unsigned int may_deactivate</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int force_deactivate</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int skipped_deactivate</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cache_trim_mode</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int file_is_tiny</code>
</li>
</ul>
</details>
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
<code>unsigned int no_demotion</code>
</li>
</ul>
</details>
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
<code>unsigned int proactive</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int memcgs_need_aging</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_reclaimed</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int memcgs_need_aging</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_reclaimed</code>
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
