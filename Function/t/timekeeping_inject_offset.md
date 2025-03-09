# Function: <code>timekeeping_inject_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848592,
      "name": "timekeeping_inject_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1203",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848592,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int timekeeping_inject_offset(struct timespec * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877712,
      "name": "timekeeping_inject_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1208",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877712,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int timekeeping_inject_offset(struct timespec * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889744,
      "name": "timekeeping_inject_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1237",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889744,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int timekeeping_inject_offset(struct timespec * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899616,
      "name": "timekeeping_inject_offset",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1267",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899616,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int timekeeping_inject_offset(struct timespec * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944224,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1271",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944224,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991856,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1272",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991856,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038480,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1263",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038480,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081296,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081296,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130368,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130368,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192080,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1272",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192080,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176832,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1341",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176832,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181120,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1342",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181120,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1341",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329216,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071592152985,
      "name": "timekeeping_inject_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1362",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541072,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071593927915,
      "name": "timekeeping_inject_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1362",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798048,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071595995960,
      "name": "timekeeping_inject_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1362",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881280,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071596514279,
      "name": "timekeeping_inject_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1362",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971712,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071597413606,
      "name": "timekeeping_inject_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491352872,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491352872,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225346524,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225346524,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284283472,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284283472,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271845164,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271845164,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099568,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099568,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044880,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044880,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090640,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090640,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int timekeeping_inject_offset(const struct timespec64 * ts)
```

```json
{
  "name": "timekeeping_inject_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142384,
      "name": "timekeeping_inject_offset",
      "external": false,
      "loc": "kernel/time/timekeeping.c:1273",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_warp_clock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142384,
      "name": "timekeeping_inject_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<b>Param type changed. </b>
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec64 * ts</code> ➡️ <code>const struct timespec64 * ts</code>
</li>
</ul>
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
