# Function: <code>tick_sched_do_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_sched_do_timer(ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886688,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:112",
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
      "addr": 18446744071579886688,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void tick_sched_do_timer(ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916272,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:112",
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
      "addr": 18446744071579916272,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void tick_sched_do_timer(ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579946896,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:112",
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
      "addr": 18446744071579946896,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void tick_sched_do_timer(ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579954768,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:116",
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
      "addr": 18446744071579954768,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void tick_sched_do_timer(ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001600,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580001600,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053120,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:116",
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
      "addr": 18446744071580053120,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099952,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:113",
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
      "addr": 18446744071580099952,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143856,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:113",
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
      "addr": 18446744071580143856,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191872,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580191872,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580257250,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:122",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580241106,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:172",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580246690,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:172",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580397394,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:172",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614240,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:174",
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
      "addr": 18446744071580614240,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879056,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:174",
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
      "addr": 18446744071580879056,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963568,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:185",
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
      "addr": 18446744071580963568,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:186",
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
      "addr": 18446744071581055424,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071597416312,
      "name": "tick_sched_do_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491421416,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446603336491421416,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225414340,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 3225414340,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284368928,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 13835058055284368928,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271889090,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446743936271889090,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160672,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580160672,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107024,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580107024,
      "name": "tick_sched_do_timer",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152144,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580152144,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_sched_do_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580203952,
      "name": "tick_sched_do_timer",
      "external": false,
      "loc": "kernel/time/tick-sched.c:117",
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
      "addr": 18446744071580203952,
      "name": "tick_sched_do_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tick_sched * ts</code>
</li>
<li>
<b>Param reordered. </b>
<code>now</code> ➡️ <code>ts, now</code>
</li>
</ul>
</details>
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
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tick_sched_do_timer(struct tick_sched * ts, ktime_t now)
```
</details>
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
