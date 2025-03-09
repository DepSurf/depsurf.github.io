# Function: <code>psi_schedule_poll_work</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579854128,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:555",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854128,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902672,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902672,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945504,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945504,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579935615,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:550",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_poll_work"
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
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579942684,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:559",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker"
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
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580068935,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:570",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker"
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
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580153873,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:569",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker"
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
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580328938,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:594",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_poll_worker"
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491102104,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491102104,
      "name": "psi_schedule_poll_work",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225104188,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225104188,
      "name": "psi_schedule_poll_work",
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
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283993088,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283993088,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271683920,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271683920,
      "name": "psi_schedule_poll_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579874784,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874784,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579809792,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809792,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579862944,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862944,
      "name": "psi_schedule_poll_work",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
```

```json
{
  "name": "psi_schedule_poll_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579908320,
      "name": "psi_schedule_poll_work",
      "external": false,
      "loc": "kernel/sched/psi.c:556",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_poll_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908320,
      "name": "psi_schedule_poll_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void psi_schedule_poll_work(struct psi_group * group, long unsigned int delay)
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
