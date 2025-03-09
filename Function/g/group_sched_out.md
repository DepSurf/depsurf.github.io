# Function: <code>group_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580402976,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:1608",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402976,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580475680,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:1833",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475680,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void group_sched_out(struct perf_event * group_event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539696,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:1841",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539696,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void group_sched_out(struct perf_event * group_event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571008,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:1854",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571008,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580639550,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:1837",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639088,
      "name": "group_sched_out.part.92",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768569,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2034",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768112,
      "name": "group_sched_out.part.108",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580835801,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2034",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835344,
      "name": "group_sched_out.part.108",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580932056,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2036",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931584,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580985992,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985520,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581183361,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2266",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163904,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581225537,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2309",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203648,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241741,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2312",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227664,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581477311,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2380",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463024,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827052,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2293",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809424,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582246480,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2281",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246480,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447200,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2281",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447200,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_event_context * ctx)
```

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582616304,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2319",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__pmu_ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616304,
      "name": "group_sched_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492357528,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492356560,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226241780,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226240660,
      "name": "group_sched_out.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285607608,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285606320,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272483056,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272482292,
      "name": "group_sched_out.part.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580954792,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954320,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580900856,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900384,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946040,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945568,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "group_sched_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581007912,
      "name": "group_sched_out",
      "external": false,
      "loc": "kernel/events/core.c:2121",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ],
      "caller_func": [
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007440,
      "name": "group_sched_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_cpu_context * cpuctx, struct perf_event_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void group_sched_out(struct perf_event * group_event, struct perf_event_context * ctx)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
