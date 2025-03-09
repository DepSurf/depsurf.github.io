# Function: <code>__dev_map_alloc_node</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939152,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939152,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099712,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:598",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099712,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127344,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:583",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127344,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147264,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:576",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147264,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381328,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:848",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381328,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703920,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:839",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703920,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110272,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:839",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110272,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306288,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:848",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306288,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, struct bpf_devmap_val * val, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467360,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:857",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:__dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467360,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492279384,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492279384,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226167856,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226167856,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285512272,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285512272,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272414364,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272414364,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907952,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907952,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854016,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854016,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580899200,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580899200,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```

```json
{
  "name": "__dev_map_alloc_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957920,
      "name": "__dev_map_alloc_node",
      "external": false,
      "loc": "kernel/bpf/devmap.c:584",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957920,
      "name": "__dev_map_alloc_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct bpf_dtab_netdev * __dev_map_alloc_node(struct net * net, struct bpf_dtab * dtab, u32 ifindex, unsigned int idx)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_devmap_val * val</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ifindex</code>
</li>
</ul>
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
