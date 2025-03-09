# Function: <code>event_function_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482848,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:245",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:perf_event_release_kernel",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482848,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548240,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:245",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548240,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580016,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:249",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580016,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659744,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:249",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659744,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790592,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:249",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790592,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856960,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:249",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856960,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949808,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949808,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002720,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002720,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174368,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:255",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174368,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215200,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:258",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215200,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236800,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:259",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236800,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475232,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:260",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475232,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800832,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:260",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800832,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230352,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:263",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230352,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430768,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:263",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430768,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597808,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:263",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:perf_event_task_disable",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_period",
        "kernel/events/core.c:perf_event_pause",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597808,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492340952,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492340952,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226209656,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226209656,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285594896,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285594896,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272468672,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272468672,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971520,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971520,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917296,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917296,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962768,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962768,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void event_function_call(struct perf_event * event, event_f func, void * data)
```

```json
{
  "name": "event_function_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993536,
      "name": "event_function_call",
      "external": false,
      "loc": "kernel/events/core.c:248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_event_enable",
        "kernel/events/core.c:_perf_event_disable",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993536,
      "name": "event_function_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void event_function_call(struct perf_event * event, event_f func, void * data)
```
</details>
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
