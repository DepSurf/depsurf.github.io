# Struct: <code>dm_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    struct mapped_device * md;
    int error;
    atomic_t io_count;
    struct bio * bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    struct mapped_device * md;
    int error;
    atomic_t io_count;
    struct bio * bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    struct mapped_device * md;
    int error;
    atomic_t io_count;
    struct bio * bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    short unsigned int magic;
    blk_short_t flags;
    spinlock_t lock;
    long unsigned int start_time;
    void * data;
    struct dm_io * next;
    struct dm_stats_aux stats_aux;
    blk_status_t status;
    atomic_t io_count;
    struct mapped_device * md;
    struct bio * split_bio;
    struct bio * orig_bio;
    unsigned int sector_offset;
    unsigned int sectors;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    short unsigned int magic;
    blk_short_t flags;
    spinlock_t lock;
    long unsigned int start_time;
    void * data;
    struct dm_io * next;
    struct dm_stats_aux stats_aux;
    blk_status_t status;
    atomic_t io_count;
    struct mapped_device * md;
    struct bio * orig_bio;
    unsigned int sector_offset;
    unsigned int sectors;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    short unsigned int magic;
    blk_short_t flags;
    spinlock_t lock;
    long unsigned int start_time;
    void * data;
    struct dm_io * next;
    struct dm_stats_aux stats_aux;
    blk_status_t status;
    atomic_t io_count;
    struct mapped_device * md;
    struct bio * orig_bio;
    unsigned int sector_offset;
    unsigned int sectors;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dm_io {
    short unsigned int magic;
    blk_short_t flags;
    spinlock_t lock;
    long unsigned int start_time;
    void * data;
    struct dm_io * next;
    struct dm_stats_aux stats_aux;
    blk_status_t status;
    atomic_t io_count;
    struct mapped_device * md;
    struct bio * orig_bio;
    unsigned int sector_offset;
    unsigned int sectors;
    struct dm_target_io tio;
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
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
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
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dm_io {
    unsigned int magic;
    struct mapped_device * md;
    blk_status_t status;
    atomic_t io_count;
    struct bio * orig_bio;
    long unsigned int start_time;
    spinlock_t endio_lock;
    struct dm_stats_aux stats_aux;
    struct dm_target_io tio;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>blk_status_t status</code>
</li>
<li>
<b>Field removed. </b>
<code>int error</code>
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
<code>unsigned int magic</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio * orig_bio</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_target_io tio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio * bio</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>blk_short_t flags</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>void * data</code>
</li>
<li>
<b>Field added. </b>
<code>struct dm_io * next</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio * split_bio</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sector_offset</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sectors</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t endio_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int magic</code> ➡️ <code>short unsigned int magic</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct bio * split_bio</code>
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
