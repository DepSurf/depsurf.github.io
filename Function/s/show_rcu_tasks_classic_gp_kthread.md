# Function: <code>show_rcu_tasks_classic_gp_kthread</code>

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
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580095984,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/tasks.h:560",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/rcu.h:539",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/rcu.h:551",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": false,
      "loc": "kernel/rcu/rcu.h:551",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_rcu_tasks_classic_gp_kthread()
```

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580373327,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": true,
      "loc": "kernel/rcu/tasks.h:950",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363920,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_rcu_tasks_classic_gp_kthread()
```

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580598799,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1001",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591856,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_rcu_tasks_classic_gp_kthread()
```

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672303,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1038",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665392,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_rcu_tasks_classic_gp_kthread()
```

```json
{
  "name": "show_rcu_tasks_classic_gp_kthread",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739151,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1136",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_rcu_tasks_gp_kthreads"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732672,
      "name": "show_rcu_tasks_classic_gp_kthread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void show_rcu_tasks_classic_gp_kthread()
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
