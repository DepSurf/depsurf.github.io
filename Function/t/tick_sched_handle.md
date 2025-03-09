# Function: <code>tick_sched_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886736,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:134",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886736,
      "name": "tick_sched_handle.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579916320,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:134",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916320,
      "name": "tick_sched_handle.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579946976,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:134",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946976,
      "name": "tick_sched_handle.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954448,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:138",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954448,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000096,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:139",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000096,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052592,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:141",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052592,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099408,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:138",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099408,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142768,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:144",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142768,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191312,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191312,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255888,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:153",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255888,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239536,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:203",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239536,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244784,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:203",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244784,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395424,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:203",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395424,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613792,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:220",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613792,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878544,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:220",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878544,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962544,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:231",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962544,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054400,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:232",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_highres_handler",
        "kernel/time/tick-sched.c:tick_nohz_lowres_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054400,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491420384,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491420384,
      "name": "tick_sched_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225413772,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225413772,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284368016,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284368016,
      "name": "tick_sched_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271888454,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271888454,
      "name": "tick_sched_handle.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160112,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160112,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106256,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106256,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151584,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151584,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```

```json
{
  "name": "tick_sched_handle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580203664,
      "name": "tick_sched_handle",
      "external": false,
      "loc": "kernel/time/tick-sched.c:148",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203664,
      "name": "tick_sched_handle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tick_sched_handle(struct tick_sched * ts, struct pt_regs * regs)
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
