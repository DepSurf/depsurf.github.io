# Function: <code>perf_event_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411920,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:7855",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411920,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1730
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484304,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:8956",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484304,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2350
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545424,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:9150",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545424,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580572704,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:9370",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572704,
      "name": "perf_event_alloc.part.85",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2328
    },
    {
      "addr": 18446744071580575040,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580653584,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:9397",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:SYSC_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653584,
      "name": "perf_event_alloc.part.86",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2349
    },
    {
      "addr": 18446744071580655936,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781392,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:9919",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781392,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2390
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848208,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:9962",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848208,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2443
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951360,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10294",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_create_kernel_counter",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951360,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2755
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004144,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004144,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2886
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180752,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10991",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180752,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2332
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218656,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11275",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218656,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2375
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239072,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239072,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2394
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480224,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11532",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480224,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2424
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820192,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11468",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820192,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2998
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249728,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11769",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249728,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2936
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450896,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11809",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450896,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619600,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:11893",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619600,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492347904,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492347904,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2320
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226235816,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226235816,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2240
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
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285629108,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285598944,
      "name": "perf_event_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3360
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
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272480042,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272473408,
      "name": "perf_event_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2410
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972944,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972944,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2886
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920000,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920000,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2978
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964192,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964192,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2886
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
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```

```json
{
  "name": "perf_event_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025232,
      "name": "perf_event_alloc",
      "external": false,
      "loc": "kernel/events/core.c:10410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025232,
      "name": "perf_event_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2957
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct perf_event * perf_event_alloc(struct perf_event_attr * attr, int cpu, struct task_struct * task, struct perf_event * group_leader, struct perf_event * parent_event, perf_overflow_handler_t overflow_handler, void * context, int cgroup_fd)
```
</details>
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
