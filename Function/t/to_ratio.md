# Function: <code>to_ratio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520006,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2266",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__setscheduler_params",
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552944,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579534287,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2445",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563760,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558575,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2455",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:sched_rt_handler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588656,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544802,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2406",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572880,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572731,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2425",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602528,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579601579,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2401",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633984,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579638728,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2390",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671728,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579668456,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2801",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703632,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579705528,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744528,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746280,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:3081",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781072,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579731960,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:3796",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771616,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738459,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:3817",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779312,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579818651,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:4429",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872768,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579928475,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:4607",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988496,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079947,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:4746",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149520,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580134283,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:4824",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580201504,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580178959,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:4845",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:__setparam_dl",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_do_global",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:init_dl_rq_bw_ratio",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249680,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490886664,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490923560,
      "name": "to_ratio",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224909580,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224940272,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283724844,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283774480,
      "name": "to_ratio",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271537426,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271559364,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579681848,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721120,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605496,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649040,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579679064,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/rt.c:tg_rt_schedulable",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708336,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long unsigned int to_ratio(u64 period, u64 runtime)
```

```json
{
  "name": "to_ratio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713208,
      "name": "to_ratio",
      "external": true,
      "loc": "kernel/sched/core.c:2921",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_cfs_schedulable_down"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:__setparam_dl",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:init_dl_rq_bw_ratio",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:init_dl_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752080,
      "name": "to_ratio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
