# Function: <code>cpufreq_driver_fast_switch</code>

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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251072,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1849",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251072,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586455840,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1821",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455840,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586580368,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1824",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580368,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063648,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1857",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063648,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361872,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1856",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361872,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541744,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:1857",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541744,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587816304,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2007",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816304,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021504,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021504,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588881552,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2058",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881552,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588901936,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2074",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588901936,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588790704,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2080",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588790704,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589483568,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2086",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589483568,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590964736,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2118",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590964736,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592666736,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2115",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592666736,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593096736,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2122",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593096736,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593849504,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2163",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849504,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501284616,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501284616,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233775056,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233775056,
      "name": "cpufreq_driver_fast_switch",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294810480,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294810480,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646496,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646496,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420368,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420368,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977648,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977648,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
```

```json
{
  "name": "cpufreq_driver_fast_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093024,
      "name": "cpufreq_driver_fast_switch",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2021",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093024,
      "name": "cpufreq_driver_fast_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy * policy, unsigned int target_freq)
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
