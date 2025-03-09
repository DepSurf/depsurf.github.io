# Function: <code>trc_wait_for_one_reader</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094746,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:877",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093984,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580077177,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:893",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076432,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void trc_wait_for_one_reader(struct task_struct * t, struct list_head * bhp)
```

```json
{
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580077712,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:928",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077712,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071580078272,
      "name": "trc_wait_for_one_reader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213175,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:976",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212144,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446744071592140743,
      "name": "trc_wait_for_one_reader.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372449,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1313",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371440,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
    },
    {
      "addr": 18446744071593911975,
      "name": "trc_wait_for_one_reader.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580595419,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1425",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594272,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071595990525,
      "name": "trc_wait_for_one_reader.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580668923,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1462",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667776,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071596508660,
      "name": "trc_wait_for_one_reader.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trc_wait_for_one_reader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580736062,
      "name": "trc_wait_for_one_reader",
      "external": false,
      "loc": "kernel/rcu/tasks.h:1578",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734944,
      "name": "trc_wait_for_one_reader.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071597406425,
      "name": "trc_wait_for_one_reader.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void trc_wait_for_one_reader(struct task_struct * t, struct list_head * bhp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void trc_wait_for_one_reader(struct task_struct * t, struct list_head * bhp)
```
</details>
</li>
</ul>
