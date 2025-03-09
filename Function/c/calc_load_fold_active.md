# Function: <code>calc_load_fold_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569472,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:81",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_enter_idle",
        "kernel/sched/loadavg.c:calc_global_load_tick"
      ],
      "caller_func": [
        "kernel/sched/core.c:migration_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569472,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581420,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:81",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_enter_idle"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580576,
      "name": "calc_load_fold_active",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579607596,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:81",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_enter_idle"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606752,
      "name": "calc_load_fold_active",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585148,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:82",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584320,
      "name": "calc_load_fold_active",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579614536,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:83",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613712,
      "name": "calc_load_fold_active",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579644952,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644128,
      "name": "calc_load_fold_active",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579682504,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681568,
      "name": "calc_load_fold_active",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579716348,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715424,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758780,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757920,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792284,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791232,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579783132,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782080,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579791244,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790208,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886940,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885904,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580191512,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:78",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189296,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580382024,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:78",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379680,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580450712,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:78",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580448352,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580510024,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:78",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_global_load_tick",
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507680,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490937364,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490936320,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224955724,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224954816,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283793320,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283792256,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271570044,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271568946,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579734700,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733840,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663532,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662672,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719148,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718288,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int calc_load_fold_active(struct rq * this_rq, long int adjust)
```

```json
{
  "name": "calc_load_fold_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579766428,
      "name": "calc_load_fold_active",
      "external": true,
      "loc": "kernel/sched/loadavg.c:79",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765568,
      "name": "calc_load_fold_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int adjust</code>
</li>
</ul>
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
