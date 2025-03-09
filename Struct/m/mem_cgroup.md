# Struct: <code>mem_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct page_counter memory;
    struct page_counter memsw;
    struct page_counter kmem;
    long unsigned int low;
    long unsigned int high;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    int initialized;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    atomic_t moving_account;
    spinlock_t move_lock;
    struct task_struct * move_lock_task;
    long unsigned int move_lock_flags;
    struct mem_cgroup_stat_cpu * stat;
    struct cg_proto tcp_mem;
    int kmemcg_id;
    bool kmem_acct_activated;
    bool kmem_acct_active;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int low;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    atomic_t moving_account;
    spinlock_t move_lock;
    struct task_struct * move_lock_task;
    long unsigned int move_lock_flags;
    struct mem_cgroup_stat_cpu * stat;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int low;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    atomic_t moving_account;
    spinlock_t move_lock;
    struct task_struct * move_lock_task;
    long unsigned int move_lock_flags;
    struct mem_cgroup_stat_cpu * stat;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int low;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    atomic_t moving_account;
    spinlock_t move_lock;
    struct task_struct * move_lock_task;
    long unsigned int move_lock_flags;
    struct mem_cgroup_stat_cpu * stat;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int low;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    atomic_t moving_account;
    spinlock_t move_lock;
    struct task_struct * move_lock_task;
    long unsigned int move_lock_flags;
    struct mem_cgroup_stat_cpu * stat;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct mem_cgroup_stat_cpu * stat_cpu;
    struct memcg_padding _pad2_;
    atomic_long_t[34] stat;
    atomic_long_t[85] events;
    atomic_long_t[7] memory_events;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct mem_cgroup_stat_cpu * stat_cpu;
    struct memcg_padding _pad2_;
    atomic_long_t[36] stat;
    atomic_long_t[85] events;
    atomic_long_t[7] memory_events;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[36] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[36] vmstats;
    atomic_long_t[92] vmevents;
    atomic_long_t[8] memory_events;
    atomic_long_t[8] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_long_t[41] vmstats;
    atomic_long_t[96] vmevents;
    atomic_long_t[8] memory_events;
    atomic_long_t[8] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct memcg_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    struct memcg_vmstats vmstats;
    atomic_long_t[8] memory_events;
    atomic_long_t[8] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct memcg_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    struct memcg_vmstats vmstats;
    atomic_long_t[8] memory_events;
    atomic_long_t[8] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct memcg_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int zswap_max;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    struct memcg_vmstats vmstats;
    atomic_long_t[9] memory_events;
    atomic_long_t[9] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct memcg_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int zswap_max;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct cacheline_padding _pad1_;
    struct memcg_vmstats * vmstats;
    atomic_long_t[9] memory_events;
    atomic_long_t[9] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct cacheline_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct lru_gen_mm_list mm_list;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int zswap_max;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct cacheline_padding _pad1_;
    struct memcg_vmstats * vmstats;
    atomic_long_t[9] memory_events;
    atomic_long_t[9] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    struct obj_cgroup * objcg;
    struct list_head objcg_list;
    struct cacheline_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct lru_gen_mm_list mm_list;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    struct work_struct high_work;
    long unsigned int zswap_max;
    bool zswap_writeback;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct cacheline_padding _pad1_;
    struct memcg_vmstats * vmstats;
    atomic_long_t[9] memory_events;
    atomic_long_t[9] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    struct obj_cgroup * objcg;
    struct obj_cgroup * orig_objcg;
    struct list_head objcg_list;
    struct cacheline_padding _pad2_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct lru_gen_mm_list mm_list;
    struct mem_cgroup_per_node *[0] nodeinfo;
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
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[81] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[59] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[78] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[61] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct mem_cgroup_per_node *[0] nodeinfo;
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
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mem_cgroup {
    struct cgroup_subsys_state css;
    struct mem_cgroup_id id;
    struct page_counter memory;
    struct page_counter swap;
    struct page_counter memsw;
    struct page_counter kmem;
    struct page_counter tcpmem;
    long unsigned int high;
    struct work_struct high_work;
    long unsigned int soft_limit;
    struct vmpressure vmpressure;
    bool use_hierarchy;
    bool oom_group;
    bool oom_lock;
    int under_oom;
    int swappiness;
    int oom_kill_disable;
    struct cgroup_file events_file;
    struct cgroup_file events_local_file;
    struct cgroup_file swap_events_file;
    struct mutex thresholds_lock;
    struct mem_cgroup_thresholds thresholds;
    struct mem_cgroup_thresholds memsw_thresholds;
    struct list_head oom_notify;
    long unsigned int move_charge_at_immigrate;
    spinlock_t move_lock;
    long unsigned int move_lock_flags;
    struct memcg_padding _pad1_;
    atomic_t moving_account;
    struct task_struct * move_lock_task;
    struct memcg_vmstats_percpu * vmstats_local;
    struct memcg_vmstats_percpu * vmstats_percpu;
    struct memcg_padding _pad2_;
    atomic_long_t[38] vmstats;
    atomic_long_t[85] vmevents;
    atomic_long_t[7] memory_events;
    atomic_long_t[7] memory_events_local;
    long unsigned int socket_pressure;
    bool tcpmem_active;
    int tcpmem_pressure;
    int kmemcg_id;
    enum memcg_kmem_state kmem_state;
    struct list_head kmem_caches;
    int last_scanned_node;
    nodemask_t scan_nodes;
    atomic_t numainfo_events;
    atomic_t numainfo_updating;
    struct list_head cgwb_list;
    struct wb_domain cgwb_domain;
    struct memcg_cgwb_frn[4] cgwb_frn;
    struct list_head event_list;
    spinlock_t event_list_lock;
    struct deferred_split deferred_split_queue;
    struct mem_cgroup_per_node *[0] nodeinfo;
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
<code>struct mem_cgroup_id id</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_counter swap</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_counter tcpmem</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct high_work</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int socket_pressure</code>
</li>
<li>
<b>Field added. </b>
<code>bool tcpmem_active</code>
</li>
<li>
<b>Field added. </b>
<code>int tcpmem_pressure</code>
</li>
<li>
<b>Field added. </b>
<code>enum memcg_kmem_state kmem_state</code>
</li>
<li>
<b>Field removed. </b>
<code>int initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cg_proto tcp_mem</code>
</li>
<li>
<b>Field removed. </b>
<code>bool kmem_acct_activated</code>
</li>
<li>
<b>Field removed. </b>
<code>bool kmem_acct_active</code>
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
<code>struct list_head kmem_caches</code>
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
<b>Field added. </b>
<code>struct cgroup_file swap_events_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct memcg_padding _pad1_</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup_stat_cpu * stat_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct memcg_padding _pad2_</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[85] events</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[7] memory_events</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int low</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mem_cgroup_stat_cpu * stat</code> ➡️ <code>atomic_long_t[34] stat</code>
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
<code>bool oom_group</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[34] stat</code> ➡️ <code>atomic_long_t[36] stat</code>
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
<code>struct cgroup_file events_local_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct memcg_vmstats_percpu * vmstats_local</code>
</li>
<li>
<b>Field added. </b>
<code>struct memcg_vmstats_percpu * vmstats_percpu</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[36] vmstats</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[85] vmevents</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t[7] memory_events_local</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mem_cgroup_stat_cpu * stat_cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t[36] stat</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t[85] events</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct memcg_cgwb_frn[4] cgwb_frn</code>
</li>
<li>
<b>Field added. </b>
<code>struct deferred_split deferred_split_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[36] vmstats</code> ➡️ <code>atomic_long_t[38] vmstats</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int high</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_scanned_node</code>
</li>
<li>
<b>Field removed. </b>
<code>nodemask_t scan_nodes</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_events</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_updating</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[38] vmstats</code> ➡️ <code>atomic_long_t[36] vmstats</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[85] vmevents</code> ➡️ <code>atomic_long_t[92] vmevents</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[7] memory_events</code> ➡️ <code>atomic_long_t[8] memory_events</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[7] memory_events_local</code> ➡️ <code>atomic_long_t[8] memory_events_local</code>
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
<code>struct obj_cgroup * objcg</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head objcg_list</code>
</li>
<li>
<b>Field removed. </b>
<code>bool use_hierarchy</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head kmem_caches</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[36] vmstats</code> ➡️ <code>atomic_long_t[41] vmstats</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[92] vmevents</code> ➡️ <code>atomic_long_t[96] vmevents</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_long_t[96] vmevents</code>
</li>
<li>
<b>Field removed. </b>
<code>struct memcg_vmstats_percpu * vmstats_local</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[41] vmstats</code> ➡️ <code>struct memcg_vmstats vmstats</code>
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
<code>long unsigned int zswap_max</code>
</li>
<li>
<b>Field removed. </b>
<code>enum memcg_kmem_state kmem_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[8] memory_events</code> ➡️ <code>atomic_long_t[9] memory_events</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[8] memory_events_local</code> ➡️ <code>atomic_long_t[9] memory_events_local</code>
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
<code>struct lru_gen_mm_list mm_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct memcg_padding _pad1_</code> ➡️ <code>struct cacheline_padding _pad1_</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct memcg_vmstats vmstats</code> ➡️ <code>struct memcg_vmstats * vmstats</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct memcg_padding _pad2_</code> ➡️ <code>struct cacheline_padding _pad2_</code>
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
<code>bool zswap_writeback</code>
</li>
<li>
<b>Field added. </b>
<code>struct obj_cgroup * orig_objcg</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[85] vmevents</code> ➡️ <code>atomic_long_t[81] vmevents</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>nodemask_t scan_nodes</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_events</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_updating</code>
</li>
<li>
<b>Field removed. </b>
<code>struct deferred_split deferred_split_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[85] vmevents</code> ➡️ <code>atomic_long_t[59] vmevents</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[85] vmevents</code> ➡️ <code>atomic_long_t[78] vmevents</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>nodemask_t scan_nodes</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_events</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t numainfo_updating</code>
</li>
<li>
<b>Field removed. </b>
<code>struct deferred_split deferred_split_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t[85] vmevents</code> ➡️ <code>atomic_long_t[61] vmevents</code>
</li>
</ul>
</details>
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
