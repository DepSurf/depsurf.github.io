# Function: <code>xfrm_policy_inexact_alloc_chain</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588795312,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1106",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795312,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589226496,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1110",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226496,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589451760,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589451760,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590440816,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1115",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590440816,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590498912,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1125",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590498912,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590424112,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1124",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590424112,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591222432,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1126",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591222432,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592885568,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1126",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592885568,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594764944,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1127",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594764944,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595157072,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1127",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595157072,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596000096,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1142",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596000096,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503107008,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503107008,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235789628,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235789628,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296822608,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296822608,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279159520,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279159520,
      "name": "xfrm_policy_inexact_alloc_chain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589056128,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056128,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781168,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781168,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589492992,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589492992,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```

```json
{
  "name": "xfrm_policy_inexact_alloc_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589539632,
      "name": "xfrm_policy_inexact_alloc_chain",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589539632,
      "name": "xfrm_policy_inexact_alloc_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```
</details>
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
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hlist_head * xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin * bin, struct xfrm_policy * policy, u8 dir)
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
