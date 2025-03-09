# Function: <code>strncpy_from_user_nofault</code>

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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303568,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:270",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303568,
      "name": "strncpy_from_user_nofault",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346624,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:268",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346624,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365600,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:268",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365600,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613984,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:284",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:filter_pred_pchar_user",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613984,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974592,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:171",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:filter_pred_pchar_user",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974592,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409344,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:171",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409344,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615328,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:177",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615328,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_user_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786848,
      "name": "strncpy_from_user_nofault",
      "external": true,
      "loc": "mm/maccess.c:177",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_user_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786848,
      "name": "strncpy_from_user_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long int strncpy_from_user_nofault(char * dst, const void * unsafe_addr, long int count)
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
