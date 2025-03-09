# Function: <code>perf_group_detach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391856,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1454",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:perf_free_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391856,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459952,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1695",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459952,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522400,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1701",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_free_event",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522400,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554896,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1714",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554896,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635664,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1711",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635664,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762160,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1893",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762160,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829568,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1893",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829568,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924560,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1895",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924560,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016064,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016064,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196832,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2126",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196832,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238752,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2165",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238752,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254864,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2148",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254864,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498880,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2216",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498880,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845024,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2129",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845024,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271968,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2128",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271968,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472832,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2128",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472832,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641584,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:2165",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641584,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492369072,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492369072,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226253952,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226253952,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285623072,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285623072,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272477748,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272477748,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984912,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984912,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931136,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931136,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976112,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976112,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
void perf_group_detach(struct perf_event * event)
```

```json
{
  "name": "perf_group_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036944,
      "name": "perf_group_detach",
      "external": false,
      "loc": "kernel/events/core.c:1978",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036944,
      "name": "perf_group_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
