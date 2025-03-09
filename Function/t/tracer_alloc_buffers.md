# Function: <code>tracer_alloc_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595114073,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:7197",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595283435,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:7605",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595530001,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:7891",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596450033,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:8263",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602776000,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:8360",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602950057,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:8465",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747971,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:8539",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604849193,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9044",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604849193,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 848
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604883271,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604883271,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 876
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
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609211072,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9386",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609211072,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 840
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612277925,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9519",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612277925,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614417270,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9841",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614417270,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615354008,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:10003",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615354008,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 973
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617140437,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:10049",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617140437,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 983
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627818640,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:10144",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627818640,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619582368,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:10382",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619582368,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621885776,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:10577",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621885776,
      "name": "tracer_alloc_buffers.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1060
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510920712,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510920712,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 688
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243408800,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243408800,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 752
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302561192,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302561192,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 912
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270655008,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270655008,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 790
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604788728,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604788728,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 876
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604757656,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604757656,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 876
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604865915,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604865915,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 876
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
int tracer_alloc_buffers()
```

```json
{
  "name": "tracer_alloc_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604887452,
      "name": "tracer_alloc_buffers",
      "external": false,
      "loc": "kernel/trace/trace.c:9100",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604887452,
      "name": "tracer_alloc_buffers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 876
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
int tracer_alloc_buffers()
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
int tracer_alloc_buffers()
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
