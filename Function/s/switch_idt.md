# Function: <code>switch_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void switch_idt(void * arg)
```

```json
{
  "name": "switch_idt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579263920,
      "name": "switch_idt",
      "external": false,
      "loc": "arch/x86/kernel/tracepoint.c:28",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263920,
      "name": "switch_idt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void switch_idt(void * arg)
```

```json
{
  "name": "switch_idt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579263296,
      "name": "switch_idt",
      "external": false,
      "loc": "arch/x86/kernel/tracepoint.c:28",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263296,
      "name": "switch_idt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void switch_idt(void * arg)
```

```json
{
  "name": "switch_idt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276896,
      "name": "switch_idt",
      "external": false,
      "loc": "arch/x86/kernel/tracepoint.c:28",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276896,
      "name": "switch_idt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void switch_idt(void * arg)
```

```json
{
  "name": "switch_idt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273424,
      "name": "switch_idt",
      "external": false,
      "loc": "arch/x86/kernel/tracepoint.c:28",
      "file": "arch/x86/kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273424,
      "name": "switch_idt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void switch_idt(void * arg)
```
</details>
</li>
</ul>
