# Function: <code>__update_blocked_fair</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579794156,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816640,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7868",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816640,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807904,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7944",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807904,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818272,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:8055",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818272,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:8193",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919904,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
    },
    {
      "addr": 18446744071592108902,
      "name": "__update_blocked_fair.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:8167",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027408,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1354
    },
    {
      "addr": 18446744071593876470,
      "name": "__update_blocked_fair.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:8621",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194416,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1349
    },
    {
      "addr": 18446744071595978374,
      "name": "__update_blocked_fair.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:8979",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259616,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1349
    },
    {
      "addr": 18446744071596496337,
      "name": "__update_blocked_fair.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool __update_blocked_fair(struct rq * rq, bool * done)
```

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:9302",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310272,
      "name": "__update_blocked_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1438
    },
    {
      "addr": 18446744071597393225,
      "name": "__update_blocked_fair.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490975440,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224977516,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283838848,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271584256,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579770012,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579700604,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579754524,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_blocked_fair",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802380,
      "name": "__update_blocked_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:7563",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_blocked_averages"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __update_blocked_fair(struct rq * rq, bool * done)
```
</details>
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
