# Struct: <code>hd_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    atomic_t[2] in_flight;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
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
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    seqcount_t nr_sects_seq;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    struct rcu_work rcu_work;
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
<code>struct rcu_work rcu_work</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t[2] in_flight</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head callback_head</code>
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
<b>Field removed. </b>
<code>seqcount_t nr_sects_seq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct hd_struct {
    sector_t start_sect;
    sector_t nr_sects;
    long unsigned int stamp;
    struct disk_stats * dkstats;
    struct percpu_ref ref;
    sector_t alignment_offset;
    unsigned int discard_alignment;
    struct device __dev;
    struct kobject * holder_dir;
    int policy;
    int partno;
    struct partition_meta_info * info;
    struct rcu_work rcu_work;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
