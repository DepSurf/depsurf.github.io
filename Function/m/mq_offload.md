# Function: <code>mq_offload</code>

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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588076976,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:27",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588076976,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253568,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:27",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253568,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644752,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644752,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588867120,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867120,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589752672,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752672,
      "name": "mq_offload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589785360,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785360,
      "name": "mq_offload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589689296,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689296,
      "name": "mq_offload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590446912,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590446912,
      "name": "mq_offload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592049184,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049184,
      "name": "mq_offload.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593867536,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593867536,
      "name": "mq_offload.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594242448,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594242448,
      "name": "mq_offload.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595039792,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595039792,
      "name": "mq_offload.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502454624,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502454624,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235170264,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235170264,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296005952,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296005952,
      "name": "mq_offload",
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278640366,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278640366,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473504,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473504,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185504,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185504,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588805680,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805680,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
```

```json
{
  "name": "mq_offload",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946320,
      "name": "mq_offload",
      "external": false,
      "loc": "net/sched/sch_mq.c:24",
      "file": "net/sched/sch_mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_init",
        "net/sched/sch_mq.c:mq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946320,
      "name": "mq_offload",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
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
int mq_offload(struct Qdisc * sch, enum tc_mq_command cmd)
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
