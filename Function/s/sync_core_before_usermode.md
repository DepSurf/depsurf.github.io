# Function: <code>sync_core_before_usermode</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579612736,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579651039,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579674579,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712890,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579758867,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724544,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579929291,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724544,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579731920,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579937195,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731920,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579811936,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580062011,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811936,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579919632,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580139659,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919632,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580074448,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580314795,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074448,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580127952,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580381467,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127952,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core_before_usermode()
```

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580172496,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580438667,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:96",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172496,
      "name": "sync_core_before_usermode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "include/linux/sync_core.h:15",
      "file": "kernel/sched/core.c",
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
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "include/linux/sync_core.h:15",
      "file": "kernel/sched/core.c",
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
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "include/linux/sync_core.h:15",
      "file": "kernel/sched/core.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "include/linux/sync_core.h:15",
      "file": "kernel/sched/core.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579689066,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579617586,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579686042,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core_before_usermode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579715556,
      "name": "sync_core_before_usermode",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:14",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void sync_core_before_usermode()
```
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
