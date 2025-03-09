# Function: <code>perf_event_groups_insert</code>

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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759312,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1550",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759312,
      "name": "perf_event_groups_insert",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825776,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1550",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825776,
      "name": "perf_event_groups_insert",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920432,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920432,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973888,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973888,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141616,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141616,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181568,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1656",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181568,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200080,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1695",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200080,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440256,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1763",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440256,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780704,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1672",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780704,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206672,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1667",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206672,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406672,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1667",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406672,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574896,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1678",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_rotate_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574896,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492323648,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492323648,
      "name": "perf_event_groups_insert",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226214536,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226214536,
      "name": "perf_event_groups_insert",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285568016,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285568016,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272448950,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272448950,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942688,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942688,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888928,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888928,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933936,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933936,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
```

```json
{
  "name": "perf_event_groups_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995648,
      "name": "perf_event_groups_insert",
      "external": false,
      "loc": "kernel/events/core.c:1552",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_mux_hrtimer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995648,
      "name": "perf_event_groups_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void perf_event_groups_insert(struct perf_event_groups * groups, struct perf_event * event)
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
