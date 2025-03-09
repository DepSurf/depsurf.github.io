# Struct: <code>css_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    atomic_t refcount;
    struct hlist_node hlist;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head cgrp_links;
    struct cgroup * dfl_cgrp;
    struct cgroup_subsys_state *[12] subsys;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct css_set * mg_dst_cset;
    struct list_head[12] e_cset_node;
    struct list_head task_iters;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    atomic_t refcount;
    struct hlist_node hlist;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head cgrp_links;
    struct cgroup * dfl_cgrp;
    struct cgroup_subsys_state *[12] subsys;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    struct list_head[12] e_cset_node;
    struct list_head task_iters;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    atomic_t refcount;
    struct hlist_node hlist;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head cgrp_links;
    struct cgroup * dfl_cgrp;
    struct cgroup_subsys_state *[12] subsys;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    struct list_head[12] e_cset_node;
    struct list_head task_iters;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_src_preload_node;
    struct list_head mg_dst_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_src_preload_node;
    struct list_head mg_dst_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_src_preload_node;
    struct list_head mg_dst_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[14] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[14] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_src_preload_node;
    struct list_head mg_dst_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
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
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[12] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[12] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
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
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct css_set {
    struct cgroup_subsys_state *[13] subsys;
    refcount_t refcount;
    struct css_set * dom_cset;
    struct cgroup * dfl_cgrp;
    int nr_tasks;
    struct list_head tasks;
    struct list_head mg_tasks;
    struct list_head dying_tasks;
    struct list_head task_iters;
    struct list_head[13] e_cset_node;
    struct list_head threaded_csets;
    struct list_head threaded_csets_node;
    struct hlist_node hlist;
    struct list_head cgrp_links;
    struct list_head mg_preload_node;
    struct list_head mg_node;
    struct cgroup * mg_src_cgrp;
    struct cgroup * mg_dst_cgrp;
    struct css_set * mg_dst_cset;
    bool dead;
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cgroup * mg_dst_cgrp</code>
</li>
<li>
<b>Field added. </b>
<code>bool dead</code>
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
<code>int nr_tasks</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t refcount</code> ➡️ <code>refcount_t refcount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct cgroup_subsys_state *[12] subsys</code> ➡️ <code>struct cgroup_subsys_state *[13] subsys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[12] e_cset_node</code> ➡️ <code>struct list_head[13] e_cset_node</code>
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
<code>struct css_set * dom_cset</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head threaded_csets</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head threaded_csets_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head dying_tasks</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cgroup_subsys_state *[13] subsys</code> ➡️ <code>struct cgroup_subsys_state *[14] subsys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[13] e_cset_node</code> ➡️ <code>struct list_head[14] e_cset_node</code>
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
<code>struct list_head mg_src_preload_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mg_dst_preload_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head mg_preload_node</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cgroup_subsys_state *[13] subsys</code> ➡️ <code>struct cgroup_subsys_state *[12] subsys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[13] e_cset_node</code> ➡️ <code>struct list_head[12] e_cset_node</code>
</li>
</ul>
</details>
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
