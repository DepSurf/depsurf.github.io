# Function: <code>sched_dl_do_global</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568770,
      "name": "sched_dl_do_global",
      "external": false,
      "loc": "kernel/sched/core.c:8085",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_rt_handler"
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
  "name": "sched_dl_do_global",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579769,
      "name": "sched_dl_do_global",
      "external": false,
      "loc": "kernel/sched/core.c:8121",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_rt_handler"
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
  "name": "sched_dl_do_global",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605958,
      "name": "sched_dl_do_global",
      "external": false,
      "loc": "kernel/sched/core.c:8274",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_rt_handler"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667392,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2405",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667392,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697888,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2392",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697888,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731968,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2474",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731968,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771648,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2477",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771648,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799040,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2468",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799040,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846880,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846880,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885552,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2514",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885552,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879008,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2634",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879008,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888048,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2618",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888048,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001136,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2631",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001136,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131584,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2784",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131584,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305808,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2784",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305808,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580373296,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2810",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373296,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431424,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2907",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431424,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491036408,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491036408,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225045748,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225045748,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283915216,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283915216,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271638064,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271638064,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819232,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819232,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753840,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753840,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807248,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807248,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void sched_dl_do_global()
```

```json
{
  "name": "sched_dl_do_global",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852256,
      "name": "sched_dl_do_global",
      "external": true,
      "loc": "kernel/sched/deadline.c:2515",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_rt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852256,
      "name": "sched_dl_do_global",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void sched_dl_do_global()
```
</details>
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
