# Struct: <code>cgroup_subsys_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct cgroup_subsys_state * parent;
    struct list_head sibling;
    struct list_head children;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct callback_head callback_head;
    struct work_struct destroy_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct cgroup_subsys_state * parent;
    struct list_head sibling;
    struct list_head children;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct callback_head callback_head;
    struct work_struct destroy_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct cgroup_subsys_state * parent;
    struct list_head sibling;
    struct list_head children;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct callback_head callback_head;
    struct work_struct destroy_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct callback_head callback_head;
    struct work_struct destroy_work;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct callback_head callback_head;
    struct work_struct destroy_work;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
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
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
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
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state {
    struct cgroup * cgroup;
    struct cgroup_subsys * ss;
    struct percpu_ref refcnt;
    struct list_head sibling;
    struct list_head children;
    struct list_head rstat_css_node;
    int id;
    unsigned int flags;
    u64 serial_nr;
    atomic_t online_cnt;
    struct work_struct destroy_work;
    struct rcu_work destroy_rwork;
    struct cgroup_subsys_state * parent;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head rstat_css_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_work destroy_rwork</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head callback_head</code>
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
