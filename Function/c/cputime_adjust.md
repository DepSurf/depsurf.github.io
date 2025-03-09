# Function: <code>cputime_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, cputime_t * ut, cputime_t * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571520,
      "name": "cputime_adjust",
      "external": false,
      "loc": "kernel/sched/cputime.c:578",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/sched/cputime.c:thread_group_cputime_adjusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571520,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, cputime_t * ut, cputime_t * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582416,
      "name": "cputime_adjust",
      "external": false,
      "loc": "kernel/sched/cputime.c:597",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582416,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, cputime_t * ut, cputime_t * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608592,
      "name": "cputime_adjust",
      "external": false,
      "loc": "kernel/sched/cputime.c:608",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608592,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586192,
      "name": "cputime_adjust",
      "external": false,
      "loc": "kernel/sched/cputime.c:588",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586192,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617056,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:594",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/stat.c:cgroup_stat_show_cputime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617056,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647472,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:590",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647472,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685040,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:590",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685040,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718816,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718816,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761248,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761248,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794864,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:586",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794864,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784269,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:540",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785888,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792381,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:540",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794016,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579888141,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:540",
      "file": "kernel/sched/cputime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889904,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088358,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:539",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:thread_group_cputime_adjusted",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129808,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580260550,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:554",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:thread_group_cputime_adjusted",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303872,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580326614,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:558",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_cputime_adjusted"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:thread_group_cputime_adjusted",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371424,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426992,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:558",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:thread_group_cputime_adjusted",
        "kernel/sched/build_policy.c:task_cputime_adjusted",
        "kernel/sched/build_utility.c:cpuacct_stats_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426992,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490939504,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490939504,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224957956,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224957956,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283795264,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283795264,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271571524,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271571524,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737168,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737168,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666128,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666128,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721616,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721616,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void cputime_adjust(struct task_cputime * curr, struct prev_cputime * prev, u64 * ut, u64 * st)
```

```json
{
  "name": "cputime_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768992,
      "name": "cputime_adjust",
      "external": true,
      "loc": "kernel/sched/cputime.c:591",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:thread_group_cputime_adjusted",
        "kernel/sched/cputime.c:task_cputime_adjusted",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768992,
      "name": "cputime_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cputime_t * ut</code> ➡️ <code>u64 * ut</code>
</li>
<li>
<b>Param type changed. </b>
<code>cputime_t * st</code> ➡️ <code>u64 * st</code>
</li>
</ul>
</details>
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
