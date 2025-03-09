# Function: <code>xfrm_policy_lookup_inexact_addr</code>

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
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588793941,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1902",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793728,
      "name": "xfrm_policy_lookup_inexact_addr.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224768,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1908",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224768,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589450032,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450032,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590438944,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1901",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590438944,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590494976,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1911",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590494976,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590420464,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590420464,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218704,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1911",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218704,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592881136,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1911",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592881136,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594760080,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1982",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594760080,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595152480,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1984",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595152480,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_spinlock_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595994608,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:2004",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994608,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503103632,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503103632,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235787100,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235787100,
      "name": "xfrm_policy_lookup_inexact_addr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296820336,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296820336,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279155978,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279155978,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589054400,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054400,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588779440,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779440,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589491264,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589491264,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```

```json
{
  "name": "xfrm_policy_lookup_inexact_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589537904,
      "name": "xfrm_policy_lookup_inexact_addr",
      "external": false,
      "loc": "net/xfrm/xfrm_policy.c:1910",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates",
        "net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537904,
      "name": "xfrm_policy_lookup_inexact_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct xfrm_pol_inexact_node * xfrm_policy_lookup_inexact_addr(const struct rb_root * r, seqcount_t * count, const xfrm_address_t * addr, u16 family)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>seqcount_t * count</code> ➡️ <code>seqcount_spinlock_t * count</code>
</li>
</ul>
</details>
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
