# Function: <code>set_process_cpu_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, cputime_t * newval, cputime_t * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579844672,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1249",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844672,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, cputime_t * newval, cputime_t * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873728,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1220",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873728,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, cputime_t * newval, cputime_t * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579929408,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1216",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929408,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938080,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1187",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938080,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983568,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1186",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983568,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034800,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1202",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034800,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081616,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1200",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081616,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clock_idx, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125168,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1199",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125168,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173648,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173648,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236436,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1157",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237488,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580221188,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1323",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221968,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580226356,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1323",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227136,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580374788,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1396",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375616,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580591697,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1403",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592656,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580854001,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1403",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855056,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937761,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1461",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938848,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028725,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1461",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": [
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597415686,
      "name": "set_process_cpu_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581029920,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491395728,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491395728,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225394076,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225394076,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284338832,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284338832,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271877242,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271877242,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142848,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142848,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088352,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088352,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133920,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133920,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void set_process_cpu_timer(struct task_struct * tsk, unsigned int clkid, u64 * newval, u64 * oldval)
```

```json
{
  "name": "set_process_cpu_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185824,
      "name": "set_process_cpu_timer",
      "external": true,
      "loc": "kernel/time/posix-cpu-timers.c:1178",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu",
        "kernel/time/itimer.c:set_cpu_itimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185824,
      "name": "set_process_cpu_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cputime_t * newval</code> ➡️ <code>u64 * newval</code>
</li>
<li>
<b>Param type changed. </b>
<code>cputime_t * oldval</code> ➡️ <code>u64 * oldval</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int clkid</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int clock_idx</code>
</li>
</ul>
</details>
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
