# Struct: <code>bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    unsigned int bi_flags;
    int bi_error;
    long unsigned int bi_rw;
    struct bvec_iter bi_iter;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    int bi_error;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    struct bvec_iter bi_iter;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    int bi_error;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    struct bvec_iter bi_iter;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    blk_status_t bi_status;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    struct bvec_iter bi_iter;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct io_context * bi_ioc;
    struct cgroup_subsys_state * bi_css;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    unsigned int bi_phys_segments;
    unsigned int bi_seg_front_size;
    unsigned int bi_seg_back_size;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    blk_qc_t bi_cookie;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    blk_opf_t bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    blk_qc_t bi_cookie;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    blk_opf_t bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    blk_qc_t bi_cookie;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct block_device * bi_bdev;
    blk_opf_t bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    blk_status_t bi_status;
    atomic_t __bi_remaining;
    struct bvec_iter bi_iter;
    blk_qc_t bi_cookie;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_crypt_ctx * bi_crypt_context;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
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
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
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
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bio {
    struct bio * bi_next;
    struct gendisk * bi_disk;
    unsigned int bi_opf;
    short unsigned int bi_flags;
    short unsigned int bi_ioprio;
    short unsigned int bi_write_hint;
    blk_status_t bi_status;
    u8 bi_partno;
    struct bvec_iter bi_iter;
    atomic_t __bi_remaining;
    bio_end_io_t * bi_end_io;
    void * bi_private;
    struct blkcg_gq * bi_blkg;
    struct bio_issue bi_issue;
    u64 bi_iocost_cost;
    struct bio_integrity_payload * bi_integrity;
    short unsigned int bi_vcnt;
    short unsigned int bi_max_vecs;
    atomic_t __bi_cnt;
    struct bio_vec * bi_io_vec;
    struct bio_set * bi_pool;
    struct bio_vec[0] bi_inline_vecs;
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
<code>unsigned int bi_opf</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int bi_ioprio</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int bi_rw</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int bi_flags</code> ➡️ <code>short unsigned int bi_flags</code>
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
<code>blk_status_t bi_status</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int bi_write_hint</code>
</li>
<li>
<b>Field removed. </b>
<code>int bi_error</code>
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
<code>struct gendisk * bi_disk</code>
</li>
<li>
<b>Field added. </b>
<code>u8 bi_partno</code>
</li>
<li>
<b>Field removed. </b>
<code>struct block_device * bi_bdev</code>
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
<code>struct blkcg_gq * bi_blkg</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_issue bi_issue</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_context * bi_ioc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_subsys_state * bi_css</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int bi_phys_segments</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bi_seg_front_size</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bi_seg_back_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 bi_iocost_cost</code>
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
<code>struct bio_crypt_ctx * bi_crypt_context</code>
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
<code>struct block_device * bi_bdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct gendisk * bi_disk</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 bi_partno</code>
</li>
</ul>
</details>
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
<code>blk_qc_t bi_cookie</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int bi_write_hint</code>
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
<code>unsigned int bi_opf</code> ➡️ <code>blk_opf_t bi_opf</code>
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
