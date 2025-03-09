# Function: <code>sugov_get_util</code>

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
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717030,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:154",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713318,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:157",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579745247,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:179",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775728,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:182",
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
      "addr": 18446744071579775728,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820944,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:274",
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
      "addr": 18446744071579820944,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849040,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:289",
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
      "addr": 18446744071579849040,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897296,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 18446744071579897296,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940320,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940320,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927712,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:280",
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
      "addr": 18446744071579927712,
      "name": "sugov_get_util",
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933776,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:163",
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
      "addr": 18446744071579933776,
      "name": "sugov_get_util",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057616,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:164",
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
      "addr": 18446744071580057616,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580159696,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:157",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580159696,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336336,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:157",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580336336,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383680,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:156",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580383680,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void sugov_get_util(struct sugov_cpu * sg_cpu, long unsigned int boost)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440272,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:198",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071580440272,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491095688,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491095688,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225099200,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 3225099200,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283984848,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283984848,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869408,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 18446744071579869408,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804352,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 18446744071579804352,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857568,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 18446744071579857568,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
```

```json
{
  "name": "sugov_get_util",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902848,
      "name": "sugov_get_util",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:292",
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
      "addr": 18446744071579902848,
      "name": "sugov_get_util",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void sugov_get_util(struct sugov_cpu * sg_cpu)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int boost</code>
</li>
</ul>
</details>
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
long unsigned int sugov_get_util(struct sugov_cpu * sg_cpu)
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
