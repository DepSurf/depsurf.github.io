# Function: <code>get_bpf_raw_tp_regs</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684640,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:927",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684640,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731664,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731664,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853024,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1391",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580844790,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1620",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580848355,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1314",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581047651,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1391",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303523,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1569",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581630579,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1786",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581770574,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1795",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581889742,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1900",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492046896,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492046896,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225946784,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225946784,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285218048,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285218048,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700464,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700464,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646672,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646672,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691712,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691712,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```

```json
{
  "name": "get_bpf_raw_tp_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749216,
      "name": "get_bpf_raw_tp_regs",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:951",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749216,
      "name": "get_bpf_raw_tp_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pt_regs * get_bpf_raw_tp_regs()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
