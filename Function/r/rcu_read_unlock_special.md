# Function: <code>rcu_read_unlock_special</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_read_unlock_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_special",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:624",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:exit_rcu",
        "kernel/rcu/tree.c:strict_work_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405824,
      "name": "rcu_read_unlock_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071593917495,
      "name": "rcu_read_unlock_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void rcu_read_unlock_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_special",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:624",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:exit_rcu",
        "kernel/rcu/tree.c:strict_work_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641552,
      "name": "rcu_read_unlock_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071595991324,
      "name": "rcu_read_unlock_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void rcu_read_unlock_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_special",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:626",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:exit_rcu",
        "kernel/rcu/tree.c:strict_work_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709696,
      "name": "rcu_read_unlock_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071596509356,
      "name": "rcu_read_unlock_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void rcu_read_unlock_special(struct task_struct * t)
```

```json
{
  "name": "rcu_read_unlock_special",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_read_unlock_special",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:626",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:exit_rcu",
        "kernel/rcu/tree.c:strict_work_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776544,
      "name": "rcu_read_unlock_special",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071597407209,
      "name": "rcu_read_unlock_special.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_read_unlock_special",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580067265,
      "name": "rcu_read_unlock_special",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:595",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__rcu_read_unlock"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void rcu_read_unlock_special(struct task_struct * t)
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
