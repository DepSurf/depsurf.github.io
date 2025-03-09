# Function: <code>__cpuusage_read</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689312,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:165",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689312,
      "name": "__cpuusage_read",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713904,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:165",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713904,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710224,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:165",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710224,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741920,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:166",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741920,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774928,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774928,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817728,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817728,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845776,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845776,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894048,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894048,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936848,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:156",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936848,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924320,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:156",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924320,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932704,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:156",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932704,
      "name": "__cpuusage_read",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580056549,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:161",
      "file": "kernel/sched/cpuacct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580161207,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:161",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:cpuusage_read",
        "kernel/sched/build_utility.c:cpuusage_sys_read",
        "kernel/sched/build_utility.c:cpuusage_user_read"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342928,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:161",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuusage_read",
        "kernel/sched/build_utility.c:cpuusage_sys_read",
        "kernel/sched/build_utility.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342928,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407440,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:161",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuusage_read",
        "kernel/sched/build_utility.c:cpuusage_sys_read",
        "kernel/sched/build_utility.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407440,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463968,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:161",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpuusage_read",
        "kernel/sched/build_utility.c:cpuusage_sys_read",
        "kernel/sched/build_utility.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463968,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491091728,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491091728,
      "name": "__cpuusage_read",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225095284,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225095284,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283979808,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283979808,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271679422,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271679422,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866160,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866160,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801104,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801104,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854416,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854416,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```

```json
{
  "name": "__cpuusage_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899504,
      "name": "__cpuusage_read",
      "external": false,
      "loc": "kernel/sched/cpuacct.c:155",
      "file": "kernel/sched/cpuacct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpuacct.c:cpuusage_read",
        "kernel/sched/cpuacct.c:cpuusage_sys_read",
        "kernel/sched/cpuacct.c:cpuusage_user_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899504,
      "name": "__cpuusage_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
u64 __cpuusage_read(struct cgroup_subsys_state * css, enum cpuacct_stat_index index)
```
</details>
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
