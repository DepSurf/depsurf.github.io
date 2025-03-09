# Function: <code>strncpy_from_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489248,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489248,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573248,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573248,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639680,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639680,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672224,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672224,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757408,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757408,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893472,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:fetch_memory_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893472,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968112,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:86",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968112,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063408,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:124",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063408,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119376,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119376,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492489704,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492489704,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226361544,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226361544,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285775600,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285775600,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272552284,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272552284,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088224,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088224,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035408,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035408,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079424,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079424,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
```

```json
{
  "name": "strncpy_from_unsafe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141312,
      "name": "strncpy_from_unsafe",
      "external": true,
      "loc": "mm/maccess.c:161",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_probe_read_str",
        "kernel/trace/bpf_trace.c:bpf_trace_printk",
        "kernel/trace/trace_kprobe.c:process_fetch_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141312,
      "name": "strncpy_from_unsafe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int strncpy_from_unsafe(char * dst, const void * unsafe_addr, long int count)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
