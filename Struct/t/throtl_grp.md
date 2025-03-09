# Struct: <code>throtl_grp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[2] bps;
    unsigned int[2] iops;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[2] bps;
    unsigned int[2] iops;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[2] bps;
    unsigned int[2] iops;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    atomic_t[2] io_split_cnt;
    atomic_t[2] last_io_split_cnt;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules_bps;
    bool[2] has_rules_iops;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    uint64_t[2] carryover_bytes;
    unsigned int[2] carryover_ios;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules_bps;
    bool[2] has_rules_iops;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    uint64_t[2] carryover_bytes;
    unsigned int[2] carryover_ios;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules_bps;
    bool[2] has_rules_iops;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long long int[2] carryover_bytes;
    int[2] carryover_ios;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
    struct blkg_rwstat stat_bytes;
    struct blkg_rwstat stat_ios;
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
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
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
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct throtl_grp {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    struct throtl_data * td;
    struct throtl_service_queue service_queue;
    struct throtl_qnode[2] qnode_on_self;
    struct throtl_qnode[2] qnode_on_parent;
    long unsigned int disptime;
    unsigned int flags;
    bool[2] has_rules;
    uint64_t[4] bps;
    uint64_t[4] bps_conf;
    unsigned int[4] iops;
    unsigned int[4] iops_conf;
    uint64_t[2] bytes_disp;
    unsigned int[2] io_disp;
    long unsigned int[2] last_low_overflow_time;
    uint64_t[2] last_bytes_disp;
    unsigned int[2] last_io_disp;
    long unsigned int last_check_time;
    long unsigned int latency_target;
    long unsigned int latency_target_conf;
    long unsigned int[2] slice_start;
    long unsigned int[2] slice_end;
    long unsigned int last_finish_time;
    long unsigned int checked_last_finish_time;
    long unsigned int avg_idletime;
    long unsigned int idletime_threshold;
    long unsigned int idletime_threshold_conf;
    unsigned int bio_cnt;
    unsigned int bad_bio_cnt;
    long unsigned int bio_cnt_reset_time;
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
<code>uint64_t[4] bps_conf</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int[4] iops_conf</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[2] last_low_overflow_time</code>
</li>
<li>
<b>Field added. </b>
<code>uint64_t[2] last_bytes_disp</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int[2] last_io_disp</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_check_time</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int latency_target</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int latency_target_conf</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_finish_time</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int checked_last_finish_time</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int avg_idletime</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int idletime_threshold</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int idletime_threshold_conf</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bio_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bad_bio_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bio_cnt_reset_time</code>
</li>
<li>
<b>Field type changed. </b>
<code>uint64_t[2] bps</code> ➡️ <code>uint64_t[4] bps</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[2] iops</code> ➡️ <code>unsigned int[4] iops</code>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<code>struct blkg_rwstat stat_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>struct blkg_rwstat stat_ios</code>
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
<code>atomic_t[2] io_split_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t[2] last_io_split_cnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t[2] io_split_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t[2] last_io_split_cnt</code>
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
<code>bool[2] has_rules_bps</code>
</li>
<li>
<b>Field added. </b>
<code>bool[2] has_rules_iops</code>
</li>
<li>
<b>Field added. </b>
<code>uint64_t[2] carryover_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int[2] carryover_ios</code>
</li>
<li>
<b>Field removed. </b>
<code>bool[2] has_rules</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>uint64_t[2] carryover_bytes</code> ➡️ <code>long long int[2] carryover_bytes</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[2] carryover_ios</code> ➡️ <code>int[2] carryover_ios</code>
</li>
</ul>
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
