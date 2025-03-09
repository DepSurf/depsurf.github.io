# Function: <code>x86_gsbase_read_cpu_inactive</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579030995,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170000,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579038643,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580215894,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041043,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580264294,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053261,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333366,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054336,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:406",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054336,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061539,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:406",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061136,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579082819,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:430",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082416,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111553,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:430",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110352,
      "name": "x86_gsbase_read_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579111040,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150225,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:430",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148096,
      "name": "x86_gsbase_read_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071579149664,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152337,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:431",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149664,
      "name": "x86_gsbase_read_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071579151776,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int x86_gsbase_read_cpu_inactive()
```

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579181633,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:431",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178944,
      "name": "x86_gsbase_read_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071579181072,
      "name": "x86_gsbase_read_cpu_inactive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041395,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580233094,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578974391,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580180591,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040979,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580224566,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
  "name": "x86_gsbase_read_cpu_inactive",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579044643,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580277334,
      "name": "x86_gsbase_read_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:33",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
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
long unsigned int x86_gsbase_read_cpu_inactive()
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
