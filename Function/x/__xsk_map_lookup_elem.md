# Function: <code>__xsk_map_lookup_elem</code>

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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726032,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:112",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__xdp_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726032,
      "name": "__xsk_map_lookup_elem",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806176,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:113",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806176,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893640,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:111",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894592,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946280,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947744,
      "name": "__xsk_map_lookup_elem",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589501499,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "include/net/xdp_sock.h:84",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591071432,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "include/net/xdp_sock.h:84",
      "file": "net/xdp/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589503899,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "include/net/xdp_sock.h:83",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591135016,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "include/net/xdp_sock.h:83",
      "file": "net/xdp/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591065950,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:127",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591908833,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:131",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593629694,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:133",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595559790,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:133",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596068062,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:141",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596936062,
      "name": "__xsk_map_lookup_elem",
      "external": false,
      "loc": "net/xdp/xskmap.c:141",
      "file": "net/xdp/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xskmap.c:xsk_map_redirect",
        "net/xdp/xskmap.c:xsk_map_lookup_elem"
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492289232,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492291224,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226175736,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226177180,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285522956,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285525264,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272421656,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272423042,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915080,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916544,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580861144,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862608,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580906328,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907792,
      "name": "__xsk_map_lookup_elem",
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
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__xsk_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580965080,
      "name": "__xsk_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:163",
      "file": "kernel/bpf/xskmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966544,
      "name": "__xsk_map_lookup_elem",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct xdp_sock * __xsk_map_lookup_elem(struct bpf_map * map, u32 key)
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
