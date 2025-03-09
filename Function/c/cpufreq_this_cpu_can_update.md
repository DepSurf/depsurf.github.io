# Function: <code>cpufreq_this_cpu_can_update</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579775654,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:574",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389229,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:574",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579818457,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:566",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587569165,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:566",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579846949,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:595",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587844956,
      "name": "cpufreq_this_cpu_can_update",
      "external": false,
      "loc": "include/linux/cpufreq.h:595",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894720,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894720,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937376,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937376,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924848,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924848,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933248,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933248,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592120823,
      "name": "cpufreq_this_cpu_can_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580057424,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:69",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593886094,
      "name": "cpufreq_this_cpu_can_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580177776,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:69",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595982644,
      "name": "cpufreq_this_cpu_can_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580362464,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:69",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501031,
      "name": "cpufreq_this_cpu_can_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580432272,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:69",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597398637,
      "name": "cpufreq_this_cpu_can_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580491472,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491092640,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491092640,
      "name": "cpufreq_this_cpu_can_update",
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225096408,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225096408,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283980752,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283980752,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866832,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866832,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801776,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801776,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855088,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855088,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_this_cpu_can_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900240,
      "name": "cpufreq_this_cpu_can_update",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:72",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900240,
      "name": "cpufreq_this_cpu_can_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
```
</details>
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy * policy)
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
