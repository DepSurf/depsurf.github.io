# Function: <code>perf_event_update_time</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627056,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627056,
      "name": "perf_event_update_time",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756080,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756080,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822384,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:638",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822384,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916992,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916992,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970448,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970448,
      "name": "perf_event_update_time",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581148544,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:645",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148544,
      "name": "perf_event_update_time",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188240,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:649",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_context_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188240,
      "name": "perf_event_update_time",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206240,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:647",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:perf_event_set_state",
        "kernel/events/core.c:perf_event_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206240,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446320,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:648",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446320,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788880,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:647",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788880,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215088,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:641",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215088,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415136,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:641",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415136,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582848,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:642",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:perf_event_context_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:event_sched_out",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582848,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492321664,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492321664,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226205264,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226205264,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285560784,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285560784,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272445704,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272445704,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939248,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939248,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885312,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885312,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930496,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930496,
      "name": "perf_event_update_time",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void perf_event_update_time(struct perf_event * event)
```

```json
{
  "name": "perf_event_update_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991120,
      "name": "perf_event_update_time",
      "external": false,
      "loc": "kernel/events/core.c:639",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991120,
      "name": "perf_event_update_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void perf_event_update_time(struct perf_event * event)
```
</details>
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
