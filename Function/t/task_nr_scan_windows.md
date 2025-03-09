# Function: <code>task_nr_scan_windows</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573730,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:819",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_scan_min",
        "kernel/sched/fair.c:task_scan_max"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584768,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:953",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584768,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610848,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1077",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610848,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588496,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1074",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588496,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617968,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1077",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617968,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650032,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1064",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650032,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579687504,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1060",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687504,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721056,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1107",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721056,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763552,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763552,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797184,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797184,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787984,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1124",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787984,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796144,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1121",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796144,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579896032,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1110",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896032,
      "name": "task_nr_scan_windows.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006784,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1112",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_task_scan_period",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006784,
      "name": "task_nr_scan_windows.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169440,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1151",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_task_scan_period",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169440,
      "name": "task_nr_scan_windows.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231152,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1168",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_task_scan_period",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231152,
      "name": "task_nr_scan_windows",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280224,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1409",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_task_scan_period",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280224,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490942816,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490942816,
      "name": "task_nr_scan_windows",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283798848,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283798848,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739408,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739408,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669792,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669792,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723920,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723920,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
```

```json
{
  "name": "task_nr_scan_windows",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771296,
      "name": "task_nr_scan_windows",
      "external": false,
      "loc": "kernel/sched/fair.c:1106",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_scan_max",
        "kernel/sched/fair.c:task_scan_min"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771296,
      "name": "task_nr_scan_windows",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
unsigned int task_nr_scan_windows(struct task_struct * p)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct * p)
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
