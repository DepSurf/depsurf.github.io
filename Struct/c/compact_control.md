# Struct: <code>compact_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    int order;
    const gfp_t gfp_mask;
    const int alloc_flags;
    const int classzone_idx;
    struct zone * zone;
    int contended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool direct_compaction;
    bool whole_zone;
    int order;
    const gfp_t gfp_mask;
    const unsigned int alloc_flags;
    const int classzone_idx;
    struct zone * zone;
    bool contended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    int order;
    const gfp_t gfp_mask;
    const unsigned int alloc_flags;
    const int classzone_idx;
    struct zone * zone;
    bool contended;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    struct zone * zone;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool finishing_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    struct zone * zone;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool finishing_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    struct zone * zone;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool finishing_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    struct zone * zone;
    long unsigned int nr_freepages;
    long unsigned int nr_migratepages;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int last_migrated_pfn;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool finishing_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool finish_pageblock;
    bool alloc_contig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int highest_zoneidx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool proactive_compaction;
    bool whole_zone;
    bool contended;
    bool finish_pageblock;
    bool alloc_contig;
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
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
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
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compact_control {
    struct list_head freepages;
    struct list_head migratepages;
    unsigned int nr_freepages;
    unsigned int nr_migratepages;
    long unsigned int free_pfn;
    long unsigned int migrate_pfn;
    long unsigned int fast_start_pfn;
    struct zone * zone;
    long unsigned int total_migrate_scanned;
    long unsigned int total_free_scanned;
    short unsigned int fast_search_fail;
    short int search_order;
    const gfp_t gfp_mask;
    int order;
    int migratetype;
    const unsigned int alloc_flags;
    const int classzone_idx;
    enum migrate_mode mode;
    bool ignore_skip_hint;
    bool no_set_skip_hint;
    bool ignore_block_suitable;
    bool direct_compaction;
    bool whole_zone;
    bool contended;
    bool rescan;
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
<code>bool direct_compaction</code>
</li>
<li>
<b>Field added. </b>
<code>bool whole_zone</code>
</li>
<li>
<b>Field type changed. </b>
<code>const int alloc_flags</code> ➡️ <code>const unsigned int alloc_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>int contended</code> ➡️ <code>bool contended</code>
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
<code>bool ignore_block_suitable</code>
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
<code>long unsigned int total_migrate_scanned</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int total_free_scanned</code>
</li>
<li>
<b>Field added. </b>
<code>int migratetype</code>
</li>
<li>
<b>Field added. </b>
<code>bool finishing_block</code>
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
<code>bool no_set_skip_hint</code>
</li>
</ul>
</details>
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
<code>long unsigned int fast_start_pfn</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int fast_search_fail</code>
</li>
<li>
<b>Field added. </b>
<code>short int search_order</code>
</li>
<li>
<b>Field added. </b>
<code>bool rescan</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_migrated_pfn</code>
</li>
<li>
<b>Field removed. </b>
<code>bool finishing_block</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int nr_freepages</code> ➡️ <code>unsigned int nr_freepages</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int nr_migratepages</code> ➡️ <code>unsigned int nr_migratepages</code>
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
<code>const int highest_zoneidx</code>
</li>
<li>
<b>Field added. </b>
<code>bool alloc_contig</code>
</li>
<li>
<b>Field removed. </b>
<code>const int classzone_idx</code>
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
<code>bool proactive_compaction</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool finish_pageblock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool rescan</code>
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
