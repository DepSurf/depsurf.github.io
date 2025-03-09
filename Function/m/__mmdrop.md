# Function: <code>__mmdrop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360480,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:686",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:idle_task_exit",
        "mm/oom_kill.c:oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__ksm_exit",
        "mm/huge_memory.c:collect_mm_slot",
        "mm/huge_memory.c:__khugepaged_exit",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360480,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367632,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:699",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_reap_task",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367632,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579385776,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:850",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385776,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373312,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:897",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373312,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579400192,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:907",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400192,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:629",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427712,
      "name": "__mmdrop.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579412496,
      "name": "__mmdrop",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:672",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461136,
      "name": "__mmdrop.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579445168,
      "name": "__mmdrop",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:678",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/hmm.c:hmm_free_rcu",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478864,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579461248,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504828,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579487568,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:698",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:bprm_mm_init",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_start",
        "fs/io_uring.c:io_poll_add",
        "fs/io_uring.c:__io_req_aux_free",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533097,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579515264,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:683",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_req_clean_work",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591276732,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579498432,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:687",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591219630,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579502832,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:699",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592098079,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579573504,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:788",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:__do_sys_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release",
        "io_uring/io_uring.c:io_ring_ctx_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593865275,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579665344,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784736,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:793",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_use_mm",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:new_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/iommu/iommu.c:iommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784736,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831504,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:915",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/trace/trace_events_user.c:user_event_mm_destroy",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:new_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/iommu/iommu.c:iommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831504,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869376,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:913",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/cpu.c:finish_cpu",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/trace/trace_events_user.c:user_event_mm_destroy",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_notifier.c:mmu_interval_notifier_remove",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/userfaultfd.c:new_userfaultfd",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:mem_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/iommu/iommu.c:iommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869376,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490622216,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_put_kvm",
        "virt/kvm/kvm_main.c:kvm_create_vm",
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__arm64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490622216,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224699368,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_do_scan",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224699368,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283439280,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb",
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release",
        "drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_release",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283439280,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271378360,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mm",
        "kernel/fork.c:mm_access",
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_do_scan",
        "fs/exec.c:__do_execve_file",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271378360,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478492,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579461232,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407388,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579390192,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478412,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579461152,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __mmdrop(struct mm_struct * mm)
```

```json
{
  "name": "__mmdrop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmdrop",
      "external": true,
      "loc": "kernel/fork.c:690",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmdrop_async_fn",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:finish_task_switch",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:collect_mm_slot",
        "mm/khugepaged.c:__khugepaged_exit",
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:mem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510284,
      "name": "__mmdrop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579492864,
      "name": "__mmdrop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
