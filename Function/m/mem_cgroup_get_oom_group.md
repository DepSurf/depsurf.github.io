# Function: <code>mem_cgroup_get_oom_group</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572800,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:1812",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572800,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684096,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2013",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684096,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756528,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756528,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975568,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:1895",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975568,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025248,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2084",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025248,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051744,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:1907",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051744,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:1959",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225474,
      "name": "mem_cgroup_get_oom_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582358544,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:1968",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004543,
      "name": "mem_cgroup_get_oom_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582850176,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2028",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596048839,
      "name": "mem_cgroup_get_oom_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583396608,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2048",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571313,
      "name": "mem_cgroup_get_oom_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583615840,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2120",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475802,
      "name": "mem_cgroup_get_oom_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583810720,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493210064,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493210064,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226840348,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226840348,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286719552,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286719552,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272986786,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272986786,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725264,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725264,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664064,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664064,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716576,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716576,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```

```json
{
  "name": "mem_cgroup_get_oom_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784160,
      "name": "mem_cgroup_get_oom_group",
      "external": true,
      "loc": "mm/memcontrol.c:2029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784160,
      "name": "mem_cgroup_get_oom_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct mem_cgroup * mem_cgroup_get_oom_group(struct task_struct * victim, struct mem_cgroup * oom_domain)
```
</details>
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
