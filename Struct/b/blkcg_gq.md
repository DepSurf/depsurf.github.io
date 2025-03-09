# Struct: <code>blkcg_gq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[2] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[2] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[2] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[3] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[3] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct request_list rl;
    atomic_t refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[3] pd;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    struct callback_head callback_head;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[6] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[6] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    struct work_struct free_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[6] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    struct work_struct free_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[6] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    struct work_struct free_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_iostat_set * iostat_cpu;
    struct blkg_iostat_set iostat;
    struct blkg_policy_data *[6] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    struct work_struct free_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
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
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
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
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blkcg_gq {
    struct request_queue * q;
    struct list_head q_node;
    struct hlist_node blkcg_node;
    struct blkcg * blkcg;
    struct bdi_writeback_congested * wb_congested;
    struct blkcg_gq * parent;
    struct percpu_ref refcnt;
    bool online;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
    struct blkg_policy_data *[5] pd;
    spinlock_t async_bio_lock;
    struct bio_list async_bios;
    struct work_struct async_bio_work;
    atomic_t use_delay;
    atomic64_t delay_nsec;
    atomic64_t delay_start;
    u64 last_delay;
    int last_use;
    struct callback_head callback_head;
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
<b>Field type changed. </b>
<code>struct blkg_policy_data *[2] pd</code> ➡️ <code>struct blkg_policy_data *[3] pd</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t use_delay</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t delay_nsec</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t delay_start</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_delay</code>
</li>
<li>
<b>Field added. </b>
<code>int last_use</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_list rl</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>struct percpu_ref refcnt</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blkg_policy_data *[3] pd</code> ➡️ <code>struct blkg_policy_data *[5] pd</code>
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
<code>spinlock_t async_bio_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_list async_bios</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct async_bio_work</code>
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
<code>struct blkg_iostat_set * iostat_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct blkg_iostat_set iostat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blkg_rwstat stat_bytes</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blkg_rwstat stat_ios</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct bdi_writeback_congested * wb_congested</code>
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
<b>Field type changed. </b>
<code>struct blkg_policy_data *[5] pd</code> ➡️ <code>struct blkg_policy_data *[6] pd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct work_struct free_work</code>
</li>
</ul>
</details>
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
