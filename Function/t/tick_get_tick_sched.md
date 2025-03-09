# Function: <code>tick_get_tick_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888192,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:44",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888192,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917792,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:38",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917792,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948320,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:38",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948320,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956192,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:42",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956192,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002181,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:43",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001952,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054917,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:43",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053712,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101749,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100544,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580145685,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144432,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580193717,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192464,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580259061,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258272,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580242645,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241856,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247621,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246832,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580398405,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397536,
      "name": "tick_get_tick_sched",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580617125,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616208,
      "name": "tick_get_tick_sched",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580882245,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881168,
      "name": "tick_get_tick_sched",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580966213,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965120,
      "name": "tick_get_tick_sched",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060949,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:41",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058240,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491424000,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491422536,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225417840,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225416136,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284371808,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284369952,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271891180,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271889792,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580162517,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161264,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110149,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108448,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153989,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152736,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct tick_sched * tick_get_tick_sched(int cpu)
```

```json
{
  "name": "tick_get_tick_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206005,
      "name": "tick_get_tick_sched",
      "external": true,
      "loc": "kernel/time/tick-sched.c:40",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls_cpu"
      ],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204720,
      "name": "tick_get_tick_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
