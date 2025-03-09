# Function: <code>btf_type_needs_resolve</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580717211,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:357",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580795376,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:385",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec"
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868432,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868432,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919392,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919392,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581072256,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:469",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072256,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581086960,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:558",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086960,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581106080,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:559",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106080,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336176,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:559",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336176,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581642688,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:647",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642688,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582034160,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:642",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034160,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582229280,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:665",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229280,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385232,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:666",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385232,
      "name": "btf_type_needs_resolve.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492254296,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492254296,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226145996,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226145996,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285483408,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285483408,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272395370,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272395370,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888192,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888192,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834256,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834256,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879440,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879440,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool btf_type_needs_resolve(const struct btf_type * t)
```

```json
{
  "name": "btf_type_needs_resolve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938080,
      "name": "btf_type_needs_resolve",
      "external": false,
      "loc": "kernel/bpf/btf.c:425",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938080,
      "name": "btf_type_needs_resolve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
bool btf_type_needs_resolve(const struct btf_type * t)
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
bool btf_type_needs_resolve(const struct btf_type * t)
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
