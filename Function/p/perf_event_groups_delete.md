# Function: <code>perf_event_groups_delete</code>

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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759248,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1592",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759248,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825712,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1592",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825712,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920368,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920368,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973824,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973824,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581184508,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1680",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:list_del_event"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581227036,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1698",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:list_del_event"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581214785,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1719",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581469096,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1787",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581836638,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1696",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582262284,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1691",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582462827,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1691",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context"
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
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582635518,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1702",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context"
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492323568,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492323568,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226214404,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226214404,
      "name": "perf_event_groups_delete",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285567888,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285567888,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272448888,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272448888,
      "name": "perf_event_groups_delete",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942624,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942624,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888864,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888864,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933872,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933872,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995584,
      "name": "perf_event_groups_delete",
      "external": false,
      "loc": "kernel/events/core.c:1594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995584,
      "name": "perf_event_groups_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
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
void perf_event_groups_delete(struct perf_event_groups * groups, struct perf_event * event)
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
