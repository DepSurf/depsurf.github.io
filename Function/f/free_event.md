# Function: <code>free_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420608,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:3743",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:orphans_remove_work",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420608,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580493568,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4012",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493568,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557024,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4109",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557024,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587696,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4196",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587696,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667648,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4130",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667648,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799232,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4468",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799232,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865792,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4469",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865792,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962624,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4503",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962624,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014832,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014832,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194848,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4826",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194848,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236768,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4905",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236768,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252832,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4989",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252832,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496736,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:5095",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496736,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842736,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4993",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842736,
      "name": "free_event",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269472,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:5208",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269472,
      "name": "free_event",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470320,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:5208",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470320,
      "name": "free_event",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582639072,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:5257",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639072,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492367776,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492367776,
      "name": "free_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226252624,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226252624,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285621232,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285621232,
      "name": "free_event",
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272472670,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272472670,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983680,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983680,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929904,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929904,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974880,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974880,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void free_event(struct perf_event * event)
```

```json
{
  "name": "free_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035712,
      "name": "free_event",
      "external": false,
      "loc": "kernel/events/core.c:4598",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035712,
      "name": "free_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
