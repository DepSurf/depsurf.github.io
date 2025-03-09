# Function: <code>task_work_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494400,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:27",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494400,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508544,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:27",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508544,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529216,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:27",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529216,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516752,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:27",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516752,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542880,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542880,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570576,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570576,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607568,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607568,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631920,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631920,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657456,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657456,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int task_work_add(struct task_struct * task, struct callback_head * work, int notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579690192,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:__io_async_wake",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690192,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579668528,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:32",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_link_timeout_fn",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:io_timeout_cancel",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_req_task_work_add",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668528,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675184,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:32",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_req_task_work_add",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675184,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753392,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:32",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_ring_exit_work",
        "fs/io_uring.c:io_req_task_work_add",
        "fs/io-wq.c:io_queue_worker_create",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753392,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858688,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:42",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io-wq.c:io_queue_worker_create",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858688,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999904,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:42",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/msg_ring.c:io_msg_ring",
        "io_uring/rsrc.c:io_rsrc_node_ref_zero",
        "io_uring/io-wq.c:io_queue_worker_create",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999904,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053776,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:42",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/core.c:task_tick_mm_cid",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:io_req_normal_work_add",
        "io_uring/msg_ring.c:io_msg_send_fd",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/io-wq.c:io_queue_worker_create",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053776,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int task_work_add(struct task_struct * task, struct callback_head * work, enum task_work_notify_mode notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096240,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:42",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:queue_task_work",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/core.c:task_tick_mm_cid",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access",
        "io_uring/io_uring.c:io_ring_exit_work",
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:io_req_normal_work_add",
        "io_uring/msg_ring.c:io_msg_send_fd",
        "io_uring/msg_ring.c:io_msg_ring_data",
        "io_uring/io-wq.c:io_queue_worker_create",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096240,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490831616,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490831616,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224862344,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224862344,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283665840,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283665840,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271502978,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_thread",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271502978,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633776,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633776,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562096,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562096,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631040,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631040,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int task_work_add(struct task_struct * task, struct callback_head * work, bool notify)
```

```json
{
  "name": "task_work_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665056,
      "name": "task_work_add",
      "external": true,
      "loc": "kernel/task_work.c:28",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/irq/manage.c:irq_thread",
        "kernel/events/uprobes.c:uprobe_copy_process",
        "fs/file_table.c:fput_many",
        "fs/namespace.c:mntput_no_expire",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/yama/yama_lsm.c:report_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665056,
      "name": "task_work_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool notify</code> ➡️ <code>int notify</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int notify</code> ➡️ <code>enum task_work_notify_mode notify</code>
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
