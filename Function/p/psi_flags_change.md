# Function: <code>psi_flags_change</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:752",
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
      "addr": 18446744071579944608,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071579950955,
      "name": "psi_flags_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:768",
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
      "addr": 18446744071579932816,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071591290908,
      "name": "psi_flags_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:773",
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
      "addr": 18446744071579940624,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071591233988,
      "name": "psi_flags_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:785",
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
      "addr": 18446744071580066032,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071592121292,
      "name": "psi_flags_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:784",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146496,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071593880466,
      "name": "psi_flags_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321376,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:870",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321376,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388576,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:893",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388576,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void psi_flags_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_flags_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445232,
      "name": "psi_flags_change",
      "external": false,
      "loc": "kernel/sched/psi.c:882",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_switch",
        "kernel/sched/build_utility.c:psi_task_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445232,
      "name": "psi_flags_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void psi_flags_change(struct task_struct * task, int clear, int set)
```
</details>
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
