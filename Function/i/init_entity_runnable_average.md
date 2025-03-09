# Function: <code>init_entity_runnable_average</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579607824,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:672",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607824,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641035,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:672",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620864,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665532,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:731",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642848,
      "name": "init_entity_runnable_average",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640156,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:728",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621488,
      "name": "init_entity_runnable_average",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653488,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:717",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653488,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684256,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:702",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684256,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719520,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:698",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719520,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754976,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754976,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797696,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797696,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579840624,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:743",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840624,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579832976,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:741",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832976,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579841920,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:738",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841920,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579946464,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:724",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946464,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059968,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:787",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059968,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229664,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:800",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229664,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293376,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:800",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293376,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345008,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:1012",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345008,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490977120,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490977120,
      "name": "init_entity_runnable_average",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224989348,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224989348,
      "name": "init_entity_runnable_average",
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283843312,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283843312,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271593764,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271593764,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773552,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773552,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579704192,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579704192,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758064,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758064,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void init_entity_runnable_average(struct sched_entity * se)
```

```json
{
  "name": "init_entity_runnable_average",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805968,
      "name": "init_entity_runnable_average",
      "external": true,
      "loc": "kernel/sched/fair.c:732",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/fair.c:alloc_fair_sched_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805968,
      "name": "init_entity_runnable_average",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
