# Function: <code>getreg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090720,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:454",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090720,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090176,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:421",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090176,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579089360,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:421",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089360,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081248,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:422",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081248,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092000,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:422",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092000,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579097376,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:422",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097376,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579103088,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:423",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579103088,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579112800,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112800,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114720,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114720,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127888,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:409",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127888,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126448,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:388",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126448,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134608,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:388",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134608,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160192,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:388",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:x32_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160192,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205648,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:387",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205648,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579261088,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:406",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261088,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267136,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:406",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267136,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296960,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:407",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296960,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579115104,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115104,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047200,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047200,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114656,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114656,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```

```json
{
  "name": "getreg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119744,
      "name": "getreg",
      "external": false,
      "loc": "arch/x86/kernel/ptrace.c:397",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ptrace.c:compat_arch_ptrace",
        "arch/x86/kernel/ptrace.c:arch_ptrace",
        "arch/x86/kernel/ptrace.c:genregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119744,
      "name": "getreg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int getreg(struct task_struct * task, long unsigned int offset)
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
