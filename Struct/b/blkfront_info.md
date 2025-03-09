# Struct: <code>blkfront_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    spinlock_t io_lock;
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    int[16] ring_ref;
    unsigned int nr_ring_pages;
    struct blkif_front_ring ring;
    unsigned int evtchn;
    unsigned int irq;
    struct request_queue * rq;
    struct work_struct work;
    struct gnttab_free_callback callback;
    struct blk_shadow[512] shadow;
    struct list_head grants;
    struct list_head indirect_pages;
    unsigned int persistent_gnts_c;
    long unsigned int shadow_free;
    unsigned int feature_flush;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int feature_persistent;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int feature_persistent;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    long unsigned int vdisk_info;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int bounce;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    long unsigned int vdisk_info;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent_parm;
    unsigned int feature_persistent;
    unsigned int bounce;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    long unsigned int vdisk_info;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent_parm;
    unsigned int feature_persistent;
    unsigned int bounce;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    long unsigned int vdisk_info;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent_parm;
    unsigned int feature_persistent;
    unsigned int bounce;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    unsigned int rinfo_size;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
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
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
    struct completion wait_backend_disconnected;
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
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
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
<code>u16 sector_size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int physical_sector_size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int feature_fua</code>
</li>
<li>
<b>Field added. </b>
<code>struct blkfront_ring_info * rinfo</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nr_rings</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head requests</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_list bio_list</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t io_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>int[16] ring_ref</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blkif_front_ring ring</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int evtchn</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int irq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct gnttab_free_callback callback</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_shadow[512] shadow</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head grants</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head indirect_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int persistent_gnts_c</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int shadow_free</code>
</li>
</ul>
</details>
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
<code>struct list_head info_list</code>
</li>
</ul>
</details>
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
<code>unsigned int rinfo_size</code>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int vdisk_info</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bounce</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int feature_persistent_parm</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct completion wait_backend_disconnected</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct blkfront_info {
    struct mutex mutex;
    struct xenbus_device * xbdev;
    struct gendisk * gd;
    u16 sector_size;
    unsigned int physical_sector_size;
    int vdevice;
    blkif_vdev_t handle;
    enum blkif_state connected;
    unsigned int nr_ring_pages;
    struct request_queue * rq;
    unsigned int feature_flush;
    unsigned int feature_fua;
    unsigned int feature_discard;
    unsigned int feature_secdiscard;
    unsigned int feature_persistent;
    unsigned int discard_granularity;
    unsigned int discard_alignment;
    unsigned int max_indirect_segments;
    int is_ready;
    struct blk_mq_tag_set tag_set;
    struct blkfront_ring_info * rinfo;
    unsigned int nr_rings;
    struct list_head requests;
    struct bio_list bio_list;
    struct list_head info_list;
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
