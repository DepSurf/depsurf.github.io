# Function: <code>perf_remove_from_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event * event, bool detach_group)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409248,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1673",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:orphans_remove_work",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409248,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580483805,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1892",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548992,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1904",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548992,
      "name": "perf_remove_from_context",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580768,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1917",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580768,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660496,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:1907",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660496,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791344,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2104",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791344,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857712,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2104",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857712,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951232,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2106",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951232,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016720,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016720,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188758,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2337",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197504,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581230390,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2377",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239472,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256032,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2383",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256032,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500496,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2454",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500496,
      "name": "perf_remove_from_context",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846688,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2367",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846688,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582273680,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2372",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273680,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474544,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2372",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474544,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582643248,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:perf_event_exit_event",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643248,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492369704,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492369704,
      "name": "perf_remove_from_context",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226254548,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226254548,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285623920,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285623920,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272478300,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272478300,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985568,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985568,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931792,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931792,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976768,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976768,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```

```json
{
  "name": "perf_remove_from_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037600,
      "name": "perf_remove_from_context",
      "external": false,
      "loc": "kernel/events/core.c:2191",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037600,
      "name": "perf_remove_from_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void perf_remove_from_context(struct perf_event * event, bool detach_group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void perf_remove_from_context(struct perf_event * event, long unsigned int flags)
```
</details>
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
