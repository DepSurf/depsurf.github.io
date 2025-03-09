# Function: <code>switch_mm_irqs_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313168,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:74",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313168,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328384,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:74",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328384,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 714
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322000,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:63",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322000,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345856,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:183",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345856,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1017
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357536,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:183",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357536,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384656,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:274",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384656,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400192,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400192,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1322
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403504,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403504,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413648,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:451",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413648,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414048,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:422",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414048,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416864,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:428",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416864,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479792,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:488",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479792,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1338
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558720,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:489",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558720,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665968,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:489",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665968,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679728,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:494",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679728,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1561
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714176,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:495",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/kthread.c:kthread_use_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714176,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1561
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282729152,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/powerpc/mm/mmu_context.c:34",
      "file": "arch/powerpc/mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282729152,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399408,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399408,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328864,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:leave_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328864,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399328,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399328,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1274
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```

```json
{
  "name": "switch_mm_irqs_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407824,
      "name": "switch_mm_irqs_off",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:275",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/tlb.c:switch_mm",
        "kernel/sched/core.c:__schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407824,
      "name": "switch_mm_irqs_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1403
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
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
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void switch_mm_irqs_off(struct mm_struct * prev, struct mm_struct * next, struct task_struct * tsk)
```
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
