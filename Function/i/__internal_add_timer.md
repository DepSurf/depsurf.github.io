# Function: <code>__internal_add_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __internal_add_timer(struct tvec_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810048,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:374",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:cascade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810048,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838320,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:523",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838320,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867376,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:523",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867376,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876896,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:526",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876896,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920144,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:526",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920144,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966816,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:543",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966816,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013472,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:542",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013472,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058304,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:544",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058304,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107360,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107360,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580179727,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer"
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491328432,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491328432,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225319192,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225319192,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284245424,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:add_timer",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284245424,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279807922,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076560,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076560,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021376,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021376,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067632,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067632,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
```

```json
{
  "name": "__internal_add_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122400,
      "name": "__internal_add_timer",
      "external": false,
      "loc": "kernel/time/timer.c:548",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122400,
      "name": "__internal_add_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tvec_base * base</code> ➡️ <code>struct timer_base * base</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __internal_add_timer(struct timer_base * base, struct timer_list * timer)
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
