# Function: <code>sched_dl_global_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568454,
      "name": "sched_dl_global_validate",
      "external": false,
      "loc": "kernel/sched/core.c:8049",
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
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579446,
      "name": "sched_dl_global_validate",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605638,
      "name": "sched_dl_global_validate",
      "external": false,
      "loc": "kernel/sched/core.c:8238",
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666976,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2356",
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
      "addr": 18446744071579666976,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697472,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2343",
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
      "addr": 18446744071579697472,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731552,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2425",
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
      "addr": 18446744071579731552,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771232,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2428",
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
      "addr": 18446744071579771232,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798608,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2419",
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
      "addr": 18446744071579798608,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846448,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446744071579846448,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885344,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2465",
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
      "addr": 18446744071579885344,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878640,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2582",
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
      "addr": 18446744071579878640,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887664,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2566",
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
      "addr": 18446744071579887664,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000640,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2579",
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
      "addr": 18446744071580000640,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131008,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2732",
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
      "addr": 18446744071580131008,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305232,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2732",
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
      "addr": 18446744071580305232,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580372720,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2758",
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
      "addr": 18446744071580372720,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580430832,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2855",
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
      "addr": 18446744071580430832,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491035824,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446603336491035824,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225045244,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 3225045244,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283914528,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 13835058055283914528,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271637560,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446743936271637560,
      "name": "sched_dl_global_validate",
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818800,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446744071579818800,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753408,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446744071579753408,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806816,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446744071579806816,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int sched_dl_global_validate()
```

```json
{
  "name": "sched_dl_global_validate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851792,
      "name": "sched_dl_global_validate",
      "external": true,
      "loc": "kernel/sched/deadline.c:2466",
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
      "addr": 18446744071579851792,
      "name": "sched_dl_global_validate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int sched_dl_global_validate()
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
