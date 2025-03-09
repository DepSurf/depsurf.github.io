# Function: <code>poll_state_synchronize_rcu</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104021,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3863",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087104,
      "name": "poll_state_synchronize_rcu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243269,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3829",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223728,
      "name": "poll_state_synchronize_rcu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580385248,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3925",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385248,
      "name": "poll_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580615766,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3730",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612528,
      "name": "poll_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580689439,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3730",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp",
        "kernel/rcu/tree.c:kfree_rcu_monitor"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686368,
      "name": "poll_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```

```json
{
  "name": "poll_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580756367,
      "name": "poll_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3802",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp",
        "kernel/rcu/tree.c:sync_rcu_do_polled_gp",
        "kernel/rcu/tree.c:kfree_rcu_monitor"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "lib/stackdepot.c:depot_alloc_stack",
        "net/sched/sch_generic.c:mini_qdisc_pair_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753184,
      "name": "poll_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool poll_state_synchronize_rcu(long unsigned int oldstate)
```
</details>
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
