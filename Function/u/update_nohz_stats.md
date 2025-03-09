# Function: <code>update_nohz_stats</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676400,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:8089",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:find_busiest_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676400,
      "name": "update_nohz_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710672,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:8109",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710672,
      "name": "update_nohz_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752704,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:8016",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752704,
      "name": "update_nohz_stats",
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
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795392,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795392,
      "name": "update_nohz_stats",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579851385,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:8308",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sg_lb_stats"
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579843465,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:8386",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sg_lb_stats"
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579853732,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:10432",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579959674,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:10674",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580074628,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:10780",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580245860,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:11308",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580311660,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:11612",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580364236,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:12076",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490976592,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490976592,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224978800,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224978800,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283840224,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283840224,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271585104,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271585104,
      "name": "update_nohz_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771248,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771248,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701840,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701840,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755760,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755760,
      "name": "update_nohz_stats",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```

```json
{
  "name": "update_nohz_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803632,
      "name": "update_nohz_stats",
      "external": false,
      "loc": "kernel/sched/fair.c:7999",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803632,
      "name": "update_nohz_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool update_nohz_stats(struct rq * rq, bool force)
```
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
bool update_nohz_stats(struct rq * rq, bool force)
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
