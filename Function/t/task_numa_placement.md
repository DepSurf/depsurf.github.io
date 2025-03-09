# Function: <code>task_numa_placement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579608754,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:1826",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579622173,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:1939",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644001,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2071",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579623010,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2067",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579654994,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2119",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579686857,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2147",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579721869,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2096",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732288,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2165",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732288,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775552,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775552,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813808,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2352",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813808,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805104,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2366",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805104,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819872,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2363",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819872,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914160,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2352",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914160,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020272,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2357",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020272,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189136,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2552",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189136,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1325
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254336,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2552",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254336,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1306
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580304080,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2793",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580304080,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490973136,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490973136,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2044
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283816080,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283816080,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2892
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751408,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751408,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681792,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681792,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1409
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735920,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735920,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
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
void task_numa_placement(struct task_struct * p)
```

```json
{
  "name": "task_numa_placement",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783584,
      "name": "task_numa_placement",
      "external": false,
      "loc": "kernel/sched/fair.c:2123",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783584,
      "name": "task_numa_placement",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1406
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void task_numa_placement(struct task_struct * p)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void task_numa_placement(struct task_struct * p)
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
void task_numa_placement(struct task_struct * p)
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
