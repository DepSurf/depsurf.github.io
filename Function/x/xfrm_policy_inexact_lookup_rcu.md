# Function: <code>xfrm_policy_inexact_lookup_rcu</code>

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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588806262,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1973",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589239806,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1979",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589465166,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590456016,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1972",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590456016,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590514805,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1982",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590514464,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590440101,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590439760,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591239845,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1982",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239504,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592904242,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1982",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594784466,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2053",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595174482,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2055",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596003529,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2075",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503125620,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235801752,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235801752,
      "name": "xfrm_policy_inexact_lookup_rcu",
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
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296837752,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279174092,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589069534,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588794574,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589506398,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_inexact_lookup_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589553019,
      "name": "xfrm_policy_inexact_lookup_rcu",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1981",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct xfrm_pol_inexact_bin * xfrm_policy_inexact_lookup_rcu(struct net * net, u8 type, u16 family, u8 dir, u32 if_id)
```
</details>
</li>
</ul>
