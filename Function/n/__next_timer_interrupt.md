# Function: <code>__next_timer_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579821788,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1269",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:get_next_timer_interrupt"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842592,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1393",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842592,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872112,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1403",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872112,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881296,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1375",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881296,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924560,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1410",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924560,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971072,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1418",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971072,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018144,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1417",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018144,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062384,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1421",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062384,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111440,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111440,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580171888,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1518",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171888,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157152,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1518",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157152,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161792,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1536",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161792,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306368,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1522",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306368,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518208,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1575",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518208,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773360,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1807",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773360,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856336,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1807",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856336,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491322624,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491322624,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225319812,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225319812,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284253152,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284253152,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271827164,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271827164,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080640,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080640,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025456,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025456,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071712,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071712,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
```

```json
{
  "name": "__next_timer_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122528,
      "name": "__next_timer_interrupt",
      "external": false,
      "loc": "kernel/time/timer.c:1506",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:get_next_timer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122528,
      "name": "__next_timer_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
long unsigned int __next_timer_interrupt(struct timer_base * base)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
long unsigned int __next_timer_interrupt(struct timer_base * base)
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
