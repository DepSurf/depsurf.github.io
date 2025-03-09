# Function: <code>xfrm_policy_insert_inexact_list</code>

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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588809487,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1489",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589242990,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1495",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589468353,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590436064,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1491",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590436064,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590494528,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1501",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590494528,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590420016,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1500",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590420016,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218256,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1502",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218256,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592880624,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1502",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592880624,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594759520,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1503",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594759520,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595151920,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1503",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595151920,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
```

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595994048,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1519",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994048,
      "name": "xfrm_policy_insert_inexact_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503119868,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235806688,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296831692,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279167814,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589072721,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588797761,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589509585,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
  "name": "xfrm_policy_insert_inexact_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589556385,
      "name": "xfrm_policy_insert_inexact_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1497",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
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
void xfrm_policy_insert_inexact_list(struct hlist_head * chain, struct xfrm_policy * policy)
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
