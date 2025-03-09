# Function: <code>xfrm_policy_insert_list</code>

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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588790320,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1525",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588790320,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1531",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222768,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071589255024,
      "name": "xfrm_policy_insert_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448048,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448048,
      "name": "xfrm_policy_insert_list",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590444864,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1527",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590444864,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590502960,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1537",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590502960,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590427536,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1536",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590427536,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591226192,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1538",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591226192,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592893056,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1538",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592893056,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594772992,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1539",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594772992,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595166320,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1539",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595166320,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596009440,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1555",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596009440,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503102728,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503102728,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235784984,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235784984,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296816304,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296816304,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279155304,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279155304,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589052416,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589052416,
      "name": "xfrm_policy_insert_list",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777456,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777456,
      "name": "xfrm_policy_insert_list",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489280,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489280,
      "name": "xfrm_policy_insert_list",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
```

```json
{
  "name": "xfrm_policy_insert_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589535520,
      "name": "xfrm_policy_insert_list",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1533",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589535520,
      "name": "xfrm_policy_insert_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
struct xfrm_policy * xfrm_policy_insert_list(struct hlist_head * chain, struct xfrm_policy * policy, bool excl)
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
