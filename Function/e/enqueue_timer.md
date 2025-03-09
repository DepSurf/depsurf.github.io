# Function: <code>enqueue_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587881272,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:514",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588098030,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:514",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579886304,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:517",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579929456,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:517",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579977151,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:534",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580024383,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:533",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058128,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:533",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058128,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107184,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107184,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580179737,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu"
      ],
      "caller_func": [
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172464,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158448,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:577",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158448,
      "name": "enqueue_timer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162752,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:578",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162752,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:578",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307632,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071592151213,
      "name": "enqueue_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:601",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519664,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071593926178,
      "name": "enqueue_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:601",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774960,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071595994357,
      "name": "enqueue_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:601",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859280,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071596512737,
      "name": "enqueue_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx, long unsigned int bucket_expiry)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:598",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:__mod_timer",
        "kernel/time/timer.c:__mod_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948192,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071597411910,
      "name": "enqueue_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491328136,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491328136,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225318932,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225318932,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284245104,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284245104,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271826538,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271826538,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076384,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076384,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021200,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021200,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067456,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067456,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```

```json
{
  "name": "enqueue_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122208,
      "name": "enqueue_timer",
      "external": false,
      "loc": "kernel/time/timer.c:537",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:__internal_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122208,
      "name": "enqueue_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void enqueue_timer(struct timer_base * base, struct timer_list * timer, unsigned int idx)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int bucket_expiry</code>
</li>
</ul>
</details>
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
