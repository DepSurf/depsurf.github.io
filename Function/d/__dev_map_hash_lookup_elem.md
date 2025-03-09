# Function: <code>__dev_map_hash_lookup_elem</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580939691,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941360,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103057,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:275",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103552,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581130529,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:261",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131024,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581150721,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:260",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581385672,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:266",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581708526,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:267",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582115127,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:267",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582311227,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:264",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582472251,
      "name": "__dev_map_hash_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:263",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_hash_map_redirect",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492282748,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492283224,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226168252,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226170636,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285513212,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285515840,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272414874,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272416834,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580908491,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910160,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580854555,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856224,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899739,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901408,
      "name": "__dev_map_hash_lookup_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```

```json
{
  "name": "__dev_map_hash_lookup_elem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580958459,
      "name": "__dev_map_hash_lookup_elem",
      "external": true,
      "loc": "kernel/bpf/devmap.c:290",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_hash_lookup_elem",
        "kernel/bpf/devmap.c:dev_map_hash_get_next_key"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_redirect_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960128,
      "name": "__dev_map_hash_lookup_elem",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
```
</details>
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
struct bpf_dtab_netdev * __dev_map_hash_lookup_elem(struct bpf_map * map, u32 key)
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
