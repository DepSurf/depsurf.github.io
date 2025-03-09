# Struct: <code>ioc_gq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat local_stat;
    struct iocg_stat desc_stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat local_stat;
    struct iocg_stat desc_stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat local_stat;
    struct iocg_stat desc_stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    s64 saved_margin;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    u64 abs_vdebt;
    u64 delay;
    u64 delay_at;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    u64 child_adjusted_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    u32 hweight_donating;
    u32 hweight_after_donation;
    struct list_head walk_list;
    struct list_head surplus_list;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    u64 activated_at;
    struct iocg_pcpu_stat * pcpu_stat;
    struct iocg_stat stat;
    struct iocg_stat last_stat;
    u64 last_stat_abs_vusage;
    u64 usage_delta_us;
    u64 wait_since;
    u64 indebt_since;
    u64 indelay_since;
    int level;
    struct ioc_gq *[0] ancestors;
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
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
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
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct ioc_gq {
    struct blkg_policy_data pd;
    struct ioc * ioc;
    u32 cfg_weight;
    u32 weight;
    u32 active;
    u32 inuse;
    u32 last_inuse;
    sector_t cursor;
    atomic64_t vtime;
    atomic64_t done_vtime;
    atomic64_t abs_vdebt;
    u64 last_vtime;
    atomic64_t active_period;
    struct list_head active_list;
    u64 child_active_sum;
    u64 child_inuse_sum;
    int hweight_gen;
    u32 hweight_active;
    u32 hweight_inuse;
    bool has_surplus;
    struct wait_queue_head waitq;
    struct hrtimer waitq_timer;
    struct hrtimer delay_timer;
    int usage_idx;
    u32[3] usages;
    int level;
    struct ioc_gq *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic64_t abs_vdebt</code> ➡️ <code>u64 abs_vdebt</code>
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
<code>s64 saved_margin</code>
</li>
<li>
<b>Field added. </b>
<code>u64 delay</code>
</li>
<li>
<b>Field added. </b>
<code>u64 delay_at</code>
</li>
<li>
<b>Field added. </b>
<code>u64 child_adjusted_sum</code>
</li>
<li>
<b>Field added. </b>
<code>u32 hweight_donating</code>
</li>
<li>
<b>Field added. </b>
<code>u32 hweight_after_donation</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head walk_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head surplus_list</code>
</li>
<li>
<b>Field added. </b>
<code>u64 activated_at</code>
</li>
<li>
<b>Field added. </b>
<code>struct iocg_pcpu_stat * pcpu_stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct iocg_stat local_stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct iocg_stat desc_stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct iocg_stat last_stat</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_stat_abs_vusage</code>
</li>
<li>
<b>Field added. </b>
<code>u64 usage_delta_us</code>
</li>
<li>
<b>Field added. </b>
<code>u64 wait_since</code>
</li>
<li>
<b>Field added. </b>
<code>u64 indebt_since</code>
</li>
<li>
<b>Field added. </b>
<code>u64 indelay_since</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_vtime</code>
</li>
<li>
<b>Field removed. </b>
<code>bool has_surplus</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hrtimer delay_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>int usage_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>u32[3] usages</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iocg_stat stat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iocg_stat local_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iocg_stat desc_stat</code>
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
