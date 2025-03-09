# Struct: <code>blkcg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[2] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[2] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[2] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[3] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[3] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct radix_tree_root blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[3] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[6] cpd;
    struct list_head all_blkcgs_node;
    char[129] fc_app_id;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[6] cpd;
    struct list_head all_blkcgs_node;
    char[129] fc_app_id;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[6] cpd;
    struct list_head all_blkcgs_node;
    struct llist_head * lhead;
    char[129] fc_app_id;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[6] cpd;
    struct list_head all_blkcgs_node;
    struct llist_head * lhead;
    char[129] fc_app_id;
    struct list_head cgwb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    refcount_t online_pin;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[6] cpd;
    struct list_head all_blkcgs_node;
    struct llist_head * lhead;
    char[129] fc_app_id;
    struct list_head cgwb_list;
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
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
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
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blkcg {
    struct cgroup_subsys_state css;
    spinlock_t lock;
    struct xarray blkg_tree;
    struct blkcg_gq * blkg_hint;
    struct hlist_head blkg_list;
    struct blkcg_policy_data *[5] cpd;
    struct list_head all_blkcgs_node;
    struct list_head cgwb_list;
    refcount_t cgwb_refcnt;
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
<code>struct blkcg_policy_data *[2] cpd</code> ➡️ <code>struct blkcg_policy_data *[3] cpd</code>
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
<code>refcount_t cgwb_refcnt</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root blkg_tree</code> ➡️ <code>struct xarray blkg_tree</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blkcg_policy_data *[3] cpd</code> ➡️ <code>struct blkcg_policy_data *[5] cpd</code>
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
<code>refcount_t online_pin</code>
</li>
<li>
<b>Field removed. </b>
<code>refcount_t cgwb_refcnt</code>
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
<code>char[129] fc_app_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blkcg_policy_data *[5] cpd</code> ➡️ <code>struct blkcg_policy_data *[6] cpd</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct llist_head * lhead</code>
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
