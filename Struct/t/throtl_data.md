# Struct: <code>throtl_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int nr_undestroyed_grps;
    struct work_struct dispatch_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    struct work_struct dispatch_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    struct work_struct dispatch_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[9] tmp_buckets;
    struct avg_latency_bucket[9] avg_buckets;
    struct latency_bucket * latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[9] tmp_buckets;
    struct avg_latency_bucket[9] avg_buckets;
    struct latency_bucket * latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
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
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
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
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct throtl_data {
    struct throtl_service_queue service_queue;
    struct request_queue * queue;
    unsigned int[2] nr_queued;
    unsigned int throtl_slice;
    struct work_struct dispatch_work;
    unsigned int limit_index;
    bool[2] limit_valid;
    long unsigned int low_upgrade_time;
    long unsigned int low_downgrade_time;
    unsigned int scale;
    struct latency_bucket[18] tmp_buckets;
    struct avg_latency_bucket[18] avg_buckets;
    struct latency_bucket *[2] latency_buckets;
    long unsigned int last_calculate_time;
    long unsigned int filtered_latency;
    bool track_bio_latency;
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
<b>Field removed. </b>
<code>unsigned int nr_undestroyed_grps</code>
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
<code>unsigned int throtl_slice</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int limit_index</code>
</li>
<li>
<b>Field added. </b>
<code>bool[2] limit_valid</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int low_upgrade_time</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int low_downgrade_time</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int scale</code>
</li>
<li>
<b>Field added. </b>
<code>struct latency_bucket[9] tmp_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>struct avg_latency_bucket[9] avg_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>struct latency_bucket * latency_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_calculate_time</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int filtered_latency</code>
</li>
<li>
<b>Field added. </b>
<code>bool track_bio_latency</code>
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
<b>Field type changed. </b>
<code>struct latency_bucket[9] tmp_buckets</code> ➡️ <code>struct latency_bucket[18] tmp_buckets</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct avg_latency_bucket[9] avg_buckets</code> ➡️ <code>struct avg_latency_bucket[18] avg_buckets</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct latency_bucket * latency_buckets</code> ➡️ <code>struct latency_bucket *[2] latency_buckets</code>
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
