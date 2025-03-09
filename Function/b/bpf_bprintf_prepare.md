# Function: <code>bpf_bprintf_prepare</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 * * bin_args, u32 num_args)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046992,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:749",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046992,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1594
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 * * bin_args, u32 num_args)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271216,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:763",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271216,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1637
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 * * bin_args, u32 num_args)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563760,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:824",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563760,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1741
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 * * bin_args, u32 num_args)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936912,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:809",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936912,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1740
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 num_args, struct bpf_bprintf_data * data)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:812",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596542183,
      "name": "bpf_bprintf_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071582120560,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2034
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 num_args, struct bpf_bprintf_data * data)
```

```json
{
  "name": "bpf_bprintf_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_bprintf_prepare",
      "external": true,
      "loc": "kernel/bpf/helpers.c:818",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/bpf/helpers.c:bpf_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597445088,
      "name": "bpf_bprintf_prepare.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071582261088,
      "name": "bpf_bprintf_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2034
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
int bpf_bprintf_prepare(char * fmt, u32 fmt_size, const u64 * raw_args, u32 * * bin_args, u32 num_args)
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
<li>
<b>Param removed. </b>
<code>u32 * * bin_args</code>
</li>
<li>
<b>Param reordered. </b>
<code>fmt, fmt_size, raw_args, bin_args, num_args</code> ➡️ <code>fmt, fmt_size, raw_args, num_args, data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
