# Function: <code>put_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420304,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:3805",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_release",
        "kernel/events/core.c:orphans_remove_work",
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420304,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494688,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4075",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494688,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558144,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4172",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558144,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588752,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4259",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588752,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580668704,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4193",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668704,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800368,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4531",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800368,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866928,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4532",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866928,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963744,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4566",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963744,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016032,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016032,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581215483,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4889",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258316,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4968",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581276940,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5052",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581520686,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5158",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581868079,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5056",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582295390,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5271",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582496158,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5271",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582664606,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:5320",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pending_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492369000,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492369000,
      "name": "put_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226253888,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226253888,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285623024,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285623024,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272499908,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984880,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984880,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931104,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931104,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976080,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976080,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void put_event(struct perf_event * event)
```

```json
{
  "name": "put_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036912,
      "name": "put_event",
      "external": false,
      "loc": "kernel/events/core.c:4661",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:perf_group_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036912,
      "name": "put_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void put_event(struct perf_event * event)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void put_event(struct perf_event * event)
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
