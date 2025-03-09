# Struct: <code>cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int populated_cnt;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    unsigned int subtree_control;
    unsigned int child_subsys_mask;
    struct cgroup_subsys_state *[12] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[12] e_csets;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int populated_cnt;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[12] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[12] e_csets;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int populated_cnt;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[12] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[12] e_csets;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct cgroup_bpf bpf;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int populated_cnt;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct cgroup_bpf bpf;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup_cpu_stat * cpu_stat;
    struct cgroup_stat pending_stat;
    struct cgroup_stat stat;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct cgroup_bpf bpf;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct cgroup_bpf bpf;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    u64[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    u64[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    u64[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    u64[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    u64[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    struct cgroup_file[3] psi_files;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group * psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    struct bpf_local_storage * bpf_cgrp_storage;
    struct cgroup *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    struct cgroup_file[3] psi_files;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group * psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    struct bpf_local_storage * bpf_cgrp_storage;
    struct cgroup *[0] ancestors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    struct cgroup_file[3] psi_files;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[14] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[14] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cacheline_padding _pad_;
    struct cgroup * rstat_flush_next;
    struct cgroup_base_stat last_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group * psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    struct bpf_local_storage * bpf_cgrp_storage;
    struct cgroup *[0] ancestors;
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
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[12] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[12] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
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
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup {
    struct cgroup_subsys_state self;
    long unsigned int flags;
    int id;
    int level;
    int max_depth;
    int nr_descendants;
    int nr_dying_descendants;
    int max_descendants;
    int nr_populated_csets;
    int nr_populated_domain_children;
    int nr_populated_threaded_children;
    int nr_threaded_children;
    struct kernfs_node * kn;
    struct cgroup_file procs_file;
    struct cgroup_file events_file;
    u16 subtree_control;
    u16 subtree_ss_mask;
    u16 old_subtree_control;
    u16 old_subtree_ss_mask;
    struct cgroup_subsys_state *[13] subsys;
    struct cgroup_root * root;
    struct list_head cset_links;
    struct list_head[13] e_csets;
    struct cgroup * dom_cgrp;
    struct cgroup * old_dom_cgrp;
    struct cgroup_rstat_cpu * rstat_cpu;
    struct list_head rstat_css_list;
    struct cgroup_base_stat pending_bstat;
    struct cgroup_base_stat bstat;
    struct prev_cputime prev_cputime;
    struct list_head pidlists;
    struct mutex pidlist_mutex;
    wait_queue_head_t offline_waitq;
    struct work_struct release_agent_work;
    struct psi_group psi;
    struct cgroup_bpf bpf;
    atomic_t congestion_count;
    struct cgroup_freezer_state freezer;
    int[0] ancestor_ids;
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
<code>int level</code>
</li>
<li>
<b>Field added. </b>
<code>u16 subtree_ss_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u16 old_subtree_control</code>
</li>
<li>
<b>Field added. </b>
<code>u16 old_subtree_ss_mask</code>
</li>
<li>
<b>Field added. </b>
<code>int[0] ancestor_ids</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int child_subsys_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int subtree_control</code> ➡️ <code>u16 subtree_control</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cgroup_bpf bpf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cgroup_subsys_state *[12] subsys</code> ➡️ <code>struct cgroup_subsys_state *[13] subsys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[12] e_csets</code> ➡️ <code>struct list_head[13] e_csets</code>
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
<code>int max_depth</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_descendants</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_dying_descendants</code>
</li>
<li>
<b>Field added. </b>
<code>int max_descendants</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_populated_csets</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_populated_domain_children</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_populated_threaded_children</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_threaded_children</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup * dom_cgrp</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_cpu_stat * cpu_stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_stat pending_stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_stat stat</code>
</li>
<li>
<b>Field removed. </b>
<code>int populated_cnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cgroup_rstat_cpu * rstat_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rstat_css_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_base_stat pending_bstat</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_base_stat bstat</code>
</li>
<li>
<b>Field added. </b>
<code>struct prev_cputime prev_cputime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_cpu_stat * cpu_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_stat pending_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_stat stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cgroup * old_dom_cgrp</code>
</li>
<li>
<b>Field added. </b>
<code>struct psi_group psi</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t congestion_count</code>
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
<code>struct cgroup_freezer_state freezer</code>
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
<code>struct cgroup_base_stat last_bstat</code>
</li>
<li>
<b>Field removed. </b>
<code>int id</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_base_stat pending_bstat</code>
</li>
<li>
<b>Field type changed. </b>
<code>int[0] ancestor_ids</code> ➡️ <code>u64[0] ancestor_ids</code>
</li>
</ul>
</details>
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
<code>struct list_head[13] e_csets</code> ➡️ <code>struct list_head[14] e_csets</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<code>struct cgroup_file[3] psi_files</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_local_storage * bpf_cgrp_storage</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup *[0] ancestors</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[0] ancestor_ids</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct psi_group psi</code> ➡️ <code>struct psi_group * psi</code>
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
<b>Field added. </b>
<code>struct cacheline_padding _pad_</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup * rstat_flush_next</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cgroup_subsys_state *[13] subsys</code> ➡️ <code>struct cgroup_subsys_state *[12] subsys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[13] e_csets</code> ➡️ <code>struct list_head[12] e_csets</code>
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
