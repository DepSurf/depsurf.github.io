# Function: <code>sock_map_link</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588224720,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:147",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224720,
      "name": "sock_map_link.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588561760,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588561760,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588778848,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778848,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
int sock_map_link(struct bpf_map * map, struct sk_psock_progs * progs, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589653392,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:229",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589653392,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int sock_map_link(struct bpf_map * map, struct sk_psock_progs * progs, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589678240,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:224",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589678240,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660432,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:216",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660432,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1414
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590417872,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:217",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590417872,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592015616,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:217",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592015616,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1437
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593831248,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:217",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593831248,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1437
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594205760,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:213",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205760,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1445
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
int sock_map_link(struct bpf_map * map, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595003136,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:213",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595003136,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1445
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502346400,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502346400,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
int sock_map_link(struct bpf_map * map, struct sk_psock_progs * progs, struct sock * sk)
```

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235085480,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235085480,
      "name": "sock_map_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295869200,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295869200,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278565298,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278565298,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588385232,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588385232,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588097920,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097920,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588717408,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717408,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
  "name": "sock_map_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588857808,
      "name": "sock_map_link",
      "external": false,
      "loc": "net/core/sock_map.c:142",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857808,
      "name": "sock_map_link.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sock_map_link(struct bpf_map * map, struct sk_psock_progs * progs, struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sk_psock_progs * progs</code>
</li>
<li>
<b>Param reordered. </b>
<code>map, progs, sk</code> ➡️ <code>map, sk</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int sock_map_link(struct bpf_map * map, struct sk_psock_progs * progs, struct sock * sk)
```
</details>
</li>
</ul>
