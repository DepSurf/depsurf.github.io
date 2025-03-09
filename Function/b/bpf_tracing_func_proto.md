# Function: <code>bpf_tracing_func_proto</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_tracing_func_proto",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1058",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856571,
      "name": "bpf_tracing_func_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580853904,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_tracing_func_proto",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1271",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322521,
      "name": "bpf_tracing_func_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580845712,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_tracing_func_proto",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:952",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591264340,
      "name": "bpf_tracing_func_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580849264,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1021",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048304,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
    },
    {
      "addr": 18446744071592178160,
      "name": "bpf_tracing_func_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1185",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304496,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1523
    },
    {
      "addr": 18446744071593951901,
      "name": "bpf_tracing_func_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631616,
      "name": "bpf_tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1391",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631616,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2016
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
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773152,
      "name": "bpf_tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1404",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773152,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892608,
      "name": "bpf_tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1505",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892608,
      "name": "bpf_tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
const struct bpf_func_proto * bpf_tracing_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
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
