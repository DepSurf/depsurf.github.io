# Function: <code>sched_attr_copy_to_user</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678480,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5118",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678480,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711808,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711808,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752784,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5542",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752784,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740256,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:6361",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740256,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746096,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:6662",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746096,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824288,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:7838",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824288,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942656,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:7946",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942656,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088736,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:8088",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088736,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144656,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:8197",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144656,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190080,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:8234",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190080,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490897464,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__arm64_sys_sched_getattr"
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
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224946704,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
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
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283726856,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
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
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271564050,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_getattr"
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687984,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687984,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616448,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616448,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685024,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685024,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```

```json
{
  "name": "sched_attr_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720240,
      "name": "sched_attr_copy_to_user",
      "external": false,
      "loc": "kernel/sched/core.c:5309",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720240,
      "name": "sched_attr_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```
</details>
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
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sched_attr_copy_to_user(struct sched_attr * uattr, struct sched_attr * kattr, unsigned int usize)
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
