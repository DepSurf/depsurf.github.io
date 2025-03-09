# Function: <code>__dev_map_lookup_elem</code>

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
struct net_device * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580610552,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:249",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:__xdp_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612208,
      "name": "__dev_map_lookup_elem",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580718968,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:301",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:__xdp_map_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721104,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580799096,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:302",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801248,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886728,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:283",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888896,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937880,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941536,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581099288,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:409",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103760,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581126920,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:395",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131232,
      "name": "__dev_map_lookup_elem",
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581147038,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:388",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581380951,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:428",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581703563,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:429",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582109707,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:429",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305675,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:426",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582466747,
      "name": "__dev_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:435",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_redirect",
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492278760,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492283432,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226166868,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226170820,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285510252,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285516112,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272413232,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272417022,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580906680,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910336,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852744,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856400,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580897928,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901584,
      "name": "__dev_map_lookup_elem",
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
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580956600,
      "name": "__dev_map_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:421",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_lookup_elem"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960320,
      "name": "__dev_map_lookup_elem",
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
struct net_device * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct net_device *</code> ➡️ <code>struct bpf_dtab_netdev *</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct bpf_dtab_netdev * __dev_map_lookup_elem(struct bpf_map * map, u32 key)
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
