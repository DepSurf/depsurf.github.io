# Function: <code>x86_gsbase_write_cpu_inactive</code>

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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579032928,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040479,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042879,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053171,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054432,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:423",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054432,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061248,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:423",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061248,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579082528,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:447",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082528,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110128,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:447",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110128,
      "name": "x86_gsbase_write_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579111136,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579147808,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:447",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147808,
      "name": "x86_gsbase_write_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071579149776,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579149376,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:448",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149376,
      "name": "x86_gsbase_write_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071579151888,
      "name": "x86_gsbase_write_cpu_inactive",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
```

```json
{
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579178656,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": true,
      "loc": "arch/x86/kernel/process_64.c:448",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178656,
      "name": "x86_gsbase_write_cpu_inactive.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071579181184,
      "name": "x86_gsbase_write_cpu_inactive",
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579043231,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578976287,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042815,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
  "name": "x86_gsbase_write_cpu_inactive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046552,
      "name": "x86_gsbase_write_cpu_inactive",
      "external": false,
      "loc": "arch/x86/include/asm/fsgsbase.h:47",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
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
void x86_gsbase_write_cpu_inactive(long unsigned int gsbase)
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
