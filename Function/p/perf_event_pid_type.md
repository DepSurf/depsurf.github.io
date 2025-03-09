# Function: <code>perf_event_pid_type</code>

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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630016,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1300",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630016,
      "name": "perf_event_pid_type",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758288,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1323",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758288,
      "name": "perf_event_pid_type",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824576,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1323",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824576,
      "name": "perf_event_pid_type",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919248,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919248,
      "name": "perf_event_pid_type",
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972704,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972704,
      "name": "perf_event_pid_type",
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581170989,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1387",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581211389,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1405",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581226413,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1403",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581467997,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1434",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581815584,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1343",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582244640,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1316",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582445824,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1316",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614432,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1327",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492323016,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492323016,
      "name": "perf_event_pid_type",
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226210568,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:__perf_event_header__init_id",
        "kernel/events/core.c:__perf_event_header__init_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226210568,
      "name": "perf_event_pid_type",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285567008,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285567008,
      "name": "perf_event_pid_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272448682,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272448682,
      "name": "perf_event_pid_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941504,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941504,
      "name": "perf_event_pid_type",
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887568,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887568,
      "name": "perf_event_pid_type",
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932752,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932752,
      "name": "perf_event_pid_type",
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
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
```

```json
{
  "name": "perf_event_pid_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994288,
      "name": "perf_event_pid_type",
      "external": false,
      "loc": "kernel/events/core.c:1325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_log_itrace_start",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_switch_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_namespaces_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_task_output",
        "kernel/events/core.c:perf_event_read_event",
        "kernel/events/core.c:perf_event_read_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994288,
      "name": "perf_event_pid_type",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u32 perf_event_pid_type(struct perf_event * event, struct task_struct * p, enum pid_type type)
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
