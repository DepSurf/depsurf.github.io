# Struct: <code>zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    unsigned int inactive_ratio;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int dirty_balance_reserve;
    long unsigned int min_unmapped_pages;
    long unsigned int min_slab_pages;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    wait_queue_head_t * wait_table;
    long unsigned int wait_table_hash_nr_entries;
    long unsigned int wait_table_bits;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    spinlock_t lru_lock;
    struct lruvec lruvec;
    atomic_long_t inactive_age;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    struct zone_padding _pad3_;
    atomic_long_t[39] vm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    wait_queue_head_t * wait_table;
    long unsigned int wait_table_hash_nr_entries;
    long unsigned int wait_table_bits;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[21] vm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[21] vm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[19] vm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] watermark;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    long unsigned int managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[11] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[11] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pages * per_cpu_pageset;
    struct per_cpu_zonestat * per_cpu_zonestats;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    long unsigned int present_early_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[11] vm_stat;
    atomic_long_t[6] vm_numa_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[4] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pages * per_cpu_pageset;
    struct per_cpu_zonestat * per_cpu_zonestats;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    long unsigned int present_early_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[11] vm_stat;
    atomic_long_t[6] vm_numa_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[4] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pages * per_cpu_pageset;
    struct per_cpu_zonestat * per_cpu_zonestats;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    long unsigned int present_early_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct cacheline_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct cacheline_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct cacheline_padding _pad3_;
    atomic_long_t[11] vm_stat;
    atomic_long_t[6] vm_numa_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[4] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pages * per_cpu_pageset;
    struct per_cpu_zonestat * per_cpu_zonestats;
    int pageset_high;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    long unsigned int present_early_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct cacheline_padding _pad1_;
    struct free_area[11] free_area;
    struct list_head unaccepted_pages;
    long unsigned int flags;
    spinlock_t lock;
    struct cacheline_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct cacheline_padding _pad3_;
    atomic_long_t[12] vm_stat;
    atomic_long_t[6] vm_numa_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[4] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pages * per_cpu_pageset;
    struct per_cpu_zonestat * per_cpu_zonestats;
    int pageset_high_min;
    int pageset_high_max;
    int pageset_batch;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    long unsigned int present_early_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct cacheline_padding _pad1_;
    struct free_area[11] free_area;
    struct list_head unaccepted_pages;
    long unsigned int flags;
    spinlock_t lock;
    struct cacheline_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct cacheline_padding _pad3_;
    atomic_long_t[12] vm_stat;
    atomic_long_t[6] vm_numa_event;
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
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[3] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[13] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[3] lowmem_reserve;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int * pageblock_flags;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[12] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[0] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[3] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[9] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[3] lowmem_reserve;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[0] vm_numa_stat;
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
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct zone {
    long unsigned int[3] _watermark;
    long unsigned int watermark_boost;
    long unsigned int nr_reserved_highatomic;
    long int[5] lowmem_reserve;
    int node;
    struct pglist_data * zone_pgdat;
    struct per_cpu_pageset * pageset;
    long unsigned int zone_start_pfn;
    atomic_long_t managed_pages;
    long unsigned int spanned_pages;
    long unsigned int present_pages;
    const char * name;
    long unsigned int nr_isolate_pageblock;
    seqlock_t span_seqlock;
    int initialized;
    struct zone_padding _pad1_;
    struct free_area[11] free_area;
    long unsigned int flags;
    spinlock_t lock;
    struct zone_padding _pad2_;
    long unsigned int percpu_drift_mark;
    long unsigned int compact_cached_free_pfn;
    long unsigned int[2] compact_cached_migrate_pfn;
    long unsigned int compact_init_migrate_pfn;
    long unsigned int compact_init_free_pfn;
    unsigned int compact_considered;
    unsigned int compact_defer_shift;
    int compact_order_failed;
    bool compact_blockskip_flush;
    bool contiguous;
    struct zone_padding _pad3_;
    atomic_long_t[13] vm_stat;
    atomic_long_t[6] vm_numa_stat;
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
<code>bool contiguous</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int inactive_ratio</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int dirty_balance_reserve</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int min_unmapped_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int min_slab_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t lru_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lruvec lruvec</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t inactive_age</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[39] vm_stat</code> ➡️ <code>atomic_long_t[21] vm_stat</code>
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
<code>int initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t * wait_table</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int wait_table_hash_nr_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int wait_table_bits</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[21] vm_stat</code> ➡️ <code>atomic_long_t[19] vm_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_long_t[6] vm_numa_stat</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[19] vm_stat</code> ➡️ <code>atomic_long_t[13] vm_stat</code>
</li>
</ul>
</details>
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
<code>long unsigned int[3] _watermark</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int watermark_boost</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[3] watermark</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int managed_pages</code> ➡️ <code>atomic_long_t managed_pages</code>
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
<code>long unsigned int compact_init_migrate_pfn</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int compact_init_free_pfn</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int pageset_high</code>
</li>
<li>
<b>Field added. </b>
<code>int pageset_batch</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[13] vm_stat</code> ➡️ <code>atomic_long_t[11] vm_stat</code>
</li>
</ul>
</details>
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
<code>struct per_cpu_pages * per_cpu_pageset</code>
</li>
<li>
<b>Field added. </b>
<code>struct per_cpu_zonestat * per_cpu_zonestats</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int present_early_pages</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[6] vm_numa_event</code>
</li>
<li>
<b>Field removed. </b>
<code>struct per_cpu_pageset * pageset</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t[6] vm_numa_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[3] _watermark</code> ➡️ <code>long unsigned int[4] _watermark</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct zone_padding _pad1_</code> ➡️ <code>struct cacheline_padding _pad1_</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct zone_padding _pad2_</code> ➡️ <code>struct cacheline_padding _pad2_</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct zone_padding _pad3_</code> ➡️ <code>struct cacheline_padding _pad3_</code>
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
<code>struct list_head unaccepted_pages</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[11] vm_stat</code> ➡️ <code>atomic_long_t[12] vm_stat</code>
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
<code>int pageset_high_min</code>
</li>
<li>
<b>Field added. </b>
<code>int pageset_high_max</code>
</li>
<li>
<b>Field removed. </b>
<code>int pageset_high</code>
</li>
</ul>
</details>
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
<code>long int[5] lowmem_reserve</code> ➡️ <code>long int[3] lowmem_reserve</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct free_area[11] free_area</code> ➡️ <code>struct free_area[13] free_area</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int * pageblock_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>int node</code>
</li>
<li>
<b>Field removed. </b>
<code>seqlock_t span_seqlock</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[5] lowmem_reserve</code> ➡️ <code>long int[3] lowmem_reserve</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct free_area[11] free_area</code> ➡️ <code>struct free_area[12] free_area</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[6] vm_numa_stat</code> ➡️ <code>atomic_long_t[0] vm_numa_stat</code>
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
<code>long int[5] lowmem_reserve</code> ➡️ <code>long int[3] lowmem_reserve</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct free_area[11] free_area</code> ➡️ <code>struct free_area[9] free_area</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int node</code>
</li>
<li>
<b>Field removed. </b>
<code>seqlock_t span_seqlock</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[5] lowmem_reserve</code> ➡️ <code>long int[3] lowmem_reserve</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[6] vm_numa_stat</code> ➡️ <code>atomic_long_t[0] vm_numa_stat</code>
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
