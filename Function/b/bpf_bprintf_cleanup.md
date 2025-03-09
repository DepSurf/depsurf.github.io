# Function: <code>bpf_bprintf_cleanup</code>

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
void bpf_bprintf_cleanup()
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581048738,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:727",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046960,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void bpf_bprintf_cleanup()
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581273010,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:741",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271184,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void bpf_bprintf_cleanup()
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581565677,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:802",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563696,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bpf_bprintf_cleanup()
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938845,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:787",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936832,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void bpf_bprintf_cleanup(struct bpf_bprintf_data * data)
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120448,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:788",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120448,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void bpf_bprintf_cleanup(struct bpf_bprintf_data * data)
```

```json
{
  "name": "bpf_bprintf_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260976,
      "name": "bpf_bprintf_cleanup",
      "external": true,
      "loc": "kernel/bpf/helpers.c:794",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/helpers.c:bpf_snprintf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260976,
      "name": "bpf_bprintf_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void bpf_bprintf_cleanup()
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_bprintf_data * data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
