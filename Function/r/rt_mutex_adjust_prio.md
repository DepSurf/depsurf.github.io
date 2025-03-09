# Function: <code>rt_mutex_adjust_prio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_adjust_prio(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678608,
      "name": "rt_mutex_adjust_prio",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:316",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678608,
      "name": "rt_mutex_adjust_prio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_adjust_prio(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697648,
      "name": "rt_mutex_adjust_prio",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:318",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697648,
      "name": "rt_mutex_adjust_prio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_adjust_prio(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724768,
      "name": "rt_mutex_adjust_prio",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:382",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724768,
      "name": "rt_mutex_adjust_prio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579720446,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:349",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579753087,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:337",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787555,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:337",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579834019,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:337",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579868976,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579917600,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579962432,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:336",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579950576,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:336",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591653242,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:317",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592826090,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:436",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594733919,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:438",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596485663,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:475",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597027204,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:504",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597956548,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:523",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491122092,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225122780,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284013272,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271696100,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579889712,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579824672,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579877872,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_adjust_prio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923502,
      "name": "rt_mutex_adjust_prio",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void rt_mutex_adjust_prio(struct task_struct * task)
```
</details>
</li>
</ul>
