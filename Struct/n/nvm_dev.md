# Struct: <code>nvm_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct list_head online_targets;
    struct nvmm_type * mt;
    void * mp;
    struct nvm_sb_info sb;
    int nr_chnls;
    int nr_planes;
    int luns_per_chnl;
    int sec_per_pg;
    int pgs_per_blk;
    int blks_per_lun;
    int sec_size;
    int oob_size;
    int mccap;
    struct nvm_addr_format ppaf;
    int max_rq_size;
    int plane_mode;
    int sec_per_pl;
    int sec_per_blk;
    int sec_per_lun;
    int lps_per_blk;
    int * lptbl;
    long unsigned int total_pages;
    long unsigned int total_blocks;
    int nr_luns;
    unsigned int max_pages_per_blk;
    void * ppalist_pool;
    struct nvm_id identity;
    struct request_queue * q;
    char[32] name;
    struct mutex mlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvmm_type * mt;
    void * mp;
    struct nvm_sb_info sb;
    int nr_chnls;
    int nr_planes;
    int luns_per_chnl;
    int sec_per_pg;
    int pgs_per_blk;
    int blks_per_lun;
    int fpg_size;
    int pfpg_size;
    int sec_size;
    int oob_size;
    int mccap;
    struct nvm_addr_format ppaf;
    int max_rq_size;
    int plane_mode;
    int sec_per_pl;
    int sec_per_blk;
    int sec_per_lun;
    int lps_per_blk;
    int * lptbl;
    long unsigned int total_blocks;
    long unsigned int total_secs;
    int nr_luns;
    long unsigned int * lun_map;
    void * dma_pool;
    struct nvm_id identity;
    struct request_queue * q;
    char[32] name;
    struct mutex mlock;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvmm_type * mt;
    void * mp;
    struct nvm_sb_info sb;
    struct nvm_geo geo;
    int lps_per_blk;
    int * lptbl;
    long unsigned int total_secs;
    long unsigned int * lun_map;
    void * dma_pool;
    struct nvm_id identity;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    int lps_per_blk;
    int * lptbl;
    long unsigned int total_secs;
    long unsigned int * lun_map;
    void * dma_pool;
    struct nvm_id identity;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    int lps_per_blk;
    int * lptbl;
    long unsigned int total_secs;
    long unsigned int * lun_map;
    void * dma_pool;
    struct nvm_id identity;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
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
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
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
<code>int fpg_size</code>
</li>
<li>
<b>Field added. </b>
<code>int pfpg_size</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int total_secs</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * lun_map</code>
</li>
<li>
<b>Field added. </b>
<code>void * dma_pool</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head online_targets</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int total_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_pages_per_blk</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ppalist_pool</code>
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
<code>struct nvm_geo geo</code>
</li>
<li>
<b>Field added. </b>
<code>void * private_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * rmap</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_chnls</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_planes</code>
</li>
<li>
<b>Field removed. </b>
<code>int luns_per_chnl</code>
</li>
<li>
<b>Field removed. </b>
<code>int sec_per_pg</code>
</li>
<li>
<b>Field removed. </b>
<code>int pgs_per_blk</code>
</li>
<li>
<b>Field removed. </b>
<code>int blks_per_lun</code>
</li>
<li>
<b>Field removed. </b>
<code>int fpg_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int pfpg_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int sec_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int oob_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int mccap</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvm_addr_format ppaf</code>
</li>
<li>
<b>Field removed. </b>
<code>int max_rq_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int plane_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>int sec_per_pl</code>
</li>
<li>
<b>Field removed. </b>
<code>int sec_per_blk</code>
</li>
<li>
<b>Field removed. </b>
<code>int sec_per_lun</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int total_blocks</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_luns</code>
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
<code>struct list_head area_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head targets</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvmm_type * mt</code>
</li>
<li>
<b>Field removed. </b>
<code>void * mp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvm_sb_info sb</code>
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
<b>Field removed. </b>
<code>int lps_per_blk</code>
</li>
<li>
<b>Field removed. </b>
<code>int * lptbl</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int total_secs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvm_id identity</code>
</li>
</ul>
</details>
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
<code>struct kref ref</code>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct nvm_dev {
    struct nvm_dev_ops * ops;
    struct list_head devices;
    struct nvm_geo geo;
    long unsigned int * lun_map;
    void * dma_pool;
    struct request_queue * q;
    char[32] name;
    void * private_data;
    struct kref ref;
    void * rmap;
    struct mutex mlock;
    spinlock_t lock;
    struct list_head area_list;
    struct list_head targets;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
