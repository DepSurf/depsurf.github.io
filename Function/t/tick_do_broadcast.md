# Function: <code>tick_do_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880960,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:259",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880960,
      "name": "tick_do_broadcast.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579910496,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:259",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910496,
      "name": "tick_do_broadcast.constprop.9",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941008,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:259",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941008,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949264,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:262",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949264,
      "name": "tick_do_broadcast",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994960,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:262",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994960,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047056,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:262",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047056,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093888,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:258",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093888,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137760,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137760,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185904,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185904,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250688,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250688,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580234512,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234512,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239632,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:276",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239632,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389696,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:345",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389696,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608416,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:345",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608416,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580872928,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:345",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872928,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956224,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:346",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956224,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047808,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:346",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047808,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491411240,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491411240,
      "name": "tick_do_broadcast.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225406060,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225406060,
      "name": "tick_do_broadcast.constprop.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284357280,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284357280,
      "name": "tick_do_broadcast.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154704,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154704,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100816,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100816,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146176,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146176,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
```

```json
{
  "name": "tick_do_broadcast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198160,
      "name": "tick_do_broadcast",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198160,
      "name": "tick_do_broadcast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
bool tick_do_broadcast(struct cpumask * mask)
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
bool tick_do_broadcast(struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool tick_do_broadcast(struct cpumask * mask)
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
