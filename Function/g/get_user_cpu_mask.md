# Function: <code>get_user_cpu_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557849,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4488",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568631,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4738",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579593705,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4775",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579577911,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4672",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579607607,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4716",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617360,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4851",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617360,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645648,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:4836",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645648,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678368,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5289",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678368,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711696,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711696,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753600,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5713",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753600,
      "name": "get_user_cpu_mask",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738720,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:6537",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738720,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747152,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:6838",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747152,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824528,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:8031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824528,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937600,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:8139",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937600,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098864,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:8323",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098864,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156832,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:8432",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156832,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202064,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:8443",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202064,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490928008,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__arm64_sys_sched_setaffinity"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224947496,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_setaffinity"
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
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283781228,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__do_sys_sched_setaffinity"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271564604,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_setaffinity"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687872,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687872,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616336,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616336,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684912,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684912,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720128,
      "name": "get_user_cpu_mask",
      "external": false,
      "loc": "kernel/sched/core.c:5480",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720128,
      "name": "get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
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
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_user_cpu_mask(long unsigned int * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
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
