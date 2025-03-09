# Function: <code>__rb_reserve_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580186886,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2687",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_reserve_next_event"
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
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580228518,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2681",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_reserve_next_event"
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263392,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2650",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263392,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275840,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2652",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275840,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329648,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2645",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329648,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390272,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2775",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390272,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445264,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2838",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445264,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498992,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2815",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498992,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546896,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546896,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639552,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2885",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639552,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629504,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3348",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629504,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3435",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632400,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
    },
    {
      "addr": 18446744071591260803,
      "name": "__rb_reserve_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3435",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804896,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071592167626,
      "name": "__rb_reserve_next.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3473",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030176,
      "name": "__rb_reserve_next.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
    },
    {
      "addr": 18446744071593941188,
      "name": "__rb_reserve_next.constprop.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3552",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330816,
      "name": "__rb_reserve_next.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
    },
    {
      "addr": 18446744071596003313,
      "name": "__rb_reserve_next.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3555",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425536,
      "name": "__rb_reserve_next.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1202
    },
    {
      "addr": 18446744071596521906,
      "name": "__rb_reserve_next.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581535216,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3461",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535216,
      "name": "__rb_reserve_next.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491841448,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491841448,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225788924,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225788924,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284902912,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284902912,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272139394,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272139394,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515696,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515696,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580464416,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464416,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506944,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506944,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
```

```json
{
  "name": "__rb_reserve_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580563920,
      "name": "__rb_reserve_next",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2816",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563920,
      "name": "__rb_reserve_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct ring_buffer_event * __rb_reserve_next(struct ring_buffer_per_cpu * cpu_buffer, struct rb_event_info * info)
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
