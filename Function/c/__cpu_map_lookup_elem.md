# Function: <code>__cpu_map_lookup_elem</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580612264,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:551",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:__xdp_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615344,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580721576,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:514",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:__xdp_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724608,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580801736,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:516",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804736,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580889464,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893104,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580942104,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945744,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104600,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:509",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108144,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581132072,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:608",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136544,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581152286,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:565",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581388913,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:630",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581711870,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:633",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582118350,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:632",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582314526,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:643",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582475550,
      "name": "__cpu_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:597",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_redirect",
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492284272,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492288416,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226171384,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226175208,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285516892,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285522192,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272417584,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272421064,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580910904,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914544,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580856968,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860608,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580902152,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905792,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__cpu_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580960888,
      "name": "__cpu_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:555",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964544,
      "name": "__cpu_map_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_lookup_elem(struct bpf_map * map, u32 key)
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
