# Function: <code>raw_tp_prog_func_proto</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571760,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:840",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571760,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629888,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:876",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629888,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690832,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1025",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690832,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737792,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737792,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580854959,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1492",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854752,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580847123,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1721",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846784,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580850944,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1415",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850592,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050205,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1492",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049824,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307276,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1671",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306336,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581634956,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1888",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633984,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775628,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1897",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775328,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895116,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:2002",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894816,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492044560,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492044560,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225948156,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225948156,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285219424,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285219424,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706592,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706592,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652800,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652800,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697840,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697840,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "raw_tp_prog_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753424,
      "name": "raw_tp_prog_func_proto",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:1049",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753424,
      "name": "raw_tp_prog_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
const struct bpf_func_proto * raw_tp_prog_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
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
