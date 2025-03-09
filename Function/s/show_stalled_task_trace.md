# Function: <code>show_stalled_task_trace</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095565,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:979",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095565,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591304737,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1001",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304737,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591247533,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1035",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247533,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1089",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209008,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071592140597,
      "name": "show_stalled_task_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1441",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367744,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071593911731,
      "name": "show_stalled_task_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580595469,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1594",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580668973,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1631",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```

```json
{
  "name": "show_stalled_task_trace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_stalled_task_trace",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1747",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730992,
      "name": "show_stalled_task_trace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071597406207,
      "name": "show_stalled_task_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void show_stalled_task_trace(struct task_struct * t, bool * firstreport)
```
</details>
</li>
</ul>
