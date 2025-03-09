# Function: <code>call_rcu_tasks_generic</code>

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
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580093701,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:144",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks",
        "kernel/rcu/update.c:call_rcu_tasks"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580075327,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:152",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks_rude"
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
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580076655,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:152",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks_rude"
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
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211055,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:152",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks_rude"
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
void call_rcu_tasks_generic(struct callback_head * rhp, rcu_callback_t func, struct rcu_tasks * rtp)
```

```json
{
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:273",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366400,
      "name": "call_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071593911569,
      "name": "call_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void call_rcu_tasks_generic(struct callback_head * rhp, rcu_callback_t func, struct rcu_tasks * rtp)
```

```json
{
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:281",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592752,
      "name": "call_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071595990472,
      "name": "call_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void call_rcu_tasks_generic(struct callback_head * rhp, rcu_callback_t func, struct rcu_tasks * rtp)
```

```json
{
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:290",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666272,
      "name": "call_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071596508607,
      "name": "call_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void call_rcu_tasks_generic(struct callback_head * rhp, rcu_callback_t func, struct rcu_tasks * rtp)
```

```json
{
  "name": "call_rcu_tasks_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_rcu_tasks_generic",
      "external": false,
      "loc": "kernel/rcu/tasks.h:322",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:call_rcu_tasks_trace",
        "kernel/rcu/update.c:call_rcu_tasks_rude",
        "kernel/rcu/update.c:call_rcu_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727232,
      "name": "call_rcu_tasks_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
    },
    {
      "addr": 18446744071597406062,
      "name": "call_rcu_tasks_generic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void call_rcu_tasks_generic(struct callback_head * rhp, rcu_callback_t func, struct rcu_tasks * rtp)
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
