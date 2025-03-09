# Function: <code>perf_event_bpf_emit_ksymbols</code>

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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979632,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:7903",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979632,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033760,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033760,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581213815,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8570",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581256647,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8752",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274663,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8881",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581515815,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:9000",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581862365,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8905",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582289485,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:9182",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582490509,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:9210",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582659149,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:9280",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_bpf_event"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492385632,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492385632,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226272908,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226272908,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285644896,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285644896,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272497326,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272497326,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002608,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002608,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948768,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948768,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993808,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993808,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
```

```json
{
  "name": "perf_event_bpf_emit_ksymbols",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054864,
      "name": "perf_event_bpf_emit_ksymbols",
      "external": false,
      "loc": "kernel/events/core.c:8019",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_bpf_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054864,
      "name": "perf_event_bpf_emit_ksymbols",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
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
void perf_event_bpf_emit_ksymbols(struct bpf_prog * prog, enum perf_bpf_event_type type)
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
