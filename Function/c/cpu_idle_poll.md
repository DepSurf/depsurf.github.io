# Function: <code>cpu_idle_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579647513,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
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
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579663128,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:56",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101504,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:59",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101504,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327136,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:61",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327136,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893264,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:61",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893264,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589271472,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:54",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271472,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589514320,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:54",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589514320,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589973440,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589973440,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590200848,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200848,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591216768,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591216768,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591711280,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591711280,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591658672,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658672,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592832352,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592832352,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594741792,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:52",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741792,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596494112,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:52",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596494112,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596945840,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:52",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596945840,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597873344,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:52",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597873344,
      "name": "cpu_idle_poll.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503947616,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503947616,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236556152,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236556152,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297800720,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297800720,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279810536,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279810536,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803136,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803136,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589525520,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589525520,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590246544,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246544,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int cpu_idle_poll()
```

```json
{
  "name": "cpu_idle_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590297696,
      "name": "cpu_idle_poll",
      "external": false,
      "loc": "kernel/sched/idle.c:55",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590297696,
      "name": "cpu_idle_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int cpu_idle_poll()
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cpu_idle_poll()
```
</details>
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
