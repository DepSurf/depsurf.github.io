# Function: <code>sugov_iowait_apply</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time, long unsigned int * util, long unsigned int * max)
```

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777056,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:301",
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
      "addr": 18446744071579777056,
      "name": "sugov_iowait_apply",
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
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time, long unsigned int * util, long unsigned int * max)
```

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579820512,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:376",
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
      "addr": 18446744071579820512,
      "name": "sugov_iowait_apply",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579849967,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:390",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579898279,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579940602,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time)
```

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926560,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:378",
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
      "addr": 18446744071579926560,
      "name": "sugov_iowait_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time)
```

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579935072,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:261",
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
      "addr": 18446744071579935072,
      "name": "sugov_iowait_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580061589,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:262",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059504,
      "name": "sugov_iowait_apply.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071592121005,
      "name": "sugov_iowait_apply.part.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580178241,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:255",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150272,
      "name": "sugov_iowait_apply.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071593880717,
      "name": "sugov_iowait_apply.part.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580362948,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:254",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323808,
      "name": "sugov_iowait_apply.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071595981928,
      "name": "sugov_iowait_apply.part.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580432726,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:254",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_perf",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391280,
      "name": "sugov_iowait_apply.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071596500104,
      "name": "sugov_iowait_apply.part.0.constprop.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:296",
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
      "addr": 18446744071580447408,
      "name": "sugov_iowait_apply.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071597397466,
      "name": "sugov_iowait_apply.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491096840,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225100420,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283986156,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870391,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579805335,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579858551,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sugov_iowait_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903831,
      "name": "sugov_iowait_apply",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:393",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time, long unsigned int * util, long unsigned int * max)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time, long unsigned int * util, long unsigned int * max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void sugov_iowait_apply(struct sugov_cpu * sg_cpu, u64 time)
```
</details>
</li>
</ul>
