# Function: <code>queue_rcu_work</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541200,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1625",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541200,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578272,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1645",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578272,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601808,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1741",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601808,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627696,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627696,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656880,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1741",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/aio.c:free_ioctx_reqs",
        "block/partitions/core.c:hd_struct_free",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656880,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636496,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1747",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636496,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643120,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1748",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643120,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719728,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1778",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719728,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823040,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1768",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823040,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958960,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1768",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958960,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009648,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1970",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/trace/trace_events_user.c:user_event_mm_remove",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009648,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052512,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:2056",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/trace/trace_events_user.c:user_event_mm_remove",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/aio.c:free_ioctx_reqs",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_unmap_iomem",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "net/core/skmsg.c:sk_psock_drop",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052512,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
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
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490797952,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490797952,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224833852,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224833852,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283621232,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283621232,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271474752,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271474752,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
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
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604000,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604000,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532640,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532640,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601280,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601280,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```

```json
{
  "name": "queue_rcu_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635968,
      "name": "queue_rcu_work",
      "external": true,
      "loc": "kernel/workqueue.c:1744",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "fs/aio.c:free_ioctx_reqs",
        "block/partition-generic.c:__delete_partition",
        "net/sched/cls_api.c:tcf_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635968,
      "name": "queue_rcu_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool queue_rcu_work(struct workqueue_struct * wq, struct rcu_work * rwork)
```
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
