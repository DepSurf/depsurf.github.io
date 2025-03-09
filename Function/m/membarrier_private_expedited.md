# Function: <code>membarrier_private_expedited</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579745906,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:38",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:SyS_membarrier"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579779760,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:110",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779760,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822320,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:110",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822320,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850544,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:101",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850544,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898864,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898864,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941920,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941920,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930016,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:309",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930016,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938096,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:309",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938096,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063040,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:310",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063040,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162016,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:309",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162016,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580344784,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:309",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344784,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411888,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:310",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411888,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
int membarrier_private_expedited(int flags, int cpu_id)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469040,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:314",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:__do_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469040,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491097720,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:__arm64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491097720,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225101424,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225101424,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283986928,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283986928,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271680072,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271680072,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870976,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870976,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805920,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805920,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859136,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859136,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int membarrier_private_expedited(int flags)
```

```json
{
  "name": "membarrier_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904448,
      "name": "membarrier_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:132",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904448,
      "name": "membarrier_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int membarrier_private_expedited(int flags)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_id</code>
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
