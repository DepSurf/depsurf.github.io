# Function: <code>calc_load_nohz_fold</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584624,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:220",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579614016,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:221",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644432,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:217",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579681984,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:271",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579715840,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:271",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757760,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757760,
      "name": "calc_load_nohz_fold",
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579791765,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579782613,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579790501,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579886197,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580190645,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:233",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580381109,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:233",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580449797,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:233",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580509109,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:233",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:calc_load_nohz_remote",
        "kernel/sched/build_utility.c:calc_load_nohz_start"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490936056,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490936056,
      "name": "calc_load_nohz_fold",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224954596,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224954596,
      "name": "calc_load_nohz_fold",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283792032,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283792032,
      "name": "calc_load_nohz_fold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271569328,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
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
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733680,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733680,
      "name": "calc_load_nohz_fold",
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
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662512,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662512,
      "name": "calc_load_nohz_fold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718128,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718128,
      "name": "calc_load_nohz_fold",
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
void calc_load_nohz_fold(struct rq * rq)
```

```json
{
  "name": "calc_load_nohz_fold",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765408,
      "name": "calc_load_nohz_fold",
      "external": false,
      "loc": "kernel/sched/loadavg.c:234",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_load_nohz_remote",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765408,
      "name": "calc_load_nohz_fold",
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void calc_load_nohz_fold(struct rq * rq)
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
void calc_load_nohz_fold(struct rq * rq)
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
