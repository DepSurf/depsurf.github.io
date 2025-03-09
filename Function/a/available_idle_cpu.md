# Function: <code>available_idle_cpu</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636928,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4041",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636928,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674608,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4026",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674608,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706528,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4445",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706528,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748624,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748624,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784336,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4880",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_smt",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784336,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774784,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:5653",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_smt",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774784,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782672,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:5868",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782672,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876624,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876624,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992496,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7123",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992496,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153888,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7264",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153888,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204400,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7365",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204400,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252960,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7415",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine",
        "kernel/sched/fair.c:wake_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252960,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490927216,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490927216,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224945040,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224945040,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283780224,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283780224,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271562746,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271562746,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724576,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724576,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653136,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653136,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711328,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711328,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
```

```json
{
  "name": "available_idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756256,
      "name": "available_idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4647",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756256,
      "name": "available_idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int available_idle_cpu(int cpu)
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
