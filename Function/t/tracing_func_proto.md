# Function: <code>tracing_func_proto</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369488,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:379",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369488,
      "name": "tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417264,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:398",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417264,
      "name": "tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429152,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:462",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429152,
      "name": "tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485024,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:506",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485024,
      "name": "tracing_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:528",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571392,
      "name": "tracing_func_proto.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071580573801,
      "name": "tracing_func_proto.isra.7.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:564",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629408,
      "name": "tracing_func_proto.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071580632089,
      "name": "tracing_func_proto.isra.12.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:661",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690240,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580693547,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737200,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580740571,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492043904,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492043904,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225947228,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225947228,
      "name": "tracing_func_proto.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285218288,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285218288,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706000,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580709371,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652208,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580655579,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697248,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580700619,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracing_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:685",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:raw_tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:pe_prog_func_proto",
        "kernel/trace/bpf_trace.c:tp_prog_func_proto",
        "kernel/trace/bpf_trace.c:kprobe_prog_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752832,
      "name": "tracing_func_proto.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071580758571,
      "name": "tracing_func_proto.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```
</details>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
const struct bpf_func_proto * tracing_func_proto(enum bpf_func_id func_id)
```
</details>
</li>
</ul>
