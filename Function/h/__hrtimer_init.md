# Function: <code>__hrtimer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823264,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1125",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_nanosleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823264,
      "name": "__hrtimer_init",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852112,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852112,
      "name": "__hrtimer_init",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881088,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881088,
      "name": "__hrtimer_init",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890320,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1097",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890320,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934832,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1097",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934832,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981920,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1268",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981920,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028720,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1259",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028720,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071776,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1259",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071776,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121136,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121136,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181040,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181040,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165968,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1393",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165968,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170528,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1393",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170528,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314896,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1541",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314896,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594739392,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1541",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525808,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596491520,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1541",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781664,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864656,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1544",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864656,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955328,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1545",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955328,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491339096,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491339096,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225332040,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225332040,
      "name": "__hrtimer_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284269280,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284269280,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271836300,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836300,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090336,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090336,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035664,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035664,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081408,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081408,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "__hrtimer_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132944,
      "name": "__hrtimer_init",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1376",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132944,
      "name": "__hrtimer_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
