# Function: <code>ptrace_unfreeze_traced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415744,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:140",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:SyS_ptrace",
        "kernel/ptrace.c:compat_SyS_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:SyS_ptrace",
        "kernel/ptrace.c:compat_SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415744,
      "name": "ptrace_unfreeze_traced.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432750,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:139",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427248,
      "name": "ptrace_unfreeze_traced.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579453102,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:177",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446656,
      "name": "ptrace_unfreeze_traced.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579441032,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:186",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435376,
      "name": "ptrace_unfreeze_traced.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579469336,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:186",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463648,
      "name": "ptrace_unfreeze_traced.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476992,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:186",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476992,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579510544,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:186",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510544,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532456,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530160,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071579536377,
      "name": "ptrace_unfreeze_traced.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558600,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556304,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590746,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587568,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579570762,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567600,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575676,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:208",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573104,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650124,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:208",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647296,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740544,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:213",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740544,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871872,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:213",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871872,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921408,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:214",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921408,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void ptrace_unfreeze_traced(struct task_struct * task)
```

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960656,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:203",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960656,
      "name": "ptrace_unfreeze_traced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490714296,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490708384,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224774492,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283538536,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283534608,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271435128,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579534904,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532608,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579463688,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461392,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532184,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529888,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_unfreeze_traced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565256,
      "name": "ptrace_unfreeze_traced",
      "external": false,
      "loc": "kernel/ptrace.c:191",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561328,
      "name": "ptrace_unfreeze_traced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void ptrace_unfreeze_traced(struct task_struct * task)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void ptrace_unfreeze_traced(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ptrace_unfreeze_traced(struct task_struct * task)
```
</details>
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
