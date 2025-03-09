# Function: <code>update_numa_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575280,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1139",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575280,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586320,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1282",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586320,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612112,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1406",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612112,
      "name": "update_numa_stats",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579592304,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1402",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592304,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621504,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1443",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621504,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579653904,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1471",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653904,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579690048,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1471",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690048,
      "name": "update_numa_stats",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722816,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1532",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722816,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765280,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765280,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811488,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1601",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811488,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804352,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1613",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804352,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804992,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1610",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804992,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901728,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1599",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901728,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012208,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1602",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012208,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182272,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1788",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182272,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238672,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1788",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238672,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
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
void update_numa_stats(struct task_numa_env * env, struct numa_stats * ns, int nid, bool find_idle)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287904,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:2029",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287904,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490944616,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490944616,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283804320,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283804320,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741136,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741136,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671520,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671520,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725648,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725648,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void update_numa_stats(struct numa_stats * ns, int nid)
```

```json
{
  "name": "update_numa_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773184,
      "name": "update_numa_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:1490",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773184,
      "name": "update_numa_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_numa_env * env</code>
</li>
<li>
<b>Param added. </b>
<code>bool find_idle</code>
</li>
<li>
<b>Param reordered. </b>
<code>ns, nid</code> ➡️ <code>env, ns, nid, find_idle</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void update_numa_stats(struct numa_stats * ns, int nid)
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
