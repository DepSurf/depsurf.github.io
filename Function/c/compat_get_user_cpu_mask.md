# Function: <code>compat_get_user_cpu_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579965416,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:602",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_sched_setaffinity"
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
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995960,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:602",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_sched_setaffinity"
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
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580026490,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:610",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_sched_setaffinity"
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
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580028788,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:331",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_sched_setaffinity"
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
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580075492,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:308",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_sched_setaffinity"
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134800,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:265",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134800,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182032,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:265",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182032,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227424,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227424,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275632,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275632,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343792,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343792,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328944,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328944,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332128,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332128,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486752,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x64_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486752,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580681527,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580952860,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039836,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581137052,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:110",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491522064,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__arm64_compat_sys_sched_setaffinity"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284486920,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__do_compat_sys_sched_setaffinity"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244432,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244432,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191984,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191984,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235680,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235680,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```

```json
{
  "name": "compat_get_user_cpu_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288672,
      "name": "compat_get_user_cpu_mask",
      "external": false,
      "loc": "kernel/compat.c:198",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288672,
      "name": "compat_get_user_cpu_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t * user_mask_ptr, unsigned int len, struct cpumask * new_mask)
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
