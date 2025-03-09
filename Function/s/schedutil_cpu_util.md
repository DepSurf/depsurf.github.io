# Function: <code>schedutil_cpu_util</code>

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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848784,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:203",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848784,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897040,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897040,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939936,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939936,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927328,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:194",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927328,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491095384,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491095384,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225098944,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225098944,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283984336,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util",
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283984336,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "schedutil_cpu_util",
      "external": false,
      "loc": "kernel/sched/sched.h:2416",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869152,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869152,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804096,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804096,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857408,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857408,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```

```json
{
  "name": "schedutil_cpu_util",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902592,
      "name": "schedutil_cpu_util",
      "external": true,
      "loc": "kernel/sched/cpufreq_schedutil.c:206",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_get_util"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902592,
      "name": "schedutil_cpu_util",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
```
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
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct * p)
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
