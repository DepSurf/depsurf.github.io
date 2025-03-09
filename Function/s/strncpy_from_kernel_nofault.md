# Function: <code>strncpy_from_kernel_nofault</code>

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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303392,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:65",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303392,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346448,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:65",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346448,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365424,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:65",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365424,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613808,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:81",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_filter.c:filter_pred_pchar",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613808,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974368,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:79",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_filter.c:filter_pred_pchar",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974368,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409104,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:79",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409104,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615088,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:80",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615088,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786608,
      "name": "strncpy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:80",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat_str",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786608,
      "name": "strncpy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int strncpy_from_kernel_nofault(char * dst, const void * unsafe_addr, long int count)
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
