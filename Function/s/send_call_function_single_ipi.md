# Function: <code>send_call_function_single_ipi</code>

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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778720,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:2391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778720,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769040,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:3070",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769040,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776736,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:3091",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776736,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869744,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:3658",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869744,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985952,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:3757",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985952,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void send_call_function_single_ipi(int cpu)
```

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147008,
      "name": "send_call_function_single_ipi",
      "external": true,
      "loc": "kernel/sched/core.c:3821",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147008,
      "name": "send_call_function_single_ipi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581000155,
      "name": "send_call_function_single_ipi",
      "external": false,
      "loc": "kernel/smp.c:110",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:__smp_call_single_queue"
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
  "name": "send_call_function_single_ipi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581096299,
      "name": "send_call_function_single_ipi",
      "external": false,
      "loc": "kernel/smp.c:112",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:__smp_call_single_queue"
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
void send_call_function_single_ipi(int cpu)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void send_call_function_single_ipi(int cpu)
```
</details>
</li>
</ul>
