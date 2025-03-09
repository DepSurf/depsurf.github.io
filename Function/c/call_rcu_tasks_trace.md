# Function: <code>call_rcu_tasks_trace</code>

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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093696,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1111",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093696,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075312,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1135",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075312,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076640,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1169",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076640,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211040,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1223",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/bpf/trampoline.c:bpf_tramp_image_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211040,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367120,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1592",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367120,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580593520,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1717",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_array_free_sleepable",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock",
        "kernel/bpf/memalloc.c:bpf_mem_refill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580593520,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667040,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1754",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_array_free_sleepable",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/bpf/memalloc.c:bpf_mem_refill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667040,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_rcu_tasks_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728160,
      "name": "call_rcu_tasks_trace",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1870",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_array_free_sleepable",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728160,
      "name": "call_rcu_tasks_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void call_rcu_tasks_trace(struct callback_head * rhp, rcu_callback_t func)
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
