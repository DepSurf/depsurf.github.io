# Function: <code>sched_setaffinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557360,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4399",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557360,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568112,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4649",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568112,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593088,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4686",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593088,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577296,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4583",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577296,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606992,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4627",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606992,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637104,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4762",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637104,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674784,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674784,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706704,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5200",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706704,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748800,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748800,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784512,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5624",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784512,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775280,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:6448",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775280,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783888,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:6749",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783888,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878624,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:7989",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x64_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878624,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994832,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8097",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994832,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156448,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8259",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156448,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8368",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495604,
      "name": "sched_setaffinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580218752,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8397",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597392492,
      "name": "sched_setaffinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580267552,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490927464,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_setaffinity",
        "kernel/compat.c:__arm64_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490927464,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224946952,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224946952,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283780512,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_setaffinity",
        "kernel/compat.c:__do_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283780512,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271564198,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271564198,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724752,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724752,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653312,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/rcu/tree.c:rcu_bind_current_to_nocb",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653312,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711504,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711504,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int sched_setaffinity(pid_t pid, const struct cpumask * in_mask)
```

```json
{
  "name": "sched_setaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756432,
      "name": "sched_setaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756432,
      "name": "sched_setaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
