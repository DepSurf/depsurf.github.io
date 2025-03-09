# Function: <code>perf_event_set_state</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685778,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:656",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637296,
      "name": "perf_event_set_state.part.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580817654,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:656",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764128,
      "name": "perf_event_set_state.part.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580884326,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:656",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828832,
      "name": "perf_event_set_state.part.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580981554,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923808,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035682,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978000,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581207848,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:663",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157792,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250265,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:667",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198768,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void perf_event_set_state(struct perf_event * event, enum perf_event_state state)
```

```json
{
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210288,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:665",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210288,
      "name": "perf_event_set_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508214,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:666",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581854851,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:665",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582281346,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:659",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582482300,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:659",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582650972,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:660",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:merge_sched_in",
        "kernel/events/core.c:merge_sched_in",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492378876,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492327768,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226264648,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226220292,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285649292,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285573408,
      "name": "perf_event_set_state.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272499000,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272451688,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581004530,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946800,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950684,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892864,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580995730,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938048,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
  "name": "perf_event_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581056579,
      "name": "perf_event_set_state",
      "external": false,
      "loc": "kernel/events/core.c:657",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999632,
      "name": "perf_event_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void perf_event_set_state(struct perf_event * event, enum perf_event_state state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void perf_event_set_state(struct perf_event * event, enum perf_event_state state)
```
</details>
</li>
</ul>
