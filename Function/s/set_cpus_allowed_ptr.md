# Function: <code>set_cpus_allowed_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547424,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1261",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/kthread.c:kthreadd",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cpuset.c:update_tasks_cpumask",
        "kernel/cpuset.c:cpuset_attach",
        "mm/vmscan.c:kswapd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547424,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595257480,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1197",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cpuset.c:cpuset_fork",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558784,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595502122,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1208",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cpuset.c:cpuset_fork",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583712,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596421874,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1132",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567328,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602746280,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1147",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597072,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602918692,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1144",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628672,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604716398,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1139",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666304,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604816966,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1581",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697552,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604851229,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738432,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609181841,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1771",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:rebind_workers",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774432,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612247369,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2395",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:rebind_workers",
        "kernel/workqueue.c:unbind_workers",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764016,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614388295,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2416",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_wq_worker_affinity",
        "fs/io-wq.c:create_io_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771728,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615322039,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2851",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_init_new_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862720,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617104457,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2950",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:unbind_workers",
        "kernel/workqueue.c:unbind_workers",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io-wq.c:io_init_new_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978144,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627767678,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:3017",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:unbind_workers",
        "kernel/workqueue.c:unbind_workers",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_init_new_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138832,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619530750,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:3193",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:unbind_worker",
        "kernel/workqueue.c:unbind_worker",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_init_new_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217968,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621829598,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:3223",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:unbind_worker",
        "kernel/workqueue.c:unbind_worker",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_init_new_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266768,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510884588,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490916680,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243371388,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224934684,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302517424,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283765344,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270625170,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271554344,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604756496,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715056,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604724123,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642944,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604834063,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702320,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask)
```

```json
{
  "name": "set_cpus_allowed_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604855398,
      "name": "set_cpus_allowed_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:1701",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:worker_attach_to_pool",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/reboot.c:migrate_to_reboot_cpu",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/vmscan.c:kswapd_cpu_online",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd_cpu_online",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745680,
      "name": "set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
