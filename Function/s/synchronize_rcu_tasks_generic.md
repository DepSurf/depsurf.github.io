# Function: <code>synchronize_rcu_tasks_generic</code>

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
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:163",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:171",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
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
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:171",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
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
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:171",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_barrier_tasks_rude"
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
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:327",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:synchronize_rcu_tasks_trace",
        "kernel/rcu/update.c:synchronize_rcu_tasks_rude",
        "kernel/rcu/update.c:synchronize_rcu_tasks"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void synchronize_rcu_tasks_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:563",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:synchronize_rcu_tasks_trace",
        "kernel/rcu/update.c:synchronize_rcu_tasks_rude",
        "kernel/rcu/update.c:synchronize_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589248,
      "name": "synchronize_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071595990355,
      "name": "synchronize_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void synchronize_rcu_tasks_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:575",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:synchronize_rcu_tasks_trace",
        "kernel/rcu/update.c:synchronize_rcu_tasks_rude",
        "kernel/rcu/update.c:synchronize_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662704,
      "name": "synchronize_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071596508468,
      "name": "synchronize_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void synchronize_rcu_tasks_generic(struct rcu_tasks * rtp)
```

```json
{
  "name": "synchronize_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "synchronize_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:633",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:synchronize_rcu_tasks_trace",
        "kernel/rcu/update.c:synchronize_rcu_tasks_rude",
        "kernel/rcu/update.c:synchronize_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729424,
      "name": "synchronize_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071597406186,
      "name": "synchronize_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void synchronize_rcu_tasks_generic(struct rcu_tasks * rtp)
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
