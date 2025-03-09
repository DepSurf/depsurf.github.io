# Function: <code>dl_change_utilization</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579666144,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:125",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666144,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579696656,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:126",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696656,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730720,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:155",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730720,
      "name": "dl_change_utilization",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770400,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770400,
      "name": "dl_change_utilization",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797744,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797744,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845232,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845232,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874432,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874432,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865920,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:233",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865920,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874448,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:233",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874448,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580002696,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:233",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:sched_dl_overflow"
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
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580133673,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:307",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
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
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580307745,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:309",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
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
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580375233,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:311",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
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
  "name": "dl_change_utilization",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580433368,
      "name": "dl_change_utilization",
      "external": false,
      "loc": "kernel/sched/deadline.c:324",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:sched_dl_overflow"
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491034160,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491034160,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225043608,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225043608,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283912448,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283912448,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271636294,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271636294,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817584,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817584,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752192,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752192,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805600,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805600,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
```

```json
{
  "name": "dl_change_utilization",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850576,
      "name": "dl_change_utilization",
      "external": true,
      "loc": "kernel/sched/deadline.c:156",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850576,
      "name": "dl_change_utilization",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
void dl_change_utilization(struct task_struct * p, u64 new_bw)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void dl_change_utilization(struct task_struct * p, u64 new_bw)
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
