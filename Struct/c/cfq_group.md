# Struct: <code>cfq_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    long unsigned int saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<b>Field type changed. </b>
<code>long unsigned int saved_wl_slice</code> ➡️ <code>u64 saved_wl_slice</code>
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
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct cfq_group {
    struct blkg_policy_data pd;
    struct rb_node rb_node;
    u64 vdisktime;
    int nr_active;
    unsigned int children_weight;
    unsigned int vfraction;
    unsigned int weight;
    unsigned int new_weight;
    unsigned int dev_weight;
    unsigned int leaf_weight;
    unsigned int new_leaf_weight;
    unsigned int dev_leaf_weight;
    int nr_cfqq;
    unsigned int[3] busy_queues_avg;
    struct cfq_rb_root[6] service_trees;
    struct cfq_rb_root service_tree_idle;
    u64 saved_wl_slice;
    enum wl_type_t saved_wl_type;
    enum wl_class_t saved_wl_class;
    int dispatched;
    struct cfq_ttime ttime;
    struct cfqg_stats stats;
    struct cfq_queue *[16] async_cfqq;
    struct cfq_queue * async_idle_cfqq;
}
```
</details>
</li>
</ul>
