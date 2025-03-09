# Function: <code>trace_sched_wake_idle_without_ipi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542306,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:549",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560181,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:549",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579585190,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:549",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579569007,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:551",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598785,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:557",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_sched_wake_idle_without_ipi(int cpu)
```

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632451,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:559",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609648,
      "name": "trace_sched_wake_idle_without_ipi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_sched_wake_idle_without_ipi(int cpu)
```

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579670195,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:574",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647328,
      "name": "trace_sched_wake_idle_without_ipi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699708,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579740587,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779073,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:586",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579769405,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:670",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777101,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:670",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870245,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:668",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986084,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:671",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580147092,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:671",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580199108,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:671",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_function_single_prep_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580247092,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:720",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_function_single_prep_ipi",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283768700,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717211,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579645100,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579704476,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
  "name": "trace_sched_wake_idle_without_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579748033,
      "name": "trace_sched_wake_idle_without_ipi",
      "external": false,
      "loc": "include/trace/events/sched.h:581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void trace_sched_wake_idle_without_ipi(int cpu)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void trace_sched_wake_idle_without_ipi(int cpu)
```
</details>
</li>
</ul>
