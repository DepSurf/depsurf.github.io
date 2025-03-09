# Function: <code>cpufreq_add_update_util_hook</code>

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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, long unsigned int, long unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689792,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:34",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689792,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714400,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:34",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714400,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710704,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:34",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710704,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742400,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:34",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742400,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775488,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:33",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775488,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818288,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:30",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818288,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:30",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846441,
      "name": "cpufreq_add_update_util_hook.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579846368,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894640,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894640,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937296,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937296,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924768,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924768,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933168,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933168,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057264,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057264,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140096,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:29",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140096,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315280,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:29",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315280,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381792,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:29",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381792,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438992,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:29",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438992,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491092496,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491092496,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225096260,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225096260,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283980624,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283980624,
      "name": "cpufreq_add_update_util_hook",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866752,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866752,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801696,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801696,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855008,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855008,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
```

```json
{
  "name": "cpufreq_add_update_util_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900160,
      "name": "cpufreq_add_update_util_hook",
      "external": true,
      "loc": "kernel/sched/cpufreq.c:32",
      "file": "kernel/sched/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900160,
      "name": "cpufreq_add_update_util_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, long unsigned int, long unsigned int) func)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*)(struct update_util_data *, u64, long unsigned int, long unsigned int) func</code> ➡️ <code>void (*)(struct update_util_data *, u64, unsigned int) func</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data * data, void (*)(struct update_util_data *, u64, unsigned int) func)
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
