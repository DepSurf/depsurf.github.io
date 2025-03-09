# Function: <code>sync_rcu_exp_done_unlocked</code>

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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108104,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:161",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104416,
      "name": "sync_rcu_exp_done_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090344,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:161",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085632,
      "name": "sync_rcu_exp_done_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099141,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:161",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087264,
      "name": "sync_rcu_exp_done_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580239397,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:161",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223888,
      "name": "sync_rcu_exp_done_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580412244,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:161",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385440,
      "name": "sync_rcu_exp_done_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580630675,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
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
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580712691,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:164",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_rcu_exp_done_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580788069,
      "name": "sync_rcu_exp_done_unlocked",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:164",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once"
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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
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
bool sync_rcu_exp_done_unlocked(struct rcu_node * rnp)
```
</details>
</li>
</ul>
