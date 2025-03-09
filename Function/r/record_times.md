# Function: <code>record_times</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825168,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:400",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825168,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851920,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:625",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851920,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900448,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900448,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943600,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_group_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943600,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931824,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:642",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_group_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931824,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579942377,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:651",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_group_change"
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
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580068511,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:662",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_group_change"
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
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580153477,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:661",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_group_change"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu * groupc, u64 now)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314624,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:726",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_group_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314624,
      "name": "record_times",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu * groupc, u64 now)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381296,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:749",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_group_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381296,
      "name": "record_times",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu * groupc, u64 now)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438496,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:738",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_group_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438496,
      "name": "record_times",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491101112,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491101112,
      "name": "record_times.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225105000,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225105000,
      "name": "record_times.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283992784,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283992784,
      "name": "record_times.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271683718,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271683718,
      "name": "record_times.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872560,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872560,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807568,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807568,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860720,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860720,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```

```json
{
  "name": "record_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579906096,
      "name": "record_times",
      "external": false,
      "loc": "kernel/sched/psi.c:626",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_memstall_tick",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906096,
      "name": "record_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void record_times(struct psi_group_cpu * groupc, u64 now)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void record_times(struct psi_group_cpu * groupc, int cpu, bool memstall_tick)
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
