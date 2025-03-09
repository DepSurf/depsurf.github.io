# Function: <code>psi_group_change</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579825559,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:446",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579855144,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:671",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903672,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947584,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071579951016,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:688",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935296,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071591290969,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:680",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942320,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071591234049,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:691",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_switch",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068432,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071592121415,
      "name": "psi_group_change.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:690",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153408,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1117
    },
    {
      "addr": 18446744071593881948,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:755",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328192,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1321
    },
    {
      "addr": 18446744071595981949,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:778",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395504,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071596500146,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, u64 now, bool wake_clock)
```

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:767",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451360,
      "name": "psi_group_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071597397511,
      "name": "psi_group_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491103092,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225108928,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283994444,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271685990,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875784,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810792,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863944,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "psi_group_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579909336,
      "name": "psi_group_change",
      "external": false,
      "loc": "kernel/sched/psi.c:672",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_task_change"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void psi_group_change(struct psi_group * group, int cpu, unsigned int clear, unsigned int set, bool wake_clock)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 now</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, cpu, clear, set, wake_clock</code> ➡️ <code>group, cpu, clear, set, now, wake_clock</code>
</li>
</ul>
</details>
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
