# Function: <code>rcu_spawn_tasks_kthread_generic</code>

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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609189098,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:237",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_spawn_tasks_trace_kthread",
        "kernel/rcu/update.c:rcu_spawn_tasks_rude_kthread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609189098,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612255445,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:245",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612255445,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614396979,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:245",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614396979,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 116
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615331094,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:244",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615331094,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617114877,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:543",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617114877,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 165
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627781712,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:579",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627781712,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619544608,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:591",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619544608,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "rcu_spawn_tasks_kthread_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621843584,
      "name": "rcu_spawn_tasks_kthread_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:649",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic",
        "kernel/rcu/update.c:rcu_init_tasks_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621843584,
      "name": "rcu_spawn_tasks_kthread_generic",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks * rtp)
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
