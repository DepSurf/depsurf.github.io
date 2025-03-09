# Struct: <code>cgroup_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *) css_e_css_changed;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    int (*)(struct task_struct *, void * *) can_fork;
    void (*)(struct task_struct *, void *) cancel_fork;
    void (*)(struct task_struct *, void *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    int early_init;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) free;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_local_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *, struct css_set *) can_fork;
    void (*)(struct task_struct *, struct css_set *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
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
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
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
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup_subsys {
    struct cgroup_subsys_state * (*)(struct cgroup_subsys_state *) css_alloc;
    int (*)(struct cgroup_subsys_state *) css_online;
    void (*)(struct cgroup_subsys_state *) css_offline;
    void (*)(struct cgroup_subsys_state *) css_released;
    void (*)(struct cgroup_subsys_state *) css_free;
    void (*)(struct cgroup_subsys_state *) css_reset;
    void (*)(struct cgroup_subsys_state *, int) css_rstat_flush;
    int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show;
    int (*)(struct cgroup_taskset *) can_attach;
    void (*)(struct cgroup_taskset *) cancel_attach;
    void (*)(struct cgroup_taskset *) attach;
    void (*)() post_attach;
    int (*)(struct task_struct *) can_fork;
    void (*)(struct task_struct *) cancel_fork;
    void (*)(struct task_struct *) fork;
    void (*)(struct task_struct *) exit;
    void (*)(struct task_struct *) release;
    void (*)(struct cgroup_subsys_state *) bind;
    bool early_init;
    bool implicit_on_dfl;
    bool threaded;
    bool broken_hierarchy;
    bool warned_broken_hierarchy;
    int id;
    const char * name;
    const char * legacy_name;
    struct cgroup_root * root;
    struct idr css_idr;
    struct list_head cfts;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    unsigned int depends_on;
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
<code>void (*)() post_attach</code>
</li>
<li>
<b>Field added. </b>
<code>bool implicit_on_dfl</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct cgroup_subsys_state *) css_e_css_changed</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct task_struct *, void * *) can_fork</code> ➡️ <code>int (*)(struct task_struct *) can_fork</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *, void *) cancel_fork</code> ➡️ <code>void (*)(struct task_struct *) cancel_fork</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *, void *) fork</code> ➡️ <code>void (*)(struct task_struct *) fork</code>
</li>
<li>
<b>Field type changed. </b>
<code>int early_init</code> ➡️ <code>bool early_init</code>
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct seq_file *, struct cgroup_subsys_state *) css_extra_stat_show</code>
</li>
<li>
<b>Field added. </b>
<code>bool threaded</code>
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
<code>void (*)(struct cgroup_subsys_state *, int) css_rstat_flush</code>
</li>
</ul>
</details>
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
<code>void (*)(struct task_struct *) release</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct task_struct *) free</code>
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
<b>Field type changed. </b>
<code>int (*)(struct task_struct *) can_fork</code> ➡️ <code>int (*)(struct task_struct *, struct css_set *) can_fork</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *) cancel_fork</code> ➡️ <code>void (*)(struct task_struct *, struct css_set *) cancel_fork</code>
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
<code>bool broken_hierarchy</code>
</li>
<li>
<b>Field removed. </b>
<code>bool warned_broken_hierarchy</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
<code>int (*)(struct seq_file *, struct cgroup_subsys_state *) css_local_stat_show</code>
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
