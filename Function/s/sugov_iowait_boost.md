# Function: <code>sugov_iowait_boost</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717279,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:179",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713711,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:182",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, long unsigned int * util, long unsigned int * max)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743616,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:217",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743616,
      "name": "sugov_iowait_boost",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579776944,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:251",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776944,
      "name": "sugov_iowait_boost",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819568,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:326",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819568,
      "name": "sugov_iowait_boost",
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846480,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:341",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846480,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894800,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894800,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937456,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937456,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924928,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:331",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924928,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933328,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:214",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933328,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580059438,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:215",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059376,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071592120984,
      "name": "sugov_iowait_boost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150188,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:208",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150112,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071593880696,
      "name": "sugov_iowait_boost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580323708,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:207",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323632,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071595981907,
      "name": "sugov_iowait_boost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580391148,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391072,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071596500083,
      "name": "sugov_iowait_boost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580447276,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:248",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447200,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071597397445,
      "name": "sugov_iowait_boost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491092760,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491092760,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225096528,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225096528,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283980864,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283980864,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866912,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866912,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801856,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801856,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855168,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855168,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
```

```json
{
  "name": "sugov_iowait_boost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900320,
      "name": "sugov_iowait_boost",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:344",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900320,
      "name": "sugov_iowait_boost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, long unsigned int * util, long unsigned int * max)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 time</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * util</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * max</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sugov_iowait_boost(struct sugov_cpu * sg_cpu, u64 time, unsigned int flags)
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
