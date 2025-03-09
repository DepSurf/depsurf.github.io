# Function: <code>__flush_smp_call_function_queue</code>

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
void __flush_smp_call_function_queue(bool warn_cpu_offline)
```

```json
{
  "name": "__flush_smp_call_function_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_smp_call_function_queue",
      "external": false,
      "loc": "kernel/smp.c:564",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_smp_call_function_single_interrupt",
        "kernel/smp.c:smpcfd_dying_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646032,
      "name": "__flush_smp_call_function_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071593933056,
      "name": "__flush_smp_call_function_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void __flush_smp_call_function_queue(bool warn_cpu_offline)
```

```json
{
  "name": "__flush_smp_call_function_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_smp_call_function_queue",
      "external": false,
      "loc": "kernel/smp.c:563",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_smp_call_function_single_interrupt",
        "kernel/smp.c:smpcfd_dying_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912848,
      "name": "__flush_smp_call_function_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071595999098,
      "name": "__flush_smp_call_function_queue.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline)
```

```json
{
  "name": "__flush_smp_call_function_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_smp_call_function_queue",
      "external": false,
      "loc": "kernel/smp.c:430",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_smp_call_function_single_interrupt",
        "kernel/smp.c:smpcfd_dying_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000784,
      "name": "__flush_smp_call_function_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1061
    },
    {
      "addr": 18446744071596517237,
      "name": "__flush_smp_call_function_queue.cold",
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
void __flush_smp_call_function_queue(bool warn_cpu_offline)
```

```json
{
  "name": "__flush_smp_call_function_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_smp_call_function_queue",
      "external": false,
      "loc": "kernel/smp.c:445",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_smp_call_function_single_interrupt",
        "kernel/smp.c:smpcfd_dying_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096928,
      "name": "__flush_smp_call_function_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
    },
    {
      "addr": 18446744071597417189,
      "name": "__flush_smp_call_function_queue.cold",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __flush_smp_call_function_queue(bool warn_cpu_offline)
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
