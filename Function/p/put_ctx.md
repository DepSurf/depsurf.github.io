# Function: <code>put_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580398288,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:884",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_disable",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:orphans_remove_work",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398288,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580470176,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1129",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470176,
      "name": "put_ctx",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580533216,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1137",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533216,
      "name": "put_ctx",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580564208,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1129",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564208,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580646592,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1168",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646592,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580776192,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1191",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776192,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844000,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1191",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844000,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950400,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950400,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581003312,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003312,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156416,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1254",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__perf_event_ctx_lock_double",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156416,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581199728,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1272",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__perf_event_ctx_lock_double",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199728,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216672,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216672,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581456368,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1301",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456368,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802000,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1210",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802000,
      "name": "put_ctx",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582231568,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1183",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231568,
      "name": "put_ctx",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582431984,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1183",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431984,
      "name": "put_ctx",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582600368,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1194",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__perf_pmu_install_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_compat_ioctl",
        "kernel/events/core.c:perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_enable_on_exec",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600368,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492334416,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492334416,
      "name": "put_ctx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336492334544,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226225980,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226225980,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285586096,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285586096,
      "name": "put_ctx",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272453372,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:find_get_context",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272453372,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972112,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972112,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918512,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918512,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963360,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963360,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void put_ctx(struct perf_event_context * ctx)
```

```json
{
  "name": "put_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581024384,
      "name": "put_ctx",
      "external": false,
      "loc": "kernel/events/core.c:1192",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_try_init_event",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_enable",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_refresh",
        "kernel/events/core.c:perf_event_enable",
        "kernel/events/core.c:perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024384,
      "name": "put_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
