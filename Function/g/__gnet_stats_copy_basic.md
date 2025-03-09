# Function: <code>__gnet_stats_copy_basic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __gnet_stats_copy_basic(struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586246368,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:127",
      "file": "net/core/gen_stats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_copy_basic"
      ],
      "caller_func": [
        "net/core/gen_estimator.c:est_timer",
        "net/core/gen_estimator.c:gen_new_estimator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246368,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670288,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:133",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/gen_estimator.c:est_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670288,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855248,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:133",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855248,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586978480,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:133",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978480,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587476672,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:133",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476672,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587781568,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:145",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781568,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587914480,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:145",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587914480,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223024,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223024,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427648,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427648,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589294848,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:140",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294848,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589293424,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:140",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589293424,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589187312,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:140",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187312,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589908832,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:140",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589908832,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501947232,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501947232,
      "name": "__gnet_stats_copy_basic",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234703240,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234703240,
      "name": "__gnet_stats_copy_basic",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295368912,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295368912,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278251398,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278251398,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588034432,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588034432,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747520,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747520,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588366208,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366208,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
```

```json
{
  "name": "__gnet_stats_copy_basic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588501840,
      "name": "__gnet_stats_copy_basic",
      "external": true,
      "loc": "net/core/gen_stats.c:141",
      "file": "net/core/gen_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/gen_stats.c:___gnet_stats_copy_basic",
        "net/core/gen_estimator.c:est_fetch_counters",
        "net/sched/sch_mq.c:mq_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501840,
      "name": "__gnet_stats_copy_basic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const seqcount_t * running</code>
</li>
<li>
<b>Param reordered. </b>
<code>bstats, cpu, b</code> ➡️ <code>running, bstats, cpu, b</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __gnet_stats_copy_basic(const seqcount_t * running, struct gnet_stats_basic_packed * bstats, struct gnet_stats_basic_cpu * cpu, struct gnet_stats_basic_packed * b)
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
