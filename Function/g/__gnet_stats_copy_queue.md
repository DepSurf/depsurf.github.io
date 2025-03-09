# Function: <code>__gnet_stats_copy_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586247113,
      "name": "__gnet_stats_copy_queue",
      "external": false,
      "loc": "net/core/gen_stats.c:238",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
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
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586671159,
      "name": "__gnet_stats_copy_queue",
      "external": false,
      "loc": "net/core/gen_stats.c:257",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
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
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586856119,
      "name": "__gnet_stats_copy_queue",
      "external": false,
      "loc": "net/core/gen_stats.c:255",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586979159,
      "name": "__gnet_stats_copy_queue",
      "external": false,
      "loc": "net/core/gen_stats.c:255",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
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
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587477369,
      "name": "__gnet_stats_copy_queue",
      "external": false,
      "loc": "net/core/gen_stats.c:255",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587782156,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:267",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781840,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587915644,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:301",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587914752,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588223980,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222944,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428604,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427568,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589294688,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:302",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294688,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589293264,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:302",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589293264,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589187152,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:302",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187152,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589908624,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:302",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_queue",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589908624,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501948552,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501947664,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234704216,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234703144,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295370388,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295368752,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278252934,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278251296,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588035388,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588034352,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748476,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747440,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588367164,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366128,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
```

```json
{
  "name": "__gnet_stats_copy_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502796,
      "name": "__gnet_stats_copy_queue",
      "external": true,
      "loc": "net/core/gen_stats.c:298",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_queue"
      ],
      "caller_func": [
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501760,
      "name": "__gnet_stats_copy_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue * qstats, const struct gnet_stats_queue * cpu, const struct gnet_stats_queue * q, __u32 qlen)
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
