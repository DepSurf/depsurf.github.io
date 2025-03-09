# Function: <code>housekeeping_any_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": false,
      "loc": "include/linux/tick.h:160",
      "file": "kernel/sched/core.c",
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
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": false,
      "loc": "include/linux/tick.h:239",
      "file": "kernel/sched/core.c",
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
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": false,
      "loc": "include/linux/tick.h:237",
      "file": "kernel/sched/core.c",
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
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": false,
      "loc": "include/linux/tick.h:238",
      "file": "kernel/sched/core.c",
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
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746320,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:21",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746320,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780688,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:16",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780688,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823568,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:16",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823568,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851776,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851776,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900272,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900272,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943424,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943424,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931680,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931680,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939520,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939520,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064544,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064544,
      "name": "housekeeping_any_cpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int housekeeping_any_cpu(enum hk_type type)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:39",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593891015,
      "name": "housekeeping_any_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580200016,
      "name": "housekeeping_any_cpu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int housekeeping_any_cpu(enum hk_type type)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:39",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983218,
      "name": "housekeeping_any_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580390912,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int housekeeping_any_cpu(enum hk_type type)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459570,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:39",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501588,
      "name": "housekeeping_any_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580459504,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int housekeeping_any_cpu(enum hk_type type)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580519218,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:39",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399274,
      "name": "housekeeping_any_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580519152,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491099624,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099624,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225102808,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225102808,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283989696,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989696,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271681636,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271681636,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872384,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872384,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807392,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807392,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860544,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860544,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_any_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905920,
      "name": "housekeeping_any_cpu",
      "external": true,
      "loc": "kernel/sched/isolation.c:23",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/sched/core.c:get_nohz_timer_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905920,
      "name": "housekeeping_any_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int housekeeping_any_cpu(enum hk_flags flags)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
