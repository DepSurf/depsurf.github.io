# Function: <code>show_rcu_tasks_generic_gp_kthread</code>

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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095379,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:272",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095379,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591304412,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:281",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_trace_gp_kthread",
        "kernel/rcu/update.c:show_rcu_tasks_rude_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304412,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591247251,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:281",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_trace_gp_kthread",
        "kernel/rcu/update.c:show_rcu_tasks_rude_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247251,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580214354,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:280",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:586",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363552,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071593911392,
      "name": "show_rcu_tasks_generic_gp_kthread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591472,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:622",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591472,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664992,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:634",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664992,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```

```json
{
  "name": "show_rcu_tasks_generic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731920,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:692",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads",
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731920,
      "name": "show_rcu_tasks_generic_gp_kthread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks * rtp, char * s)
```
</details>
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
