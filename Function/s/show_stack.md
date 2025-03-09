# Function: <code>show_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049984,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:183",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_show_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049984,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046176,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:191",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_show_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046176,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579045248,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:163",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_show_task",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045248,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037856,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:165",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037856,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046048,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:225",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046048,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050674,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:291",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050674,
      "name": "show_stack",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579055479,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055479,
      "name": "show_stack",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062000,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062000,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064096,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064096,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073785,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:289",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073785,
      "name": "show_stack",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591246014,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246014,
      "name": "show_stack",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591189808,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591189808,
      "name": "show_stack",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592053370,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592053370,
      "name": "show_stack",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593820183,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:300",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593820183,
      "name": "show_stack",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179824,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179824,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183216,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:309",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183216,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void show_stack(struct task_struct * task, long unsigned int * sp, const char * loglvl)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212432,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:309",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212432,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void show_stack(struct task_struct * tsk, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490240224,
      "name": "show_stack",
      "external": true,
      "loc": "arch/arm64/kernel/traps.c:138",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490240224,
      "name": "show_stack",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void show_stack(struct task_struct * tsk, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224437288,
      "name": "show_stack",
      "external": true,
      "loc": "arch/arm/kernel/traps.c:243",
      "file": "arch/arm/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224437288,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void show_stack(struct task_struct * tsk, long unsigned int * stack)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282305664,
      "name": "show_stack",
      "external": true,
      "loc": "arch/powerpc/kernel/process.c:2031",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/process.c:show_regs",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282305664,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271348732,
      "name": "show_stack",
      "external": true,
      "loc": "arch/riscv/kernel/stacktrace.c:105",
      "file": "arch/riscv/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271348732,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064448,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064448,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997200,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997200,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064032,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064032,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void show_stack(struct task_struct * task, long unsigned int * sp)
```

```json
{
  "name": "show_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068096,
      "name": "show_stack",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:282",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack",
        "lib/dump_stack.c:dump_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068096,
      "name": "show_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<b>Param added. </b>
<code>const char * loglvl</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int * stack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * sp</code>
</li>
</ul>
</details>
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
