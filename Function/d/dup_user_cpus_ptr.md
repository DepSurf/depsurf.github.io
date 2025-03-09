# Function: <code>dup_user_cpus_ptr</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```

```json
{
  "name": "dup_user_cpus_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859584,
      "name": "dup_user_cpus_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2500",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859584,
      "name": "dup_user_cpus_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```

```json
{
  "name": "dup_user_cpus_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974896,
      "name": "dup_user_cpus_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2599",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974896,
      "name": "dup_user_cpus_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```

```json
{
  "name": "dup_user_cpus_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135296,
      "name": "dup_user_cpus_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2632",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135296,
      "name": "dup_user_cpus_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```

```json
{
  "name": "dup_user_cpus_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_user_cpus_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2808",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495355,
      "name": "dup_user_cpus_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580197488,
      "name": "dup_user_cpus_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```

```json
{
  "name": "dup_user_cpus_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_user_cpus_ptr",
      "external": true,
      "loc": "kernel/sched/core.c:2836",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597392222,
      "name": "dup_user_cpus_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580245472,
      "name": "dup_user_cpus_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int dup_user_cpus_ptr(struct task_struct * dst, struct task_struct * src, int node)
```
</details>
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
