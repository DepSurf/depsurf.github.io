# Function: <code>xfrm_policy_inexact_insert</code>

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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809328,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1166",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809328,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1170",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242832,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
    },
    {
      "addr": 18446744071589255252,
      "name": "xfrm_policy_inexact_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589468192,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468192,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590458160,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1175",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590458160,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590516560,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1185",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590516560,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590441840,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1184",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590441840,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591241600,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1186",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241600,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592907888,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1186",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592907888,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594788704,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1187",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594788704,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595180928,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1187",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595180928,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596021616,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1202",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021616,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503119752,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503119752,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235806572,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235806572,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296831552,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296831552,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279167720,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279167720,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589072560,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589072560,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797600,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797600,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509424,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509424,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
```

```json
{
  "name": "xfrm_policy_inexact_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589556224,
      "name": "xfrm_policy_inexact_insert",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589556224,
      "name": "xfrm_policy_inexact_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
struct xfrm_policy * xfrm_policy_inexact_insert(struct xfrm_policy * policy, u8 dir, int excl)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
