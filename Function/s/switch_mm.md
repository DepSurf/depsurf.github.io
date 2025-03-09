# Function: <code>switch_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "switch_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587363864,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:107",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:idle_task_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613697,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:107",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022062,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:107",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313824,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:64",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313824,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329104,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:64",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329104,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322464,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:53",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322464,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346880,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:145",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:enter_lazy_tlb",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346880,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358576,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:145",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:enter_lazy_tlb",
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_switch_mm",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358576,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386016,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:153",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386016,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401520,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401520,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404784,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404784,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415269,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:310",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:leave_mm"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414560,
      "name": "switch_mm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415461,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:309",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:leave_mm"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414816,
      "name": "switch_mm",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579418405,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:310",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:leave_mm"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417824,
      "name": "switch_mm",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579481829,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:317",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:leave_mm"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481136,
      "name": "switch_mm",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560160,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:318",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560160,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667424,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:318",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667424,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681312,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:323",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681312,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715760,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:324",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_teardown",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup",
        "kernel/sched/core.c:idle_task_exit",
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715760,
      "name": "switch_mm",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "switch_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490930368,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:230",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492646292,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:230",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493362420,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:230",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "switch_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224949404,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm/include/asm/mmu_context.h:128",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 3226486992,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm/include/asm/mmu_context.h:128",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226948160,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/arm/include/asm/mmu_context.h:128",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "switch_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282779408,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/powerpc/include/asm/mmu_context.h:199",
      "file": "arch/powerpc/mm/book3s64/radix_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283785300,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/powerpc/include/asm/mmu_context.h:199",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:idle_task_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285962684,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/powerpc/include/asm/mmu_context.h:199",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286906060,
      "name": "switch_mm",
      "external": false,
      "loc": "arch/powerpc/include/asm/mmu_context.h:199",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * task)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271360320,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/riscv/mm/context.c:43",
      "file": "arch/riscv/mm/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271360320,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400688,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400688,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579330213,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:leave_mm"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330144,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400608,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400608,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409232,
      "name": "switch_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:154",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "kernel/sched/core.c:idle_task_exit",
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409232,
      "name": "switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void switch_mm(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
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
