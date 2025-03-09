# Function: <code>can_nice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526800,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3504",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526800,
      "name": "can_nice.part.85",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579555728,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579551092,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3757",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543120,
      "name": "can_nice.part.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579566400,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575954,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3794",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567936,
      "name": "can_nice.part.87",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579591376,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560407,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3800",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552656,
      "name": "can_nice.part.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579575632,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579589678,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3844",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581488,
      "name": "can_nice.part.78",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579605328,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621558,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3954",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610528,
      "name": "can_nice.part.74",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579636752,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658897,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:3938",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648176,
      "name": "can_nice.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579648208,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579684409,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4357",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672192,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579672224,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579723839,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709584,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579709616,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765864,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4792",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750432,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754691,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:5565",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736256,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761688,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:5776",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742960,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848111,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:6939",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825088,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962195,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:7035",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937040,
      "name": "can_nice",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121779,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:7176",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087856,
      "name": "can_nice",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183587,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:7277",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143792,
      "name": "can_nice",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230515,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:7327",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189216,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490906272,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__arm64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__arm64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490890280,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336490890320,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224920180,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__se_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__se_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224906172,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3224906204,
      "name": "can_nice",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283746324,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__se_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__se_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283729328,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283729392,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271546684,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271539676,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446743936271539714,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579700787,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685808,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579685840,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627525,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614224,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579614256,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692918,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682960,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579682992,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int can_nice(const struct task_struct * p, const int nice)
```

```json
{
  "name": "can_nice",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729572,
      "name": "can_nice",
      "external": true,
      "loc": "kernel/sched/core.c:4559",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice"
      ],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718176,
      "name": "can_nice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579718208,
      "name": "can_nice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
