# Function: <code>synchronize_rcu_tasks_rude</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:659",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092192,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:669",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074544,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:669",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075872,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:713",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210272,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368512,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1058",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368512,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589536,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1121",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589536,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662992,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1158",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662992,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void synchronize_rcu_tasks_rude()
```

```json
{
  "name": "synchronize_rcu_tasks_rude",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729712,
      "name": "synchronize_rcu_tasks_rude",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1262",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729712,
      "name": "synchronize_rcu_tasks_rude",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void synchronize_rcu_tasks_rude()
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
