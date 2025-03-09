# Function: <code>timekeeping_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2038",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040528,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1426
    },
    {
      "addr": 18446744071580044639,
      "name": "timekeeping_advance.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082960,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580088205,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132032,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580137217,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195072,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2047",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195072,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179040,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2117",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179040,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2128",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183728,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
    },
    {
      "addr": 18446744071591253753,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
bool timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2129",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329744,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    },
    {
      "addr": 18446744071592153238,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
bool timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2150",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541648,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    },
    {
      "addr": 18446744071593928168,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
bool timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2150",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798640,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    },
    {
      "addr": 18446744071595996213,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
bool timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2150",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881856,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
    },
    {
      "addr": 18446744071596514558,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
bool timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2150",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972288,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    },
    {
      "addr": 18446744071597413885,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491353912,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491353912,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225348088,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225348088,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2352
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284285952,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284285952,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1848
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
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271846732,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271846732,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1434
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101232,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580106417,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046544,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580051729,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092304,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580097489,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```

```json
{
  "name": "timekeeping_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_advance",
      "external": false,
      "loc": "kernel/time/timekeeping.c:2048",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144048,
      "name": "timekeeping_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1433
    },
    {
      "addr": 18446744071580149231,
      "name": "timekeeping_advance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
